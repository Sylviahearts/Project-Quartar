<template>
    <div>
        <!-- navbar begins -->
        <div class=" sticky-top shadow">
            <nav class="navbar navbar-expand-lg navbar-light  p-4  bg-white ">
                <div class="container-fluid ">
                    <router-link class="navbar-brand" to="/"><img src="./images/quartarlogo.png" alt="logo here"></router-link>
                    <button class="navbar-toggler collapsed" type="button" data-bs-toggle="collapse"
                        data-bs-target="#mynavbar" aria-expanded="false">
                        <span class="navbar-toggler-icon"></span>
                    </button>
                    <div class="navbar-collapse collapse" id="mynavbar">
                        <ul class="navbar-nav mx-auto">
                            <li class="dropdown nav-item">
                                <a href="#" class="dropbtn">Home+</a>
                                <div class="dropdown-content drop-cont">
                                    <a href="#">Home Style 01</a>
                                    <a href="#">Home Style 02</a>
                                    <a href="#">Home Style 03</a>
                                    <a href="#">Home Style 04</a>
                                    <a href="#">Home Style 05</a>
                                    <a href="#">Home Style 06</a>
                                    <a href="#">Home Style 07</a>
                                    <a href="#">Home Style 08</a>
                                    <a href="#">Home Style 09</a>
                                    <a href="#">Home Style 10</a>
                                    <a href="#">Home Style 11</a>
                                </div>
                            </li>
                            <li class="dropdown nav-item">
                                <a href="#" class="dropbtn">About+</a>
                                <div class="dropdown-content drop-cont">
                                    <a href="#">About</a>
                                    <a href="#">Servives </a>
                                    <a href="#">Services Details</a>
                                    <a href="#">Portfolio</a>
                                    <a href="#">Portfolio 02</a>
                                    <a href="#">Portfolio Details</a>
                                    <a href="#">Team</a>
                                    <a href="#">Team Details</a>
                                    <a href="#">FAQ 01</a>
                                    <a href="#">Googke Map Locations</a>
                                </div>
                            </li>
                            <li class="dropdown nav-item">
                                <a href="#" class="dropbtn">Shop+</a>
                                <div class="dropdown-content drop-cont">
                                    <a href="#">Shop</a>
                                    <a href="#">Shop Grid</a>
                                    <a href="#">Shop Left sidebar</a>
                                    <a href="#"> Shop right sidebar</a>
                                    <a href="#">Shop details</a>
                                    <a href="#"> Other Pages >></a>
                                </div>
                            </li>
                            <li class="dropdown">
                                <a href="#" class="dropbtn">News+</a>
                                <div class="dropdown-content drop-cont">
                                    <a href="#">News</a>
                                    <a href="#">News Grid</a>
                                    <a href="#">News Left sidebar</a>
                                    <a href="#"> News right sidebar</a>
                                    <a href="#">News details</a>
                                </div>
                            </li>
                            <li class="dropdown">
                                <a href="#" class="dropbtn">Pages+</a>
                                <div class="dropdown-content drop-cont">
                                    <router-link to="/contact">404</router-link>
                                </div>
                            </li>
                            <li class="dropdown">
                                <a href="#" class="dropbtn">Contact</a>
                            </li>
                        </ul>
                        <ul class="navbar-nav">
                            <li class="nav-item nav-icon shadow me-2"><i class="fa fa-search"></i></li>
                            <li class="nav-item nav-icon shadow me-2"><i class="fa fa-user"></i></li>
                            <li class="nav-item nav-icon shadow"><i class="fa fa-user"></i></li>
                        </ul>
                    </div>
                </div>
            </nav>
        </div>
        <!-- navbar ends -->

        <router-view />

        <!-- second relative top begins -->
        <div class="rel-top-div">
            <div class="row">
                <div class="col-lg-6 col-md-12 rel-txt ">
                    <h2 class="r-txt fsize">Looking for a dream home?</h2>
                    <p class="mt-2 ab-text fsize-sub">We can help you realize your dream of a new home</p>
                </div>
                <div class="col-lg-6 col-md-12">

                    <button class="rel-btn">Explore Properties <img src="./images/right-arrow.png" alt=""></button>
                </div>
            </div>
        </div>
        <!-- second relative top ends -->


        <!-- footer section begins -->
        <div class="footer">
            <div class="row">
                <div class="col-lg-3 col-md-6 col-sm-6 col-12">
                    <ul class="list-it">
                        <li class="footer-space mt-3 f-head"><img src="./images/footer-logo.png" class="img-fluid" alt="">
                        </li>
                        <li class="footer-space ">Lorem Ipsum is simply dummy text of the and typesetting industry. Lorem
                            Ipsum is dummy text of the printing.</li>
                        <li class="footer-space li-it">
                            <img src="images/pin.png" class="me-2" alt="">Brooklyn, New York, United States
                        </li>
                        <li class="footer-space li-it"> <img src="./images/phone-call.png" class="me-2" alt="">+0123-456789
                        </li>
                        <li class="footer-space li-it"> <img src="./images/phone-call.png" class="me-2 "
                                alt="">example@example.com</li>
                        <li>
                            <i class="fab fa-facebook-f text-white mt-4 me-3"></i>
                            <i class="fab fa-twitter text-white me-3"></i>
                            <i class="fab fa-linkedin text-white me-3"></i>
                            <i class="fab fa-youtube text-white"></i>
                        </li>

                    </ul>
                </div>
                <div class="col-lg-2 col-md-6 col-sm-6 col-12">
                    <ul class="list-it">
                        <li class="footer-space mt-3 f-head">Company</li>
                        <li class="footer-space li-it">About</li>
                        <li class="footer-space li-it">Blog</li>
                        <li class="footer-space li-it">All Products</li>
                        <li class="footer-space li-it">Locations Map</li>
                        <li class="footer-space li-it">FAQ</li>
                        <li class="li-it">Contact us</li>

                    </ul>

                </div>
                <div class="col-lg-2 col-md-6 col-sm-6 col-12">
                    <ul class="list-it">
                        <li class="footer-space mt-3 f-head">Services</li>
                        <li class="footer-space li-it">Order tracking</li>
                        <li class="footer-space li-it">Wish List</li>
                        <li class="footer-space li-it">Login</li>
                        <li class="footer-space li-it"> My account</li>
                        <li class="footer-space li-it">Terms & Conditions</li>
                        <li class="li-it">Promotional Offers</li>

                    </ul>

                </div>
                <div class="col-lg-2 col-md-6 col-sm-6 col-12">
                    <ul class="list-it">
                        <li class="footer-space mt-3 f-head">Customer Care</li>
                        <li class="footer-space li-it">Login</li>
                        <li class="footer-space li-it">My account</li>
                        <li class="footer-space li-it">Wish List</li>
                        <li class="footer-space li-it">Order tracking</li>
                        <li class="footer-space li-it">FAQ</li>
                        <li class="li-it">Contact us</li>

                    </ul>

                </div>
                <div class="col-lg-3 col-md-6 col-sm-6 col-12">
                    <ul class="list-it">
                        <li class="footer-space mt-3 f-head">Newsletter</li>
                        <li class="footer-space ">Subscribe to our weekly Newsletter and receive updates via email.</li>
                        <li class="footer-space">
                            <div class="input-group ">
                                <input type="email" class="form-control" placeholder="Email*"
                                    aria-label="Recipient's username" aria-describedby="basic-addon2">
                                <div class="input-group-append">
                                    <span class="input-group-text p-3 text-white inp-btn" id="basic-addon2"><i
                                            class="fas fa-location-arrow "></i></span>
                                </div>
                            </div>
                        </li>
                        <li class="footer-space">We Accept</li>
                        <li class="footer-space"><img src="./images/visa.png" class="img-fluid" alt=""></li>

                    </ul>

                </div>
            </div>
        </div>
        <!-- footer section ends -->

        <!-- semi-footer begins -->
        <div class="sec-footer">
            <div class="row">

                <div class="col-md-6">
                    <p class="smt">All Rights Reserved @ Company 2023</p>

                </div>
                <div class="col-md-6">
                    <span class="semi-foot smt semi-txt">Terms & Conditions</span>
                    <span class="semi-txt smt">Claim</span>
                    <span class="semi-txt sm-txt smt">Privacy & Policy</span>

                </div>
            </div>
        </div>
        <!-- semi-footer ends -->


    </div>
</template>


<style lang="scss" scoped></style>