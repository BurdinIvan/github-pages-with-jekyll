<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="css/main1.css">
</head>

<body>

    <!-- SPRITE -->

    <svg style="display: none;">

        <symbol id="intro3__twitter" viewBox="0 0 512 512">

            <g>
                <path d="M512,97.248c-19.04,8.352-39.328,13.888-60.48,16.576c21.76-12.992,38.368-33.408,46.176-58.016
                c-20.288,12.096-42.688,20.64-66.56,25.408C411.872,60.704,384.416,48,354.464,48c-58.112,0-104.896,47.168-104.896,104.992
                c0,8.32,0.704,16.32,2.432,23.936c-87.264-4.256-164.48-46.08-216.352-109.792c-9.056,15.712-14.368,33.696-14.368,53.056
                c0,36.352,18.72,68.576,46.624,87.232c-16.864-0.32-33.408-5.216-47.424-12.928c0,0.32,0,0.736,0,1.152
                c0,51.008,36.384,93.376,84.096,103.136c-8.544,2.336-17.856,3.456-27.52,3.456c-6.72,0-13.504-0.384-19.872-1.792
                c13.6,41.568,52.192,72.128,98.08,73.12c-35.712,27.936-81.056,44.768-130.144,44.768c-8.608,0-16.864-0.384-25.12-1.44
                C46.496,446.88,101.6,464,161.024,464c193.152,0,298.752-160,298.752-298.688c0-4.64-0.16-9.12-0.384-13.568
                C480.224,136.96,497.728,118.496,512,97.248z"/>
            </g>

        </symbol>

        <symbol id="intro3__facebook" viewBox="0 0 24 24">

            <g>
                <path d="m15.997 3.985h2.191v-3.816c-.378-.052-1.678-.169-3.192-.169-3.159 0-5.323 1.987-5.323 5.639v3.361h-3.486v4.266h3.486v10.734h4.274v-10.733h3.345l.531-4.266h-3.877v-2.939c.001-1.233.333-2.077 2.051-2.077z"/>
            </g>

        </symbol>

        <symbol id="intro3__linked-in" viewBox="0 0 552.77 552.77">

            <g>
                <path d="M17.95,528.854h71.861c9.914,0,17.95-8.037,17.95-17.951V196.8c0-9.915-8.036-17.95-17.95-17.95H17.95
			        C8.035,178.85,0,186.885,0,196.8v314.103C0,520.816,8.035,528.854,17.95,528.854z"/>
                <path d="M17.95,123.629h71.861c9.914,0,17.95-8.036,17.95-17.95V41.866c0-9.914-8.036-17.95-17.95-17.95H17.95
                    C8.035,23.916,0,31.952,0,41.866v63.813C0,115.593,8.035,123.629,17.95,123.629z"/>
                <path d="M525.732,215.282c-10.098-13.292-24.988-24.223-44.676-32.791c-19.688-8.562-41.42-12.846-65.197-12.846
                    c-48.268,0-89.168,18.421-122.699,55.27c-6.672,7.332-11.523,5.729-11.523-4.186V196.8c0-9.915-8.037-17.95-17.951-17.95h-64.192
                    c-9.915,0-17.95,8.035-17.95,17.95v314.103c0,9.914,8.036,17.951,17.95,17.951h71.861c9.915,0,17.95-8.037,17.95-17.951V401.666
                    c0-45.508,2.748-76.701,8.244-93.574c5.494-16.873,15.66-30.422,30.488-40.649c14.83-10.227,31.574-15.343,50.24-15.343
                    c14.572,0,27.037,3.58,37.393,10.741c10.355,7.16,17.834,17.19,22.436,30.104c4.604,12.912,6.904,41.354,6.904,85.33v132.627
                    c0,9.914,8.035,17.951,17.949,17.951h71.861c9.914,0,17.949-8.037,17.949-17.951V333.02c0-31.445-1.982-55.607-5.941-72.48
                    S535.836,228.581,525.732,215.282z"/>
            </g>

        </symbol>

        <symbol id="intro3__mail" viewBox="0 0 512 512">

            <g>
                <g>
                    <path d="M507.49,101.721L352.211,256L507.49,410.279c2.807-5.867,4.51-12.353,4.51-19.279V121
                        C512,114.073,510.297,107.588,507.49,101.721z"/>
                </g>
            </g>
            <g>
                <g>
                    <path d="M467,76H45c-6.927,0-13.412,1.703-19.279,4.51l198.463,197.463c17.548,17.548,46.084,17.548,63.632,0L486.279,80.51
                        C480.412,77.703,473.927,76,467,76z"/>
                </g>
            </g>
            <g>
                <g>
                    <path d="M4.51,101.721C1.703,107.588,0,114.073,0,121v270c0,6.927,1.703,13.413,4.51,19.279L159.789,256L4.51,101.721z"/>
                </g>
            </g>
            <g>
                <g>
                    <path d="M331,277.211l-21.973,21.973c-29.239,29.239-76.816,29.239-106.055,0L181,277.211L25.721,431.49
                        C31.588,434.297,38.073,436,45,436h422c6.927,0,13.412-1.703,19.279-4.51L331,277.211z"/>
                </g>
            </g>

        </symbol>

    </svg>



    <!--HEADER-->

    <header class="header">
        <div class="container">
            <div class="header__inner">
                <div class="header__logo">
                    <img src="img/logo.png" alt="Cuda">
                </div>
                
                <div class="container2">
                    <nav class="nav">
                        <a class="nav__link" href="#">HOME</a>
                        <a class="nav__link" href="#">ABOUT</a>
                        <a class="nav__link" href="#">WORK</a>
                        <a class="nav__link" href="#">BLOG</a>
                        <a class="nav__link" href="#">CONTACT</a>
                    </nav>
                </div>

                <button class="burger" type="button">
                    <span class="burger__item">Menu</span>
                </button>
            </div>
        </div>
    </header>

    <!--INTRO-->

    <div class="intro">
        <div class="container">
            <div class="intro__inner">
                <h1 class="intro__title">Hi there! We are the new kids on the block 
                    and we build awesome websites and mobile apps.</h1>
                <a class="btn btn--red" href="#">WORK WITH US!</a>
            </div>
        </div>
    </div>

    <!--FEATURES-->

    <div class="intro2">
        <div class="container">
                <div class="container3">
                    <div class="intro2__title">SERVICES WE PROVIDE</div>
                        <p2 class="intro2__paragraf">We are working with both individuals and businesses from all over the globe 
                            to create awesome websites and applications.</p2>
                </div>                   

            <div class="features">
                <div class="features__item">
                    <img class="features__icon" src="img/Branding.png" alt="">
                    <h3 class="features__title">Branding</h3>
                    <div class="features__text">Lorem ipsum dolor sit amet, 
                        consectetuer adipiscing elit, sed diam nonummy nibh.</div>
                </div>

                <div class="features__item">
                    <img class="features__icon1" src="img/Design.png" alt="">
                    <h3 class="features__title">Design</h3>
                    <div class="features__text">Sed ut perspiciatis unde omnis iste natus error sit voluptatem</div>
                </div>
                
                <div class="features__item">
                    <img class="features__icon" src="img/Development.png" alt="">
                    <h3 class="features__title">Development</h3>
                    <div class="features__text">At vero eos et accusamus et iusto odio dignissimos qui blanditiis praesentium.</div>
                </div>

                <div class="features__item">
                    <img class="features__icon2" src="img/Rocket Science.png" alt="">
                    <h3 class="features__title">ROCKET SCIENCE</h3>
                    <div class="features__text">Et harum quidem rerum est et expedita distinctio. Nam libero tempore.</div>
                </div>
            </div><!--/features-->          
        </div><!--/container-->
    </div><!--/intro2-->

    <section class="intro3">
        <div class="container">
            <div class="container4">
                <div class="intro3__title">MEET OUR BEAUTIFUL TEAM</div>
                <p2 class="intro3__paragraf">We are a small team of designers and developers, who help brands with big ideas.</p2>
            </div>
            
            <div class="icon">
                <div class="icon__item">                   
                    <img class="icon__icon" src="img/Base.png" alt="">
                    <h3 class="icon__title">ANNE HATHAWAY</h3>
                    <div class="icon__text1">CEO / Marketing Guru</div>
                    <div class="icon__text2">Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna.</div>
                    
                    <div class="btn2">                
                        <a class="btn__link1" href="#" target="_blank">
                            <svg class="btn__link__icon1">
                                <use xlink:href="#intro3__facebook"></use>
                            </svg>
                        </a>

                        <a class="btn__link2" href="#" target="_blank">
                            <svg class="btn__link__icon2">
                                <use xlink:href="#intro3__twitter"></use>
                            </svg>
                        </a>

                        <a class="btn__link3" href="#" target="_blank">
                            <svg class="btn__link__icon3">
                                <use xlink:href="#intro3__linked-in"></use>
                            </svg>
                        </a>

                        <a class="btn__link4" href="#" target="_blank">
                            <svg class="btn__link__icon4">
                                <use xlink:href="#intro3__mail"></use>
                            </svg>
                        </a>
                    </div><!--/btn2-->          
                </div><!--/icon__item-->
            
                <div class="icon__item">                   
                    <img class="icon__icon" src="img/Base.png" alt="">
                    <h3 class="icon__title">Kate Upton</h3>
                    <div class="icon__text1">Creative Director</div>
                    <div class="icon__text2">Duis aute irure dolor in in voluptate velit esse cillum dolore fugiat nulla pariatur. Excepteur sint occaecat non diam proident.</div>
                    
                    <div class="btn2">
                        <a class="btn__link2" href="#" target="_blank">
                            <svg class="btn__link__icon2">
                                <use xlink:href="#intro3__twitter"></use>
                            </svg>
                        </a>
                        
                        <a class="btn__link3" href="#" target="_blank">
                            <svg class="btn__link__icon3">
                                <use xlink:href="#intro3__linked-in"></use>
                            </svg>
                        </a>

                        <a class="btn__link4" href="#" target="_blank">
                            <svg class="btn__link__icon4">
                                <use xlink:href="#intro3__mail"></use>
                            </svg>
                        </a>
                    </div>                            
                </div>

                <div class="icon__item">                   
                    <img class="icon__icon" src="img/Base.png" alt="">
                    <h3 class="icon__title">Olivia Wilde</h3>
                    <div class="icon__text1">Lead Designer</div>
                    <div class="icon__text2">Nemo enim ipsam voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem nesciunt.</div>
                    
                    <div class="btn2">
                        <a class="btn__link1" href="#" target="_blank">
                            <svg class="btn__link__icon1">
                                <use xlink:href="#intro3__facebook"></use>
                            </svg>
                        </a>

                        <a class="btn__link2" href="#" target="_blank">
                            <svg class="btn__link__icon2">
                                <use xlink:href="#intro3__twitter"></use>
                            </svg>
                        </a>

                        <a class="btn__link3" href="#" target="_blank">
                            <svg class="btn__link__icon3">
                                <use xlink:href="#intro3__linked-in"></use>
                            </svg>
                        </a>

                        <a class="btn__link4" href="#" target="_blank">
                            <svg class="btn__link__icon4">
                                <use xlink:href="#intro3__mail"></use>
                            </svg>
                        </a>
                    </div>                            
                </div>

                <div class="icon__item">                   
                    <img class="icon__icon" src="img/Base.png" alt="">
                    <h3 class="icon__title">Ashley Greene</h3>
                    <div class="icon__text1">SEO / Developer</div>
                    <div class="icon__text2">Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam.</div>
                    
                    <div class="btn2">
                        <a class="btn__link1" href="#" target="_blank">
                            <svg class="btn__link__icon1">
                                <use xlink:href="#intro3__facebook"></use>
                            </svg>
                        </a>
                        
                        <a class="btn__link2" href="#" target="_blank">
                            <svg class="btn__link__icon2">
                                <use xlink:href="#intro3__twitter"></use>
                            </svg>
                        </a>

                        <a class="btn__link4" href="#" target="_blank">
                            <svg class="btn__link__icon4">
                                <use xlink:href="#intro3__mail"></use>
                            </svg>
                        </a>
                    </div>         
                </div><!--/icon__item-->
            </div><!--/icon-->
        </div><!--/container-->
    </section><!--/intro3-->

    <section class="intro4">
        <div class="container">
            <div class="container5">
                <div class="intro4__title">WE GOT SKILLS!</div>
                    <p2 class="intro4__paragraf">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod 
                        tempor incididunt ut labore et dolore magna aliqua.</p2>
            </div>
        
            <div class="grafik">
                <div class="grafik__item">
                    <img class="grafik__icon" src="img/grafik1.png" alt="">
                    <h3 class="grafik__title">Web Design</h3>
                </div>

                <div class="grafik__item">
                    <img class="grafik__icon" src="img/grafik2.png" alt="">
                    <h3 class="grafik__title">HTML / CSS</h3>
                </div>

                <div class="grafik__item">
                    <img class="grafik__icon" src="img/grafik3.png" alt="">
                    <h3 class="grafik__title">GRAPHIC DESIGN</h3>
                </div>

                <div class="grafik__item">
                    <img class="grafik__icon" src="img/grafik4.png" alt="">
                    <h3 class="grafik__title">UI / UX</h3>
                </div>

            </div>
        </div>
    </section>

    <section class="intro5">
        <div class="container">
            <div class="container6">
                <div class="intro5__title">OUR PORTFOLIO</div>
                <p2 class="intro5__paragraf">Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet
                consectetur, adipisci velit, sed quia non numquam</p2>
            </div>

            <div class="containerNAV">
                <div class="nav2">
                    <a class="nav__link2" href="#">ALL</a>
                    <a class="nav__link2" href="#">WEB</a>
                    <a class="nav__link2" href="#">APPS</a>
                    <a class="nav__link2" href="#">ICONS</a>
                </div>
            </div>
            
            <div class="icon__nout">
                <div class="nout__item">
                    <img class="nout__icon" src="img/nout1.png" alt="">
                    <h3 class="nout__title">Isometric Perspective Mock-Up</h3>
                </div>

                <div class="nout__item">
                    <img class="nout__icon" src="img/nout2.png" alt="">
                    <h3 class="nout__title">Time Zone App UI</h3>
                </div>
  
                <div class="nout__item">
                    <img class="nout__icon" src="img/nout3.png" alt="">
                    <h3 class="nout__title">Viro Media Players UI</h3>
                </div>

                <div class="nout__item">
                    <img class="nout__icon" src="img/nout4.png" alt="">
                    <h3 class="nout__title">Blog / Magazine Flat UI Kit</h3>
                </div>
            </div>
        </div>

        <div class="intro__inner2">
            <a class="btn3 btn--red2" href="#">LOAD MORE PROJECTS</a>
        </div>
    </section>

    <section class="intro6">
        <div class="container">
            <div class="container7">
                <div class="intro6__title">WHAT POEPLE SAY ABOUT US</div>
                   <p2 class="intro6__paragraf">Our clients love us!</p2>
            </div>

            <div class="clients">
                <div class="clients__item">
                    <img class="clients__icon" src="img\Base1.png" alt="">
                    <p class="clients__text">“Nullam dapibus blandit orci, viverra gravida dui lobortis eget. Maecenas fringilla urna eu nisl scelerisque.”</p>
                    <div class="clients__name">Chanel Iman</div>
                    <div class="clients__working">CEO of Pinterest</div>
                </div>

                <div class="clients__item">
                    <img class="clients__icon" src="img\Base1.png" alt="">
                    <p class="clients__text">“Vivamus luctus urna sed urna ultricies ac tempor dui sagittis. In condimentum facilisis porta.”</p>
                    <div class="clients__name">ADRIANA LIMA</div>
                    <div class="clients__working">Founder of Instagram</div>
                </div>
                        
                <div class="clients__item">
                    <img class="clients__icon" src="img\Base1.png" alt="">
                    <p class="clients__text">“Vivamus luctus urna sed urna ultricies ac tempor dui sagittis. In condimentum facilisis porta.”</p>
                    <div class="clients__name">ANNE HATHAWAY</div>
                    <div class="clients__working">Lead Designer at Behance</div>
                </div>

                <div class="clients__item">
                    <img class="clients__icon" src="img\Base1.png" alt="">
                    <p class="clients__text">“Phasellus non purus vel arcu tempor commodo. Fusce semper, purus vel luctus molestie, risus sem cursus neque.”</p>
                    <div class="clients__name">EMMA STONE</div>
                    <div class="clients__working">Co-Founder of Shazam</div>
                </div>
            </div>
        </div>
    </section>

    <section class="intro7">
        <div class="container">
            <div class="container8">
                <div class="intro7__title">GET IN TOUCH</div>
                <p2 class="intro7__paragraf">1600 Pennsylvania Ave NW, Washington, DC 20500, United States of America. Tel: (202) 456-1111</p2>
            </div>
            <div class="container9">
                <div class="name__email">
                    <label class="container9__name">
                        <input required type="text">
                            <div class="container9__text">Your Name <strong style="color: red;">*</strong></div>
                    </label>
        
                    <label class="container9__email">
                        <input required type="text">
                        <div class="container9__text">Your Email <strong style="color: red;">*</strong></div>
                    </label>
                </div>
                
                <div class="div">
                    <input class="input3" type="Your Name *" placeholder="Your Message *"></input>
                </div>
                
                <a class="btn4" href="#">SEND MESSAGE</a>
            
            </div>

        </div>
    </section>

    <footer class="footer">
        <div class="container">
            <div class="container10">
                <div class="nav__footer">
                    <a class="nav__footer__link" href="#">Facebook</a>
                    <a class="nav__footer__link" href="#">Twitter </a>
                    <a class="nav__footer__link" href="#">Google+</a>
                    <a class="nav__footer__link" href="#">LinkedIn</a>
                    <a class="nav__footer__link" href="#">Behance</a>
                    <a class="nav__footer__link" href="#">Dribbble</a>
                    <a class="nav__footer__link" href="#">GitHub</a>
                </div>
            </div>
        </div>
    </footer>
</body>
</html>
