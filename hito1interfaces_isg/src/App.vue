<template>
  <div class="container">
    <h1><b>LENGUAJES DE PROGRAMACIÓN</b></h1>
    <ul class="nav nav-tabs" id="myTab" role="tablist">
      <li class="nav-item" role="presentation">
        <button class="nav-link active" id="home-tab" data-bs-toggle="tab" data-bs-target="#home-tab-pane" type="button"
          role="tab" aria-controls="home-tab-pane" aria-selected="true">Home</button>
      </li>
      <li class="nav-item" role="presentation">
        <button class="nav-link" id="profile-tab" data-bs-toggle="tab" data-bs-target="#profile-tab-pane" type="button"
          role="tab" aria-controls="profile-tab-pane" aria-selected="false">Java</button>
      </li>
      <li class="nav-item" role="presentation">
        <button class="nav-link" id="contact-tab" data-bs-toggle="tab" data-bs-target="#contact-tab-pane" type="button"
          role="tab" aria-controls="contact-tab-pane" aria-selected="false">JavaScript</button>
      </li>
      <li class="nav-item" role="presentation">
        <button class="nav-link" id="disabled-tab" data-bs-toggle="tab" data-bs-target="#disabled-tab-pane" type="button"
          role="tab" aria-controls="disabled-tab-pane" aria-selected="false">Python</button>
      </li>
      <li class="nav-item" role="presentation">
        <button class="nav-link" id="other-tab" data-bs-toggle="tab" data-bs-target="#other-tab-pane" type="button"
          role="tab" aria-controls="other-tab-pane" aria-selected="false">Kotlin</button>
      </li>
    </ul>


    <div class="tab-content" id="myTabContent">
      <div class="tab-pane fade show active" id="home-tab-pane" role="tabpanel" aria-labelledby="home-tab" tabindex="0">
        <div class="container">
          <div class="row">
            <div class="col">
              <h2><b>¿QUÉ ES UN LENGUAJE DE PROGRAMACIÓN?</b></h2>
            </div>
          </div>
          <div class="row">
            <div class="col">
              <p>Un lenguaje de programación es un lenguaje formal (o artificial, es decir, un lenguaje con reglas
                gramaticales bien definidas) que proporciona a una persona, en este caso el programador, la capacidad y
                habilidad de escribir (o programar) una serie de instrucciones o secuencias de órdenes en forma de
                algoritmos con el fin de controlar el comportamiento físico o lógico de un sistema informático, para que
                de esa manera se puedan obtener diversas clases de datos o ejecutar determinadas tareas. A todo este
                conjunto de órdenes escritas mediante un lenguaje de programación se le denomina programa informático.
              </p>
              <p>Programar viene a ser el proceso de crear un software fiable mediante la escritura, prueba, depuración,
                compilación o interpretación, y mantenimiento del código fuente de dicho programa informático.
                Básicamente, este proceso se define aplicando lógicamente los siguientes pasos:
              </p>
              <ul class="list-group">
                <li class="list-group-item">El desarrollo lógico del programa para resolver un problema en particular.</li>
                <li class="list-group-item">Escritura de la lógica del programa empleando un lenguaje de programación específico (codificación del
                  programa).</li>
                <li class="list-group-item">Compilación o interpretación del programa hasta convertirlo en lenguaje de máquina.</li>
                <li class="list-group-item">Prueba y depuración del programa.</li>
                <li class="list-group-item">Desarrollo de la documentación.</li>
              </ul>
              <p>
                Los lenguajes de programación están formados por un conjunto de símbolos (llamado alfabeto), reglas
                gramaticales (léxico/morfológicas y sintácticas) y semánticas, que en conjunto definen las estructuras
                válidas del lenguaje y su significado. Existe el error común de tratar como sinónimos los términos
                'lenguaje de programación' y 'lenguaje informático'. Los lenguajes informáticos engloban a los lenguajes
                de programación y a otros más, como por ejemplo HTML (lenguaje para el marcado de páginas web, que no es
                propiamente un lenguaje de programación, sino un conjunto de instrucciones que permiten estructurar el
                contenido de los documentos).
              </p>
            </div>
          </div>
        </div>
      </div>
      <div class="tab-pane fade" id="profile-tab-pane" role="tabpanel" aria-labelledby="profile-tab" tabindex="0">
        <div class="container">
          <div class="row justify-content-start">
            <div class="col-1">
              <img alt="java_logo" src="./assets/imgs/java_logo.png" width="100px">
            </div>
            <div class="col-1 align-self-center">
              <h2>Java</h2>
            </div>
          </div>
          <div class="row justify-content-start">
            <div class="col">
              <p>Java es un lenguaje de programación y una plataforma informática que fue comercializada por primera vez
                en
                1995
                por Sun Microsystems.El lenguaje de programación Java fue desarrollado originalmente por James Gosling, de
                Sun
                Microsystems (constituida en 1983 y posteriormente adquirida el 27 de enero de 2010 por la compañía
                Oracle),
                y
                publicado en 1995 como un componente fundamental de la plataforma Java de Sun Microsystems. Su sintaxis
                deriva
                en gran medida de C y C++, pero tiene menos utilidades de bajo nivel que cualquiera de ellos. Las
                aplicaciones
                de Java son compiladas a bytecode (clase Java), que puede ejecutarse en cualquier máquina virtual Java
                (JVM)
                sin
                importar la arquitectura de la computadora subyacente. La compañía Sun desarrolló la implementación de
                referencia
                original para los compiladores de Java, máquinas virtuales y librerías de clases en 1991, y las publicó
                por
                primera
                vez en 1995. A partir de mayo de 2007, en cumplimiento de las especificaciones del Proceso de la Comunidad
                Java, Sun
                volvió a licenciar la mayoría de sus tecnologías de Java bajo la Licencia Pública General de GNU. Otros
                han
                desarrollado
                también implementaciones alternas a estas tecnologías de Sun, tales como el Compilador de Java de GNU y el
                GNU Classpath.
              </p>
              <p>Java se creó como una herramienta de programación para ser usada en un proyecto de set-top-box en una
                pequeña
                operación denominada the Green Project en Sun Microsystems en 1991. El equipo (green team), compuesto por
                trece
                personas y dirigido por James Gosling, trabajó durante 18 meses en Sand Hill Road, Menlo Park
                (California),
                para desarrollarlo.
                El lenguaje se denominó inicialmente Oak (por un roble que había fuera de la oficina de Gosling), luego
                pasó
                a llamarse
                green tras descubrir que Oak era ya una marca comercial registrada para adaptadores de tarjetas gráficas,
                y finalmente se le renombró java.
              </p>
            </div>
          </div>
          <div class="row">
            <div class="col">
              <div class="card" style="width: 18rem;">
                <div class="card-body">
                  <h5 class="card-title"><b>Portabilidad</b></h5>
                  <p class="card-text">Java permite que el código sea ejecutado en cualquier plataforma con JVM,
                    facilitando el desarrollo de aplicaciones que funcionan en diversos dispositivos y sistemas
                    operativos.
                  </p>
                </div>
              </div>
            </div>
            <div class="col">
              <div class="card" style="width: 18rem;">
                <div class="card-body">
                  <h5 class="card-title"><b>Orientado a objetos</b></h5>
                  <p class="card-text">Java se basa en clases y objetos, permitiendo la modularidad y extensibilidad
                    del código mediante la encapsulación de datos y funcionalidades en objetos.
                  </p>
                </div>
              </div>
            </div>
            <div class="col">
              <div class="card" style="width: 18rem;">
                <div class="card-body">
                  <h5 class="card-title"><b>Seguridad</b></h5>
                  <p class="card-text">Java prioriza la seguridad, con un administrador de seguridad que controla el
                    acceso a recursos sensibles y un modelo de ejecución de código sandbox para prevenir amenazas.
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col">
              <a class="btn btn-primary" href="https://www.java.com/es/" role="button">Visita la página oficial de
                Java</a>
            </div>
          </div>
        </div>
      </div>


      <div class="tab-pane fade" id="contact-tab-pane" role="tabpanel" aria-labelledby="contact-tab" tabindex="0">
        <div class="container">
          <div class="row justify-content-start">
            <div class="col-1">
              <img alt="javascript_logo" src="./assets/imgs/javascript_logo.png" width="100px">
            </div>
            <div class="col-1 align-self-center">
              <h2>JavaScript</h2>
            </div>
          </div>
          <div class="row justify-content-start">
            <div class="col">
              <p>JavaScript (abreviado comúnmente JS) es un lenguaje de programación interpretado, dialecto del estándar
                ECMAScript. Se define como orientado a objetos, basado en prototipos, imperativo, débilmente tipado y
                dinámico.
                Se utiliza principalmente del lado del cliente, implementado como parte de un navegador web permitiendo
                mejoras
                en la interfaz de usuario y páginas web dinámicas y JavaScript del lado del servidor (Server-side
                JavaScript
                o SSJS).
                Su uso en aplicaciones externas a la web, por ejemplo en documentos PDF, aplicaciones de escritorio
                (mayoritariamente
                widgets) es también significativo. JavaScript se diseñó con una sintaxis similar a C++ y Java, aunque
                adopta
                nombres y convenciones del lenguaje de programación Java. Sin embargo, Java y JavaScript tienen semánticas
                y propósitos diferentes. Su relación es puramente comercial, tras la compra del creador de Java (Sun
                Microsystems)
                de Netscape Navigator (creador de LiveScript) y el cambio de nombre del lenguaje de programación.
              </p>
              <p>JavaScript fue desarrollado originalmente por Brendan Eich de Netscape con el nombre de Mocha, el cual
                fue
                renombrado posteriormente a LiveScript, para finalmente quedar como JavaScript. En 1997 los autores
                propusieron JavaScript para que fuera adoptado como estándar de la European Computer Manufacturers
                'Association ECMA, que a pesar de su nombre no es europeo sino internacional, con sede en Ginebra. En
                junio
                de 1997 fue adoptado como un estándar ECMA, con el nombre de ECMAScript. Poco después también como un
                estándar ISO.
              </p>
            </div>
          </div>
          <div class="row">
            <div class="col">
              <div class="card" style="width: 18rem;">
                <div class="card-body">
                  <h5 class="card-title"><b>Lenguaje interpretado</b></h5>
                  <p class="card-text">JavaScript se ejecuta en tiempo real en el navegador o en el servidor, lo que
                    permite
                    una rápida implementación y desarrollo de aplicaciones web interactivas.
                  </p>
                </div>
              </div>
            </div>
            <div class="col">
              <div class="card" style="width: 18rem;">
                <div class="card-body">
                  <h5 class="card-title"><b>Tipado dinámico</b></h5>
                  <p class="card-text">No requiere declaraciones explícitas de tipos de datos, lo que facilita la
                    flexibilidad en el desarrollo y permite adaptarse a diferentes tipos de datos dinámicamente.
                  </p>
                </div>
              </div>
            </div>
            <div class="col">
              <div class="card" style="width: 18rem;">
                <div class="card-body">
                  <h5 class="card-title"><b>Asincronía y Event-Driven</b></h5>
                  <p class="card-text">Basado en el modelo de ejecución asíncrona y eventos, lo que permite la creación de
                    aplicaciones reactivas y eficientes que responden a las interacciones del usuario de manera rápida y
                    sin
                    bloqueos.
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col">
              <a class="btn btn-primary" href="https://www.javascript.com/" role="button">Visita la página oficial de
                JavaScript</a>
            </div>
          </div>
        </div>
      </div>


      <div class="tab-pane fade" id="disabled-tab-pane" role="tabpanel" aria-labelledby="disabled-tab" tabindex="0">
        <div class="container">
          <div class="row justify-content-start">
            <div class="col-1">
              <img alt="python_logo" src="./assets/imgs/python_logo.svg" width="100px">
            </div>
            <div class="col-1 align-self-center">
              <h2>Python</h2>
            </div>
          </div>
          <div class="row justify-content-start">
            <div class="col">
              <p>Python es un lenguaje de alto nivel de programación interpretado cuya filosofía hace hincapié en la
                legibilidad de su código, se utiliza para desarrollar aplicaciones de todo tipo, por ejemplo: Instagram,
                Netflix, Spotify, Panda3D, entre otros. Se trata de un lenguaje de programación multiparadigma, ya que
                soporta parcialmente la orientación a objetos, programación imperativa y, en menor medida, programación
                funcional. Es un lenguaje interpretado, dinámico y multiplataforma.

                Administrado por Python Software Foundation, posee una licencia de código abierto, denominada Python
                Software Foundation License. Python se clasifica constantemente como uno de los lenguajes de programación
                más populares.
                Python es un lenguaje de programación multiparadigma. Esto significa que más que forzar a los
                programadores
                a adoptar un estilo particular de programación, permite varios estilos: programación orientada a objetos,
                programación imperativa y programación funcional. Otros paradigmas están soportados mediante el uso de
                extensiones.
              </p>
              <p>Python fue creado a finales de los años ochenta por Guido van Rossum en Stichting Mathematisch Centrum
                (CWI), en los Países Bajos, como un sucesor del lenguaje de programación ABC, capaz de manejar excepciones
                e
                interactuar con el sistema operativo Amoeba. El nombre del lenguaje proviene de la afición de su creador
                por
                los humoristas británicos Monty Python.
              </p>
            </div>
          </div>
          <div class="row">
            <div class="col">
              <div class="card" style="width: 18rem;">
                <div class="card-body">
                  <h5 class="card-title"><b>Sintaxis clara y legible</b></h5>
                  <p class="card-text">Python prioriza la legibilidad del código, lo que facilita su aprendizaje y
                    mantenimiento, fomentando un estilo de programación limpio y eficiente para desarrolladores de todos
                    los
                    niveles.
                  </p>
                </div>
              </div>
            </div>
            <div class="col">
              <div class="card" style="width: 18rem;">
                <div class="card-body">
                  <h5 class="card-title"><b>Multiparadigma</b></h5>
                  <p class="card-text">Soporta programación imperativa, orientada a objetos y funcional, ofreciendo
                    flexibilidad para adaptarse a diferentes estilos de programación y facilitando la resolución de
                    diversos
                    problemas de manera eficiente.
                  </p>
                </div>
              </div>
            </div>
            <div class="col">
              <div class="card" style="width: 18rem;">
                <div class="card-body">
                  <h5 class="card-title"><b>Amplia biblioteca estándar</b></h5>
                  <p class="card-text">Viene con una extensa colección de módulos y bibliotecas para diversas tareas,
                    desde
                    manipulación de datos hasta desarrollo web, lo que acelera el desarrollo de aplicaciones al
                    proporcionar
                    soluciones listas para usar.
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col">
              <a class="btn btn-primary" href="https://www.python.org/" role="button">Visita la página oficial de
                Python</a>
            </div>
          </div>
        </div>
      </div>


      <div class="tab-pane fade" id="other-tab-pane" role="tabpanel" aria-labelledby="other-tab" tabindex="0">
        <div class="container">
          <div class="row justify-content-start">
            <div class="col-1">
              <img alt="kotlin_logo" src="./assets/imgs/kotlin_logo.png" width="100px">
            </div>
            <div class="col-1 align-self-center">
              <h2>Kotlin</h2>
            </div>
          </div>
          <div class="row justify-content-start">
            <div class="col">
              <p>Kotlin es un lenguaje de programación multiplataforma, estáticamente tipado, de alto nivel y propósito
                general con inferencia de tipos. Kotlin está diseñado para ser totalmente interoperable con Java, y la
                versión JVM de la biblioteca estándar de Kotlin depende de la Java Class Library, pero la inferencia de
                tipos permite que su sintaxis sea más concisa. Kotlin se dirige principalmente a la JVM, pero también
                compila a JavaScript (por ejemplo, para aplicaciones web front-end que utilizan React) o código nativo a
                través de LLVM (por ejemplo, para aplicaciones nativas de iOS que comparten lógica de negocio con
                aplicaciones Android.) Los costes de desarrollo del lenguaje corren a cargo de JetBrains, mientras que la
                Fundación Kotlin protege la marca comercial Kotlin.</p>
              <p>En julio de 2011 JetBrains reveló el Proyecto Kotlin, un nuevo lenguaje para la JVM, el cual había estado
                bajo desarrollo por un año. El líder de JetBrains, Dmitry Jemerov, dijo que la mayoría de lenguajes no
                tienen las características que buscaban, con la excepción de Scala. Sin embargo, citó el lento tiempo de
                compilación de Scala como una deficiencia obvia. Uno de los objetivos establecidos de Kotlin es el de
                compilar tan rápido como Java. En febrero de 2012, JetBrains liberó el código fuente del proyecto bajo la
                Licencia Apache 2.</p>
            </div>
          </div>
          <div class="row">
            <div class="col">
              <div class="card" style="width: 18rem;">
                <div class="card-body">
                  <h5 class="card-title"><b>Interoperabilidad</b></h5>
                  <p class="card-text">Kotlin puede interoperar sin problemas con código Java existente, lo que facilita
                    la
                    migración gradual y el uso de bibliotecas Java establecidas en proyectos Kotlin.
                  </p>
                </div>
              </div>
            </div>
            <div class="col">
              <div class="card" style="width: 18rem;">
                <div class="card-body">
                  <h5 class="card-title"><b>Seguridad del tipo de datos</b></h5>
                  <p class="card-text">Ofrece un sistema de tipos seguro que previene errores comunes durante la
                    compilación, reduciendo así los errores en tiempo de ejecución y mejorando la estabilidad del código.
                  </p>
                </div>
              </div>
            </div>
            <div class="col">
              <div class="card" style="width: 18rem;">
                <div class="card-body">
                  <h5 class="card-title"><b>Concisión y expresividad</b></h5>
                  <p class="card-text">Kotlin ofrece una sintaxis concisa y expresiva que permite escribir menos código
                    con
                    la misma funcionalidad que en Java, lo que aumenta la productividad del desarrollador y reduce la
                    probabilidad de errores.</p>
                </div>
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col">
              <a class="btn btn-primary" href="https://kotlinlang.org/" role="button">Visita la página oficial de
                Kotlin</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.card-text {
  color: black;
}
</style>
