Pasos realizados
1. Clonar el repositorio original
   Usé el comando git clone para clonar el repositorio original desde GitHub a mi máquina local. Esto lo hice con la siguiente línea de comando:

bash
Copiar código
git clone https://github.com/danielcastelao/pruebasReadme repo_metodo2
Esto creó una carpeta llamada repo_metodo2 que contiene los archivos del repositorio original.

2. Acceder al directorio clonado
   Navegué al directorio del repositorio clonado con:

bash
Copiar código
cd repo_metodo2
3. Eliminar el repositorio remoto original
   Para desvincular este proyecto del repositorio original, eliminé la referencia remota llamada origin con el siguiente comando:

bash
Copiar código
git remote remove origin
4. Crear un nuevo repositorio en mi cuenta de GitHub
   En mi cuenta de GitHub, creé un nuevo repositorio vacío llamado repo_metodo2. Este será el repositorio remoto al que conectaré mi proyecto.

5. Añadir mi propio repositorio remoto
   Conecté el proyecto local al nuevo repositorio remoto que creé en mi cuenta de GitHub. Esto lo hice con el siguiente comando:

bash
Copiar código
git remote add origin https://github.com/<mi_usuario>/repo_metodo2.git
Reemplacé <mi_usuario> con mi nombre de usuario de GitHub.

6. Editar el archivo README.md
   Modifiqué este archivo README.md para explicar el proceso seguido.

7. Subir los cambios al nuevo repositorio
   Finalmente, subí los cambios al nuevo repositorio remoto con los siguientes comandos:

bash
Copiar código
git add README.md
git commit -m "Añadir explicación del método 2"
git push -u origin main
