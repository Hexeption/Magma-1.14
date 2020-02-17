![Magma](https://img.hexeption.co.uk/magma.png)

# Magma 1.14.4

![](https://img.shields.io/badge/Minecraft%20Forge-1.14.4%20--%2028.1.93-orange.svg?style=for-the-badge) ![](https://img.shields.io/badge/Status-Unstable-red?style=for-the-badge) [![](https://img.shields.io/jenkins/build/https/ci.hexeption.co.uk/job/Magma-Main/job/1.14?label=CI&style=for-the-badge)](https://ci.hexeption.co.uk)

## About

Magma is the next generation of hybrid minecraft server softwares.

Magma is based on Forge and Paper, meaning it can run both Craftbukkit/Spigot/Paper plugins and Forge mods.

We hope to eliminate all issues with craftbukkit forge servers. In the end, we envision a seamless, low lag Magma experience with support for newer 1.12+ versions of Minecraft.

### 1.14.4 Changes

Magma will be swapping from craftbukkit to a custom made bukkit/spigot/paper implementation to make it easier to update and make compatibility with mods and plugins better overall.

This update will take some time as we are rewriting a lot of the underlying code.

## Deployment

### Installation

1. Download the recommended builds from the [**Releases** section](https://github.com/magmafoundation/Magma-1.14/releases)
   1. Download Beta builds from the [**CI**](https://ci.hexeption.co.uk/job/Magma-1.14/)
2. Make a new directory for the server
3. Move the jar that you previously downloaded to the new directory
4. Run the jar

### Building the sources

- Clone the Project
  - You can use Git GUI (like GitHub Desktop/GitKraken) or clone using the terminal using:
    - `git clone https://github.com/MagmaFoundation/Magma-1.14`
  - Next, clone the submodules using:
    - `git submodule update --init --recursive`
- Building
  - First you want to run the build command
    - `./gradlew reobfShadowJar`
  - Now go and get a drink this may take some time
  - Navigate to `build/distributions` directory of the compiled source code
  - Copy the Jar to a new server directory
  - Run the jar

## Contribute to Magma

If you wish to inspect Magma, submit PRs, or otherwise work with Magma itself, you're in the right place!.

Please read the [CONTRIBUTING.md](https://github.com/magmafoundation/Magma-1.14/blob/master/CONTRIBUTING.md) to see how to contribute, setup, and run.

## Chat

You are welcome to visit Magma Discord server [here](https://discord.gg/6rkqngA).

## Partners

<a href="https://aternos.org/en/"><img src="https://design.aternos.org/dl/logotype-horizontal-blue.png" width="200"></a>
<a href="https://songoda.com/"><img src="https://cdn2.songoda.com/branding/logo.svg" width="200"></a>
