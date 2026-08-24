- Minecraft Android Native Libraries
  (`mc-android-libs`)

A centralized collection of compiled Android `aarch64` native binaries (`.so`) for Java mods built by me and true to the original source.

## 📦 Supported Libraries & Mods

| Mod / Library | Status | Target Path in JAR | Target Release |
| :--- | :--- | :--- | :--- |
| **Simple Voice Chat** `lame4j` `opus4j` `rnnoise4j` `speex4j` | ✅ Available | `.../natives/linux-aarch64` | [Release](../../releases/tag/SVC) |
| **Plasmo Voice** `opus-jni-rust` `rnnoise-jni-rust` | ✅ Available | `.../natives/linux-aarch64` | [Release](../../releases/tag/PZ) |
| **Distant Horizons** `zstd-jni-dh` | 🚧 Planned | `linux/aarch64/` | - |

---
>If you maintain a launcher, these pre compiled `.so` libs can be added to your `jniLibs/arm64-v8a` folder and used to inject the `.so` by replacing the one in the jar.
- Some mods just look at the jniLibs like distant horizons so sometimes you don't need a script.
