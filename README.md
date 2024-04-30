# project_with_pure_css_html


*{
    margin: 0px;
    padding: 0px;
  
    text-decoration: none;
 
}

.container{
    background-image: url(camera.jpeg);
    background-size: cover;
    background-repeat: no-repeat;
    height: 100vh;
    
    
}

.bar{
    color: white;
    display: flex;
    box-shadow: 2px 0px 2px rgb(213, 213, 213);
    width: 100%;
    height: 7%;
}



.mainbox{

    height: 100vh;
    box-shadow: 2px 2px 4px rgb(233, 230, 230);
    background-color: rgba(173, 170, 170, 0.1);
    width: 20%;
    position: absolute;
   
    left: -400px; 
    transition: all 0.1s ease-in;
}

.btn_one{
    position: absolute;
    left: 2%;
    top: 4%; 
    
    font-size: 3vh;
    color: rgb(189, 169, 169);
    transition: all 0.1s ease-in ;
}


.btn_two{
    position: absolute;
    left: 80%;
    top: 2%; 
    color: rgb(189, 169, 169);
    transition: all 0.1s ease-in ;
    font-size: 3vh;
   
}

.brand{
    position: absolute;
    left: 23%;
    top: 1%;
    font-size: 4vh;
    color: white;
}

 #check{
  
    display: none;
} 



.menu a{
    color: white;
    font-size: 1.2em;
    
}
.menu ul li i {
   
    color: white;
    font-size:1.3em ;
    line-height: 60px;
    
}



li i {
    padding: 0px 10px 8px 10px; 
}


.social{
    position: absolute;
    top: 85%;
    left: 30%;
   

}


.social a{
    margin: 5px;
    font-size: 20px;
    color: gray;
  
}

#check:checked ~ .btn_one i{
    opacity: 0;
}

#check:checked ~ .mainbox{
    left: 0px;
    } 


    .btn_one:hover{
        color: white;
        transform: scale(1.1);
    }

    .btn_two:hover{
        color: white;
        transform: scale(1.1);
    }

    
    .btn_two:active{
        background-color: rgb(150, 146, 146);
      
    }

    .btn_two:active{
        background-color: red;
      
    }

    .menu ul li:hover{
        box-shadow: 2px 0px 4px white;
    }

    .social i:hover{
        transition: all 0.7s ease-in;
      transform: scale(1.2);
      color: rgb(235, 233, 233);

    }
    










    @media(max-width:500px){


        *{
            margin: 0px;
            padding: 0px;
          
            text-decoration: none;
         
        }
        
        .container{
            background-image: url(camera.jpeg);
          
            background-size: cover;
            background-position: ;
            background-repeat: no-repeat;
            height: 100vh;
            
            
        }
        
        .bar{
            color: white;
            display: flex;
            box-shadow: 2px 0px 2px rgb(213, 213, 213);
            width: 100%;
            height: 7%;
        }
        
        
        
        .mainbox{
        
            height: 100vh;
            box-shadow: 2px 2px 4px rgb(233, 230, 230);
            background-color: rgba(173, 170, 170, 0.1);
            width: 50%;
            position: absolute;
           
            left: -400px; 
            transition: all 0.1s ease-in;
        }
        
        .btn_one{
            position: absolute;
            left: 2%;
            top: 4%; 
            
            font-size: 3vh;
            color: rgb(180, 178, 178);
            transition: all 0.1s ease-in ;
        }
        
        
        .btn_two{
            position: absolute;
            left: 80%;
            top: 2%; 
            color: rgb(180, 178, 178);
            transition: all 0.1s ease-in ;
            font-size: 3vh;
           
        }
        
        .brand{
            position: absolute;
            left: 4%;
            top: 2%;
            font-size: 2.7vh;
            color: rgb(252, 252, 252);
         
        }
        
         #check{
          
            display: none;
        } 
        
        
        
        .menu a{
            color: white;
            font-size: 1em;
            
        }
        .menu ul li i {
           
            color: white;
            font-size: 1.2em ;
            line-height: 60px;
            
        }
        
        
        
        li i {
            padding: 0px 10px 8px 10px; 
        }
        
        
        .social{
            position: absolute;
           bottom: 24%;
            left: 22%;
           
        
        }
        
        
        .social a{
            margin: 5px;
            font-size: 20px;
            color: gray;
          
        }
        
        #check:checked ~ .btn_one i{
            opacity: 0;
        }
        
        #check:checked ~ .mainbox{
            left: 0px;
            } 
        
        
            .btn_one:hover{
                color: white;
                transform: scale(1.1);
            }
        
            .btn_two:hover{
                color: white;
                transform: scale(1.1);
            }
        
            
            .btn_two:active{
                background-color: rgb(150, 146, 146);
              
            }
        
            .btn_two:active{
                background-color: red;
              
            }
        
            .menu ul li:hover{
                box-shadow: 2px 0px 4px white;
            }
        
            .social i:hover{
                transition: all 0.600ms ease-in;
              transform: scale(1.2);
              color: rgb(235, 233, 233);
        
            }
        }

        #html code

        <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="portfolio.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" integrity="sha512-SnH5WK+bZxgPHs44uWIX+LLJAJ9/2PkPKZ5QiAj6Ta86w+fsb2TkcmfRyVX3pBnMFcV7oQPJkl9QevSCWr3W6A==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <title>Document</title>
</head>
<body>
    
  <div class="container">

    
    <input type="checkbox" id="check">
  
    
<div class="btn_one">

    <label for="check">
        <i class="fa-solid fa-bars"></i>

    </label>

</div>
    
<div class="mainbox">
<div class="bar">


   <a href="#" class="brand">Apna college</a> 



<div class="btn_two">
    
    <label for="check">
        <i class="fa-solid fa-xmark"></i>
    </label>
    </div>

    
</div>


    <div class="menu">
    <ul>
        <li class="menulist">
            <i class="fa-solid fa-image"></i> 
            <a href="#">Gallery</a>
        </li>

        <li>
            <i class="fa-solid fa-arrow-up-right-from-square"></i>
            <a href="#">Shortcuts</a>
            </li>

        <li>
            <i class="fa-solid fa-hands-holding-circle"></i>
            <a href="#">Exhibits</a>  
        </li>

        <li>
            <i class="fa-regular fa-calendar-days"></i> 
            <a href="#">Events</a>
        </li>

        <li>
            <i class="fa-solid fa-store"></i>
           <a href="#">store</a>
            </li>

        <li>
            <i class="fa-solid fa-phone-flip"></i> 
            <a href="#">Contact</a>
        </li>

        <li>
            <i class="fa-regular fa-comments"></i>
            <a href="#">Feedback</a>
            </li>
    </ul>
</div>


<div class="social">

    <ul>
        <a href="https://r.search.yahoo.com/_ylt=Awrx_NNb1ytmLAQA_9K7HAx.;_ylu=Y29sbwNzZzMEcG9zAzEEdnRpZAMEc2VjA3Ny/RV=2/RE=1715358812/RO=10/RU=http%3a%2f%2fin.youtube.com%2f/RK=2/RS=aT4yL6MAhI3h_Hl2aHAlcBgBSfo-"><i class="fa-brands fa-youtube"></i></a>
        <a href="https://r.search.yahoo.com/_ylt=Awrx_vEM2CtmGwQAV3G7HAx.;_ylu=Y29sbwNzZzMEcG9zAzEEdnRpZAMEc2VjA3Ny/RV=2/RE=1715358989/RO=10/RU=https%3a%2f%2fwww.instagram.com%2f%3fhl%3den/RK=2/RS=MAhHohrvnCulMPKLSk3STIuNQUc-"><i class="fa-brands fa-instagram"></i></a>
        <a href="https://r.search.yahoo.com/_ylt=Awr1QSW42CtmgAQAt967HAx.;_ylu=Y29sbwNzZzMEcG9zAzEEdnRpZAMEc2VjA3Ny/RV=2/RE=1715359161/RO=10/RU=https%3a%2f%2ftwitter.com%2f%3flang%3den-in/RK=2/RS=yoxDZbaEdy7AnwDLhHqidxIx.us-    "><i class="fa-brands fa-twitter"></i></a>
    </ul>
</div>

</div>
  </div>

</body>
</html>
