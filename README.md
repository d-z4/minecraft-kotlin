# Spigot Minecraft server plugin for kotlin runtime

- kotlin version: 2.3.0-Beta2
- jvm target: java 21
- available minecraft versions: 1.21.10

Build for Minecraft 1.21.10
```
./gradlew build
```

## Adding `kotlin-reflect`
Use `-P reflect` to also shadow in `kotlin-reflect` library.
This is a big library and will roughly double the kotlin runtime size.
