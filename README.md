# Proyecto-de-transversalidad1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="Estilos-css.css">
    <title>Proyecto de transversalidad</title>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
</head>
<body>
    <header>
        <div class="header_superior">
            <div class="logo">
                <img src="https://fotos.perfil.com/2022/06/03/0306medio-ambiente-1366664.jpg" alt="">
            </div>
            <div class="search">
                <input type="search" placeholder="¿Que desea buscar?">
            </div>
        </div>
        <div class="container_menu">
            <div class="menu" >
                <nav>
                    <ul>
                        <li><a href="#">Inicio</a></li>
                        <li><a href="#calculo">Calculo</a></li>
                        <li><a href="#fisica">Fisica</a></li>
                        <li><a href="#ecologia">Ecologia</a></li>
                        <li><a href="#ingles">Ingles IV</a></li>
                        <li><a href="Proyectos.html"> Proyectos</a></li>
                        <li><a href="#integrantes">Integrantes</a>
                            <ul> <li><a href="Informacion.html">Informacion</a></ul>
                           </li>
                           <li><a href="#contacto">Contacto</a></li>
                    </ul>
                </nav>
            </div>
        </div>
    </header>
<main>
   
    <section id="calculo">
        <h2 >Calculo</h2>
        <h2>Producción de Energías Renovables en México 2023</h2>
        <canvas id="renewableEnergyChart" width="400" height="400"></canvas>
        <script>
            var ctx = document.getElementById('renewableEnergyChart').getContext('2d');
            var renewableEnergyChart = new Chart(ctx, {
                type: 'bar',
                data: {
                    labels: ['Solar', 'Eólica', 'Hidroeléctrica', 'Geotérmica', 'Biomasa'],
                    datasets: [{
                        label: 'Producción (GWh)',
                        data: [25000, 18000, 12000, 4000, 1000],
                        backgroundColor: [
                            'rgba(250, 99, 132, 0.2)',
                            'rgba(54, 162, 235, 0.2)',
                            'rgba(255, 206, 86, 0.2)',
                            'rgba(75, 192, 192, 0.2)',
                            'rgba(153, 102, 255, 0.2)'
                        ],
                        borderColor: [
                            'rgba(255, 99, 132, 1)',
                            'rgba(54, 162, 235, 1)',
                            'rgba(255, 206, 86, 1)',
                            'rgba(75, 192, 192, 1)',
                            'rgba(153, 102, 255, 1)'
                        ],
                        borderWidth: 1
                    }]
                },
                options: {
                    scales: {
                        y: {
                            beginAtZero: true,
                            title: {
                                display: true,
                                text: 'Producción (GWh)'
                            }
                        }
                    },
                    plugins: {
                        title: {
                            display: true,
                            text: 'Producción de Energías Renovables en México 2023'
                        }
                    }
                }
            });
        </script>
    </section>
    <section>
        <h2 id="fisica">Fisica</h2>
        <p style="color: red;">TIPOS DE ENERGIAS</p>
       <div id="EOLICA"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSfsOxgdMZR6cB0_r6xu582aKywhm1h15XMsw&s" align="right" hspace="20" vspace="2px" >
       <p align="left"><b> ENERGIA SOLAR:</b>La energía solar es una energía renovable, obtenida a partir del aprovechamiento de la radiación electromagnética procedente del Sol.La radiación solar que alcanza la Tierra ha sido aprovechada por el ser humano desde la antigüedad, mediante diferentes tecnologías que han ido evolucionando.Las diferentes tecnologías solares se pueden clasificar en pasivas o activas según cómo capturan, convierten y distribuyen la energía solar. Las tecnologías activas incluyen el uso de paneles fotovoltaicos y colectores solares térmicos para recolectar la energía. </p>
    </div>
    <div><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRL0ZoE7MAIXRU9FQbM-m3AcD9VAyAvNjCIvQ&s" align="left" hspace="10px" vspace="10px"  >
        <p align="right"> <b>ENERGIA HIDRAULICA:</b> Energía hidráulica, energía hídrica o hidroenergía es aquella que se obtiene a partir del aprovechamiento de las energías cinéticas y potenciales de la corriente del agua,saltos de agua o mareas. Se puede transformar a diferentes escalas. Generalmente se consideraba como un tipo de energía renovable puesto que no emite productos contaminantes. Otros consideran que produce un gran impacto ambiental debido a la construcción de las presas, que inundan grandes superficies de terreno y modifican el caudal del río y la calidad del agua.1​2​ </p>
    </div>
               <div class="IMAGENES" id="EOLICA">
                <img src="data:image/jpeg;base64,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" align="right" hspace="10px" vspace="10px">
           <P>  <b>ENERGIA EOLICA: </b>La energía eólica es la energía que se obtiene a partir del viento, es decir, es el aprovechamiento de la energía cinética de las masas de aire.
             El término «eólico» proviene del latín aeolicus, dios de los vientos en la mitología griega.En la actualidad, la energía eólica se utiliza principalmente para producir electricidad, lo que se consigue mediante aerogeneradores conectados a las grandes redes de distribución de energía eléctrica, entre otras. Los parques eólicos construidos en tierra representan una fuente de energía cada vez más barata y competitiva.
            </P>
        </div>
       
             <div ><img src="data:image/jpeg;base64,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" align="left" hspace="13px" >
                <P align="right" class="geotérmica"> <b> ENERGIA GEOTERMICA:</b>  
                    La energía geotérmica es una energía renovable que se obtiene mediante el aprovechamiento del calor del interior de la Tierra
                     que se transmite a través de los cuerpos de roca o piedras calientes o conducción y convección, donde se suscitan procesos de interacción de agua subterránea y rocas, dando origen a los sistemas geotérmicos.. El interior de la Tierra está caliente y la temperatura aumenta con la profundidad. Las capas profundas están a temperaturas elevadas y, a menudo, a esa profundidad hay Capa freática|capas freáticas en las que se calienta el agua: al ascender, el agua caliente o el vapor producen manifestaciones en la superficie, como los El Tatio|géiseres o las Aguas termales|fuentes termales, utilizadas para baños desde la antigüedad.</P>
            </div>
            <div class="IMAGENES" id="EOLICA"><img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAkGBxMTEhUTEhMVFRUVFRUVFRUWFRUVFRUVFRUWFhUVFRUYHSggGBolGxUXITEhJSkrLi4uFx8zODMtNygtLisBCgoKDg0OGhAQGi0lHx8tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLSstLf/AABEIAKMBNgMBIgACEQEDEQH/xAAcAAABBQEBAQAAAAAAAAAAAAAEAAIDBQYBBwj/xABAEAABAwIDBQUGAwgABgMAAAABAAIRAyEEMUEFElFhcQaBkbHBEyIyodHwFELhFSNSYnKSsvE0Q4Kis8IWM1P/xAAaAQADAQEBAQAAAAAAAAAAAAABAgMABAUG/8QAJBEAAgICAgMBAQADAQAAAAAAAAECEQMSITETQVEEYSJxkTL/2gAMAwEAAhEDEQA/AN0QmEKUphXqo8yTRGWqM01LC5CaxOyIBOcE4NTnNSyY8AR6ieES5iTKaKdDNcgTlH3I51EJopjgm2QGmAuCYeiJqshDuVFyTfBGXKJzU9z1EXp0ibkhjmqSk06JjinUnws+gJ8h+CrS6CralSi6qcHSlwcFo/ZwFy5HTOqHXJASoK91KQhnuSozK/Gssqj8wnVX1dshVWJoZHmuiDJSQFiAWuVg3Ft3PeHBMxTQuOoBwAGmadtNKwcroLo44RZHBsiVS4TCEOvlK0QFlKdLoeNtclHiKRLisntSm8OuFuq4VVtCgDorYslMjlx7qjLYLZxfnkrqlsgAKy2ZhwNFYNokpsmZ2dOD8kIxv2UL8DbJNbg+ULQGhxUTmt0SLKyssKK+lhI0U7MNyhGjJRPfCGzYdUjjaYXVE7EBC4jHgIqLZOWWMUE1KkISviVW1toc0I7FErpjhZ5+X9sekWTqwXFUuqykq+M43+pnq5auFqKNNcNNeLse34mCbq4WoksTSxHYHjoH3Ei1T7i4GpWx1GgNxvdQVKsGyNxFNVtdpCMWKyTflOcUH7WFNTrSE9AsbXbKEfSAzRrgVG+jKpF0RkrAXNTHUk9w5KJzTorIi2Ru6KJ7lNuuKlw2ELjlbVFtLsCTfRfbIogMBVi99kHgm7jQ0ZIneELgk7dnelSInuVfWN0TiChwE8RWMqZIOs5EVyg6zlWIpFVp8pROHpRpBUYeVZ7Pw5+JyMnSCojGFTPKc9gBsmVW2UzAtZ6FqNUz1wtlUXBlG+iXAgQp6lTQKCjDcypA8DIJWuTsi6jRxzOKGqODV3EYhVOJq81SEGyOTKohdXGoDEYxQOPNQuLdSumMEjz8n6JM5UxTig6zyc0S6s0KCs8HIQrxX8PNzTbXZAknQuinxVDmGJJ9gksY9phcLVLCaQvmz7Ai3EwsUjlG4oiuSGFije1PcUwlMLuiFxQlZso1wULxCCdAZVVqChFEhHk3TnBVUibiV7Q5OdKne6E19WyaxKBac6hTjDTf5LrDKn9qRoE2zNrH2COwh/0rDBsDREKEPPBOa4yhJtoeMEuUHFOpNTmU/dSpmCoFAeuxQVGwp6rrqCu9OibA65QNQyia70M0jVXiTsmwLAXXVl7fRVgBFwERs5riZdaPmhLnkeywLVC9T1Ch3OSIDBKzEA/GAaExbkrGrUCpsXWhXhyTc3HobiNt7pgNHmhnbacUPUfJ+HvUDqYzuuuOOHw4Mn6ct8S4CH40nVQVKx4rkhNtwVEkjnllk+2Rl7jxSFFxUzSdAugOTWT1vu2Klgzqk9jRqO5dcwnMlNFBLf1lNVVRj/0jLuCjKLGHS9im2RN4psE3UkZ7FJbdA8Ej2RyjKlKYV84mfVOyItUZYpymFMmTaXshLUxwUrlE4J0Tboic1D1mIktTTSKzQYyb9FY8gJtGrNkXUwoOaFfhouFgguIdBUO/ZB7e2qGO3QxziACdBcTmqF+3njJg/u/RUjOIjhI0rHGbI2k+c1ih2kcM6Y/uP0VrsztMx7msc1zS4gDUSdOPyTbJi00jTveoSCck3f5J1GtByTVQFl2dNl1gvhAKixVQMkkgDiTA8U2g+QqftVT3qbOT/MH6LmZ0DMTt2i3889A4/OFW4jtPR/n/ALR6n7lUeJoqurs5IqbA4Iv6naKiTm4dW/RG4TGU6gljg4DhmDzGYWEqU1pOxuH92q7i5o8AT/7K8JX2QlH4aelUkoym/ggAIRAxTGj3ntHVwBRlwMk2GOqIWtVQOJ23RH/MagKm2qRt7RvjHmtGmLK0F4jEKuq3UjH7wkGRoRddNMrpgkjnm2+AT2aQoon2RXQwquxBY/4DGgm/h0YGLpYtuN4U/QEKacAiHU0wsW2sHjaGBKAu7hXfZFawqL+HJTTUUoopww/JbZB8c2D76SL/AAy4tug+CZ6qSmkKbdKaQV4NnsuJCQmEKYtTS1MmTlEHcFG4IhzFG5iaybRCSmucpCxcLAs2ikFJ/AdwUZpKdzU0hMpGcF7Mp2ooDe6tHmR6LHYmldbntQPeH9Pq5Y7FsSrsz6Kl7Ub2cp72Koj+Zx/tY4oaqFYdkv8Ai6XP2n/jcqol2ehCiu+wCkNMpvsSm2/plD+FRidveykNZPV0fIBVo2+7EO9mWNaLukEk2tr1S25TgnqVT7GH74/0O8woW3ZWqDMYxU9dqvcYFUYlqMQSZVvatT2PpzSff/mH/FqzLlqOxdT93UA0eD4tH0XREj2y0xtOGGDw+Zj1WaxVMharF/CfvVZzaGqnl/8ASKxqigqhQOYiqzVDC0RZGq2HDaDBGhPi4n1RhfyUeyaQ9jTz+EIv2Q4FdkWkiejYLfkluniivZ/ypexOgR3MsILudU4MCJ/Du6JfhzqVtxvD/CARwXC8cApjhgufhwhsg6S+EJrJhrHgihRC6KY4I7IHjl9A99y6C7gjNzkuwVtxlhf0C3HJIsjmEltw+E9QKaVJK4V4lnYQOlMupymFazP/AEQkKNwU7lGU2wmjZA5RuCnITSAj5EMsE36By1N3FNUe0TJyE9yrTtplgGneIJg5ACJJPC63lKL8kvZSdpv/ALI4NaPM+qymKatDtLFiq5zwIvHhbyCo8UFeH048nDaKeu26I7NO3cVQP8+7/c0t9U2s1D0au45r/wCBzXf2uB9FRk49nrxprgaE+xvIg5LoaOK59z0vD8Ri9v8AxO6lVew2e+88AB4kn0R22HSSmbDpxTceLj4C3nKZdHE+x+LHqqnEhXGKVTiAqRJyZWVQrzsWJfVaNWtd/aSD/kFU1Wo/slifZ4pnBwcw94kf9wCrdLgSCTmkzWY/DltNziMgPMLJ4+otl2jxP7ktB+JwGUZX9FisaFBycnydWXHHG6iVVV11E1SELm6qxOWRvezIa7C0ydA4H/pe4eisDujh4LI7A2kW0iwflcTGdnD6+atmbSGsyTbwP0KXZX2ejjf+C4LU1AmF6ExONaGgjXJVdbbcEACYmel7/fBNaQzovt8cCVG48ln6falmrDnoPvij8PtWm/IjldFSTFbX0OLkxz1xtWcoKaXclRE2kJ1QqM1CnlxTd4phGhu8UwzxTy5MLk1iNIYWnj5pKKtioMDMZjqkjsJpE9Lx22aVGBVqsYSJAcQCQNYQuG7TYao4NZiKLnOMNaKjd4ngBqvPNudo6eK3WgODx7pdHuGmZmL5yc1S9n3No4plSpO5SqP3nNa527utO6ZbMiY7l5McFo7ZZop0e4GumGuqX9q0jBFQEGIz1yVZtDbjw4+y9i5gAO855Bvnbgp6MqpYzUOxCjdiVgndosSZIqYQAGLl3E6zy+SGHbGqHQ6phSJglorOgamwi3VP4hfLFPg9CdiVWbQ2uyk9rnOG6GPkB03Lqce6O/5rM4vtBNMA1Kbi+27T/pDrOgGLjxWC2zVFQ2eY3iN20hsyLzfrKKxpBed+j0bHdraUyJMy3xgTPC8rIVe0lUOJZEm0boPu+9YnPMk96zTa5Z+afKIhQVcacp++5akTllkzY7Cx++SHGImDYTOc+A8SrDEDgvP8Jjd10k/PwVidqOaTDok6RGcq0ZUjllG2X1cKuq6oE7ZdGYJm97/6UDtrb3XXx+aLmhVBnrvZrGCphqTibhu6erPdPlPerHEVgGOvpHivK+zPaM02mnvR74cJyuId5DxWxobdp1GkB1wekg/CVPg6/M9aKzalS5VlhKW7Ta3lfqbnzVaWh1QBxgT5XhHYvaLG23mz/UM7AeY8Ub9HNQzEqsrhB4nbzSTD2xmLi2ds+UqgxW2S/wDOItYEcPnZMppAeNsvajhxHyUDam64Pbm0hw6tM+izdXFC8Pta/LOV2jj4/N8+KPmA8Ps9S25jGu9nGRG/3OyWfxb1kHbUdcb87pibxyzU9Ha7rAkHiL2vF/PokU0UyJydls5Q18S0A3uqvF7UzAIzNx6KudiZN0ZZfSFji5tmp2Rioeb2cCOhExnyJUmJ2xDhAlw1tfeuT4E3/mWXpYjdjrNjpMEGMtV2tiLk5983zMRZT2LptKjS4na28WkkjSBoB9+aEfjRDgc4kHlnfxBVH+IBF85sdF1jz70yHBotlLY3rf8ASLdOaO5uWHNx4EAalvT7t80bSxQiZ8idTfh/tZyiYI4TOY4XRQxJg3EAn8wi8CAJv+qKkLyX9DbD6ZEOMTBvIvxCvn7ZIZvgTyn74hee+14yfTvU5xj4iSIHja3yVI5qA0zdDbR3SS2COesEjyVbhNvvJ3TEnXTIR81nq+1C4RyE3PG32FXDGwmebngVJ+zaN2rUO8ZtJj+EiwkHh9UNvuaRvGSDOtnQIBGp/RVWBxnumTYZDnon0RL5LjYzIzNx9YTb3QvJom1t0++4ngCcuvNJVGJxDGm5vrrwt8klR5UiaTZR0Nulp90XuOMXH0Sodon094NtvZk38FcHD4ciQ1ngAo34Oh/AwnrwXLu0V0sqRtt0gzfiCRl/pS0ttv0c4Tbj3c0e7DYYEEUwTMySeHX5dFJ+Fw5/JpoTFuX3kg5X2FQror3Y0m7nGOgCHqbROQMK1q4WhInLgJ7vNQ1BQkiNY52CRysfQqfxIP5ndxyRLn7o4zE/RF08Ph3EAAg8YF7HyuiH4WjGZI6C/P0WbCombqViU38RotB+ApdLTMCdDmus2ZRJyHE2AiPspQ6mb9payY+oQc1o3bOob/cRbLL9U0YCkYsBlcgGwi5lY2pnzWi096hbVN1oK2EY4+64TlG6MuExwBU79nUgBLmiDlug5wczfMLG1M5TxVx6omltJ7fhcRlkcyFfHDsAB3ryXfCMgZ4aQgqrWbxvMiwPl5LWwOIqW2a0XdvSIgmdZ8VDWx7znnbhoAPQeAVvgKQd+RsAWmO4i11Mdj0i4l0EcAban1CG4sIS9mVrYs2nRDvxNu5bKtgMOIHs2yuNwVC5FNlrXjXkVrKaGNGJPkPP6pe3Jkha1mzaJdJYBxEDTIZRr9wpqWAohp90G/8ACLDl4DwQs2pihWN7xxT2v1nXj1WwOBo//mDw93jH0TXYei0waYvFt0Ec/JYOplWycl2o6O6VqG06Pw7oB/pHcuMw1B0+63LMjUi5zzW5NRlmvkrja2Q+S0n4SgCCN33RGVxaAfNTYfC0nOsG35cLQPBZmozdOlVJ91hM5R92R9HYVc5kNmAdTBPLqVuaGCYGiBkpX0govIyqxoxFHs68fE+eEDiNbp3/AMctJcZ7uZWrc26iI9FtmbVfDM/sVw/MeHck7YhvDiM/NaGrbvv5JoNp5T5/RNbFaXwzLtkvac/Ox1UTtmvOgWnqu7v1CgFTMfeSdWI0ihp4dwsBz6LlNzhf78OCuN6/3yUFemIkakWjL7lPbEpFVUqVDeF1WtPDkWAnnkfpCS1s1IPqYeo2A5gbJ91wgg63GlgT4LmAwdWtV9lTLS5xe1tgB7gLib8gvSO0PZF1WPYmmAGbsOke9eHQGm8ECc7Ks7P9hcRQxFOs6pThjiSG70kEEG8DimjkjQ7wyT/gG/sJW3R+8pudIsBAjqq6t2cqUnOFTMNBG4x7mkni8N3V60aSaaSn5C3ij9PCcfvMMmCAY3SwgkXEgxlZAPxIJ92kSSSddQve8XgW1GlrwCCqWt2RpFwcC4cRNj9E2yE8Xxnj9N75BbTAk3OdxrCfWxu7ILRM3A8CvaDsSkGFgY0AgiR8QJ1B4yvOe2PZltIgs33AhxJMaFoOQE3JujaYHjkuTLftVvAZReeQ4JM2zT1A8Dke5A4ihGTcoGXf42Qppj9PFAnbLf8AatMus3jkSBMaCEm7QZEwMwDPPSe4+BVVhmmQOYHDXyU+KwkOy1Ot/KyNA2CK+OaDbd6zP2YlTP2hTIEtbe4MjT3ctLz4Kpq0L+qFZhzKDQdjU4eKggNFt4SCMp5dfJM/CtD/AHhkSJnUWN13YFD2bQ7icssyNRfgralsw1W2Emb24nXuCNBptHa2AnddTGYu2c8oA8FWuwtUOv4X0z++a0bqJptDZuPkUH2iwjjFWnqAbaTJP0Qlj9gjlfTMviqNTdiL9Te4J+Vk9jHySQYvaTnpaeKJFeoYB5knUDn3Shn7TcCRGnzBzS6D7oKxDzvWD/hOuvNR1KrwBG9MCesmcuSEbtRwdJE279foE9u2bEEGx8QhqHdHamJqQPi+eYyBtxVfiMQ/fMT8WWkWVxUxgbmIsDkYnhdDVsY3hlwAvCKQJSK/29SWxP2dPkhxUqSPi7pylWTdpNz3cjnbLTons2mwG7dLdQERSvwbnHfmcxnPB3BXmyKgYD7u9axvqJPmg6GNa50Bukm3TO+UlT4TacO3QBExlp9ylkuB4tFxU26RaNRx4pw276nyU7KTHgGAmPwDOCgXsGbt0E3jM+kfNRs2s0m+gnTu8k47NZP6of8AZzBxumQjolxO1W25c+X34oantlu4G6w4eYC5iNmMtz5IUbIbuz1OXh5p0K6CXbWa4+E91vqh27Tkk8iTwvuj6qI7KAOef+1CNm3InThll+qdWI6Cae0Lg8geORE+qPGJBDOrJ4kk+94C6pmYE+LQPG31RgwvwGbgtIvbUHpF0eReC0p4lkiTbd+ZP+0lWDAEwJOU5n6pLG4PplcICYXpjqiGprbJCUwlROqphqoqIWmuSQlMJUZqJjqiPjQnmlEkMKh7S7P32y0SY3Q0TqQTI7vNWxemGoj4kOv1yPPH9kWvPvAtDT5iXdYus1ieylUn92N6DpHWc8oXsVUB08YIlUtTZBEOaQTulrgNQTpzu5FQYHmjLtHl2H2JUY8hwjMKQ7HJJLjGfXP6LZbSwns3EOiSAbcwAfJUWKqqkUQk/hTnZTQLlQnAtE7syfPRG1qt07Y438RRboarJ6Ahx+QTaoRN2bsdlqYDBluhomP4QRPzV3hMFTY0tb+aSbcVx1QJu/zSaHorIl1Rjtq5lM2c4PpQc2kj1Hmnbds93UoDY1a729D5g+ixwvsbidmAFxb3Dhms/jdlubJF5+z5LV4p6rK70VFMDk0Zarhjw+8kTsjZTqtVjA3N2XEASfkFZVaiseyj4r738LHHvMN8iUyxWZZOVfRVbU2HUAc4tMB0XB+80JT2Q602/Vek7Rxm9Se06jyIPosniyUjx6vkrklFv/Ay2KwBGSBdSWjeboSrRBmyDx+0JHJ6YFgaFnO6Ad6hqtM24zOULT7JwTfZZfE4k8QGmAO/0QeM2W6ZGRuLX0nzHgUjidCTqwTB497Bc2b8+SsaO3AbHTiO5CYnZhaBMXM93PkhvwrpygAR3wT5ykeNB2aLdu0mk2Pgn/iQdVmKeFOfMeceqsGUXQBeZM9cvkgsQdy1dWBGf3AXPaCInIH1VLUpuGR6X6+KusNsolgcTBvztrZMsUn0K5IjfUH3yUG+JP3y9FcM2PvBpBEcumU9Ux2xoiRMCDztn4+isvzyJuaKw0SLjl10jyKTqDojWcjy/wBK+bgXAAgNJPxTIBEQBadYUWJwpDp3d5oiwzIzdnrmneBrkXdFXXfBEWG6Nb3ASRGIpOn4SZv8QbAyAAAKSk4j2e8kphKSSKIsa4pjkklhvRG5RkpJJ0SZGSmOKSSIENJTSUkkUM+jLdqj+8H9A83LJYkpJJfYfRW1ijOy/wDxVH+o/wCDkkkwi7PSymSkknRQym3j7zuqqNlH947+g+YXElz/AELDsUbKsrlJJPEWQBUOauOynxVejPNySStDsi+y7xHwnoVR4xJJDP2hsXTKmqoCkklRpFpgnkUhHB3+X6ohrsjrverkkkDpj0TbSpjdaevqqWobu6P6WBAskktMKYEw3d1jwmPJGUGguE6kE/NJJTiZh2x8Mx7hvNBzPzKvjSEgRqkkunGuBGTUhAgZJ5KSSsIcaU8sHBJJBlI9FfhKYNGmSJO43ySSSSx6Qr7P/9k=" align="right" hspace="10px" vspace="10px">
                <p> <b> ENERGIA NUCLEAR: </b>                
                    La energía nuclear es la que se libera espontánea o artificialmente en las reacciones nucleares. Sin embargo, este término engloba otro significado que es el aprovechamiento de dicha energía para otros fines,
                    tales como la obtención de energía eléctrica, térmica y mecánica a partir de reacciones atómicas.​ De esta manera, es común referirse a la energía nuclear no solo como el resultado de una reacción, sino como un concepto más amplio que incluye los conocimientos y técnicas que permiten la utilización de esta energía por parte del ser humano.  </p>
            </div>
        <div><img src="https://www.abc.com.py/resizer/s4eleISy0RSsxs0YLtYe_VW5yxE=/fit-in/1200x1080/smart/filters:format(webp)/cloudfront-us-east-1.images.arcpublishing.com/abccolor/4MH5CJS6QBEONG6VNWQ3IET3ZE.jpg" align="left" hspace="10px" vspace="10px">
            <P align="right"><b>ENERGIA CINETICA: </b>
                En física, la energía cinética es aquella que un cuerpo posee debido a su movimiento relativo.
                 Se define como el trabajo necesario para acelerar un cuerpo de una masa determinada desde el reposo hasta la velocidad indicada. Una vez conseguida esta energía, durante la aceleración, el cuerpo mantiene su energía cinética salvo que cambie su velocidad</P>    
        </div>
       </section>
   
    <section>
        <h2 id="ecologia">Ecologia</h2>
        <p >Las ciudades crecen en todo el mundo a gran velocidad. Desde 2007, más de la mitad de la población mundial vive en ciudades y se prevé que en un futuro próximo 70 de cada 100 personas vivirán en núcleos urbanos. Las áreas metropolitanas tienen el potencial de marcar una nueva era de desarrollo, pero el reto de estas ciudades del futuro es hacerlo de forma sustentable, promoviendo el crecimiento económico inclusivo y sostenible, el empleo y el trabajo decente para todos, manteniendo la calidad ambiental y preservando el equilibrio social, en línea con los Objetivos de Desarrollo Sostenible (ODS) de la Organización de las Naciones Unidas (ONU).  En 2022, Arcadis, una de las principales firmas de ecodiseño y consultoría de patrimonio natural y edificado del mundo, realizó un estudio para evaluar cuáles son las ciudades más sostenibles en el mundo. Las ciudades incluidas en este informe, son aquellas que reinvierten los beneficios obtenidos en servicios y políticas sociales, en acciones medioambientales para mejorar la calidad de vida de sus habitantes
        </p>
        <div>
            <table>
                <tr>
                     <th >CIUDADES MÁS SUSTENTABLES DEL MUNDO </th>
                </tr>
                <tr><td>Oslo,Noruega </td></tr>
                <tr><td>Estocolmo, Suecia</td></tr>
                <tr><td>Tokio,Japón</td></tr>
                <tr><td>Copenhague,Dinamarca</td></tr>
                <tr><td> Berlín,Alemania</td></tr>
                <tr><td>Londres,Reino Unido</td></tr>
                <tr><td>Seattle,Estados Unidos</td></tr>
                <tr><td>París,Francia</td></tr>
                <tr><td>San Francisco,Estados Unidos</td></tr>
                <tr><td>Amsterdam, Países Bajos</td></tr>      
            </table><br>
           <p>En la actualidad, se estima que alrededor de la mitad de la población mundial reside en ciudades en todo el planeta. A lo largo de décadas, la División de Población del Departamento de Asuntos Económicos y Sociales de las Naciones Unidas, a través de ONU-Hábitat, ha estado publicando resultados y proyecciones actualizadas sobre las principales concentraciones urbanas y rurales en todos los países del mundo. </p>
            <table class="cuatro">
                <tr>
                     <th >CIUDADES MÁS POBLADOS DEL MUNDO</th>
                </tr>
                <tr><td>Tokio, en Japón.</td></tr>
                <tr><td>Nueva Delhi, en la India</td></tr>
                <tr><td>Shanghái, en China.</td></tr>
                <tr><td>Mumbai, en la India.</td></tr>
                <tr><td>Sao Paulo, en Brasil.</td></tr>
                <tr><td>Pekín, en China.</td></tr>
                <tr><td>Ciudad de México, en México.</td></tr>
                <tr><td>Osaka, en Japón.</td></tr>
                <tr><td>El Cairo, en Egipto. </td></tr>      
                <tr><td>Nueva York, en Estados Unidos.</td></tr>      
            </table>
        </div>
    </section>
    <section>
        <h2 id="ingles">Ingles IV</h2>
        <h3>description of a product</h3>
        <div>
            Coca-Cola (also known as Coca in many Spanish-speaking countries; in English also known as Coke) is a sugary carbonated beverage sold globally in stores, restaurants, and vending machines in more than two hundred countries or territories. It is the main product of The Coca-Cola Company, of American origin. Initially, when it was invented by the pharmacist John Stith Pemberton, it was conceived as a patented medicinal drink, although it was later acquired by the businessman Asa Griggs Candler, who made the drink one of the most consumed of the 20th century, and of the . xxi.
            
            The company produces a concentrate that it then sells to several licensed bottling companies, which mix the concentrate with filtered water and sweeteners and then sell and distribute the drink in aluminum cans and plastic or glass bottles in stores.
        </div>
    </section>
    <section>
        <h2 id="integrantes">Integrantes</h2>
            <div class="slider-container">
                <div class="slider">
                   <a href="Informacion.html"><img src="https://chat.google.com/u/0/api/get_attachment_url?url_type=FIFE_URL&content_type=image%2Fjpeg&attachment_token=AOo0EEWYYoGBXZjN%2BPTeKpEdmCycjGyGLCVgsj4BoxB%2B4EPyV6WhC5C6xHyKQx6pf7W6OHKpjjlXIEXgivWU3xUFPWub3%2BWNnYD9gFZ%2FIrRdCYm2L4TQ%2BGBbarEUAVvRb666iZsYtXEo9j4eV8R4LtEho2ikilleIGp91dm10jn8hTs8l%2BEdJ7IazluunXKe%2BMmwi6ecQ9pnhWYacxWdVO2NXA9SUUFZn8ZUpukLjIyTwDBWqvOXaYPVaqZcH0ej8b2B0%2F7HO3DAZDq78k8OWFaoBMRCqu0PgAl21MQPnwO2BO1a1cEPpss1pvFNQNfKXmkzby9lkDLkfiJ9xIS9%2BnZfYNeSb1xk4g55DLg59d7OD5cylq1ylfqNj148I1wK8XEVUhvGz%2B9OCHV9Zu9GKd%2BpGRjR2ZuumvUf%2F%2FerGsXY5LlPFZFmcxjP6fI%2B%2BgkDFCzKw%2B9e5wBS4eLoaKX2RKXYjbkziRpU%2BH4A%2BOGADANYDmGTgIEx3wakvySYkJ%2FkEgBsbV4g%2FkcMpGqKPRn%2FAehs8toPHTtd4WTSXTCJEpb62sHDjs7GXR8YKMRF5MXd%2F8qOWRPM1nQiOyY%3D&sz=w512" alt="image1"></a>
                    <img src="https://chat.google.com/u/0/api/get_attachment_url?url_type=FIFE_URL&content_type=image%2Fpng&attachment_token=AOo0EEW0HPgEz4ybeq4krnregSTfgojXz5t37Q%2FI1H%2Bi4HhsZjLj56cXexMJYOWrcOUFlGnb91n86vHjlZwG8uCzGabyAEjZb020TPYXcUd6TuLA%2FWkzwc4m0YBqRB1qKCbgpU0pvAW8G57mvQs2tdZL6143PNT%2FTvoELrCRWHmXeeee3YvKSujPxU228o7Gjhv4LxASjj3%2B5Ax%2FJ4Nomv%2Bgjkaj4WsPaizg0kEBNQ0P1Er%2FvchQANTDU4ttDxoKyJx2iMme9Rv2Tjk7WI6Z5xreTI5ZaW%2F5ON5Yp%2F%2B0sY7UhlujGM8wlsaW01lPS0HvEJnB33s9DoSjL3aCAqmzaDzveTXRkhkvcLUqblOJB7yk7aMD6viu8xuo%2BF%2Be%2Bej5Y%2BCHJ99dkAbFRozOwRFEiWYXNsdjtP%2F9hPopkyXwGd4vIclpWKQQwQBZyDPv3jc%2Fr8FlTGrVbdJrCQbdCgd3VH7jPnMzfWOSuqYE3%2BHEuNgCMmMiXqqV8dd0icdo9YYFXYpPPxbmIyMsT87WSr4ODMmpy01mCsKh70U5fI8sEIopxyqkdNUrHq69wtTAjO8UvC7W6LzLBg%3D%3D&sz=w512" alt="image2">
                    <img src="https://chat.google.com/u/0/api/get_attachment_url?url_type=FIFE_URL&content_type=image%2Fjpeg&attachment_token=AOo0EEWeeCk1catln78a2Ykw%2BIKH8hG%2FyOu5hq4mb%2BsDTEs2OGJNYONZlawgXwB1ouDiS%2F5ph9z2%2BiEDCO%2BWLywM4zLY%2BoeV4Q1na1TJ3yUcPhsXcZurwGtENts55B0r0%2FIsULav9Z6K3iZXSQQTdR2TVhb%2FSZekKYLz4VdZgLbwKKfwhmmmj1JauAP%2FNsL7GzPIz05gkf%2FU4fylkdj6c7JGraUgPbLJq47tEjqsfWQMo3vpu5Zzt55aP5Aqbx8ogpUdjihA%2FILCW%2BaMI5GqbJVfNnxVHM2ykz9uhXOBXPwlZ%2BxK%2BdwyZIphatsocnrmA56Pn6wZoK2ZpqHpB2Q0aRmufBpVgPoWW4ltgK0VizkaUaYPVEuRNE3KHdx3h6YOft%2BHjgP2bsRqOaoUQEiCYcNAdl46BUBvGVVgL62c03rG2K2f%2Bs2thSOwfuMOeitFJwshtGfZQga%2FdKuWdLqZ%2BLmNKRQIVbNfslpCc2XXnCJtHaJWmf%2Bv5xyQLh25kNyz71czQHHmXHjX6FR%2BGhTGD4h7%2BVbVN18OliVzs%2Bmj5EjO8kaWWmNsgxDzw7ifhkUVTASjTOFPvGwhMUDuXQFiuC0E%2F90%3D&sz=w512" alt="image3">
                    <img src="https://chat.google.com/u/0/api/get_attachment_url?url_type=FIFE_URL&content_type=image%2Fpng&attachment_token=AOo0EEVdf9lEdlQjAZ6KmElUCTpVE89kaOHSmfXIYLnOeeRIfE77fBilVA3R57njXpAFYhOIpX4rUyqK18%2FTD1qhOozzP%2FuEck%2Fp%2FgHI1ilmNfkVjTr%2BJIcGfiNXS%2B%2F9ptPT2xmIFkL1t68h%2Fi8yvqif1GtSyu756o0lnmMl9PWRPxqcSZGbx4rkCUNmJABe3h9gfeYdPG1lUoIKDJzmahK23RebVwZt%2FmnfPrQNeICSN4S78QXYCK0YPzmp2qn9FWrh8Bn4azgosC0S1tTK8Qfr8dMtkwpSGGO5UsZ0%2FMEdIL%2BDYMjCebWhMq5qf4aBy1B5bgKChNqdlGjCfdVu880hcLz5aes6eXpX8R3Bf4sPem%2FP%2BfvlFunqh3U%2BVmB8G3IXOO7%2FGh8byEC%2B6fkRVWCKiGQjLEEdYRN0PRn5w%2FzC13mB%2FyTB%2BcV%2BpQFnCg6searf53UKc%2BzY4EW2yzM%2BrgBszHD9PUatSStvZy%2Bx6DorMScgKtpAvSJMdloDdQOljggYXJ51gVr9M9LSBQBCZlQ9OAJ65qRM5CZ5%2FgQ6tBpUU%2BKDnhvNBv%2FpYvsKxbGXIWdZ%2BlMirw%3D%3D&sz=w512" alt="imagen4">
                </div>
            </div>
            <script>
                const slider = document.querySelector('.slider');
                const slides = document.querySelectorAll('.slider img');
               
                let currentIndex = 1;
                const slideWidth = slides[1].clientWidth;
               
                function nextSlide() {
                if (currentIndex >= slides.length - 1) {
                currentIndex = 1;
                } else {
                currentIndex++;
                }
                updateSlide();
                }
               
                function updateSlide() {
                slider.style.transform = `translateX(${-currentIndex * slideWidth}px)`;
                }
                setInterval(nextSlide,)
            </script>
    </section>
        <section id="contacto">
        <form action="" id="form" class="form_contact" onsubmit=" return validaciondeformulario()">
            <h2>Envia un mensaje</h2>
            <div class="user_info">
                <label for="name">Nombre *</label>
                <input type="text" id="name" name="name">

                <label for="phone">Telefono </label>
                <input type="text" id="phone" >

                <label for="email">Correo Electronico *</label>
                <input type="email" id="email" >

                <label for="mensaje">Mensaje</label>
                <textarea  id="mensaje" name="mensaje"></textarea>

               <button type="submit">Envaiar mensaje</button>
            </div>
        </form>
        <a href="mailto:perez.morales.edwin.22@cetis156.edu.mx" id="TRUCAZO">mail</a>
        <script>
            function validaciondeformulario() {
                var name = document.getElementById("name").value;
                var email= document.getElementById("email").value;
                if (name == "") {
                alert("Por favor ingrese su nombre")
                    return false;
                }
                if (email == "") {
                    alert("Por favor INGRESE SU CORREO");
                    return false;
                } else {
             alert("Gracias por enviarnos su mensaje")
                    return false;
                }
            }
        </script>
        <script>
           const  $form =  document.querySelector('#form')
           const  $buttonMailto=  document.querySelector('#TRUCAZO')

                $form.addEventListener('submit', handlSubmit )

            function handlSubmit(event){
                event.preventDefault()
             const form =   new FormData(this)
             console.log(form.get('name'))
             $buttonMailto.setAttribute('href',`mailto:perez.morales.edwin.22@cetis156.edu.mx?subject=${form.get('name')}${form.get('email')}&body=${form.get('mensaje')}`)
             $buttonMailto.click()
            }
        </script>
    </section>
</main>
</body>
</html>
