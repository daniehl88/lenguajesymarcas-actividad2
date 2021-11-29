# lenguajesymarcas-actividad2

EJEMPLOS CON JAVASCRIPT
ARCHIVO HTML

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>ej_seleccionar_capa_JS</title>
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>

<body>
    <div id="menu">
        <ul>
            <li><a href="#" onclick="return ShowContent('op1');">Opción 1</a></li>
            <li><a href="#" onclick="return ShowContent('op2');">Opción 2</a></li>
            <li><a href="#" onclick="return ShowContent('op3');">Opción 3</a></li>
        </ul>
    </div>

    <div id="info">
        <div id="op1">
            <h1>Unidad 1</h1>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Officia deleniti animi beatae sapiente?
                Veritatis, nostrum accusamus optio vel rem ullam obcaecati fugit. Nam facere quisquam minus,
                necessitatibus dolore minima animi!Impedit corrupti aliquid incidunt tempora! Provident optio earum
                minus reprehenderit a! Reprehenderit debitis odit totam voluptatem magni? Sequi necessitatibus mollitia
                facilis qui, architecto quo quibusdam reiciendis exercitationem eos, numquam blanditiis.
                Lorem, ipsum dolor sit amet consectetur adipisicing elit. Officia deleniti animi beatae sapiente?
                Veritatis, nostrum accusamus optio vel rem ullam obcaecati fugit. Nam facere quisquam minus,
                necessitatibus dolore minima animi!Impedit corrupti aliquid incidunt tempora! Provident optio earum
                minus reprehenderit a! Reprehenderit debitis odit totam voluptatem magni? Sequi necessitatibus mollitia
                facilis qui, architecto quo quibusdam reiciendis exercitationem eos, numquam blanditiis.
                Lorem, ipsum dolor sit amet consectetur adipisicing elit. Officia deleniti animi beatae sapiente?
                Veritatis, nostrum accusamus optio vel rem ullam obcaecati fugit. Nam facere quisquam minus,
                necessitatibus dolore minima animi!Impedit corrupti aliquid incidunt tempora! Provident optio earum
                minus reprehenderit a! Reprehenderit debitis odit totam voluptatem magni? Sequi necessitatibus mollitia
                facilis qui, architecto quo quibusdam reiciendis exercitationem eos, numquam blanditiis.</p>
        </div>
        <div id="op2">
            <h1>Unidad 2</h1>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Officia deleniti animi beatae sapiente?
                Veritatis, nostrum accusamus optio vel rem ullam obcaecati fugit. Nam facere quisquam minus,
                necessitatibus dolore minima animi!Impedit corrupti aliquid incidunt tempora! Provident optio earum
                minus reprehenderit a! Reprehenderit debitis odit totam voluptatem magni? Sequi necessitatibus mollitia
                facilis qui, architecto quo quibusdam reiciendis exercitationem eos, numquam blanditiis.
                Lorem, ipsum dolor sit amet consectetur adipisicing elit. Officia deleniti animi beatae sapiente?
                Veritatis, nostrum accusamus optio vel rem ullam obcaecati fugit. Nam facere quisquam minus,
                necessitatibus dolore minima animi!Impedit corrupti aliquid incidunt tempora! Provident optio earum
                minus reprehenderit a! Reprehenderit debitis odit totam voluptatem magni? Sequi necessitatibus mollitia
                facilis qui, architecto quo quibusdam reiciendis exercitationem eos, numquam blanditiis.</p>
        </div>
        <div id="op3">
            <h1>Unidad 3</h1>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Officia deleniti animi beatae sapiente?
                Veritatis, nostrum accusamus optio vel rem ullam obcaecati fugit. Nam facere quisquam minus,
                necessitatibus dolore minima animi!Impedit corrupti aliquid incidunt tempora! Provident optio earum
                minus reprehenderit a! Reprehenderit debitis odit totam voluptatem magni? Sequi necessitatibus mollitia
                facilis qui, architecto quo quibusdam reiciendis exercitationem eos, numquam blanditiis.Lorem, ipsum
                dolor sit amet consectetur adipisicing elit. Officia deleniti animi beatae sapiente?
                Veritatis, nostrum accusamus optio vel rem ullam obcaecati fugit. Nam facere quisquam minus,
                necessitatibus dolore minima animi!Impedit corrupti aliquid incidunt tempora! Provident optio earum
                minus reprehenderit a! Reprehenderit debitis odit totam voluptatem magni? Sequi necessitatibus mollitia
                facilis qui, architecto quo quibusdam reiciendis exercitationem eos, numquam blanditiis.
                Reprehenderit debitis odit totam voluptatem magni? Sequi necessitatibus mollitia
                facilis qui, architecto quo quibusdam reiciendis exercitationem eos, numquam blanditiis.
                Lorem, ipsum dolor sit amet consectetur adipisicing elit. Officia deleniti animi beatae sapiente?
                Veritatis, nostrum accusamus optio vel rem ullam obcaecati fugit. Nam facere quisquam minus,
                necessitatibus dolore minima animi!Impedit corrupti aliquid incidunt tempora! Provident optio earum
                minus reprehenderit a! Reprehenderit debitis odit totam voluptatem magni? Sequi necessitatibus mollitia
                facilis qui, architecto quo quibusdam reiciendis exercitationem eos, numquam blanditiis.
                Lorem, ipsum dolor sit amet consectetur adipisicing elit. Officia deleniti animi beatae sapiente?
                Veritatis, nostrum accusamus optio vel rem ullam obcaecati fugit. Nam facere quisquam minus,
                necessitatibus dolore minima animi!Impedit corrupti aliquid incidunt tempora! Provident optio earum
                minus reprehenderit a! Reprehenderit debitis odit totam voluptatem magni? Sequi necessitatibus mollitia
                facilis qui, architecto quo quibusdam reiciendis exercitationem eos, numquam blanditiis.</p>
        </div>

    </div>

    <script type="text/javascript">
        function ShowContent(content) {
            document.getElementById("op1").style.display = 'none';
            document.getElementById("op2").style.display = 'none';
            document.getElementById("op3").style.display = 'none';
            document.getElementById(content).style.display = 'block';
        }
    </script>
</body>

</html>


---------------------------------------------ARCHIVO CSS-------------------------------------------

li {
    display: inline;
}
#info{
    /*No es necesario, solamente para ver el área*/
    border: black solid 2px;
}
#op1{
    display: block; /* Mostrar por defecto */
}
#op2{
    display: none;
}
#op3{
    display: none;
}


