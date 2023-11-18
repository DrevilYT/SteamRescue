@echo off
taskkill /f /im steam.exe
timeout /2
cd C:\Program Files (x86)\Steam
start steam.exe
