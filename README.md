# 🎴 Jujutsu Kaisen SMP — Modpack & Join Guide

**Minecraft `1.20.1` · Forge `47.4.0` · 41 mods**

Jujutsu Craft + JJSK + Cursed Enhancement, plus combat (Better Combat, ParCool, over-the-shoulder camera), exploration (YUNG's structures, dungeons, villages, Waystones), quality-of-life, and performance mods. Ships with **pre-configured keybinds**, a **custom JujutsuCraft texture pack**, and **optional shaders**.

---

## ⬇️ Download the modpack

Grab **`JJK-Modpack-1.20.1.zip`** from the **[Releases page](../../releases/latest)**.

> ~100 MB. Download it but **don't unzip it yet** — Step 3 tells you when.

---

## ✅ Before you start

| # | You need |
|---|----------|
| 1 | **SKlauncher** installed |
| 2 | The **modpack zip** from the Releases page above |
| 3 | The **server address** (below) — you're all set, it's already in this guide |

### 🌐 Server address
```
whacking-prevent.gl.joinmc.link
```
Just paste that in — no port needed.

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

Set the **Game Directory** to a **new empty folder** (e.g. `C:\JJK`) so this doesn't touch your normal Minecraft. Click **Save**.

**2. Launch once to finish Forge**
Select `JJK 1.20.1` → **Play**. Let it reach the title screen (this installs Forge), then **close the game**. No mods yet — that's expected.

**3. Copy everything from the zip in**
Unzip `JJK-Modpack-1.20.1.zip` and copy **all of its contents** into your game directory (`C:\JJK`), overwriting if asked. You get:

| Folder / file | What it does |
|---|---|
| `mods/` | the 41 mods |
| `options.txt` | **pre-configured keybinds** (no conflicts — see below) |
| `resourcepacks/` | the custom JujutsuCraft textures |
| `shaderpacks/` | Complementary shaders (optional) |

> ⚠️ **Use all 41 mods — exactly.** Don't add or remove any, or you'll be kicked with a *mod mismatch* error.

**4. Turn on the extras (in-game)**
- **Resource pack:** Options → Resource Packs → enable **Customized JujutsuCraft**
- **Shaders (optional, needs a decent GPU):** Options → Video Settings → Shader Packs → enable **Complementary Reimagined**

**5. Launch & connect**
Start SKlauncher → `JJK 1.20.1` → **Play**. First load is slow. Then **Multiplayer → Direct Connection** → enter `whacking-prevent.gl.joinmc.link` → **Join Server**.

---

## ⌨️ Keybinds (pre-configured)

The included `options.txt` already fixes the 40-mod keybind pile-up. Highlights:

| Key | Action |
|---|---|
| `WASD` / `Space` | move **and** JJK technique directions (intentional — that's how combos read) |
| `C` `R` `M` `Z` `X` `V` `G` `N` | JJK cursed techniques (switch / change / reverse / start / reset / main skill / simple domain / domain amp) |
| `K` | extension technique · `H` `I` `J` | addon techniques |
| `Left Alt` | ParCool **dodge** (other parkour moves = double-tap a direction) |
| `F6`–`F12` | shader toggle, backpack, waypoints (moved here to stay out of the way) |

Prefer your own layout? Just edit them in **Options → Controls** like normal.

---

## 🧯 Troubleshooting

| Problem | Fix |
|---|---|
| *"needs language provider"* / *"failed to load"* | Your `mods` folder is missing files. Delete its contents and re-copy all 41. |
| Kicked for **mod mismatch** | Use exactly the 41 from the zip — same versions, nothing added/removed. |
| *"requires Java 17"* | Install **Temurin (Adoptium) Java 17** and select it in the install settings. |
| Can't connect | Use the exact address the host gave you (not `localhost`). Make sure the server is on. |
| Low FPS with shaders | Shaders are optional — turn them off, or lower render distance to 8–10. Give the install 4–6 GB RAM. |

---

## 📦 What's inside

Full list: **[modlist.md](modlist.md)**. A prettier version of this guide: **[JJK-Install-Guide.html](JJK-Install-Guide.html)**.

*Domain expansion — see you in there.*
