# Comandos usados

- ## **Generacion de la aplicacion genérica**
  
npx -p @angular/cli@15 ng new amazonmf --create-application=false --package-manager=npm

- ## **Generación de la aplicación raiz de microfrontends**

npx ng generate application shell --routing --style=css

- ## **Generacion del resto de módulos dinámicos**

npx ng generate application carrito --routing --style=css

npx ng generate application productos --routing --style=css

npx ng generate application perfil --routing --style=css

- ## **Generacion de las librerias compartidas por los distintos microfrontends**

npx ng generate library core

npx ng generate library shared

npx ng generate library models
