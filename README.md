Codepen.io/saamerm
For all my work on HTML
++++++++++++++++++++++++++++
https://www.w3.org/TR/2012/WD-html5-20121025/ Best source
==============================================
++++++++++++++++++++++++++++++++++++++++
http://www.w3schools.com/html/html_headings.asp Good source
============================
=================
Smashing HTML5
+++++++++++++++++++
# HTML5

<head>
    <title>Smashing HTML5!</title>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <!-- Bootstrap core CSS -->
    <link href="css/bootstrap.css" rel="stylesheet">
    <!-- Custom styles for this template -->
    <link href="css/styles.css" rel="stylesheet">
</head>
//Header should have (h1) the google search keywords. Googles algorithm is set to read that h1
//container sticks everything to the center -power of bootstrap
//Main semantic tags-DateTime, Author, Side, Main
/*
<body
main class container
header
a href="#"
h1 Smashing htmls 5
h5 html5 in the year 20199
/a
/header

nav class navbar navbar - default container -fluid
//Div tag Puts in a new line to avoid using 
<div class ="navbar-header">
<button type="button" class= "navbar-toggle collapsed" data-toggle="collapse..... aria-expanded="false">
<span class="sr-only">Toggle navigation</span>
<span class ="icon-bar"> </span>
<span class ="icon-bar"> </span>
<span class ="icon-bar"> </span>
</button>
<a class ="navbar-brand visible-xs" href="#">Menu</a>
</div>
*/
//_________________________________________________
<body>
    <main class="container">
        <!--Header-->
        <header>
            <a href="#">
                <h1>Smashing HTML5!</h1>
                <h5>HTML5 in the year<del>2022</del>2009</h5>
            </a>
        </header>

        <nav class="navbar navbar-default container-fluid">
        //3 different classes given to nav for bootstrap
            <!-- Brand and toggle get grouped for better mobile display -->
            <div class="navbar-header">
                <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1" aria-expanded="false">
                    <span class="sr-only">Toggle navigation</span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                </button>
                <a class="navbar-brand visible-xs" href="#">Menu</a>
            </div>
            <!-- Collect the nav links, forms, and other content for toggling -->
            <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
                <ul class="nav navbar-nav">
                    <li class="active"><a href="#">home</a></li>
                    //home-This is where you are now, may not be selectable
                    <li><a href="#">portfolio</a></li>
                    <li><a href="#">blog</a></li>
                    <li><a href="#">contact</a></li>
                </ul>
            </div>
        </nav>

        <!-- Main Content Sections-->
        <!--Featured Article">-->
        <section id="featured">
            <div class="row featured-article link-highlight-hover">
                <div class="col-xs-12 col-md-7">
                    <h3 class="primary-color">Featured Article</h3>
                    <h4 class="black-h4"><a href="#">HTML5 in Smashing Magazine!</a></h4>
                    <p>
                        Discover how to use Graceful Degradation and Progressive Enhancement techniques to achieve an outstanding, cross- browser
                        <a class="primary-color underline" href="#"> HTML5</a> and <a class="primary-color underline" href="#">CSS3</a>                        website today!
                    </p>
                </div>
                <div class=" col-xs-12 .col-sm-12 col-md-offset-1 col-md-4">
                    <img class="img-responsive" alt="Responsive image" src="https://media-mediatemple.netdna-ssl.com/wp-content/uploads/images/smashing-html5/files/images/temp/sm-logo.gif">
                    <div class="clear-fix clearfix"></div>
                </div>
            </div>
        </section>

        <!--Middle Content">-->
        <!--Article 1">-->
        <section id="main">
            <div class=" article fix-top-radius add-padding-top">
                <div class="row highlighter add-border">
                    <div class="col-md-3">
                        <p>10th October 2005
                            <br>By <a class="underline" href="#">Enrique Ramirez</a>
                        </p>
                    </div>
                    <div class="col-md-9">
                        <h4> <a href="#">This be the title</a></h4>
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque venenatis nunc vitae libero iaculis elementum. Nullam et
                            justo <a class="underline" href="#">non sapien</a> dapibus blandit
                            nec et leo. Ut ut malesuada tellus.
                        </p>
                    </div>
                </div>
            </div>
            <!--Article 2">-->
            <div class=" article add-padding-sides">
                <div class="row highlighter add-border ">
                    <div class="col-md-3">
                        <p>10th October 2005
                            <br>By <a class="underline" href="#">Enrique Ramirez</a>
                        </p>
                    </div>
                    <div class="col-md-9">
                        <h4> <a href="#">This be the title</a></h4>
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque venenatis nunc vitae libero iaculis elementum. Nullam et
                            justo <a class="underline" href="#">non sapien</a> dapibus blandit
                            nec et leo. Ut ut malesuada tellus.
                        </p>
                    </div>
                </div>
            </div>
            <!--Article 3">-->
            <div class="add-padding-bot article fix-bottom-radius">
                <div class="row highlighter">
                    <div class="col-md-3">
                        <p>10th October 2005
                            <br>By <a class="underline" href="#">Enrique Ramirez</a>
                        </p>
                    </div>
                    <div class="col-md-9">
                        <h4> <a href="#">This be the title</a></h4>
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque venenatis nunc vitae libero iaculis elementum. Nullam et
                            justo <a class="underline" href="#">non sapien</a> dapibus blandit
                            nec et leo. Ut ut malesuada tellus.
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!--Bottom Content & Footer-->
        <footer>
            <div>
                <!--BlogRoll">-->
                <div class="row list-highlight-hover list-link-highlight all-rows">
                    <div class="col-md-9">
                        <h4 class="primary-color blogroll">blogroll</h4>
                        <div class="row black-text">
                            <div class="col-md-4">
                                <ul class="remove-bullet row1">
                                    <li class="no-top-border"><a href="#">HTML5 Doctor</a></li>
                                    <li><a href="#">W3C</a></li>
                                    <li><a href="#">HTML5 Doctor</a></li>
                                    <li><a href="#">W3C</a></li>
                                    <li><a href="#">HTML5 Doctor</a></li>
                                    <li class="no-bot-border"><a href="#">W3C</a></li>
                                </ul>
                            </div>
                            <div class="col-md-4">
                                <ul class="remove-bullet row2">
                                    <li class="no-top-border"><a href="#">HTML5 Spec (working draft)</a></li>
                                    <li><a href="#">Wordpress</a></li>
                                    <li><a href="#">HTML5 Spec (working draft)</a></li>
                                    <li><a href="#">Wordpress</a></li>
                                    <li><a href="#">HTML5 Spec (working draft)</a></li>
                                    <li class="no-bot-border"><a href="#">Wordpress</a></li>
                                </ul>
                            </div>
                            <div class="col-md-4">
                                <ul class="remove-bullet row3">
                                    <li class="no-top-border"><a href="#">Smashing Magazine</a></li>
                                    <li><a href="#">Wikipedia</a></li>
                                    <li><a href="#">Smashing Magazine</a></li>
                                    <li><a href="#">Wikipedia</a></li>
                                    <li><a href="#">Smashing Magazine</a></li>
                                    <li class="no-bot-border"><a href="#">Wikipedia</a></li>
                                </ul>
                            </div>
                        </div>
                    </div>
                    <!--Social">-->
                    <div class="col-md-3">
                        <h4 class="primary-color social">social</h4>
                        <ul class="remove-bullet black-text row4">
                            <li class="no-top-border">
                                <a href="#"><img src="images/delicious.png"> delicious</a>
                            </li>
                            <li>
                                <a href="#"><img src="images/digg.png"> digg</a>
                            </li>
                            <li>
                                <a href="#"><img src="images/facebook.png"> facebook</a>
                            </li>
                            <li>
                                <a href="#"><img src="images/lastfm.png"> last.fm</a>
                            </li>
                            <li>
                                <a href="#"><img src="images/rss.png"> rss</a></li><a href="#">
                            </a><li class="no-bot-border"><a href="#">
                                </a><a href="#"><img src="images/twitter.png"> twitter</a>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
            <!--Bottom Article">-->
            <section>
                <div class="bottom-article">
                    <div class="row">
                        <div class="col-md-3 left-col">
                            <h5 class="primary-color link-highlight-hover"><a href="#">Smashing Magazine</a></h5>
                            <p>Amazing Magazine</p>
                        </div>
                        <div class="col-md-1 bot-img">
                            <img src="https://media-mediatemple.netdna-ssl.com/wp-content/uploads/images/smashing-html5/files/images/avatar.gif ">
                        </div>
                        <div class="col-md-8">
                            <p>
                                Smashing Magazine is a website and blog that offers resources and advice to web developers and web designers. It was founded
                                by Sven Lennartz and Vitaly Friedman.
                            </p>
                        </div>
                    </div>
                </div>
            </section>

            <!--Copy right">-->
            <p class="link-highlight-hover left-float">2005-2009 <a class="primary-color underline" href="#">Smashing Magazine</a>.</p>
        </footer>
    </main>

    <!-- Bootstrap core JavaScript
    ================================================== -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
    <script src="js/bootstrap.js"></script>


</body>
