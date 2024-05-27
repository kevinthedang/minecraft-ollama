## Setup Development Environment
* Get and IDE like IntelliJ IDEA or VS Code for developing with Java. I would recommend IntelliJ as that is what the Code owners will use.
* Get a Java Development Kit (JDK) of [17+](https://adoptium.net/temurin/releases/?version=17)
* Get the Latest (LTS) of [Forge](https://files.minecraftforge.net/net/minecraftforge/forge/) through the `Mdk` link. Click to skip the ad and it should download.
* Clone the repository and open with IntelliJ (or others somehow)
  * Allow for Grade to set up environment with Forge.
  * Most of the setup will already be done. We are utilizing [parchment](https://parchmentmc.org/docs/getting-started) instead of `official`.
    * Mapping versions can be found on the site. Ensure the mapping versions matches in `/grade-properties`.
* For first time setup (or maybe for first clone), run `./gradlew genIntellijRuns` in a terminal in IntelliJ for proper setup.
* In the `grade` tab, you can now open to `forgegradle runs/runClient` and run that to open Minecraft with the Mod.