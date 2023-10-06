Después de haber creado una carpeta en el escritorio, los comandos utilizados por orden en la consola fueron:

cd devjumpers
git clone https://github.com/atal1212/devjumpers.git


Una vez creado el repositorio, ingresé en él y al abrir la consola utilicé los comandos:

touch README.md
git commit -m 'commit incial'
git config --global user.email 'cuentasatal@gmail.com'
git add README.md
git commit -m "Commit inicial"
git push -u origin master
touch privado.txt
mkdir privada
touch 1.txt
git add 1.txt
git commit -m "Añadir fichero 1.txt"
git branch v0.2
git checkout v0.2
touch 2.txt
git add 2.txt
git commit -m "Añadir fichero 2.txt en la rama v0.2"
git push origin v0.2
git checkout master
git merge v0.2
echo "Hola" > 1.txt
git add 1.txt
git commit -m "Añadir Hola en 1.txt en la rama master"
echo "Adios" > 1.txt
git add 1.txt
git commit -m "Añadir Adios en 1.txt en la rama v0.2"
git merge v0.2
git branch --merged
git branch --no-merged
git commit -m "Arreglar conflicto en 1.txt"
git branch -d v0.2  
git push origin --delete v0.2 
git list
  




