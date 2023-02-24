# Convierte un SVG en un PNG poniendo padding con background transparente tanto para el padding como para el icono
convert -background transparent input.svg -background transparent -gravity center -scale 112x112 -extent 128x128 output.png
