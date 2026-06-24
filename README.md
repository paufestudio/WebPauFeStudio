# Paufe Studio | Catálogo Web Móvil

Aplicación web interactiva que funciona como catálogo digital para **Paufe Studio**, especializada en artesanías de velas, yeso y flores secas.

## 🚀 Características
- **Carrusel Principal:** Slider dinámico automatizado en la sección Home.
- **Catálogo Organizado:** Navegación categórica lateral y visualización en cuadrícula (*Grid*).
- **Mini-Carruseles de Producto:** Deslizadores manuales independientes dentro de tarjetas de producto con múltiples variantes de imagen.
- **Efecto Lightbox:** Visualización expandida (zoom) de imágenes de productos al hacer clic.
- **Diseño Responsivo:** Adaptado para una óptima visualización en dispositivos de escritorio, tablets y smartphones.
- **Acceso Directo a Pedidos:** Enlace integrado directo hacia WhatsApp.

## 🛠️ Tecnologías utilizadas
- **HTML5** (Estructura semántica)
- **CSS3** (Layouts con Grid y Flexbox, variables, Media Queries adaptativas)
- **JavaScript Vanila** (Lógica de carruseles, mini-slides y Lightbox)
- **FontAwesome v6.0.0** (Iconografía de navegación)

## 📁 Estructura del Proyecto
- `index_5.html`: Estructura del sitio y scripts interactivos.
- `style_2.css`: Estilos visuales globales y diseño responsivo.

---

## 💻 Flujo de Trabajo y Comandos Git

Si realizas cambios cotidianos en el catálogo (actualizar precios, corregir textos o añadir productos), utiliza los siguientes comandos estándar para guardar tu progreso en Git:

```bash
# 1. Ver qué archivos han cambiado o son nuevos
git status

# 2. Añadir todos los cambios al escenario de preparación
git add .

# 3. Guardar los cambios con un mensaje descriptivo
git commit -m "Feat: Añadidos nuevos ambientadores de yeso para coche y ajustes móviles"

# 4. Subir los cambios a tu repositorio de GitHub
git push origin main

#Opción A: Crear una Rama para una Campaña Nueva
# 1. Asegúrate de estar en la rama principal y totalmente actualizada
git checkout main
git pull origin main

# 2. Crea y muévete a la nueva rama estacional
git checkout -b campaña-navidad

# [!] En este punto ya puedes editar tu index_5.html: poner fotos de árboles, cambiar banners, añadir velas navideñas, etc.

# 3. Guarda los cambios exclusivos de Navidad
git add .
git commit -m "Design: Cambiados colores a tonos rojos/dorados y añadidas velas de Navidad"

# 4. Sube esta rama estacional a GitHub para que quede respaldada
git push -u origin campaña-navidad


#https://github.com/tu-usuario/WebPauFeStudio.git
https://loren2013.github.io/paufe-studio/
#https://paufestudio.netlify.app/