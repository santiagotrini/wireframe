# Apunte

Pasos para subir una web a GitHub Pages

1. Crear el directorio, `mkdir wireframe`
2. Cambiar al directorio, `cd wireframe`
3. Inicializar repo de git, `git init`
4. Crear un archivo para commitear, `echo hola >> index.html`
5. Configurar la identidad si no lo hicieron, `git config user.name` y `git config user.email`.
6. Agregar al stage, `git add .`
7. Commitear, `git commit -m "primer commit"`
8. Agregar el remoto, `git remote add origin https://github.com/usuario/repo`
9. Pushear por primera vez, `git push -u origin master`
10. Te pide las credenciales, usuario y token, conseguir token en `github.com/settings/tokens`.
11. Ir a settings del repo, menu Pages, poner deploy from branch, la rama que tenes (master seguramente).


## Contenido de index.html

```html
<html>
  <body>
    <h1>Hola</h1>
  </body>
</html>
```
