<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@3.4.1/dist/css/bootstrap.min.css" integrity="sha384-HSMxcRTRxnN+Bdg0JdbxYKrThecOKuH5zCYotlSAcp1+c8xmyTe9GYg1l9a69psu" crossorigin="anonymous">
    <style>
        body{
            width:100%;
            height:100%;
            background-image:linear-gradient(120deg, red,rgb(255, 238, 0),green);
            
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
        }
        .images{
            
            display: grid;
             grid-template-columns: 1fr 1fr 1fr 1fr;grid-auto-rows:300px;
             grid-column-gap: 0px;
             text-align: center;   
        }
        img{
            width: 250px;
             height: 200px;
             object-fit:cover;
             margin-left: 50px;
             margin-top: 50px;
             border-radius: 35px;
        }
        .song{
             text-align: center;
         }
         .footer{
            bottom: 20px;
            text-align: center;
            background-color:aqua;
            width: 100%;
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
         .img-6{
             margin-left: 20px;
         }
    </style>

</head>
<body>
    <nav class="navbar navbar-inverse navbar-fixed-top">
        <div class="container-fluid">
            <div class="navbar-header">
                <!-- to create a collapseable bar -->
                <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#mynavbar">
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>

                </button>
                <a href="#" class="navbar-brand">Welcome</a>
            </div>
            <div class="collapse navbar-collapse" id="mynavbar">
            <ul class="nav navbar-nav">
                <li class="active"><a href="#" >
                    <i class="glyphicon glyphicon-home">Menu</i>
                </a>
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
                <li><a target="blank" href="#sign">
                    <i class="glyphicon glyphicon-check"></i> Sign in
                 </a>
                </li>

                <div class="col-md-6">
                    <form id="sign">
                        <div class="form-group">
                            <label for="email" class="control-label">User email</label>
                            <input type="email" id="email" name="email" class="form-control" placeholder="Enter email ID">
                        </div>
                    </form>
                </div>
                <li><a href="#">
                    <i class="glyphicon glyphicon-share">
                    </i> Log out</a>
                </li>
            </ul>
        </div>
        </div>
    </nav>

    <div class="header"><h1>Historical Places In India</h1>
    </div>
    <div class="images">
        
        <div><a target="blank" href="https://en.wikipedia.org/wiki/Group_of_Monuments_at_Mahabalipuram" class="img1">
            <img src="https://img.traveltriangle.com/blog/wp-content/uploads/2017/08/mahabalipuram-400x229.jpg">
        </a>Mahabalipuram Temple</div>

        <div><a target="blank" href="https://en.wikipedia.org/wiki/Agra_Fort" class="img-2">
            <img src="https://th.bing.com/th/id/OIP.irQ69RJCqKrsrfFjZPXe5wHaFk?w=262&h=197&c=7&r=0&o=5&pid=1.7">
        </a>Agra-Fort</div>

        <div><a target="blank" href="https://en.wikipedia.org/wiki/Humayun%27s_Tomb" class="img-3">
            <img src="https://img.traveltriangle.com/blog/wp-content/uploads/2019/02/Humayun%E2%80%99s-Tomb-Delhi-400x267.jpg">
        </a>Humayun's Tomb</div>

        <div><a target="blank" href="https://en.wikipedia.org/wiki/Khajuraho_Group_of_Monuments" class="img-4">
            <img src="https://img.traveltriangle.com/blog/wp-content/uploads/2019/02/Khajuraho-Temples-Madhya-Pradesh-400x267.jpg">
        </a>Khajuraho Temple</div>

        <div><a target="blank" href="https://en.wikipedia.org/wiki/Mahabodhi_Temple" class="img-5">
            <img src="https://img.traveltriangle.com/blog/wp-content/uploads/2019/02/Mahabodhi-Temple-Bodh-Gaya-400x261.jpg">
        </a>Mahabodhi-Temple</div>

        <div><a target="blank" href="https://en.wikipedia.org/wiki/Taj_Mahal" class="img-6">
            <img src="https://img.traveltriangle.com/blog/wp-content/uploads/2017/07/Agra1.jpg" alt="">
        </a>Taj-Mahal</div>

        <div><a target="blank" href="https://en.wikipedia.org/wiki/Golden_Temple" class="img-7">
            <img src="https://img.traveltriangle.com/blog/wp-content/uploads/2019/02/Golden-Temple-400x267.jpg">
        </a>Golden-Temple</div>

        <div><a target="blank" href="https://en.wikipedia.org/wiki/Great_Living_Chola_Temples" class="img-8">
            <img src="https://img.traveltriangle.com/blog/wp-content/uploads/2019/02/chola-temples_23rd-oct-400x229.jpg">
        </a>Chola-Temple</div>
    </div>

    <div class="song">
        <audio controls>
           <source src="http://web.archive.org/web/20041019023748/http://www.navyband.navy.mil/anthems/ANTHEMS/India.mp3" type="audio/mpeg">
       </audio>    
       </div>

       <div class="footer">Thank you</div>
       <div class="lead">Designed By:</div>
       <div class="small">Nandha Gopal S</div>


    <script src="https://code.jquery.com/jquery-1.12.4.min.js" integrity="sha384-nvAa0+6Qg9clwYCGGPpDQLVpLNn0fRaROjHqs13t4Ggj3Ez50XnGQqc/r8MhnRDZ" crossorigin="anonymous"></script>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@3.4.1/dist/js/bootstrap.min.js" integrity="sha384-aJ21OjlMXNL5UyIl/XNwTMqvzeRMZH2w8c5cRVpzpU8Y5bApTppSuUkhZXN0VxHd" crossorigin="anonymous"></script>
    
</body>
</html>
