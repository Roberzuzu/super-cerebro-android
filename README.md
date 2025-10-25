# Super Cerebro Android

## Descripción

Super Cerebro Android es una aplicación nativa para Android diseñada para gestionar tiendas WooCommerce con el poder de la Inteligencia Artificial. Esta aplicación permite a los propietarios de tiendas administrar sus productos, pedidos e inventario de manera eficiente desde dispositivos móviles, aprovechando capacidades de IA para optimizar la gestión del comercio electrónico.

## Características Principales

- 🛍️ **Gestión de Productos**: Administra el catálogo de productos de tu tienda WooCommerce
- 📦 **Control de Pedidos**: Visualiza y gestiona pedidos en tiempo real
- 🤖 **Integración con IA**: Funcionalidades potenciadas con Inteligencia Artificial para ayudar en la gestión
- 📱 **Interfaz Nativa Android**: Experiencia optimizada para dispositivos Android
- 🔄 **Sincronización en Tiempo Real**: Mantén tu tienda actualizada desde cualquier lugar

## Requisitos Previos

Antes de compilar y ejecutar la aplicación, asegúrate de tener instalado:

- **Android Studio** (versión Arctic Fox o superior)
- **JDK** 11 o superior
- **SDK de Android** (API nivel 24 o superior)
- **Gradle** 7.0 o superior (incluido con Android Studio)

## Instalación

### 1. Clonar el Repositorio

```bash
git clone https://github.com/Roberzuzu/super-cerebro-android.git
cd super-cerebro-android
```

### 2. Abrir en Android Studio

1. Abre Android Studio
2. Selecciona "Open an Existing Project"
3. Navega hasta la carpeta del proyecto clonado
4. Espera a que Gradle sincronice las dependencias

### 3. Configurar el Proyecto

Crea un archivo `local.properties` en la raíz del proyecto si no existe, y configura la ruta del SDK:

```properties
sdk.dir=/ruta/a/tu/Android/sdk
```

## Compilación

### Compilar desde Android Studio

1. En Android Studio, selecciona **Build > Make Project** o presiona `Ctrl+F9` (Windows/Linux) o `Cmd+F9` (Mac)
2. Espera a que la compilación finalice sin errores

### Compilar desde la Línea de Comandos

#### En Windows:
```bash
gradlew.bat assembleDebug
```

#### En Linux/Mac:
```bash
./gradlew assembleDebug
```

El APK compilado se generará en: `app/build/outputs/apk/debug/`

## Ejecución

### Ejecutar en Emulador

1. En Android Studio, crea un AVD (Android Virtual Device) desde **Tools > Device Manager**
2. Selecciona el dispositivo virtual
3. Presiona el botón **Run** (triángulo verde) o presiona `Shift+F10`

### Ejecutar en Dispositivo Físico

1. Habilita las **Opciones de Desarrollador** en tu dispositivo Android
2. Activa la **Depuración USB**
3. Conecta el dispositivo a tu computadora mediante USB
4. Selecciona tu dispositivo en Android Studio
5. Presiona el botón **Run**

## Estructura del Proyecto

```
super-cerebro-android/
├── app/                    # Módulo principal de la aplicación
├── build.gradle.kts        # Configuración de Gradle del proyecto
├── settings.gradle.kts     # Configuración de módulos
├── gradle/                 # Wrapper de Gradle
└── README.md              # Este archivo
```

## Tecnologías Utilizadas

- **Kotlin** - Lenguaje de programación principal
- **Android SDK** - Framework de desarrollo Android
- **Gradle** - Sistema de compilación
- **WooCommerce REST API** - Integración con tiendas WooCommerce
- **Inteligencia Artificial** - Funcionalidades de IA integradas

## Contribuciones

Las contribuciones son bienvenidas. Por favor:

1. Haz un Fork del proyecto
2. Crea una rama para tu función (`git checkout -b feature/nueva-funcionalidad`)
3. Realiza tus cambios y haz commit (`git commit -m 'Agregar nueva funcionalidad'`)
4. Sube los cambios a tu rama (`git push origin feature/nueva-funcionalidad`)
5. Abre un Pull Request

## Licencia

Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.

## Contacto

Para preguntas o soporte, por favor abre un issue en este repositorio.

---

**Nota**: Esta aplicación requiere una tienda WooCommerce activa y credenciales API válidas para funcionar correctamente.
