# Sieged Empires — Client Pack

Remote pack payload for the Sieged Empires launcher. This repo contains **only** assets we may redistribute:

- **Custom mods** (`mods/`) — Sieged Empires–authored Fabric jars
- **Custom resource pack** (`resourcepacks/WeaponsModAddon-FA-Compat.zip`)
- **Pack config** (`config/`) — tuned settings for the modpack
- **Default options** (`options.txt`) — resource pack order, keybinds, audio
- **Shader profiles** (`shaderpacks/*.txt`) — BSL/Iris preset values (not shader zips)
- **`manifest.json`** — full pack index; third-party mods/resource/shader **zips are not stored here**

Third-party content listed under `manifest.json` → `files[]` is fetched at install time from **official Modrinth / CurseForge CDN URLs** only. Do not commit ARR third-party `.jar` or `.zip` binaries to this repo.

## Layout

| Path | Contents |
|------|----------|
| `manifest.json` | Pack manifest (CDN downloads + override hashes) |
| `mods/` | SE custom jars |
| `resourcepacks/` | SE-owned resource packs |
| `shaderpacks/` | Iris/BSL profile `.txt` files (shader zips download via CDN) |
| `config/` | Mod and performance configs |
| `options.txt` | Default Minecraft options |

## License

Custom Sieged Empires mods and the WeaponsMod FA compat pack are owned by the Sieged Empires project. Third-party mods remain subject to their respective licenses and are distributed only via their official CDNs as referenced in `manifest.json`.
