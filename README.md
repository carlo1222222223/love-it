<html><meta charset='UTF-8'/><meta content='width=device-width, initial-scale=1, user-scalable=1, minimum-scale=1, maximum-scale=5' name='viewport'/><meta content='IE=edge' http-equiv='X-UA-Compatible'/>
  
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Work+Sans:wght@400;700&display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Ubuntu:wght@400;700&display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Dancing+Script&display=swap" rel="stylesheet">
  
  <script src="https://cdn.jsdelivr.net/npm/sweetalert2@11.0.19/dist/sweetalert2.all.min.js"></script>
  <script src="https://kit.fontawesome.com/4f3ce16e3e.js" crossorigin="anonymous"></script><link href="https://feeldreams.github.io/night/style.css" rel="stylesheet" type="text/css" />

<head>
<title>Script HTML Night</title>
<!-- 

  Made with love by Rayys!
  
     Blog: https://PalingIT.com
     Instagram: @rayyarrr
     TikTok: @rayy4r
     Email: rayyar0703@gmail.com
     
  Thanks to all <3
  
-->
</head>
<body>
	
   <!-- Ganti Audio di sini -->
   <audio src="https://feeldreams.github.io/fullsenyum.mp3" id="linkmp3" class="sembunyi"></audio>
   
   <div id="bodyblur">
     <!-- Wallpaper --><img src="https://feeldreams.github.io/nightin.jpeg" id="wallpaper"/><div id="beneranblur"></div>
   </div>
   
   <div id='Content'>

     <div id="suratin" onClick="memulai();">
       <!-- Tombol Surat --><img src="https://feeldreams.github.io/kadoin.png"/>
     </div>
     <p id="ket">คลิกที่ของขวัญ</p>

     <div class="kumpulanstiker">
         <!-- Stiker untuk Konten -->
         <img src="https://feeldreams.github.io/pusn.gif" id="stiker1"/>
         <img src="https://feeldreams.github.io/bunga.gif" id="stiker2"/>
         <img src="https://feeldreams.github.io/mndkat.gif" id="stiker3"/>
         <img src="https://feeldreams.github.io/smprt.gif" id="stiker4"/>
         <img src="https://feeldreams.github.io/ngumpet.gif" id="stiker5"/>

         <!-- Stiker untuk Akhiran -->
         <img src="https://feeldreams.github.io/bunga.gif" id="stiker"/>
     </div>
     <p id="halo">Good Night!</p>

     <script class="sembunyi">
       async function pesanAwal() {
          suratin.style="display:none";ket.style="display:none";
          await swalst.fire({
            title: 'เฮ้ คิระ! ❤️',
            imageUrl: '' + stiker1.src,
         });   	
         await swalst.fire({
            title: 'ฉันแค่อยากจะพูด',
            imageUrl: '' + stiker2.src,
         });
         await swalst.fire({
            title: 'ราตรีสวัสดิ์ใช่! 🤭❤️',
            imageUrl: '' + stiker3.src,
         });
         await swalst.fire({
            title: 'อย่านอนดึกนะ โอเคไหม ',
            imageUrl: '' + stiker4.src,
         });
         await swalst.fire({
            title: 'คุณจะป่วยในภายหลัง❤️  &#x1F60A; ',
            imageUrl: '' + stiker5.src,
         });
         mulaikonten();
       }
     </script>
     <div><blockquote id='bq'>

       <!-- Konten Pembukaan -->
       <p id="kalimat">นั่นคือทั้งหมดที่</p>
       <p id="kalimat2">พักผ่อนเยอะๆ อย่าลืมอ่านบทสวดมนต์ก่อนเข้านอนนะคะ 😍... พรุ่งนี้ขอให้มีกำลังใจกับวันดีๆ นะคะ...</p>
       <p id="kalimatbawah">I Love You ❤️</p> 
       <p id="kalimatbawah2" class="sembunyi">Good Night ❤️</p> 
       <p id="kalimatbawah3" class="sembunyi">ฝันดีนะ โอเค ❤️</p> 

     </blockquote></div>

     <!-- Pesan yang dikirim ke WhatsApp -->
     <span id="pesanWA" class="sembunyi">Awww Good Night too ❤️❤️❤️</span>
     
   </div>

<!-- Jangan Edit Bagian Ini --><script>
  ftom=0;aksift=0;ftganti=0;flag=1;flagg=1;fungsi=0;fungsiAwal=0;fungsitimer=0;vketikhalo=halo.innerHTML;
  halo.innerHTML = "";var ahalo=0,vketikhalo;pesanwhatsapp = pesanWA.innerHTML;
  Content.style = "opacity:1;margin-top:16vh;";
  
  

  const body = document.querySelector("body");const swalst = Swal.mixin({timer: 2300, allowOutsideClick: false, showConfirmButton: false, timerProgressBar: true, imageHeight: 90,}); const swals = Swal.mixin({allowOutsideClick: false, cancelButtonColor: '#FF0040', imageWidth: 100, imageHeight: 100,});
  audio = new Audio('' + linkmp3.src);
  
  function createHeart() {const heart = document.createElement("div"); heart.className = "fas fa-heart"; heart.style.left = (Math.random() * 90)+"vw"; heart.style.animationDuration = (Math.random()*3)+2+"s"; body.appendChild(heart);} setInterval(function name(params) {var heartArr = document.querySelectorAll(".fa-heart"); if (heartArr.length > 100) {heartArr[0].remove()}},100);
</script>
<script src="https://feeldreams.github.io/night/script.js"></script>
<!-- Sampai Sini -->
</body>
</html>
