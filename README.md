# BulbOn-Off
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bulb</title>
    <style>
        .light img {
            width: 200px;
            height: 200px;
            margin-left: 565px;
            margin-top: 170px;
        }

        .light figcaption {
            margin-left: 565px;
        }
    </style>
</head>

<body>
    <main class="light">
        <figure>
            <img src="bulboff.jpg" id="on" alt="" onclick="lighton()">
            <figcaption>Light On/Off</figcaption>
        </figure>

    </main>
    <script>

        const lighton = () =>{
            let bid=document.getElementById('on');
            if(bid.src.match('bulbon')){
                bid.src='bulboff.jpg';
            }else{
                bid.src='bulbon.jpg';
            }
        }


        // function lighton() {
        //     let bid = document.getElementById('on');
        //     if (bid.src.match('bulbon')) {
        //         bid.src = 'bulboff.jpg';
        //     } else {
        //         bid.src = 'bulbon.jpg';
        //     }
        // }
    </script>

</body>

</html>
