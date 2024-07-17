# Quick intro

## What is CleanroomMC loader?

CleanroomMC loader is an alternative to Forge loader for 1.12.2 that runs on Java 21. They are open-source modding APIs. Basically they don't do anything on their own but they are the basis for all the mods we're going to download here. CleanroomMC is based on Forge and therefore is compatible with (almost) every mod based on Forge.

## Why use CleanroomMC loader?

- Better performance thanks to Java 21 due to :
  - Java 21 simply being more recent and better coded
  - Java 21 having better garbage collection options. This is especially useful for servers with ZGC that scales well the more RAM you give it (impossible on Java 8). Other garbage collectors such as ShenGC are better suited for client loads.
- Open source (Forge is too)
- Active developpment, which may mean more features, more performance, less bugs. Forge has stopped developpment.

## Problems with CleanroomMC loader

- Most mods aren't directly coded with CleanroomMC in mind, this may lead to rare incompatibilities/bugs. Not the case for Nomi-CEu and this specific fork of it either.

# Installation
