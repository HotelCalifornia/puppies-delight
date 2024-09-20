# Puppies' Delight

a 1.20.1 (forge) modpack focused on magic, exploration, and, most importantly, food.

## Mods

- Tech & Tools:
  - Create
  - Project Red
  - Tetra
- Magic:
  - Apotheosis
  - Ars Nouveau
  - Blood Magic
  - Botania
  - Iron's Spells n' Spellbooks
- Exploration:
  - The Aether
  - Alex's Caves & Alex's Mobs
  - Deeper and Darker
  - Goblin Traders
  - The Graveyard
  - Kobolds!
  - L\_ender's Cataclysm
  - Marium's Soulslike Weaponry
  - Terralith
  - A lot of Yung's mods
- Food:
  - Farmer's Delight and a huge number of addons and integrations
  - Mystical Agriculture
  - Nether's Exoticism
- Gameplay:
  - Default Skill Trees
  - Majrusz's Progressive Difficulty
  - Origins & Origins++

and more!

## Installation

### Release
Download the pack zip file from the releases page and import it into the launcher of your choice.

### Manual

To install the pack for a client, I recommend using a launcher like [prism](https://prismlauncher.org) or [multiMC](https://multimc.org). The following instructions will work for either of them.

1. Create a new instance. Pick 1.20.1 for the version, and select Forge as the mod loader.
2. Edit the instance you just made. While you're here, you should probably set new memory limits.
3. Go to the Custom commands pane in the settings window, and check the custom commands box. In the **Pre-launch command** field, enter `"$INST_JAVA" -jar packwiz-installer-bootstrap.jar https://hotelcalifornia.github.io/puppies-delight/pack.toml`
4. Download [packwiz-installer-bootstrap](https://github.com/packwiz/packwiz-installer-bootstrap/releases) and place the jar file in the .minecraft or minecraft folder inside your instance folder (right click on the instance and click Folder).
5. On first launch, you may be prompted to manually download a few mods that are excluded from the CurseForge API.

### Server

I don't really know all the ins and outs of Minecraft server setup these days, because I have made my life vastly simpler by using [itzg's docker-minecraft-server](https://github.com/itzg/docker-minecraft-server), which also has built in support for packwiz. Simply point the `PACKWIZ_URL` environment variable toward `https://hotelcalifornia.github.io/puppies-delight/pack.toml` (and make sure to set `TYPE=FORGE` and `VERSION=1.20.1`).

