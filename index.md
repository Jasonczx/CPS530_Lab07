<!DOCTYPE>
<html>
<head>
<meta charset="utf-8">
<title>Draw</title>
<link rel="stylesheet" href="ani.css">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
<script src="ani.js"></script>

<script>
$(document).ready(function(){
  $("button").click(function(){
    $("img").animate({
      left: '250px',
      height: '150px',
      width: '150px'
    });
  });
});
</script>

</head>
<body>

<button>Start Animation</button>

<img src="PinClipart.com_mr-potato-head-parts_1440968.png">
<img src="PinClipart.com_mond-clipart_1412617.png">
<img src="PinClipart.com_hearing-aid-clip-art_571926.png">
<img src="PinClipart.com_french-barrette-hat-clipart_3766435.png">
<img src="PinClipart.com_vampire-teeth-clipart_1094419.png">
<img src="PinClipart.com_mrs-potato-head-clip_873307.png">

</body>
</html>
