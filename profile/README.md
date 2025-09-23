<div align="center">
  <img src="assets/jabline.png" alt="Jabline Logo" width="100">
  
  # **Jabline Programming Language**
  
  *Un lenguaje de programación interpretado simple y expresivo*
  
  [![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://github.com/Jabline-lang/Jabline)
  [![License](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/Jabline-lang/Jabline/blob/main/LICENSE)
  [![Go](https://img.shields.io/badge/go-1.24.6-00ADD8.svg)](https://golang.org/)
</div>

---

## 🎯 **¿Qué es Jabline?**

**Jabline** es un lenguaje de programación interpretado diseñado para ser simple, expresivo y fácil de aprender. Con una sintaxis familiar inspirada en JavaScript y Python, Jabline permite a los desarrolladores crear scripts y programas de manera intuitiva.

### ✨ **Características Principales**

- **📝 Sintaxis Simple** - Fácil de leer y escribir
- **🔧 Funciones Built-in** - Más de 30 funciones integradas listas para usar
- **📁 Operaciones de Archivos** - Lectura, escritura y manipulación de archivos
- **🌐 Cliente HTTP** - Peticiones GET y POST integradas
- **📦 Sistema de Módulos** - Importa y exporta funciones entre archivos
- **⚡ Ejecución Rápida** - Intérprete optimizado escrito en Go

---

## 🚀 **Ejemplo Rápido**

```jabline
// Variables y tipos básicos
let nombre = "Jabline";
let version = 1.0;
let activo = true;

echo(`¡Bienvenido a ${nombre} v${version}!`);

// Funciones
fn saludar(usuario) {
    return `Hola ${usuario}, ¿cómo estás?`;
}

echo(saludar("Desarrollador"));

// Arrays y operaciones
let numeros = [1, 2, 3, 4, 5];
echo("Longitud: " + len(numeros));
echo("Primer elemento: " + first(numeros));
```

---

## 🛠️ **Funcionalidades Implementadas**

### **Variables y Tipos**
```jabline
let texto = "Hola mundo";
let numero = 42;
let decimal = 3.14;
let booleano = true;
let lista = [1, 2, 3];
let objeto = {"clave": "valor"};
```

### **Funciones y Control de Flujo**
```jabline
fn calcular(a, b) {
    if (a > b) {
        return a + b;
    } else {
        return a - b;
    }
}

// Bucles
for (let i = 0; i < 5; i++) {
    echo("Número: " + i);
}
```

### **Operaciones de Archivos**
```jabline
// Leer y escribir archivos
let contenido = readFile("datos.txt");
writeFile("salida.txt", "Nuevo contenido");

// Verificar existencia
if (fileExists("config.json")) {
    echo("Archivo encontrado");
}
```

### **Peticiones HTTP**
```jabline
// GET request
let respuesta = httpGet("https://api.ejemplo.com/datos");
echo("Status: " + respuesta["status"]);
echo("Contenido: " + respuesta["body"]);

// POST request
let datos = '{"nombre": "Juan"}';
let resultado = httpPost("https://api.ejemplo.com/usuarios", datos);
```

---

## 📚 **Funciones Built-in Disponibles**

### **Básicas**
- `echo(valor)` - Imprime valores
- `len(objeto)` - Longitud de arrays/strings
- `type(objeto)` - Tipo de un objeto

### **Strings**
- `upper(texto)`, `lower(texto)` - Convertir mayúsculas/minúsculas
- `split(texto, separador)` - Dividir string
- `join(array, separador)` - Unir array en string
- `contains(texto, buscar)` - Verificar contenido
- `replace(texto, buscar, reemplazar)` - Reemplazar texto

### **Arrays**
- `push(array, elemento)` - Agregar elemento
- `pop(array)` - Remover último elemento
- `first(array)`, `last(array)` - Primer/último elemento
- `reverse(array)` - Invertir array

### **Archivos y Sistema**
- `readFile(archivo)`, `writeFile(archivo, contenido)`
- `fileExists(archivo)`, `deleteFile(archivo)`
- `createDir(directorio)`, `listDir(directorio)`
- `getEnv(variable)`, `setEnv(variable, valor)`

### **HTTP y Red**
- `httpGet(url)`, `httpPost(url, datos)`

### **Tiempo**
- `now()` - Timestamp actual
- `sleep(milisegundos)` - Pausar ejecución
- `formatTime(timestamp, formato)` - Formatear fecha

---

## 📦 **Repositorios**

| Repositorio | Descripción | Estado |
|-------------|-------------|--------|
| **[Jabline](https://github.com/Jabline-lang/Jabline)** | Intérprete principal del lenguaje | ✅ Activo |

---

## 🏃 **Comenzar**

### **Instalación**
```bash
# Clonar el repositorio
git clone https://github.com/Jabline-lang/Jabline.git
cd Jabline

# Compilar el intérprete
cd builder && go run .

# Ejecutar un programa
jabline run ejemplo.jb
```

### **Tu Primer Programa**
```jabline
// Guarda esto como hola.jb
let mensaje = "¡Hola desde Jabline!";
echo(mensaje);

fn suma(a, b) {
    return a + b;
}

echo("2 + 3 = " + suma(2, 3));
```

```bash
# Ejecutar
jabline run hola.jb
```

---

## 🎯 **Casos de Uso**

- **🔧 Scripts de Automatización** - Tareas del sistema y procesamiento de archivos
- **🌐 APIs Simples** - Cliente HTTP para consumir servicios web
- **📊 Procesamiento de Datos** - Manipulación básica de texto y números
- **🧪 Prototipado Rápido** - Desarrollo y testing de ideas
- **📚 Aprendizaje** - Introducción a conceptos de programación

---

## 🤝 **Contribuir**

¡Las contribuciones son bienvenidas! 

- **🐛 [Reportar Bugs](https://github.com/Jabline-lang/Jabline/issues)** - Ayúdanos a mejorar
- **💡 [Sugerir Features](https://github.com/Jabline-lang/Jabline/discussions)** - Comparte tus ideas
- **🔄 [Pull Requests](https://github.com/Jabline-lang/Jabline/pulls)** - Contribuye código

---

## 📋 **Roadmap**

- ✅ **v1.0** - Lenguaje base con funciones esenciales
- 🚧 **v1.1** - Más módulos de la librería estándar
- 📋 **v1.2** - Mejor manejo de errores y debugging
- 🎯 **v2.0** - Optimizaciones de rendimiento

---

## 📄 **Licencia**

Jabline está licenciado bajo la [Licencia MIT](https://github.com/Jabline-lang/Jabline/blob/main/LICENSE).

---

<div align="center">
  
**Creado con ❤️ para la comunidad de desarrolladores**

[Comenzar](https://github.com/Jabline-lang/Jabline#instalación) • [Ejemplos](https://github.com/Jabline-lang/Jabline/tree/main/examples) • [Documentación](https://github.com/Jabline-lang/Jabline/blob/main/STDLIB_REFERENCE.md)

</div>
