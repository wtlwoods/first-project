<!Doctype html>

<html>
<head>
<title>first project</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta charset="utf-8"> 
<link rel="stylesheet" type="text/css"  href="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/css/bootstrap.min.css">
<link rel="stylesheet" type="text/css" href="main.css">
</head>
<body>


<!-------beginning of content--------->
<!------beginning of nav----->
<nav class="navbar navbar-default" style="background-color:lavender">
<div class="container-fluid">
<div class="navbar-header">
<div class="navbar-brand" href="#">ABC Childcare</a></div>
<div>
<ul>
<a href="#"><li>Home</li></a>
<a href="#"><li>About</li></a>
<a href="#"><li>Contact</li></a>
</ul>
</div>
</div>
</div>
</nav>

<!-----beginning of jumbotron, may make this a carosel------>
<div class="container">
<div class="jumbotron">
<h1>ABC Childcare</h1>
<p style="font-family:Vivaldi, Cursive">"where children play and learn</p>
</div>
</div>
<!-------tumbnails with text------->
<div class="row">
<div class="col-sm-4"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSE5eAk2Si87usDrFlWrNK61rhn1zjfQYHqkRI-GxneAdSJ1AYm" class="img-thumbnail" alt="Cinque Terre" width="120" height="120" />
<p>Die Internationale Raumstation (englisch International Space Station, kurz ISS) ist eine bemannte Raumstation, die in internationaler Kooperation betrieben und ausgebaut wird. Die Pläne für eine große inter­nationale Raumstation gehen bis in die 1980er Jahre zurück. <a href="#">Learn More</a></p>
</div>
<div class="col-sm-4"><img src="https://encrypted-tbn1.gstatic.com/images?q=tbn:ANd9GcSpfMzFknb-RrbEuS-BIq88B6DZ__eE8rsroWSwawTCi9wdVXN_zA" class="img-thumbnail" alt="Cinque Terre" width="120" height="120"/><p>Die Internationale Raumstation (englisch International Space Station, kurz ISS) ist eine bemannte Raumstation, die in internationaler Kooperation betrieben und ausgebaut wird. Die Pläne für eine große inter­nationale Raumstation gehen bis in die 1980er Jahre zurück. <a href="#">Learn More</a></p></div>
<div class="col-sm-4"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRjSZnIiN_6W5ymtHYUoYAYbBmvsWh6S5sOyUn002YVaqUNiuXQmQ" class="img-thumbnail" alt="Cinque Terre" width="120" height="120"/><p>Die Internationale Raumstation (englisch International Space Station, kurz ISS) ist eine bemannte Raumstation, die in internationaler Kooperation betrieben und ausgebaut wird. Die Pläne für eine große inter­nationale Raumstation gehen bis in die 1980er Jahre zurück. <a href="#">Learn More</a></p></div>
</div>
<!-----buttons this may go on coverpage------->
<div class="container">
<a href="#"><button type="button" class="btn btn-info">Contact  Us</button></a> <a href="#"><button type="button" class="btn btn-info">Learn More</button></a>
</div>

<footer style="background-color:#777777;">
Melisa Pettaway &copy;Copyright 2015
</footer>

<script type="text/css">
$(document).ready(function(){
  $('button').hover(function(){
    $(this).fadeOut('slow', 1);
      });
      $('button').hover(function(){
        $(this).fadeIn('slow',1);
        
      });
  });
  
  </script>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
<script src="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/js/bootstrap.min.js"></script>
<link rel='stylesheet' type='text/css' href='http://code.jquery.com/ui/1.9.1/themes/base/jquery-ui.css'/>
<script src="//ajax.googleapis.com/ajax/libs/jqueryui/1.9.1/jquery-ui.min.js"></script>
</body>
</html>
