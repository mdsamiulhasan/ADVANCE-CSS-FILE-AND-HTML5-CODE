# ADVANCE-CSS-FILE-AND-HTML5-CODE


////////////advance css/////////////////
body {
    padding: 0;
    margin: 0;
    background: whitesmoke;

}
round{
             background:yellowgreen;
             padding:20px;
             width: 200px;
             height:150px;
             text-emphasis: none;
             text-align: center;
             padding-top:50px;
             margin-top: 50px;
             border-radius: 50px;


        }
        .round2{
            background-color:red;
            width: 200px;
            height: 150px;
            padding: 20px;
            margin-top: 50px;
            border-radius: 50px;
            text-align: center;
            padding-top:50px;

        }
        .round3{
            border-radius: 50px;
            background-image: url();
        }
    </style>

.border1 {
    height: 200px;
    width: 200px;
    padding: 20px;
    margin: 20px;
    border: 30px solid orange;
    font-size: 20px;
    /* border-image: url('image/image.jpg') 30 stretch; */
    border-image-source: url('image/image.jpg');
    border-image-slice: 30%;
    border-image-repeat: repeat round;

    border-image-width: 35px;
    border-image-outset: 20px;





}

h1 {
    padding: 30px;
    margin-top: 30px;
    margin-top: 50px;
    text-align: center;
    font-size: 40px;
    font-weight: bold;
    text-transform: uppercase;
}

p {
    padding: 30px;
    margin-top: 30px;
    margin-top: 50px;
    text-align: center;
    font-size: 25px;
    font-weight: bold;
    text-emphasis: none;
    top: 50%;
    left: 50%;


}

/* Here Show How to making Multiple background */


.multiple {

    padding: 20px;
    margin: 20px;
    width: 300px;
    height: 100px;
    border: 10px solid orange;
    text-align: center;
    background-image: url('image/image.jpg');
    background-repeat: no-repeat;
    background-position: left, right top;
    background-size: cover;
    background-origin: padding-box;
    /*content-box + border-box */


}


.multiple2 {

    padding: 20px;

    width: 300px;
    height: 100px;
    border: 10px solid green;
    text-align: center;

    background-origin: padding-box;
    /*content-box + border-box */
    background-clip: padding-box;
    /* For padding the text */
    background-color: yellow;
    border-radius: 50px;





}

/* Here i will show you gradient css */

.gradient {
    width: 300px;
    height: 200px;
    border: 1px solid red;
    border-radius: 5px solid orange;


    /* background-image: linear-gradient(to bottom, green, yellow); */

    background-image: radial-gradient(red 5%, yellow 60%, orange 40%);

}


.gradient2 {
    width: 300px;
    height: 200px;
    border: 1px solid red;
    border-radius: 5px solid orange;


    background-image: linear-gradient(to bottom, green, yellow);



}


.gradient3 {
    width: 300px;
    height: 200px;
    border: 1px solid red;
    border-radius: 5px solid orange;


    background-image: radial-gradient(closest-corner at 50px 50px, red, yellow, black);

    /* 
        background-image: radial-gradient(closest-side at 50px 50px, red, yellow, black); */



}


.gradient4 {
    width: 300px;
    height: 200px;
    border: 1px solid red;
    border-radius: 5px solid orange;


    background-image: radial-gradient(farthest-corner at 50px 50px, red, black, chocolate);



}


.gradient5 {
    width: 300px;
    height: 200px;
    border: 1px solid red;
    border-radius: 5px solid orange;




    background-image: radial-gradient(closest-side at 50% 50%, red, yellow, black);



}

.gradient6 {
    width: 300px;
    height: 300px;
    border: 1px solid red;
    border-radius: 5px solid orange;



    background-image: repeating-radial-gradient(black, red 10%, yellow 15%);



}


/* Here i will show you about text shadow effect in css */
p.shadow {
    width: 300px;
    height: 300px;
    border: 2px solid black;
    font-size: 50px;
    font-weight: bold;
    font-style: italic;
    color: pink;
    text-shadow: -1px 0px blue, 0 1px blue, 0 -4px navy;
}

p.shadow1 {
    width: 300px;
    height: 300px;
    border: 2px solid black;
    font-size: 30px;
    padding: 15px;
    background: coral;
    text-align: center;
    box-shadow: 10px 10px 5px grey, 20px 10px 10px blue;




}

.card {
    width: 250px;
    text-align: center;
    box-sizing: border-box;
    box-shadow: 0 5px 10px rgba(0, 0, 0, 0.1), 0 6px 20px rgba(0, 0, 0, 0.19);

}

.hello {
    background-color: gray;
    padding: 10px;
    color: white;
    font-size: 40px;

}

.cards {
    padding: 10px;

    background: orangered;
    color: white;
    font-size: 50px;

}

/* text shadow system overflow */

.text {
    width: 200px;

    border: 2px solid yellowgreen;
    border-radius: 5px;
    text-align: center;
    white-space: nowrap;
    margin-bottom: 50px;
    overflow: hidden;





}

.text:hover {
    overflow: visible;
}

.text1 {
    width: 300px;


    border: 2px solid yellowgreen;
    border-radius: 5px;
    text-emphasis: none;
    text-align: center;
    word-break: word-break;
    text-shadow: 4px -3px green, 0 2px red, 4px 4px;
    text-transform: capitalize;
    writing-mode: horizontal-tb;



}

.transform {
    border-radius: 2px solid rgb(163, 163, 100);
    width: 200px;
    height: 200px;
    background: green;
    text-align: center;
    transform: translate(50px, -30px, 50px);
    transform: rotate(20deg);
    ;
    transform: scaleX(30deg);
    transform: skew(-40deg, 30deg);
    transform-origin: 40% 50%;




}

.transform3d {


    width: 200px;
    height: 200px;
    background: crimson;
    text-align: center;
    transform: rotateX(60deg);
    perspective: 1000px;

}

.c {
    overflow: hidden;
    border: 2px solid black;
    width: 200px;
    height: 100px;
    background-color: burlywood;
    transform: rotate(-60deg);
    transform-style: preserve-3d;
    transform: rotateY(-60deg);

}

.c:hover {
    overflow: visible;
    clear: both;

}

.b {
    position: absolute;
    width: 300px;
    height: 200px;
    margin: 50px;
    border: 1px solid black;
    transform: rotate(60deg);
    transform-style: preserve-3d;



}

.c {
    padding: 40px;
    position: absolute;
    border: 1px solid black;
    background-color: yellow;
    transform: rotateY(-60deg);




}

.backface {
    width: 200px;
    height: 200px;
    margin: 20px;
    border: 1px solid violet;
    margin-bottom: 50px;
    text-emphasis: none;
    text-align: center;
    background-color: goldenrod;
    color: white;
    transform: rotateY(180deg);
    /* backface-visibility: hidden; */

}

.backface1 {
    width: 200px;
    height: 200px;
    position: absolute;
    margin: -150px;
    padding: 20px;
    background: coral;

    margin-top: 100px;
    left: 50%;
    left: 50%;



}

.backface2 {
    width: 100%;
    height: 100%;
    position: absolute;
}

.frontpage,
.backpage {
    width: 100%;
    height: 100%;
    position: absolute;
    background: yellow;
    backface-visibility: hidden;
    font-size: 50px;
    line-height: 300px;
    transition: transform 1s;
}

.backpage {
    background: orange;
    color: cyan;
    transform: rotateX(180deg);
    transition: transform 1s;
}

.backface:hover,
.backface1 {
    transform: rotateY(180deg);
}


/* 
Transtion css color set */

.transition {
    width: 300px;
    height: 300px;
    /* top: 50%;
    left: 50%; */
    margin-top: 50px;

    background-color: red;
    border: 2px solid black;
    padding: 20px;
    margin-top: 600px;
    border-radius: 50%;





}

.transition:hover {
    width: 300px;
    transition: width 2s;
}

/* transiton part3 */
.transition2 {
    width: 200px;
    height: 200px;
    margin: 50px;
    border: 1px solid black;
    transition: width 2s;
    background-color: rgb(189, 30, 210);
    color: white;
    border-radius: 50%;
    font-weight: bold;

}

div:hover {
    width: 300px;
}

.id1 {
    transition-timing-function: linear;
    transition-delay: 2s;
}

.id2 {
    transition-timing-function: ease;
}

.id2 {
    transition-timing-function: ease-in;
}

.id2 {
    transition-timing-function: ease-out;
}

.id2 {
    transition-timing-function: ease-in-out;
}

.id1 {
    transition-timing-function: cubic-bezier(1. 0.4, 0.54, 0.34);
}


/* 
   css animation system  */

.animation {
    width: 200px;
    height: 200px;
    border: 2px solid black;
    text-align: center;
    background-color: darkblue;
    color: white;
    animation-name: eg;
    animation-duration: 4s;
    margin-top: 300px;
    margin-bottom: 250px;
    animation-delay: 1s;
    position: relative;
    animation-iteration-count: 4;
    animation-direction: alternate;




}

@keyframes eg {
    from {
        background-color: darkblue;
        font-size: 20px;
    }

    to {
        background-color: yellow;
        font-size: 30px;
        color: brown;

    }

    0% {
        background-color: red;
        font-color: whitesmoke;
        font-size: 30px;
        left: 0px;
        top: 0px;
    }

    25% {
        background-color: rgb(94, 255, 0);
        font-color: whitesmoke;
        font-size: 30px;
        left: 200px;
        top: 0;
    }

    50% {
        background-color: rgba(255, 0, 0, 0.274);
        font-color: whitesmoke;
        font-size: 30px;
        top: 200px;
        left: 200px;
    }

    75% {
        background-color: rgb(46, 82, 25);
        font-color: whitesmoke;
        font-size: 30px;
        top: 200px;
        left: 0px;
    }

    100% {
        background-color: rgb(46, 82, 25);
        font-color: whitesmoke;
        font-size: 30px;
        top: 0px;
        left: 0px;
    }
}

/* tooltip working system css*/

.t1{
    background-color:yellow;
    padding:15px 32px;
    text-align:center;
    text-transform: capitalize;
    text-emphasis: none;
    display: inline-block;
    position: relative;
    background-color: yellowgreen;


}
.t1 .t2{
    color:whitesmoke;
    padding:5px 0;
    width: 120px;
    background:black;
    position: absolute;
    text-align: center;
    border-radius: 6px;
    z-index: 1;
    margin-bottom: 100px;
    margin-right:35px;




    

}

/* image system of css */
img{
    width:200px;
    margin-top: 100px;
    height: 200px;
    border-radius: 50%;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    transition:1 ease-in;
    overflow: hidden;
    object-fit: cover;


}

/* css of button */


.btn1{
    color: white;
    background-color:red;
    padding:10px;
    border-radius: 15px;
    text-emphasis: none;
    text-decoration: none;
    display: inline-block
  0

}

.btn2 {
    color: white;
    background-color: green;
    padding: 10px;
    border-radius: 15px;
    display: inline-block;
    text-decoration: none;
    font-size:20px;
    padding: 10px;


}
.btn3 {
    color: white;
    background-color: violet;
    padding: 10px;
    border-radius: 15px;
    display: inline-block;
    text-decoration: none;
    font-size: 20px;


}
.btn4 {
    color: white;
    background-color: yellowgreen;
    padding: 10px;
    border-radius: 15px;
    display: inline-block;
    text-decoration: none;
    font-size: 20px;

    cursor: pointer;
    text-align: center;


}

/* pagination css */

.pagination {
    display: inline-block;
}

.pagination a{
    color: black;
    padding:10px;
   border: 2px solid black;
}

.pagination a.active {
     color: black;
     background: yellow;
}

.pagination a:hover:not(.active) {
    background-color: blueviolet;

}

/* 
multiple column system */

h4{
    font-size: 20px;
    column-count: 3;
    column-gap: 60px;
    column-rule-style: dashed;
    column-rule-color: brown;
    column-span: all ;
}

h6{
    background:red;
    font-size: 15px;
    clear: both;
    color:white;

}
h3{
    width: 300px;
    height:300px;
    padding:20px;
    border: 2px solid brown;
    resize: horizontal;


}

h5{
    padding:20px;
    font-size: 20px;
    font-weight: bold;
    font-style:none;

    text-transform:capitalize;
    
}
:root{
    --main-color: red;
   --main-size:20px;
}

.font{
    margin: 20px;
    border: 1px soid red;
    outline:4px solid blue;
    outline-offset: 15px;
    background-color:var(--main-color);
    font-size: var(--main-size);
    

}


.font2{
    margin: 20px;
    border: 1px soid yellow;
    outline: 4px solid green;
    outline-offset: 15px;
     background-color:var(--main-color);
     font-size: var(--main-size);


}

/* flexbox css */

.flexbox{
    border: 2px solid red;
    padding:10px;
    display: flex;
    font-size: 30px;
    flex-direction: column-reverse;
    flex-wrap:wrap ;
    /* flex-flow: row wrap; */
    flex-wrap: column nowrap;
    justify-content: center;

}

body{
    background-color:coral;
}
@media screen and (min-width: 680px){
    body{
background-color:darkgreen;
    }
}











********************************************************
***********************HTML5**************************
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Border css style</title>

</head>

<body>
    <center>
        <p class="border1">Border sizing image</p>

        <h1>How to making multiple background</h1>
        <p class="multiple">Multiple background
            Multiple background
            Multiple background
            Multiple background
        </p>

        <h1>How to making multiple background system 2</h1>
        <p class="multiple2">Multiple background
            Multiple background
            Multiple background
            Multiple background
        </p>

        <div class="container">
            <h1>Type of Gradient css</h1>

            <p class="gradient">CSS gradient</p>

        </div>

        <div class="container">
            <h1>Type of Gradient css</h1>

            <p class="gradient2">CSS gradient</p>

        </div>

        <div class="container">
            <h1>Type of Gradient css</h1>

            <p class="gradient3">CSS gradient</p>

        </div>

        <div class="container">
            <h1>Type of Gradient css</h1>

            <p class="gradient4">CSS gradient</p>

        </div>

        <div class="container">
            <h1>Type of Gradient css</h1>

            <p class="gradient5">CSS gradient</p>

        </div>
        <div class="container">
            <h1>Type of Gradient css</h1>

            <p class="gradient6">CSS gradient</p>

        </div>
    </center>


    <!-- css text shadow effect -->

    <h1>Css text shadow effect </h1>


    <center>
        <div class="container">
            <p class="shadow">text shadow and box shadow effect</p>
            <p class="shadow1">text shadow and box shadow effect</p>

        </div>
    </center>


    <center>
        <h1>Cards</h1>
        <div class="container">
            <div class="card">
                <div class="hello">
                    <h1>Hello World</h1>

                </div>
                <div class="cards">
                    8
                </div>
            </div>
        </div>

    </center>

    <!-- text overflow system -->


    <center>
        <div class="container">
            <h1>text shadow overflow system</h1>
            <p class="text"> Hello guys, Iam samiul Hasan</p>
        </div>
    </center>

    <center>
        <div class="container">
            <h1>text shadow 2</h1>
            <p class="text1">
                Hello guys, Iam samiul Hasan,Hello guys, Iam samiul hasan

                border: 2px solid yellowgreen;

                Hello guys, Iam samiul Hasan
                Hello guys, Iam samiul Hasan
            </p>
        </div>
    </center>


    <center>
        <h1>Web Fonts</h1>
    </center>

    <center>
        <div class="container">
            <h1>css 2d transform</h1>
            <p class="transform">Tranform system</p>
        </div>
    </center>


    <center>
        <h1>text transform 3d model</h1>
        <div class="container">
            <p class="transform3d">3D transform</p>
            <div class="c">
                3D
            </div>
        </div>
    </center>

    <center>
        <div class="b">

            <div class="c">

            </div>
        </div>
    </center>

    <!-- backspace visiblity show -->
    <br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
    <br><br><br><br><br><br>
    <center>
        <div class="backface">
            Backface visibility

        </div>
    </center>

    <center>
        <div class="backface1">
            <div class="backface2">
                <div class="frontpage">
                    Front Page
                </div>
                <div class="backpage">
                    Back page
                </div>
            </div>
        </div>
    </center>


    <!-- transition: transform 1s; -->
    <main>

        <div class="container">
            <div class="transition">

            </div>
        </div>
    </main>


    <center>

        <div class="transition2">
            Transition
            <div class="id1">
            </div>
            <div class="id2"></div>
            <div class="id3"></div>
            <div class="id4"></div>
        </div>
    </center>


    <!-- css animation system -->





    <center>
        <main class="animation">
            Iam samiul Hasan
        </main>
    </center>

    <!-- tooltip woking system -->



    <center>

        <main class="t1">
            Iam samiul Hasan Roxy
        <span class="t2">Tooltip next</span>
        </main>

    </center>




<!-- image sytstem -->





<center>
    <main>
        <img src="image/samiul.jpg" alt="samiul">
    </main>
</center>

<!-- now we will see making button -->


<center>
    <main>
        <button class="btn1">click1</button>
        <button class="btn2">click2</button>
        <button class="btn3">click3</button>
        <button class="btn4">click4</button>
    </main>
</center>



<br><br><br>
<h1>How to making paginantion</h1>
<center>
    <main class="pagination">
        <a href="#">&laquo;</a>
                <a href="#">1</a>
                        <a href="#">2</a>
                                <a href="#" class="active">3</a>
                                        <a href="#">4</a>
                                        <a href="">&raquo;</a>





    </main>

</center>


<h1>multiple column system</h1>



<center>
    <main>
    <h4>amar sonar bangla ami tomai valobasi.chirodin tomar akas tomar batas amar prane omai prane bajai basi sonar bangla mai tomai valo basi .oma fagune to tor amer bone gharen pagol kore .oma aghroane tor vora khete </h4>    
    </main>
</center>


<h6>Here i will show you paragraph system+</h6>

<center>
  <main>
      <h3>
        amar sonar bangla ami tomai valobasi.chirodin tomar akas tomar batas amar prane omai prane bajai basi sonar bangla mai
        tomai valo basi .oma fagune to tor amer bone gharen pagol kore .oma aghroane tor vora khete
      </h3>
  </main>
</center>


<h5>Outline offeset </h5>

<center>
    <main>
        <p class="font">Hey, How are you</p>
        <p class="font2">Hey, How are you</p>
    </main>
</center>

<center>
    <main>
        <h2>Flex box / Border Box</h2>
    </main>
   <div class="flexbox">1
   </div>
    <div class="flexbox">2
    </div>
    <div class="flexbox">3
    </div>
    <div class="flexbox">4
    </div>
</center>


<h1>Media screen set up</h1>

<main>
    <h1>youtube</h1>
    <h1>facebook</h1>
    <h1>whatsapp</h1>
    <h1>twitter</h1>
</main>

</body>

</html>
