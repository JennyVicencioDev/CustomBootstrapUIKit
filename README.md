Proyecto base + UI Kit Bootstrap
========

1. Sass custom Bootstrap
2. Sass custom styles

## 1. Sass custom bootstrap

- Editar colores, texto y variables en el archivo *"sass/custom-bootstrap.scss"*. 
- Por si las dudas, esta estructura está inspirada en la sugerida en la [documentación del sitio de Bootstrap](https://getbootstrap.com/docs/5.0/customize/sass/), ya que no se considera una buena práctica editar los archivos sass principales. Así esto genera un nuevo stylesheet con tus cambios. 
- Para consultar todas las variables modificables de Bootstrap (`!default`) ir al archivo *"sass/bootstrap/variables.scss"*.
- Para compilar los nuevos estilos sass en terminal, usar cualquiera de los comandos:
```
npm run sass-bs
```
```
sass --watch sass/custom-bootstrap.scss:css/bootstrap.css
```

## 2. Sass custom styles

- Editar estilos personalizados de cada proyecto *sin bootstrap* en la carpeta "custom-styles". Tiene un orden parecido al patrón 7-1, pero pueden organízarlo como mejor les parezca.

- Para compilar los custom-styles sass en terminal, usar cualquiera de los comandos (pensado como si fuera un proyecto de tema Wordpress):
```
npm run sass-style
```
```
sass --watch sass/style.scss:style.css
```

## 3. UI Kit

- Ver htmls de la carpeta /UI-Kit para ver cambios realizados en componentes.
