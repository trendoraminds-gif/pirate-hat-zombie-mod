# Pirate Hat Zombies (Fabric)

A starter Fabric mod project for **Minecraft Java 1.21.1**. Zombies are equipped with a Pirate Hat when their equipment is initialized. The hat has a 10% equipment drop chance when the zombie dies.

## Build

- Install Java 21 (JDK).
- Install Gradle or add a Gradle wrapper from a trusted Gradle installation.
- From this folder run: `gradle build`
- The compiled mod jar will be in `build/libs/`.
- Put the resulting JAR in your Minecraft instance's `mods` folder along with Fabric Loader and Fabric API for Minecraft 1.21.4.

## Notes

- This is source code, not a precompiled JAR.
- The project targets Minecraft 1.21.4, which is within the requested 1.21+ range. It is not guaranteed compatible with every later Minecraft version; Minecraft/Fabric mappings and APIs change between versions.
- The included hat is a helmet item with a custom pixel-art icon and armor texture. The supplied `.bbmodel` is included separately as the editable Blockbench source model; this starter mod does not yet render that exact geometry on the zombie's head.
- To change drop chance, edit `0.10F` in `ZombieEntityMixin.java` (0.10 = 10%).
