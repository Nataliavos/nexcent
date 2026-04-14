
# Nexcent

**Proyecto:** Reto frontend — prueba técnica para Riwi

**Descripción corta**

Nexcent es una landing page de demostración creada como respuesta al reto técnico de frontend para Riwi. Es una página estática (HTML/CSS) que muestra un diseño de hero, sección de clientes, secciones de producto/comunidad, y un área de demo. El objetivo fue construir una interfaz responsiva, alineada con buenas prácticas semánticas y accesibilidad básica.

## Qué incluye este repositorio

- `index.html` — Página principal (marca las secciones: Hero, Clients, Community, Maecenas, Caring, Demo, Footer).
- `styles.css` — Estilos CSS con media queries y reglas responsivas.
- `assets/` — Imágenes y recursos usados en la maqueta.

## Capturas

Las imágenes están en `assets/images/`. Aquí hay algunas rutas de ejemplo usadas en la demo:

- `assets/images/Illustration.png` — Ilustración del hero
- `assets/images/Logo-*.png` — Logos de clientes y marcas

Puedes abrir el proyecto y ver las pantallas en diferentes tamaños (mobile/tablet/desktop).

## Funcionalidades implementadas

- Diseño responsivo con media queries para móviles y tablets.
- Menú hamburguesa accesible (botón con `aria-expanded`) para navegación en pantallas pequeñas.
- Grid y layout adaptativo para secciones: hero, maecenas, communities y cards de contenido.
- Imágenes fluidas (`max-width:100%`) y manejo básico del flujo visual en dispositivos pequeños.
- Pequeño script para toggling del menú y cierre al clicar fuera.
- Estructura semántica de secciones para facilitar SEO y accesibilidad.

## Cómo ejecutar / probar localmente

Forma rápida (abrir archivo):

1. Abrir `index.html` directamente en un navegador.

Forma recomendada (servidor local):

```bash
cd path/to/nexcent
python3 -m http.server 8000
# Abrir http://localhost:8000 en tu navegador
```

Esto evita problemas con rutas relativas en algunos navegadores.

## Notas y mejoras posibles

- Imágenes de ejemplo y algunos logos son marcadores; sustituir por assets finales si se dispone de ellos.
- Mejorar la experiencia de teclado y focus states para una accesibilidad completa.
- Añadir pruebas visuales (screenshots automáticos) y optimizaciones de rendimiento (lazy-loading de imágenes, compress).

## Estado conocido

- La página está funcional y adaptada para la mayoría de anchos de pantalla comunes. En pantallas muy pequeñas, algunos textos podrían necesitar ajuste fino.

## Autor y créditos

Reto técnico para Riwi — implementado por el/la autor(a) del repositorio. Añade tu nombre y contacto aquí.

---

Si quieres que convierta este README en inglés, añada una demo en video real o incluya capturas de pantalla dentro del README, dímelo y lo agrego.
This project is a landing page inspired by the Figma Nexcent mockup. It includes:

- Header with navigation and main hero.

- Sections with CSS Grid layouts (text + illustrations)
- Footer with columns of links

Technologies
- HTML5
- CSS3 (Grid + Flexbox)
- Google Fonts

Project structure:
/ (root)
├─ index.html 
├─ styles.css 
├─ README.md 
└─ assets/ 
    └─ images/
      └─ footer/ 


How to run:
Download or clone the project.

Open index.html in your browser.

Recommended: Use VS Code with the Live Server extension for automatic page reload.

Notes
Images and patterns are loaded from the assets/images and assets/images/footer folders.

Coder Information:
Full Name: Natalia Vargas Osorio
Clan: Hamilton
Email: nataliav0517@gmail.com
ID: 1017259440





