# Visionfuscastor | Advanced Fabric Mod Obfuscation For 1.21.x Mods
## Features:

Class renaming

Optional member renaming, but it is off by default now because it can break Fabric/Minecraft mods

String encryption for normal method string literals

Encryption of static final String field constants by moving them into <clinit>

Rewriting of common invokedynamic string concat patterns so concat literals can be hidden too

Number obfuscation for some integer constants

Debug metadata stripping

Conservative control-flow obfuscation

Optional control-flow flattening

Mapping file output so you can trace obfuscated builds

Fabric entrypoint and mixin discovery to avoid renaming classes referenced by metadata

Manifest Main-Class remapping

Resource and META-INF copying

Runtime decryptor injection

Output JAR generation from input JARs
