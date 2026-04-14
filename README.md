
# Nexcent

**Proyecto:** Reto frontend — prueba técnica para Riwi

**Descripción**

Nexcent es una landing page de demostración creada como respuesta al reto técnico de frontend para Riwi. Es una página estática (HTML/CSS) que muestra un diseño de hero, sección de clientes, secciones de producto/comunidad, y un área de demo. El objetivo fue construir una interfaz responsiva, alineada con buenas prácticas semánticas y accesibilidad básica.

## Qué incluye este repositorio

- `index.html` — Página principal (marca las secciones: Hero, Clients, Community, Maecenas, Caring, Demo, Footer).
- `styles.css` — Estilos CSS con media queries y reglas responsivas.
- `assets/` — Imágenes y recursos usados en la maqueta.

## Capturas

<img width="1077" height="927" alt="nexcent1" src="https://github.com/user-attachments/assets/10038520-f3b3-414a-b61a-b90af33ce224" />
<img width="1067" height="867" alt="nexcent2" src="https://github.com/user-attachments/assets/cd813db2-6cf7-4170-805c-96525c61c342" />
<img width="1077" height="926" alt="nexcent3" src="https://github.com/user-attachments/assets/156caeb6-5656-4bb0-a962-f702f6f07a33" />

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


## Estado conocido

- La página está funcional y adaptada para la mayoría de anchos de pantalla comunes. En pantallas muy pequeñas, algunos textos podrían necesitar ajuste fino.

## Autor y créditos

Reto técnico para Riwi - 2025

Natalia Vargas Osorio
Email: nataliav0517@gmail.com





