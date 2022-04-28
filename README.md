# Spigot Minecraft server plugin for kotlin runtime

- kotlin version: 1.6.10
- jvm target: java 16
- available minecraft versions: 1.12, 1.16, 1.17
- minecraft 1.18 requires manually changing jvm to java 17 (currently no cli build command for jvm target)

## Minecraft version

Build for Minecraft 1.12.2
```
./gradlew build -P 1.12
```

Build for Minecraft 1.16.5
```
./gradlew build -P 1.16
```

Build for Minecraft 1.17.1
```
./gradlew build -P 1.17
```

## Adding `kotlin-reflect`
Use `-P reflect` to also shadow in `kotlin-reflect` library.
This is a big library and will roughly double the kotlin runtime size.

Example for Minecraft 1.16.5:
```
./gradlew build -P 1.16 -P reflect
```