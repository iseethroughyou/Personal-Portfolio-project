# Personal-Portfolio-project
free code camp project
<!DOCTYPE html>
<html lang="en">

<head>

    <!--required meta tags -->
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scal=1">

    <!-- title -->
    <title>Porfolio</title>

    <!-- favicon -->
    <link rel="shortcut icon" href="img/favicon.ico">

    <!-- google fonts -->
    <link href="https://fonts.googleapis.com/css?family=Oswald:200,300,400,500,600,700" rel="stylesheet">

    <!-- fontawesome -->
    <link rel="stylesheet" href="css/font-awesome/css/font-awesome.min.css">

    <!-- bootstrap -->
    <link rel="stylesheet" href="css/bootstrap/bootstrap.min.css">

    <!-- style CSS -->
    <link rel="stylesheet" href="css/style.css">

    <!-- responsive CSS -->
    <link rel="stylesheet" href="css/responsive.css">

</head>

<body data-spy="scroll" data-target=".navbar-fixed-top" data-offset="91">

    <header>

        <nav class="navbar navbar-inverse navbar-fixed-top" role="navigation">

            <div class="container-fluid">
                <div class="portfolio-nav-wrapper">

                    <div class="navbar-header">

                        <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#portfolio menu">
                           <span class="sr-only">Toggle navigation</span>
                           <span class="sr-only">Toggle navigation</span>
                           <span class="sr-only">Toggle navigation</span>
                           <span class="sr-only">Toggle navigation</span>
                       </button>
                        <a class="navbar-brand" href="#home">
                        <img src="img/favicon.ico" alt="logo">
                        </a>
                    </div>
                    <div class="collapse navbar-collapse" id="portfolio-menu">
                        <ul class="nav navbar-nav">
                            <li><a class="smooth-scroll" href="#home">Home</a></li>
                            <li><a class="smooth-scroll" href="#about">My Work</a></li>
                            <li><a class="smooth-scroll" href="#contact">Contact Me</a></li>
                        </ul>

                    </div>
                </div>
            </div>

        </nav>


    </header>

    <!-- Home -->
    <section id="home" class="bg-parallax">

        <div id="home-cover">

            <div id="home-content-box">

                <div id="home-content-box-inner" class="text-center">

                    <div id="home-heading">

                        <h3>Welcome To My Portfolio</h3>
                        <p>I am an aspirant fledgling in the world of web design. I have simply begun to enter into these waters.</p>
                        </div>

                        <div id="home-btn" class="animated zoomIn">
                            <a class="btn btn-lg btn-general btn-white smooth-scroll" href="#about" role="button" title="My Work">My Work</a>
                        </div>
                    

                </div>

            </div>

        </div>

    </section>

    <!-- About -->
    <section id="about">

        <div class="content-box">

            <div class="content-title">
                <h3>My Work</h3>
                <div class="content-title-underline"></div>
            </div>
            <div class="container-fluid">

                <div class="row no-gutters wow animated fadeInUp" data-wow-duration="1s" data-wow-delay=".5s">

                    <div class="col-md-6 col-sm-4">
                        <div class="img-wrapper">
                            <a href="https://codepen.io/iseethroughyou/pen/vpzMMO" title="CodePen Tribute Page Project"> 
            <img src="img/codepen%20webpage%20project.jpg" class="img-responsive" alt="Work">
        </a>
                        </div>
                    </div>
                    <div class="col-md-6 col-sm-4">
                        <div class="img-wrapper">
                            <a href="http://127.0.0.1:54115/index.html" title="Modern Responsive Website Project, coursework completed by me on Udemy.com"> 
            <img src="img/Vesco%20Project%20Image.jpg" class="img-responsive" alt="Work">
        </a>
                        </div>
                    </div>
                </div>

            </div>

        </div>
        <!-- End Content Box -->

    </section>

    <footer>

        <div id="contact">

            <div class="container">

                <div class="row">

                    <div class="col-sm-6">
                        <div id="contact-left">

                            <h3>Contact Me</h3>
                            <p>I would love to provide further information about myself, my experience and training, and even my resume. Please feel free to contact me.<br>No spam, please.</p>
                            <div id="contact-info">

                                <address>
                                    <strong>Farha Shafiuddin</strong><br><p>777 Golden Brick Road<br>Mubaaraka Mountain, IL 7666667</p>
                                </address>
                                <div id="phone-fax-email">
                                    <p>
                                        <strong>Phone:</strong><span> (630) 555-5555</span><br>
                                        <strong> Fax:</strong><span> (224) 555-5555</span> <br>
                                        <strong> Email:</strong><span> fnshafi123@gmail.com</span>
                                    </p>
                                </div>

                            </div>
                            <ul class="social-list">
                                <li><a href="https://www.facebook.com/farah.shafiuddin" class="social-icon icon-white"><i class="fa fa-facebook"></i></a></li>
                                <li><a href="#" class="social-icon icon-white"><i class="fa fa-youtube-play"></i></a></li>
                                <li><a href="#" class="social-icon icon-white"><i class="fa fa-google-plus"></i></a></li>
                                <li><a href="https://github.com/iseethroughyou" class="social-icon icon-white"><i class="fa fa-github"></i></a></li>
                                <li><a href="https://www.freecodecamp.org/iseethroughyou" class="social-icon icon-white"><i class="fa fa-free-code-camp"></i></a></li>
                            </ul>
                        </div>

                    </div>

                    <div class="col-sm-6">
                        <div id="contact-right">

                            <form action="#">

                                <input type="text" name="full-name" placeholder="Full Name" class="form-control">
                                <input type="text" name="email" placeholder="Email Address" class="form-control">
                                <textarea rows="5" name="message" placeholder="Message..." class="form-control"></textarea>
                                <div id="send-btn">
                                    <a class="btn btn-lg btn-white" href="https://mail.google.com/mail/u/1/#inbox" role="button">SEND</a>

                                </div>
                            </form>
                        </div>
                    </div>

                </div>


            </div>




        </div>

        <div id="footer-bottom">
            <div class="container">
                <div class="row">
                    <div class="col-sm-6">

                        <div id="footer-copyrights">
                            <p>Copyrights &copy; 2018 All Rights Reserved</p>
                        </div>
                    </div>
                    <div class="col-sm-6 hidden-sm hidden-xs">

                        <div id="footer-menu">
                            <ul>
                                <li><a class="smooth-scrolling" href="#home">Home</a></li>
                                <li><a class="smooth-scrolling" href="#about">My Work</a></li>
                                <li><a class="smooth-scrolling" href="#contact">Contact Me</a></li>

                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <a href="#home" id="back-to-top" class="btn btn-sm btn-white btn-back-to-top smooth scroll hidden-sm hidden-xs" title="home" role="button"><i class="fa fa-angle-up"></i></a>

    </footer>


    <!-- jQuery -->
    <script src="js/jquery-3.3.1.min.js"></script>

    <!-- bootstrap JS -->
    <script src="js/bootstrap/bootstrap.min.js"></script>

    <!-- custom JS -->
    <script src="js/custom.js"></script>


</body>

</html>

/*=================================================================
                        DEFAULT VALUES:
                        
                        Font Family             : Oswald
                        
                        Rich Black              :#040404   (Text)
                        Timberwolf              :#d7d9ce   (buttons,Backgrounds)
                       Metallic Seaweed         :#0c7489   (Text with black background)
                        Midnight Green          :#13505b    (Heading)   
                        Blue-Green              :#119da4   (links, lines) 
                        
======================================================================*/

/* General CSS */

html,
body {
    height: 100%;
}

body {
    font-family: "Oswald", sans-serif;

}

h3 {
    text-transform: uppercase;
}

/*=================================================================
                            HOME
=================================================================*/

#home {
    height: 100%;

}

#home-cover {

    height: 100%;
    background-image: url("../img/web%20page%20background%20image.jpg");
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
}

#home-content-box {
    width: 100%;
    height: 100%;
    display: table;

}

#home-content-box-inner {
    display: table-cell;
    vertical-align: middle;
    /*text-align: center;*/
}

#home-heading h3 {
    color: #d7d9ce;
    font-size: 55px;
    font-weight: 700;
    margin: 20px 0 20px 0;

}

#home-heading p {
    font-size: 18px;
    font-weight: 400;

}


/*=================================================================
                            BUTTONS (Generic)
=================================================================*/

.btn-general {
    border-color: #d7d9ce;
    border-width: 2px;
    padding: 12px 26px 12px 26px;
    font-size: 16px;
    font-weight: 400;
    text-transform: uppercase;
    margin-top: 30px;
}

.btn-white {
    border-color: #d7d9ce;
    color: #d7d9ce;
}

.btn-white:hover,
.btn-white:focus {
    background-color: #d7d9ce;
    color: #119da4;
}

.btn-back-to-top {
    position: fixed;
    bottom: 20px;
    right: 20px;
    font-size: 22px;
    padding: 3px 15px;
    border-radius: 0;
    display: none;
}

/*=================================================================
                            CONTENT (Generic)
=================================================================*/

.content-box {
    padding: 60px 0 60px 0;
    background-color: #d7d9ce;

}

.content-title h3 {

    font-size: 30px;
    font-weight: 700;
    text-align: center;
    margin: 0 0 30px 0;

}

.content-title-underline {
    width: 30px;
    height: 3px;
    background-color: #0c7489;
    margin: 0 auto 30px auto;


}

/*=================================================================
                            My Work (Generic)
=================================================================*/

.about-item {

    padding: 20px 0 20px 0;
    margin-bottom: 20px;
    cursor: pointer;
    color: #13505b;

}

.about-item-icon i {

    color: #13505b;
    float: center;
    padding: 15px;
    width: 75px;
    height: 75px;
    text-align: center;

}

.about-item:hover .about-item-icon i {
    color: #119da4;
    background-color: #fff;

}

/*==================================================
                        CONTACT
==================================================*/

footer {
    background-color: #0c7489;
    padding-top: 30px;
    border-top: 5px solid rgba(0, 0, 0, 1.0);
}

#contact-left h3,
#contact-right h3 {
    color: #fff;
    font-size: 27px;
    font-weight: 700;
}

#contact-left p {
    color: #fff;
    margin-bottom: 30px;
}

#contact-info address {
    color: #fff;
}

address strong {
    font-size: 16px;
}

address strong,
#phone-fax-email strong {
    letter-spacing: 1px;
}

form .form-control {
    background: transparent;
    border-radius: 0;
    border-color: #fff;
    font-size: 17px;
    font-weight: 300;
    padding: 8px 16px;
    margin-bottom: 20px;
    color: #fff;
}

/*==================================================
                     FOOTER
==================================================*/

#footer-bottom {
    background-color: rgba(0, 0, 0, 0.1);
    padding: 30px 0;
    margin-top: 60px;
}

#footer-copyrights p {
    margin: 0;
    color: #fff;
}

#footer-menu {
    float: left;
    color: #fff;
    font-size: 16px;
    font-weight: 300;
}

#footer-menu a {
    color: #fff;
    font-size: 16px;
    font-weight: 300;
    margin: 0 10px;
    text-decoration: none;
}

#footer-menu a:hover {
    color: #fff;
}

.social-list > li > a {
    color: #fff;
    font-size: 15px;
    letter-spacing: 1px;
    font-weight: 700;

}

/*====================================================================

                            NAVIGATION
====================================================================*/

.navbar {
    padding: 20px 0;

}

.portfolio-nav-wrapper {
    padding: 0 85px;
}

.navbar-nav {
    float: right;
}

.navbar-nav > li > a {
    color: #d7d9ce;
    font-size: 15px;
    text-transform: uppercase;
    letter-spacing: 1px;
    font-weight: 700;

}

.navbar-nav > li > a:hover,
.navbar-nav > li > a:focus {
    background: none;
    color: #119da4;
}

.navbar-toggle {
    background-color: rgba(0, 0, 0, 0.1);
    border: 1px solid #fff;
    border-radius: 0;
}

.navbar-toggle .icon-bar {
    background-color: #fff;
}

.navbar-collapse {
    max-height: none !important;
}

.portfolio-top-nav ul.navbar-nav > li.active > a {
    color: #119da4;
}

/*====================================================================

                            NAVIGATION
====================================================================*/
// Show/Hide transparent black navigation
$(function () {
    $(window).scroll(function ()) {

        if ($(this).scrollTop() < 50) {
            //hide nav
            $("nav").removeClass("portfolio-top-nav");

        } else {
            // show nav
            $("nav").addClass("portfolio-top-nav");
        }
    });

});
//Smooth scrolling
$(function () {

    $("a.smooth-scroll").click(function (event) {

        event.preventDefault();

        // get/return id like #about, #contact
        var section = $(this).attr("href");

        $('html, body').animate({
            scrollTop: $(section).offset().top - 90
        }, 1250);

    });

});

/*=================================================================

                        Bootstrap 3 Media Queries
===================================================================*/

/* Large Devices (Desktop & Laptops) */

@media (min-width: 1200px) {}

/* OK */

/* Medium Devices (Medium Desktop & Landscape Tablets) */

@media (min-width: 992px) and (max-width: 1199px) {}

/* Small Devices (Small Desktop & Portrait Tablets) */

@media (min-width: 768px) and (max-width: 991px) {}

/* Extra Small Devices (Landscape Phones & Portrait Tablets) */

@media (max-width: 767px) {}

/* Extra Small Devices (Smaller devices) */

@media (max-width: 480px) {}

/* Extra Small Devices (Smaller devices) */

@media (max-width: 320px) {}
