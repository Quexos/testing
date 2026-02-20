# Mace Skins — Fabric Mod

Press **M** in-game to open the skin picker and choose from:
- 🌸 Petals
- ⚡ Lightning  
- 🤍 White
- ⚔  Original (Gold, vanilla)

---

## How to compile

### Requirements
- **Java 21** (already on your system if you run Minecraft 1.21)
- **Internet connection** (Gradle downloads Fabric on first build)

### Steps

1. **Get the Gradle wrapper** (one-time setup):

   The easiest way is to copy `gradlew`, `gradlew.bat`, and `gradle/wrapper/gradle-wrapper.jar`
   from the official Fabric example mod:
   ```
   https://github.com/FabricMC/fabric-example-mod
   ```
   Just copy those 3 files into this folder.

   **OR** if you have Gradle installed locally:
   ```bash
   gradle wrapper --gradle-version 8.11.1
   ```

2. **Build the mod:**
   ```bash
   # macOS / Linux
   ./gradlew build

   # Windows
   gradlew.bat build
   ```

3. **Find your jar:**
   ```
   build/libs/mace-skins-1.0.0.jar
   ```

4. **Install:**
   - Copy `mace-skins-1.0.0.jar` into your `.minecraft/mods/` folder
   - Also make sure **Fabric API** is in your mods folder
   - Launch Minecraft 1.21.4 with Fabric Loader

---

## In-game usage

1. Hold your mace (or have one in your inventory)
2. Press **M** to open the Mace Skins menu
3. Click a skin — it applies in ~1 second (resource reload)
4. The checkmark (✓) shows your current active skin

You can rebind the key in **Options → Controls → Mace Skins**.
