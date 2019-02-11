<html>
  <head>
    <title>comp</title>
    <script>
      var queryString = window.location.search.slice(1);
      if(queryString){
       var qstring = queryString.split('q=')[1].split('&')[0];
        alert(qString);
      }else{
        alert('test');
      }
    </script>
  </head>
  
  <body>
    TBO
  </body>
</html>
