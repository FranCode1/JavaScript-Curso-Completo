---

## 📘 Curso Completo de JavaScript — Versión Detallada con Subtemas

---

### 🧩 **Módulo 0 — Historia y contexto (poco común, pero valioso para tu libro)**

**Objetivo:** Aprender la historia de JavaScript y su influencia en la web.

* Rol de JavaScript en la Web.
* Las guerras de los navegadores y diferencias históricas.
* Evolución del estándar (ECMA, DOM Levels, etc.).

### 🔰 **Módulo 1 — Introducción a la Programación**

**Objetivo:** Aprender los fundamentos de la lógica de programación y sentar las bases para dominar cualquier lenguaje.

#### Tema 1: ¿Qué es programar?

* Concepto de programa, algoritmo y lenguaje
* Tipos de lenguajes (interpretados vs compilados)
* Entorno de trabajo (navegador, consola, editor)
* Cómo se ejecuta el código paso a paso

#### Tema 2: Conceptos fundamentales

* Sintaxis y estructura de un programa
* Expresiones y sentencias
* Operadores aritméticos, lógicos y de comparación
* Valores y tipos primitivos

#### Tema 3: Variables y datos

* `let`, `const`, `var` (diferencias y cuándo usar cada uno)
* Tipos de datos primitivos
* Conversión de tipos (implícita y explícita)
* Buenas prácticas al nombrar variables

#### Tema 4: Estructuras de control

* Condicionales (`if`, `else if`, `else`, `switch`)
* Bucles (`for`, `while`, `do while`)
* Control de flujo con `break` y `continue`

#### Tema 5: Funciones básicas

* Declaración y llamada de funciones
* Parámetros y argumentos
* Retorno de valores
* Ámbito de variables dentro de funciones

#### 🧩 Errores comunes

* Olvidar `return`
* Uso incorrecto de `=` vs `==` vs `===`
* Variables globales sin declarar

#### 💪 Ejercicios sugeridos

* Calculadora básica
* Conversor de temperatura
* Verificador de números pares/impares

#### 🚀 Proyecto parcial

**Mini proyecto:** *Simulador de decisiones simples* (elige una opción, muestra resultados distintos con condicionales)

---

### ⚙️ **Módulo 2 — Fundamentos del Lenguaje JavaScript**

**Objetivo:** Comprender las particularidades del lenguaje y sus mecanismos básicos.

#### Tema 1: Tipos de datos y coerción

* `undefined`, `null`, `boolean`, `number`, `string`, `symbol`
* Conversión automática de tipos
* Comparación estricta vs no estricta

#### Tema 2: Funciones como valores

* Funciones anónimas y nombradas
* Funciones de orden superior
* Callbacks
* Funciones flecha (`=>`)

#### Tema 3: `this` y contexto

* Qué es el contexto de ejecución
* Cómo se determina `this`
* Casos típicos: funciones, objetos, eventos, clases

#### Tema 4: Prototipos

* Concepto de herencia prototípica
* Propiedades heredadas
* Métodos del prototipo (`Object.create`, `Object.assign`)

#### Tema 5: Modo estricto y buenas prácticas

* `'use strict'` y sus beneficios
* Errores que previene
* Normas de estilo y consistencia

#### 🧩 Errores comunes

* No entender el contexto de `this`
* Confundir referencia con copia
* Mezclar `let` y `var` sin necesidad

#### 💪 Ejercicios sugeridos

* Reescribir funciones con arrow functions
* Crear objetos con prototipos manualmente

#### 🚀 Proyecto parcial

**Mini proyecto:** *Sistema de perfiles* (creación de usuarios con métodos compartidos por prototipo)

---

### 🧠 **Módulo 3 — Scope, Contexto y Clausuras**

**Objetivo:** Comprender cómo se organizan las variables y funciones dentro del motor de JS.

#### Tema 1: Teoría del compilador

* Etapas de compilación e interpretación
* Fases de creación y ejecución

#### Tema 2: Scope léxico

* Ámbito léxico y su importancia
* Cómo funcionan los closures
* Ejemplos de variables capturadas

#### Tema 3: Hoisting

* Qué es y cómo afecta a variables y funciones
* Diferencia entre `let`, `const` y `var`
* Ejemplos de comportamiento inesperado

#### Tema 4: Módulos y encapsulación

* Patrón módulo clásico
* IIFE (Immediately Invoked Function Expressions)
* Exportaciones modernas con `export` y `import`

#### 🧩 Errores comunes

* Confundir alcance léxico con dinámico
* Crear closures dentro de bucles sin entender la referencia
* Variables declaradas tarde (efecto hoisting)

#### 💪 Ejercicios sugeridos

* Reescribir ejemplos con closures
* Crear un módulo de contador
* Simular variables privadas

#### 🚀 Proyecto parcial

**Mini proyecto:** *Generador de contraseñas seguras* (usa closures para mantener valores privados)

---

### 🧩 **Módulo 4 — Objetos, Prototipos y Clases**

**Objetivo:** Dominar el sistema de objetos y herencia de JavaScript.

#### Tema 1: Objetos y propiedades

* Creación de objetos literales
* Métodos, `this`, y propiedades dinámicas
* Iteración con `for...in` y `Object.keys`

#### Tema 2: Prototipos y herencia

* `Object.getPrototypeOf`, `__proto__`
* Cadena de prototipos
* Herencia funcional vs clásica

#### Tema 3: Clases en ES6

* `class`, `constructor`, `extends`, `super`
* Métodos estáticos
* Diferencia entre clase y prototipo

#### Tema 4: Delegación de comportamiento

* Patrón de diseño basado en objetos
* Composición vs herencia
* Ventajas del diseño orientado a prototipos

#### 🧩 Errores comunes

* No usar `new` correctamente
* Sobrescribir propiedades del prototipo
* Malentender `this` dentro de métodos

#### 💪 Ejercicios sugeridos

* Crear jerarquías de clases simples
* Extender objetos para agregar comportamientos

#### 🚀 Proyecto parcial

**Mini proyecto:** *Sistema de personajes de videojuego* (herencia entre clases `Guerrero`, `Mago`, `Arquero`, etc.)

---

### 🧮 **Módulo 5 — Tipos, Valores y Gramática**

**Objetivo:** Comprender en profundidad los datos, operadores y la gramática del lenguaje.

#### Tema 1: Tipos y valores

* Tipos primitivos y de referencia
* Mutabilidad e inmutabilidad
* Conversión entre tipos

#### Tema 2: Nativos y envoltorios

* Objetos `Number`, `String`, `Boolean`
* Boxing y unboxing
* Métodos de tipo (`.toFixed()`, `.length`, etc.)

#### Tema 3: Coerción

* Implícita vs explícita
* Comparaciones complejas
* Peligros de `==`

#### Tema 4: Gramática y sintaxis

* Precedencia de operadores
* Sentencias y expresiones
* Inserción automática de punto y coma

#### 🧩 Errores comunes

* Esperar que `NaN == NaN`
* Confundir mutabilidad
* No usar `Number()` o `String()` correctamente

#### 💪 Ejercicios sugeridos

* Experimentar coerción entre tipos
* Crear funciones que validen tipos manualmente

#### 🚀 Proyecto parcial

**Mini proyecto:** *Validador de datos* (detecta tipos y valida entradas del usuario)

---

### ⚡ **Módulo 6 — Asincronía y Rendimiento**

**Objetivo:** Comprender cómo JavaScript maneja tareas simultáneas y optimizar el rendimiento.

#### Tema 1: Asincronía y el Event Loop

* Stack, heap y cola de tareas
* Cómo funciona el bucle de eventos
* Callbacks y su problema de anidación

#### Tema 2: Promesas

* Estados (`pending`, `fulfilled`, `rejected`)
* Encadenamiento y manejo de errores
* Métodos (`all`, `race`, `any`)

#### Tema 3: Async/Await y Generadores

* `async` y `await`
* Generadores (`function*`)
* Integración Generators + Promises

#### Tema 4: Rendimiento

* Web Workers y tareas paralelas
* SIMD, asm.js y optimizaciones
* Benchmarking con `performance.now()`

#### 🧩 Errores comunes

* Olvidar `await`
* No manejar errores de Promesas
* Bloquear el hilo principal

#### 💪 Ejercicios sugeridos

* Reescribir callbacks como Promesas
* Crear una cola de tareas asíncronas

#### 🚀 Proyecto parcial

**Mini proyecto:** *Simulador de descargas con progreso y Promesas*

---

### 🌐 **Módulo 7 — ES6 y Más Allá**

**Objetivo:** Adoptar las características modernas del lenguaje.

#### Tema 1: Nuevas declaraciones

* `let`, `const` y alcance de bloque
* Spread y rest
* Desestructuración de objetos y arrays

#### Tema 2: Nuevas estructuras

* `Map`, `Set`, `WeakMap`, `WeakSet`
* Iteradores y generadores
* Clases modernas y módulos

#### Tema 3: Metaprogramación

* `Symbol` y `Reflect`
* `Proxy` para interceptar operaciones
* Tail Call Optimization y `WebAssembly`

#### Tema 4: Async avanzado

* `Promise.allSettled`, `Promise.any`
* `async` functions y *event microtasks*

#### 🧩 Errores comunes

* Desestructuración con valores `undefined`
* Sobrescribir propiedades de Proxy

#### 💪 Ejercicios sugeridos

* Usar destructuring y spread en código real
* Crear un `Proxy` personalizado

#### 🚀 Proyecto parcial

**Mini proyecto:** *Sistema de módulos modernos* (import/export + asincronía)

---

### 💻 **Módulo 8 — Proyecto Final**

**Objetivo:** Aplicar todos los conocimientos en una aplicación completa.

**Ejemplos:**

* Aplicación de tareas (To-Do List) con almacenamiento local y asincronía
* Juego interactivo por navegador
* Pequeño framework o librería personalizada
* Aplicación Node.js con APIs

---

### 💻 **Módulo 9 — APIs del navegador (DOM/BOM)**

**Objetivo:** Aplicar todos los conocimientos en una aplicación completa.

**Ejemplos:**
* DOM avanzado y eventos
* Entorno del navegador (BOM, compatibilidad, legado)

---

### 📚 Apéndices

* Referencia rápida y compatibilidad
* Glosario de conceptos esenciales
* Lista de errores comunes en JS moderno
* Guía de estilo y convenciones
* Bibliografía y lecturas recomendadas (YDKJS, MDN, Eloquent JS, etc.)

---
