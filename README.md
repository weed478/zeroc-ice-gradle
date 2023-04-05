# Zeroc Ice

## Zmiany dla MacOS

Zmienić dla swojego systemu.

1. Ścieżka do Ice

```gradle
// /build.gradle
subprojects {
  slice.iceHome '/opt/homebrew'
}
```

2. Adres `127.0.0.2` -> `127.0.0.1` w plikach Java


## Uruchamianie

Z jednego terminala:

```bash
./gradlew :server:run
```

Z drugiego:

```bash
./gradlew :client:run --quiet --console plain
```
