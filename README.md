###Sistemas y Tecnologias Web

***Autor: Javier Clemente Rodriguez Gomez


##Instacion del rvm

El primer paso fue instalar rvm para linux, para ello se debe copiar en una terminal como un usuario normal el codigo necesario que especifica la web rvm.io/rvm/install

En mi caso ya lo tenia previamente instalado como se muestra en la imagen a continuacion

imagen rvm

Este programa permitira manejar las diferentes version de ruby instaladas como se indica en rvm.io/rvm/basics
Ruby

##Instalacion de Ruby y Bundle

Previamente tenia instalada la verion ruby 2.1.0p0 ademas de Rails 4.0.2

imagen ruby

 
Se comprobo que bundle funcionaba en la version instalada en el sistema
imagen bundle

En caso contrario habria que haberlo instalado mediante el comando: 
`sudo gem install bundle

##Instalacion de Sinatra y Twitter

El siguiente paso fue instalar Sinatra. 

Para ello se utilizo el comando sudo gem install sinatra
imagen sinatra

Para instalar twitter se ejecuto el comando `sudo gem install twitter
imagen twitter


##Instalacion de Git

El controlador de versiones Git habia sido instalado previamente
imagen git

En caso contrario hubiese sido necesario seguir el tutorial git-scm.com/book/es/Empezando-Instalando-Git

Para el caso de Linux en la distribucion debian el comando seria: 
`apt-get install git



