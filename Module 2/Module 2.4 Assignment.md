# Módulo 2.4 Asignación

En esta lección, aprendió acerca de los conflictos de fusión. Para completar esta tarea, creará un archivo "README.md" que diga "Hola mundo". Copie y pegue los siguientes comandos en su línea de comando, luego presione Entrar:

<<<<<<< HEAD
```
mkdir MergeConflict
cd MergeConflict/
git init
touch README.md
echo "echo Hello" > README.md
git add .
git commit -m "first commit on master"
git checkout -b new-branch
echo "Hello World" > README.md
git add .
git commit -m "first commit on new-branch"
git checkout master
echo "Hola" > README.md
git add .
git commit -m "second commit on master"
git merge new-branch
```
=======
''
mkdir MergeConflict
cd MergeConflict /
git init
toque README.md
echo "echo Hola"> README.md
git add.
git commit -m "primer compromiso con el maestro"
git checkout -b nueva rama
echo "Hola mundo"> README.md
git add.
git commit -m "primer compromiso en nueva rama"
maestro de git checkout
echo "Hola"> README.md
git add.
git commit -m "segundo compromiso en el maestro"
git fusionar nueva rama
''
>>>>>>> 4326e42cc9b94a35f89bbbd4b83f59e36c996da2

Este "script" creará un conflicto de fusión. Resuelva el conflicto de fusión para que el texto en `README.md` sea` "Hola mundo" `.

## Sumisión
Para enviar esta tarea, cree un problema titulado "Asignación del módulo 2.4" en este repositorio. En el problema, proporcione una captura de pantalla de su línea de comandos que muestre los comandos que usó para resolver el conflicto de fusión en esta asignación, luego continúe con el siguiente módulo.
