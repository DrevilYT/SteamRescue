# SteamRescue
Fixes any UI bug with Steam by restarting, refreshing and reloading all Steam cache.

IF IT DOESN'T WORK, TRY RUNNING AS ADMIN.

# 1st Method
- Run the downloaded file (as admin) while Steam is running and having any issues.

# 2nd Method
- When Steam is running and having any issues, hit Windows key + R at the same time and in the box that appears, paste this: 
- "cmd.exe /c @echo off & taskkill /f /im steam.exe & cd C:\Program Files (x86)\Steam & color c & echo Drev's Steam Rescue Script Loaded & timeout /t 2 & start steam.exe & exit"
- Paste without the quotes or quoation marks (")
