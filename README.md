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

## 🚀 Cómo Ejecutar Localmente

Para abrir las presentaciones en un entorno local y permitir que los recursos de Reveal.js y KaTeX carguen sin restricciones de protocolo `file://`:

```bash
# Iniciar servidor HTTP en el puerto 8000
python -m http.server 8000
```

Abrir en el navegador:
```
http://localhost:8000
```

---

## ⌨️ Atajos de Teclado en Reveal.js

- **Avanzar diapositiva:** `Barra espaciadora` o `Flecha derecha (→)` / `Flecha abajo (↓)`.
- **Retroceder:** `Flecha izquierda (←)` / `Flecha arriba (↑)`.
- **Pantalla completa:** Tecla `F`.
- **Vista general (mosaico):` Tecla `O` o `Esc`.
- **Pausa / Pantalla negra:** Tecla `B` o `.`.

---

## 📁 Estructura del Proyecto

```
clases-particulares/
├── index.html                  # Portal global de asignaturas
├── README.md                   # Documentación técnica y pedagógica
├── fisica/
│   ├── index.html              # Portal del temario de Física
│   ├── css/
│   │   └── presentation.css    # Design System compartido de Física
│   ├── 01-unidades-si.html     # Presentación SI y conversiones
│   ├── 02-notacion-cientifica.html # Presentación notación científica
│   ├── 03-errores-medicion.html    # Presentación teoría de errores
│   ├── 04-vectores.html        # Presentación vectores 2D
│   ├── resolucion-tp1.html     # Resolución completa del TP 1
│   └── primer trabajo practico.pdf # PDF fuente original
└── matematica/
    ├── index.html              # Portal de Matemática
    ├── css/
    │   └── presentation.css    # Design System de Matemática
    ├── 01-funcion-cuadratica.html
    ├── 02-polinomios.html
    └── 03-exponencial-y-logaritmica.html
```

---

## 🛠️ Cómo Agregar un Nuevo Tema de Física

1. Crear un archivo en `fisica/` (ej: `05-cinematica-mru.html`).
2. Vincular el CSS común: `<link rel="stylesheet" href="css/presentation.css">`.
3. Reutilizar la barra superior `<div class="top-bar">` con enlace a `index.html`.
4. Incluir la inicialización de Reveal.js con el plugin `RevealMath.KaTeX`.
5. Agregar la tarjeta correspondiente en `fisica/index.html`.