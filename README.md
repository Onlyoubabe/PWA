# Sistema de Gestión de Alquileres

Este es un sistema moderno para la gestión de propiedades y alquileres, construido con el último stack tecnológico de Laravel.

## 🚀 Tecnologías

*   **Framework:** [Laravel 12](https://laravel.com)
*   **Frontend:** [Livewire 3](https://livewire.laravel.com) + Volt + Flux
*   **Estilos:** [Tailwind CSS 4](https://tailwindcss.com)
*   **Base de Datos:** SQLite (Configurable)

## ✨ Características Principales

*   **Gestión de Propiedades:** CRUD completo para administrar inmuebles (precio, dirección, estado, descripción).
*   **Gestión de Inquilinos:** Registro y administración de información de arrendatarios.
*   **Interfaz Moderna:** Diseño responsivo y fluido gracias a Tailwind y Flux UI.

## 🛠️ Instalación y Configuración

Sigue estos pasos para levantar el proyecto en tu entorno local:

1.  **Clonar el repositorio:**
    ```bash
    git clone https://github.com/Onlyoubabe/PWA.git
    cd PWA
    ```

2.  **Instalar dependencias de PHP:**
    ```bash
    composer install
    ```

3.  **Instalar dependencias de Node:**
    ```bash
    npm install
    npm run build
    ```

4.  **Configurar entorno:**
    ```bash
    cp .env.example .env
    php artisan key:generate
    touch database/database.sqlite
    ```

5.  **Ejecutar migraciones:**
    ```bash
    php artisan migrate
    ```

6.  **Iniciar servidor:**
    ```bash
    php artisan serve
    ```

El sitio estará disponible en `http://127.0.0.1:8000`.

## 📄 Licencia

Este proyecto es de código abierto y está bajo la licencia [MIT](https://opensource.org/licenses/MIT).
