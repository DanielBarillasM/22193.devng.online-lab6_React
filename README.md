# 🎮 Juego de Memoria Mejorado

Este proyecto consiste en un juego de memoria implementado completamente en **React**, utilizando únicamente un **archivo HTML** que incluye el código JavaScript, JSX y CSS necesarios. No se utiliza create-react-app, Vite ni herramientas externas de empaquetado, cumpliendo con los requerimientos del curso.

---

## 🎯 Objetivos del Proyecto

- Practicar el uso de **librerías externas de JavaScript** como `lodash`, `canvas-confetti`, `React`, `ReactDOM` y `Babel-standalone`.
- Configurar un **entorno mínimo** para desarrollar en React sin herramientas como CRA o Vite.
- Aplicar conceptos básicos sobre **Babel**, JSX y el flujo de componentes en React.
- Implementar una interfaz animada, funcional y visualmente atractiva, que cumpla con los criterios de evaluación establecidos.

---

## ✅ Funcionalidades Implementadas

- ✅ Cuadrícula de **4x4 tarjetas** con disposición aleatoria al inicio.
- ✅ Tarjetas **boca abajo** al comenzar el juego.
- ✅ Volteo animado de tarjetas con CSS y React.
- ✅ Verificación automática de coincidencia entre parejas.
- ✅ Reversión automática si no coinciden (con espera).
- ✅ **Contador de movimientos** visible en todo momento.
- ✅ **Mensaje de juego completado** al terminar.
- ✅ Interfaz con diseño visual moderno y responsivo.
- ✅ Código organizado, comentado y estructurado en un único archivo `index.html`.

---

## 🧠 Tecnologías Usadas

- 💡 **React** para la estructura del juego.
- ⚙️ **Babel Standalone** para convertir JSX directamente en el navegador.
- 🎲 **Lodash** para el mezclado aleatorio de las tarjetas.
- 🎉 **Canvas Confetti** para animar la victoria.
- 🎨 **CSS Grid** y animaciones con `transform` y `perspective`.

---

## 🧪 Cómo Ejecutar el Juego Localmente

### A. Usando Python (servidor HTTP local)

1. Asegúrese de tener **Python instalado** (versión 3).
2. Abra la terminal en la carpeta donde esta el `index.html`:
   ```bash
   cd /ruta/al/proyecto
   ```
3. Ejecute el servidor HTTP:
   ```bash
   python -m http.server 8000
   ```
4. Abra su navegador en:
   ```
   http://localhost:8000/
   ```

---

## 🌐 Publicación del Juego Online

### GitHub Pages

1. El juego está disponible en:
   ```
   https://danielbarillasm.github.io/
   ```

---

## 🌐 Publicación del Juego Online en el server

### Server: devng.online

1. El juego está disponible también en:
   ```
   https://22193.devng.online/lab6/
   ```

---

## 🧾 Criterios de Evaluación

| Criterio                                                                 | Puntos |
|--------------------------------------------------------------------------|--------|
| Diseño visual de la interfaz (criterio subjetivo)                        | 40 pts |
| Animación de volteo de las tarjetas                                      | 10 pts |
| Calidad de la animación (suavidad, feedback)                             | 30 pts |
| Tarjetas en posiciones aleatorias cada vez                               | 20 pts |
| Mostrar mensaje de "juego completado" al finalizar                       | 20 pts |
| Contador visible de movimientos                                          | 10 pts |
| Publicación en GitHub con URL compartida                                 | 10 pts |
| Uso de **CSS Grid**                                                      |  5 pts |
| ❌ Penalización si se usa CRA o Vite                                    | -50 pts |

---

## 📂 Estructura del Proyecto

```
📁 proyecto-juego-memoria
└── 📄 index.html   <-- Contiene TODO: React, CSS, JS y HTML
└── 📄 README.md    <-- Este archivo
```

---

**¡Gracias por revisar este proyecto y que disfrute jugando! 🧠🃏**
