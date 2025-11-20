# devops
DEVOPS 
1. lépés 
alkalmazások telepítése: VSCode, GitHub Desktop, Git Bash, Docker, 

2. lépés 
NodeJS csomag telepítése
VSCode-ban a trminál ablakban a projekt mappában állva fittasuk le a következő parancsot:
    npm init -y    - npm csomag inicializásáa 
    npm install express 
    npm install body-parser    -segít feldolgozni a http kéréseket JSON formátumban 

3. lépés    
szerver.js létrehozása - ami biztosítja a backend funkciót 

4. lépés 
index.html létrehozása - frontend

5. lépés 
GitHub repo létrehozása - repo megadása és readme hozzáadása

6. lépés 
GitHub repo klónozása lokális gépre

7. lépés 
A létrejöt projekt commitálása + leírás hozzáadása 

8. lépés 
Projekt push a main branch-el a repoba - egy másik gépen először fetch gomb majd pull gomb lehuzom a repoból akár egy másik gépre
(amennyiben talál frisseb változatot)

Git parancsok:
git fetch --all  - ellenőrizzük a friss változatokat
git branch -a - listázza a brencheket
git switch -c docker origin/docker - 

Docker parancsok:
docker build -t devops-1 . - docker image-t készít a teljes projekt kódból
docker run -p 8080:8080 devops-1  - futtatás docker környezetben
