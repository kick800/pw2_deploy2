# Vite Webbundler installation

## Installatio

```bash

node --version # v18

nmp create vite

vite ask for project: nombre del proyecto si espacios ni mayusculas ni especiales
vite asks for framwework: vanilla
vite asks for variant: javascript

cd nombre-del-proyecto
npm install
npm run dev

```
# para generar los ASSETS de produccion

```bash

npm run build

# para copiar y pegar la ruta

Copy-Item -Path .\portalesweb2\ -Destination .\pw2_vite\ -recurse

#Git init

PS C:\Users\josec\Desktop\clase\pw2_vite> git init

#Git add

PS C:\Users\josec\Desktop\clase\pw2_vite> git add . 

#Git status

PS C:\Users\josec\Desktop\clase\pw2_vite> git satus

#git commit

PS C:\Users\josec\Desktop\clase\pw2_vite> git commit -m "Deploy initial without workflow"

#git remote

PS C:\Users\josec\Desktop\clase\pw2_vite> git remote add origin https://github.com/kick800/pw2_deploy-prueba-.git

#git branch

PS C:\Users\josec\Desktop\clase\pw2_vite> git branch
* master

#git push

PS C:\Users\josec\Desktop\clase\pw2_vite> git push -u origin master