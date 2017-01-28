# Bootstrap---January-2017
Cooking Blog
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <!-- The above 3 meta tags *must* come first in the head; any other head content must come *after* these tags -->
    <title><OodlesofYum></title>

    <!-- Bootstrap -->
    <link href="css/bootstrap.min.css" rel="stylesheet">
    <link href="bootstrap.min.js" rel="stylesheet">
    
    
    <!-- Custom CSS -->
     <link href="css/style.css" rel="stylesheet">  
       
    
    

    <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
    <!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
    <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/html5shiv/3.7.3/html5shiv.min.js"></script>
      <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
    <![endif]-->
  </head>


<!-- NAVBAR
================================================== -->
  <body>

   <!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>

     <!-- Include all compiled plugins (below), or include individual files as needed -->
    <script src="js/bootstrap.min.js"></script>
    <style type="text/css">
   body { background: #D7B49E !important; } /* Adding !important forces the browser to overwrite the default style applied by Bootstrap */
</style>

   <div class="navbar-wrapper">
      <div class="containerfluid">
        <nav class="navbar navbar-inverse navbar=full navbar-fixed-top">
          <div class="container">
            <div class="navbar-header">
              <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar" aria-expanded="false" aria-controls="navbar">
                <span class="sr-only">Toggle navigation</span>
                <span class="icon-bar"></span>
                <span class="icon-bar"></span>
                <span class="icon-bar"></span>
              </button>
              <!--<a class="navbar-brand" href="#">Project name</a>-->
              <img id="oodlesofyumlogo" src="img/Oodles of Yum White Letters Only.png" alt="oodlesofyum Logo" height="56" width="70">
            </div>
            <div id="navbar" class="navbar-collapse collapse">
              <ul class="nav pull-right navbar-nav">
                <li class="active"><a href="#">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#television">Contact</a></li>


                <li class="dropdown">
                <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">Recipes<span class="caret"></span></a>
                <ul class="dropdown-menu">
                <li><a href="#contact">Recipes</a></li>
                       </ul>
                </li>

                <li class="dropdown">
                  <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">Articles<span class="caret"></span></a>
                  <ul class="dropdown-menu">
                  <li><a href="#contact">Articles</a></li>
                    </ul>
                </li>


               
                <li class="dropdown">
                  <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">Social Media <span class="caret"></span></a>
                  <ul class="dropdown-menu">
                  <li><a href="#contact"><Social </a></li>
                    <li><a href="https://twitter.com/tzgu" target="blank">Twitter</a></li>
                    <li><a href="https://www.linkedin.com/in/rebs160" target="blank">Linkedin</a></li>
                    <li><a href="https://www.instagram.com/rebeccaleo17/" target="blank">Instagram</a></li>
                    <li><a href="https://www.youtube.com/channel/UCxIoNNGoWcLy6diKGS6YwGA" target="blank">YouTube</a></li>
                  </ul>
                </li>
                
                
                 
            </div>
          </div>
        </nav>

      </div>
    </div>





    <!-- Carousel
    ================================================== -->
      <div id = "myCarousel" class="carousel slide" data-ride="carousel">

      <ol class="carousel-indicators"> 
        <li data-target = "#myCarousel" data-slide-to  = "0" class = "active"></li>
        <li data-target = "#myCarousel" data-slide-to  = "1"></li>
        <li data-target = "#myCarousel" data-slide-to  = "2"></li>
        <li data-target = "#myCarousel" data-slide-to  = "3"></li>
      </ol>

      <div class="carousel-inner">

      <div class= "item active">
          <img src="img/RedCake.jpg" alt="Red Cake"  class = "img-responsive">  
          </div>


          <div class= "item">
          <img src="img/ToastedMarshmallowPiecopy.jpg" alt="Toasted Marshmallow Pie"  class = "img-responsive">  
        </div>

        <div class= "item">
          <img src="img/OrangeCake.jpg" alt="Orange Cake"  class = "img-responsive"> 
        </div>

        
        <div class= "item">
          <img src="img/MousseCake.jpg" alt="Mousse Cake"  class = "img-responsive">   
        </div>

       

      </div>
      <a class="left carousel-control" href = "#myCarousel" role = "button" data-slide = "prev">
        <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
      </a>
      <a class="right carousel-control" href = "#myCarousel" role = "button" data-slide = "next">
        <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
      </a>
   </div>
    

     
     <div class="container marketing">
      <!-- Three columns of text below the carousel -->
      <div class="row">
      <div class="col-lg-3"></div>
        <div class="col-lg-6">
         
          <h2><b>Oodles of Yum</b></h2>
          <p>My favorite thing to do since I was 10 is cook. This year I plan to do more YouTube videos with this website as well as my original one, peppermint love.</p> 

          <p>My New Year's resolutions are to spend more time researching desserts, I am continually seeking out new recipes and do research on ingredients as well</p> 

          <p>I welcome your suggestions on what kinds of desserts you would like to see. As always, pie remains my favorite, but sweet to me reflects the sweetness of life.</p> 

           <div class="form-group">
    &nbsp;
</div>
<div class="form-group">
    &nbsp;
</div>
</div>


      </div><!-- /.row -->
      <div class="col-lg-3"></div> 


    <!-- Marketing messaging and featurettes
    ================================================== -->
    <!-- Wrap the rest of the page in another container to center all the content. -->

    

      <!-- Three columns of text below the carousel -->
       <div class="container marketing">


       <div class="new-background">
      <!--<img class="featurette-image img-responsive center-block" src="img/LLSBlurBG.jpg">-->
    
<hr class="featurette-divider">
      
 <div class="container">
      <div id="pies" class="row featurette">
        <div class="col-md-7">
         <h2><b>Pies</b></h2>
         </style>
          <p>My absolute favorite thing to do is make a pie. There are an infinite number of pies can can create, from butterscotch pie and coconut cream pie to key lime pie.</p>          
        </div>
        <div class="col-md-5">
                 
        </div> 
        <img class="picture-padding thumbnail featurette-image img-responsive center-block" src="img/Butterscotchpie.png" height="640" width = "419" alt="Butterscotch Pie">
        </div>
        </div>
      </div>
    </div>
    
<hr class="featurette-divider">
    
       <div class="container">
      <div id="cakes" class="row featurette">
        <div class="col-md-7 col-md-push-5">
          <h2 class="featurette-heading"><b>Cakes</b></h2>
          <p>From white, strawberry, chocolate, coconut to Rhubarb, there is a cake for everyone.</p>          
        </div>
        <div class="col-md-5 col-md-pull-7">
          <img class="picture-padding thumbnail featurette-image img-responsive center-block" src="img/chocolate malt cake(my recipe)January2017copy.jpg" alt="Chocolate Malt Cake">
        </div>
      </div>
    </div>
    </div>

<hr class="featurette-divider">

    <div class="container">
    <div id="cookies" div class="row featurette">
        <div class="col-md-7">
          <h2><b>Cookies</b></h2>
          <p>You could spend an entire season just making Christmas cookies.</p>          
        </div>
        <div class="col-md-5">
          <img class="picture-padding thumbnail featurette-image img-responsive center-block" src="img/christmascookies.jpg" alt="Christmas Cookies">
        </div>
      </div>
    </div>
    </div>

<hr class="featurette-divider">
     

      <!-- FOOTER -->
      <div class = "container">
      <footer id = "footer">

    
      
        <p class="pull-right"><a href="#">Back to top</a></p>
        <div>&copy; 2017 oodlesofyum &middot; Made with<span id = "heart"></span> &hearts;
        by oodlesofyum </p>
      </footer>

    </div><!-- /.container -->

    
   


    <!-- Bootstrap core JavaScript
    ================================================== -->
    <!-- Placed at the end of the document so the pages load faster -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
    <script>window.jQuery || document.write('<script src="../../assets/js/vendor/jquery.min.js"><\/script>')</script>
    <script src="js/bootstrap.min.js"></script>
    <!-- Just to make our placeholder images work. Don't actually copy the next line! -->
    <script src="assets/js/vendor/holder.min.js"></script>
    <!-- IE10 viewport hack for Surface/desktop Windows 8 bug -->
    <script src="assets/js/ie10-viewport-bug-workaround.js"></script>
  </body>

  <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
    <script src="js/bootstrap.js"></script>
    <script src="js/Articles.js"></script>

</html>
