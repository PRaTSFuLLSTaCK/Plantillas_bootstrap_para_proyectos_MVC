# Plantillas Bootstrap para Proyectos PHP (MVC)

Este repositorio contiene una colección de plantillas diseñadas con **Bootstrap** para su uso en proyectos **PHP** bajo el patrón **Modelo-Vista-Controlador (MVC)**. Estas plantillas están listas para ser integradas en cualquier desarrollo basado en PHP, facilitando la creación de interfaces modernas y responsivas.

## 🚀 Características

- **Diseño Responsivo:** Todas las plantillas están basadas en **Bootstrap 5**, garantizando compatibilidad con dispositivos móviles y escritorio.
- **Estructura Modular:** Diseñadas para integrarse fácilmente en proyectos con arquitectura MVC.
- **Código Limpio y Personalizable:** HTML, CSS y JavaScript estructurados para facilitar modificaciones y personalización.
- **Compatibilidad con PHP:** Se pueden usar con frameworks PHP como CodeIgniter, Laravel o desarrollos propios.

## 📂 Estructura del Repositorio

```
📂 templates/
 ├── 📂 admin/        # Plantilla para panel de administración
 ├── 📂 auth/         # Plantillas para login y registro
 ├── 📂 dashboard/    # Plantilla de panel de usuario
 ├── 📂 landing/      # Página principal con diseño atractivo
 ├── 📂 errors/       # Páginas de error personalizadas (404, 500, etc.)
 └── 📂 components/   # Elementos reutilizables como botones, cards, modales
```

## 📌 Requisitos

- PHP 7.4 o superior
- Bootstrap 5
- Un framework MVC en PHP (opcional, pero recomendado)

## 📖 Instalación y Uso

1. **Clonar el repositorio:**
   ```sh
   git clone https://github.com/tu_usuario/tu_repositorio.git
   ```
2. **Copiar la plantilla deseada en tu proyecto:**
   ```sh
   cp -r templates/landing /ruta_de_tu_proyecto/views/
   ```
3. **Integrar en tu estructura MVC:** Asegúrate de que tu controlador carga la vista correctamente, por ejemplo:
   ```php
   class HomeController {
       public function index() {
           include_once "views/landing/index.php";
       }
   }
   ```

## 📄 Licencia
Este proyecto está bajo la licencia **MIT**, lo que significa que puedes usarlo, modificarlo y distribuirlo libremente.

## 🤝 Contribuciones
Si deseas mejorar las plantillas o agregar nuevas, ¡las contribuciones son bienvenidas! Haz un **fork** del repositorio, realiza tus cambios y envía un **pull request**.

