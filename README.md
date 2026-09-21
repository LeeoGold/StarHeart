# BigBang x U

> *Un pequeño universo hecho de estrellas, para que cada 21 de septiembre tu corazón explote por mí.*

---

## 💌 Una carta, escrita en estrellas

Para ti, hoy, y para todos los días por venir:

Hay momentos que no caben en palabras, y por eso los escribo con luz. Este proyecto es un universo que late, colapsa y vuelve a nacer una y otra vez — como un corazón que se atreve a explotar cada vez que te ve.

Las estrellas forman un corazón que late por ti, implosiona hasta un solo punto de luz, y entonces… el **Big Bang**: todas las estrellas estallan, se desbordan por la pantalla y, cuando parecen perdidas, se reúnen de nuevo. Porque todo lo que estalla con amor vuelve a encontrarse.

Espero que al abrirlo sientas lo mismo que siento yo cuando te pienso.

**Feliz 21 de setiembre. I love U.** 💫

---

## ✨ ¿Qué es?

`StarHeart` es una animación generativa en puro **HTML, CSS y JavaScript** (sin frameworks, sin builds, sin dependencias): un lienzo de ~800 estrellas que forman un corazón y protagonizan un ciclo infinito de latido, implosión, explosión y renacimiento.

### Fases del ciclo (31 segundos en total, en bucle infinito)

| Fase | Tiempo | Qué ocurre |
| ---- | ------ | ---------- |
| ❤️ **Latido** | 0 – 7 s | El corazón de estrellas late suavemente. |
| 💥 **Implosión** | 7 – 12 s | Todas las estrellas colapsan y se junten en el centro. |
| 🎆 **Big Bang** | 12 – 24 s | Explosión total: las estrellas se expanden por toda la pantalla, aparecen chispas temporales y, entre 14 y 22 segundos, el texto de la dedicatoria aparece en el centro. |
| 🌱 **Reconstrucción** | 24 – 31 s | Las estrellas regresan a formar el corazón desde cero. |

---

## 🎨 Detalles técnicos

- **Estrellas (800):** asteriscos dibujados en canvas con rotación individual.
- **Paleta:** dorado, amarillo y lavanda sobre un espacio azul profundo (`#030518`).
- **Nitidez:** el canvas usa `devicePixelRatio` para verse nítido en cualquier pantalla.
- **Fluidez:** el bucle corre limitado a ~45 FPS para un movimiento suave y constante.
- **Tipografía:** *Great Vibes* (Google Fonts) con respaldo a *Georgia*, cargada antes de dibujar el texto para evitar parpadeos.
- **Favicon:** un corazón emoji embebido (sin archivos externos).
- **Música:** botón de play circular que abre el video dedicado en YouTube.

---

## 🚀 Cómo usarlo

Es un archivo único. No requiere instalar nada:

1. Descarga la carpeta (o clona el repositorio).
2. Abre `index.html` con cualquier navegador (doble clic).
3. Si quieres música, pulsa el botón ▶ (esquina superior derecha).

### Publicar en GitHub

```bash
git init
git add .
git commit -m "BigBang x U: un universo de estrellas para ti"
git branch -M main
git remote add origin https://github.com/tu-usuario/StarHeart.git
git push -u origin main
```

---

## 📂 Estructura del proyecto

```
StarHeart/
├── index.html   # Toda la aplicación (HTML + CSS + JS)
└── README.md    # Este archivo
```

---

## 🛠️ Tecnologías

- HTML5
- CSS3
- JavaScript (Canvas 2D + `requestAnimationFrame`)

---

## 💡 Ideas futuras

- Modo "silencio" con activación de música por primera interacción.
- Más fases o motivos (galaxias, nebulosas, constelaciones).
- Compartir en pantalla completa como épica visual.

---

## 📜 Licencia

Hecho con amor, para regalar. Úsalo, abrázalo, compártelo — un corazón como este no se puede patentar. 💖