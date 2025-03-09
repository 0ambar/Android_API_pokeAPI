# PokeApi by DaniVegaM

Esta es una aplicación desarrollada en **Kotlin** que consume la [PokeAPI](https://pokeapi.co) para listar y mostrar detalles de los Pokémon. La app implementa dos pantallas principales:
- **Pantalla principal**: Muestra una lista de todos los pokemones.
- **Pantalla de detalles**: Al seleccionar un Pokémon, se muestra información detallada y estadísticas sobre el mismo.

La aplicación utiliza principalmente las siguiente librerias:
- **Kotlin**
- **MVVM (Model-View-ViewModel)**
- **ViewBinding**
- **Navigation Component**
- **Retrofit y OkHttp** (para las llamadas a la API)
- **Coroutines** (para el manejo de operaciones asíncronas)
- **Paging 3** (para la paginación de datos)
- **Dagger Hilt** (para la inyección de dependencias)

## Estructura del Proyecto

A continuación, se detalla la función de cada carpeta y parte del código:

### Carpeta `app`
Contiene todo el código fuente y recursos de la aplicación Android.

- **src/main**:
    - **AndroidManifest.xml**: Archivo de configuración esencial que declara componentes de la aplicación (actividades, servicios, etc.) y permisos.
    - **java/**:  
      Aquí se encuentra el código Kotlin organizado en diferentes paquetes, que podrían incluir:
        - **UI**: Actividades y fragmentos que implementan las pantallas de la aplicación, como la lista de Pokémon y la pantalla de detalles.
        - **ViewModel**: Clases que gestionan la lógica de presentación y actúan de intermediarias entre la UI y la capa de datos.
        - **Repository**: Encargado de manejar la lógica de acceso a datos, incluyendo la comunicación con la PokeAPI.
        - **Models**: Clases de datos que representan los Pokémon y sus estadísticas.
        - **Networking**: Configuración de Retrofit, OkHttp y servicios necesarios para realizar las peticiones a la API.
    - **res/**:  
      Contiene todos los recursos de la aplicación, como:
        - **layout/**: Archivos XML que definen la estructura de las interfaces de usuario para cada pantalla.
        - **values/**: Archivos de recursos que incluyen cadenas, colores, estilos, dimensiones, etc.
        - **drawable/**: Imágenes, íconos y otros recursos gráficos usados en la app.

### Carpeta `gradle`
Incluye archivos y scripts relacionados con la configuración y el wrapper de Gradle, necesarios para compilar el proyecto de manera consistente en diferentes entornos.

### Carpeta `previews`
Contiene imágenes o archivos de previsualización que pueden utilizarse para mostrar capturas de pantalla o vistas previas del diseño de la aplicación.

## Requisitos Previos

Antes de ejecutar el proyecto, asegúrate de contar con lo siguiente:

- **Android Studio** (versión recomendada: Arctic Fox o superior)
- **JDK 11** o superior
- **Gradle** (Android Studio lo administra automáticamente)
- **Conexión a Internet** (para descargar las dependencias y obtener datos de la API)

## Pasos para ejecutar el proyecto

1. Clonar este repositorio en tu máquina local. (Puedes usar el comando `git clone` para esto)
2. Abrir este proyecto con Android Studio y te pedira descargar y sicronizar el proyecto con las dependencias necesarias
3. Una vez aceptadas las dependencias y tu proyecto sincronizado, puedes dar click en el boton de `PLAY` para que pueda empezar la simulación del proyecto en tu maquina local
4. Disfruta de esta APP que consume la PokeAPI :]


