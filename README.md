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
- `index.html`: Estructura del sitio y scripts interactivos.
- `style.css`: Estilos visuales globales y diseño responsivo.
- `/assets`: Carpeta que contiene las imágenes de los productos (formatos `.png`, `.jpeg`).

## 💻 Instalación y Despliegue Local
1. Clona este repositorio:
   ```bash
   git clone [https://github.com/tu-usuario/WebPauFeStudio.git](https://github.com/tu-usuario/WebPauFeStudio.git)
   ## 🚀 Flujo de Trabajo y Comandos Git

Si realizas cambios en el catálogo, utiliza los siguientes comandos estándar para guardar tu progreso.

### 1. Guardar cambios (Commit habitual)
Cada vez que agregues nuevos productos o modifiques los precios, ejecuta:
```bash
# Ver qué archivos han cambiado
git status

# Añadir todos los cambios al escenario
git add .

# Guardar los cambios con un mensaje descriptivo
git commit -m "Feat: Añadidos nuevos ambientadores de yeso para coche y ajustes móviles"

# Subir los cambios a GitHub (si usas repositorio remoto)
git push origin main