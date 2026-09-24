# WordUp

Aplicación móvil de aprendizaje de vocabulario desarrollada en Flutter.

## Requisitos

- Flutter 3.38.3 (channel stable)
- Dart 3.10.1
- Android SDK 21 o superior
- Android Studio / VS Code

## Emulador recomendado

Para correr la app en un emulador de Android Studio se recomienda:

- **Dispositivo:** Medium Phone
- **API Level:** 36.1 (Android 16)
- **ABI:** x86_64

### Pasos para crear el emulador

1. Abre Android Studio
2. Ve a **Device Manager → Add a new device**
3. Selecciona **Medium Phone**
4. Selecciona **API 35**
5. Finaliza la configuración y corre el emulador
6. Ejecuta `flutter run` en la terminal

## Instalación

### Opción 1 — Desde el APK

1. Descarga el archivo `app-release.apk`
2. En tu dispositivo Android ve a **Ajustes → Seguridad → Fuentes desconocidas** y actívalo
3. Abre el archivo APK e instala

### Opción 2 — Desde el código fuente

1. Clona el repositorio:
```bash
git clone <url-del-repo>
cd wordup
```

2. Instala las dependencias:
```bash
flutter pub get
```

3. Corre la app:
```bash
flutter run
```

4. O genera el APK:
```bash
flutter build apk --release
```
El APK queda en `build/app/outputs/flutter-apk/app-release.apk`

## Dependencias principales

- `google_fonts` — tipografía Plus Jakarta Sans
- `flutter/material` — componentes Material Design 3

## Pantallas

- **Home** — resumen del progreso
- **Actividades** — Flashcard, Significado, Pronunciación
- **Alarmas** — gestión de horarios de estudio
- **Configuración** — ajustes del perfil