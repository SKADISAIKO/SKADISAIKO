- 👋 Hi, I’m @SKADISAIKO
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
SKADISAIKO/SKADISAIKO is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
!DOCTYPE html>
<html>
    <head>
        <title>RDRxMandalorian</title>
        <style>
            #sun{
                width: 600px;
                height: 600px;
                background-color: rgba(224, 166, 6, 0.747);
                border-radius: 50%;
                position: absolute;
                left: 30%
            }
            #sun2{
                width: 200px;
                height: 200px;
                background-color: rgba(224, 166, 6, 0.747);
                border-radius: 50%;
                position: absolute;
                left: -300px;
                bottom: 70px   ;
            }
            #back{
                width: 1500px;
                height: 700px;
                background-color: rgb(187, 9, 9);
                position: absolute;
            }
            #ground1{
                width: 1500px;
                height: 50px;
                background-color: black;
                position :absolute;
                bottom: 0%;
            }
            #ground2{
                width: 100px;
                height: 30px;
            }
            .triangle {
            display: inline-block;
            font-size: 0;
            overflow: hidden;
            position: relative;
            bottom: 2px;
            border-bottom-right-radius: 50%;
            border-bottom-left-radius: 50%;
            }
            .triangle:before {
            content: "";
            position: relative;
            top: 16px;
            display: inline-block;
            border: 12px solid rgb(10, 9, 9);
            border-bottom-width: 14px;
            border-top-width: 13px;
            border-top-color: rgba(181, 181, 181, 0);
            }
            #fly2{
                position: absolute
            }
            #fly1{
                position: absolute;
                bottom: 200px;
                left: 540px;
            }
            #fly3{
                position: absolute;
                bottom: 270px;
                left: 670px;
            }
            #fly4{
                position: absolute;
                bottom: 290px;
                left: 710px;
            }
            #fly4{
                position: absolute;
                bottom: 50px;
                left: -100px;
            }
            #mandoHead{
                width: 20px;
                height: 20px;
                border-radius: 50%;
                background-color: black;
                position: absolute;
                bottom: 20px;
                left: 50%;
            }
            #mandoMask{
                width: 20px;
                height: 10px;
                background-color: black;
                position: absolute;
                bottom: -5px;
            }
            #mandoBody1{
                width: 20px;
                height: 34px;
                background-color: black;
                position: absolute;
                bottom: -35px;
                left: 0px;
            }
            #grass1{
                width: 0;
                height: 0;
                border-top: 20px solid transparent;
                border-bottom: 20px solid black;
                border-right: 20px solid transparent;
                border-left: 20px solid transparent;
                position: absolute;
                bottom: 50px;
            }
            #grass2{
                width: 0;
                height: 0;
                border-top: 40px solid transparent;
                border-bottom: 40px solid black;
                border-right: 40px solid transparent;
                border-left: 40px solid transparent;
                position: absolute;
                bottom: 50px;
                left: 40px;
            }
            #grass3{
                width: 0;
                height: 0;
                border-top: 10px solid transparent;
                border-bottom: 10px solid black;
                border-right: 10px solid transparent;
                border-left: 10px solid transparent;
                position: absolute;
                bottom: 50px;
                left: 200px;
            }
            #grass4{
                width: 0;
                height: 0;
                border-top: 20px solid transparent;
                border-bottom: 20px solid black;
                border-right: 20px solid transparent;
                border-left: 20px solid transparent;
                position: absolute;
                bottom: 50px;
                right: 90px;
            }
            #grass5{
                width: 0;
                height: 0;
                border-top: 50px solid transparent;
                border-bottom: 50px solid black;
                border-right: 50px solid transparent;
                border-left: 50px solid transparent;
                position: absolute;
                bottom: 50px;
                right: 0px;
            }
            #grass6{
                width: 0;
                height: 0;
                border-top: 10px solid transparent;
                border-bottom: 10px solid black;
                border-right: 10px solid transparent;
                border-left: 10px solid transparent;
                position: absolute;
                bottom: 50px;
                right: 170px;
            }
            #grass7{
                width: 0;
                height: 0;
                border-top: 10px solid transparent;
                border-bottom: 10px solid black;
                border-right: 10px solid transparent;
                border-left: 10px solid transparent;
                position: absolute;
                bottom: 50px;
                right: 190px;
            }
            #grass8{
                width: 0;
                height: 0;
                border-top: 30px solid transparent;
                border-bottom: 30px solid black;
                border-right: 30px solid transparent;
                border-left: 30px solid transparent;
                position: absolute;
                bottom: 50px;
                right: 210px;
            }
            #grass9{
                width: 0;
                height: 0;
                border-top: 10px solid transparent;
                border-bottom: 10px solid black;
                border-right: 10px solid transparent;
                border-left: 10px solid transparent;
                position: absolute;
                bottom: 50px;
                right: 300px;
            }
            #mandoNeck{
                width: 10px;
                height: 10px;
                background-color: black;
                position: absolute;
                bottom: 30px;
                left: 5px;
            }
            #mandoHand1{
                width: 0;
                height: 0;
                border-top: 40px solid transparent;
                border-bottom: 0px solid transparent;
                border-right: 10px solid black;
                border-left: 10px solid transparent;
                position: absolute;
                bottom: -6px;
                right: 20px;
            }
            #mandoHand2{
                width: 0;
                height: 0;
                border-top: 40px solid transparent;
                border-bottom: 0px solid transparent;
                border-right: 10px solid transparent;
                border-left: 10px solid black;
                position: absolute;
                bottom: -6px;
                left: 20px;
            }
            #mandoLegs1{
                width: 0;
                height: 0;
                border-top: 5px solid transparent;
                border-bottom: 90px solid black;
                border-right: 5px solid transparent;
                border-left: 5px solid transparent;
                position: absolute;
                bottom: -30px;
                right: 0px;
            }
            #mandoLegs2{
                width: 0;
                height: 0;
                border-top: 5px solid transparent;
                border-bottom: 90px solid black;
                border-right: 5px solid transparent;
                border-left: 5px solid transparent;
                position: absolute;
                bottom: -30px;
                right: 10px;
            }
            #mandoCloth1{
                width: 0;
                height: 0;
                border-top: 60px solid transparent;
                border-bottom: 0px solid transparent;
                border-right: 10px solid transparent;
                border-left: 40px solid black;
                position: absolute;
                bottom: -10px;
                left: 10px;
            }
            #rifle1{
                width: 3px;
                height: 100px;
                background-color: black;
                position: absolute;
                bottom: -30px;
                left: 50%;
                transform: rotate(50deg);
            }
            #rifle2{
                width: 0;
                height: 0;
                border-top: 0px solid transparent;
                border-bottom: 40px solid transparent;
                border-right: 10px solid transparent;
                border-left: 10px solid black;
                position: absolute;
                bottom: 60px;
                left: 3px;
            }
            #rifle3{
                width: 0;
                height: 0;
                border-top: 0px solid transparent;
                border-bottom: 30px solid transparent;
                border-right: 4px solid transparent;
                border-left: 4px solid black;
                position: absolute;
                bottom: -20px;
                left: 3px;
            }
            #rifle4{
                width: 0;
                height: 0;
                border-top: 0px solid transparent;
                border-bottom: 30px solid transparent;
                border-right: 4px solid black;
                border-left: 4px solid transparent;
                position: absolute;
                bottom: -20px;
                right: 3px;
            }
            #kid1{
                width: 35px;
                height: 30px;
                border-radius: 50%;
                background-color: black;
                position: absolute;
                right: 80px;
                bottom: -20px;
            }
            #device1{
                width: 10px;
                height: 120px;
                background-color: black;
                border-radius: 30%;
                position: absolute;
                bottom: 30px;
                right: 390px;
            }
            #device2{
                width: 20px;
                height: 5px;
                background-color: black;
                border-radius: 30%;
                position: absolute;
                bottom: 100px;
                right: -5px;
            }
            #device3{
                width: 20px;
                height: 5px;
                background-color: black;
                border-radius: 30%;
                position: absolute;
                bottom: 90px;
                right: -5px;
            }
            #device4{
                width: 20px;
                height: 5px;
                background-color: black;
                border-radius: 30%;
                position: absolute;
                bottom: 80px;
                right: -5px;
            }
            #device5{
                width: 20px;
                height: 5px;
                background-color: black;
                border-radius: 30%;
                position: absolute;
                bottom: 70px;
                right: -5px;
            }
            #device6{
                width: 20px;
                height: 40px;
                background-color: black;
                border-radius: 20%;
                position: absolute;
                bottom: 10px;
                right: 30px;
            }
            #device7{
                width: 7px;
                height: 70px;
                background-color: black;
                border-radius: 30%;
                position: absolute;
                bottom: 10px;
                right: 37px;
            }
            #device8{
                width: 30px;
                height: 5px;
                background-color: black;
                position: absolute;
                bottom: 55px;
                right: 10px;
            }
            #device9{
                width: 30px;
                height: 5px;
                background-color: black;
                position: absolute;
                bottom: 45px;
                right: 10px;
            }
            #device0{
                width: 30px;
                height: 5px;
                background-color: black;
                position: absolute;
                bottom: 35px;
                right: 10px;
            }
            #device11{
                width: 30px;
                height: 5px;
                background-color: black;
                position: absolute;
                bottom: 25px;
                right: 10px;
            }
            #device10{
                width: 20px;
                height: 50px;
                background-color: black;
                border-radius: 20%;
                position: absolute;
                bottom: 15px;
                right: -10px;
            }
            #plants1{
                width: 10px;
                height: 80px;
                background-color: black;
                border-radius: 30%;
                position: absolute;
                bottom: 30px;
                right: 20px;
            }
            #plants2{
                width: 10px;
                height: 60px;
                background-color: black;
                border-radius: 30%;
                position: absolute;
                bottom: 30px;
                right: 200px;
            }
            #plants3{
                width: 10px;
                height: 90px;
                background-color: black;
                border-radius: 30%;
                position: absolute;
                bottom: 30px;
                left: 7px;
            }
            #plants4{
                width: 10px;
                height: 80px;
                background-color: black;
                border-radius: 30%;
                position: absolute;
                bottom: 30px;
                right: 300px;
            }
            #plants5{
                width: 10px;
                height: 70px;
                background-color: black;
                border-radius: 30%;
                position: absolute;
                bottom: 30px;
                left: 50px;
            }
            #plants6{
                width: 10px;
                height: 70px;
                background-color: black;
                border-radius: 30%;
                position: absolute;
                bottom: 30px;
                left: 50px;
            }
            #plants7{
                width: 10px;
                height: 50px;
                background-color: black;
                border-radius: 30%;
                position: absolute;
                bottom: 30px;
                left: 200px;
            }
            #plants8{
                width: 10px;
                height: 70px;
                background-color: black;
                border-radius: 30%;
                position: absolute;
                bottom: 30px;
                left: 170px;
            }
            #plants9{
                width: 10px;
                height: 40px;
                background-color: black;
                border-radius: 30%;
                position: absolute;
                bottom: 30px;
                left: 290px;
            }
            #plants10{
                width: 10px;
                height: 60px;
                background-color: black;
                border-radius: 30%;
                position: absolute;
                bottom: 30px;
                left: 450px;
            }
            #plants11{
                width: 10px;
                height: 70px;
                background-color: black;
                border-radius: 30%;
                position: absolute;
                bottom: 30px;
                left: 400px;
            }
            #plants12{
                width: 10px;
                height: 80px;
                background-color: black;
                border-radius: 30%;
                position: absolute;
                bottom: 30px;
                left: 500px;
            }
            #plants13{
                width: 10px;
                height: 60px;
                background-color: black;
                border-radius: 30%;
                position: absolute;
                bottom: 30px;
                right: 590px;
            }
            #logo1{
                position:absolute;
                left: 450px;
                top: 140px;
            }
        </style>
    </head>
    <body>

        <div id="wrap">
            <audio autoplay id="audio">
                <source src="./The Mandalorian (1).mp3" type="audio/mp3">
            </audio>
            <div id="back" class="background">  
                <div id="ground1" class="background">
                    <div id="device1" class="background">
                        <div id="device2" class="background"></div>
                        <div id="device3" class="background"></div>
                        <div id="device4" class="background"></div>
                        <div id="device5" class="background"></div>
                        <div id="device6" class="background"></div>
                        <div id="device7" class="background"></div>
                        <div id="device8" class="background"></div>
                        <div id="device9" class="background"></div>
                        <div id="device11" class="background"></div>
                        <div id="device10" class="background"></div>
                        <div id="device0" class="background"></div>
                    </div>
                    <div id="plants1" class="background"></div>
                    <div id="plants2" class="background"></div>
                    <div id="plants3" class="background"></div>
                    <div id="plants4" class="background"></div>
                    <div id="plants5" class="background"></div>
                    <div id="plants6" class="background"></div>
                    <div id="plants7" class="background"></div>
                    <div id="plants8" class="background"></div>
                    <div id="plants9" class="background"></div>
                    <div id="plants10" class="background"></div>
                    <div id="plants11" class="background"></div>
                    <div id="plants12" class="background"></div>
                    <div id="plants13" class="background"></div>
                    <div id="grass1" class="background"></div>
                    <div id="grass2" class="background"></div>
                    <div id="grass3" class="background"></div>
                    <div id="grass4" class="background"></div>
                    <div id="grass5" class="background"></div>
                    <div id="grass6" class="background"></div>
                    <div id="grass7" class="background"></div>
                    <div id="grass8" class="background"></div>
                    <div id="grass9" class="background"></div>
                </div>
                <div id="sun" class="background">
                    <div id="mandoHead" class="character">
                        <div id="mandoMask" class="character">
                            <div id="mandoBody1" class="character">
                                <div id="mandoHand1" class="character"></div>
                                <div id="mandoHand2" class="character"></div>
                                <div id="mandoLegs1" class="character"></div>
                                <div id="mandoLegs2" class="character"></div>
                                <div id="mandoCloth1" class="character"></div>
                                <div id="mandoCloth2" class="character"></div>
                                <div id="mandoNeck" class="character"></div>
                                <div id="mandoEyes" class="character"></div>
                                <div id="kid1"></div>
                                <div id="rifle1" class="character">
                                    <div id="rifle2" class="character"></div>
                                    <div id="rifle3" class="character"></div>
                                    <div id="rifle4" class="character"></div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div id = "fly2" class="triangle triangle-up"></div>
                    <div id = "fly1"class="triangle triangle-up"></div>
                    <div id = "fly3"class="triangle triangle-up"></div>
                    <div id = "fly4"class="triangle triangle-up"></div>
                    <div id="sun2" class="background"></div>
                </div>
            </div>
            <div id="trees" class="background"></div>
            <div id="ground2" class="background"></div>
            <div id="ground3" class="background"></div>
            <div id="grass" class="background"></div>
            <div id = "fly1"class="triangle triangle-up"></div>
            <div id="logo1">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b6/Red-Dead-Redemption-Logo.svg/640px-Red-Dead-Redemption-Logo.svg.png">
            </div>
        </div>
        <script></script>
    </body>
</html>
