# ACTIVIDADCSSavanzado
# UI Library - Componentes Reutilizables con CSS Avanzado

Este proyecto presenta una colección de componentes de interfaz de usuario creados con HTML y CSS puro, diseñados para ser reutilizables, personalizables y responsive, perfectos para ser implementados en cualquier proyecto web.

## ¿Qué incluye esta biblioteca?

- Botones (primario, secundario, hover, disabled)
- Tarjetas de contenido
- Campos de formulario (inputs, textarea, select, checkboxes)
-  Navbar responsiva
-  Ventana modal (popup)

# Estructura del proyecto

ui-library/
components/ Archivos CSS de cada componente
      button
      card
      form
      navbar
      modal

Styles/ Variables, base y utilidades globales
     variables css
     Image

demo/ Página demostrativa
      index.html

      README.md # Esta guía  

         USO

1. Importar los estilos

Agrega en  HTML las hojas de estilo

   html
<link rel="stylesheet" href="estilos.css">   

2. Usar los componentes, por ejemplo:

<button class="btn primary">Visualizar</button>
<nav class="navbar">
<button onclick="document.getElementById('miModal').classList.add
('modal--open')">Abrir Modal</button>
 <div class="card">

##  Personalización de la pagina
Podemos modificar fácilmente las variables CSS para adaptar el diseño a nuestrar necesidades.

body {
  background-color: aqua;
}
:root{
  --color-primary:hwb(65 82% 8%) ;
  --color-secondary: #3498db;
  --color-danger: #27ae60;
  --text-color:rgb(22, 10, 10);
  --border-radius: 8px;
  --padding: 10px  20px;
}

## Demo
Abrimos el archivo demo/biblioteca.html en njuestro navegador para ver todos los componentes funcionando.

## Tecnologias
Las tecnologías utilizadas son: Webp, JavaScript DOM, flexbox, CSS, variables, , clases, elementos, animaciones y transiciones suaves, entre otros. Dependiendo del componente se ha implementado el estilo.

## Licencia
Este proyecto es de uso libre para fines educativos. Se puede adaptar a sus necesidades.
