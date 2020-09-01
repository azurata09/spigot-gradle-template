# Spigot Gradle Template
This is template for developing and building spigot plugin in minimize.

# How to use?
1. Cloning this repository
1. Change `gradle.properties` for your environment
1. Run `./gradlew setup` or `.\gradlew.bat setup`
1. Coding plugin
1. Run `./gradlew build --info` or `.\gradlew.bat build --info` for building

# Properties
## pluginName
Set your plugin name.

**Examples**
- SamplePlugin
- JinroMC
- Essentials

This name be Main class if you run `./gradlew setup` or `.\gradlew.bat setup`

## pluginPackage
Set your plugin package

**Examples**
- com.example.sample
- me.azurata.jinromc
- com.earth2me.essentials

## pluginVersion
Set your plugin version

Generally, formal release versions are over 1.0

**Examples**
- 0.1-alpha
- 0.5.2-beta
- stable-2.13.1

## minecraftVersion
Set your plugin's minecraft version

But, you can select [here](https://hub.spigotmc.org/nexus/content/repositories/snapshots/org/spigotmc/spigot-api/) only.

**Examples**
- 1.8-R0.1-SNAPSHOT
- 1.12.2-R0.1-SNAPSHOT
- 1.7.2-R0.3-SNAPSHOT (This is bukkit version)

# License
Apply MIT License
