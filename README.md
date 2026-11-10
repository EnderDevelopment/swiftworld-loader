# SwiftWorld Loader Minecraft Bedrock Behavior Pack

SwiftWorld Loader is a Minecraft Bedrock behavior pack with a manual function for removing dropped item entities from loaded areas. It does not change world or dimension loading, suppress loading screens, or guarantee faster performance.

## Install

1. Place the behavior pack folder in the world’s `behavior_packs` directory, or package it as an `.mcpack` and open it with Minecraft.
2. Open the world settings and enable **World Performance Helpers** under Behavior Packs.
3. Back up the world before using the cleanup function, because it removes dropped items.

## Use

1. Load the world with the behavior pack enabled.
2. Run `/function performance/cleanup_drops` to remove dropped item entities in loaded areas.

The function is manual; no recurring tick function or script module is enabled. Compatibility with Minecraft version 26.50 is not confirmed. The pack declares a minimum engine version of 1.21.0.

---

More Minecraft mod projects by EnderDevelopment: https://github.com/EnderDevelopment

Project page: https://dash.enderdevelopment.com/community/ee82267b-2f1c-434e-911c-58bf127e6096?utm_source=github&utm_medium=readme&utm_campaign=auto_publish&utm_content=ee82267b-2f1c-434e-911c-58bf127e6096
