<template>
  <div>

    <button onclick="topFunction()" id="myBtn" title="Go to top"><img src="public/images/arrowhead-up.png" alt=""></button>
    

  

    <!-- slideshow section begins -->
    <div class="pad-style  slide-section">
        <div id="demo" class="carousel  " data-bs-ride="carousel">

            <!-- Indicators/dots -->
            <div class="carousel-indicators dots">
                <button type="button" data-bs-target="#demo" data-bs-slide-to="0" class="active"></button>
                <button type="button" data-bs-target="#demo" data-bs-slide-to="1"></button>
            </div>

            <!-- The slideshow/carousel -->
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <div class="d-block" style="width:100%">
                        <div class="row">
                            <div
                                class="col-lg-6  slide-text1 ps-5  animate__animated animate__slideInUp animate__delay-0.8s    ">
                                <h6><i class="fa fa-home home-ic me-1 "></i>Real Estate Agency</h6>
                                <h1 class="head h1">Find Your Dream House By Us</h1>
                                <p class="text1">Lorem ipsum, dolor sit amet consectetur
                                    commodi ipsum susdolorum voluptas excepturi doloremque
                                </p>
                                <button class="btn animate-btn ">Make An Enquiry</button>
                                <button class="vid-btn ms-3 "><a
                                        href="https://www.youtube.com/embed/HnbMYzdjuBs?autoplay=1&showinfo=0"><i
                                            class="fa fa-play home-ic"></i></a></button>
                            </div>
                            <div class="col-lg-6 f-slidep slide-pic">
                                <img src="@/images/hm.png" class="img-fluid w-75 " alt="">
                            </div>
                        </div>
                    </div>
                </div>
                <div class="carousel-item">
                    <div class="d-block" style="width:100%">
                        <div class="row">
                            <div class="col-lg-6  slide-pic">
                                <img src="@/images/hm.png" class="img-fluid  w-75" alt="">
                            </div>
                            <div
                                class="col-lg-6 slide-text2 animate__animated animate__slideInUp animate__delay-0.8s    ">
                                <h6><i class="fa fa-home home-ic me-1"></i>Real Estate Agency</h6>
                                <h1 class="head h11 h2">The Right Place Of House Finding</h1>
                                <p class="text2 h2-min">Lorem ipsum, dolor sit amet consectetur
                                    commodi ipsum susdolorum voluptas excepturi doloremque
                                </p>
                                <button class="btn animate-btn ">OUR SERVICES</button>
                                <button class="btn learn shadow  ">LEARN MORE</button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Left and right controls/icons -->
            <button class="carousel-control-prev prevcol " type="button" data-bs-target="#demo" data-bs-slide="prev">
                <span class="carousel-control-prev-icon"></span>
            </button>
            <button class="carousel-control-next prevcol" type="button" data-bs-target="#demo" data-bs-slide="next">
                <span class="carousel-control-next-icon"></span>
            </button>
        </div>
    </div>

    <!-- slideshow section ends -->
    <!-- relative top begins -->
    <div class="find-now shadow">
        <div class="dropdown d-inline">
            <button type="button" class="drop-btn dbtn dropdown-toggle" data-bs-toggle="dropdown">
                Choose Area
            </button>
            <ul class="dropdown-menu">
                <li>
                    <h1 class="dropdown-header">Choose Area</h1>
                </li>
                <li><a class="dropdown-item" href="#">Chicago </a></li>
                <li><a class="dropdown-item" href="#">London </a></li>
                <li><a class="dropdown-item" href="#">Los Angeles </a></li>
                <li><a class="dropdown-item" href="#">New York </a></li>
                <li><a class="dropdown-item" href="#">New Jersey </a></li>
            </ul>
        </div>


        <div class="dropdown d-inline">
            <button type="button" class="drop-btn dbtn1 dropdown-toggle" data-bs-toggle="dropdown">
                Property Status
            </button>
            <ul class="dropdown-menu">
                <li>
                    <h1 class="dropdown-header">Property Status </h1>
                </li>
                <li><a class="dropdown-item" href="#">Open House </a></li>
                <li><a class="dropdown-item" href="#">Rent </a></li>
                <li><a class="dropdown-item" href="#">Sale </a></li>
                <li><a class="dropdown-item" href="#">Sold </a></li>
            </ul>
        </div>



        <div class="dropdown d-inline">
            <button type="button" class="drop-btn dbtn dropdown-toggle" data-bs-toggle="dropdown">
                Property Type
            </button>
            <ul class="dropdown-menu">
                <li>
                    <h1 class="dropdown-header ">Property Type </h1>
                </li>
                <li><a class="dropdown-item" href="#">Apartment </a></li>
                <li><a class="dropdown-item" href="#">Co-op </a></li>
                <li><a class="dropdown-item" href="#">Condo </a></li>
                <li><a class="dropdown-item" href="#">Single Family Home </a></li>
            </ul>
        </div>

        <button class="btn animate-btn find ">FIND NOW </button>
    </div>
    <!-- relative top ends -->

    <!-- about us section  begins-->
    <div class="pad-style ab-div ">
        <div class="row ">
            <div class="col-lg-5 ps abimg">
                <img src="@/images/abimg1.png" class="img-fluid absolute-img" alt="">

                <img src="@/images/minigrid3.jpg" class="img-fluid w-75 p-5 vid-bg" alt="">

                <button class="vid-btn ms-3 vid-bg-btn "><a
                        href="https://www.youtube.com/embed/X7R-q9rsrtU?autoplay=1&showinfo=0"><i
                            class="fa fa-play home-ic"></i></a></button>

            </div>
            <div class="col-lg-7  ab">
                <div class="ab-icon mb-2">
                    About Us
                </div>
                <h1 class="head ab-head">The Leading Real Estate Rental Marketplace<span class="home-ic">.</span></h1>
                <p class="pe-5 mt-3 mb-4 ab-text">
                    Over 39,000 people work for us in more than 70 countries all
                    over the This breadth of global coverage, combined with specialist services
                </p>

                <div class="row mt-4 mb-3">
                    <div class="col-md-6">
                        <img src="@/images/homie.png" class=" me-1 icons img-fluid " alt="">
                        <span>Smart Home Design</span>
                    </div>
                    <div class="col-md-6 pe-5 ab-subtext">
                        <img src="@/images/mountain.png" class="home-ic me-1  icons img-fluid " alt="">
                        <span class=" me-5 ">Beautiful Scene Around</span>
                    </div>
                </div>
                <div class="row mb-5">
                    <div class="col-md-6">
                        <img src="@/images/heart-attack.png" class=" me-1 icons img-fluid " alt="">
                        <span>Exceptional Lifestyle</span>
                    </div>
                    <div class="col-md-6 ab-subtext">
                        <img src="@/images/security.png" class="home-ic me-1  icons img-fluid " alt="">
                        <span>Complete 24/7 Security</span>
                    </div>
                </div>


                <p class="txt-bg ">"Enimad minim veniam quis nostrud exercitation
                    llamco laboris. Lorem ipsum dolor sit amet"
                </p>
                <button class="btn animate-btn mt-4 ">OUR SERVICES</button>
            </div>
        </div>
    </div>
    <!-- about us section ends-->


    <!-- counter section -->
    <div class="counter-div  ">
        <div class="row">
            <div class="col-md-3 count-pad">
                <img src="@/images/excavator.png" class="img-fluid counter-img" alt="">
                <h1 class=""><span class="count">560</span>+</h1>
                <p class="count-p">Total Area Sq</p>
            </div>
            <div class="col-md-3 count-pad">
                <img src="@/images/office-building.png" class="img-fluid counter-img" alt="">
                <h1 class=""><span class="count">197</span>k+</h1>
                <p class="count-p">Apartments Sold</p>
            </div>
            <div class="col-md-3 count-pad">
                <img src="@/images/excavator.png" class="img-fluid counter-img" alt="">
                <h1 class=""><span class="count">268</span>+</h1>
                <p class="count-p">Total Constructions</p>
            </div>
            <div class="col-md-3 count-pad">
                <img src="@/images/armchair (1).png" class="img-fluid counter-img" alt="">
                <h1 class=""><span class="count">340</span>+</h1>
                <p class="count-p">Apartio Rooms</p>
            </div>
        </div>

    </div>
    <!-- second about us section begins -->

    <div class="sec-ab-div ab-div2">
        <div class="row">
            <div class="col-lg-6 sec-ab-pad ">
                <div class="ab-icon mb-1">
                    About Us
                </div>
                <h1 class="head ab-head mt-3">Today Sells Properties</h1>
                <p class=" mt-3 ab-text mb-4">
                    Houzez allow you to design unlimited panels and real
                    estate custom forms to capture leads and keep record of all information
                </p>
                <p class="mb-4"><span class="home-ic me-2">-</span>Live Music Cocerts at Luviana</p>
                <p class="mb-4"><span class="home-ic me-2">-</span>Our SecretIsland Boat Tour is Just for You</p>
                <p class="mb-4"><span class="home-ic me-2">-</span>Live Music Cocerts at Luviana</p>
                <p><span class="home-ic me-2 ">-</span>Live Music Cocerts at Luviana</p>
                <div class="row text-ic-div">
                    <div class="col-lg-12 mt-3 d-flex">
                        <div class="bd-rt pe-3">
                            <span class="mb-5 ab-text">3</span>
                            <img src="@/images/bed (1).png" class="mb-1" alt="">
                            <span class="d-block ab-text1">Bedrooms</span>
                        </div>
                        <div class="bd-rt ps-3 pe-3">
                            <span class="mb-5 ab-text">2</span>
                            <img src="@/images/clean (1).png" class="mb-1" alt="">
                            <span class="d-block ab-text1">Bathrooms</span>
                        </div>
                        <div class="bd-rt ps-3 pe-3">
                            <span class="mb-5 ab-text">2</span>
                            <img src="@/images/electric-car (2).png" class="mb-1" alt="">
                            <span class="d-block ab-text1">Car Parking</span>
                        </div>
                        <div class="ps-3">
                            <span class="mb-5 ab-text">3450</span>
                            <img src="@/images/selection (1).png" class="mb-1" alt="">
                            <span class="d-block ab-text1">square Ft</span>
                        </div>
                    </div>
                </div>
                <div class="row mini-grid-div mt-4">
                    <div class="col-lg-12 ">
                        <img src="@/images/minigrid1.jpg" class="img-fluid w-25 me-4" alt="">
                        <img src="@/images/minigrid2.jpg" class="img-fluid w-25  me-4 " alt="">
                        <img src="@/images/minigrid3.jpg" class="img-fluid w-25  " alt="">
                    </div>
                </div>
            </div>
            <div class="col-lg-6 grid">
                <img src="@/images/gridimg1.png" class="img-fluid" alt="">
            </div>
        </div>
    </div>

    <!-- second about us section ends -->


    <!-- services section begins -->
    <div class="services-div">
        <center>
            <div class="ab-icon mb-3 ">
                Our Services
            </div>
            <h1 class="head ab-head">Our Main Focus</h1>
        </center>

        <div class="row mt-5">
            <div class="col-lg-4 col-md-6">
                <div class="card card-body serv shadow pt-5 pb-5 bg-white crd-space">
                    <center>
                        <img src="@/images/crd1pic.png" class="img-fluid  w-50" alt="">
                        <h3>Buy a home</h3>
                        <p>over 1 million+ homes for sale available on the website,
                            we can match you with a house you will want to call home.</p>
                        <a href="#" class="ser-a">Find A Home <i class="fa fa-arrow-right  "></i></a>
                    </center>
                </div>
            </div>
            <div class="col-lg-4 col-md-6">
                <div class="card card-body serv shadow pt-5 pb-5 bg-white crd-space">
                    <center>
                        <img src="@/images/crd2pic.png" class="img-fluid w-50" alt="">
                        <h3>Rent a home</h3>
                        <p>over 1 million+ homes for sale available on the website,
                            we can match you with a house you will want to call home.</p>
                        <a href="#" class="ser-a">Find A Home <i class="fa fa-arrow-right  "></i></a>
                    </center>
                </div>
            </div>
            <div class="col-lg-4 col-md-6 lone-crd">
                <div class="card card-body serv shadow pt-5 pb-5 bg-white">
                    <center>
                        <img src="@/images/crd3pic.png" class="img-fluid w-50" alt="">
                        <h3>Sell a home</h3>
                        <p>over 1 million+ homes for sale available on the website,
                            we can match you with a house you will want to call home.</p>
                        <a href="#" class="ser-a">Find A Home <i class="fa fa-arrow-right  "></i></a>
                    </center>
                </div>
            </div>
        </div>
    </div>
    <!-- services section ends -->

    <!-- properties section begins -->

    <div class="props-secc">
        <center>
            <div class="ab-icon mb-3 props">
                Properties
            </div>
            <h1 class="head ab-head mb-5">Featured Listings</h1>
        </center>

        <div id="demo" class="carousel  " data-bs-ride="carousel">




            <!-- The slideshow/carousel -->
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <div class="d-block" style="width:100%">
                        <div class="row">
                            <div class="col-lg-4 col-md-6 hide-md ">
                                <div class="card shadow" style="width:400px">

                                    <img class="card-img-top " src="@/images/im1.jpg" alt="Card image" style="width:100%">

                                    <div class="card-img-overlay">
                                        <h4 class=" crd-title bg-sale">FOR SALE</h4>
                                        <div class="text-overlay  text-overlay-space">
                                            <a href="#" class="text-white a-style1 text-sp ">
                                                <img src="@/images/pin.png" alt="">
                                                Belmont Gardens, Chicago</a>
                                            <span class="propicon-bg space2 padd">
                                                <img src="@/images/photo.png" alt="">
                                                <span class="ms-1 text-white">4</span>
                                            </span>
                                            <span class="propicon-bg ms-2 padd ">
                                                <img src="@/images/film.png" alt="">
                                                <span class="ms-1 text-white">2</span>
                                            </span>

                                        </div>

                                    </div>
                                    <div class="card-body">
                                        <span class="home-ic ">$34,900<label>/Month</label></span>
                                        <h4 class="card-title mt-3 liit">New Apartment Nice View</h4>
                                        <p class="card-text mt-3 props-icon ">Beautiful Huge 1 Family House In Heart Of
                                            <br>
                                            Westbury. Newly Renovated With New Wood
                                        </p>
                                        <div class="row ">
                                            <div class="col-lg-12 mt-3 d-flex">
                                                <div class="bd-rt pe-3">
                                                    <span class="mb-5 props-icon">3</span>
                                                    <img src="@/images/bed (1).png" class="mb-1" alt="">
                                                    <span class="d-block props-icon">Bedrooms</span>
                                                </div>
                                                <div class="bd-rt ps-3 pe-3">
                                                    <span class="mb-5 props-icon">2</span>
                                                    <img src="@/images/clean (1).png" class="mb-1" alt="">
                                                    <span class="d-block props-icon">Bathrooms</span>
                                                </div>
                                                <div class="ps-3">
                                                    <span class="mb-5 props-icon">3450</span>
                                                    <img src="@/images/selection (1).png" class="mb-1" alt="">
                                                    <span class="d-block props-icon">square Ft</span>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="row crd-hr">
                                            <div class="col-md-7 d-flex ">
                                                <img src="@/images/author.jpg" class="img-fluid crd-sm-im w-25" alt="">
                                                <div class="ms-3">
                                                    <span class=" fsize">William Sekio</span>
                                                    <br>
                                                    <span class="fsize props-icon">Estate Agents</span>
                                                </div>


                                            </div>
                                            <div class="col-md-5 ic-marg mt-3">

                                                <span class="ic-container me-1"><img src="@/images/expand.png"
                                                        alt=""></span>
                                                <span class="ic-container me-1"><img src="@/images/heart.png"
                                                        alt=""></span>
                                                <span class="ic-container"><img src="@/images/add.png" alt=""></span>

                                            </div>
                                        </div>

                                    </div>
                                </div>
                            </div>
                            <div class="col-lg-4 col-md-6 hidee">
                                <div class="card shadow" style="width:400px">
                                    <img class="card-img-top" src="@/images/im2.jpg" alt="Card image" style="width:100%">
                                    <div class="card-img-overlay">
                                        <h4 class=" crd-title bg-rent">FOR RENT</h4>
                                        <div class="text-overlay text-overlay-space">
                                            <a href="#" class="text-white  a-style1 ">
                                                <img src="@/images/pin.png" alt="">
                                                Belmont Gardens, Chicago</a>

                                            <span class="propicon-bg space2 padd">
                                                <img src="@/images/photo.png" alt="">
                                                <span class="ms-1 text-white">4</span>
                                            </span>
                                            <span class="propicon-bg ms-2 padd">
                                                <img src="@/images/film.png" alt="">
                                                <span class="ms-1 text-white">2</span>
                                            </span>

                                        </div>


                                    </div>
                                    <div class="card-body">
                                        <span class="home-ic ">$34,900<label>/Month</label></span>
                                        <h4 class="card-title mt-3 li-it">Modern Apartment </h4>
                                        <p class="card-text mt-3 props-icon ">Beautiful Huge 1 Family House In Heart Of
                                            <br>
                                            Westbury. Newly Renovated With New Wood
                                        </p>
                                        <div class="row ">
                                            <div class="col-lg-12 mt-3 d-flex">
                                                <div class="bd-rt pe-3">
                                                    <span class="mb-5 props-icon">3</span>
                                                    <img src="@/images/bed (1).png" class="mb-1" alt="">
                                                    <span class="d-block props-icon">Bedrooms</span>
                                                </div>
                                                <div class="bd-rt ps-3 pe-3">
                                                    <span class="mb-5 props-icon">2</span>
                                                    <img src="@/images/clean (1).png" class="mb-1" alt="">
                                                    <span class="d-block props-icon">Bathrooms</span>
                                                </div>
                                                <div class="ps-3">
                                                    <span class="mb-5 props-icon">3450</span>
                                                    <img src="@/images/selection (1).png" class="mb-1" alt="">
                                                    <span class="d-block props-icon">square Ft</span>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="row crd-hr">
                                            <div class="col-md-7 d-flex ">
                                                <img src="@/images/author.jpg" class="img-fluid crd-sm-im w-25" alt="">
                                                <div class="ms-3">
                                                    <span class="fs-6">William Sekio</span>
                                                    <br>
                                                    <span class="fs-6 props-icon">Estate Agents</span>
                                                </div>


                                            </div>
                                            <div class="col-md-5 mt-3">

                                                <span class="ic-container me-1"><img src="@/images/expand.png"
                                                        alt=""></span>
                                                <span class="ic-container me-1"><img src="@/images/heart.png"
                                                        alt=""></span>
                                                <span class="ic-container"><img src="@/images/add.png" alt=""></span>

                                            </div>
                                        </div>

                                    </div>
                                </div>
                            </div>
                            <div class="col-lg-4 col-md-6 hidee ">
                                <div class="card shadow" style="width:400px">
                                    <img class="card-img-top" src="@/images/im3.jpg" alt="Card image" style="width:100%">
                                    <div class="card-img-overlay">
                                        <h4 class=" crd-title bg-sale">FOR SALE</h4>
                                        <div class="text-overlay text-overlay-space">
                                            <a href="#" class="text-white a-style1 ">
                                                <img src="@/images/pin.png" alt="">
                                                Belmont Gardens, Chicago</a>
                                            <span class="propicon-bg space2 padd">
                                                <img src="@/images/photo.png" alt="">
                                                <span class="ms-1 text-white">4</span>
                                            </span>
                                            <span class="propicon-bg ms-2 padd">
                                                <img src="@/images/film.png" alt="">
                                                <span class="ms-1 text-white">2</span>
                                            </span>

                                        </div>


                                    </div>
                                    <div class="card-body">
                                        <span class="home-ic ">$34,900<label>/Month</label></span>
                                        <h4 class="card-title mt-3 li-it">Comfortable Apartment </h4>
                                        <p class="card-text mt-3 props-icon ">Beautiful Huge 1 Family House In Heart Of
                                            <br>
                                            Westbury. Newly Renovated With New Wood
                                        </p>
                                        <div class="row ">
                                            <div class="col-lg-12 mt-3 d-flex">
                                                <div class="bd-rt pe-3">
                                                    <span class="mb-5 props-icon">3</span>
                                                    <img src="@/images/bed (1).png" class="mb-1" alt="">
                                                    <span class="d-block props-icon">Bedrooms</span>
                                                </div>
                                                <div class="bd-rt ps-3 pe-3">
                                                    <span class="mb-5 props-icon">2</span>
                                                    <img src="@/images/clean (1).png" class="mb-1" alt="">
                                                    <span class="d-block props-icon">Bathrooms</span>
                                                </div>
                                                <div class="ps-3">
                                                    <span class="mb-5 props-icon">3450</span>
                                                    <img src="@/images/selection (1).png" class="mb-1" alt="">
                                                    <span class="d-block props-icon">square Ft</span>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="row crd-hr">
                                            <div class="col-md-7 d-flex ">
                                                <img src="@/images/author.jpg" class="img-fluid crd-sm-im w-25" alt="">
                                                <div class="ms-3">
                                                    <span class="fs-6">William Sekio</span>
                                                    <br>
                                                    <span class="fs-6 props-icon">Estate Agents</span>
                                                </div>


                                            </div>
                                            <div class="col-md-5 mt-3">

                                                <span class="ic-container me-1"><img src="@/images/expand.png"
                                                        alt=""></span>
                                                <span class="ic-container me-1"><img src="@/images/heart.png"
                                                        alt=""></span>
                                                <span class="ic-container"><img src="@/images/add.png" alt=""></span>

                                            </div>
                                        </div>

                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="carousel-item">
                    <div class="d-block" style="width:100%">
                        <div class="row">
                            <div class="col-lg-4 col-md-6 hide-md ">
                                <div class="card shadow" style="width:400px">
                                    <img class="card-img-top" src="@/images/im2.jpg" alt="Card image" style="width:100%">
                                    <div class="card-img-overlay">
                                        <h4 class="bg-rent crd-title">FOR RENT</h4>
                                        <div class="text-overlay text-overlay-space">
                                            <a href="#" class="text-white a-style1 text-sp">
                                                <img src="@/images/pin.png" alt="">
                                                Belmont Gardens, Chicago</a>
                                            <span class="propicon-bg space2 padd">
                                                <img src="@/images/photo.png" alt="">
                                                <span class="ms-1 text-white">4</span>
                                            </span>
                                            <span class="propicon-bg ms-2 padd">
                                                <img src="@/images/film.png" alt="">
                                                <span class="ms-1 text-white">2</span>
                                            </span>

                                        </div>


                                    </div>
                                    <div class="card-body">
                                        <span class="home-ic ">$34,900<label>/Month</label></span>
                                        <h4 class="card-title mt-3 li-it">Luxuru Villa In Rego Park </h4>
                                        <p class="card-text mt-3 props-icon ">Beautiful Huge 1 Family House In Heart Of
                                            <br>
                                            Westbury. Newly Renovated With New Wood
                                        </p>
                                        <div class="row ">
                                            <div class="col-lg-12 mt-3 d-flex">
                                                <div class="bd-rt pe-3">
                                                    <span class="mb-5 props-icon">3</span>
                                                    <img src="@/images/bed (1).png" class="mb-1" alt="">
                                                    <span class="d-block props-icon">Bedrooms</span>
                                                </div>
                                                <div class="bd-rt ps-3 pe-3">
                                                    <span class="mb-5 props-icon">2</span>
                                                    <img src="@/images/clean (1).png" class="mb-1" alt="">
                                                    <span class="d-block props-icon">Bathrooms</span>
                                                </div>
                                                <div class="ps-3">
                                                    <span class="mb-5 props-icon">3450</span>
                                                    <img src="@/images/selection (1).png" class="mb-1" alt="">
                                                    <span class="d-block props-icon">square Ft</span>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="row crd-hr">
                                            <div class="col-md-7 d-flex ">
                                                <img src="@/images/author.jpg" class="img-fluid crd-sm-im w-25" alt="">
                                                <div class="ms-3">
                                                    <span class="fsize">William Sekio</span>
                                                    <br>
                                                    <span class="fsize props-icon">Estate Agents</span>
                                                </div>


                                            </div>
                                            <div class="col-md-5 ic-marg mt-3">

                                                <span class="ic-container me-1"><img src="@/images/expand.png"
                                                        alt=""></span>
                                                <span class="ic-container me-1"><img src="@/images/heart.png"
                                                        alt=""></span>
                                                <span class="ic-container"><img src="@/images/add.png" alt=""></span>

                                            </div>
                                        </div>

                                    </div>
                                </div>
                            </div>
                            <div class="col-lg-4 col-md-6 hidee">
                                <div class="card shadow" style="width:400px">
                                    <img class="card-img-top" src="@/images/im3.jpg" alt="Card image" style="width:100%">
                                    <div class="card-img-overlay">
                                        <h4 class="bg-sale crd-title">FOR SALE</h4>
                                        <div class="text-overlay text-overlay-space">
                                            <a href="#" class="text-white a-style1 ">
                                                <img src="@/images/pin.png" alt="">
                                                Belmont Gardens, Chicago</a>
                                            <span class="propicon-bg space2 padd">
                                                <img src="@/images/photo.png" alt="">
                                                <span class="ms-1 text-white">4</span>
                                            </span>
                                            <span class="propicon-bg ms-2 padd">
                                                <img src="@/images/film.png" alt="">
                                                <span class="ms-1 text-white">2</span>
                                            </span>

                                        </div>

                                    </div>
                                    <div class="card-body">
                                        <span class="home-ic ">$34,900<label>/Month</label></span>
                                        <h4 class="card-title mt-3 li-it">Beatiful Flat In Manhatan </h4>
                                        <p class="card-text mt-3 props-icon ">Beautiful Huge 1 Family House In Heart Of
                                            <br>
                                            Westbury. Newly Renovated With New Wood
                                        </p>
                                        <div class="row ">
                                            <div class="col-lg-12 mt-3 d-flex">
                                                <div class="bd-rt pe-3">
                                                    <span class="mb-5 props-icon">3</span>
                                                    <img src="@/images/bed (1).png" class="mb-1" alt="">
                                                    <span class="d-block props-icon">Bedrooms</span>
                                                </div>
                                                <div class="bd-rt ps-3 pe-3">
                                                    <span class="mb-5 props-icon">2</span>
                                                    <img src="@/images/clean (1).png" class="mb-1" alt="">
                                                    <span class="d-block props-icon">Bathrooms</span>
                                                </div>
                                                <div class="ps-3">
                                                    <span class="mb-5 props-icon">3450</span>
                                                    <img src="@/images/selection (1).png" class="mb-1" alt="">
                                                    <span class="d-block props-icon">square Ft</span>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="row crd-hr">
                                            <div class="col-md-7 d-flex ">
                                                <img src="@/images/author.jpg" class="img-fluid crd-sm-im w-25" alt="">
                                                <div class="ms-3 ">
                                                    <span class="fs-6">William Sekio</span>
                                                    <br>
                                                    <span class="fs-6 props-icon">Estate Agents</span>
                                                </div>


                                            </div>
                                            <div class="col-md-5 mt-3">

                                                <span class="ic-container me-1"><img src="@/images/expand.png"
                                                        alt=""></span>
                                                <span class="ic-container me-1"><img src="@/images/heart.png"
                                                        alt=""></span>
                                                <span class="ic-container"><img src="@/images/add.png" alt=""></span>

                                            </div>
                                        </div>

                                    </div>
                                </div>
                            </div>
                            <div class="col-lg-4 col-md-6  hidee ">
                                <div class="card shadow" style="width:400px">
                                    <img class="card-img-top" src="@/images/img4.jpg" alt="Card image" style="width:100%">
                                    <div class="card-img-overlay">
                                        <h4 class=" bg-rent crd-title">FOR RENT</h4>
                                        <div class="text-overlay text-overlay-space">
                                            <a href="#" class="text-white a-style1 ">
                                                <img src="@/images/pin.png" alt="">
                                                Belmont Gardens, Chicago</a>
                                            <span class="propicon-bg space2 padd">
                                                <img src="@/images/photo.png" alt="">
                                                <span class="ms-1 text-white">4</span>
                                            </span>
                                            <span class="propicon-bg ms-2 padd">
                                                <img src="@/images/film.png" alt="">
                                                <span class="ms-1 text-white">2</span>
                                            </span>

                                        </div>

                                    </div>
                                    <div class="card-body">
                                        <span class="home-ic ">$34,900<label>/Month</label></span>
                                        <h4 class="card-title mt-3 li-it">New Apartment Nice View</h4>
                                        <p class="card-text mt-3 props-icon ">Beautiful Huge 1 Family House In Heart Of
                                            <br>
                                            Westbury. Newly Renovated With New Wood
                                        </p>
                                        <div class="row ">
                                            <div class="col-lg-12 mt-3 d-flex">
                                                <div class="bd-rt pe-3">
                                                    <span class="mb-5 props-icon">3</span>
                                                    <img src="@/images/bed (1).png" class="mb-1" alt="">
                                                    <span class="d-block props-icon">Bedrooms</span>
                                                </div>
                                                <div class="bd-rt ps-3 pe-3">
                                                    <span class="mb-5 props-icon">2</span>
                                                    <img src="@/images/clean (1).png" class="mb-1" alt="">
                                                    <span class="d-block props-icon">Bathrooms</span>
                                                </div>
                                                <div class="ps-3">
                                                    <span class="mb-5 props-icon">3450</span>
                                                    <img src="@/images/selection (1).png" class="mb-1" alt="">
                                                    <span class="d-block props-icon">square Ft</span>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="row crd-hr">
                                            <div class="col-md-7 d-flex ">
                                                <img src="@/images/author.jpg" class="img-fluid crd-sm-im w-25" alt="">
                                                <div class="ms-3">
                                                    <span class="fs-6">William Sekio</span>
                                                    <br>
                                                    <span class="fs-6 props-icon">Estate Agents</span>
                                                </div>


                                            </div>
                                            <div class="col-md-5 mt-3">

                                                <span class="ic-container me-1"><img src="@/images/expand.png"
                                                        alt=""></span>
                                                <span class="ic-container me-1"><img src="@/images/heart.png"
                                                        alt=""></span>
                                                <span class="ic-container"><img src="@/images/add.png" alt=""></span>

                                            </div>
                                        </div>

                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="carousel-item">
                    <div class="d-block" style="width:100%">
                        <div class="row">
                            <div class="col-lg-4 col-md-6 hide-md ">
                                <div class="card shadow" style="width:400px">

                                    <img class="card-img-top img-zoom" src="@/images/im3.jpg" alt="Card image"
                                        style="width:100%">

                                    <div class="card-img-overlay">
                                        <h4 class="bg-rent crd-title">FOR RENT</h4>
                                        <div class="text-overlay text-overlay-space">
                                            <a href="#" class="text-white a-style1 text-sp">
                                                <img src="@/images/pin.png" alt="">
                                                Belmont Gardens, Chicago</a>
                                            <span class="propicon-bg space2 padd">
                                                <img src="@/images/photo.png" alt="">
                                                <span class="ms-1 text-white">4</span>
                                            </span>
                                            <span class="propicon-bg ms-2 padd">
                                                <img src="@/images/film.png" alt="">
                                                <span class="ms-1 text-white">2</span>
                                            </span>

                                        </div>


                                    </div>
                                    <div class="card-body">
                                        <span class="home-ic ">$34,900<label>/Month</label></span>
                                        <h4 class="card-title mt-3 li-it">New Apartment Nice View</h4>
                                        <p class="card-text mt-3 props-icon ">Beautiful Huge 1 Family House In Heart Of
                                            <br>
                                            Westbury. Newly Renovated With New Wood
                                        </p>
                                        <div class="row ">
                                            <div class="col-lg-12 mt-3 d-flex">
                                                <div class="bd-rt pe-3">
                                                    <span class="mb-5 props-icon">3</span>
                                                    <img src="@/images/bed (1).png" class="mb-1" alt="">
                                                    <span class="d-block props-icon">Bedrooms</span>
                                                </div>
                                                <div class="bd-rt ps-3 pe-3">
                                                    <span class="mb-5 props-icon">2</span>
                                                    <img src="@/images/clean (1).png" class="mb-1" alt="">
                                                    <span class="d-block props-icon">Bathrooms</span>
                                                </div>
                                                <div class="ps-3">
                                                    <span class="mb-5 props-icon">3450</span>
                                                    <img src="@/images/selection (1).png" class="mb-1" alt="">
                                                    <span class="d-block props-icon">square Ft</span>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="row crd-hr">
                                            <div class="col-md-7 d-flex ">
                                                <img src="@/images/author.jpg" class="img-fluid crd-sm-im w-25" alt="">
                                                <div class="ms-3">
                                                    <span class="fsize">William Sekio</span>
                                                    <br>
                                                    <span class="fsize props-icon">Estate Agents</span>
                                                </div>


                                            </div>
                                            <div class="col-md-5 ic-marg  mt-3">

                                                <span class="ic-container me-1"><img src="@/images/expand.png"
                                                        alt=""></span>
                                                <span class="ic-container me-1"><img src="@/images/heart.png"
                                                        alt=""></span>
                                                <span class="ic-container"><img src="@/images/add.png" alt=""></span>

                                            </div>
                                        </div>

                                    </div>
                                </div>
                            </div>
                            <div class="col-lg-4 col-md-6 hidee">
                                <div class="card shadow" style="width:400px">
                                    <img class="card-img-top" src="@/images/img4.jpg" alt="Card image" style="width:100%">
                                    <div class="card-img-overlay">
                                        <h4 class="bg-sale crd-title">FOR SALE</h4>
                                        <div class="text-overlay text-overlay-space">
                                            <a href="#" class="text-white a-style1 ">
                                                <img src="@/images/pin.png" alt="">
                                                Belmont Gardens, Chicago</a>
                                            <span class="propicon-bg space2 padd">
                                                <img src="@/images/photo.png" alt="">
                                                <span class="ms-1 text-white">4</span>
                                            </span>
                                            <span class="propicon-bg ms-2 padd">
                                                <img src="@/images/film.png" alt="">
                                                <span class="ms-1 text-white">2</span>
                                            </span>

                                        </div>

                                    </div>
                                    <div class="card-body">
                                        <span class="home-ic ">$34,900<label>/Month</label></span>
                                        <h4 class="card-title mt-3 li-it">New Apartment Nice View</h4>
                                        <p class="card-text mt-3 props-icon ">Beautiful Huge 1 Family House In Heart Of
                                            <br>
                                            Westbury. Newly Renovated With New Wood
                                        </p>
                                        <div class="row ">
                                            <div class="col-lg-12 mt-3 d-flex">
                                                <div class="bd-rt pe-3">
                                                    <span class="mb-5 props-icon">3</span>
                                                    <img src="@/images/bed (1).png" class="mb-1" alt="">
                                                    <span class="d-block props-icon">Bedrooms</span>
                                                </div>
                                                <div class="bd-rt ps-3 pe-3">
                                                    <span class="mb-5 props-icon">2</span>
                                                    <img src="@/images/clean (1).png" class="mb-1" alt="">
                                                    <span class="d-block props-icon">Bathrooms</span>
                                                </div>
                                                <div class="ps-3">
                                                    <span class="mb-5 props-icon">3450</span>
                                                    <img src="@/images/selection (1).png" class="mb-1" alt="">
                                                    <span class="d-block props-icon">square Ft</span>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="row crd-hr">
                                            <div class="col-md-7 d-flex ">
                                                <img src="@/images/author.jpg" class="img-fluid crd-sm-im w-25" alt="">
                                                <div class="ms-3">
                                                    <span class="fs-6">William Sekio</span>
                                                    <br>
                                                    <span class="fs-6 props-icon">Estate Agents</span>
                                                </div>


                                            </div>
                                            <div class="col-md-5 mt-3">

                                                <span class="ic-container me-1"><img src="@/images/expand.png"
                                                        alt=""></span>
                                                <span class="ic-container me-1"><img src="@/images/heart.png"
                                                        alt=""></span>
                                                <span class="ic-container"><img src="@/images/add.png" alt=""></span>

                                            </div>
                                        </div>

                                    </div>
                                </div>
                            </div>
                            <div class="col-lg-4 col-md-6  hidee ">
                                <div class="card shadow" style="width:400px">
                                    <img class="card-img-top" src="@/images/im5.jpg" alt="Card image" style="width:100%">
                                    <div class="card-img-overlay">
                                        <h4 class="bg-rent crd-title">FOR RENT</h4>
                                        <div class="text-overlay text-overlay-space">
                                            <a href="#" class="text-white a-style1 ">
                                                <img src="@/images/pin.png" alt="">
                                                Belmont Gardens, Chicago</a>
                                            <span class="propicon-bg space2 padd">
                                                <img src="@/images/photo.png" alt="">
                                                <span class="ms-1 text-white">4</span>
                                            </span>
                                            <span class="propicon-bg ms-2 padd">
                                                <img src="@/images/film.png" alt="">
                                                <span class="ms-1 text-white">2</span>
                                            </span>

                                        </div>


                                    </div>
                                    <div class="card-body">
                                        <span class="home-ic ">$34,900<label>/Month</label></span>
                                        <h4 class="card-title mt-3 li-it">New Apartment Nice View</h4>
                                        <p class="card-text mt-3 props-icon ">Beautiful Huge 1 Family House In Heart Of
                                            <br>
                                            Westbury. Newly Renovated With New Wood
                                        </p>
                                        <div class="row ">
                                            <div class="col-lg-12 mt-3 d-flex">
                                                <div class="bd-rt pe-3">
                                                    <span class="mb-5 props-icon">3</span>
                                                    <img src="@/images/bed (1).png" class="mb-1" alt="">
                                                    <span class="d-block props-icon">Bedrooms</span>
                                                </div>
                                                <div class="bd-rt ps-3 pe-3">
                                                    <span class="mb-5 props-icon">2</span>
                                                    <img src="@/images/clean (1).png" class="mb-1" alt="">
                                                    <span class="d-block props-icon">Bathrooms</span>
                                                </div>
                                                <div class="ps-3">
                                                    <span class="mb-5props-icon">3450</span>
                                                    <img src="@/images/selection (1).png" class="mb-1" alt="">
                                                    <span class="d-block props-icon ">square Ft</span>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="row crd-hr">
                                            <div class="col-md-7 d-flex ">
                                                <img src="@/images/author.jpg" class="img-fluid crd-sm-im w-25" alt="">
                                                <div class="ms-3">
                                                    <span class="fs-6">William Sekio</span>
                                                    <br>
                                                    <span class="fs-6 props-icon">Estate Agents</span>
                                                </div>


                                            </div>
                                            <div class="col-md-5 mt-3">

                                                <span class="ic-container me-1"><img src="@/images/expand.png"
                                                        alt=""></span>
                                                <span class="ic-container me-1"><img src="@/images/heart.png"
                                                        alt=""></span>
                                                <span class="ic-container"><img src="@/images/add.png" alt=""></span>

                                            </div>
                                        </div>

                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="carousel-item">
                    <div class="d-block" style="width:100%">
                        <div class="row">
                            <div class="col-lg-4 col-md-6 hide-md ">
                                <div class="card shadow" style="width:400px">

                                    <img class="card-img-top img-zoom" src="@/images/img4.jpg" alt="Card image"
                                        style="width:100%">

                                    <div class="card-img-overlay">
                                        <h4 class="bg-rent crd-title">FOR RENT</h4>
                                        <div class="text-overlay text-overlay-space">
                                            <a href="#" class="text-white a-style1 text-sp ">
                                                <img src="@/images/pin.png" alt="">
                                                Belmont Gardens, Chicago</a>
                                            <span class="propicon-bg space2 padd">
                                                <img src="@/images/photo.png" alt="">
                                                <span class="ms-1 text-white">4</span>
                                            </span>
                                            <span class="propicon-bg ms-2 padd">
                                                <img src="@/images/film.png" alt="">
                                                <span class="ms-1 text-white">2</span>
                                            </span>

                                        </div>


                                    </div>
                                    <div class="card-body">
                                        <span class="home-ic ">$34,900<label>/Month</label></span>
                                        <h4 class="card-title mt-3 li-it">New Apartment Nice View</h4>
                                        <p class="card-text mt-3 props-icon ">Beautiful Huge 1 Family House In Heart Of
                                            <br>
                                            Westbury. Newly Renovated With New Wood
                                        </p>
                                        <div class="row ">
                                            <div class="col-lg-12 mt-3 d-flex">
                                                <div class="bd-rt pe-3">
                                                    <span class="mb-5 props-icon">3</span>
                                                    <img src="@/images/bed (1).png" class="mb-1" alt="">
                                                    <span class="d-block props-icon">Bedrooms</span>
                                                </div>
                                                <div class="bd-rt ps-3 pe-3">
                                                    <span class="mb-5 props-icon">2</span>
                                                    <img src="@/images/clean (1).png" class="mb-1" alt="">
                                                    <span class="d-block props-icon">Bathrooms</span>
                                                </div>
                                                <div class="ps-3">
                                                    <span class="mb-5 props-icon">3450</span>
                                                    <img src="@/images/selection (1).png" class="mb-1" alt="">
                                                    <span class="d-block props-icon">square Ft</span>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="row crd-hr">
                                            <div class="col-md-7 d-flex ">
                                                <img src="@/images/author.jpg" class="img-fluid crd-sm-im w-25" alt="">
                                                <div class="ms-3">
                                                    <span class="fsize">William Sekio</span>
                                                    <br>
                                                    <span class="fsize props-icon">Estate Agents</span>
                                                </div>


                                            </div>
                                            <div class="col-md-5 ic-marg  mt-3">

                                                <span class="ic-container me-1"><img src="@/images/expand.png"
                                                        alt=""></span>
                                                <span class="ic-container me-1"><img src="@/images/heart.png"
                                                        alt=""></span>
                                                <span class="ic-container"><img src="@/images/add.png" alt=""></span>

                                            </div>
                                        </div>

                                    </div>
                                </div>
                            </div>
                            <div class="col-lg-4 col-md-6 hidee">
                                <div class="card shadow" style="width:400px">
                                    <img class="card-img-top" src="@/images/im5.jpg" alt="Card image" style="width:100%">
                                    <div class="card-img-overlay">
                                        <h4 class="bg-sale crd-title">FOR SALE</h4>
                                        <div class="text-overlay text-overlay-space">
                                            <a href="#" class="text-white a-style1 ">
                                                <img src="@/images/pin.png" alt="">
                                                Belmont Gardens, Chicago</a>
                                            <span class="propicon-bg space2 padd">
                                                <img src="@/images/photo.png" alt="">
                                                <span class="ms-1 text-white">4</span>
                                            </span>
                                            <span class="propicon-bg ms-2 padd">
                                                <img src="@/images/film.png" alt="">
                                                <span class="ms-1 text-white">2</span>
                                            </span>

                                        </div>


                                    </div>
                                    <div class="card-body">
                                        <span class="home-ic ">$34,900<label>/Month</label></span>
                                        <h4 class="card-title mt-3 li-it">New Apartment Nice View</h4>
                                        <p class="card-text mt-3 props-icon ">Beautiful Huge 1 Family House In Heart Of
                                            <br>
                                            Westbury. Newly Renovated With New Wood
                                        </p>
                                        <div class="row ">
                                            <div class="col-lg-12 mt-3 d-flex">
                                                <div class="bd-rt pe-3">
                                                    <span class="mb-5 props-icon">3</span>
                                                    <img src="@/images/bed (1).png" class="mb-1" alt="">
                                                    <span class="d-block props-icon">Bedrooms</span>
                                                </div>
                                                <div class="bd-rt ps-3 pe-3">
                                                    <span class="mb-5 props-icon">2</span>
                                                    <img src="@/images/clean (1).png" class="mb-1" alt="">
                                                    <span class="d-block props-icon">Bathrooms</span>
                                                </div>
                                                <div class="ps-3">
                                                    <span class="mb-5 props-icon">3450</span>
                                                    <img src="@/images/selection (1).png" class="mb-1" alt="">
                                                    <span class="d-block props-icon">square Ft</span>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="row crd-hr">
                                            <div class="col-md-7 d-flex ">
                                                <img src="@/images/author.jpg" class="img-fluid crd-sm-im w-25" alt="">
                                                <div class="ms-3">
                                                    <span class="fs-6">William Sekio</span>
                                                    <br>
                                                    <span class="fs-6 props-icon">Estate Agents</span>
                                                </div>


                                            </div>
                                            <div class="col-md-5 mt-3">

                                                <span class="ic-container me-1"><img src="@/images/expand.png"
                                                        alt=""></span>
                                                <span class="ic-container me-1"><img src="@/images/heart.png"
                                                        alt=""></span>
                                                <span class="ic-container"><img src="@/images/add.png" alt=""></span>

                                            </div>
                                        </div>

                                    </div>
                                </div>
                            </div>
                            <div class="col-lg-4 col-md-6  hidee ">
                                <div class="card shadow" style="width:400px">
                                    <img class="card-img-top" src="@/images/im1.jpg" alt="Card image" style="width:100%">
                                    <div class="card-img-overlay">
                                        <h4 class="bg-rent crd-title">FOR RENT</h4>
                                        <div class="text-overlay text-overlay-space">
                                            <a href="#" class="text-white a-style1 ">
                                                <img src="@/images/pin.png" alt="">
                                                Belmont Gardens, Chicago</a>
                                            <span class="propicon-bg space2 padd">
                                                <img src="@/images/photo.png" alt="">
                                                <span class="ms-1 text-white">4</span>
                                            </span>
                                            <span class="propicon-bg ms-2 padd">
                                                <img src="@/images/film.png" alt="">
                                                <span class="ms-1 text-white">2</span>
                                            </span>

                                        </div>


                                    </div>
                                    <div class="card-body">
                                        <span class="home-ic ">$34,900<label>/Month</label></span>
                                        <h4 class="card-title mt-3 li-it">New Apartment Nice View</h4>
                                        <p class="card-text mt-3 props-icon ">Beautiful Huge 1 Family House In Heart Of
                                            <br>
                                            Westbury. Newly Renovated With New Wood
                                        </p>
                                        <div class="row ">
                                            <div class="col-lg-12 mt-3 d-flex">
                                                <div class="bd-rt pe-3">
                                                    <span class="mb-5 props-icon">3</span>
                                                    <img src="@/images/bed (1).png" class="mb-1" alt="">
                                                    <span class="d-block props-icon">Bedrooms</span>
                                                </div>
                                                <div class="bd-rt ps-3 pe-3">
                                                    <span class="mb-5 props-icon">2</span>
                                                    <img src="@/images/clean (1).png" class="mb-1" alt="">
                                                    <span class="d-block props-icon">Bathrooms</span>
                                                </div>
                                                <div class="ps-3">
                                                    <span class="mb-5 props-icon">3450</span>
                                                    <img src="@/images/selection (1).png" class="mb-1" alt="">
                                                    <span class="d-block props-icon">square Ft</span>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="row crd-hr">
                                            <div class="col-md-7 d-flex ">
                                                <img src="@/images/author.jpg" class="img-fluid crd-sm-im w-25" alt="">
                                                <div class="ms-3">
                                                    <span class="fs-6">William Sekio</span>
                                                    <br>
                                                    <span class="fs-6 props-icon">Estate Agents</span>
                                                </div>


                                            </div>
                                            <div class="col-md-5 mt-3">

                                                <span class="ic-container me-1"><img src="@/images/expand.png"
                                                        alt=""></span>
                                                <span class="ic-container me-1"><img src="@/images/heart.png"
                                                        alt=""></span>
                                                <span class="ic-container"><img src="@/images/add.png" alt=""></span>

                                            </div>
                                        </div>

                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

            </div>

            <!-- Indicators/dots -->
            <div class="carousel-indicators ind-style">
                <button type="button" data-bs-target="#demo" data-bs-slide-to="0" class="active dot "></button>
                <button type="button" data-bs-target="#demo" data-bs-slide-to="1" class="dot"></button>
                <button type="button" data-bs-target="#demo" data-bs-slide-to="2" class="dot"></button>
                <button type="button" data-bs-target="#demo" data-bs-slide-to="3 " class="dot"></button>
            </div>





        </div>
    </div>
    <!-- properties section ends -->


    <!-- apartment section begins -->

    <div class="apartment-sec">
        <center>
            <div class="ab-icon mb-3 ">
                Apartment Sketch
            </div>
            <h1 class="head ab-head mb-5 ab-head"> Apartments Plan</h1>
            <div class="mb-5 li-pd">
                <span class="h5 fb f-size home-ic" style="text-decoration: underline;"> The Studio</span>
                <span class="f-size  h5"> Deluxe Portion</span>
                <span class="f-size h5"> Penthouse</span>
                <span class="f-size h5">Top Garden</span>
                <span class="f-size h5">Double Height</span>
            </div>
        </center>


        <div class="props-sec">
            <div class="row ">
                <div class="col-lg-6 props-spec">
                    <h3 class="stud-txt1">The Studio</h3>
                    <p class="stud-txt2">Enimad minim veniam quis nostrud exercitation ullamco laboris.
                        Lorem ipsum dolor sit amet cons aetetur adipisicing elit
                        sedo eiusmod tempor.Incididunt labore et dolore magna aliqua. sed ayd minim veniam.</p>
                    <p class="stud-txt2">Total Area -------------------------- 2800 Sq. Ft</p>
                    <p class="stud-txt2">Bedroom -------------------------- 150 Sq. Ft</p>
                    <p class="stud-txt2">Bathroom -------------------------- 45 Sq. Ft</p>
                    <p class="stud-txt2"> Belcony/Pets -------------------------- Allowed</p>
                    <p class="stud-txt2">Lounge -------------------------- 650 Sq. Ft</p>
                </div>
                <div class="col-lg-6 apart-img">
                    <img src="@/images/apartmentplanimg.png" class="img-fluid fa-w-10 " alt="">
                </div>
            </div>
        </div>
    </div>
    <!-- apartment section ends -->

    <!-- background image section begins -->

    <div class="bg-fix ">

        <button class=" bg-vid-btn   "><a href="https://www.youtube.com/embed/HnbMYzdjuBs?autoplay=1&showinfo=0"><i
                    class="fa fa-play home-ic"></i></a>
        </button>


    </div>

    <!-- background image section ends -->


    <!-- amenities section begins -->
    <div class="apartment-sec props-sec amenities">
        <center>
            <div class="ab-icon mb-3 ">
                Our Amenities
            </div>
            <h1 class="head ab-head mb-5">Building Amenities </h1>
        </center>

        <div class="row mb-5">
            <div class=" col-lg-3 col-md-4 col-sm-6 col-6">
                <div class="card card-body crd crd-r1 shadow ">
                    <center>
                        <img src="@/images/electric-car.png" class="img-fluid  mt-4 card-im" alt="">
                        <h4 class="mt-3 ab-text1">Parking Space</h4>
                        <i class="fa fa-arrow-right shadow p-3 crd-ic-arrow"></i>
                    </center>
                </div>
            </div>
            <div class=" col-lg-3 col-md-4 col-sm-6 col-6">
                <div class="card card-body crd crd-r1 shadow ">
                    <center>
                        <img src="@/images/swimming-pool.png" class="img-fluid  mt-4 card-im" alt="">
                        <h4 class="mt-3 ab-text1">SwimmingPool </h4>
                        <i class="fa fa-arrow-right shadow p-3 crd-ic-arrow"></i>
                    </center>
                </div>
            </div>
            <div class=" col-lg-3 col-md-4 col-sm-6 col-6">
                <div class="card card-body crd shadow ">
                    <center>
                        <img src="@/images/security.png" class="img-fluid  mt-4 card-im" alt="">
                        <h4 class="mt-3 ab-text1">Private Security </h4>
                        <i class="fa fa-arrow-right shadow p-3 crd-ic-arrow"></i>
                    </center>
                </div>
            </div>
            <div class=" col-lg-3 col-md-4 col-sm-6 col-6 hide-md">
                <div class="card card-body crd shadow ">
                    <center>
                        <img src="@/images/stethoscope.png" class="img-fluid  mt-4 card-im" alt="">
                        <h4 class="mt-3 ab-text1">Medical Center</h4>
                        <i class="fa fa-arrow-right shadow p-3 crd-ic-arrow"></i>
                    </center>
                </div>
            </div>
        </div>

        <div class="row">
            <div class=" col-lg-3 col-md-4 col-sm-6 col-6 ">
                <div class="card card-body crd crd-r1 shadow ">
                    <center>
                        <img src="@/images/book.png" class="img-fluid  mt-4 card-im" alt="">
                        <h4 class="mt-3 ab-text1">Library Area </h4>
                        <i class="fa fa-arrow-right shadow p-3 crd-ic-arrow"></i>
                    </center>
                </div>
            </div>
            <div class=" col-lg-3 col-md-4 col-sm-6 col-6">
                <div class="card card-body crd crd-r1 shadow ">
                    <center>
                        <img src="@/images/beed.png" class="img-fluid  mt-4 card-im" alt="">
                        <h4 class="mt-3 ab-text1">King Size Beds </h4>
                        <i class="fa fa-arrow-right shadow p-3 crd-ic-arrow"></i>
                    </center>
                </div>
            </div>
            <div class=" col-lg-3 col-md-4 col-sm-6 col-6">
                <div class="card card-body crd shadow ">
                    <center>
                        <img src="@/images/home.png" class="img-fluid  mt-4 card-im" alt="">
                        <h4 class="mt-3 ab-text1">Smart Homes </h4>
                        <i class="fa fa-arrow-right shadow p-3 crd-ic-arrow"></i>
                    </center>
                </div>
            </div>
            <div class=" col-lg-3 col-md-4 col-sm-6 col-6 hide-md">
                <div class="card card-body crd shadow ">
                    <center>
                        <img src="@/images/playgroundd.png" class="img-fluid  mt-4 card-im" alt="">
                        <h4 class="mt-3 ab-text1">Kid's Playland</h4>
                        <i class="fa fa-arrow-right shadow p-3 crd-ic-arrow"></i>
                    </center>
                </div>
            </div>
        </div>

    </div>
    <!-- amenities section ends -->


    <!-- testimonial section begins -->
    <div class="qbg-img">
        <center>
            <div class="ab-icon mb-3 ">
                Our Testimonial
            </div>
            <h1 class="head ab-head"> Clients Feedback </h1>
        </center>

        <div id="demo" class="carousel  " data-bs-ride="carousel">

            <!-- Indicators/dots -->
            <div class="carousel-indicators">
                <button type="button" data-bs-target="#demo" data-bs-slide-to="0" class="active"></button>
                <button type="button" data-bs-target="#demo" data-bs-slide-to="1"></button>


            </div>


            <!-- The slideshow/carousel -->
            <div class="carousel-inner props-sec">
                <div class="carousel-item active">
                    <div class="d-block" style="width:100%">
                        <div class="row">
                            <div class="col-lg-4 col-md-6  col-md-6">
                                <div class="card shadow cardbody p-4">
                                    <p>
                                        <img src="@/images/left-quote.png" alt="">
                                        <i class="flaticon-left-quote-1"></i>
                                        Precious ipsum dolor sit amet
                                        consectetur adipisicing elit, sed dos
                                        mod tempor incididunt ut labore et
                                        dolore magna aliqua. Ut enim ad min
                                        veniam, quis nostrud Precious ips
                                        um dolor sit amet, consecte
                                    </p>
                                    <div class=" d-flex ">
                                        <img src="@/images/testimg1.jpg" class="img-fluid crd-sm-im w-25 p-3" alt="">
                                        <div class="ms-1 mt-4">
                                            <span class="fs-6"><b>Jacob William </b></span>
                                            <br>
                                            <span class="fs-6 props-icon">SELLING AGENTS </span>
                                        </div>


                                    </div>
                                </div>
                            </div>
                            <div class="col-lg-4 col-md-6  hidee">
                                <div class="card shadow cardbody p-4">
                                    <p>
                                        <img src="@/images/left-quote.png" alt="">
                                        <i class="flaticon-left-quote-1"></i>
                                        Precious ipsum dolor sit amet
                                        consectetur adipisicing elit, sed dos
                                        mod tempor incididunt ut labore et
                                        dolore magna aliqua. Ut enim ad min
                                        veniam, quis nostrud Precious ips
                                        um dolor sit amet, consecte
                                    </p>
                                    <div class=" d-flex ">
                                        <img src="@/images/keliantest.jpg" class="img-fluid crd-sm-im w-25 p-3" alt="">
                                        <div class="ms-1 mt-4">
                                            <span class="fs-6"><b>Kelian Anderson </b></span>
                                            <br>
                                            <span class="fs-6 props-icon">SELLING AGENTS </span>
                                        </div>


                                    </div>
                                </div>
                            </div>
                            <div class="col-lg-4 col-md-6  hidee hide-md">
                                <div class="card shadow cardbody p-4">
                                    <p>
                                        <img src="@/images/left-quote.png" alt="">
                                        <i class="flaticon-left-quote-1"></i>
                                        Precious ipsum dolor sit amet
                                        consectetur adipisicing elit, sed dos
                                        mod tempor incididunt ut labore et
                                        dolore magna aliqua. Ut enim ad min
                                        veniam, quis nostrud Precious ips
                                        um dolor sit amet, consecte
                                    </p>
                                    <div class=" d-flex ">
                                        <img src="@/images/adamtest.jpg" class="img-fluid crd-sm-im w-25 p-3" alt="">
                                        <div class="ms-1 mt-4">
                                            <span class="fs-6"><b>Adam Joseph </b></span>
                                            <br>
                                            <span class="fs-6 props-icon">SELLING AGENTS </span>
                                        </div>


                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="carousel-item">
                    <div class="d-block" style="width:100%">
                        <div class="row">
                            <div class="col-lg-4 col-md-6 hidee ">
                                <div class="card shadow cardbody p-4">
                                    <p>
                                        <img src="@/images/left-quote.png" alt="">
                                        <i class="flaticon-left-quote-1"></i>
                                        Precious ipsum dolor sit amet
                                        consectetur adipisicing elit, sed dos
                                        mod tempor incididunt ut labore et
                                        dolore magna aliqua. Ut enim ad min
                                        veniam, quis nostrud Precious ips
                                        um dolor sit amet, consecte
                                    </p>
                                    <div class=" d-flex ">
                                        <img src="@/images/cartertest.jpg" class="img-fluid crd-sm-im w-25 p-3" alt="">
                                        <div class="ms-1 mt-4">
                                            <span class="fs-6"><b>James Carter</b></span>
                                            <br>
                                            <span class="fs-6 props-icon">SELLING AGENTS </span>
                                        </div>


                                    </div>
                                </div>
                            </div>
                            <div class="col-lg-4 col-md-6 hide-md ">
                                <div class="card shadow cardbody p-4">
                                    <p>
                                        <img src="@/images/left-quote.png" alt="">
                                        <i class="flaticon-left-quote-1"></i>
                                        Precious ipsum dolor sit amet
                                        consectetur adipisicing elit, sed dos
                                        mod tempor incididunt ut labore et
                                        dolore magna aliqua. Ut enim ad min
                                        veniam, quis nostrud Precious ips
                                        um dolor sit amet, consecte
                                    </p>
                                    <div class=" d-flex ">
                                        <img src="@/images/testimg1.jpg" class="img-fluid crd-sm-im w-25 p-3" alt="">
                                        <div class="ms-1 mt-4">
                                            <span class="fs-6"><b>Jacob William </b></span>
                                            <br>
                                            <span class="fs-6 props-icon">SELLING AGENTS </span>
                                        </div>


                                    </div>
                                </div>
                            </div>
                            <div class="col-lg-4 col-md-6 hidee ">
                                <div class="card shadow cardbody p-4">
                                    <p>
                                        <img src="@/images/left-quote.png" alt="">
                                        <i class="flaticon-left-quote-1"></i>
                                        Precious ipsum dolor sit amet
                                        consectetur adipisicing elit, sed dos
                                        mod tempor incididunt ut labore et
                                        dolore magna aliqua. Ut enim ad min
                                        veniam, quis nostrud Precious ips
                                        um dolor sit amet, consecte
                                    </p>
                                    <div class=" d-flex ">
                                        <img src="@/images/author.jpg" class="img-fluid crd-sm-im w-25 p-3" alt="">
                                        <div class="ms-1 mt-4">
                                            <span class="fs-6"><b>William Sekio</b></span>
                                            <br>
                                            <span class="fs-6 props-icon">SELLING AGENTS</span>
                                        </div>


                                    </div>
                                </div>
                            </div>


                        </div>
                    </div>
                </div>

                <div class="carousel-item">
                    <div class="d-block" style="width:100%">
                        <div class="row">
                            <div class="col-lg-4 col-md-6  hidee">
                                <div class="card shadow cardbody p-4">
                                    <p>
                                        <img src="@/images/left-quote.png" alt="">
                                        <i class="flaticon-left-quote-1"></i>
                                        Precious ipsum dolor sit amet
                                        consectetur adipisicing elit, sed dos
                                        mod tempor incididunt ut labore et
                                        dolore magna aliqua. Ut enim ad min
                                        veniam, quis nostrud Precious ips
                                        um dolor sit amet, consecte
                                    </p>
                                    <div class=" d-flex ">
                                        <img src="@/images/cartertest.jpg" class="img-fluid crd-sm-im w-25 p-3" alt="">
                                        <div class="ms-1 mt-4">
                                            <span class="fs-6"><b>James Carter</b></span>
                                            <br>
                                            <span class="fs-6 props-icon">SELLING AGENTS </span>
                                        </div>


                                    </div>
                                </div>
                            </div>
                            <div class="col-lg-4 col-md-6  hidee">
                                <div class="card shadow cardbody p-4">
                                    <p>
                                        <img src="@/images/left-quote.png" alt="">
                                        <i class="flaticon-left-quote-1"></i>
                                        Precious ipsum dolor sit amet
                                        consectetur adipisicing elit, sed dos
                                        mod tempor incididunt ut labore et
                                        dolore magna aliqua. Ut enim ad min
                                        veniam, quis nostrud Precious ips
                                        um dolor sit amet, consecte
                                    </p>
                                    <div class=" d-flex ">
                                        <img src="@/images/testimg1.jpg" class="img-fluid crd-sm-im w-25 p-3" alt="">
                                        <div class="ms-1 mt-4">
                                            <span class="fs-6"><b>Jacob William </b></span>
                                            <br>
                                            <span class="fs-6 props-icon">SELLING AGENTS </span>
                                        </div>


                                    </div>
                                </div>
                            </div>
                            <div class="col-lg-4 col-md-6  hide-md ">
                                <div class="card shadow cardbody p-4">
                                    <p>
                                        <img src="@/images/left-quote.png" alt="">
                                        <i class="flaticon-left-quote-1"></i>
                                        Precious ipsum dolor sit amet
                                        consectetur adipisicing elit, sed dos
                                        mod tempor incididunt ut labore et
                                        dolore magna aliqua. Ut enim ad min
                                        veniam, quis nostrud Precious ips
                                        um dolor sit amet, consecte
                                    </p>
                                    <div class=" d-flex ">
                                        <img src="@/images/author.jpg" class="img-fluid crd-sm-im w-25 p-3" alt="">
                                        <div class="ms-1 mt-4">
                                            <span class="fs-6"><b>William Sekio</b></span>
                                            <br>
                                            <span class="fs-6 props-icon">SELLING AGENTS</span>
                                        </div>


                                    </div>
                                </div>
                            </div>


                        </div>
                    </div>
                </div>


                <div class="carousel-item">
                    <div class="d-block" style="width:100%">
                        <div class="row">
                            <div class="col-lg-4 col-md-6 ">
                                <div class="card shadow cardbody p-4">
                                    <p>
                                        <img src="@/images/left-quote.png" alt="">
                                        <i class="flaticon-left-quote-1"></i>
                                        Precious ipsum dolor sit amet
                                        consectetur adipisicing elit, sed dos
                                        mod tempor incididunt ut labore et
                                        dolore magna aliqua. Ut enim ad min
                                        veniam, quis nostrud Precious ips
                                        um dolor sit amet, consecte
                                    </p>
                                    <div class=" d-flex ">
                                        <img src="@/images/cartertest.jpg" class="img-fluid crd-sm-im w-25 p-3" alt="">
                                        <div class="ms-1 mt-4">
                                            <span class="fs-6"><b>James Carter</b></span>
                                            <br>
                                            <span class="fs-6 props-icon">SELLING AGENTS </span>
                                        </div>


                                    </div>
                                </div>
                            </div>
                            <div class="col-lg-4 col-md-6 hide-md hidee">
                                <div class="card shadow cardbody p-4">
                                    <p>
                                        <img src="@/images/left-quote.png" alt="">
                                        <i class="flaticon-left-quote-1"></i>
                                        Precious ipsum dolor sit amet
                                        consectetur adipisicing elit, sed dos
                                        mod tempor incididunt ut labore et
                                        dolore magna aliqua. Ut enim ad min
                                        veniam, quis nostrud Precious ips
                                        um dolor sit amet, consecte
                                    </p>
                                    <div class=" d-flex ">
                                        <img src="@/images/testimg1.jpg" class="img-fluid crd-sm-im w-25 p-3" alt="">
                                        <div class="ms-1 mt-4">
                                            <span class="fs-6"><b>Jacob William </b></span>
                                            <br>
                                            <span class="fs-6 props-icon">SELLING AGENTS </span>
                                        </div>


                                    </div>
                                </div>
                            </div>
                            <div class="col-lg-4 col-md-6 hidee">
                                <div class="card shadow cardbody p-4">
                                    <p>
                                        <img src="@/images/left-quote.png" alt="">
                                        <i class="flaticon-left-quote-1"></i>
                                        Precious ipsum dolor sit amet
                                        consectetur adipisicing elit, sed dos
                                        mod tempor incididunt ut labore et
                                        dolore magna aliqua. Ut enim ad min
                                        veniam, quis nostrud Precious ips
                                        um dolor sit amet, consecte
                                    </p>
                                    <div class=" d-flex ">
                                        <img src="@/images/author.jpg" class="img-fluid crd-sm-im w-25 p-3" alt="">
                                        <div class="ms-1 mt-4">
                                            <span class="fs-6"><b>William Sekio</b></span>
                                            <br>
                                            <span class="fs-6 props-icon">SELLING AGENTS</span>
                                        </div>


                                    </div>
                                </div>
                            </div>


                        </div>
                    </div>
                </div>


            </div>







        </div>





    </div>

    <!-- testimonial section ends -->


    <!-- News section begins  -->

    <div class="props-sec news">
        <center>
            <div class="ab-icon mb-4 ">
                News & Blogs
            </div>
            <h1 class="head ab-head mb-5">Latest News Feeds </h1>
        </center>

        <div id="demo" class="carousel  " data-bs-ride="carousel">

            <!-- Indicators/dots -->
            <div class="carousel-indicators">
                <button type="button" data-bs-target="#demo" data-bs-slide-to="0" class="active"></button>
                <button type="button" data-bs-target="#demo" data-bs-slide-to="1"></button>
                <button type="button" data-bs-target="#demo" data-bs-slide-to="2"></button>

            </div>


            <!-- The slideshow/carousel -->
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <div class="d-block" style="width:100%">
                        <div class="row">
                            <div class="col-lg-4 col-md-6 ">
                                <div class="card shadow" style="width:400px">

                                    <img class="card-img-top img-zoom" src="@/images/im1.jpg" alt="Card image"
                                        style="width:100%">
                                    <div class="card-body">
                                        <span class="home-ic ">$34,900<label>/Month</label></span>
                                        <h4 class="card-title mt-3 fo-size li-it">10 Brilliant Ways To Decorate Your
                                            Home Apartment
                                            Nice View</h4>


                                        <div class="row  crd-hr">
                                            <div class="col-md-7 col-sm-6 col-6  d-flex ">
                                                <img src="@/images/calendar.png" class="cal-ic" alt="">
                                                <div class="ms-3 date col-sm-6  fosize">
                                                    July 23, 2021
                                                </div>


                                            </div>
                                            <div class="col-md-5 col-sm-6 col-6  fosize home-ic">
                                                <p class="date-txt">READ MORE</p>
                                            </div>
                                        </div>

                                    </div>
                                </div>
                            </div>
                            <div class="col-lg-4 col-md-6  hidee">
                                <div class="card shadow" style="width:400px">
                                    <img class="card-img-top img-zoom" src="@/images/im2.jpg" alt="Card image"
                                        style="width:100%">
                                    <div class="card-body">
                                        <span class="home-ic ">$34,900<label>/Month</label></span>
                                        <h4 class="card-title mt-3 li-it">The Most Insprining Interior Design of 2021
                                        </h4>

                                        <div class="row crd-hr">
                                            <div class="col-md-7 d-flex ">
                                                <img src="@/images/calendar.png" class="cal-ic" alt="">
                                                <div class="ms-3">
                                                    July 23, 2021
                                                </div>


                                            </div>
                                            <div class="col-md-5 home-ic">
                                                <p>READ MORE</p>
                                            </div>
                                        </div>

                                    </div>
                                </div>
                            </div>
                            <div class="col-lg-4 col-md-6 hide-md hidee">
                                <div class="card shadow" style="width:400px">
                                    <img class="card-img-top img-zoom" src="@/images/im3.jpg" alt="Card image"
                                        style="width:100%">
                                    <div class="card-body">
                                        <span class="home-ic ">$34,900<label>/Month</label></span>
                                        <h4 class="card-title mt-3 li-it">Recent Commercial Real Estate Transactions
                                        </h4>

                                        <div class="row crd-hr">
                                            <div class="col-md-7 d-flex ">
                                                <img src="@/images/calendar.png" class="cal-ic" alt="">
                                                <div class="ms-3">
                                                    July 23, 2021
                                                </div>


                                            </div>
                                            <div class="col-md-5 home-ic">
                                                <p>READ MORE</p>
                                            </div>
                                        </div>

                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="carousel-item">
                    <div class="d-block" style="width:100%">
                        <div class="row">
                            <div class="col-lg-4 col-md-6 ">
                                <div class="card shadow" style="width:400px">
                                    <img class="card-img-top img-zoom" src="@/images/im2.jpg" alt="Card image"
                                        style="width:100%">
                                    <div class="card-body">
                                        <span class="home-ic ">$34,900<label>/Month</label></span>
                                        <h4 class="card-title mt-3 fo-size li-it">Renovating A Living Room? Experts
                                            Share Their
                                            Secrets </h4>

                                        <div class="row crd-hr">
                                            <div class="col-md-7 col-sm-6 col-6  d-flex ">
                                                <img src="@/images/calendar.png" class="cal-ic" alt="">
                                                <div class="ms-3 date fosize">
                                                    July 23, 2021
                                                </div>


                                            </div>
                                            <div class="col-md-5 col-sm-6 col-6  fosize home-ic">
                                                <p class="date-txt">READ MORE</p>
                                            </div>
                                        </div>

                                    </div>
                                </div>
                            </div>
                            <div class="col-lg-4 col-md-6 hide-md hidee">
                                <div class="card shadow" style="width:400px">
                                    <img class="card-img-top img-zoom" src="@/images/im3.jpg" alt="Card image"
                                        style="width:100%">
                                    <div class="card-body">
                                        <span class="home-ic ">$34,900<label>/Month</label></span>
                                        <h4 class="card-title mt-3 li-it">7 Home Trends That will Shape Your House in
                                            2021
                                        </h4>

                                        <div class="row crd-hr">
                                            <div class="col-md-7 d-flex ">
                                                <img src="@/images/calendar.png" class="cal-ic" alt="">
                                                <div class="ms-3">
                                                    July 23, 2021
                                                </div>


                                            </div>
                                            <div class="col-md-5 home-ic">
                                                <p>READ MORE</p>
                                            </div>
                                        </div>

                                    </div>
                                </div>
                            </div>
                            <div class="col-lg-4 col-md-6  hidee">
                                <div class="card shadow" style="width:400px">
                                    <img class="card-img-top img-zoom" src="@/images/img4.jpg" alt="Card image"
                                        style="width:100%">
                                    <div class="card-body">
                                        <span class="home-ic ">$34,900<label>/Month</label></span>
                                        <h4 class="card-title mt-3 li-it">10 Brilliant Ways To Decorate Your Home</h4>

                                        <div class="row crd-hr">
                                            <div class="col-md-7 d-flex ">
                                                <img src="@/images/calendar.png" class="cal-ic" alt="">
                                                <div class="ms-3">
                                                    July 23, 2021
                                                </div>


                                            </div>
                                            <div class="col-md-5 home-ic">
                                                <p>READ MORE</p>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="carousel-item">
                    <div class="d-block" style="width:100%">
                        <div class="row">
                            <div class="col-lg-4 col-md-6 ">
                                <div class="card shadow" style="width:400px">
                                    <img class="card-img-top img-zoom" src="@/images/im3.jpg" alt="Card image"
                                        style="width:100%">
                                    <div class="card-body">
                                        <span class="home-ic ">$34,900<label>/Month</label></span>
                                        <h4 class="card-title mt-3 fo-size li-it">Renovating A Living Room? Experts
                                            Share Their
                                            Secretsw</h4>

                                        <div class="row crd-hr">
                                            <div class="col-md-7 col-sm-6 col-6 d-flex ">
                                                <img src="@/images/calendar.png" class="cal-ic" alt="">
                                                <div class="ms-3 date fosize">
                                                    July 23, 2021
                                                </div>


                                            </div>
                                            <div class="col-md-5 col-sm-6 col-6 fosize home-ic">
                                                <p class="date-txt">READ MORE</p>
                                            </div>
                                        </div>

                                    </div>
                                </div>
                            </div>
                            <div class="col-lg-4 col-md-6 hidee">
                                <div class="card shadow" style="width:400px">
                                    <img class="card-img-top img-zoom" src="@/images/img4.jpg" alt="Card image"
                                        style="width:100%">
                                    <div class="card-body">
                                        <span class="home-ic ">$34,900<label>/Month</label></span>
                                        <h4 class="card-title mt-3 fo-size li-it">Renovating A Living Room? Experts
                                            Share Their
                                            Secretsw</h4>

                                        <div class="row crd-hr">
                                            <div class="col-md-7 col-sm-6 col-6 d-flex ">
                                                <img src="@/images/calendar.png" class="cal-ic" alt="">
                                                <div class="ms-3 date fosize">
                                                    July 23, 2021
                                                </div>


                                            </div>
                                            <div class="col-md-5 col-sm-6 col-6 fosize home-ic">
                                                <p class="date-txt">READ MORE</p>
                                            </div>
                                        </div>

                                    </div>
                                </div>
                            </div>
                            <div class="col-lg-4 col-md-6 hide-md hidee ">
                                <div class="card shadow" style="width:400px">
                                    <img class="card-img-top img-zoom" src="@/images/im5.jpg" alt="Card image"
                                        style="width:100%">
                                    <div class="card-body">
                                        <span class="home-ic ">$34,900<label>/Month</label></span>
                                        <h4 class="card-title mt-3 fo-size li-it">Renovating A Living Room? Experts
                                            Share Their
                                            Secretsw</h4>

                                        <div class="row crd-hr">
                                            <div class="col-md-7 col-sm-6 col-6 d-flex ">
                                                <img src="@/images/calendar.png" class="cal-ic" alt="">
                                                <div class="ms-3 date fosize">
                                                    July 23, 2021
                                                </div>


                                            </div>
                                            <div class="col-md-5 col-sm-6 col-6 fosize home-ic">
                                                <p class="date-txt">READ MORE</p>
                                            </div>
                                        </div>

                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

            </div>







        </div>
    </div>

    <!-- News section ends  -->





  </div>
</template>

<script>
  export default {
    
  }
</script>

<style lang="scss" scoped>

</style>
