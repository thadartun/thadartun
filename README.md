<!--Created By: Riya
    Created On:Aug-15-2023-->


    <!DOCTYPE html>
    <html>
     <head>
    <title>happy independence day</title>
    <style>
        
        
        .holder {
          height: 350px;
          width: 10px;
          background:silver;
          margin-left:70px;
          margin-top:20px;
          }
    
      
      .stand {
          height: 20px;
          width: 50px;
          background: brown;
          margin-left:50px;
          }
      .stand1 {
          height: 20px;
          width: 90px;
          background: brown;
          margin-left:30px;
          }
       .stand2 {
          height: 20px;
          width: 130px;
          background: brown;
          margin-left:10px;
          }
        
          
      .flag {
          width: 200px;
          height: 120px;
          margin-left:10px;
          animation-name: flag;
          animation-duration: 7s;
          animation-iteration-count:1;
          }
     
      .orange {
          height: 40px;
          background-color:orange;
      }
     
      .white {
          height: 40px;
          background-color:white;
      }
     
      .green {
          height: 40px;
          background-color: green;
      }
     
    @keyframes flag {
        0% { transform: translate(0px,180px);} 
    }
    .colorchange{
            position: absolute;
            top: 0;
            left: 0;
            width:100%;
            height:120%;
            background-color:#fad46c;
            animation-name:colorchange;
            animation-duration:7s;
            animation-iteration-count:1;
       }
    @keyframes colorchange {
       0% {background-color:#221426;}
       30% {background-color:#c47c1c;}
         60% {background-color:#f4d588;}
             100% {background-color:#fad46c;}
       
    }
    </style>
    </head>
    <body>
        
       <div class="colorchange">
     
      <img src="https://drive.google.com/uc?export=view&id=1qOe1E-X784as17MZmvf_4fZZWviPDQtQ" style=" height:100px;width:350px">
       
       <div class="holder">
             
            <div class="flag">
                <div class="orange"></div>
                <div class="white">
                   <img src="https://drive.google.com/uc?export=view&id=1orox751LV2TSx-T6sLEKqQZ36KuE_hNS" style=" height:40px;width:40px; margin-left:80px"></div>
                <div class="green"></div>
             </div>
           <img src="https://drive.google.com/uc?export=view&id=1qc2DwRkdYWLf4PzdOiUBT9Qhz68CAVT_" style=" height:100px;width:100px;margin-left:160px;margin-top:180px">
        
           </div>
         
          <div class="stand"></div>
          <div class="stand1"></div>
          <div class="stand2"></div><br>
     
    <audio src="https://drive.google.com/uc?export=download&id=1qEay5j83VmrcLy2FJ6F31NVHynP3jBW0" id="music">
           </audio>
    <marquee> <h3 style="color:blue">🇮🇳𝟟𝟟𝕥𝕙 𝕀𝕟𝕕𝕖𝕡𝕖𝕟𝕕𝕖𝕟𝕔𝕖 𝔻𝕒𝕪 𝟚𝟘𝟚𝟛🇮🇳
    </h3</marquee>
    </div>
    
     <script>
      var music = document.getElementById("music")
      music.load();
      document.addEventListener("click", function() {
      music.play()
      })
      </script> 
    </body>
    </html>
