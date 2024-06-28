<!DOCTYPE html>

<html>

<head>

    <title>Welcome Page</title>

    <style>

        body {

            background-color: pink;

            font-family: Arial, sans-serif;

            color: #333;

            margin: 0;

        }



        #letterPage {

            display: none;

        }



        .container {

            padding: 20px;

            text-align: center;

        }



        button {

            background-color: #ff69b4;

            color: white;

            border: none;

            padding: 10px 20px;

            font-size: 16px;

            cursor: pointer;

            border-radius: 5px;

        }



        button:hover {

            background-color: #ff1493;

        }



        h1 {

            color: #ff1493;

        }



        p {

            font-size: 18px;

        }

    </style>

    <script>

        function showLetterPage() {

            document.getElementById('welcomePage').style.display = 'none';

            document.getElementById('letterPage').style.display = 'block';

        }

    </script>

</head>

<body>

    <div class="container">

        <!-- Welcome Page -->

        <div id="welcomePage">

            <h1>Welcome my love</h1>

            <button onclick="showLetterPage()">Click here</button>

        </div>



        <!-- Letter Page -->

        <div id="letterPage">

            <h1>A Letter for You</h1>

            <p>para sa pinaka maldita,</p>

            <p>basaha ug tarung kay kapoy buhat HAHAHAHA:</p>

            <p>

                so i made this to show you my  progress , so mapansin man nimo diba na always ko tulog pag naa ko dira, its because ga learn ko ug ginatawag na html its about coding , and wala lang , my first basic coding is this one HAHAHAHA kong unsa ug asa nimo ni gina basa , i made it my self , the letter and pages each letter and number sa code gi learn nako and mao ni ang reasult hahaha mao ra iloveyou..

            </p>

            <p>With all my love,</p>

            <p>CARL PATRICK BABIA</p>

        </div>

    </div>

</body>

</html>
