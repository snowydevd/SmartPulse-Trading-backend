# SmartPulse Trading - Backend

## Descripción

El backend de **SmartPulse Trading** es el núcleo del sistema que combina datos de mercado en tiempo real, autenticación segura y generación de inteligencia artificial para proporcionar recomendaciones y análisis personalizados. Este backend está construido con **Laravel**, utilizando las siguientes tecnologías clave:

- **MarketStack API**: Para obtener datos de mercado en tiempo real.
- **Firebase**: Manejo del sistema de autenticación.
- **AI Genkit**: Motor para las funcionalidades de inteligencia artificial.

## Características principales

- **Autenticación segura**: Sistema de login y registro basado en Firebase.
- **Datos en tiempo real**: Integración con MarketStack para consultar precios y parámetros recientes del mercado.
- **Recomendaciones con IA**: Generación de análisis personalizados y predicciones mediante AI Genkit.
- **Escalabilidad y flexibilidad**: Construido sobre Laravel para facilitar el desarrollo y mantenimiento.

## Requisitos previos

- **PHP** >= 8.0  
- **Composer** >= 2.0  
- **Laravel** >= 10.x  
- **Firebase SDK** configurado  
- API key de **MarketStack**  
- Configuración de **AI Genkit**  

## Instalación

1. Clona el repositorio:
   ```bash
   git clone https://github.com/usuario/smartpulse-backend.git
   cd smartpulse-backend
2. Instala las dependencias:
   ```bash
   composer install

3. Configura las variables de entorno .env:
- Configuración de base de datos.
- Claves de la API de MarketStack.
- Credenciales de Firebase.
- Configuración para AI Genkit.
- Genera la clave de aplicación:

bash
Copy code
php artisan key:generate
Ejecuta las migraciones:

bash
Copy code
php artisan migrate
Inicia el servidor:

bash
Copy code
php artisan serve
Endpoints
Autenticación
POST /auth/register: Registro de usuarios.
POST /auth/login: Inicio de sesión.
Datos del mercado
GET /market/data: Obtiene datos de mercado desde MarketStack.
Recomendaciones con IA
POST /ai/recommendations: Genera recomendaciones basadas en los últimos datos del mercado.
Tecnologías utilizadas
Framework: Laravel
API: MarketStack
Autenticación: Firebase
IA: AI Genkit
Base de datos: MySQL / PostgreSQL (configurable)
Contribuciones
¡Contribuciones son bienvenidas! Por favor, sigue estos pasos para contribuir:

Haz un fork del repositorio.
Crea una rama para tu funcionalidad (git checkout -b feature/nueva-funcionalidad).
Realiza un pull request a la rama principal del repositorio.
Licencia
Este proyecto está bajo la licencia MIT. Consulta el archivo LICENSE para más detalles.
