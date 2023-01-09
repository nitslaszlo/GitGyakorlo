# Verziókezelés alapjai
## 1. git letöltése
- [git for windows](https://gitforwindows.org/)
- [git scm](https://git-scm.com/)
## 2. Konfigurációs parancsok
- git config --global user.name nitslaszlo
- git config --global user.email nitslaszlo@gmail.com
- git config --global credential.helper wincred
## 3. Repository létrehozása
- git init
## 4. Állomány hozzáadása a stage-hez (staging area)
> A stagen lévő állományokról tudunk állapotfelvételt (commit-ot)készíteni
> Üres mappa nem kerül a stage-re
- git add állomány_neve
- git add . (összes állomány és mappa hozzáadása)
## 5. Állapotfelvétel (commit) készítése
- git commit -m "commit message"
## 6. Git állapot és log lekérdezése
- git status
- git log
## 7. Lokális változások szinkronizálása a távoli repóba
- git push
## 8. Távoli repó másolása (klónozása) a lokális repóba
- git clone "távoli repó URL címe"