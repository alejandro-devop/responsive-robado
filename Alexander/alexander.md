<figure>
    <img src = "https://img.icons8.com/3d-fluency/344/github.png"  height = 200px width= 200px>
</figure>

<section>
    <h1>
    <strong>
        My first repo
    </strong>
    </h1>
</section>

<section>
    <article>
    <header>
     <h2>
        <strong>
            Primeros pasos
        </strong>
     </h2>
        <h4>
        <header>
        ¡¡Hola!!<br> 
            En este documento encuentras una pequeña guía con el paso a paso de como crear tu primer repositorio 
        </h4>
     </header>
     <nav>
       <h5>
        lista de paso a paso
       </h5>
       <ol>
        <li>
           <a href="#container-git-init">Iniciar un nuevo repositorio</a>
        </li>
        <li>
            <a href="#container-git-add">Guardar cambios</a>
        </li>
        <li>
        </li>
        <li>
        </li>
        <li>
        </li>
        <li>
        </li>
        <li>
        </li>
        <li>
        </li>
       </ol>
     </nav>
    </article>
    <br>
    <section>
     <article id="container-git-init">
     <header>
        <h4>
        <strong>
            Git init
        </strong>
        </h4>
     </header>
     <footer>
        <p>
        Para crear un nuevo repositorio en git, utilizamos el comando <em>"git  init" </em>
        </br>
        Al ejecutar el comando se crea una carpeta oculta  llamada <em>".git"</em> . Este es <strong>El directorio de Git </strong>  donde se almacenan los metadatos y la base de datos de objetos para tu proyecto
     </footer>
     </article>
     </br>
     <article id ="container-git-add">
     <header>
        <h4>
         <strong>
            Git add  &nbsp - &nbsp Git status
         </strong>
        </h4>
     </header>
    <footer>
        <p>
            Primero crearemos un archivo("puedes crear un archivo desde consola con el comando: '<strong>touch [nombre del archivo]'</strong>")
            </br>
            Para poder ver los cambios introduciremos el comando  <em>"git status"</em>
            </br>
            Al introducir este comando podemos observar  información importante, como :
            </br>
            <strong>On branch master</strong> 
            </br>
            on breach nos indica en que rama estamos
            </br>
           <strong> Changes not staged for commit
        </strong>
        </br>
        esto nos indicara que cambios hay para y si los archivos se les estan haciendo seguimeinto. Por los genral cuando un archivo es modificado  se muesa una letra <strong>M</strong> y/o de color rojo.Esto indica que el archivo ha sido modificado pero no se esta realizando seguimiento.
        </br>
        Para indicarle a git que debe escuchar realizar seguimiento a al archivo utilizamos el comando <em>"git add [nombre del arichovo] o git add . para selecionar todos los archivos"</em>
        </br>
        Al ingresar este comando podemos volver a ingresar el  comando <em>"git status"</em> y podremos observar que el archivo ahora se encuentra de color ver y la leta <strong>M</strong> cambio a <strong>A</strong>. Ahora git esta realizando seguimeitno a nuestro archivo.  
        </p>
    </footer>
     </article>
    </section>

</section>
