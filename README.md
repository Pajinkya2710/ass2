# ass2
Create a portfolio website using HTML, CSS and BOOTSTRAP  
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exercise</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    
    <nav>
        <div class="logo">
            <p>HEADER</p>
        </div>
            <ul>
                <li><a href="#">HOME</a></li>
                <li><a href="#">ABOUT</a></li>
                <li><a href="#">SERVICES</a></li>
                <li><a href="#">CONTACT</a></li>
            </ul>
    </nav>

    <div class="content-item">
        <img src="images/pexels..jpg" alt="">

    </div>

</body>
</html>

<--CSS PART--->

*{
margin: 0px;
padding: opx;
box-sizing: border-box;
}

nav{
width: 100%;
height: 75px;
line-height: 75px;
padding: 0px 100px;
position: fixed;
background-image: linear-gradient(	#03182c, #061b2e);

}

nav .logo p{
    font-size: 30px;
    font-weight: bold;
    float: left;
    color: white;
    text-transform: uppercase;
    letter-spacing: 1.5px;
    cursor: pointer;

}

nav ul{
    float: right;
}
nav li{
    display: inline-block;
    list-style: none;
}
nav li a{
    font-size: 18px;
    text-transform: uppercase;
    padding: 30px;
    color: white;
    text-decoration: none;
}

nav li a:hover{
    color: rgb(32, 185, 40);
    transition: all 0.4s ease 0s;
}

.content-item img{
    width: 100%;
    height: 100vh;
    background-size: cover;
    background-position: center;

}
