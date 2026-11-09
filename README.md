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

## Other Linux machines

For Ubuntu 24.04 on ARM64, download `canopy-linux-arm64.tar.gz` and follow the same steps, using the
folder `ss-client-linux-arm64`.

## Android

Download `canopy-android-arm64.apk` on an ARM64 phone or tablet, open it, and allow the install when
Android asks. Then enter your recorder's address and sign in with your own Synology account.

## Windows

1. Open [Releases](../../releases) and download `canopy-windows-x86_64.zip` from the release marked
   for Windows.
2. Unpack the whole folder, then open `ss-client.exe` inside it. Keep the files together.
3. The app is not code-signed, so Windows may warn before opening it. Choose **More info**, then
   **Run anyway**.
4. Enter your recorder's address and sign in with your own Synology account.

This is an older build from 4 November 2026 and has not had the Linux package's recent updates.

## macOS

A macOS package will be added to Releases when it is ready.

## Licence

Copyright © 2026. All rights reserved. No licence is granted to copy, modify or redistribute this
software.
