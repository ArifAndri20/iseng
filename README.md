<html>
<meta charset='UTF-8'/><meta content='width=device-width, initial-scale=1, user-scalable=1, minimum-scale=1, maximum-scale=5' name='viewport'/><meta content='IE=edge' http-equiv='X-UA-Compatible'/><link rel="preconnect" href="https://fonts.googleapis.com"><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin><link href="https://fonts.googleapis.com/css2?family=Quicksand&display=swap" rel="stylesheet"><script src="https://cdn.jsdelivr.net/npm/sweetalert2@11.0.19/dist/sweetalert2.all.min.js"></script><link href="https://lv3000.likeadream.repl.co/style.css" rel="stylesheet" type="text/css" /><script src="https://lv3000.likeadream.repl.co/script.js"></script>
<head>
<!-- 
This code was made by Rayya R!
Blog: https://sinkronin.com
Instagram: @rayyarrr
TikTok: @rayyarr_
Telegram: @rayyarr
WhatsApp: 6282130626142
-->
</head>
<body>
<style>
body{background-image: url("https://i.postimg.cc/mg3gmmB8/IMG-20211112-181440-797.jpg");background-repeat: no-repeat;background-size: 100% 100%;animation:none;transition:all .3s ease;}
</style>
<div id="konten">

<div id="foto"><div class="image">
<img id="photo" src="https://i.postimg.cc/zXNZhvZZ/hati.png" width="200px" height="200px"/></div>
<span id="sp2"></span></div>

<div id='slider'>
  <p>Haii kamuuuu ツ</p>
  <p>Akuu mau bilang nihh</p>
  <p>Kamuu jangan ngambek terus dong:(</p>
  <p>Jangan cuek mulu :(</p>
  <p>Kalo kamu marah-marah terus</p>
  <p>Akunya takut digigit kamu :p</p>
  <p>Candaa wleeee</p>
  <p>Oh iyaa bbyy, Happy Anniversary ya!</p>
  <p><3 <3 <3</p>
  <p>I Love U Bbyyyy &#9829;</p>
  <p>Pencet LOVE ini dong~<label class='lovein' onClick="duar()">&#128158;</label></p>
</div><div id="contTom"><a class='button whatsapp' onClick='bukaWa();'><i class='icon whatsapp'></i>Kirim</a></div>
</div>
<div id="bodyblur"></div>
<script>  
//Teks terakhir
var a=0,finish;
finish = "Happy Anniversary";

function play() {
//Link Audio Bisa Diganti
  var audio = new Audio('https://lv3000.likeadream.repl.co/musik.mp3');
  audio.play();
}
            
//Opsi WhatsApp
 function bukaWa(){window.location = "https://api.whatsapp.com/send?phone=&text=Hai, Aku udah liat semuanya <3" + "%0A%0A" + "Happy anniversary!" + "%0A%0A" + "Dikirim: " + dateTime;} 
</script>
 
<script type="text/javascript">            
            var today = new Date();var date = today.getDate()+'/'+(today.getMonth()+1)+'/'+today.getFullYear()+'.';var dateTime = date;
            const swals = Swal.mixin({
                allowOutsideClick: false,
            });
            async function mulai(){
                    await swals.fire('Halo!');
                    setTimeout(showDiv, 1000);play();                      
            }
            mulai();
</script>

</body>
</html>
