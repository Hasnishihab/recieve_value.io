<html>
<head>
</head>
<body>
  <h2>you can view the values here</h2>
 <p>The serial number is: </p>
      <script>
 
var queryString = decodeURIComponent(window.location.search);
queryString = queryString.substring(1);
var queries = queryString.split("&");
for (var i = 0; i < queries.length; i++)
{
  document.write(queries[i] + "<br>");
}
 
</script> 
  
</body>
</html>
