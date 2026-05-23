<!DOCTYPE html>
<html>
<head>
    <title>Task 1 simple webpage</title>

    <style>
        body{
            font-family: Arial;
            margin: 0;
            background-color: #f4f4f4;
        }

        .header{
            background-color: #0056d6;
            color: white;
            text-align: center;
            padding: 25px;
        }

        .container{
            width: 80%;
            margin: auto;
            background: white;
            padding: 20px;
            margin-top: 20px;
            border-radius: 10px;
        }

        h2{
            text-align: center;
        }

        p{
            font-size: 20px;
        }

        img{
            width: 500px;
            border-radius: 10px;
            display: block;
            margin: auto;
        }

        a{
            color: blue;
            font-size: 20px;
        }

        .btn{
            background-color: green;
            color: white;
            border: none;
            padding: 15px 25px;
            font-size: 20px;
            border-radius: 8px;
            cursor: pointer;
        }

        .btn:hover{
            background-color: darkgreen;
        }

        #message{
            margin-top: 20px;
            padding: 15px;
            background-color: #dff0d8;
            color: #2e6b2e;
            border-radius: 8px;
            display: none;
            font-size: 22px;
        }

        .center{
            text-align: center;
        }
    </style>
</head>

<body>

  
        <h1 class="header">SIMPLE WEBPAGE</h1>
    

    <div class="container">

        <h2>About This Page</h2>

        <p>
            Rohit Sharma is an Indian international cricketer, former multi-format national captain, and the iconic opening batsman for the Mumbai 
            Indians in the Indian Premier League (IPL). Popularly known as the "Hitman", he is widely celebrated as one of the greatest limited-overs
             batsmen in cricket history, renowned for his effortless timing, explosive six-hitting capabilities, and astute leadership.
        </p>

        <img src="https://c.ndtvimg.com/2025-10/ce5hpbnc_rohit-sharma-afp_625x300_26_October_25.jpg?im=FeatureCrop,algorithm=dnn,width=1200,height=738">

        <br>

        <p>
            SEASON 19
            <a href="https://share.google/RJlnu2iyP2QKKsZ0p"
            Target="_blank">
                IPL link 
            </a>
        </p>

        <hr>

        <div class="center">
            

            <button class="btn" onclick="showMessage()">
                CLICK ME
            </button>

            <div id="message">
                HELLO ! YOU HAVE CLICK THE ABOVE BUTTON.
                WELCOME TO OUR WEBPAGE.
                Thank You Visit Again... .. . 
            </div>
        </div>

    </div>

    <script>
        function showMessage(){
            document.getElementById("message").style.display = "block";
        }
    </script>

</body>
</html>
