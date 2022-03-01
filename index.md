<!DOCTYPE html>
<html lang="en">

<head>
    <meta http-equiv="content-type" content="text/html; charset=utf-8" />
    <title>My first html file</title>
    <style>
        body {
          font-family: Comic Sans MS, Comic Sans, cursive ;
          text-shadow: 1px 1px 1px ;
          background-image: url(https://pixabay.com/get/g0f6fd0c56a4ea4c6b0c5623211803e588eaaf8a8f538a5335c47a6c9e3f5d6b13d699b5511c174ea1e448bedd36ab0ea6626782292fe7006603e7065a74435d9af569c78ab5566c07db6b379ced9b764_1920.jpg);
          background-repeat: no-repeat;
          background-position: center;
          background-size: cover;
        } 
        a {
            color: #FF5600;
            border: solid white;
            border-radius: 10px;
            background-color: #000000;
            padding: 5px 15px;
        }
        a:hover{
            border: solid white;
            background-color: #000000;
        }
        .flash{
            background-color: rgb(255, 123, 0);
            border: 2px solid black;
            border-radius: 8px;
            padding: 6px 10px;
        }
        .flash:hover{
            background-color: #FFC700;
        }
        .homebtn{
            background-color: #FFFFFF;
            border: 2px solid black;
            padding: 6px 10px;
        }
        .imgearth{
            border: 20px solid black;
            border-radius: 1000px;
        }
        
        </style>
        <script>
                window.alert("TO CONTINUE PLEASE CLICK ON OK");
        </script>
</head>

<body>
    <header>
        <section>
            <hr>
            <a href='https://theju002.w3spaces.com/indhtmlex.' class="homebtn">HOME</a>
            <center>
                <hr>
                <h1><em>My name </em></h1>
                <h4> is</h4>
                <p id="My name" style="color:#FF8200" ><em><strong>THEJUS FRENIL</strong></em></p>
                <button class="flash" type="button" onclick="document.getElementById('My name').innerHTML = 'THEJUS GTA'">A.K.A</button> 
                <p> I'm 11 years old</p>
            <center>
            <hr>
        </section>
        <section>
            <h2><em>MY FAMILY</em></h2> 
            <ol>
                <li>My father's name is <em>Frenil Francis </em></li>
                <li>My mother's name is <em>Jini Frenil </em></li>
                <li>My sister's name is <em>Twinkle Frenil </em></li>
            </ol>
        </section>
            <hr>
    </header>
    <main>
        <p style="color:#008E81"> MY FAVORITE GAME IS </p>     
        <a href="https://app.playpkxd.com/login"> PK XD </a>
        <br><br>
        <center><iframe class="imgearth" href="https://www.google.co.in/maps/@10.5131564,76.1761428,70m/data=!3m1!1e3?hl=en" width="500" height="500" alt="Earth">
            <h2><strong> MY HOME IS IN INDIA </strong></h2>
        </center>
        <a href="https://newsforkids.net/"> Todays news please read </a><br><br>
        <center><hr>
            <img
                src="https://theju002.w3spaces.com/Fire_tube.jpeg"
                width="500" height="309" alt="MY YOUTUBE PIC">
            <p style="color:red"><strong>THIS IS MY MY LITTLE YOUTUBE CHANNEL, PLEASE SUPPORT ME BY CLICKING THAT RED SUBSCRIBE BUTTON TO
                    GREY</strong></p>
        </center>
        <a href="https://youtube.com/channel/UCoKI-1Q3QB2KqjHI913kVrA"> SUBSCRIBE </a>
        <br>
        <br>
        <center>
            <details>
                <summary>
                    <h3>My dream in code</h3>
                </summary>
                <div>
                    <h2>To be a web dev(actualy, I want to be a astronaut)</h2>
                    <img src="https://mimo.app/i/hacker.png" width="500" height="500" alt="hacker">
                </div>
            </details>
            <button class="flash" type="button" onclick="alert('THANKS A LOT FOR SEEING!')">I want to tell that</button>
            <hr>
        </center>
    </main>
</body>

</html>
