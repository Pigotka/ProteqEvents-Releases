# ProteqEvents releases

Installers for the **ProteqEvents** plugin for Milestone XProtect.

## Install or update

1. Download `ProteqEvents-<version>.msi` from the [latest release](../../releases/latest).
2. Run it as administrator on the Event Server machine and on every Management Client machine. Close Management Client first.

The installer stops XProtect Event Server, installs the plugin, opens TCP 18080 in Windows Firewall and starts Event Server again. Installing a newer version upgrades the existing one in place.

Silent install:

```
msiexec /i ProteqEvents-<version>.msi /qn
```

Each release also has `latest.json` with the version, download URL and SHA-256 checksum of the MSI. The newest one is always at:

```
https://github.com/Pigotka/ProteqEvents-Releases/releases/latest/download/latest.json
```
