<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
    

</head>
<style>
    @import url('https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap');
</style>
<body>
    <div class="header">
        <div class="marquee">
            <marquee>Rock, Paper, Scissors...Shoot! The Game Is First To Five Wins.</marquee></div>
    </div>
    <div class="middle">
        <div class="left">
            <div class="text">
                Your Score
            </div>
            <div class="progressBar">
                <div id="leftBar" class="leftFiller">

                </div>
            </div>
        </div>

        <div class="centerScreen">
            <div class="choices">
            <div class="option1">
                <button class="rock">
                    <img id="rock" class="pic"src="rock-paper-scissors-g62bff4504_1280.png" alt="rocks">
                    <p>Rock</p>
                </button>
            </div>
            <div class="option2">
                <button class="paper">
                    <img id="paper" class="pic" src="rock-paper-scissors-ga9d22e8bf_1280.png" alt="paper">
                    <p>Paper</p>
                </button>
            </div>
            <div class="option3">
                <button class="scissor">
                    <img id="scissor" class="pic" src="rock-paper-scissors-gd3927188d_1280.png" alt="scissors">
                    <p>Scissor</p>
                </button>
            </div>
            </div>
            <div class="faceOff">
                <div>Choose your move above to begin!</div>
            </div>
        </div>
        
        <div class="right">
            <div class="text">
                Computer Score
            </div>
            <div class="progressBar">
                <div id="rightBar" class="rightFiller">
                    
                </div>
            </div>
        </div>
    </div>
    <div class="bottom">
        
    </div>
    <script src="myScript1.js"></script>
</body>
</html>
