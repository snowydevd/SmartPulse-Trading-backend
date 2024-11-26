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

## Endpoints

### Autenticación
- `POST /auth/register`: Registro de nuevos usuarios.  
- `POST /auth/login`: Inicio de sesión de usuarios existentes.  

### Datos del mercado
- `GET /market/data`: Obtiene datos de mercado en tiempo real desde la API de MarketStack.  

### Recomendaciones con IA
- `POST /ai/recommendations`: Genera recomendaciones y análisis basados en los últimos datos del mercado.  

## Tecnologías utilizadas

- **Framework**: Laravel  
- **API**: MarketStack  
- **Autenticación**: Firebase  
- **IA**: AI Genkit  
- **Base de datos**: MySQL / PostgreSQL (configurable)  

