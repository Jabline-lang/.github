<div align="center">
  <img src="assets/jabline.png" alt="Jabline Logo" width="100">
  
  # **Jabline Programming Language**
  
  *A powerful, modern interpreted language for rapid development and system integration*
  
  [![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://github.com/Jabline-lang/Jabline)
  [![License](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/Jabline-lang/Jabline/blob/main/LICENSE)
  [![Go](https://img.shields.io/badge/go-1.24.6-00ADD8.svg)](https://golang.org/)
</div>

---

## 🎯 **What is Jabline?**

**Jabline** is a modern interpreted programming language designed for developers who need powerful built-in capabilities without external dependencies. With syntax inspired by JavaScript and Python, Jabline provides native JSON processing, comprehensive mathematical functions, pattern matching, and professional-grade debugging tools.

### ✨ **Key Features**

- **🔧 Rich Standard Library** - 70+ built-in functions covering JSON, mathematics, regex, HTTP, and file operations
- **📊 Native JSON Support** - Built-in `stringify()` and `parse()` functions for seamless data processing
- **🧮 Scientific Computing** - Complete mathematical function library with trigonometry, logarithms, and constants
- **🔍 Pattern Matching** - Integrated regex operations and common validation functions
- **🐛 Advanced Debugging** - Colored output, stack traces, assertions, and intelligent error suggestions
- **🌐 HTTP Integration** - Built-in web client for API consumption and data fetching
- **⚡ High Performance** - Go-powered interpreter optimized for speed and reliability
- **📁 File System Operations** - Comprehensive file and directory management capabilities

---

## 🚀 **Quick Example**

```jabline
// Data processing with built-in functions
let userData = {"name": "Alice", "email": "alice@example.com", "scores": [85, 92, 78]};

// JSON operations
let json = stringify(userData);
let parsed = parse(json);

// Mathematical calculations
let average = (85 + 92 + 78) / 3;
let standardDev = sqrt(pow(85 - average, 2) + pow(92 - average, 2) + pow(78 - average, 2));

// Validation
if (isEmail(userData["email"])) {
    echo("Valid user email");
}

// Debugging and assertions
debug("Processing user:", userData["name"]);
assert(average > 80, "User has good performance");
```

---

## 🛠️ **Language Capabilities**

### **Data Processing**
- **JSON Integration** - Native parsing and serialization without external libraries
- **String Operations** - Case conversion, splitting, joining, pattern matching
- **Array Manipulation** - Sorting, filtering, transformation, and aggregation
- **Hash Operations** - Key-value processing, merging, and iteration

### **Mathematical Computing**
- **Basic Functions** - `abs()`, `sqrt()`, `pow()`, `min()`, `max()`
- **Trigonometry** - Complete sine, cosine, tangent functions and inverses
- **Logarithms** - Natural, base-10, and base-2 logarithmic functions
- **Utilities** - Rounding, factorial, random number generation
- **Constants** - Mathematical constants like Pi and E

### **Pattern Matching & Validation**
- **Common Validations** - Email, URL, and phone number verification
- **Regex Operations** - Pattern testing, matching, and replacement
- **Text Processing** - Advanced string manipulation and analysis

### **System Integration**
- **File Operations** - Reading, writing, and managing files and directories
- **HTTP Client** - GET and POST requests with automatic response parsing
- **Environment Access** - System environment variable management
- **Process Control** - Input/output operations and system interaction

### **Development Tools**
- **Debugging Suite** - Colored debug output, execution tracing, and assertions
- **Error Handling** - Professional error messages with suggestions and context
- **Performance Monitoring** - Stack traces and execution analysis
- **Testing Support** - Built-in assertion framework for quality assurance

---

## 🏗️ **Architecture & Design**

Jabline is engineered for both performance and developer experience:

- **Modular Design** - Clean separation between lexing, parsing, and evaluation
- **Extensible Built-ins** - Easy addition of new functions and capabilities  
- **Memory Efficient** - Optimized object system with automatic cleanup
- **Error Recovery** - Graceful handling of syntax and runtime errors
- **Cross-Platform** - Consistent behavior across Windows, macOS, and Linux

---

## 💼 **Use Cases**

### **Data Analysis & Processing**
Perfect for JSON data manipulation, statistical calculations, and report generation

### **System Automation**
Ideal for scripting file operations, system monitoring, and task automation

### **API Integration**  
Built-in HTTP client and JSON processing make API consumption seamless

### **Rapid Prototyping**
Rich built-in library enables quick development without dependency management

### **Educational Projects**
Clear syntax and helpful error messages make it excellent for learning programming concepts

---

## 🚀 **Getting Started**

```bash
# Clone and build
git clone https://github.com/Jabline-lang/Jabline.git
cd Jabline && cd builder && go run .

# Create your first program
echo 'echo("Hello, Jabline!");' > hello.jb
jabline run hello.jb
```

### **Language Highlights**

```jabline
// Variables and functions
let name = "Jabline";
const VERSION = "1.0.0";

fn processData(input) {
    return stringify({"processed": true, "input": input});
}

// Built-in capabilities
let result = abs(-15) + sqrt(25) + pow(2, 3);
let valid = isEmail("user@domain.com");
debug("Result:", result, "Valid:", valid);
```

---

## 📊 **Performance & Reliability**

- **Production Ready** - Comprehensive error handling and debugging tools
- **High Performance** - Go-based interpreter with optimized execution
- **Memory Safe** - Automatic memory management with garbage collection
- **Robust Parsing** - Advanced error recovery and intelligent suggestions
- **Extensive Testing** - Comprehensive test suite ensuring code quality

---

## 🌟 **Why Choose Jabline?**

### **Zero Dependencies**
All essential functions built-in - no external libraries needed for common tasks

### **Developer Experience**  
Professional debugging tools with colored output and intelligent error messages

### **Rapid Development**
Rich standard library eliminates boilerplate and accelerates development

### **Modern Syntax**
Familiar language constructs that developers can learn quickly

### **Versatile Applications**
Suitable for scripting, data processing, system integration, and rapid prototyping

---

## 🤝 **Community & Support**

- **📖 [Documentation](https://github.com/Jabline-lang/Jabline#documentation)** - Complete language reference and guides
- **💬 [Discussions](https://github.com/Jabline-lang/Jabline/discussions)** - Community support and feature requests  
- **🐛 [Issues](https://github.com/Jabline-lang/Jabline/issues)** - Bug reports and improvement suggestions
- **🔄 [Contributing](https://github.com/Jabline-lang/Jabline#contributing)** - Guidelines for code contributions

---

## 📄 **License**

Jabline is open-source software released under the [MIT License](https://github.com/Jabline-lang/Jabline/blob/main/LICENSE).

---

<div align="center">

**Jabline v1.0.0** - *Powerful Programming Made Simple*

**Built with ❤️ using Go**

[Get Started](https://github.com/Jabline-lang/Jabline#quick-start) • [Examples](https://github.com/Jabline-lang/Jabline/tree/main/examples) • [Community](https://github.com/Jabline-lang/Jabline/discussions)

</div>
