// Selecciona todos los enlaces de la barra de navegación
const navLinks = document.querySelectorAll('.navbar-link');

// Obtiene la URL actual (solo la parte del archivo)
const currentPage = window.location.pathname.split('/').pop();

navLinks.forEach(link => {
    // Verifica si el `href` del enlace coincide con la página actual
    if (link.getAttribute('href') === currentPage) {
        link.classList.add('active');
    }
});
