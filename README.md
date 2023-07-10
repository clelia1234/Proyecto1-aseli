tittle es el texto que se ve en la pestaña
asection 
    article 1
        h2
        p
        p 

    article

section
    article
        h2
        p
        p
    article
section

section
    article
        form
           <label for="nombre">nombre</label> para darle nombre al input
            input (nombres, fechas, etc)
            input
            input para pedir opciones: 
            <label for="opciones"></label>
                <option value="1">opcion 1</option>
                <option value="2">opcion 1</option>
            diferencia entre article y div es semantica. div va dentro de article
            nav.- donde estaran los iconos de navegacion 
            main es lo principal 

            input type=checkbox

            para enviar datos:
            button type=submit>enviar datos</button>

            para hipervinculo: en index.html
            header
            nav
            ul
            il
            a href="./index.html">
                        inicio
            a
            li
            li
            a href="./contacto.html">
            contacto
            ul

            en contacto.html
            se crea la otra pagina y se pone la misma estructura

            copiar header y footer en contacto

            span no sirve para nada, solo para separar estilizados
            b sirve para poner en negritas

en figure se usa:
            -img (ruta absoluta)
                img src" se agrega la liga"
            -figtcaption para poner fotos con descripcion

            puede ser por ruta absoluta

            ruta relativa
            se usa para imagenes dentro de la compu: img src="se agrega la carpaeta

            link se utiliza para vincular html y css

            background pone fondo de color
            border sirve para englobar el contenedor (grosor, tipo de linea, color)
            font-family determina la fuente
            antes del body se puede escribir :root{} y se aplica para variables que se van a repetir. se escribe por ejemplo: --font-family: arial
            y luego en el selector, si se quiere usar, solo se escribe: font-family:var(--font-family);

            *{} se utiliza para resetear todos los valores predeterminados. se le llama normalizar. se utiliza para resetear:
            margin 0
            padding 0
            box-sizing:border-box

            display ejecuta los layouts grandes (block toma el 100 de pantalla; inline block toma el ancho de contenido)

            max width es para que se recorra cuando se minimiza

            id= identificador. solo se puede usar unavez. si es id se utiliza con #
            en div se pone .

            class=puede usarse varias veces
            margin( arriba, laterales, abajo)

            input placeholder="lo que va adentro del input buscador"

            div class="accordion"> para hacerun desplegado
                <div class="item">
                p
                p
                

            en index.cxx en la primera parte se puede poner:
            @import url(la liga que se copia en import, en google fonts)
            mas delante en secciones o body se puede abreviar poniendo solo font-family: "nombre de tipograia"

            line-height para separar bloques
            display: flex se usa flexbox para trabajar componentes de manera unidimensional. alinea de manera horizontal

            .item{
                display:grid; trabaja de forma bidimensional
                grid-template-columns (se agrega medidas en representacion de columnas. ejemlo 30px 30px 30px son 3 columnas)
                column-gap: es la separacion de columnas

                gap es separacion de columnas
                line-height separacion de oraciones

            }

            responsive design:
            imagenes fluidas
            media queries
            -debajo de 1344 px para escritorios pequeños
            -"1024 tablets
            1200 compus portatiles
            944 tablets pequeñas
            544 telefonos

            cheatseat(comandos)


    cualquier cambio