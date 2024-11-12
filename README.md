Práctica 1 UT2 


Terminar el porfolio de con la gúia del vídeo.

Contexto:

1. Se tiene un primer código el cual debe ser revisado y observado, el cual se clona de este repositporio.

2. Se debe concluír los pasos que hagan falta del vídeo.

3. Registrar al menos 4 ejemplos del código dónde se utilice flexbox.En la section services se usa un display grid especial para hacer responsive las tarjetas(profundice en él y consulte la explicación)

4. Usar correctamente las variables definidas en la psudoclase :root

5. LLenar con datos reales de vuestro CV.

6. Crear un repositorio sobre el proyecto, crear una rama llamada develpment y trabajar sobre esta, cuando se culminen los commits y el proyecto hacer merge a main.(observación: debe borrar el directorio .git para crear el repositorio personal)

7. Publicar en github pages o en netlify.


   - **Ejemplo 1: Menú de navegación**  
   En el menú de navegación, se utiliza Flexbox para distribuir los elementos de manera equitativa y hacer que el menú sea flexible:

   ```css
   .nav {
       display: flex;
       align-items: center;
       justify-content: space-around;
       flex-wrap: wrap;
       gap: 2rem;
       padding: 2rem 0;
   }
