# Simple hack to enable Docker on Windows 10 Home

- Step 1: execute as administrator the "enable-hyperv.bat" file. Reboot Windows as requested.
- Step 2: execute the "go-to-pro.reg" to "change" the Windows version from "Home" to "Professional". This will bypass the docker installer validation.
- Step 3: download and install docker for windows: https://download.docker.com/win/stable/Docker%20Desktop%20Installer.exe.
- Step 4: after docker installed, execute the "back-to-home.reg" file to restore your Windows version to "Home".
- Step 5: reboot your Windows.

That's it. Enjoy.
