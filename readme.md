# adventure-platform

![GitHub Workflow Status (branch)](https://img.shields.io/github/actions/workflow/status/PaperMC/adventure-platform/ci.yaml?branch=main) [![MIT License](https://img.shields.io/badge/license-MIT-blue)](license.txt) [![Maven Central](https://img.shields.io/maven-central/v/net.kyori/adventure-platform-api?label=stable)](https://search.maven.org/search?q=g:net.kyori%20AND%20a:adventure*) ![Maven snapshots](https://img.shields.io/maven-metadata/v?metadataUrl=https%3A%2F%2Fcentral.sonatype.com%2Frepository%2Fmaven-snapshots%2Fnet%2Fkyori%2Fadventure-platform-api%2Fmaven-metadata.xml&strategy=highestVersion&label=dev)

> [!CAUTION]
> Adventure platform implementations for Bungeecord, Spigot, and Sponge API 7, as well as the serializers in this repository, are no longer maintained.
> Support for using these libraries is no longer provided by the Adventure team.
> 
> We recommend that users of these libraries update to modern platforms that natively support Adventure (e.g., Velocity, Paper, Sponge API 8+).
> For users who develop for modded platforms, we recommend that you use [adventure-platform-mod](https://github.com/PaperMC/adventure-platform-mod) for near-native support for Fabric and NeoForge.

Adventure platform implementations, for servers and proxies including [Paper](https://papermc.io)/Spigot/Bukkit, [BungeeCord](https://www.spigotmc.org/go/bungeecord), and [SpongeAPI 7](https://spongepowered.org). Other platforms may be supported through native integration, or other libraries.

See the [documentation](https://docs.papermc.io/adventure/platform/) for usage and dependency information for this project and the main `adventure` library.

### Contributing

We appreciate contributions of any type. For any new features or typo-fix/style changes, please open an issue or come talk to us in our [Discord] first so we make sure you're going in the right direction for the project.

All the adventure projects are built with Gradle, require at least JDK 8, and use a common checkstyle configuration. Please make sure all tests pass, license headers are updated, and checkstyle passes to help us review your contribution.

`adventure-platform` is released under the terms of the [MIT License](license.txt).

[Discord]: https://discord.gg/papermc
