<script>
    
    document.write('Hola');
    document.write('<br>');
    document.write('buenas, este seria mi primer programa en este curso, ya habia hecho el rediseño para una pagina web, pero no un programa, deseenme suerte');
    document.write('<br>');
    document.write('fecha del trabjo: 22/08/2024');
    document.write('<br>');
    document.write('<br>');
    document.write('buenas compañeros y maestro, mi nombre es patricia alejandra flores malibran,vivo en tampico y estudio en la universidad de la uat,justo ya habia hecho trabajos de codigos html y css y justo hacer esto de nuevo me sirve para aprender mas :D');
    document.write('me dedico en mis tiempos libres a creacion de contenido, y trabajo como por el momento de ayudante para una ofisinista y ayudante de pemex, debes en cuando abro ventas personales de crecion de personales en modelos 2d a lo 3d, amo la creacion de diseño de personajes y en ocaciones los vendo');
    document.write('<br>');
    document.write('<br>');
    document.write("vayamos a hacer unas operaciones");

    /*creo variables*/
    var areatriangulo;
    var ladoCuadrado;
    var baseTrapecio;
    var ladoPentagono;

    /*pido datos en un dialogo del explorador*/
    areatriangulo = prompt('Dame el área del triángulo:', ''); // pido área triángulo
    ladoCuadrado = prompt('Dame el lado del cuadrado:', ''); // pido lado cuadrado
    baseTrapecio = prompt('Dame la base menor del trapecio:', ''); // pido base menor trapecio
    ladoPentagono = prompt('Dame el lado del pentágono:', ''); // pido lado pentágono

    /*convierto valores a valores numéricos para poder hacer operaciones*/
    areatriangulo = parseInt(areatriangulo);
    ladoCuadrado = parseInt(ladoCuadrado);
    baseTrapecio = parseInt(baseTrapecio);
    ladoPentagono = parseInt(ladoPentagono);

    /*hago operaciones*/
    var alturaTriangulo = (2 * areatriangulo) / baseTrapecio;
    var perimetroCuadrado = ladoCuadrado * 4;
    var areaTrapecio = ((baseTrapecio + 10) / 2) * alturaTriangulo; // Supuse una base mayor de 10 para el trapecio
    var perimetroPentagono = ladoPentagono * 5;

    /*escribo resultados*/
    document.write('<br>');
    document.write('<br>');
    document.write('La altura del triángulo es: ');
    document.write(alturaTriangulo);
    document.write('<br>');
    document.write('<br>');
    document.write('El perímetro del cuadrado es: ');
    document.write(perimetroCuadrado);
    document.write('<br>');
    document.write('<br>');
    document.write('El área del trapecio es: ');
    document.write(areaTrapecio);
    document.write('<br>');
    document.write('<br>');
    document.write('El perímetro del pentágono es: ');
    document.write(perimetroPentagono);
    document.write('<br>');
    document.write('<br>');

    /*la verdad fue entretenido este trabajo, yo agregue uno mas para ver que onda,pero asi quedo*/

</script>
