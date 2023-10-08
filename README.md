<head>
    <img src="images.jpg" width="1900" height="200">
    <h1 style="text-align: center">Ogólno Polska Akcja Łowiena Ryb</h1>
    <img src="rybka2.jpg" width="400" height="400" style="float: right">
    <img src="opalr1.jpg" width="700" height="350" style="float: centre">
    <img src="PZW.jpg" width="400" height="400" style="float: left">
    <img src="PLflag.jpg" width="1900" height="20">
    
    <h1>Informacje główne:</h1>
    <h2>Ogólno Polska Akcja Łowienia Ryb odbywa się cztery razy w roku w miesiącach letnich<h2>
    <h2>Aby brać udział w zawodach potrzebujesz karty rybackiej oraz zgłosić się co najmniej tydzień przed zawodami</h2>

<h1>Zasady:</h1>
<h2>można brać udział pojedyńczo oraz w drużynie</h2>

<h1>Udział jedno osobowy:</h1>
<h2>Każdy z zawodników posiada swoją kartę OPAŁR. Za zdobyte miejsca dosteje się punkty, które trafiają na konto wędkarza</h2>
<h2>
    1 miejsce: 15pkt
    2 miejsce: 9pkt
    3 miejsce: 6pkt
    4 miejsce: 2pkt
    5 miejsce: 1pkt
</h2>
<h2>Punkty są liczone na zasadzie ilości złowionych ryb. Im więcej uczestnik złowi ryb tym lepsze miejsce zajmie</h2>
    
<h1>Udział Drużyn:</h1>
<h2>Aby utworzyć druynę musi być minimalnie 5 osób</h2>
<h2>Punkty drużynowe liczą się no podstawie punktów wszystkich członków drużyny</h2>
<h2>na koniec sezonu letniego ogłaszane są zwycięskie drużyny oraz zwycięzcy wędkaże</h2>
</head>
    

    
    
    
    
    
     <script>
        function countdown(endDate, elementId) {
          var endDateObj = new Date(endDate).getTime();
    
    var x = setInterval(function() {
        var now = new Date().getTime();
        var distance = endDateObj - now;
    
    var days = Math.floor(distance / (1000 * 60 * 60 * 24));
    var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
    var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
    var seconds = Math.floor((distance % (1000 * 60)) / 1000);
    
    document.getElementById(elementId).innerHTML = days + "d " + hours + "g "
    + minutes + "m " + seconds + "s ";
    
    if (distance < 0) {
      clearInterval(x);
      document.getElementById(elementId).innerHTML = "OPALR";
    }
    }, 1000);
    }
    </script>
          <img src="PLMap.jpg" width="512" height="512" style="float: right">
    
    
    
    <body style="background-color: rgb(77, 109, 157);"></body>
    <center>
      <font size="5"><h1 style="text-align: left"> Następne zawody:</h1></font>
      <h1><p style="text-align: left"><span id="data1"></span> - 12 Czerwca 2024 roku: Bug</p></h1>
      <h1><p style="text-align: left"><span id="data2"></span> - 24 Lipca 2024 roku: Wisła</p></h1>
      <h1><p style="text-align: left"><span id="data3"></span> - 18 Sierpnia 2024 roku: Odra</p></h1>
      <h1><p style="text-align: left"><span id="data4"></span> - 27 Września 2024 roku: Wisła</p></h1>
    <script>
        countdown('2024-06-12', 'data1');
        countdown('2024-07-24', 'data2');
        countdown('2024-08-18', 'data3');
        countdown('2024-09-27', 'data4');
      </script>


<h1>Główny sponsor: PZW - Polski Związek Wędkarski</h1>
<a href="https://www.pzw.org.pl/"><h2>Strona PZW</h2></a>
