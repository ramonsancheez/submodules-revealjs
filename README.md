# submodules-revealjs

Lo primero que debemos hacer, es habilitar GitHub Pages en el Settings del repositorio, indicando la rama main como la principal para los cambios.
<img width="1035" alt="image" src="https://user-images.githubusercontent.com/91556453/173178618-b118bdca-d3ef-4b90-885f-b5930fab6bbf.png">

Clonamos e iniciamos el repositorio de revealjs.js con:
```
git submodule add https://github.com/hakimel/reveal.js revealjs
git submodule update --init --recursive
```

Para finalizar, copiamos el index.html del repositorio clonado al nuestro, y le modificamos el contenido:
<img width="586" alt="image" src="https://user-images.githubusercontent.com/91556453/173178743-cba067ee-aac5-4c27-8de9-018c9dda715b.png">

