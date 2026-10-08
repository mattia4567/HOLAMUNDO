# HOLAMUNDO
# 💻 Actividad 2: El Taller del Programador (Configuración de Entorno & C++)

**Integrantes** Del Pino, Mattia, Orue, Ferrari
**Materia:** Laboratorio de Programación (LPR) — 5° 3° A-B  
**Institución:** E.E.S.T. N° 1 "Eduardo Ader" — Vicente López  
**Ciclo Lectivo:** 2026 (1° Cuatrimestre)  
**Profesor:** Prof. York  

---

## 🎯 Descripción del Proyecto

Esta actividad tiene como propósito la **configuración y personalización del Entorno de Desarrollo Integrado (IDE)**, promoviendo el dominio de herramientas de software profesional utilizadas en la industria (VS Code, compiladores GCC/MinGW, consola de comandos y control de versiones). 

Como demostración práctica, se desarrolla, compila y ejecuta un programa base en C++ ("Hola Mundo") con salida formateada en consola.

---

## 🧰 Herramientas y Entorno de Desarrollo

- **IDE Principal:** [Visual Studio Code](https://code.visualstudio.com/)
- **Extensiones Obligatorias de VS Code:**
  - *C/C++* (Microsoft)
  - *C/C++ Extension Pack*
  - *Code Runner* (Opcional)
- **Compilador:** `g++` (MinGW-w64 via MSYS2)
- **Terminal:** PowerShell / Command Prompt (Windows 10/11)
- **Alternativa Web:** [OnlineGDB](https://www.onlinegdb.com/) (para equipos con restricciones de administrador)

---

## 📕 Glosario Técnico Breve

- **Código Fuente:** Texto escrito en lenguaje legible por humanos (C++) que contiene las instrucciones del programa.
- **Compilador:** Herramienta que traduce el código fuente a código máquina (binario ejecutable `.exe`).
- **IDE:** Entorno que integra editor de texto, compilador y depurador en un solo flujo de trabajo.
- **PATH:** Variable de entorno del sistema que permite a la terminal reconocer el comando `g++` desde cualquier directorio.

---

## 🗂️ Estructura del Repositorio

```text
holamundo/
├── .gitignore                      <-- Archivo para ignorar configuraciones locales (.vscode, etc.)
├── README.md                       <-- Documentación general de la actividad
├── LICENSE                         <-- Licencia del proyecto
├── docs/
│   └── InformeProyectoHOLAMUNDO.pdf  <-- Informe del proyecto con cuestionario técnico (APA v7)
├── src/
│   ├── main.cpp                    <-- Código fuente en C++
│   └── holamundo.exe               <-- Ejecutable generado (local)
└── capturas/
    ├── gpp_version.png             <-- Verificación del compilador en consola (`g++ --version`)
    ├── extensiones_vscode.png      <-- Extensiones instaladas en VS Code
    └── ejecucion_hola_mundo.png    <-- Salida por pantalla y compilación exitosa
```

---

## 🛠️ Compilación y Ejecución desde Terminal

1. Abrir la terminal integrada de VS Code (`Ctrl + Ñ`) en la raíz del proyecto `holamundo`.
2. Compilar el archivo fuente generando el ejecutable en la carpeta `src/`:
   ```powershell
   g++ src/main.cpp -o src/holamundo.exe
   ```
3. Ejecutar el programa en Windows:
   ```powershell
   .\src\holamundo.exe
   ```

---

## 📋 Cuestionario Técnico de Control

Las respuestas detalladas a las 10 preguntas de reflexión técnica sobre el entorno de desarrollo, el uso de Inteligencia Artificial, y metas de la carrera técnica se encuentran redactadas dentro del informe PDF ubicado en la carpeta `docs/InformeProyectoHOLAMUNDO.pdf`.

---

## 🏆 Criterios de Entrega

- **Estudiante / Grupo:** [Tu Nombre y Apellido]
- **Formato:** Repositorio en GitHub + Informe APA v7 en PDF + Planilla de Proyectos (P.I.A.).
- **Fecha Prorrogada de Entrega:** 31 de Agosto de 2026.
