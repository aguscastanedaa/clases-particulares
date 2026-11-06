# 📚 Portal Académico de Clases Particulares

Plataforma educativa con presentaciones interactivas de alta calidad desarrolladas con **Reveal.js 5.1.0** y renderizado matemático con **KaTeX**, diseñadas para nivel secundario, técnico y preuniversitario.

🌐 **Sitio Web Publicado:** [https://aguscastanedaa.github.io/clases-particulares/](https://aguscastanedaa.github.io/clases-particulares/)

---

## ⚡ Módulo de Física

El módulo de Física incluye 4 presentaciones teóricas progresivas y una presentación exhaustiva con la **resolución oficial paso a paso del Trabajo Práctico N.º 1**:

1. **[Módulo 01: Sistema Internacional y Conversión de Unidades](fisica/01-unidades-si.html)**
   - Magnitudes físicas fundamentales ($m, kg, s$) y derivadas.
   - Prefijos métricos (mega a mili) y múltiplos/submúltiplos.
   - El método sistemático del **factor de conversión**.
   - Detección de errores y análisis dimensional.

2. **[Módulo 02: Notación Científica y Órdenes de Magnitud](fisica/02-notacion-cientifica.html)**
   - Forma canónica $a \times 10^n$ ($1 \le |a| < 10$).
   - Exponentes positivos (macrocosmos) y negativos (microcosmos).
   - Multiplicación y división con potencias de diez.
   - Suma y resta con **igualación de exponentes** y normalización final.

3. **[Módulo 03: Teoría de Errores y Mediciones Experimentales](fisica/03-errores-medicion.html)**
   - Diferencia entre exactitud, precisión y resolución instrumental.
   - Cálculo del error absoluto ($E_a$), error relativo ($E_r$) y porcentual ($E_r\%$).
   - Comparación de escalas ($1\text{ mm}$ en $1\text{ m}$ vs $300\text{ m}$ en $300\text{ km}$).
   - Tratamiento de mediciones repetidas: promedio ($\bar{x}$), desviación media, semidispersión e intervalo de márgenes.

4. **[Módulo 04: Vectores en el Plano Cartesiano](fisica/04-vectores.html)**
   - Magnitudes escalares vs vectoriales.
   - Módulo (Pitágoras), dirección y sentido en los 4 cuadrantes.
   - Operaciones vectoriales: suma (punta-cola y paralelogramo), resta con vector opuesto y producto por un escalar.
   - Gráficos vectoriales SVG precisos con escala y componentes.

5. **[Resolución Oficial: Trabajo Práctico N.º 1](fisica/resolucion-tp1.html)**
   - Resolución íntegra y justificada de los **Ejercicios 1 al 8**.
   - Metodología pedagógica de 8 pasos: Enunciado fiel, datos, concepto físico, estrategia, paso a paso, resultado, interpretación y comprobación.

---

## 📐 Módulo de Matemática

- **[PA 1: Función Cuadrática](matematica/01-funcion-cuadratica.html)**: Formas polinómica, canónica y factorizada; raíces, vértice y análisis de la parábola.
- **[PA 2: Polinomios](matematica/02-polinomios.html)**: Operaciones, regla de Ruffini, Teorema del Resto y Gauss.
- **[PA 3: Función Exponencial y Logarítmica](matematica/03-exponencial-y-logaritmica.html)**: Asíntotas, crecimiento y cambio de base.

---

## 💻 Módulo de Programación: C y Python

El módulo de Programación contiene un plan curricular completo de **54 presentaciones interactivas e independientes**, organizadas en dos cuatrimestres y cuatro bimestres: **C (bimestres 1 a 3, estándar C99/C11)** y **Python 3 (bimestre 4)**, animadas con **Reveal.js 5.1.0**.

### 📘 1er Cuatrimestre: Fundamentos, Estructuras de Datos y Memoria Dinámica (23 Unidades en 2 Bimestres)
🔗 **Portal del Cuatrimestre:** [programacion/1er-cuatrimestre/index.html](programacion/1er-cuatrimestre/index.html)

#### 🔹 1er Bimestre: Fundamentos de C y Control de Flujo (13 Unidades)
🔗 **Portal del 1er Bimestre:** [programacion/1er-cuatrimestre/1er-bimestre/index.html](programacion/1er-cuatrimestre/1er-bimestre/index.html)
📄 **Apunte Teórico Oficial:** [Apunte teorico - Lab. Algoritmos y Estructura de Datos.pdf](programacion/1er-cuatrimestre/1er-bimestre/Apunte%20teorico%20-%20Lab.%20Algoritmos%20y%20Estructura%20de%20Datos.pdf)

1. **[Unidad 01: ¿Qué es programar?](programacion/1er-cuatrimestre/1er-bimestre/presentaciones/01-introduccion-programacion.html)**
   - Algoritmos de la vida cotidiana, ambigüedad humana vs precisión matemática de la computadora.
   - Rol de la CPU, memoria RAM y almacenamiento secundario; cómo viajan los datos.
   - Lenguaje de máquina (binario) vs lenguaje compilado de alto nivel (C).
   - Sintaxis vs lógica, ciclo de vida del código (código fuente $\rightarrow$ compilador $\rightarrow$ ejecutable binario).
   - Primer programa en C con análisis detallado: cálculo del doble de un número (`numero * 2`).

2. **[Unidad 02: Estructura básica de un programa en C](programacion/1er-cuatrimestre/1er-bimestre/presentaciones/02-estructura-programa-c.html)**
   - Anatomía de un archivo `.c`: directivas de preprocesador (`#include <stdio.h>`), punto de entrada `main()`.
   - Delimitadores de bloque `{ }`, sangría/indentación como buena práctica y punto y coma `;` como finalizador de sentencias.
   - Significado del valor de retorno `return 0;` como señal de éxito al sistema operativo.
   - Comentarios de una sola línea (`//`) y de múltiples líneas (`/* ... */`).
   - El primer "¡Hola, mundo!" explicado línea por línea y errores de novato (olvido de `;`, omitir `#include`).

3. **[Unidad 03: Variables: La memoria de tu programa](programacion/1er-cuatrimestre/1er-bimestre/presentaciones/03-variables.html)**
   - Analogía de la memoria RAM como una estantería de cajas etiquetadas.
   - Las 3 características de una variable: tipo de dato, identificador (nombre) y contenido.
   - Reglas y convenciones de nomenclatura en C (`camelCase`, `snake_case`, palabras reservadas).
   - Declaración vs Inicialización vs Asignación; peligro de variables no inicializadas (valores basura en RAM).
   - Operador de asignación `=` (copia de derecha a izquierda) vs operador de comparación `==`.
   - Trazas de memoria paso a paso y el error clásico de intentar guardar texto en un `int`.

4. **[Unidad 04: Tipos de datos fundamentales](programacion/1er-cuatrimestre/1er-bimestre/presentaciones/04-tipos-datos.html)**
   - Tipado estático y estricto de C: por qué la máquina necesita saber el tamaño exacto en bytes.
   - Tipos primitivos: `int` (enteros, 4 bytes), `float` (reales, 4 bytes), `double` (doble precisión, 8 bytes), `char` (1 byte).
   - El tipo `char` y su relación directa con la tabla de códigos ASCII (un carácter es un número entero).
   - Rango de representación y desbordamiento (*overflow*) numérico.
   - Constantes literales y prefijo `const` para variables de solo lectura.

5. **[Unidad 05: Entrada y salida de datos (E/S)](programacion/1er-cuatrimestre/1er-bimestre/presentaciones/05-entrada-salida.html)**
   - La biblioteca `<stdio.h>` y los flujos estándar `stdout` y `stdin`.
   - Salida con `printf()`: cadenas de texto, secuencias de escape (`\n`, `\t`, `\\`, `\"`).
   - Especificadores de formato: `%d` / `%i` (enteros), `%f` (flotantes), `%.2f` (redondeo a 2 decimales), `%c` (caracteres).
   - Entrada con `scanf()`: especificadores correspondientes y el operador de dirección `&` (el porqué del ampersand).
   - Errores típicos: olvidar el `&` en `scanf()`, mezclar tipos entre el especificador y la variable, y limpieza básica de búfer.

6. **[Unidad 06: Operadores aritméticos y módulo %](programacion/1er-cuatrimestre/1er-bimestre/presentaciones/06-operadores-aritmeticos.html)**
   - Operadores básicos: suma (`+`), resta (`-`), multiplicación (`*`), división (`/`).
   - El gran dilema de la división en C: división entera `5 / 2 = 2` vs división real `5.0 / 2.0 = 2.5` y casteo `(float)a / b`.
   - El operador módulo o resto `%`: qué calcula matemáticamente y por qué solo opera sobre enteros.
   - Aplicaciones clave del módulo: comprobar paridad (`n % 2 == 0`), verificar divisibilidad y aislar dígitos de un número.
   - Precedencia de operadores aritméticos y uso correcto de paréntesis asociativos.

7. **[Unidad 07: Incremento de variables](programacion/1er-cuatrimestre/1er-bimestre/presentaciones/07-incremento-variables.html)**
   - Concepto de auto-modificación: `x = x + 1` desglosado paso a paso.
   - Operadores de asignación compuesta: `+=`, `-=`, `*=`, `/=`, `%=`.
   - Operadores unarios de incremento y decremento: `++` y `--`.
   - Diferencia fundamental entre pre-incremento (`++x`) y post-incremento (`x++`) con ejemplos y tablas de traza.
   - Patrones fundamentales en programación: la variable **Contador** vs la variable **Acumulador / Totalizador**.

8. **[Unidad 08: Operadores de comparación](programacion/1er-cuatrimestre/1er-bimestre/presentaciones/08-operadores-comparacion.html)**
   - Proposiciones y preguntas booleanas en la computadora: la respuesta binaria verdadera (`1`) o falsa (`0`).
   - Operadores relacionales: igualdad (`==`), desigualdad (`!=`), menor (`<`), mayor (`>`), menor o igual (`<=`), mayor o igual (`>=`).
   - La trampa mortal de los principiantes: confundir `=` (asignación) con `==` (comparación).
   - Comparación entre números de punto flotante y comparación de caracteres según su código ASCII.
   - Evaluación de expresiones lógicas complejas y generación de resultados numéricos en memoria.

9. **[Unidad 09: Condicionales: if y else](programacion/1er-cuatrimestre/1er-bimestre/presentaciones/09-condicionales.html)**
   - La toma de decisiones en el software: bifurcación de flujos de ejecución.
   - Estructura `if` simple: ejecución condicional basada en una expresión booleana.
   - Estructura `if ... else`: caminos mutuamente excluyentes (verdadero vs falso).
   - Estructura `if ... else if ... else`: escaleras de decisión múltiple con salida anticipada.
   - Condicionales anidados, buenas prácticas de llaves `{ }` obligatorias y diagramas de flujo SVG paso a paso.

10. **[Unidad 10: Operadores lógicos: &&, || y !](programacion/1er-cuatrimestre/1er-bimestre/presentaciones/10-operadores-logicos.html)**
    - Combinación de condiciones complejas mediante lógica proposicional booleana.
    - Conjunción lógica **AND** (`&&`): tabla de verdad completa y validación de rangos numéricos (`x >= 10 && x <= 20`).
    - Disyunción lógica **OR** (`||`): tabla de verdad completa y validación de alternativas (`dia == 6 || dia == 7`).
    - Negación lógica **NOT** (`!`): inversión de polaridad de una condición.
    - Evaluación de cortocircuito (*short-circuit evaluation*) en C y su uso defensivo contra división por cero o punteros nulos.
    - Leyes de De Morgan aplicadas a la simplificación de condiciones en C.

11. **[Unidad 11: Booleanos: bool, true y false](programacion/1er-cuatrimestre/1er-bimestre/presentaciones/11-booleanos.html)**
    - Historia de la verdad en C: el estándar original C89 donde cualquier valor distinto de cero es verdadero (`1`) y cero es falso (`0`).
    - El estándar C99 y la cabecera estándar `<stdbool.h>`: tipos `bool`, `true` y `false`.
    - Patrón de banderas (*flags*): variables booleanas de estado para alertar eventos en el algoritmo.
    - Escritura de condiciones idiomáticas y limpias (`if (esActivo)` en lugar de `if (esActivo == true)`).
    - Casos prácticos de banderas: detección de condiciones especiales en secuencias y bucles.

12. **[Unidad 12: Funciones en C: Modularidad y Reutilización](programacion/1er-cuatrimestre/1er-bimestre/presentaciones/12-funciones.html)**
    - Filosofía de "Dividir y Vencerás" y el principio DRY (*Don't Repeat Yourself*).
    - Anatomía de una función: tipo de retorno, nombre significativo, lista de parámetros formales y cuerpo.
    - Diferencia crucial entre parámetros (declarados en la función) y argumentos (valores reales enviados en la llamada).
    - Declaración (prototipo de función) vs Definición (implementación) vs Invocación (llamada).
    - La instrucción `return` y el tipo especial `void` (funciones que ejecutan acciones sin devolver valor).
    - Scope o ámbito de variables: variables locales, variables globales y aislamiento de pila de ejecución (Stack frame).

13. **[Unidad 13: Bucles: while y for](programacion/1er-cuatrimestre/1er-bimestre/presentaciones/13-bucles-while-for.html)**
    - La necesidad de la repetición: automatizar tareas iterativas sin duplicar código.
    - Los 3 pilares indispensables de cualquier ciclo: inicialización, condición de continuación y actualización.
    - El bucle `while`: ciclo pre-prueba para repeticiones indeterminadas o basadas en condiciones externas.
    - El bucle `for`: ciclo compacto ideal para iteraciones con contador conocido de antemano (`inicialización; condición; incremento`).
    - Comparación lado a lado de `while` y `for` resolviendo el mismo problema.
    - El ciclo `do-while`: ciclo post-prueba que garantiza al menos una ejecución (ideal para validación de menús y entradas).
    - Control de flujo con `break` (corte anticipado) y `continue` (salto de iteración), bucles anidados y prevención de bucles infinitos.

#### 🔹 2do Bimestre: Vectores, Matrices, Registros y Memoria Dinámica (10 Unidades)
🔗 **Portal del 2do Bimestre:** [programacion/1er-cuatrimestre/2do-bimestre/index.html](programacion/1er-cuatrimestre/2do-bimestre/index.html)
📄 **Apunte Teórico Oficial:** [Apunte teorico - Lab. Algoritmos y Estructura de Datos p2.pdf](programacion/1er-cuatrimestre/2do-bimestre/Apunte%20teorico%20-%20Lab.%20Algoritmos%20y%20Estructura%20de%20Datos%20p2.pdf)

1. **[Unidad 01: Vectores y Arreglos Estáticos](programacion/1er-cuatrimestre/2do-bimestre/presentaciones/01-vectores-estaticos.html)**
   - Problema de las variables individuales vs colecciones homogéneas en una fila de casilleros numerados.
   - Declaración (`int numeros[5];`), índices de `0` a `N-1`, acceso (`numeros[0] = 10`) y modificación.
   - Inicialización explícita (`{8, 10, 7, 9, 6}`), parcial a ceros y contigüidad en memoria RAM (`sizeof`).
   - Prevención de accesos fuera de rango (*buffer overflow*) y 4 niveles progresivos de ejemplos prácticos.

2. **[Unidad 02: Recorridos, Búsquedas y Procesamiento de Vectores](programacion/1er-cuatrimestre/2do-bimestre/presentaciones/02-recorridos-busquedas-vectores.html)**
   - Recorrido canónico con `for(int i = 0; i < N; i++)`, simulación paso a paso y modificación (`numeros[i] = numeros[i] * 2`).
   - El error clásico `for(int i = 1; i <= 5; i++)`: saltar `pos[0]` y desbordar en `pos[5]`.
   - Búsqueda de mínimo/máximo (inicializando con `numeros[0]`), primer par con `break`, conteo de pares y búsqueda lineal con bandera.
   - Problema integrador de examen: encontrar el **menor número par** del vector.

3. **[Unidad 03: Ordenamiento de Vectores: Intercambio y Burbuja](programacion/1er-cuatrimestre/2do-bimestre/presentaciones/03-ordenamiento-vectores.html)**
   - La lógica del intercambio seguro de dos variables usando variable auxiliar (`aux`) vs el error de sobreescritura directa.
   - Algoritmo de **Ordenamiento por Intercambio** del apunte (`for i` fijando posición y `for j = i + 1` comparando el resto) con traza completa sobre `{8, 3, 10, 1, 5}`.
   - Algoritmo de **Ordenamiento Burbuja (Bubble Sort)** por pares adyacentes (`j` y `j + 1`) y optimización con bandera.
   - Ordenamiento ascendente (`<`), descendente (`>`), mediana y ranking de notas.

4. **[Unidad 04: Matrices y Recorridos Bidimensionales](programacion/1er-cuatrimestre/2do-bimestre/presentaciones/04-matrices-bidimensionales.html)**
   - Grillas de dos dimensiones (`int matriz[3][3]`), analogía del aula de pupitres y coordenadas `[fila][columna]`.
   - Inicialización estructurada por filas, acceso puntual y el error de escribir `matriz[1, 2]` en lugar de `matriz[1][2]`.
   - Recorrido completo con doble ciclo `for` anidado (`i` para filas, `j` para columnas) y tabla de seguimiento de las 9 iteraciones.
   - Impresión en formato tabla con `\n` al cierre de cada fila, sumatoria total, suma por fila/columna y máximo con coordenadas `(fila, col)`.

5. **[Unidad 05: Diagonales de una Matriz Cuadrada](programacion/1er-cuatrimestre/2do-bimestre/presentaciones/05-diagonales-matriz.html)**
   - Matrices cuadradas $N \times N$ y por qué solo ellas poseen diagonales completas.
   - **Diagonal Principal**: deducción de la ley matemática `i == j` (`[0][0]`, `[1][1]`, `[2][2]`).
   - **Diagonal Secundaria**: deducción de la ley matemática `i + j == N - 1` (`[0][2]`, `[1][1]`, `[2][0]`) y optimización en un solo ciclo `O(N)`.
   - Elementos fuera de las diagonales, matriz identidad, traza matricial y cruces en matrices de orden impar.

6. **[Unidad 06: Estructuras (`struct`) y Vectores de Registros](programacion/1er-cuatrimestre/2do-bimestre/presentaciones/06-estructuras-struct.html)**
   - Limitación de vectores paralelos homogéneos vs agrupación heterogénea con `struct Alumno { int edad; float promedio; char division; };`.
   - Diferencia entre definir el molde (`struct Alumno`) y crear variables en RAM (`struct Alumno alumno1;`), incluyendo el `;` obligatorio tras `}`.
   - Acceso a campos mediante el operador punto (`.`) y alias opcional con `typedef`.
   - **Vectores de estructuras** (`struct Alumno alumnos[30];`), acceso combinado `alumnos[i].campo`, carga e informes estadísticos con `for`.

7. **[Unidad 07: Introducción a la Memoria Dinámica y Punteros](programacion/1er-cuatrimestre/2do-bimestre/presentaciones/07-introduccion-memoria-dinamica.html)**
   - Memoria estática vs memoria dinámica: la analogía de las sillas de una fiesta y el desperdicio/falta de espacio en `int alumnos[100];`.
   - Mapa de la memoria RAM: **Stack** (automática y fija) vs **Heap** (manual y flexible en tiempo de ejecución).
   - Fundamentos de direcciones de memoria y punteros (`int *numeros;`), operador dirección `&` y desreferenciación `*`.
   - Las 4 herramientas de `<stdlib.h>`: `malloc()`, `calloc()`, `realloc()` y `free()`.

8. **[Unidad 08: Reserva y Liberación: `malloc()`, `free()` y `sizeof()`](programacion/1er-cuatrimestre/2do-bimestre/presentaciones/08-reserva-liberacion-malloc-free.html)**
   - La analogía del alquiler de una cancha de fútbol: reservar espacio (`malloc`), usarlo y devolverlo (`free`).
   - Desglose completo de `numeros = (int*) malloc(n * sizeof(int));` y cálculo portable de bytes con `sizeof`.
   - Verificación defensiva obligatoria contra `NULL` (`if (numeros == NULL)`) y valores basura iniciales en el bloque reservado.
   - Fugas de memoria (*memory leaks*), punteros colgantes (`numeros = NULL;`) y ciclo de vida completo en 6 pasos.

9. **[Unidad 09: `calloc()` y `realloc()`: Inicialización en Cero y Redimensión](programacion/1er-cuatrimestre/2do-bimestre/presentaciones/09-calloc-realloc.html)**
   - `calloc(n, sizeof(int))`: reserva de memoria limpia inicializada automáticamente en `0` vs la basura de `malloc()`.
   - Tabla comparativa y visualizador de celdas en RAM (`154 | -20 | 987` en `malloc` vs `0 | 0 | 0` en `calloc`).
   - `realloc(numeros, nuevoTam * sizeof(int))`: ampliación o reducción conservando intactos los datos previos (`10 20 30 40 50 ? ? ? ? ?`).
   - Los 3 escenarios internos de `realloc()` en el Heap y el patrón seguro con puntero auxiliar `aux` para no perder los datos si devuelve `NULL`.

10. **[Unidad 10: Vectores Dinámicos e Integración del Bimestre](programacion/1er-cuatrimestre/2do-bimestre/presentaciones/10-vectores-dinamicos.html)**
    - Qué es un vector dinámico y por qué en C se recorre y utiliza exactamente igual que un vector estático (`notas[i]`, `&notas[i]`).
    - Comparación integral: vector estático en Stack vs vector dinámico en Heap.
    - Integración de todos los algoritmos del bimestre (búsqueda, mínimo/máximo, ordenamiento y vectores dinámicos de `struct Alumno`) sobre memoria dinámica.
    - Menú interactivo de crecimiento con `realloc()` y checklist completo de preparación para el examen del 2do Bimestre.

---

### 📗 2do Cuatrimestre: C Avanzado (3er Bimestre, 13 Unidades) y Python (4to Bimestre, 18 Unidades)
🔗 **Portal del Cuatrimestre:** [programacion/2do-cuatrimestre/index.html](programacion/2do-cuatrimestre/index.html)
📄 **Apunte Teórico Oficial:** [Apunte teorico - Lab. Algoritmos y Estructura de Datos p3.pdf](programacion/2do-cuatrimestre/3er-bimestre/Apunte%20teorico%20-%20Lab.%20Algoritmos%20y%20Estructura%20de%20Datos%20p3.pdf)

1. **[Unidad 01: Funciones con Retorno y Arreglos como Parámetros](programacion/2do-cuatrimestre/3er-bimestre/presentaciones/01-funciones-retorno-arreglos-parametros.html)**
   - Funciones `void` vs funciones con retorno (`int`, `float`, `double`).
   - Uso de `return`, flujo de control y descarte de valores no asignados.
   - Parámetros vs argumentos: paso de arreglos por dirección base con tamaño explícito `(int arr[], int n)`.
   - Ejemplos prácticos: `doble`, `sumar`, `calcularDescuento`, cálculo de sumas y promedios en vectores.

2. **[Unidad 02: Introducción a los Strings en C](programacion/2do-cuatrimestre/3er-bimestre/presentaciones/02-introduccion-strings.html)**
   - Qué es una cadena: arreglo unidimensional de caracteres terminado por el centinela nulo `'\0'`.
   - Carácter simple `'A'` (1 byte) vs cadena `"A"` (2 bytes con `'\0'`).
   - Representación en memoria RAM y tamaño necesario ($N+1$).
   - Impresión con `%s`, lectura y recorridos manuales con bucles `while` y `for`.
   - Cálculo algorítmico de la longitud sin librerías externas.

3. **[Unidad 03: Biblioteca `<string.h>` y Operaciones Estándar](programacion/2do-cuatrimestre/3er-bimestre/presentaciones/03-libreria-string-h.html)**
   - Inclusión de cabecera `#include <string.h>`.
   - Medición: `strlen()`.
   - Copia de cadenas: `strcpy()` y la variante segura con límite de caracteres `strncpy()`.
   - Comparación lexicográfica: `strcmp()` y `strncmp()` (por qué `==` compara direcciones y no contenido).
   - Concatenación: `strcat()` y `strncat()`.
   - Búsqueda: `strchr()` (primer carácter) y `strstr()` (primera ocurrencia de subcadena).
   - Prevención de desbordamiento de búfer y buenas prácticas defensivas.

4. **[Unidad 04: Procesamiento y Algoritmos con Strings](programacion/2do-cuatrimestre/3er-bimestre/presentaciones/04-algoritmos-procesamiento-strings.html)**
   - Conteo de frecuencias de un carácter específico.
   - Búsqueda manual de caracteres y subcadenas desde cero.
   - Detección de prefijos: comprobar si una cadena comienza con otra.
   - Modificación in-situ y reemplazo de caracteres.
   - Conversión entre mayúsculas y minúsculas mediante código ASCII (+32 / -32) y `<ctype.h>`.
   - Algoritmo de inversión de cadenas con dos punteros/índices opuestos.
   - Algoritmo de detección de palíndromos paso a paso.

5. **[Unidad 05: Introducción a los Punteros y Direcciones de Memoria](programacion/2do-cuatrimestre/3er-bimestre/presentaciones/05-introduccion-punteros-direcciones-memoria.html)**
   - Organización de la memoria RAM y concepto de dirección física.
   - Qué es un puntero: variable que almacena la dirección de otra variable.
   - Declaración de punteros (`int *p;`).
   - Operador de dirección `&` y operador de desreferenciación / indirección `*`.
   - Diferencia fundamental entre `edad`, `&edad`, `p` y `*p`.
   - Impresión de direcciones en hexadecimal con `%p`.
   - Errores críticos: punteros no inicializados (salvajes), direcciones nulas y desreferenciación inválida.

6. **[Unidad 06: Paso por Referencia, Punteros y Funciones](programacion/2do-cuatrimestre/3er-bimestre/presentaciones/06-paso-por-referencia-punteros-funciones.html)**
   - Modelo de paso por valor estricto de C.
   - Por qué modificar un parámetro regular no afecta a la variable del llamador.
   - Simulación de paso por referencia pasando la dirección con `&` y recibiendo con `*`.
   - Funciones que modifican variables originales (`incrementar`, `intercambiar`).
   - Retorno de múltiples resultados: función de división entera (cociente y resto) y mínimo/máximo simultáneo.

7. **[Unidad 07: Relación entre Punteros y Arreglos](programacion/2do-cuatrimestre/3er-bimestre/presentaciones/07-punteros-y-arreglos.html)**
   - Identidad entre el identificador de un arreglo y la dirección de su elemento 0 (`vec == &vec[0]`).
   - Aritmética de punteros: suma de enteros a punteros escalada por `sizeof(tipo)`.
   - Equivalencia fundamental: `*(p + i)` es idéntico a `p[i]` y `vec[i]`.
   - Recorridos eficientes de vectores mediante avance de puntero (`p++`).
   - Diferencias cruciales: los arreglos son constantes fijas no reasignables, los punteros son variables modificables.

8. **[Unidad 08: Introducción a las Estructuras (`struct`)](programacion/2do-cuatrimestre/3er-bimestre/presentaciones/08-estructuras-struct-fundamentos.html)**
   - Limitaciones de variables sueltas y motivación para agrupar datos heterogéneos.
   - Definición de tipos estructurados (`struct Persona`, `struct Alumno`, `struct Empleado`).
   - Campos miembros, asignación e inicialización directa.
   - Acceso a campos mediante el operador punto (`.`).
   - Paso de estructuras completas por valor a funciones (copia defensiva en Stack).

9. **[Unidad 09: Punteros a Estructuras y el Operador Flecha (`->`)](programacion/2do-cuatrimestre/3er-bimestre/presentaciones/09-punteros-a-estructuras-operador-flecha.html)**
   - Declaración y asignación de punteros a estructuras (`struct Empleado *emp = &e;`).
   - El operador flecha `->`: azúcar sintáctico para `(*emp).campo`.
   - Eficiencia en el paso por referencia a funciones: evitar copias pesadas de memoria.
   - Modificación in-situ de registros: aumentos salariales y actualización de datos.

10. **[Unidad 10: Arreglos de Estructuras](programacion/2do-cuatrimestre/3er-bimestre/presentaciones/10-arreglos-de-estructuras.html)**
    - Declaración de arreglos de registros (`struct Alumno curso[30];`).
    - Anatomía de memoria: bloques contiguos de registros completos.
    - Recorrido con bucles `for`, lectura de campos (`curso[i].promedio`) y carga de datos.
    - Envío de arreglos de structs a funciones.
    - Algoritmos sobre arreglos estructurados: búsqueda del mejor promedio, filtrado y modificación de registros.

11. **[Unidad 11: Estructuras con Arreglos Internos y Estructuras Anidadas](programacion/2do-cuatrimestre/3er-bimestre/presentaciones/11-estructuras-arreglos-internos-anidadas.html)**
    - Estructuras con miembros de tipo arreglo (`float notas[3]`).
    - Acceso compuesto: `alumno.notas[i]` y cálculo modular del promedio de calificaciones.
    - Estructuras anidadas (composición de tipos): `struct Fecha` dentro de `struct Persona`.
    - Acceso en cadena: `persona.nacimiento.ano`.
    - Funciones que reciben y procesan estructuras jerárquicas complejas.

12. **[Unidad 12: Integración: Estructuras, Punteros y Transferencia Bancaria](programacion/2do-cuatrimestre/3er-bimestre/presentaciones/12-integracion-transferencia-bancaria.html)**
    - Proyecto integrador: modelado del sistema `CuentaBancaria` (número, titular, saldo, estado activo/inactivo).
    - Función de transferencia bancaria con punteros de origen y destino (`origen`, `destino`, `monto`).
    - Programación defensiva y transaccionalidad: validación de cuentas activas, monto positivo y saldo disponible.
    - Atomicidad: si cualquier condición falla, ningún saldo se modifica.
    - Retorno de códigos de estado para informar éxito o causa del fallo.

13. **[Unidad 13: Resumen de Símbolos y Repaso Integrador](programacion/2do-cuatrimestre/3er-bimestre/presentaciones/13-resumen-simbolos-repaso-integrador.html)**
    - Tabla comparativa definitiva de operadores de C: `&`, `*`, `int *p`, `[]`, `.`, `->`, `'\0'`, `return`.
    - Preguntas de autoevaluación conceptual con explicaciones.
    - Taller de ejercicios integradores guiados.
    - Errores típicos y trampas frecuentes de compilación y ejecución.

---

### 🐍 4to Bimestre: Programación en Python (18 Unidades)
🔗 **Portal del Bimestre:** [programacion/2do-cuatrimestre/4to-bimestre/index.html](programacion/2do-cuatrimestre/4to-bimestre/index.html)
📄 **Apunte Teórico Oficial:** [Apunte teorico - Lab. Algoritmos y Estructura de Datos p4.pdf](programacion/2do-cuatrimestre/4to-bimestre/Apunte%20teorico%20-%20Lab.%20Algoritmos%20y%20Estructura%20de%20Datos%20p4.pdf)

Python enseñado desde cero, con explicaciones paso a paso, tablas de seguimiento, errores frecuentes con su mensaje real, comparaciones con C y ejercicios por unidad. **Todas las salidas mostradas en las clases se obtuvieron ejecutando el código con Python 3.14.**

1. **[Unidad 01: Introducción a Python y Fundamentos del Lenguaje](programacion/2do-cuatrimestre/4to-bimestre/presentaciones/01-introduccion-python.html)** — compilado vs interpretado, `print()`, comentarios, errores e indentación
2. **[Unidad 02: Variables y Tipos de Datos](programacion/2do-cuatrimestre/4to-bimestre/presentaciones/02-variables-y-tipos-de-datos.html)** — asignación, nombres, `int`/`float`/`str`/`bool`, `type()` y conversión
3. **[Unidad 03: Entrada y Salida de Datos](programacion/2do-cuatrimestre/4to-bimestre/presentaciones/03-entrada-salida-de-datos.html)** — `print()`, f-strings, `input()` siempre devuelve `str`, `int()`/`float()`
4. **[Unidad 04: Operadores Aritméticos](programacion/2do-cuatrimestre/4to-bimestre/presentaciones/04-operadores-aritmeticos.html)** — `/` vs `//`, `%`, `**`, precedencia, `+=`, contadores y acumuladores
5. **[Unidad 05: Operadores de Comparación y Lógicos](programacion/2do-cuatrimestre/4to-bimestre/presentaciones/05-operadores-comparacion-y-logicos.html)** — `==` vs `=`, `and`/`or`/`not`, tablas de verdad, cortocircuito
6. **[Unidad 06: Estructuras Condicionales](programacion/2do-cuatrimestre/4to-bimestre/presentaciones/06-estructuras-condicionales.html)** — `if`/`elif`/`else`, anidados y diagramas de flujo
7. **[Unidad 07: Bucles while](programacion/2do-cuatrimestre/4to-bimestre/presentaciones/07-bucles-while-control-repeticion.html)** — tres partes del bucle, bucles infinitos, `break`/`continue`, validación
8. **[Unidad 08: Bucles for y range()](programacion/2do-cuatrimestre/4to-bimestre/presentaciones/08-bucles-for-range-control-ciclos.html)** — `range(inicio, fin, paso)`, límite excluyente, `for` anidados
9. **[Unidad 09: Funciones: Definición, Parámetros y return](programacion/2do-cuatrimestre/4to-bimestre/presentaciones/09-funciones-definicion-parametros-return.html)** — `def`, parámetros vs argumentos, `return` vs `print`, `None`
10. **[Unidad 10: Funciones: Alcance y Valores por Defecto](programacion/2do-cuatrimestre/4to-bimestre/presentaciones/10-funciones-alcance-valores-por-defecto.html)** — argumentos con nombre, valores por defecto, variables locales y globales
11. **[Unidad 11: Strings: Fundamentos, Índices y Slicing](programacion/2do-cuatrimestre/4to-bimestre/presentaciones/11-strings-fundamentos-indices-slicing.html)** — índices positivos/negativos, `len()`, slicing e inmutabilidad
12. **[Unidad 12: Strings: Métodos y Procesamiento de Texto](programacion/2do-cuatrimestre/4to-bimestre/presentaciones/12-strings-metodos-y-procesamiento.html)** — `upper`, `strip`, `replace`, `find`, `split`, `join`, `isdigit`
13. **[Unidad 13: Listas: Fundamentos y Operaciones](programacion/2do-cuatrimestre/4to-bimestre/presentaciones/13-listas-fundamentos-y-operaciones.html)** — `append`, `insert`, `remove`, `pop`, `sort`, copias y referencias
14. **[Unidad 14: Listas: Recorridos y Algoritmos](programacion/2do-cuatrimestre/4to-bimestre/presentaciones/14-listas-recorridos-y-algoritmos.html)** — acumuladores, máximo, búsqueda, comprensiones, burbuja, búsqueda binaria
15. **[Unidad 15: Listas Anidadas y Matrices](programacion/2do-cuatrimestre/4to-bimestre/presentaciones/15-listas-anidadas-y-matrices.html)** — `m[i][j]`, `for` anidados, diagonales, transpuesta, `deepcopy`
16. **[Unidad 16: Manejo de Archivos: Lectura y Escritura](programacion/2do-cuatrimestre/4to-bimestre/presentaciones/16-manejo-de-archivos-lectura-escritura.html)** — `open()`, modos `r/w/a/x`, `read`, `readline`, `with open()`
17. **[Unidad 17: Archivos: Procesamiento y Manejo de Errores](programacion/2do-cuatrimestre/4to-bimestre/presentaciones/17-archivos-procesamiento-y-errores.html)** — `try/except`, CSV, actualizar y eliminar registros
18. **[Unidad 18: Organización, Buenas Prácticas y Repaso Final](programacion/2do-cuatrimestre/4to-bimestre/presentaciones/18-organizacion-buenas-practicas-repaso.html)** — PEP 8, `main()`, módulos, 7 etapas para resolver problemas, `assert`

---

## 🚀 Cómo Ejecutar Localmente

Para abrir las presentaciones en un entorno local y permitir que los recursos de Reveal.js carguen sin restricciones de protocolo `file://`:

```bash
# Iniciar servidor HTTP en el puerto 8000
python -m http.server 8000
```

Abrir en el navegador:
```
http://localhost:8000
```

---

## ⌨️ Atajos de Teclado

- **Avanzar diapositiva:** `Barra espaciadora` o `Flecha derecha (→)` / `Flecha abajo (↓)`.
- **Retroceder:** `Flecha izquierda (←)` / `Flecha arriba (↑)`.
- **Pantalla completa:** Tecla `F`.
- **Vista general (mosaico):** Tecla `O` o `Esc`.
- **Pausa / Pantalla negra:** Tecla `B` o `.`.

---
