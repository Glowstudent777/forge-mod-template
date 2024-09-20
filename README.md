# Forge Mod Template

This will be using [Forge Mod Development Kit (MDK)](https://files.minecraftforge.net/net/minecraftforge/forge/index_1.21.html) for Minecraft v1.21.0

## Using This Code:

### Prerequisites

- [Minecraft Java Edition](https://www.minecraft.net/en-us/store/minecraft-java-bedrock-edition-pc)
- [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)
- [Gradle](https://gradle.org/)

## Building

Windows and Linux:
```console
gradlew build
```

MacOs:
```console
./gradlew build
```

The output `.jar` file will be located in `build/libs` with the name `[archivesBaseName]-[version].jar`

## Installation

### Windows

1. Go to `%appdata%/.minecraft` or wherever you installed Minecraft to.
2. Put your `.jar` mod file into the `mods` folder of your Forge Minecraft version installation.

## Contributing

Before creating an issue, please ensure that it hasn't already been reported/suggested.

## License

This repository is licensed under the [Apache 2.0 License](LICENSE).
