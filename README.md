# Reduccion-de-las-desigualdades
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Reducción de Desigualdades</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }

        .container {
            width: 80%;
            margin: 20px auto;
        }

        .news-title {
            background-color: #0056b3;
            color: white;
            padding: 10px;
            cursor: pointer;
            margin-top: 10px;
            border-radius: 5px;
            font-size: 18px;
            text-align: center;
        }

        .news-content {
            background-color: #ffffff;
            padding: 20px;
            margin-top: 10px;
            border-radius: 5px;
            display: none;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }

        .news-content p {
            margin: 10px 0;
        }

        .news-title:hover {
            background-color: #00408d;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Noticias sobre la Reducción de Desigualdades</h1>

        <!-- Historia de Joseline Morales -->
        <div class="news-item">
            <div class="news-title" onclick="toggleNewsContent(1)">Joseline Morales y la lucha contra el racismo</div>
            <div class="news-content" id="news-content-1">
                <p>Apenas tenía 3 años cuando Joseline Morales vivió por primera vez la violencia racista. Fue la mamá de una amiga de la escuela quien la interrogó sobre sus orígenes lo que la hizo sentirse diferente y ajena a su familia solo por el color de su piel.</p>
                <p>Luego, en la secundaria, cuando denunció al profesor de civismo que la acosaba, éste empezó a decir que no se juntaran con ella porque “las negras olían horrible”.</p>
                <p>“(Dicen que) olemos mal, somos flojos, no somos inteligentes. Te minimizan (…) Por verme piensan que no hablo español o dicen: ‘mira, esta gente ya nos está invadiendo’. O cosas de temas sexuales; la exotización hacia los cuerpos de las mujeres negras también es mucha. Piensan que las mujeres negras vienen a prostituirse o a hacer trabajo sexual (…) Hay mucha gente que no puede creer que yo sea abogada”, cuenta Joseline, quien se identifica como una mujer afromexicana y afrodiaspórica, hija de madre mexicana y padre beliceño.</p>
                <p>Es difícil reconocer el racismo en este país, indica Joseline, porque mucha gente te dice que “en México somos bien llevados” o que “eres muy sensible”. Pero hasta en los insultos hay una connotación racista: “Siempre es un ‘maldita negra, siempre con ese adjetivo”, comenta.</p>
                <p>“A mí me ha fortalecido decir: ‘Sí, soy negra. Con mucho orgullo’. Hago notar mi cabello, mis facciones”, destaca Joseline, quien trabaja activamente en su comunidad, en Iztapalapa, para visibilizar y dignificar a la población afrodescendiente a través de la cultura, la información y la educación, sobre todo ahora que han llegado más personas procedentes de Haití a la Ciudad de México.</p>
                <p>“Se le tiene mucho miedo a la migración, pero, sobre todo, a la migración negra”, destaca.</p>
                <p>Joseline, quien es madre de un joven de 16 años, sueña con un México libre de racismo y discriminación para su hijo y para toda la comunidad afromexicana del país.</p>
            </div>
        </div>

        <!-- Historia de Yolanda de la Viuda -->
        <div class="news-item">
            <div class="news-title" onclick="toggleNewsContent(2)">Yolanda de la Viuda: Discriminación en el campamento de verano</div>
            <div class="news-content" id="news-content-2">
                <p>El campamento de verano (…) ha rechazado a David después de estar ya pagado y todo hecho. Ha tenido inicio hoy. En su reunión de coordinación, hace unos días, decidieron que no tenían voluntarios preparados para atender a David (no lo conocen) basándose en un documento en el que pedían que explicáramos posibles problemas de conducta y sugerencias para afrontarlos, o algo así. Yo hice una descripción de todo lo que se me ocurrió que pudiera suceder en algún momento y cómo lo resolvemos en casa. Que agradecían mi sinceridad pero que las voluntarias eran chicas jóvenes sin experiencia y no se atrevían. Es un campamento para personas con discapacidad. Me ofrecieron devolverme el dinero. David se ha quedado con la maleta preparada, se nos han quedado billetes de autobús sin poder usarse.</p>
            </div>
        </div>

        <!-- Historia de Isabel Ramiro -->
        <div class="news-item">
            <div class="news-title" onclick="toggleNewsContent(3)">Isabel Ramiro: La discriminación hacia su hijo con TEA</div>
            <div class="news-content" id="news-content-3">
                <p>En 2021, escribí para solicitar el ingreso de mi hijo en la escuela de verano. (…) Tras decirme que sí la empresa, y pedirme más dinero porque mi hijo tenía TEA, el día de antes de empezar dicha escuela de verano, recibí un audio para decirme que no le cogían, que no era asumible para la monitora. Yo solamente accedí a pagarle 20 euros más. Ella quería que le pagara exactamente el doble. Y, por supuesto, el dinero en mano. Mi hijo se fue a (…), donde viven mis padres. Allí, a las dos horas, fue echado de una escuela de verano de una asociación de vecinos. Afortunadamente, en la escuela de verano de la piscina del camping, estuvieron con él 3 semanas y sin quejas.</p>
                <p>En 2022, me pongo en contacto con la nueva empresa y me dicen que tengo que llamar a una de las encargadas. Me dice que lo van a intentar. El primer día me dice que no cree que pueda porque la monitora tiene 20 niños más y no puede estar pendiente de mi hijo. Ha buscado a la que, para ella, tiene más sensibilidad y respeto, pero no es posible. El segundo día, la misma encargada viene a comentarme que no es posible, que no es asumible para ellos. Me devuelve el dinero en mano y me pide que me lleve ya a mi hijo, aunque no era la hora de salida.</p>
                <p>Esto es inadmisible y estamos, como familias, vendidos porque nuestros hijos no son asumibles para un Estado o para unas empresas que solo miran por los intereses propios.</p>
            </div>
        </div>

        <!-- Historia de Camila Díaz Córdova -->
        <div class="news-item">
            <div class="news-title" onclick="toggleNewsContent(4)">Camila Díaz Córdova: Violencia y justicia en El Salvador</div>
            <div class="news-content" id="news-content-4">
                <p>Camila Díaz Córdova, una mujer transgénero de 29 años, intentó durante años escapar de la violencia que había marcado su vida en El Salvador. Llegó a Estados Unidos en 2017 con la intención de pedir asilo, pero tras cuatro meses en detención inmigratoria, en noviembre de ese año fue deportada a El Salvador, donde encontraría la muerte.</p>
                <p>El 27 de julio de 2020, un tribunal de El Salvador condenó a tres policías por el asesinato de Díaz. La fiscalía sostuvo que, el 31 de enero de 2019, los agentes la obligaron a subir a la parte trasera de su camioneta, la golpearon y la arrojaron desde el vehículo en movimiento. Falleció días después. El juez determinó que las pruebas, como el registro de GPS del vehículo, el sitio donde se halló el cuerpo de Díaz Córdova y el informe de autopsia establecían la responsabilidad penal de los agentes. Fue la primera vez que se condenó a alguien por el asesinato de una persona transgénero en El Salvador.</p>
                <p>Aunque esta sentencia representó un primer paso absolutamente necesario en El Salvador para que se haga justicia por los hechos de violencia contra las personas trans; sigue habiendo delitos motivados por el odio contra personas lesbianas, gais, bisexuales y transgénero (LGBT) allí y en los países vecinos de Honduras y Guatemala. A su vez, en Estados Unidos, el gobierno de Donald J. Trump se ha abocado activamente a cerrar puertas a los solicitantes de asilo, incluidas personas LGBT procedentes de América Central.</p>
            </div>
        </div>

    </div>

    <script>
        function toggleNewsContent(id) {
            var content = document.getElementById('news-content-' + id);
            if (content.style.display === "none" || content.style.display === "") {
                content.style.display = "block";
            } else {
                content.style.display = "none";
            }
        }
    </script>

</body>
</html>
