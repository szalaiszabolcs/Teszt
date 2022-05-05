#Hello
…or create a new repository on the command line
echo "# Teszt" >> README.md         #fájl léterhozása, az első sorba "#teszt" kerül
git init         #a git mappa inicializálása
git add README.md          #staging, changes azaz a  változások mentése
git commit -m "first commit"          #változtatások jóváhagyása
git branch -M main         #a fejlesztési ág átnevezése main-re 
git remote add origin https://github.com/szalaiszabolcs/Teszt.git       #távoli repo hozzáadása origin néven 
git push -u origin main       #a fejlesztési ág feltöltése első alkalommal
…or push an existing repository from the command line
git remote add origin https://github.com/szalaiszabolcs/Teszt.git
git branch -M main
git push -u origin main
