# 📌 Práctica PSP — Aleatorios & Ordenar Números

> Proyecto de la asignatura **Programación de Servicios y Procesos (PSP)**.  
> Consiste en dos aplicaciones Java que interactúan mediante **entrada/salida estándar** y el uso de **tuberías (`|`)** en consola.

---

## 📂 Estructura del proyecto

```
📦 actividad1_tema3
 ┣ 📜 Aleatorios.java
 ┣ 📜 OrdenarNumeros.java
 ┗ 📜 README.md
```

---

## 🎯 Objetivos

- Generar números aleatorios desde un proceso.
- Ordenar un conjunto indeterminado de números recibidos desde **entrada estándar**.
- Usar **tuberías** (`|`) para encadenar procesos.
- Documentar el código con **Javadoc**.
- Elaborar un pequeño manual de uso con capturas y ejemplos.

---

## ⚙️ Instalación y compilación

1. Clonar el repositorio:

```bash
git clone https://github.com/tuusuario/psp-actividad1.git
cd psp-actividad1/src/main/java
```

2. Compilar las clases (con paquete `actividad1_tema3`):

```bash
javac actividad1_tema3/Aleatorios.java actividad1_tema3/OrdenarNumeros.java
```

---

## 🚀 Ejecución

### ▶️ Generar números aleatorios
```bash
java actividad1_tema3.Aleatorios
```
👉 Por defecto genera **40 números** entre 0 y 100.

Con parámetro:
```bash
java actividad1_tema3.Aleatorios 10
```
👉 Genera 10 números.

---

### ▶️ Ordenar números introducidos manualmente
```bash
java actividad1_tema3.OrdenarNumeros
```
Introduce valores (ejemplo):
```
34 7 98 0 23
```

Finaliza con:
- **Ctrl+D** (Linux/Mac)
- **Ctrl+Z + Enter** (Windows)

👉 Salida:
```
0
7
23
34
98
```

---

### ▶️ Usar tubería (`|`)
```bash
java actividad1_tema3.Aleatorios 50 | java actividad1_tema3.OrdenarNumeros
```
👉 Los 50 números generados se ordenan automáticamente.

---

## 📖 Generar Javadoc

```bash
javadoc -d doc actividad1_tema3/Aleatorios.java actividad1_tema3/OrdenarNumeros.java
```

Abrir en navegador:
```
doc/index.html
```

---

## 🖼️ Capturas sugeridas (para informe)

- ✅ Compilación sin errores  
- ✅ Ejecución de `Aleatorios`  
- ✅ Ejecución de `OrdenarNumeros` con entrada manual  
- ✅ Ejemplo con tubería  
- ✅ Documentación Javadoc en navegador  

---

## 📝 Autor

👤 **Alberto Agredano**  
💻 Diseñador Web & Desarrollador  
📍 Sevilla, España  

---

✨ _Este proyecto forma parte de las prácticas de la asignatura PSP. El objetivo es aprender a trabajar con procesos, entrada/salida estándar y documentación en Java._  
