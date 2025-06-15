# Spigot Minecraft server plugin for kotlin runtime

- kotlin version: 2.2.0-RC2
- jvm target: java 21
- available minecraft versions: 1.21.5

Build for Minecraft 1.21.5
```
./gradlew build
```

## Adding `kotlin-reflect`
Use `-P reflect` to also shadow in `kotlin-reflect` library.
This is a big library and will roughly double the kotlin runtime size.
