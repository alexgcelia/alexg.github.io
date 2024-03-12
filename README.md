# alexg.github.io
Este repositorio es para la practica 6.1 Jekyll del módulo IAW

## Creamos un Github Codespaces y en el editaremos lo pedido en https://josejuansanchez.org/iaw/practica-jekyll/index.html
### Podremos hacer uso de estos comandos
#### jekyll new: Este comando nos permite crear la estructura de directorios y los archivos necesarios de un nuevo proyecto Jekyll.
```
docker run -it --rm -v "$PWD:/srv/jekyll" jekyll/jekyll jekyll new blog
```
#### jekyll build: Este comando nos permite generar un sitio HTML estático a partir del contenido del proyecto Jekyll.
```
docker run -it --rm -v "$PWD:/srv/jekyll" jekyll/jekyll jekyll build
```
Nota: Tenga en cuenta que este comando tendrá que ejecutarlo dentro del directorio donde tenga el contenido del blog.
#### jekyll serve: Este comando nos permite servir de forma local un sitio HTML estático generado a partir del contenido del proyecto Jekyll.
```
docker run -it --rm -p 4000:4000 -v "$PWD:/srv/jekyll" jekyll/jekyll jekyll serve --force_polling
```

### Publicaremos la web estática en Github Pages
#### Se recomienda seguir los pasos de la documentación oficial de GitHub Pages (https://pages.github.com/).

### Podemos cambiar temas para Jekkyl
#### En esta web puedes encontrar una extensa colección de themes para crear web estáticas con Jekyll (https://github.com/jekyll/jekyll/wiki/Themes).
