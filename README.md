# netflix_clone
<html>
    <head>
        <meta name="description" content="hello"/>
        <meta name="viewport" content="width=device-width , initial-scale=1.0"/>
        <link rel ="stylesheet" href="style.css"/>
        <link rel="stylesheet" 
        href="https://use.fontawesome.com/releases/v5.15.4/css/all.css"
        integrity="sha384-DyZ88mC6Up2uqS4h/KRgHuoeGwBcD4Ng9SiP4dIRy0EXTlnuz47vAwmeGwVChigm"
        crossorigin="anonymous"/>
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">
    </head>
    <body>
        <header>
            <nav class="navbar">
                <div class="navbar-brand">
                <img src="logo.png" 
                alt="logo"
                class="brand-logo"/>
            </div>
            <div class="navbar-nav-items">
                <div class="nav-item">
                   <div class="dropdown-container">
                    <i class="fas fa-globe"></i>
                    <select name="languages" 
                    id="languagesSelect" 
                    class="language-drop-down">  
                    <option value="english" selected>English</option>
                    <option value="hindi">Hindi</option>     
                </select>   
                   </div>        
                </div>
                <div>
                    <div class="nav-item">
                        <button class="signin-button">Sign in</button>
                    </div>
                </div>
            </div>
            </nav>
        </header>
        <main>
            <section class="hero">
                <div class="hero-bg-container">
                    <img src="header-image.png"
                    alt="bg hero image"
                    class="hero-bg-image"/>
                </div>
                <div class="hero-bg-overlay">
                </div>
                <div class="hero-card">
                    <h1 class="hero-title">Unlimited Movies TV, <br> Shows and more.</h1>
                    <p class="hero-subtitle">Watch anywhere and cancel anytime</p>
                    <p class="hero-description">Ready to watch?Enter your email to create or restart your <br> membership.</p>
                    <div class="email-form-container">
                        <div class="form-container">
                            <input type="email" class="email-input" placeholder=" "/>
                            <label class="email-label">Email Address</label>
                        </div>
                        <button class="primary-button">
                            Get Started <i class="fal fa-chevron-right"></i>
                        </button>
                    </div>
                </div>
            </section>
            <section class="features-container">

                <!-- f-1 -->
                <div class="feature">
                    <div class="feature-details">
                        <h3 class="feature-title">Enjoy on your TV.</h3>
                        <h5 class="feature-subtitle">Watch on smart TVs, PlayStation, Xbox, Chromecast,
                            Apple TV, Blu-ray players and more.</h5>
                            </div>
                            <div class="feature-image-container">
                                <img alt="" 
                                src="https://assets.nflxext.com/ffe/siteui/acquisition/ourStory/fuji/desktop/tv.png" 
                                data-uia="feature image"
                                class="feature-image"/>
                                <div class="feature-bg-video-container">
                                    <video autoplay=""
                                    loop=""
                                    muted=""
                                    class="feature-bg-video">
                                       <source src="https://assets.nflxext.com/ffe/siteui/acquisition/ourStory/fuji/desktop/video-tv-in-0819.m4v"
                                        type="video/mp4" />
                                    </video>
                                </div>

                            </div>
                    </div>

                    <!-- f-2 -->
                    <div class="feature">
                        <div class="feature-details">
                            <h3 class="feature-title">Download your shows to watch offline.</h3>
                            <h5 class="feature-subtitle">Save your favourites easily and always have something to watch.</h5>
                                </div>
                                <div class="feature-image-container">
                                    <img alt="" 
                                    src="https://assets.nflxext.com/ffe/siteui/acquisition/ourStory/fuji/desktop/mobile-0819.jpg" 
                                    alt="feature image"
                                    class="feature-image"/>
                                    <div class="feature-2-poster-container">
                                        <div class="poster-container">
                                            <img src="https://assets.nflxext.com/ffe/siteui/acquisition/ourStory/fuji/desktop/boxshot.png"
                                            alt="poster"/>
                                        </div>
                                        <div class="poster-details">
                                            <h4>Stranger Things</h4>
                                            <h6>Downloading...</h6>
                                        </div>
                                        <div class="download-gif-container">
                                            <img src="https://assets.nflxext.com/ffe/siteui/acquisition/ourStory/fuji/desktop/download-icon.gif"
                                            alt="Downloading gif"
                                            class="gif"/>
                                        </div>
                                    </div>
                                </div>
                        </div>
                            
                </div>   
            </section>
        </main>
        <script src="src/index.js"></script>
    </body>
</html>
