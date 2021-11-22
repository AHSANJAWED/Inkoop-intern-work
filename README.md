# Inkoop-intern-work

//HTML code

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <nav class="navbar">

        <div class="left-nav">
            <a href="#BookPad">BookPad.</a>
        </div>

        <ul class="nav-list">


            <li><a href="#Home">Home</a></li>
            <li><a href="#Categories">Categories</a>
            <li><a href="#Podcasts">Podcasts</a></li>

        </ul>
        <div class="right-nav">
            <input type="text" id="search" placeholder="search">
        </div>



    </nav>

    <div class="sentence">


        <div class="big-words">
            Home of 100,000+ <br>
            books and Podcasts

        </div>
        <div class="small-words">
            Get the lastest books and listen to the <br>
            latest Podcasts all in one place.

        </div>
        <div class="button-start">
            <button type="button"> Get Started

            </button>
        </div>

    </div>

    <div class="overlap-contain">

        <div class="img1">
            <img src="photo.PNG" alt="img" class="edit">
        </div>

        <div class="words">
            <p class="c1">Lorem, ipsum.</p>

            <p class="c2">Lorem ipsum dolor sit amet.</p>

            <p class="c3">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quis optio quidem, obcaecati cumque quam culpa ipsam repudiandae nobis voluptatibus!</p>
        </div>
        
        <div class="links">
        <ul class="social-media">
        <li> <a href="https://www.facebook.com/login/"><img src="facebook.png" alt="facebook"></a> </li>
        <li> <a href="https://twitter.com/login"><img src="twiter(1).png" alt="twiter"></a> </li> 
        <li> <a href="https://www.linkedin.com/"><img src="linkedin.png" alt="linkedin"></a> </li>     
        <li> <a href="https://www.instagram.com/"><img src="instagram.png" alt="instagram"></a> </li> 
        </ul>
        </div>


    </div>


    <div class="last-box">

        <div class="temp1"></div>

    <div class="speech">
       
            
           
        <img src="face1.PNG" alt="face" class="aj"><img src="face2.PNG" alt="face" class="aj"><img src="face 3.PNG " class="aj" alt="face"><img src="face 4.PNG" alt="face" class="aj"><img src="face 5.PNG" alt="face" class="aj"><img src="face 6.PNG" alt="face" class="aj"><img src="face 7.PNG" alt="face" class="aj"><img src="face 8.PNG" alt="face" class="aj"> 

        
    </div>

    <div class="temp2"></div>

</div>

<div class="em"></div>
</body>

</html>



................................................
//CSS

*{
    margin: 0;
    padding: 0;
}


.navbar{

    display: flex;

}


.nav-list{

    width: 60%;
    background-color:white;
    margin-top: 2%;
    display: flex;
    justify-content: center;
    align-items: center;

}

.nav-list li{

    list-style: none;
    padding: 23px;

    
} 

.nav-list li a{

    text-decoration: none;
    color: black;
    
} 

.left-nav a{
    text-decoration: none;
    color: black;
    font-size: x-large;
    font-weight: bold;
}
.right-nav{


    width: 20%;
    background-color:white;
    text-align: right;
    margin-right: 4%;
    margin-top: 2%;
    display: flex;
    justify-content: center;
    align-items: center;

}

.left-nav{

    width: 20%;
    background-color:white;
   
    margin-left: 4%;
    margin-top: 2%;
    display: flex;
    justify-content: center;
    align-items: center;
}

#search{
   border-radius: 11px;
   width: 11vw;
   background-color:rgb(247, 237, 237);
   
    
}


.big-words{
    display: flex;
justify-content: center;
align-items: center;
margin-top: 4%;
font-size: xxx-large;
font-weight: bold;

}

.small-words{

    display: flex;
justify-content: center;
align-items: center;
margin-top: 2%;
color: grey;

}


.button-start{
    
    display: flex;
justify-content: center;
align-items: center;
margin-top: 2%;

}

.button-start button{

    background-color:darkslateblue;
    color: white;
    width: 8vw;
height: 4vh;
}

.overlap-contain{

    display: flex;
    justify-content: center;
align-items: center;
margin-top: 4%;
margin-left: 4%;
margin-right: 4%;

}


.words{

    border: 2px solid whitesmoke;
    width: 27vw;
    z-index: 2;
    background-color: white;
    border-radius: 11px;
    
   

}

.c1{

    color:darkslateblue ;
    font-weight: bolder;
    font-size: larger;

}

.c2{
    color: black;
    font-weight: bolder;
    font-size: xx-large;
}

.img1{
    z-index: -1;
    width: 26vw;
    
}


.edit{
    border-radius: 11px;
}


.social-media li a img{

    width: 1vw;
    

}

.social-media{
   list-style: none;
    padding: 9px;
}

.aj{
    border-radius: 147px;
    padding: 4%;
}





.speech{

    background-color:darkslateblue ;
    border-radius: 44px;
   
}




.last-box{

    display: flex;
    margin-top: 4%;
    margin-left: 2%;
    margin-right: 2%;
}

.temp1{

    width: 10%;

}

.temp2{
    
    width: 10%;
}


.em{

    margin-top: 4%;
}

