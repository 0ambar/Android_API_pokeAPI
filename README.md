### Resumen de la Aplicación de Pokémon en Kotlin

Esta aplicación, desarrollada en **Kotlin**, consume la [PokeAPI](https://pokeapi.co) para listar y mostrar detalles de Pokémon. Está estructurada en dos pantallas principales:

1. **Pantalla principal**: Muestra una lista de todos los Pokémon.
2. **Pantalla de detalles**: Al seleccionar un Pokémon, se muestra información detallada y sus estadísticas.

---

### Tecnologías y Librerías Utilizadas
- **Kotlin**: Lenguaje de programación principal.
- **MVVM (Model-View-ViewModel)**: Arquitectura para separar la lógica de la interfaz de usuario.
- **ViewBinding**: Para vincular vistas de manera segura.
- **Navigation Component**: Gestiona la navegación entre pantallas.
- **Retrofit y OkHttp**: Para realizar llamadas a la API.
- **Coroutines**: Manejo de operaciones asíncronas.
- **Paging 3**: Paginación de datos para la lista de Pokémon.
- **Dagger Hilt**: Inyección de dependencias.

---

### Estructura del Proyecto

#### Carpeta `app`
Contiene el código fuente y recursos de la aplicación.

- **src/main**:
  - **AndroidManifest.xml**: Configuración esencial de la aplicación.
  - **java/**: Código Kotlin organizado en paquetes:
    - **UI**: Actividades y fragmentos para las pantallas.
    - **ViewModel**: Lógica de presentación.
    - **Repository**: Acceso a datos y comunicación con la API.
    - **Models**: Clases de datos para Pokémon y estadísticas.
    - **Networking**: Configuración de Retrofit y servicios API.
  - **res/**: Recursos de la aplicación:
    - **layout/**: Archivos XML para las interfaces de usuario.
    - **values/**: Cadenas, colores, estilos, etc.
    - **drawable/**: Imágenes y recursos gráficos.

#### Carpeta `gradle`
Contiene scripts y configuración de Gradle para compilar el proyecto.

#### Carpeta `previews`
Incluye imágenes o archivos de previsualización de la aplicación.

---

### Requisitos Previos
- **Android Studio** (versión Arctic Fox o superior).
- **JDK 11** o superior.
- **Gradle** (administrado por Android Studio).
- **Conexión a Internet** (para descargar dependencias y obtener datos de la API).

---

### Pasos para Ejecutar el Proyecto
1. Clona el repositorio en tu máquina local:
   ```bash
   git clone <URL-del-repositorio>
   ```
2. Abre el proyecto en **Android Studio**.
3. Sincroniza el proyecto para descargar las dependencias necesarias.
4. Haz clic en el botón **PLAY** para ejecutar la aplicación en un emulador o dispositivo físico.
5. ¡Disfruta de la aplicación que consume la PokeAPI! 😊
