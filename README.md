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

# PauFe Studio Web

Bienvenida al repositorio oficial de PauFe Studio. Aquí gestionamos el código de nuestra web.

## 🚀 Flujo de trabajo profesional (Git Flow)

Para mantener la estabilidad de la web, seguimos este flujo de trabajo utilizando ramas:
#Antes tengo que comprobar que estoy en el repositorio adecuado
ferna@Portatil MINGW64 ~/Documents/Feli_Velas/paufe-studio-web (develop)
$ git remote -v
origin  https://github.com/paufestudio/WebPauFeStudio.git (fetch)
origin  https://github.com/paufestudio/WebPauFeStudio.git (push)


1. **Trabajar en una rama nueva:**
   Cada vez que vayas a realizar un cambio o añadir algo nuevo:
   ```bash
   git checkout develop
   git pull origin develop
   git checkout -b nombre-de-tu-tarea
   Guardar cambios:
Una vez hechos tus cambios:

Bash
git add .
git commit -m "Descripción clara de los cambios realizados"
Integrar cambios:
Cuando tu tarea esté terminada y probada:

Bash
git checkout develop
git merge nombre-de-tu-tarea
git push origin develop
Publicar en Producción:
Cuando estés lista para que los cambios se vean en la web oficial:

Bash
git checkout main
git merge develop
git push origin main
Nota: Recuerda trabajar siempre desde develop para evitar errores en la rama principal (main).


***

### ¿Cómo añadirlo ahora mismo?
Si ya tienes abierto tu editor (o usando la terminal):

1. **Abre el archivo `README.md`** y pega ese texto al final.
2. **Guárdalo** y luego, para que se suba al repositorio:

```bash
git add README.md
git commit -m "Documentación: Añadido flujo de trabajo profesional al README"
git push origin main