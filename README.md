# Okyanus Advanced Template

This is an "advanced" mod template for Okyanus. It supports:

* Viewing / Modifying (via mixins) Minecraft Internals
* Launching the server automatically

## Setup

1. Edit build.gradle and mod.json to suit your needs.
    * The "mixins" object can be removed from mod.json if you do not need to use mixins.
    * Please replace all occurences of "modid" with your own mod ID - 
      sometimes, a different string may also suffice.
2. Run the following command:

```
./gradlew idea
```

There will be a generated "Minecraft Client" run, you might want to delete it,
as Okyanus is not supported under the client.
