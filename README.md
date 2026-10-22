# 100 Mexicanos Dijeron

Juego estilo "Family Feud" en HTML/JS puro (sin dependencias). Funciona en GitHub Pages.

## Publicar en GitHub Pages
1. Crea un repo y sube todo el contenido de esta carpeta.
2. Settings → Pages → Source: `main` / root.
3. Abre `https://TU-USUARIO.github.io/NOMBRE-REPO/`.

## Cómo editar
- **Dentro del juego:** `Esc` → *4 Editar preguntas* (también nombre, equipos y rondas). Se guarda en el navegador; usa *Exportar JSON* para respaldar.
- **En el código:** edita `preguntas.js` (valores por defecto para todos).
- **Voz:** el juego lee preguntas y respuestas (menú 3 para elegir voz, velocidad y tono).
- **Sonidos:** pon MP3 en `sounds/` llamados `intro, reveal, strike, buzz, win`.
- **Skins:** menú *1* o agrega skins en el CSS (`body[data-skin=...]`).

## Teclas (configurables en el menú 2)
`1-9` revelar · `X` error · `Z` pulsador azul · `M` pulsador rojo · `← / →` dar puntos al azul / rojo · `N` siguiente ronda · `R` reiniciar pulsadores · `V` leer pregunta de nuevo · `F` pantalla completa · `Esc` menú

## Rondas
5 rondas con multiplicadores `1,1,1,2,3` (editable). Gana el equipo con más puntos al terminar.
