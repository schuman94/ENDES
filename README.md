Sergio Chulian Mantel

git clone https://github.com/schuman94/refuerzo-SCM.git
git add .
git commit -m "commit inicial"

git push

Creamos el archivo "privado.txt" y el directorio "privada"
Creamos el archivo ".gitignore" y le añadimos los dos anteriores
Creamos "1.txt"

git add .
git commit -m "gitignore y 1.txt añadidos"
git push

git tag v0.1 -m "Version 0.1"
git push --tags
