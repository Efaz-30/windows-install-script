@echo off
echo Installing your software with Winget...

:: Update Winget sources
winget source update

:: Install Google Chrome
winget install --id=Google.Chrome -e --accept-package-agreements --accept-source-agreements

:: Install Visual Studio Code
winget install --id=Microsoft.VisualStudioCode -e --accept-package-agreements --accept-source-agreements

:: Install PGAdmin
winget install --id=PostgreSQL.pgAdmin -e --accept-package-agreements --accept-source-agreements

:: Install PostgreSQL (includes psql shell)
winget install --id=PostgreSQL.PostgreSQL -e --accept-package-agreements --accept-source-agreements

:: Install WhatsApp
winget install --id=9NKSQGP7F2NH -e --accept-package-agreements --accept-source-agreements

:: Install Telegram
winget install --id=Telegram.TelegramDesktop -e --accept-package-agreements --accept-source-agreements

:: Install Tableau Public (free version)
winget install --id=Tableau.TableauPublic -e --accept-package-agreements --accept-source-agreements

:: Install Adobe Acrobat Reader
winget install --id=Adobe.Acrobat.Reader.64-bit -e --accept-package-agreements --accept-source-agreements

:: Install VLC Media Player
winget install --id=VideoLAN.VLC -e --accept-package-agreements --accept-source-agreements

:: Install Avro Keyboard (from OmicronLab)
winget install --id=OmicronLab.AvroKeyboard -e --accept-package-agreements --accept-source-agreements

echo.
echo ✅ All installations attempted. Check above for any errors.
pause
