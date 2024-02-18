# Guia para configurar vim
## Preparacion
Una vez se tenga nvim instalado en la computadora, necesitaras instalar un plugins para poder instalar los demas plugins.
el primero sera el [vim-plug](https://github.com/junegunn/vim-plug) el cual nos sirve como un gestor de plugins para que nos sea mas facil su instalacion
dicho gestor quedara instalado en la siguiente ruta en la computadora: `C:\Users\usuario\AppData\Local\nvim-data\site\autoload`.
ahora nos situaremos en la siguiente carpeta: `C:\Users\usuario\AppData\Local\nvim` dentro de esta carpeta vamos a crear una nueva carpeta llamada `plugged`,
una vez creada dicha carpeta procederemos a copiar todo lo que tengamos en nuestro archivo de [init.vim](https://github.com/Damacy64/init.vim) que esta en esta pagina.

## Instalacion
una vez que se haya hecho todo lo anterior, deberar abrir vim, ya abierto presionaras la tecla `esc` para poder escribir el siguiente comando `:PlugInstall`, una vez ejecutemos este comando, se instalaran todos los plugins que tengamos en nuestro **init.vim**.
cerramos nuestro nvim, y volvemos a abrirlo para que se noten los cambios
