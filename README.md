# Veyora releases

Pre-release builds of the Veyora workspace server, the helper that Veyora installs on WSL distros and SSH hosts so terminals and agents can run there.

- `workspace-server-v<version>` releases hold the Linux x64 and arm64 archives, their `.sha256` files and `install.sh`.
- The `channels` release holds small pointer files (`<channel>-protocol-<major>.json`) that tell Veyora which version to install.

Veyora downloads and checksum-verifies these files itself; you don't need to install anything from here by hand.
