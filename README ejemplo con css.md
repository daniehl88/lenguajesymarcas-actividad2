# lenguajesymarcas-actividad2



ARCHIVO HTML.

<!DOCTYPE html>
<html>
<head>
    <title>ej_seleccionar_capa_CSS</title>
    <link rel="stylesheet" type="text/css" href="estilo.css">
</head>
<body>
    <div id="menu">
        <ul>
            <li><a href="#op1">Opción 1</a></li>
            <li><a href="#op2">Opción 2</a></li>
            <li><a href="#op3">Opción 3</a></li>
        </ul>
    </div>
    <div id="info">
        <div id="op1">
            <h1>Opción 1</h1>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Expedita maiores blanditiis, perferendis soluta facilis dolor, aliquid animi similique fugit sit quod cupiditate quisquam excepturi delectus reprehenderit rem. Odit, nam facere.</p>
        </div>
        <div id="op2">
            <h1>Opción 2</h1>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam tempore rem molestiae perspiciatis. Excepturi iusto nihil, consequuntur assumenda, deleniti commodi deserunt natus, animi repudiandae doloribus sint perspiciatis eum totam esse!</p>
        </div>
        <div id="op3">
            <h1>Opción 3</h1>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Laborum voluptates earum dolorum consequuntur officiis corrupti, sed, ex reiciendis autem rem inventore, ipsum vero cum? Quas tempora fuga consequatur ullam quo.</p>
        </div>
    </div>
    <div id="pie">
      <p>algo en el pie</p>
    </div>
</body>
</html>





----------------------------------------ARCHIVO CSS------------------------------------------------------

li{
    display: inline;
}

#info, #op1, #op2, #op3{
    height: 900px;
    width: 1000px;
}

#info{
    /*No es necesario, solamente es para saber el marco de trabajo*/
    border: black solid 2px;

    /*texto que no entre en la ventana se oculta*/
    overflow: hidden;
}
