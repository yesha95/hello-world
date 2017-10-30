# hello-world
my first repository
<!--<html>
  <head>
  </head>
  <body>
    <p>
      yooooohoooooo
    </p>
  </body>
</html> -->
var http = require('http');
http.createServer(function (req, res) {
    res.writeHead(200, {'Content-Type': 'text/html'});
    res.end('Hello World!');
}).listen(8080);
