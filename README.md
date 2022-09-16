<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@3.4.1/dist/css/bootstrap.min.css" integrity="sha384-HSMxcRTRxnN+Bdg0JdbxYKrThecOKuH5zCYotlSAcp1+c8xmyTe9GYg1l9a69psu" crossorigin="anonymous">
    <link rel="html" type="text" src="Project-min.html">
    <style>
        body{
            width:100%;
            height:100%;
            background-image:linear-gradient(120deg, red,rgb(255, 238, 0),green);
            background-repeat:no-repeat;
            background-size:100%;
            background-attachment:fixed;
            display:inline-block;
        }
        .header{
            margin-top:70px;
            font-family: cursive;
            background-size: 100%;
            text-align: center;
            background-image: linear-gradient(100deg, orange, white, green);
            background-repeat: no-repeat;
            background-position: center;
            width:100%;
            text-decoration: underline;
            border-radius: 50px;
        }
        .images{
            
            display: grid;
             grid-template-columns: 1fr 1fr 1fr 1fr;
             grid-auto-rows:300px;
             grid-column-gap: 10px;
             grid-row-gap:20px;
             text-align: center;  
          
        }
        img{
            width: 250px;
             height: 200px;
             object-fit:cover;
             margin-left: 50px;
             margin-top: 50px;
             border-radius: 50px;
        }
         .footer{
            margin-bottom: 20px;
            text-align: center;
            background-color:aqua;
            width: 100%;
            font-size: 25px;

         }
         .small{
             color:coral;
             text-align: right;
             font-size:25px;
         }
         .lead{
             color:navy;
             text-align: right;

         }
         .lead h4{
             font-size: 20px;
         }
         .img-6{
             margin-left: 10px;
         }
         .name{
             color: red;
             background: white;
             border-radius: 30px;
             width:200px;
             align-items: center;
             margin-left: 90px;
             margin-top: 10px;
         }
         .row{
             text-align: center;
             width:100%;
         }
         h4{
             color:red;
         }
         .song1{
             margin-right:130px;
             color:black;
             font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
             margin-top: 60px;
             
         }
         .song{
             text-align: center;
             margin-bottom: 10px;
         }
         .img-1{
             margin-left:0px !important;
         }
        .img1{
            margin-left:58px;
            font-size: 14px;
        }
        .img2{
            margin-left:56px;
            font-size: 14px;
        }
        .img3{
            margin-left:58px;
            font-size: 14px;
        }
        .img4{
            margin-left:60px;
            font-size: 14px;
        }
        .img5{
            margin-left:58px;
            font-size: 14px;
        }
        .img6{
            margin-left:64px;
            font-size: 14px;
        }
        .img7{
            margin-left:58px;
            font-size: 14px;
        }
        .img8{
            margin-left:56px;
            font-size: 14px;
        }
        input[type=text],
    input[type=password] {
        width: 100%;
        padding: 12px 20px;
        margin: 8px 0;
        display: inline-block;
        border: 1px solid #ccc;
        box-sizing: border-box;
    }
    button {
        background-color: #4CAF50;
        color: white;
        padding: 14px 20px;
        margin: 8px 0;
        border: none;
        cursor: pointer;
        width: 100%;
    }
    button:hover {
        opacity: 0.8;
    }
    .cancelbtn {
        width: auto;
        padding: 10px 18px;
        background-color: #f44336;
    }
    .imgcontainer {
        text-align: center;
        margin: 24px 0 12px 0;
        position: relative;
    }
    .container {
        padding: 10px;
    }
    span.psw {
        float: right;
        padding-top: 16px;
    }
    .modal {
        display: none;
        position: fixed;
        z-index: 1;
        left: 0;
        top: 0;
        width: 110%;
        height: 100%;
        overflow: auto;
        background-color: rgb(0, 0, 0);
        background-color: rgba(0, 0, 0, 0.4);
        padding-top: 60px;
    }
    .modal-content {
        background-color: #fefefe;
        margin: 5% auto 15% auto;
        border: 1px solid #888;
        width: 80%;
    }
    .close {
        position: absolute;
        right: 25px;
        top: 0;
        color: #000;
        font-size: 35px;
        font-weight: bold;
    }
     
    .close:hover,
    .close:focus {
        color: red;
        cursor: pointer;
    }
    .animate {
        -webkit-animation: animatezoom 0.6s;
        animation: animatezoom 0.6s
    }
     
    @-webkit-keyframes animatezoom {
        from {
            -webkit-transform: scale(0)
        }
        to {
            -webkit-transform: scale(1)
        }
    }
     
    @keyframes animatezoom {
        from {
            transform: scale(0)
        }
        to {
            transform: scale(1)
        }
    }
     
    @media screen and (max-width: 300px) {
        span.psw {
            display: block;
            float: none;
        }
        .cancelbtn {
            width: 100%;
        }
    }

        
    </style>

</head>
<body>
    <div class="col-md-12 col-sm-6">
        
    <nav class="navbar navbar-inverse navbar-fixed-top">
        <div class="container-fluid">
            <div class="navbar-header">
                <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#mynavbar">
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>

                </button>
                <a href="#"  class="navbar-brand" >Welcome</a>
            </div>
            <div class="collapse navbar-collapse" id="mynavbar">
            <ul class="nav navbar-nav">
                <li class="active"><a href="#" >
                    <i class="glyphicon glyphicon-home">Menu</i> </a>
                </li>
                <li><a target="blank" href="https://traveltriangle.com/blog/famous-historical-places-in-india/">
                    <i class="	glyphicon glyphicon-zoom-in"></i>
                    Places</a>
                </li>
                <li class="disabled"><a href="#"><i class="glyphicon glyphicon-earphone"></i> Book now</a></li>
            </ul>
            <ul class="nav navbar-nav navbar-right">
                <li><a href="#">
                    <i class="glyphicon glyphicon-user"></i> 
                    About</a>
                </li>
                
                <li>
                    <a target="blank" onclick="document.getElementById('id01').style.display='block'" style="width:auto;">Login</a>
 
                    <div id="id01" class="modal">
                 
                        <form class="modal-content animate" action="/action_page.php">
                            <div class="imgcontainer">
                                <span onclick="document.getElementById('id01').style.display='none'" class="close" title="Close Modal">&times;</span>
                            
                            </div>
                 
                            <div class="container">
                                <label><b>Username</b></label>
                                <input type="text" placeholder="Enter Username" name="uname" required>
                 
                                <label><b>Password</b></label>
                                <input type="password" placeholder="Enter Password" name="psw" required>
                 
                                <button type="submit">Login</button>
                                <input type="checkbox" checked="checked"> Remember me
                            </div>
                 
                            <div class="container" style="background-color:#f1f1f1">
                                <button type="button" onclick="document.getElementById('id01').style.display='none'" class="cancelbtn">Cancel</button>
                                <span class="psw">Forgot <a href="#">password?</a></span>
                            </div>
                        </form>
                    </div>
                 
                    <script>
                        var modal = document.getElementById('id01');
                        window.onclick = function(event) {
                            if (event.target == modal) {
                                modal.style.display = "none";
                            }
                        }
                    </script>
                </li>

                <li><a href="#">
                    <i class="glyphicon glyphicon-share">
                    </i> Log out</a>
                </li>
            </ul>
        </div>
        </div>
    </nav>

    <div class="header" data-toggle="collapse" data-target="#box"><h1>Historical Places In India</h1>
    </div>
    <div id="box" class="collapse">
<p style="text-align:center; color:white;">
    1. Taj mahal<br>
    Build by: Shah Jahan in 1648 located in Agra, delhi.
    <br><br>
    2.Agra fort <br>
    Build by :Akbar in 1565 located in Uttar pradesh.
    <br><br>
    3.Red Fort<br>
    construced when shah jahan shifted from agra <br>to delhi and then it was known as Qila-e-Mubarak <br>in the time of 1638 to 1648.<br><br>
    4.Qutub Minar<br>
    Its name from Qutb-ud-din Aibak who was the first<br> Muslim ruler of North India and Build in 1193.<br><br>
    5.Sanji stupa<br>
    Build by:Lord Asoka in 3rd century for emperior Ashoka.
    <p><h4 style="color:black; text-align: center;">To see more click places and Images for more details..</h4></p>

</p>

    </div>
    <div class="images">
        <!--
            
          -->
          <div>
              <a id="maha" href="https://en.wikipedia.org/wiki/Group_of_Monuments_at_Mahabalipuram" class="img-1">
                  <img src="https://img.traveltriangle.com/blog/wp-content/uploads/2017/08/mahabalipuram-400x229.jpg">
              </a>
                  <div class="name"> Mahabalipuram temple</div>
                  <p class="img1">The Group of Monuments at Mahabalipuram, 
                    <a href="https://en.wikipedia.org/wiki/Group_of_Monuments_at_Mahabalipuram">See more...</a></p>
          </div>
        <div>
            <a target="blank" href="https://en.wikipedia.org/wiki/Agra_Fort" class="img-2">
            <img src="https://th.bing.com/th/id/OIP.irQ69RJCqKrsrfFjZPXe5wHaFk?w=262&h=197&c=7&r=0&o=5&pid=1.7">
        </a>
        <div class="name"> Agra-Fort</div>
        <p class="img2">This fort was include in one of sherlock Holme's cases:
            <a href="https://en.wikipedia.org/wiki/Agra_Fort">See more...</a></p>
    </div>

        <div>
            <a target="blank" href="https://en.wikipedia.org/wiki/Humayun%27s_Tomb" class="img-3">
            <img src="https://img.traveltriangle.com/blog/wp-content/uploads/2019/02/Humayun%E2%80%99s-Tomb-Delhi-400x267.jpg">
        </a>
        <div class="name"> Humayun's Tomb</div>
        <p class="img3">A beautiful synthesis of Indian and Persian architecture, Humay: <a href="https://en.wikipedia.org/wiki/Humayun%27s_Tomb">see more...</a></p>
    
    </div>

        <div>
            <a target="blank" href="https://en.wikipedia.org/wiki/Khajuraho_Group_of_Monuments" class="img-4">
            <img src="https://img.traveltriangle.com/blog/wp-content/uploads/2019/02/Khajuraho-Temples-Madhya-Pradesh-400x267.jpg">
        </a>
        <div class="name"> Khajuraho Temple</div>
        <p class="img4">Khajuraho has always been through of as the pla: <a href="https://en.wikipedia.org/wiki/Khajuraho_Group_of_Monuments">see more...</a></p>
    
    </div>

        <div>
            <a target="blank" href="https://en.wikipedia.org/wiki/Mahabodhi_Temple" class="img-5">
            <img src="https://img.traveltriangle.com/blog/wp-content/uploads/2019/02/Mahabodhi-Temple-Bodh-Gaya-400x261.jpg">
        </a>
        <div class="name"> Mahabodhi-Temple</div>
        <p class="img5">The Bodhi tree is the: <a href="https://en.wikipedia.org/wiki/Mahabodhi_Temple">see more...</a></p>
    
    </div>

        <div>
            <a target="blank" href="https://en.wikipedia.org/wiki/Taj_Mahal" class="img-6">
            <img src="https://img.traveltriangle.com/blog/wp-content/uploads/2017/07/Agra1.jpg">
        </a>
        <div class="name"> Taj-Mahal</div>
        <p class="img6">This opulent white marble,
            <a href="https://en.wikipedia.org/wiki/Taj_Mahal">See more...</a></p>
    
        </div>

        <div><a target="blank" href="https://en.wikipedia.org/wiki/Golden_Temple" class="img-7">
            <img src="https://img.traveltriangle.com/blog/wp-content/uploads/2019/02/Golden-Temple-400x267.jpg">
        </a><div class="name"> Golden-Temple</div>
        <p class="img7">One of the most famous Guru <a href="https://en.wikipedia.org/wiki/Great_Living_Chola_Temples">see more...</a></p>
    
    
    </div>

        <div>
            <a target="blank" href="https://en.wikipedia.org/wiki/Great_Living_Chola_Temples" class="img-8">
            <img src="https://www.bing.com/th?id=OIP.CQbEsKMwYrphq-TQWO9wkQHaFh&w=136&h=106&c=8&rs=1&qlt=90&o=6&pid=3.1&rm=2">
        </a>
        <div class="name"> Chola-Temple</div>
        <p class="img8">Raja raja cholan was insp <a href="https://en.wikipedia.org/wiki/Great_Living_Chola_Temples">see more...</a></p>
       
    </div>
    </div>

    <div class="row">
        <div class="col-md-12">
            
    <div class="song">
        <h4 class="song1">National Anthom:</h4>
        <audio controls>
           <source src="http://web.archive.org/web/20041019023748/http://www.navyband.navy.mil/anthems/ANTHEMS/India.mp3" type="audio/mpeg">
    
       </audio>    
    </div>
    
    <br>

       <div class="footer">"Design and Developed By (Name)"</div>
       
           </div>
    <script src="https://code.jquery.com/jquery-1.12.4.min.js" integrity="sha384-nvAa0+6Qg9clwYCGGPpDQLVpLNn0fRaROjHqs13t4Ggj3Ez50XnGQqc/r8MhnRDZ" crossorigin="anonymous"></script>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@3.4.1/dist/js/bootstrap.min.js" integrity="sha384-aJ21OjlMXNL5UyIl/XNwTMqvzeRMZH2w8c5cRVpzpU8Y5bApTppSuUkhZXN0VxHd" crossorigin="anonymous"></script>
    
</body>
</html>
