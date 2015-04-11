# clasegithub
Esto es un ejemplo de github 

Una vez instalas GIT debes configurarlo:
git config --global user.name "pepe"
git config --global user.mail "xxxx@xxx.xx"

Generando tu Public Key:
ssh-keygen

Leyendo tu llave para copiarla a github:
cat ~/.ssh/RjKyo.pub

Arrancado tu proyecto:
git init

Crear archivo
touch README

Agregar README
git add README

COMENTARIO
git commit -m "tu primer commit"

git push origin master 

Si no te llega a dar ingresar por denegacion:
ssh-add ~/.ssh/RjKyo

