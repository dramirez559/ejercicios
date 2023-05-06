pwd 
mkdir ejercicios
ls 
cd ejercicios/ 
mkdir ejercicio1
ls
cd ejercicio1/
touch README.md
cd ..
ejercicios/git init
git config --global user.name ""
git config --global user.email ""
git add .
git commit -m "Version Inicial"
git status
git log
git commit -m "Agrega solución primer ejercicio"
git remote add origin https://github.com/dramirez559/ejercicios.git
git push -u origin master
git commit -m "olvide los comandos"