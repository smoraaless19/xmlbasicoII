<!--
Nombre: Sergio Morales
Curso: ASIR1
Fecha: 01/04/2025
Ejercicio: XML Básico 2
-->

<!-- Ejercicio 1: Lista de marcadores de páginas web -->
<marcadores>
    <pagina>
        <nombre>W3Schools</nombre>
        <descripcion>Tutoriales de informática.</descripcion>
        <url>https://www.w3schools.com/</url>
    </pagina>
    <pagina>
        <nombre>Wikipedia</nombre>
        <descripcion>La enciclopedia libre.</descripcion>
        <url>http://www.wikipedia.org/</url>
    </pagina>
    <pagina>
        <nombre>W3C</nombre>
        <descripcion>World Wide Web Consortium.</descripcion>
        <url>http://www.w3.org/</url>
    </pagina>
</marcadores>

<!-- Ejercicio 2: Información sobre equipos de fútbol -->
<equipos>
    <equipo>
        <nombre>Real Madrid</nombre>
        <ciudad>Madrid</ciudad>
        <jugadores>
            <jugador posicion="delantero">
                <nombre>Vinícius Jr.</nombre>
                <nacionalidad>Brasil</nacionalidad>
            </jugador>
            <jugador posicion="portero">
                <nombre>Thibaut Courtois</nombre>
                <nacionalidad>Bélgica</nacionalidad>
            </jugador>
        </jugadores>
    </equipo>
    <equipo>
        <nombre>FC Barcelona</nombre>
        <ciudad>Barcelona</ciudad>
        <jugadores>
            <jugador posicion="medio">
                <nombre>Pedri</nombre>
                <nacionalidad>España</nacionalidad>
            </jugador>
            <jugador posicion="defensa">
                <nombre>Ronald Araújo</nombre>
                <nacionalidad>Uruguay</nacionalidad>
            </jugador>
        </jugadores>
    </equipo>
</equipos>

<!-- Ejercicio 3: Receta de cocina -->
<receta>
    <nombre>Sopa de cebolla</nombre>
    <comensales>4</comensales>
    <ingredientes>
        <ingrediente cantidad="1 kg">Cebollas</ingrediente>
        <ingrediente cantidad="2 litros">Caldo de carne</ingrediente>
        <ingrediente cantidad="100 gr">Mantequilla</ingrediente>
        <ingrediente cantidad="1 cucharada">Harina</ingrediente>
        <ingrediente cantidad="100 gr">Queso emmental</ingrediente>
        <ingrediente>Pan tostado en rebanadas</ingrediente>
        <ingrediente>Tomillo</ingrediente>
        <ingrediente>1 hoja de laurel</ingrediente>
        <ingrediente>Pimienta</ingrediente>
    </ingredientes>
    <proceso>
        <paso>Pelar y partir las cebollas en rodajas finas.</paso>
        <paso>Rehogarlas con la mantequilla, sal y pimienta a fuego lento hasta que estén transparentes sin dorarse.</paso>
        <paso>Añadir la harina sin dejar de remover.</paso>
        <paso>Ponerlo en una cazuela con el caldo, el tomillo y el laurel.</paso>
        <paso>Dejar cocer a fuego lento durante unos 15 minutos.</paso>
        <paso>Poner las rebanadas de pan encima, espolvorear el queso y gratinar al horno.</paso>
    </proceso>
</receta>

<!-- Ejercicio 4: Información de alumnos del módulo de DAW -->
<modulo>
    <nombre>Lenguajes de Marcas</nombre>
    <horas_semanales>4</horas_semanales>
    <caracter>Obligatorio</caracter>
    <fecha_inicio>15/09/2023</fecha_inicio>
    <fecha_fin>22/06/2024</fecha_fin>
    <alumnos>
        <alumno>
            <nombre>Ana Fernández Gutiérrez</nombre>
            <dni>51623487V</dni>
            <telefono>666544566</telefono>
            <email>anafernandez@gmail.com</email>
            <direccion>C/ Amatista, 14, 28905 Getafe (Madrid)</direccion>
        </alumno>
        <alumno>
            <nombre>Carlos López Sánchez</nombre>
            <dni>52369874B</dni>
            <telefono>666455477</telefono>
            <email>carloslopez@gmail.com</email>
            <direccion>C/ Ópalo, 15, 28905 Getafe (Madrid)</direccion>
            <nota>apto</nota>
            <faltas_asistencia>0</faltas_asistencia>
        </alumno>
    </alumnos>
</modulo>
