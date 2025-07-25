# 🏨 Booking.com

Clon estático de una página de reservas de alojamientos, inspirado en Booking.com, desarrollado con **HTML**, **CSS** y **Bootstrap**.  
Perfecto como ejercicio de **UI/UX**, **diseño web** y **desarrollo web** (aunque aún sin lógica de backend o formularios funcionales).

---

## 🚀 Características principales

- Maquetación con **Bootstrap 5** (navbar, grid, cards, modals, tooltips)
- **Modal de selección de idioma y moneda**
- **Buscador visual** con selección de fechas y personas
- **Filtros desplegables** para instalaciones, servicios y tipo de alojamiento
- Páginas individuales para dos alojamientos:

  - **`tierraDeVinos.html`**:  
    Hostal tradicional con ambientación colonial en Cafayate.  
    Se presenta con una galería de imágenes, mapa interactivo, tabla de disponibilidad según tipo de habitación, y un apartado completo con servicios, normas, condiciones para niños y métodos de pago.

  - **`domosDelViento.html`**:  
    Alojamiento tipo glamping también en Cafayate, rodeado de naturaleza.  
    Incluye puntuaciones, galería de imágenes, ubicación geográfica, descripción del entorno, características del domo y servicios más populares.

- **Página de error personalizada** (`error404.html`)
---

## 🛠️ Tecnologías y herramientas

- **HTML5**
- **CSS3**
- **Bootstrap 5.3.3**
- **Bootstrap Icons**
- **JavaScript** (mínimo, solo para tooltips)

---

## 📂 Estructura del proyecto

```
BOOKING.COM
├── assets/                     # Imágenes, logos, recursos estáticos
├── pages/
│   ├── createAccount.html      # Formulario alta de usuario (no funcional)
│   ├── logIn.html              # Formulario login (no funcional)
│   ├── domosDelViento.html     # Página individual del hotel "Domos del Viento"
│   ├── tierraDeVinos.html      # Página individual del hotel "Tierra de Vinos"
│   └── error404.html
├── styles/                     # Hojas de estilo por página
│   ├── account.css
│   ├── 404.css
│   ├── domosDelViento.css
│   ├── tierraDeVinos.css
│   ├── index.css
│   └── styles.css
├── index.html                  # Página principal
└── README.md
```

---

## 📌 Cómo ejecutar el proyecto

[![Netlify Status](https://img.shields.io/badge/Demo%20Online-Booking--LLDP-blue?logo=netlify&style=for-the-badge)](https://booking-lldp.netlify.app)

```bash
# Clonar este repositorio:
git clone https://github.com/tu-usuario/booking-clon.git

# Entrar a la carpeta:
cd BOOKING.COM

# Abrir `index.html` en tu navegador.
```

---
