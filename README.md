<!DOCTYPE html>
<html>
<meta charset='UTF-8'/><meta content='width=device-width, initial-scale=1, user-scalable=1, minimum-scale=1, maximum-scale=5' name='viewport'/><meta content='IE=edge' http-equiv='X-UA-Compatible'/><link href="https://feeldreams.github.io/singkat/style.css" rel="stylesheet" type="text/css" />
  
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Shippori+Antique:wght@400;700&display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Dancing+Script&display=swap" rel="stylesheet">

  <script src="https://cdn.jsdelivr.net/npm/sweetalert2@11.0.19/dist/sweetalert2.all.min.js"></script>
  <script src="https://unpkg.com/typeit@8.7.0/dist/index.umd.js"></script>
  <script src="https://kit.fontawesome.com/4f3ce16e3e.js" crossorigin="anonymous"></script>
  
<head>
<title>babbab</title>
</head>
<body>
	
   <!-- Ganti Audio di sini -->
   <audio src="https://feeldreams.github.io/vibescorona.mp3" id="linkmp3" class="sembunyi"></audio>
   
   <div id="bodyblur">
     <!-- Wallpaper --><img src="https://feeldreams.github.io/wp4.jpg" id="wallpaper"/><div id="beneranblur"></div>
   </div>
   
   <div id='Content'>

     <div id="kadoIn">
       <!-- Tombol Surat --><img src="https://feeldreams.github.io/kadoin.png"/>
     </div>
     <p id="ket">A gift for you</p>

     <div class="kumpulanstiker">
         <!-- Stiker untuk Konten -->
         <img src="https://feeldreams.github.io/bunga.gif" id="fotostiker"/>
         <img src="https://feeldreams.github.io/g5.gif" id="fotostiker2"/>
         <img src="https://feeldreams.github.io/mndkat.gif" id="fotostiker3"/>
         <img src="https://feeldreams.github.io/ywdh.gif" id="fotostiker4"/>
         <img src="https://feeldreams.github.io/ngumpet.gif" id="fotostiker5"/>
         <img src="https://feeldreams.github.io/smprt.gif" id="fotostiker6"/>
         <img src="https://feeldreams.github.io/ciumin.gif" id="fotostiker7"/>
     </div>
     <p id="halo" class="halo">hello babbab</p>
     <!-- Konten Pesan Setelah Aksi -->
     <p id="halo2" class="halo">I love you always ✨</p>
     
     <!-- Konten Pesan Akhir -->
     <p id="kalimatbawah">I Love You ❤️</p> 
     <p id="kalimatbawah2" class="sembunyi">i miss you ❤️</p> 
     <p id="kalimatbawah3" class="sembunyi">i love you moreeeeee ❤️</p>
       
     <div><blockquote id='bq' data-text='&#9829;'>

       <!-- Konten Pembukaan -->
       <p id="kalimat">i know your having a bad day...</p>
       <p id="kalimatb">but dont forget i love you no matter what❤️</p>
       <p id="kalimatc">just think positive and it gonna be alright.. ☺️</p>
       <p id="kalimatd">Even though we are appart.. 🥺</p>
       <p id="kalimate">my presence will burst love for you.. 🥺</p>
       <p id="kalimatf">maskin pala away ka HAHAHAHA 🤬</p>
       
       <p id="opsL">From ping</p>
       
     </blockquote></div>

     <!-- Tombol Kirim Pesan -->
     <div id="Tombol"><a id="By">&#128140; Balas</a></div>

     <!-- Pesan yang dikirim ke WhatsApp -->
     <span id="pesanWA" class="sembunyi">Aww, GoodNight too!</span>
     
   </div>

<!-- Jangan Edit Bagian Ini --><script>
  const body = document.querySelector("body");inikuis=0;ftganti=0;flag=1;flagg=1;fungsi=0;ftfungsi=0;fungsiAwal=0;fungsitimer=0;vketikhalo=halo.innerHTML;halo.innerHTML = "";vketikhalo2=halo2.innerHTML;halo2.innerHTML = "";pesanwhatsapp = pesanWA.innerHTML;deffotostiker=fotostiker.src;audio = new Audio('' + linkmp3.src);Content.style = "opacity:1;margin-top:16vh;";const swalst = Swal.mixin({timer: 2777, allowOutsideClick: false, showConfirmButton: false, timerProgressBar: true, imageHeight: 90,}); const swals = Swal.mixin({allowOutsideClick: false, cancelButtonColor: '#FF0040', imageWidth: 100, imageHeight: 100,}); const style = document.createElement('style'); var today = new Date();var dd = String(today.getDate()).padStart(2, '0');var mm = String(today.getMonth() + 1).padStart(2, '0');var yyyy = today.getFullYear();const monthNames = ["Januari", "Februari", "Maret", "April", "Mei", "Juni", "Juli", "Agustus", "September", "Oktober", "November", "Desember"];today = dd + ' ' + monthNames[today.getMonth()] + ' ' + yyyy;
  function createHeart() {const heart = document.createElement("div"); heart.className = "fas fa-heart"; heart.style.left = (Math.random() * 90)+"vw"; heart.style.animationDuration = (Math.random()*3)+2+"s"; body.appendChild(heart);} setInterval(function name(params) {var heartArr = document.querySelectorAll(".fa-heart"); if (heartArr.length > 100) {heartArr[0].remove()}},100);
  async function menuju(){window.location = "https://api.whatsapp.com/send?phone=&text=" + pesanwhatsapp;} document.getElementById("kadoIn").onclick = function() {if(fungsiAwal==0){audio.play();fungsiAwal=1;kadoIn.style="transition:all .8s ease;transform:scale(10);opacity:0";wallpaper.style="transform: scale(1.5);";ket.style="display:none";setTimeout(mulainama,700)}}
</script>
<script src="https://feeldreams.github.io/singkat/script.js"></script>
<!-- Sampai Sini -->
</body>
</html>
