# 🎴 Jujutsu Kaisen SMP — Modpack & Join Guide

**Minecraft `1.20.1` · Forge `47.4.0` · 40 mods**

Jujutsu Craft + JJSK + Cursed Enhancement, plus combat (Better Combat, ParCool), exploration (YUNG's structures, dungeons, villages, Waystones), quality-of-life, and performance mods.

---

## ⬇️ Download the modpack

Grab **`JJK-Modpack-1.20.1.zip`** from the **[Releases page](../../releases/latest)**.

> It's ~100 MB. Download it but **don't unzip it yet** — Step 3 tells you when.

---

## ✅ Before you start

| # | You need |
|---|----------|
| 1 | **SKlauncher** installed (the launcher you already use) |
| 2 | The **modpack zip** from the Releases page above |
| 3 | The **server address** — ask the host, keep it handy for the last step |

---

## 🛠️ Install (SKlauncher)

**1. Create a Forge 1.20.1 install**
SKlauncher → **Installations Manager** → **New Installation**:

| Setting | Value |
|---|---|
| Name | `JJK 1.20.1` |
| Version type | **Forge** |
| Minecraft | `1.20.1` |
| Forge loader | `47.4.0` |

Set the **Game Directory** to a **new empty folder** (e.g. `C:\JJK`) so these mods don't mix with your normal Minecraft. Click **Save**.

**2. Launch once to finish Forge**
Select the `JJK 1.20.1` install → **Play**. Let it reach the title screen (this installs Forge), then **close the game**. No mods yet — that's expected.

**3. Add the mods**
Unzip `JJK-Modpack-1.20.1.zip`. Inside is a `mods` folder with 40 `.jar` files. Move that whole `mods` folder into your game directory, so you end up with jars at `C:\JJK\mods\`.

> ⚠️ **Use all 40 — exactly.** Don't add or remove any. Everyone must run the identical set or you'll be kicked with a *mod mismatch* error.

**4. (Optional) music pack**
If the host shares a **JJK-Music** resource pack, drop it in the `resourcepacks` folder and enable it under **Options → Resource Packs**.

**5. Launch & connect**
Start SKlauncher → pick `JJK 1.20.1` → **Play**. First load is slow (40 mods). At the menu: **Multiplayer → Direct Connection** → enter the host's address → **Join Server**.

---

## 🧯 Troubleshooting

| Problem | Fix |
|---|---|
| *"needs language provider"* / *"failed to load"* | Your `mods` folder is missing files. Delete its contents and re-copy all 40 jars. |
| Kicked for **mod mismatch** | You have a different set than the server. Use exactly the 40 — same versions. |
| *"requires Java 17"* | Install **Temurin (Adoptium) Java 17** and select it in the install settings. |
| Can't connect | Use the exact address the host gave you (not `localhost`). Make sure the server is on. |
| Low FPS | Give the install **4–6 GB RAM** in its settings. Performance mods are already included. |

---

## 📦 What's inside

Full list: **[modlist.md](modlist.md)**. A prettier version of this guide: **[JJK-Install-Guide.html](JJK-Install-Guide.html)** (download & open in any browser).

*Domain expansion — see you in there.*
