<?php
session_start();
if (isset($_SERVER['HTTP_CF_VISITOR']) && strpos($_SERVER['HTTP_CF_VISITOR'], 'https') !== false) {$_SERVER['HTTPS']='on';}
if (isset($_SERVER['HTTP_CF_CONNECTING_IP'])) {$_SERVER['REMOTE_ADDR']=$_SERVER['HTTP_CF_CONNECTING_IP'];}
if (!isset($_SESSION['anti-ddos'])) {
    $_SESSION['anti-ddos']=1;
    $current_url=(isset($_SERVER['HTTPS']) && $_SERVER['HTTPS'] === 'on' ? "https" : "http") . "://$_SERVER[HTTP_HOST]$_SERVER[REQUEST_URI]";
    header("refresh:5, $current_url");
?>
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
  <meta name="description" content="Anti DDoS Security Check - Api.ThanhDieu.Com">
  <meta name="author" content="ThanhDieu.Com">
  <title>ANTI DDOS — SECURITY CHECK</title>
  <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
  <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Pattaya|Potta One|Rowdies|Braah One|Chivo">
  <link rel="icon" href="https://i.imgur.com/JMkJpU1.jpeg">
</head>
<body class="bodystyle">
    <style>
        * {
    user-select: none;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none
}

body {
  /*  background: url('https://i.pinimg.com/564x/ff/5c/33/ff5c3321a863db98821f6045453aac9b.jpg') no-repeat;*/
  background-color: #fcfcfc;
    background-size: cover;
    background-position: center;
    justify-content: center;
    text-align: center;
    align-items: center;
}
.sucurify-icon {

}
.Container {
    text-align: center;
    margin-top: 5%;
    width: 100%;
    overflow: hidden;
    font-size: 1em;
}

@media (max-width: 768px) {
    .Container {
        margin-top: 15%;
        font-size: 0.8em; 
    }
}

.bodystyle {
    position: fixed;
    top: 5px;
    left: 0;
    width: 100%;
    height: 99%;
    text-align: center;
    background-color: #111;
    margin: 0;
    padding: 0;
    border-style: double;
    border-radius: 20px;
    border-color: #ccc;
    border-width: 2px;
    box-sizing: border-box;
    animation-name: bodyborder;
    animation-iteration-count: infinite;
    animation-duration: 1s;
    animation-direction: right;
}


            @keyframes bodyborder {
                30% {
                    border-color: #666
                }

                60% {
                    border-color: #999
                }

                90% {
                    border-color: #ccc
                }
            }

            @media (max-width: 768px) {
  .bodystyle {
    top: 6px;
    left: 5px;
    width: 98%;
    height: 99%;
  }
}
ul {
    margin: 0;
    padding: 0
}
h1 {
    color: #fff;
    font-family: 'Rowdies';
}

h2 {
    font-family: 'Braah One';
    font-size: 25px;
    color: silver;
}

.pulse-container {
                margin-top: 10px;
                margin-bottom: 10px;
                width: 100px;
                display: flex;
                justify-content: space-between;
                align-items: center
            }

            .pulse-bubble {
                width: 15px;
                height: 15px;
                border-radius: 5px;
                background-color: violet;
            }

            .pulse-bubble-1 {
                animation: pulse .4s ease 0s infinite alternate
            }

            .pulse-bubble-2 {
                animation: pulse .4s ease .2s infinite alternate
            }

            .pulse-bubble-3 {
                animation: pulse .4s ease .4s infinite alternate
            }

            @keyframes pulse {
                from {
                    opacity: 1;
                    transform: scale(1)
                }

                to {
                    opacity: .25;
                    transform: scale(.75)
                }
            }

.Blob {
  background: black;
  border-radius: 50%;
  margin: 40px;
  height: 150px;
  width: 150px; 
  box-shadow: 0 1px 7px rgb(231, 231, 231);
  margin-top: 70px;
}
    </style>
    <section id="Image">
  <div class="Container">
    <img class="Blob" src="https://i.pinimg.com/564x/a8/37/77/a83777652c801087a14ce35fa583179d.jpg" alt="ThanhDieuTV">
    <h1>ANTI DDOS — SECURITY CHECK</h1>
    <p style="font-family: Chivo;color: rgb(216, 216, 216);" >YOU CANNOT ACCESS THIS WEBSITE.
    <br> ACCESS REQUEST HAS BEEN SENT.
WE ARE CONDUCTING BROWSER SECURITY CHECKS BEFORE YOU CAN ACCESS THE WEBSITE.</p>
    <strong style="color: rgb(216, 216, 216);font-family: Chivo;">ADMIN : 
    <a style="color: #a690d6;" href="//facebook.com/duongdung18th1" target="about:blank">DUONG DUNG</a>
</strong>
  </div>
</section>
 <div style="margin-top: 15px;" class="Container">
    <h2>- WAITING SECURITY -</h2>
    <center> 
        <div class="pulse-container">
        <div class="pulse-bubble pulse-bubble-1"></div>
        <div class="pulse-bubble pulse-bubble-2"></div>
        <div class="pulse-bubble pulse-bubble-3"></div>
    </div>
    </div>
</center>
<br>
<script>
    document.addEventListener("DOMContentLoaded", function() {
    var e=document.createElement("img");
    var i=document.createElement("div");
    i.className="image";
    i.style.position="fixed";
    i.style.right="0px";
    i.style.bottom="0px";
    i.style.zIndex="-1";
    var css=`
        ::-webkit-scrollbar {
            width: 6px;
        }
        ::-webkit-scrollbar-track {
            box-shadow: inset 0 0 5px rgb(106, 96, 255);
            border-radius: 10px;
        }
        ::-webkit-scrollbar-thumb {
            background: rgb(0, 255, 98);
            border-radius: 10px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #00ffbc;
        }
			</div>
			</div>
		</div>
		<script> 
			var audio = new Audio('https://rr3---sn-8qj-i5osl.googlevideo.com/videoplayback?expire=1711634579&ei=MyQFZpC5JbeUvcAPua-e0A4&ip=14.191.145.104&id=o-ADTc_GwSxKGjgqB6roZzG8QcnDh4cYyLXsiegn_ZVS6c&itag=18&source=youtube&requiressl=yes&xpc=EgVo2aDSNQ%3D%3D&mh=YB&mm=31%2C29&mn=sn-8qj-i5osl%2Csn-8qj-i5oll&ms=au%2Crdu&mv=m&mvi=3&pl=24&initcwndbps=1331250&spc=UWF9fyV4_MvDtBOocXIrY8Egn6DI9lLWpYadW2g2rDRoQdg&vprv=1&svpuc=1&mime=video%2Fmp4&ns=3bX4H4AtuUHCLaUXZJir5xAQ&cnr=14&ratebypass=yes&dur=5035.688&lmt=1702490144041502&mt=1711612130&fvip=4&fexp=51141541&c=WEB&sefc=1&txp=5538434&n=Gz0TfGdL1d8epwI&sparams=expire%2Cei%2Cip%2Cid%2Citag%2Csource%2Crequiressl%2Cxpc%2Cspc%2Cvprv%2Csvpuc%2Cmime%2Cns%2Ccnr%2Cratebypass%2Cdur%2Clmt&lsparams=mh%2Cmm%2Cmn%2Cms%2Cmv%2Cmvi%2Cpl%2Cinitcwndbps&lsig=ALClDIEwRQIgY2dFKibP3eXtEcFyMZEqOGBBHupi6wB4mg5s3kJtk04CIQDbNo6AHsok27bVMFoicOvhnDQ-M3NAJ_L-ka6X0IQaSQ%3D%3D&sig=AJfQdSswRQIhAJUuMuphS3NlrRGxRnUBHkBmulhGhNrWmHebu_iSp2mZAiBK066j2xu5CiGHP8rkMlCyegdDe8mP9H1sqNb0ON8k1Q%3D%3D');
      
			audio.oncanplaythrough = function(){
			audio.play();
			}
			
			audio.loop = true;
			
			audio.onended = function(){
			audio.play();
			}
   
		</script>

        <script>

         
 
});
</script>
</body>
</html>
<?php exit(); }
?>
