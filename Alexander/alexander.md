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
            <a href="#container-git-add">Seguimiento</a>
        </li>
        <li>
            <a href="#container-git-commit">Guardar cambios</a>
        </li>
        <li>
          <a href="#container-git-init">Repositorio remoto</a>
        </li>
        <li>  <a href="#container-git-init"> Enviar cambios al tepositorio remoto</a>
        </li>
         <a href="#container-git-init">Actualizar repositorio local</a>
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
        Al ingresar este comando podemos volver a ingresar el  comando <em>"git status"</em> y podremos observar que el archivo ahora se encuentra de color verde y la leta <strong>M</strong> cambio a <strong>A</strong>. Ahora git esta realizando seguimeitno a nuestro archivo.  
        </p>
    </footer>
     </article>
    </section>
    </br>
    <section>
        <article id = container-git-commit>
        <header>
            <h4>
                <strong> Git commit
                </strong>
            </h4>
        </header>
        <footer>
            <p>
                El comando <em>git commit</em> nos ayuda a crear una punto en el tiempo en el que podemos retornar,Esta informacón se almacena en la carpeta
                <em>
                .git
                </em>, le damos la bandera <strong>
                -M</strong> para agregar información hacerca del commit que se va a realizar
                ('git commit -m "example"').
                </br>
                si ingresamos el comando git status notaremos que el archivo ya no se visualiza, eso se deba a que se encuentra en el area de repositorio
            </p>
            </footer>
        </article>
        </br>
        <article>
            <header>
            <h4> 
                <strong>
                    Git add remote origen
                </strong>
             </h4>
            </header>
            <footer>
            <p> git es una herramienta muy utilizada con <em>github</em>. Este nos permite alojar nuestro reposotorio local y compartirlo con nuestro equipo de trabajo o la comunidad de desarollo en si.
            <br>
            para poder enviar nuestro repositorio a git primero debemos crear una cuenta y crear un repo. Luego tenemos que indicarle la ruta a git del repositorio, para eso existe el comando 
            <em>
                git add remote origen [ "path del la ruta" ]
            </em>
            con este comando abremos agreagdo la ruta.
            </p>
            </footer>
        </article>
        </br>
        <article>
            <hearder>
                <h4>
                    <strong>
                    Git push 
                    </strong>
                </h4>
            </hearder>
            <footer>
            <p>
                Cuando ya realizamos un commit podemos eniviar nuestro repositorio a un repositorio remoto, esto lo podemos hacer mediente el comando 
                <em>
                    "git push origin [branch]"
                </em>
                por defecto la rama principal es master.
                </br>
                para subir nuestro contenido a la rama master utilizariamos el comando  <em>
                    "git push origin master"
                </em>.
                </br>
                ahora nuestro repo esta en remoto
            </p>
            </footer>
        </article>
        <article>
            <header>
                <h4>
                <strong>
                Git pull
                </strong>
                </h4>
            </header>
            <footer>
            <p>
            cuando trabajamos con repositorios remotos y con colaboradores, se recomienda antes de iniciar actualizar el repo por si algun compañero hizo algunos nuevos cambios.
            esto lo podemos realizar mediante el comando <em> "git pull origin [branch]"</em>.
            </br>
            si no actualizamos nuestro repo podemos encontrarnos con conflictos
            </p>
            </footer>
        </article>
    </section>
    </br>
    <footer>
        <p>
         <strong>by Kravmaga</strong> 
        </p>
    </footer>
</section>
