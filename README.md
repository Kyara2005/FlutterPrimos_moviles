# flutter_application_1

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Learn Flutter](https://docs.flutter.dev/get-started/learn-flutter)
- [Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Flutter learning resources](https://docs.flutter.dev/reference/learning-resources)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.



## Autor

**Kyara Altamirano**

## Requisitos Previos

Antes de iniciar la instalación es necesario contar con:

* Visual Studio Code
* Android Studio
* Extensión Flutter para VS Code
* Extensión Dart para VS Code
* Git instalado y configurado

## Instalación de Flutter

### 1. Crear un nuevo proyecto Flutter

1. Abrir Visual Studio Code.
2. Presionar **F1** para abrir la paleta de comandos.
3. Escribir **Flutter**.
4. Seleccionar **Flutter: New Project**.
5. Elegir la ubicación donde se instalará el SDK de Flutter.
6. Seleccionar **Download SDK** cuando VS Code lo solicite.
7. Esperar a que finalice la descarga e instalación.
8. Agregar Flutter al PATH del sistema.

### 2. Configuración de Android Studio

1. Abrir Android Studio.
2. Ir a:

```text
Tools > SDK Manager
```

3. Verificar y configurar correctamente la ruta del Android SDK.

### 3. Verificación de la instalación

Ejecutar el siguiente comando:

```bash
flutter doctor
```

Este comando permite comprobar si Flutter fue instalado correctamente y detectar posibles problemas de configuración.

## Solución de Problemas

![Captura de los errores](https://github.com/user-attachments/assets/1d85e23f-69a0-4035-92c7-945186e8911e)

### Error: cmdline-tools is missing

Si aparece el mensaje:

```text
cmdline-tools component is missing
```

Realizar los siguientes pasos:

1. Abrir Android Studio.
2. Ir a:

```text
SDK Manager > SDK Tools
```

3. Instalar o habilitar:

* Android SDK Command-line Tools (latest)

4. Ejecutar:

```bash
flutter doctor -v
```

para verificar que Flutter detecte correctamente las herramientas instaladas.

### Configuración manual del SDK

Si Flutter no detecta la ruta del SDK, ejecutar:

```bash
flutter config --android-sdk "C:\Users\Kyara\sdk"
```

Posteriormente verificar nuevamente con:

```bash
flutter doctor
```

### Licencias de Android

Para aceptar las licencias necesarias ejecutar:

```bash
flutter doctor --android-licenses
```

Seleccionar siempre:

```text
YES
```

hasta completar todas las licencias.

## Ejecución del Proyecto

```bash
flutter pub get
flutter run
```

