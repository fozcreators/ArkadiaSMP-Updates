# ArkadiaSMP Updates
Download the Arkadia SMP Menu add-on for Minecraft 26.3 from Releases, channel `menu-26.3`.
## One-time install
Install the Fabric menu JAR in your Minecraft instance mods folder, replacing the previous menu JAR. Keep ArkadiaCore and Fabric dependencies installed separately. Do not install two menu versions together. The Paper JAR belongs on the server only.
## Automatic updates
From 1.0.4-prebuild.7, compatible publisher-signed menu updates download after joining a server. Close Minecraft and wait a few seconds to apply; next launch loads the update. Only the menu mod updates, not Minecraft, Fabric, Core, other mods or the server plugin. Opt out in config/arkadia_smp_menu-updates.properties. Older installed clients need this first updater-enabled version once.
## Scope
Prebuild.7 adds the signed updater. Expanded objective, group/location and hunting browser previews are not implemented in this build. Live multiplayer and visual acceptance testing remain necessary.
## Publisher
Upload a versioned Fabric JAR, update.properties and update.properties.sig to release tag menu-26.3. Never upload private signing keys.
