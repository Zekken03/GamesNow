# GamesNow

## Descripción
GamesNow es una plataforma web dedicada a la publicación de contenido relacionado con videojuegos, donde los usuarios pueden encontrar noticias, análisis, guías y más información sobre la industria de los videojuegos.

**Sitio web:** [games-now.skyzerozx.com/GamesNow](https://games-now.skyzerozx.com/GamesNow/index.php)

## Características

- **Sistema de Usuarios**: Registro e inicio de sesión de usuarios.
- **Panel de Administración**: Gestión completa del contenido y usuarios del sitio.
- **Artículos**: Publicación y gestión de diferentes tipos de contenido (noticias, análisis, guías).
- **Comentarios**: Sistema de comentarios para interactuar con el contenido.
- **Autores**: Gestión de creadores de contenido.
- **Diseño Responsive**: Interfaz adaptable a diferentes dispositivos.

## Tecnologías Utilizadas

- **Frontend**: HTML5, CSS3, JavaScript
- **Backend**: PHP
- **Base de Datos**: MySQL
- **Frameworks/Librerías**: Bootstrap
- **Componentes Adicionales**: WYSIWYG Editor para la creación de contenido

## Estructura del Proyecto

```
.
├── index.html/php         # Página principal
├── iniciar.html/php       # Página de inicio de sesión
├── registro.html/php      # Página de registro
├── admin/                 # Área de administración
│   ├── BD/                # Scripts SQL
│   └── php/               # Scripts PHP para administración
├── css/                   # Estilos CSS
├── dashboard/             # Panel de control
│   ├── add/               # Sección para añadir contenido
│   └── js/                # Scripts JavaScript para el dashboard
├── img/                   # Imágenes del sitio
│   ├── articulosImg/      # Imágenes de artículos
│   └── autoresImg/        # Imágenes de autores
├── layouts/               # Componentes reutilizables (header, aside)
├── lib/                   # Librerías externas
└── src/                   # Código fuente adicional
```

## Instalación

Puedes acceder directamente al sitio en vivo: [https://games-now.skyzerozx.com/GamesNow/index.php](https://games-now.skyzerozx.com/GamesNow/index.php)

Para instalación local:

1. Clona este repositorio:
   ```
   git clone https://github.com/Zekken03/Zekken03.github.io.git
   ```

2. Importa la base de datos desde `admin/BD/gamesnow.sql`.

3. Configura la conexión a la base de datos en `admin/php/conexion.php`.

4. Asegúrate de tener un servidor web con soporte para PHP y MySQL (como XAMPP, WAMP o LAMP).

5. Accede al sitio a través de tu navegador web.

## Uso

### Para usuarios:
- Navega por los artículos disponibles.
- Registra una cuenta para comentar en los artículos.
- Inicia sesión para acceder a funciones adicionales.

### Para administradores:
- Accede al panel de administración con credenciales de administrador.
- Gestiona artículos, autores, usuarios y comentarios.
- Añade, edita o elimina contenido según sea necesario.

## Contribución

Si deseas contribuir a este proyecto:

1. Haz un fork del repositorio.
2. Crea una rama para tu función (`git checkout -b feature/nueva-funcion`).
3. Realiza tus cambios y haz commit (`git commit -m 'Añadir nueva función'`).
4. Sube los cambios a tu fork (`git push origin feature/nueva-funcion`).
5. Abre un Pull Request.


Enlace del proyecto: https://github.com/Zekken03/Zekken03.github.io
