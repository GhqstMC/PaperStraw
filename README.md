<div align="center">

## PaperStraw
### You're welcome, turtles

PaperStraw is a slightly memey fork of [Purpur](https://github.com/pl3xgaming/Purpur) with the goal of adding random patches

</div>

## Contact
[![Join us on Discord](https://img.shields.io/discord/626221022013816842.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://discord.com/invite/734UWzJyV8)

## Downloads
i can't afford jenkins

## License
[![MIT License](https://img.shields.io/github/license/GhqstMC/PaperStraw?&logo=github)](License)

All patches are licensed under the MIT license, unless otherwise noted in the patch headers.

See [PaperMC/Paper](https://github.com/PaperMC/Paper), [Spottedleaf/Tuinity](https://github.com/Spottedleaf/Tuinity), [TECHNOVE/Airplane](https://github.com/TECHNOVE/Airplane), and [jpenilla/Toothpick](https://github.com/jpenilla/Toothpick) for the license of material used by this project.


## API

### Javadoc coming soon

### Dependency Information (nonexistent)

Yes, this will also includes all API provided by Paper, Spigot, and Bukkit.

## Building and setting up

#### Initial setup
Run the following commands in the root directory:

```
./gradlew applyPatches
```

#### Creating a patch
Patches are effectively just commits in either `PaperStraw-API` or `PaperStraw-Server`. 
To create one, just add a commit to either repo and run `./gradlew rebuildPatches`, and a 
patch will be placed in the patches folder. Modifying commits will also modify its 
corresponding patch file.

See [CONTRIBUTING.md](CONTRIBUTING.md) for more detailed information.


#### Compiling

Use the command `./gradlew build` to build the api and server. Compiled jars
will be placed under `PaperStraw-API/build/libs` and `PaperStraw-Server/build/libs`.

To get a purpurclip jar, run `./gradlew paperclip`.
To install the `paperstraw-api` and `paperstraw` dependencies to your local maven repo, run `./gradlew publishToMavenLocal`
