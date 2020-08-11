<!DOCTYPE html>
<html lang="kr"
    <head>
        <meta charset="utf-8" />
        <meta http-equiv="X-UA-Compatible" content="IE=edge" />
        <meta name="viewport" content="width=device-width, initial-scale=1" />
        <meta name="description" content="" />
        <meta name="author" content="" />

        <title>API-Test</title>

        <!-- Bootstrap Core CSS -->
        <link href="vendor/bootstrap/css/bootstrap.min.css" rel="stylesheet" />

        <!-- Theme CSS -->
        <link href="css/freelancer.min.css" rel="stylesheet" />

        <!-- Custom Fonts -->
        <link href="vendor/font-awesome/css/font-awesome.min.css" rel="stylesheet" type="text/css" />
        <link href="https://fonts.googleapis.com/css?family=Montserrat:400,700" rel="stylesheet" type="text/css" />
        <link href="https://fonts.googleapis.com/css?family=Lato:400,700,400italic,700italic" rel="stylesheet" type="text/css" />

        <!-- HTML5 Shim and Respond.js IE8 support of HTML5 elements and media queries -->
        <!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
        <!--[if lt IE 9]>
            <script src="https://oss.maxcdn.com/libs/html5shiv/3.7.0/html5shiv.js"></script>
            <script src="https://oss.maxcdn.com/libs/respond.js/1.4.2/respond.min.js"></script>
        <![endif]-->
    </head>

    <body id="page-top" class="index">
        <div id="skipnav"><a href="#maincontent">Skip to main content</a></div>

        <!-- Navigation -->
        <nav id="mainNav" class="navbar navbar-default navbar-fixed-top navbar-custom">
            <div class="container">
                <!-- Brand and toggle get grouped for better mobile display -->
                <div class="navbar-header page-scroll">
                    <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1"><span class="sr-only">Toggle navigation</span> Menu <i class="fa fa-bars"></i></button>
                    <a class="navbar-brand" href="#page-top"> Map based Application Test-Site</a>
                </div>

                <!-- Collect the nav links, forms, and other content for toggling -->
                <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
                    <ul class="nav navbar-nav navbar-right">
                        <li class="hidden">
                            <a href="#page-top"></a>
                        </li>
                        <li class="page-scroll">
                            <a href="#API-Maps">API-Maps Provider</a>
                        </li>
                        <li class="page-scroll">
                            <a href="#about">About</a>
                        </li>
                        <li class="page-scroll">
                            <a href="#contact">Contact</a>
                        </li>
                    </ul>
                </div>
                <!-- /.navbar-collapse -->
            </div>
            <!-- /.container-fluid -->
        </nav>

        <!-- Header -->
        <header>
            <div class="container" id="maincontent" tabindex="-1">
                <div class="row">
                    <div class="col-lg-12">
                        <img class="img-responsive" src="img/profile.png" alt="" />
                        <div class="intro-text">
                            <h1 class="name">Map API Applications</h1>
                            <hr class="star-light" />
                            <span class="skills">System Developer - User Experience Designer</span>
                        </div>
                    </div>
                </div>
            </div>
        </header>

        <!-- API-Maps -->
        <section id="API-Maps">
            <div class="container">
                <div class="row">
                    <div class="col-lg-12 text-center">
                        <h2>MAP-API PROVIDER</h2>
                        <hr class="star-primary" />
                    </div>
                </div>
                <div class="row">
                    <div class="col-sm-4 portfolio-item">
                        <a href="#portfolioModal1" class="portfolio-link" data-toggle="modal">
                            <div class="caption">
                                <div class="caption-content">
                                    <i class="fa fa-search-plus fa-3x"></i>
                                </div>
                            </div>
                            <img src="img/portfolio/Google_Map.png" class="img-responsive" alt="Google" />
                        </a>
                    </div>
                    <div class="col-sm-4 portfolio-item">
                        <a href="#portfolioModal2" class="portfolio-link" data-toggle="modal">
                            <div class="caption">
                                <div class="caption-content">
                                    <i class="fa fa-search-plus fa-3x"></i>
                                </div>
                            </div>
                            <img src="img/portfolio/Naver_Map.png" class="img-responsive" alt="Naver" />
                        </a>
                    </div>
                    <div class="col-sm-4 portfolio-item">
                        <a href="#portfolioModal3" class="portfolio-link" data-toggle="modal">
                            <div class="caption">
                                <div class="caption-content">
                                    <i class="fa fa-search-plus fa-3x"></i>
                                </div>
                            </div>
                            <img src="img/portfolio/Kakao_Map.png" class="img-responsive" alt="KaKao" />
                        </a>
                    </div>
                </div>
            </div>
        </section>

        <!-- About Section -->
        <section class="success" id="about">
            <div class="container">
                <div class="row">
                    <div class="col-lg-12 text-center">
                        <h2>About</h2>
                        <hr class="star-light" />
                    </div>
                </div>
                <div class="row">
                    <div class="col-lg-4 col-lg-offset-2 text-center">
                        <p> 상용으로 제공되고 있는 지도 기반 API 기능 > Web 구현 가능 기능 테스트</p>
                    </div>
                    <div class="col-lg-4 text-center">
                        <p> 부가 활용 가능한 공공 API에 대해 적용 실습 및 기능 개발 PoC</p>
                    </div>
                    <div class="col-lg-8 col-lg-offset-2 text-center">
                        <a href="#" class="btn btn-lg btn-outline"> <i class="fa fa-download"></i> Download </a>
                    </div>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact">
            <div class="container">
                <div class="row">
                    <div class="col-lg-12 text-center">
                        <h2>Contact Me</h2>
                        <hr class="star-primary" />
                    </div>
                </div>
                <div class="row">
                    <div class="col-lg-8 col-lg-offset-2">
                        <!-- To configure the contact form email address, go to mail/contact_me.php and update the email address in the PHP file on line 19. -->
                        <!-- The form should work on most web servers, but if the form is not working you may need to configure your web server differently. -->
                        <form name="sentMessage" id="contactForm" novalidate>
                            <div class="row control-group">
                                <div class="form-group col-xs-12 floating-label-form-group controls">
                                    <label for="name">Name</label>
                                    <input type="text" class="form-control" placeholder="Name" id="name" required data-validation-required-message="Please enter your name." />
                                    <p class="help-block text-danger"></p>
                                </div>
                            </div>
                            <div class="row control-group">
                                <div class="form-group col-xs-12 floating-label-form-group controls">
                                    <label for="email">Email Address</label>
                                    <input type="email" class="form-control" placeholder="Email Address" id="email" required data-validation-required-message="Please enter your email address." />
                                    <p class="help-block text-danger"></p>
                                </div>
                            </div>
                            <div class="row control-group">
                                <div class="form-group col-xs-12 floating-label-form-group controls">
                                    <label for="phone">Phone Number</label>
                                    <input type="tel" class="form-control" placeholder="Phone Number" id="phone" required data-validation-required-message="Please enter your phone number." />
                                    <p class="help-block text-danger"></p>
                                </div>
                            </div>
                            <div class="row control-group">
                                <div class="form-group col-xs-12 floating-label-form-group controls">
                                    <label for="message">Message</label>
                                    <textarea rows="5" class="form-control" placeholder="Message" id="message" required data-validation-required-message="Please enter a message."></textarea>
                                    <p class="help-block text-danger"></p>
                                </div>
                            </div>
                            <br />
                            <div id="success"></div>
                            <div class="row">
                                <div class="form-group col-xs-12">
                                    <button type="submit" class="btn btn-success btn-lg">Send</button>
                                </div>
                            </div>
                        </form>
                    </div>
                </div>
            </div>
        </section>

        <!-- Footer -->
        <footer class="text-center">
            <div class="footer-above">
                <div class="container">
                    <div class="row">
                        <div class="footer-col col-md-4">
                            <h3>Location</h3>
                            <p>
                                Baumoe-ro 2-gil, Seocho-gu, Seoul, Republic of Korea <br />
                                06763
                            </p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="footer-below">
                <div class="container">
                    <div class="row">
                        <div class="col-lg-12">
                            Copyright &copy; For test_from August. 2020
                        </div>
                    </div>
                </div>
            </div>
        </footer>

        <!-- Scroll to Top Button (Only visible on small and extra-small screen sizes) -->
        <div class="scroll-top page-scroll hidden-sm hidden-xs hidden-lg hidden-md">
            <a class="btn btn-primary" href="#page-top">
                <i class="fa fa-chevron-up"></i>
            </a>
        </div>


        <!-- Portfolio Modals -->
        <div class="portfolio-modal modal fade" id="portfolioModal1" tabindex="-1" role="dialog" aria-hidden="true">
            <div class="modal-content">
                <div class="close-modal" data-dismiss="modal">
                    <div class="lr">
                        <div class="rl"></div>
                    </div>
                </div>

                <div class="container">
                    <div class="row">
                        <div class="col-lg-8 col-lg-offset-2">
                            <div class="modal-body">
                                <h2>Based on Google Maps API</h2>
                                <hr class="star-primary" />
                                <img src="img/portfolio/Google_Map.png" class="img-responsive img-centered" alt="" />
                                <p>
                                    Android 단말에 대한 서비스를 주로 제공하고 있는 Google Maps Platform은 세계 사용자를 대상으로 주로 서비스를 제공하고 있습니다.
                                    <a href="https://cloud.google.com/maps-platform/">Google API</a> 사이트를 통해 해당 Key를 발급받아 각종 서비스 테스트가 가능합니다.
                                </p>
                                <ul class="list-inline item-details">
                                    <li>
                                        My Google Maps
                                        <strong><a href="https://Google.com/maps/d/"> My Google Maps</a> </strong>
                                    </li>
                                </ul>
                                <button type="button" class="btn btn-default" data-dismiss="modal"><i class="fa fa-times"></i> Close</button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <div class="portfolio-modal modal fade" id="portfolioModal2" tabindex="-1" role="dialog" aria-hidden="true">
            <div class="modal-content">
                <div class="close-modal" data-dismiss="modal">
                    <div class="lr">
                        <div class="rl"></div>
                    </div>
                </div>

                <div class="container">
                    <div class="row">
                        <div class="col-lg-8 col-lg-offset-2">
                            <div class="modal-body">
                                <h2>Based on Naver Maps API</h2>
                                <hr class="star-primary" />
                                <img src="img/portfolio/Naver_Map.png" class="img-responsive img-centered" alt="" />
                                <p>
                                    가장 많은 사용자가 사용하고 있는 Portal Service Platform과 연동하여 접근성이 높은 지도 서비스 입니다.
                                    <a href="https://navermaps.github.io/maps.js/">Naver Maps API v3</a>사이트를 통해 해당 Key를 발급받아 각종 서비스 테스트가 가능합니다.
                                </p>
                                <ul class="list-inline item-details">
                                    <li>
                                        Date:
                                        <strong><a href="http://startbootstrap.com">April 2014</a> </strong>
                                    </li>
                                    <li>
                                        Service:
                                        <strong><a href="http://startbootstrap.com">Web Development</a> </strong>
                                    </li>
                                </ul>
                                <button type="button" class="btn btn-default" data-dismiss="modal"><i class="fa fa-times"></i> Close</button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        
		<div class="portfolio-modal modal fade" id="portfolioModal3" tabindex="-1" role="dialog" aria-hidden="true">
            <div class="modal-content">
                <div class="close-modal" data-dismiss="modal">
                    <div class="lr">
                        <div class="rl"></div>
                    </div>
                </div>

                <div class="container">
                    <div class="row">
                        <div class="col-lg-8 col-lg-offset-2">
                            <div class="modal-body">
                                <h2>Based on Kakao Maps API</h2>
                                <hr class="star-primary" />
                                <img src="img/portfolio/Kakao_Map.png" class="img-responsive img-centered" alt="" />
                                <p>
                                    국내 가장 많은 사용자를 보유하고 있는 SNS, 카카오에서 제공하는 지도 플랫폼 입니다.
                                   <a href="https://apis.map.kakao.com//">Kakao Maps API</a>사이트를 통해 해당 Key를 발급받아 각종 서비스 테스트가 가능합니다.
                                </p>
                                <ul class="list-inline item-details">
								<body>
									<div id="map" style="width:500px;height:400px;"></div>
									<script type="text/javascript" src="//dapi.kakao.com/v2/maps/sdk.js?appkey=d2d814f01aca897823f1ef87666f3e51."></script>
									<script>
										var container = document.getElementById('map');
										var options = {
											center: new kakao.maps.LatLng(33.450701, 126.570667),
											level: 3
										};

		var map = new kakao.maps.Map(container, options);
	</script>
                                    <li>
                                        Client:
                                        <strong><a href="http://startbootstrap.com">Start Bootstrap</a> </strong>
                                    </li>
                                    <li>
                                        Date:
                                        <strong><a href="http://startbootstrap.com">April 2014</a> </strong>
                                    </li>
                                    <li>
                                        Service:
                                        <strong><a href="http://startbootstrap.com">Web Development</a> </strong>
                                    </li>
                                </ul>
                                <button type="button" class="btn btn-default" data-dismiss="modal"><i class="fa fa-times"></i> Close</button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- jQuery -->
        <script src="vendor/jquery/jquery.min.js"></script>

        <!-- Bootstrap Core JavaScript -->
        <script src="vendor/bootstrap/js/bootstrap.min.js"></script>

        <!-- Plugin JavaScript -->
        <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery-easing/1.3/jquery.easing.min.js"></script>

        <!-- Contact Form JavaScript -->
        <script src="js/jqBootstrapValidation.js"></script>
        <script src="js/contact_me.js"></script>

        <!-- Theme JavaScript -->
        <script src="js/freelancer.min.js"></script>
    </body>
</html>
