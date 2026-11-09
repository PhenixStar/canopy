# Canopy

Canopy is a camera-wall client for Synology Surveillance Station. This repository holds installable
packages only. The source code is not published here.

## Install on Ubuntu

Packages are built for Ubuntu 24.04 on x86-64.

1. Open [Releases](../../releases) and download the newest `canopy-linux-x86_64.tar.gz`.
2. Unpack it and run the installer. It adds the system libraries the app needs, so it may ask for
   your password.

   ```sh
   tar -xzf canopy-linux-x86_64.tar.gz
   cd ss-client-linux-x86_64
   ./install.sh
   ```

3. Open **Canopy** from your applications menu.
4. Enter your recorder's address and sign in with your own Synology account.

To remove it, run `./install.sh --uninstall` from the same folder.

## Other systems

Windows, macOS and Android packages will be added to Releases when they are ready.

## Licence

Copyright © 2026. All rights reserved. No licence is granted to copy, modify or redistribute this
software.
