# ThinkPilot Releases

Public distribution repository for ThinkPilot Windows x64 installers. Development takes place separately.

No stable release has been published yet. Test builds are not production updates.

After publication, each stable release should contain an installer named `ThinkPilot-Setup-<version>.exe` and `manifest.json` (signed release metadata). ThinkPilot 0.5.1 or later can retrieve the current manifest from:

https://github.com/LukeZilla-777/ThinkPilot-Releases/releases/latest/download/manifest.json

The publisher public key must be verified through an independent trusted channel. Do not trust a replacement key merely because it appears in this repository. The signature verifies update metadata and installer integrity; the installer itself is not Authenticode signed. Review release notes, exit ThinkPilot before upgrading, and approve the installer manually. No unattended installations.
