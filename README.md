# WebGL Solar System

Una simulación interactiva del sistema solar implementada usando WebGL 2.0, JavaScript puro y matemáticas 3D.

## 🌟 Descripción

Este proyecto presenta una representación visual y animada del sistema solar con todos los planetas principales. Utiliza WebGL para renderizar gráficos 3D directamente en el navegador, ofreciendo una experiencia inmersiva y educativa.

## ✨ Características

- **Simulación completa del sistema solar**: Sol, Mercurio, Venus, Tierra (con Luna), Marte, Júpiter y Saturno con anillos
- **Animación en tiempo real**: Cada planeta orbita a velocidades relativamente realistas
- **Controles interactivos**: Panel GUI para manipular la vista y la simulación
- **Física orbital**: Los planetas siguen órbitas circulares alrededor del Sol
- **Colores realistas**: Cada planeta tiene colores representativos
- **Zoom y rotación**: Control completo de la cámara y vista

## 🎮 Controles

El proyecto incluye un panel de control (dat.GUI) que permite:

- **Translate X/Y**: Mover la vista horizontalmente y verticalmente (-2 a 2)
- **Zoom**: Acercar o alejar la vista (1 a 100)
- **Speed**: Controlar la velocidad de la simulación (-50 a 50)
- **Rotate X/Y/Z**: Rotar la vista en los tres ejes (-180° a 180°)

## 🪐 Planetas incluidos

1. **Sol** - Centro del sistema, amarillo brillante
2. **Mercurio** - El más cercano, órbita rápida, color marrón-gris
3. **Venus** - Segundo planeta, color amarillo-dorado
4. **Tierra** - Nuestro planeta, azul con su luna blanca
5. **Marte** - El planeta rojo
6. **Júpiter** - El gigante gaseoso, color marrón-naranja
7. **Saturno** - Con sus característicos anillos, color amarillo-dorado

## 🛠️ Tecnologías utilizadas

- **WebGL 2.0**: Para renderización de gráficos 3D
- **JavaScript ES6+**: Lógica de la aplicación
- **gl-matrix**: Biblioteca para operaciones de matrices 3D
- **dat.GUI**: Interfaz de usuario para controles interactivos
- **GLSL**: Shaders personalizados para vertex y fragment
- **HTML5 Canvas**: Elemento de renderizado

## 🚀 Cómo ejecutar

1. Abre el archivo `index.html` en un navegador web moderno que soporte WebGL 2.0
2. El panel de controles aparecerá en la esquina inferior izquierda
3. ¡Experimenta con los controles para explorar el sistema solar!

## 📁 Estructura del proyecto

```
├── index.html          # Archivo principal con toda la aplicación
├── dat.gui.min.js       # Biblioteca para interfaz de usuario
├── gl-matrix-min.js     # Biblioteca de matemáticas 3D
├── .gitignore          # Archivos ignorados por git
└── README.md           # Este archivo
```

## 🎯 Características técnicas

- **Vertex Shaders**: Transforman las coordenadas de los vértices
- **Fragment Shaders**: Definen los colores de los píxeles
- **Matrix Stack**: Sistema de matrices para transformaciones jerárquicas
- **Orbit Animation**: Animación fluida usando `requestAnimationFrame`
- **Interactive GUI**: Controles en tiempo real para manipular la simulación

## 🌌 Física y matemáticas

- Cada planeta tiene su propia velocidad orbital
- Las órbitas son circulares para simplicidad
- Se utilizan matrices 4x4 para todas las transformaciones
- Sistema de coordenadas 3D con rotaciones en X, Y, Z

## 🎓 Propósito educativo

Este proyecto es ideal para:
- Aprender WebGL y gráficos 3D
- Entender transformaciones de matrices
- Visualizar conceptos astronómicos
- Experimentar con shaders GLSL
- Practicar JavaScript y matemáticas 3D

¡Explora el cosmos desde tu navegador! 🌠