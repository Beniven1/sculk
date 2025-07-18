# S.C.U.L.K.
### The Source Code Utility & Launcher Kit

---

Tired of waiting for tools to update? Want to get your hands on Minecraft's source code *right now*?

SCULK is a lightweight, no-fuss development kit that gets you a fully decompiled and remapped Minecraft source environment in minutes. It's built to be fast, flexible, and easy to update. No complex APIs, just the raw source.

*   **Instant Setup:** Clone and run one command. That's it.
*   **Choose Your Mappings:** Use Parchment, Yarn, or plain Mojmaps.
*   **Direct Source Access:** View, edit, and experiment with the game's code directly in your IDE.
*   **Always Fast:** Designed to support new Minecraft versions with minimal delay.

## Quickstart

**Prerequisites:** Git, Java 21+ & IntelliJ IDEA.

1.  **Clone it:**
    ```bash
    git clone https://github.com/Beniven1/sculk.git
    cd sculk
    ```

2.  **Set it up:**
    ```bash
    ./gradlew setup
    ```
     **this may take a while*


3.  **Run it:**
    Open the project in IntelliJ and use the `runClient` configuration.

## Change Mappings

Run the setup task with a property. SCULK remembers your choice.

```bash
# For Yarn
./gradlew setup -PmappingType=yarn
# For Parchment
./gradlew setup -PmappingType=parchment
# For plain Mojang mappings
./gradlew setup -PmappingType=mojmap
```

## Who is this for?

Researchers, client developers, and anyone who wants to mess with Minecraft's core. If you want to build a standard mod, you should look at [Fabric](https://fabricmc.net/) or [NeoForge](https://neoforged.net/).

## Contributing

Find a bug or have an idea? Open an issue or a PR. All contributions are welcome.

## License
**MIT** - Go Build Something Unique.
