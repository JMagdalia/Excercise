<!DOCTYPE HTML>
  <html lang="pl">
    <head>
    <meta charset="utf-8"/>
    <title>Odliczanie czasu</title>

<script type="text/javascript">
  
var dzisiaj = new Date();

var dzien = dzisiaj.getDate();
var miesiac = dzisiaj.getMonth();
var rok = dzisiaj.getFullYear();
var godzina = dzisiaj.getHours();
var minuta = dzisiaj.getMinutes();
var sekunda = dzisiaj.getSeconds();

</script>
</head>

<body>
 
<div id = "zegar"></div>

<script type="text/javascript">
  document.getElementById("zegar").innerHTML = dzien;
  
  
 </script>

</body>
</html>
