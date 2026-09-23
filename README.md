# ClubDeportivo

Aplicación Android para la gestión operativa de un club deportivo.

![Logo del club](logo_club.png)

## Funcionalidades

- Gestión de socios y no socios.
- Registro y administración de actividades.
- Inscripciones a actividades.
- Gestión de pagos y consulta de facturas.
- Administración de profesores y suplencias.
- Módulo de nutrición.
- Listados de socios, no socios, actividades, pagos, inscripciones, profesores y morosos.

## Versiones y requisitos

Las versiones verificadas en el código del proyecto son:

- Gradle Wrapper: `9.3.1` (`gradle/wrapper/gradle-wrapper.properties`).
- Android Gradle Plugin: `9.1.0` (`gradle/libs.versions.toml`).
- Compile SDK: Android `36.1`.
- Target SDK: Android `36`.
- Minimum SDK: Android `7.0` (API `24`).
- Java para compilar el código: `11`.
- JDK configurado en Android Studio: `jbr-21`.
- Android Studio: Iguana.

## Ejecutar el proyecto

1. Clona el repositorio y ábrelo en Android Studio.
2. Espera a que Gradle sincronice las dependencias.
3. Conecta un dispositivo Android o inicia un emulador.
4. Ejecuta la configuración `app`.

También puedes compilar desde la terminal:

```bash
./gradlew assembleDebug
```

En Windows:

```powershell
.\gradlew.bat assembleDebug
```

El APK de depuración se genera en `app/build/outputs/apk/debug/`.

## Tecnología

- Kotlin DSL para la configuración de Gradle.
- Java 11.
- Gradle Wrapper 9.3.1.
- Android Gradle Plugin 9.1.0.
- Android SDK con `minSdk 24` y `targetSdk 36`.
- AndroidX y Material Components.
- ConstraintLayout.
- Navigation Component.
- View Binding.

## Estructura

- `app/src/main/java`: actividades y lógica de la aplicación.
- `app/src/main/res/layout`: diseños de las pantallas y diálogos.
- `app/src/main/res/drawable`: iconos y recursos gráficos.
- `app/src/main/res/values`: textos, temas y colores.
- `app/src/test`: pruebas unitarias.
- `app/src/androidTest`: pruebas instrumentadas.

## Identificador de la aplicación

- Namespace: `com.example.clubdeportivo`
- Application ID: `com.example.clubdeportivo`
- Versión inicial: `1.0` (1)
