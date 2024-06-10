</head>
<body>
    <div class="container">
        <h1>📚 Métodos del Objeto String en JavaScript</h1>
        <p>Explora algunos de los métodos más útiles del objeto <strong>String</strong> en programación:</p>
        <img class="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSIRvnBpMk0N6ExLe3ZEv8Oba3CmJhWZOE1rx4EO7X94Ikd2pl-VJQq4j4&s=10">
      <div class="method">
            <h2>🔤 Concat</h2>
        Permite unir dos matrices, para formar una tercera, ejem:
        <script>
          var indice=0;
          var matriz1= new Array("Uno"."Dos","Tres");
           var matriz2= new Array("Cuatro"."Cinco","Seis");
           var matriz3= matriz1.concat(matriz2);
          for(indice =0; indice<matriz3.length;indice++)
            {
              document.write(matriz3[indice]+"<br>");
               }
        </script>
        </div>
          <div class="method">
            <h2>🔤 Join </h2>
               Une todos los elementos de una matriz en una cadena_alfanumerica, ejemplo:
            var matriz=new Array("Elemento 1", "Elemento 2", "Elemento 3");
            var cadena;
            cadena=matriz.join();
           document.write(cadena);
           --------------------------------------------------------------------------------------------------------------
           Elemento 1, Elemento 2, Elemento 3
        Al unir los elementos, JavaScript los separa mediante comas, si queremos cambiarlo debemos poner el separador entre comillas ejem:
          </head>
          <body>
              <script>
                  var matriz=new Array("Elemento 1", "Elemento 2", "Elemento 3");
                  var cadena;
                  cadena=matriz.join("**");
                  document.write(cadena);
              </script>
          </body>
         

  </div> 
        <div class="method">
            <h2>🔤 length</h2>
            <p>Devuelve la longitud de una cadena de texto.</p>
        </div>
        <div class="method">
            <h2>🔠 toUpperCase()</h2>
            <p>Devuelve una cadena en mayúsculas.</p>
            <img src="https://th.bing.com/th/id/R.c3e601bbec9d303cd114fe416579485c?rik=AQS12tRHMaxpfg&pid=ImgRaw&r=0&sres=1&sresct=1" alt="toUpperCase Method">
        </div>
        <div class="method">
            <h2>🔡 toLowerCase()</h2>
            <p>Devuelve una cadena en minúsculas.</p>
        </div>
        <div class="method">
            <h2>🔠 charAt()</h2>
            <p>Devuelve el carácter en la posición especificada de una cadena.</p>
            <h2>🔤 split()</h2>
            <p>Divide una cadena en un array de subcadenas.</p>
        </div>
        <div class="method">
            <h2>🔡 slice()</h2>
            <p>Extrae una sección de una cadena y devuelve una nueva cadena.</p>
            <img src="https://webtechparadise.com/sites/default/files/inline-images/javascript-array-slice-method-foxbits-fact-1_0.jpg" alt="slice Method">
        </div>
        <div class="social-links">
            <a href="https://www.instagram.com/ykl_mgt?igsh=MTRuMDJ5enJ3dHFqcQ%3D%3D&utm_source=qr">Instagram</a>
            <a href="https://www.facebook.com/itkayul.montes?mibextid=LQQJ4d">Facebook</a>
        </div>
    </div>
</body>
</html>
