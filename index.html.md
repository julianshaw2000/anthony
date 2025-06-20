<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta content="width=device-width, initial-scale=1.0" name="viewport" />
    <title>Broadland Corporate Consulting</title>
    <meta name="description" content="" />
    <meta name="keywords" content="" />

    <!-- Favicons -->
    <link href="assets/img/favicon.png" rel="icon" />
    <link href="assets/img/apple-touch-icon.png" rel="apple-touch-icon" />

    <!-- Fonts -->
    <link href="https://fonts.googleapis.com" rel="preconnect" />
    <link href="https://fonts.gstatic.com" rel="preconnect" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&family=Raleway:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800&display=swap"
      rel="stylesheet"
    />

    <!-- Vendor CSS Files -->
    <link
      href="assets/vendor/bootstrap/css/bootstrap.min.css"
      rel="stylesheet"
    />
    <link
      href="assets/vendor/bootstrap-icons/bootstrap-icons.css"
      rel="stylesheet"
    />
    <link href="assets/vendor/aos/aos.css" rel="stylesheet" />
    <link
      href="assets/vendor/glightbox/css/glightbox.min.css"
      rel="stylesheet"
    />
    <link href="assets/vendor/swiper/swiper-bundle.min.css" rel="stylesheet" />

    <!-- Main CSS File -->
    <link href="assets/css/main.css" rel="stylesheet" />

    <style>
      ul {
        list-style-type: none; /* Removes bullet points */
        padding: 0; /* Removes default padding */
        margin: 0; /* Removes default margin */
      }
    </style>
  </head>

  <body class="index-page">
    <header id="header" class="header d-flex align-items-center sticky-top">
      <div class="container position-relative d-flex align-items-center">
        <a href="index.html" class="logo d-flex align-items-center me-auto">
          <!-- Uncomment the line below if you also wish to use an image logo -->
          <img src="assets/img/favicon.png" alt="" />
          <h1 class="sitename">Broadland Corporate Consulting</h1>
          <span>.</span>
        </a>

        <nav id="navmenu" class="navmenu">
          <ul>
            <!-- <li><a href="#hero" class="active">Home</a></li> -->
            <!-- <li class="dropdown">
              <a href="about.html"
                ><span>About</span>
                <i class="bi bi-chevron-down toggle-dropdown"></i
              ></a>
              <ul>
                <li><a href="team.html">Team</a></li>
                <li><a href="testimonials.html">Testimonials</a></li>
                <li class="dropdown">
                  <a href="#"
                    ><span>Deep Dropdown</span>
                    <i class="bi bi-chevron-down toggle-dropdown"></i
                  ></a>
                  <ul>
                    <li><a href="#">Deep Dropdown 1</a></li>
                    <li><a href="#">Deep Dropdown 2</a></li>
                    <li><a href="#">Deep Dropdown 3</a></li>
                    <li><a href="#">Deep Dropdown 4</a></li>
                    <li><a href="#">Deep Dropdown 5</a></li>
                  </ul>
                </li>
              </ul>
            </li> -->
            <!-- <li><a href="services.html">Services</a></li>
            <li><a href="portfolio.html">Portfolio</a></li>
            <li><a href="pricing.html">Pricing</a></li>
            <li><a href="blog.html">Blog</a></li>
            <li><a href="contact.html">Contact</a></li> -->
          </ul>
          <i
            class="mobile-nav-toggle d-xl-none bi bi-list"
            style="display: none"
          ></i>
        </nav>

        <!-- <div class="header-social-links">
          <a href="#" class="twitter"><i class="bi bi-twitter-x"></i></a>
          <a href="#" class="facebook"><i class="bi bi-facebook"></i></a>
          <a href="#" class="instagram"><i class="bi bi-instagram"></i></a>
          <a href="#" class="linkedin"><i class="bi bi-linkedin"></i></a>
        </div> -->
      </div>
    </header>

    <main class="main">
      <!-- Hero Section -->

      <section id="hero" class="hero section dark-background">
        <div
          id="hero-carousel"
          class="carousel slide carousel-fade"
          data-bs-ride="carousel"
          data-bs-interval="5000"
        >
          <div class="carousel-item active">
            <img src="assets/img/hero-carousel/carousel-1.png" alt="" />
            <div class="container">
              <h2>Clarity That Drives Decisions</h2>
              <p>
                We cut through complexity to give you a clear financial picture.
                With accurate insights and transparent reporting, you’ll
                understand your business performance and make decisions with
                certainty.
              </p>
              <!-- <a href="about.html" class="btn-get-started">Read More</a> -->
            </div>
          </div>
          <!-- End Carousel Item -->

          <div class="carousel-item">
            <img src="assets/img/hero-carousel/carousel-2.png" alt="" />
            <div class="container">
              <h2>Strategy That Fuels Growth</h2>
              <p>
                Our tailored financial strategies align with your goals, helping
                you scale sustainably, allocate resources wisely, and stay ahead
                of market shifts.
              </p>
              <!-- <a href="about.html" class="btn-get-started">Read More</a> -->
            </div>
          </div>
          <!-- End Carousel Item -->

          <div class="carousel-item">
            <img src="assets/img/hero-carousel/carousel-3.png" alt="" />
            <div class="container">
              <h2>Confidence to Move Forward</h2>
              <p>
                With our expert guidance and risk-aware planning, you can
                approach every financial decision with assurance, knowing you
                have the support to succeed.
              </p>
              <!-- <a href="about.html" class="btn-get-started">Read More</a> -->
            </div>
          </div>
          <!-- End Carousel Item -->

          <a
            class="carousel-control-prev"
            href="#hero-carousel"
            role="button"
            data-bs-slide="prev"
          >
            <span
              class="carousel-control-prev-icon bi bi-chevron-left"
              aria-hidden="true"
            ></span>
          </a>

          <a
            class="carousel-control-next"
            href="#hero-carousel"
            role="button"
            data-bs-slide="next"
          >
            <span
              class="carousel-control-next-icon bi bi-chevron-right"
              aria-hidden="true"
            ></span>
          </a>

          <ol class="carousel-indicators"></ol>
        </div>
      </section>

      <!-- /Hero Section -->

      <!-- About Section -->
      <section id="about" class="about section">
        <div class="container">
          <div class="row position-relative">
            <div
              class="col-lg-7 about-img"
              data-aos="zoom-out"
              data-aos-delay="200"
            >
              <img src="assets/img/about.png" />
            </div>

            <div class="col-lg-7" data-aos="fade-up" data-aos-delay="100">
              <h2 class="inner-title">Elevate Your Business</h2>
              <div class="our-story">
                <h4>Est 1988</h4>
                <h3>Our Services</h3>
                <p>
                  We specialize in transformation Succession Planning &
                  Strategic Planning
                </p>

                <ul>
                  <li>
                    <i class="bi bi-check-circle"></i>
                    <span>Financial Advisory & Risk Management</span>
                  </li>
                  <li>
                    <i class="bi bi-check-circle"></i>
                    <span>Business Transformation Consulting</span>
                  </li>
                  <li>
                    <i class="bi bi-check-circle"></i>
                    <span>Succession Planning</span>
                  </li>
                  <li>
                    <i class="bi bi-check-circle"></i>
                    <span>Executive Leadership & Strategic Planning</span>
                  </li>
                  <li>
                    <i class="bi bi-check-circle"></i>
                    <span>Project Management & Business Expansion</span>
                  </li>
                  <li>
                    <i class="bi bi-check-circle"></i>
                    <span>Corporate Governance & Board Advisory</span>
                  </li>
                </ul>

                <!-- <p>
                  Vitae autem velit excepturi fugit. Animi ad non. Eligendi et
                  non nesciunt suscipit repellendus porro in quo eveniet.
                  Molestias in maxime doloremque.
                </p> -->
                <!-- 
                <div
                  class="watch-video d-flex align-items-center position-relative"
                >
                  <i class="bi bi-play-circle"></i>
                  <a
                    href="https://www.youtube.com/watch?v=Y7f98aduVJ8"
                    class="glightbox stretched-link"
                    >Watch Video</a
                  >
                </div> -->
              </div>
            </div>
          </div>
        </div>
      </section>
      <!-- /About Section -->

      <!-- Services Section -->
      <section id="services" class="services section light-background">
        <div class="container">
          <div class="row gy-4">
            <div
              class="col-lg-4 col-md-6"
              data-aos="fade-up"
              data-aos-delay="100"
            >
              <div class="service-item item-blue position-relative">
                <div class="icon">
                  <svg
                    width="100"
                    height="100"
                    viewBox="0 0 600 600"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      stroke="none"
                      stroke-width="0"
                      fill="#f5f5f5"
                      d="M300,503.46388370962813C374.79870501325706,506.71871716319447,464.8034551963731,527.1746412648533,510.4981551193396,467.86667711651364C555.9287308511215,408.9015244558933,512.6030010748507,327.5744911775523,490.211057578863,256.5855673507754C471.097692560561,195.9906835881958,447.69079081568157,138.11976852964426,395.19560036434837,102.3242989838813C329.3053358748298,57.3949838291264,248.02791733380457,8.279543830951368,175.87071277845988,42.242879143198664C103.41431057327972,76.34704239035025,93.79494320519305,170.9812938413882,81.28167332365135,250.07896920659033C70.17666984294237,320.27484674793965,64.84698225790005,396.69656628748305,111.28512138212992,450.4950937839243C156.20124167950087,502.5303643271138,231.32542653798444,500.4755392045468,300,503.46388370962813"
                    ></path>
                  </svg>
                  <i class="bi bi-gear"></i>
                </div>
                <!-- <a href="service-details.html" class="stretched-link"> -->
                  <h3>Business Transformation</h3>
                </a>
                <p>We help you unlock your organization’s potential:</p>
                <ul>
                  <li>Change Management</li>
                  <li>Operational Efficiency & Process Optimization</li>
                  <li>Restructuring & Turnaround</li>
                  <li>Digital Strategy & Transformation</li>
                  <li>Performance Improvement</li>
                </ul>

                <!-- <a href="service-details.html" class="stretched-link"></a> -->
              </div>
            </div>
            <!-- End Service Item -->

            <div
              class="col-lg-4 col-md-6"
              data-aos="fade-up"
              data-aos-delay="200"
            >
              <div class="service-item item-orange position-relative">
                <div class="icon">
                  <svg
                    width="100"
                    height="100"
                    viewBox="0 0 600 600"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      stroke="none"
                      stroke-width="0"
                      fill="#f5f5f5"
                      d="M300,503.46388370962813C374.79870501325706,506.71871716319447,464.8034551963731,527.1746412648533,510.4981551193396,467.86667711651364C555.9287308511215,408.9015244558933,512.6030010748507,327.5744911775523,490.211057578863,256.5855673507754C471.097692560561,195.9906835881958,447.69079081568157,138.11976852964426,395.19560036434837,102.3242989838813C329.3053358748298,57.3949838291264,248.02791733380457,8.279543830951368,175.87071277845988,42.242879143198664C103.41431057327972,76.34704239035025,93.79494320519305,170.9812938413882,81.28167332365135,250.07896920659033C70.17666984294237,320.27484674793965,64.84698225790005,396.69656628748305,111.28512138212992,450.4950937839243C156.20124167950087,502.5303643271138,231.32542653798444,500.4755392045468,300,503.46388370962813"
                    ></path>
                  </svg>
                  <i class="bi bi-shield-check"></i>
                </div>
                <!-- <a href="service-details.html" class="stretched-link"> -->
                  <h3>Corporate Governance & Board Advisory</h3>
                </a>
                <p>Build trust, compliance, and leadership:</p>
                <ul>
                  <li>Board Effectiveness Reviews</li>
                  <li>Director Training & Governance Development</li>
                  <li>Risk & Compliance Oversight</li>
                  <li>Customized Governance Frameworks</li>
                </ul>
                <!-- <a href="service-details.html" class="stretched-link"></a> -->
              </div>
            </div>

            <!-- End Service Item -->

            <div
              class="col-lg-4 col-md-6"
              data-aos="fade-up"
              data-aos-delay="300"
            >
              <div class="service-item item-red position-relative">
                <div class="icon">
                  <svg
                    width="100"
                    height="100"
                    viewBox="0 0 600 600"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      stroke="none"
                      stroke-width="0"
                      fill="#f5f5f5"
                      d="M300,503.46388370962813C374.79870501325706,506.71871716319447,464.8034551963731,527.1746412648533,510.4981551193396,467.86667711651364C555.9287308511215,408.9015244558933,512.6030010748507,327.5744911775523,490.211057578863,256.5855673507754C471.097692560561,195.9906835881958,447.69079081568157,138.11976852964426,395.19560036434837,102.3242989838813C329.3053358748298,57.3949838291264,248.02791733380457,8.279543830951368,175.87071277845988,42.242879143198664C103.41431057327972,76.34704239035025,93.79494320519305,170.9812938413882,81.28167332365135,250.07896920659033C70.17666984294237,320.27484674793965,64.84698225790005,396.69656628748305,111.28512138212992,450.4950937839243C156.20124167950087,502.5303643271138,231.32542653798444,500.4755392045468,300,503.46388370962813"
                    ></path>
                  </svg>
                  <i class="bi bi-people"></i>
                </div>
                <!-- <a href="service-details.html" class="stretched-link"> -->
                  <h3>Executive Leadership & Strategic Planning</h3>
                </a>
                <p>Shape your leadership and future:</p>
                <ul>
                  <li>Succession Planning & Executive Coaching</li>
                  <li>Organizational Design</li>
                  <li>Visionary Strategic Planning</li>
                  <li>Operational Realignment</li>
                </ul>
                <!-- <a href="service-details.html" class="stretched-link"></a> -->
              </div>
            </div>

            <!-- End Service Item -->

            <div
              class="col-lg-4 col-md-6"
              data-aos="fade-up"
              data-aos-delay="600"
            >
              <div class="service-item item-teal position-relative">
                <div class="icon">
                  <svg
                    width="100"
                    height="100"
                    viewBox="0 0 600 600"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      stroke="none"
                      stroke-width="0"
                      fill="#f5f5f5"
                      d="M300,503.46388370962813C374.79870501325706,506.71871716319447,464.8034551963731,527.1746412648533,510.4981551193396,467.86667711651364C555.9287308511215,408.9015244558933,512.6030010748507,327.5744911775523,490.211057578863,256.5855673507754C471.097692560561,195.9906835881958,447.69079081568157,138.11976852964426,395.19560036434837,102.3242989838813C329.3053358748298,57.3949838291264,248.02791733380457,8.279543830951368,175.87071277845988,42.242879143198664C103.41431057327972,76.34704239035025,93.79494320519305,170.9812938413882,81.28167332365135,250.07896920659033C70.17666984294237,320.27484674793965,64.84698225790005,396.69656628748305,111.28512138212992,450.4950937839243C156.20124167950087,502.5303643271138,231.32542653798444,500.4755392045468,300,503.46388370962813"
                    ></path>
                  </svg>
                  <i class="bi bi-megaphone"></i>
                </div>
                <!-- <a href="service-details.html" class="stretched-link"> -->
                  <h3>Media & Communications Strategy</h3>
                </a>
                <p>Communicate with clarity and strength:</p>
                <ul>
                  <li>Crisis & Reputation Management</li>
                  <li>Media Positioning & Digital Strategy</li>
                  <li>Executive Communication Coaching</li>
                </ul>
                <!-- <a href="service-details.html" class="stretched-link"></a> -->
              </div>
            </div>

            <!-- End Service Item -->

            <div
              class="col-lg-4 col-md-6"
              data-aos="fade-up"
              data-aos-delay="400"
            >
              <div class="service-item item-indigo position-relative">
                <div class="icon">
                  <svg
                    width="100"
                    height="100"
                    viewBox="0 0 600 600"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      stroke="none"
                      stroke-width="0"
                      fill="#f5f5f5"
                      d="M300,503.46388370962813C374.79870501325706,506.71871716319447,464.8034551963731,527.1746412648533,510.4981551193396,467.86667711651364C555.9287308511215,408.9015244558933,512.6030010748507,327.5744911775523,490.211057578863,256.5855673507754C471.097692560561,195.9906835881958,447.69079081568157,138.11976852964426,395.19560036434837,102.3242989838813C329.3053358748298,57.3949838291264,248.02791733380457,8.279543830951368,175.87071277845988,42.242879143198664C103.41431057327972,76.34704239035025,93.79494320519305,170.9812938413882,81.28167332365135,250.07896920659033C70.17666984294237,320.27484674793965,64.84698225790005,396.69656628748305,111.28512138212992,450.4950937839243C156.20124167950087,502.5303643271138,231.32542653798444,500.4755392045468,300,503.46388370962813"
                    ></path>
                  </svg>
                  <i class="bi bi-currency-dollar"></i>
                </div>
                <!-- <a href="service-details.html" class="stretched-link"> -->
                  <h3>Financial Advisory & Risk Management</h3>
                </a>
                <p>Strengthen your financial core:</p>
                <ul>
                  <li>Corporate Finance & Capital Structuring</li>
                  <li>Commercial Banking Advice & Proposals</li>
                  <li>Investment Strategy & Portfolio Management</li>
                  <li>Risk Mitigation & Financial Forecasting</li>
                </ul>
                <!-- <a href="service-details.html" class="stretched-link"></a> -->
              </div>
            </div>

            <!-- End Service Item -->

            <div
              class="col-lg-4 col-md-6"
              data-aos="fade-up"
              data-aos-delay="500"
            >
              <div class="service-item item-pink position-relative">
                <div class="icon">
                  <svg
                    width="100"
                    height="100"
                    viewBox="0 0 600 600"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      stroke="none"
                      stroke-width="0"
                      fill="#f5f5f5"
                      d="M300,503.46388370962813C374.79870501325706,506.71871716319447,464.8034551963731,527.1746412648533,510.4981551193396,467.86667711651364C555.9287308511215,408.9015244558933,512.6030010748507,327.5744911775523,490.211057578863,256.5855673507754C471.097692560561,195.9906835881958,447.69079081568157,138.11976852964426,395.19560036434837,102.3242989838813C329.3053358748298,57.3949838291264,248.02791733380457,8.279543830951368,175.87071277845988,42.242879143198664C103.41431057327972,76.34704239035025,93.79494320519305,170.9812938413882,81.28167332365135,250.07896920659033C70.17666984294237,320.27484674793965,64.84698225790005,396.69656628748305,111.28512138212992,450.4950937839243C156.20124167950087,502.5303643271138,231.32542653798444,500.4755392045468,300,503.46388370962813"
                    ></path>
                  </svg>
                  <i class="bi bi-briefcase"></i>
                </div>
                <!-- <a href="service-details.html" class="stretched-link"> -->
                  <h3>Project Management & Business Expansion</h3>
                </a>
                <p>Execute with precision and scale effectively:</p>
                <ul>
                  <li>Project Oversight from Inception to Delivery</li>
                  <li>Mergers & Acquisitions (M&A)</li>
                  <li>International Market Entry</li>
                  <li>Scalable Operational Frameworks</li>
                </ul>
                <!-- <a href="service-details.html" class="stretched-link"></a> -->
              </div>
            </div>

            <!-- End Service Item -->
          </div>
        </div>
      </section>
      <!-- /Services Section -->

      <!-- Portfolio Section -->

      <!-- /Portfolio Section -->

      <!-- Clients Section -->

      <!-- /Clients Section -->
    </main>

    <footer id="footer" class="footer dark-background">
      <div class="container footer-top">
        <div class="row gy-4">
          <div class="col-lg-12 footer-about text-center">
            <a
              href="index.html"
              class="logo d-flex align-items-center justify-content-center"
            >
            
          <img src="assets/img/favicon.png" alt="" />
              <span class="sitename">Broadland Corporate Consulting</span>
            </a>
            <p><strong>Anthony Shaw</strong></p>

            <div class="footer-contact pt-3">
              <p><strong>Phone JA:</strong> 876-332-0408</p>
              <p><strong>Phone BD:</strong> 246-234-1500</p>
              <p>
                <strong>Email:</strong>
                <a href="mailto:broadlandsconsulting@gmail.com"
                  >broadlandsconsulting@gmail.com</a
                >
              </p>
            </div>
          </div>
        </div>
      </div>
    </footer>

    <!-- Scroll Top -->
    <a
      href="#"
      id="scroll-top"
      class="scroll-top d-flex align-items-center justify-content-center"
      ><i class="bi bi-arrow-up-short"></i
    ></a>

    <!-- Preloader -->
    <div id="preloader"></div>

    <!-- Vendor JS Files -->
    <script src="assets/vendor/bootstrap/js/bootstrap.bundle.min.js"></script>
    <script src="assets/vendor/php-email-form/validate.js"></script>
    <script src="assets/vendor/aos/aos.js"></script>
    <script src="assets/vendor/glightbox/js/glightbox.min.js"></script>
    <script src="assets/vendor/imagesloaded/imagesloaded.pkgd.min.js"></script>
    <script src="assets/vendor/isotope-layout/isotope.pkgd.min.js"></script>
    <script src="assets/vendor/waypoints/noframework.waypoints.js"></script>
    <script src="assets/vendor/swiper/swiper-bundle.min.js"></script>

    <!-- Main JS File -->
    <script src="assets/js/main.js"></script>
  </body>
</html>
