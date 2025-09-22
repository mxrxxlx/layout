<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Corrected Layout Recreation</title>
    <style>
        body {
            font-family: sans-serif;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background-color: #5d3fd3; 
            gap: 20px;
        }

        .name-banner {
            text-align: center;
            font-size: 1.5em;
            font-weight: bold;
            color: #fff; 
            margin-bottom: 20px;
        }

        .layout-container {
            display: flex;
            justify-content: center;
            align-items: flex-start;
            gap: 20px;
        }

        .container {
            display: flex;
            flex-direction: column;
            width: 300px;
            height: 330px; 
            padding: 10px;
            border: 2px solid #fff; 
            border-radius: 8px;
            background-color: #8a6de6; 
            box-sizing: border-box; 
        }

        .container h2 {
            text-align: center;
            margin: 0 0 10px 0;
            color: #fff; 
        }

        .box {
            border: 1px solid #ccc;
            background-color: #b9a4ed; 
            margin-bottom: 10px;
            border-radius: 4px;
        }
        
        
        #layout1 .top {
            height: 30px;
        }
        
        #layout1 .middle {
            display: flex;
            gap: 10px;
            flex-grow: 1; 
        }
        
        #layout1 .middle .left {
            width: 30%;
        }
        
        #layout1 .middle .right {
            width: 70%;
            display: flex;
            flex-direction: column;
            gap: 10px;
        }
        
        #layout1 .middle .right .right-top {
            height: 30px;
        }
        
        #layout1 .middle .right .right-bottom {
            flex-grow: 1; 
        }
        
        #layout1 .bottom {
            height: 30px;
            margin-bottom: 0;
        }

        #layout2 .top {
            height: 30px;
        }
        
        #layout2 .middle {
            display: flex;
            gap: 10px;
            flex-grow: 1; 
        }
        
        #layout2 .middle .middle-left,
        #layout2 .middle .middle-center,
        #layout2 .middle .middle-right {
            flex: 1;
        }
        
        #layout2 .bottom {
            height: 30px;
            margin-bottom: 0;
        }
        
        
        #layout3 .top-row,
        #layout3 .middle-row,
        #layout3 .bottom-row {
            display: flex;
            gap: 10px;
        }
        
        #layout3 .top-row {
            align-items: center;
        }
        
        #layout3 .top-row .circle {
            width: 40px;
            height: 40px;
            border-radius: 50%;
        }
        
        #layout3 .top-row .rect {
            flex-grow: 1;
            height: 30px;
            margin-bottom: 0;
        }
        
        #layout3 .middle-row {
            flex-direction: column;
            flex-grow: 1; 
            gap: 10px;
        }
        
        #layout3 .middle-row .small-rect {
            height: 30px;
            margin-bottom: 0;
        }
        
        #layout3 .middle-row .large-rect-container {
            display: flex;
            flex-grow: 1; 
            gap: 10px;
        }

        #layout3 .middle-row .large-rect {
            flex: 1;
            margin-bottom: 0;
        }

        #layout3 .bottom-row {
            align-items: center;
        }
        
        #layout3 .bottom-row .rect {
            flex-grow: 1;
            height: 30px;
            margin-bottom: 0;
        }
        
        #layout3 .bottom-row .circle {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            margin-bottom: 0;
        }
    </style>
</head>
<body>

    <div class="name-banner">Marielle Shanine Grace Castillo - IT201</div>

    <div class="layout-container">
        <div class="container" id="layout1">
            <h2>Layout 1</h2>
            <div class="box top"></div>
            <div class="middle">
                <div class="box left"></div>
                <div class="right">
                    <div class="box right-top"></div>
                    <div class="box right-bottom"></div>
                </div>
            </div>
            <div class="box bottom"></div>
        </div>

        <div class="container" id="layout2">
            <h2>Layout 2</h2>
            <div class="box top"></div>
            <div class="middle">
                <div class="box middle-left"></div>
                <div class="box middle-center"></div>
                <div class="box middle-right"></div>
            </div>
            <div class="box bottom"></div>
        </div>

        <div class="container" id="layout3">
            <h2>Layout 3</h2>
            <div class="top-row">
                <div class="circle box"></div>
                <div class="rect box"></div>
            </div>
            <div class="middle-row">
                <div class="box small-rect"></div>
                <div class="large-rect-container">
                    <div class="box large-rect"></div>
                    <div class="box large-rect"></div>
                </div>
            </div>
            <div class="bottom-row">
                <div class="box rect"></div>
                <div class="circle box"></div>
            </div>
        </div>
    </div>

</body>
</html>
