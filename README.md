# Dauletyar
Dauletyar Uralbayev
<html>
    <head>
        <style>
            body
            {
                background-color: green;
                color: white;
                text-align: center;
            }
            button
            {
                background-color: red;
                color: white;
                padding: 1%;
                margin: 1%;
            }
        </style>
        <script>
            function juwap(){
            var m=3650;
            var m2=600;
            var h=54;
            var h2=2;
            var a=8;

                var j=m2*a+m;
                var j2=h2*a+h;

                document.querySelector(".juwap").innerText="Salmagi "+a+" aydan keyin shama menen = "+j +"gr";
                document.querySelector(".juwap2").innerText="Boyi "+a+" aydan shama menen  = "+j2+" sm";

            }
        </script>
    </head>
    <body>
        <h2>m= 3650 gr</h2>
        <h2>m2 = 600 gr</h2>
        <h2>h = 54 sm</h2>
        <h2>h2 = 2 sm</h2>
        <h2>a = 8 </h2>
        <h1>Juwabi</h2>
        <h2 class="juwap"></h2>
        <h2 class="juwap2"></h2>
        <button onclick="juwap()">Tekseriw</button>
    </body>
</html>
