Contributing
============

Dividir cada tema en grupos de slides. Para esto, hay que anidar cada slide
(`<section>`) del tema dentro de una `<section>` que lo englobe.

Esto hace que la navegacion entre temas sea horizontal, pero entre diapositivas
de un mismo tema, vertical.

Cada grupo de slides, debe ir guardado en `src/slides`.

Va a pasar que un grupo necesite dividirse en pequeñas sub-secciones. En esos
casos, crear un directorio nuevo en `src/slides` y guardar los archivos ahí.

Para mantener el orden y que los archivos aparezcan listados como corresponde,
el nombre del archivo debería seguir el formano `NN-nombre-de-la-seccion.html`,
donde `NN` se refiere a dos nros, por ejemplo: `01`, `02`, etc...

Ejemplo
-------

`src/slides/02-php7-features/05-null-coalesce-op.html`:

```html
<section> <!-- Groupo de slides -->
    <section>
        <h2><code>??</code> The <em>Null Coalesce Operator</em></h2>
    </section>
    <section>
        <h3>Etc...</h3>
        <p class="fragment">More etc...</p>
    </section>
</section>
```
