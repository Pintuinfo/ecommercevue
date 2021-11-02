<template>
  <div id="app">
    <div class="header">
    <div class="top-header">
        <div class="container">
            <div class="row">
                <div class="col-xl-5 col-lg-5 col-sm-3">
                    <div class="top-left">
                        <a href="callto:0045 29890472" class="mr-3"><i class="icofont-ui-call"></i> 0045
                                29890472</a>
                        <a href="mailto:simon@3dplus.dk"><i class="fas fa-envelope"></i> simon@3dplus.dk</a>
                    </div>
                </div>
                <div class="col-xl-7 col-lg-7 col-sm-9">
                    <div class="top-right">
                        <a href="javascript:void(0);"><i class="icofont-fast-delivery"></i> World wide delivery -
                                Daily shipping</a>
                        <div class="select-lang mr-3">
                            <div id="demo" data-input-name="country" data-selected-country="US" data-scrollable-height="250px">
                            </div>
                        </div>

                        <a href="#" class="login-btn"><i class="fas fa-user"></i> login</a>

                        <a href="#" class="login-btn quotation">Get a Quote</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="bottom-header">
        <div class="container">
            <div class="row">
                <div class="col-xl-2 col-lg-2 d-xl-flex d-lg-flex d-block align-items-center">
                    <div class="row no-gutters">
                        <div class="col-xl-12 col-lg-12 col-4 d-xl-block d-lg-block d-flex align-items-center">
                            <div class="logo">
                                <a href="index.html"><img src="assets/images/logo.png" alt="LOGO"></a>
                            </div>
                        </div>
                        <div class="d-xl-none d-lg-none d-flex align-items-center col-md-7 col-6">
                            <div class="others-btn">
                                <button id="sm-search-box"><i class="icofont-search"></i></button>
                                <button id="sm-w-list"><i class="far fa-heart"></i><span>3</span></button>
                                <button id="sm-c-list"><i class="icofont-cart-alt"></i><span>3</span></button>
                            </div>
                        </div>
                        <div class="d-xl-none d-lg-none d-block col-md-1 col-2">
                            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                                    <i class="fas fa-bars"></i>
                                </button>
                        </div>
                    </div>
                </div>
                <div class="col-xl-10 col-lg-10">
                    <nav class="navbar navbar-expand-lg navbar-light">
                        <div class="collapse navbar-collapse" id="navbarSupportedContent">
                            <ul class="navbar-nav ml-auto">

                                <li class="nav-item">
                                   <router-link to="/" class="nav-link">Home</router-link>
                                    <!-- <a class="nav-link" href="index.html">Home</a> -->
                                </li>

                                <li class="nav-item">
                                  <router-link to="/about" class="nav-link">About</router-link>
                                    <!-- <a class="nav-link" href="about-us.html">About Us</a> -->
                                </li>

                                <li class="nav-item">
                                    <a class="nav-link" href="product-list.html">Product</a>
                                </li>


                                <li class="nav-item">
                                    <a class="nav-link" href="blog.html">Reviews</a>
                                </li>

                                <li class="nav-item">
                                  <router-link to="/contact" class="nav-link">Contact</router-link>
                                    <!-- <a class="nav-link" href="contact-us.html">Contact Us</a> -->
                                </li>
                            </ul>
                            <div class="others-btn d-xl-block d-lg-block d-none">
                                <button id="search-box"><i class="icofont-search"></i></button>
                                <button id="w-list"><i class="far fa-heart"></i><span>2</span></button>
                                <button id="c-list"><i class="icofont-cart-alt"></i><span>2</span></button>
                            </div>
                        </div>
                    </nav>
                </div>
            </div>
        </div>
    </div>
</div>


<!-- -----------SEARCH MODEL CODE START-------------- -->
<div class="search-box">
    <button class="close"><svg aria-hidden="true" focusable="false" data-prefix="fal" data-icon="times-circle"
                role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"
                class="svg-inline--fa fa-times-circle fa-w-16 fa-fw fa-2x">
                <path fill="currentColor"
                    d="M256 8C119 8 8 119 8 256s111 248 248 248 248-111 248-248S393 8 256 8zm0 464c-118.7 0-216-96.1-216-216 0-118.7 96.1-216 216-216 118.7 0 216 96.1 216 216 0 118.7-96.1 216-216 216zm94.8-285.3L281.5 256l69.3 69.3c4.7 4.7 4.7 12.3 0 17l-8.5 8.5c-4.7 4.7-12.3 4.7-17 0L256 281.5l-69.3 69.3c-4.7 4.7-12.3 4.7-17 0l-8.5-8.5c-4.7-4.7-4.7-12.3 0-17l69.3-69.3-69.3-69.3c-4.7-4.7-4.7-12.3 0-17l8.5-8.5c4.7-4.7 12.3-4.7 17 0l69.3 69.3 69.3-69.3c4.7-4.7 12.3-4.7 17 0l8.5 8.5c4.6 4.7 4.6 12.3 0 17z"
                    class=""></path>
            </svg></button>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-xl-10 col-lg-10">
                <form>
                    <input type="search" name="search" placeholder="Search Products…" required>
                    <button type="submit">search</button>
                </form>
            </div>
        </div>
    </div>
</div>

<!-- -----------SEARCH MODEL CODE END-------------- -->

<!-- -----------WISHLIST MODEL CODE START-------------- -->
<div class="wish-list">
    <button class="close"><svg aria-hidden="true" focusable="false" data-prefix="fal" data-icon="times-circle"
                role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"
                class="svg-inline--fa fa-times-circle fa-w-16 fa-fw fa-2x">
                <path fill="currentColor"
                    d="M256 8C119 8 8 119 8 256s111 248 248 248 248-111 248-248S393 8 256 8zm0 464c-118.7 0-216-96.1-216-216 0-118.7 96.1-216 216-216 118.7 0 216 96.1 216 216 0 118.7-96.1 216-216 216zm94.8-285.3L281.5 256l69.3 69.3c4.7 4.7 4.7 12.3 0 17l-8.5 8.5c-4.7 4.7-12.3 4.7-17 0L256 281.5l-69.3 69.3c-4.7 4.7-12.3 4.7-17 0l-8.5-8.5c-4.7-4.7-4.7-12.3 0-17l69.3-69.3-69.3-69.3c-4.7-4.7-4.7-12.3 0-17l8.5-8.5c4.7-4.7 12.3-4.7 17 0l69.3 69.3 69.3-69.3c4.7-4.7 12.3-4.7 17 0l8.5 8.5c4.6 4.7 4.6 12.3 0 17z"
                    class=""></path>
            </svg></button>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-xl-6 col-lg-6 col-md-8">
                <div class="box">
                    <h3>wish list</h3>
                    <div class="single-box">
                        <button class="wish-close"><i class="fas fa-times"></i></button>
                        <div class="part-img">
                            <img src="assets/images/wishlist-1.jpg" alt="image">
                        </div>
                        <div class="part-txt">
                            <a href="#">Lorem Ipsum is simply dummy</a>
                            <p class="price">1 x <span>$100</span></p>
                        </div>
                    </div>
                    <div class="single-box">
                        <button class="wish-close"><i class="fas fa-times"></i></button>
                        <div class="part-img">
                            <img src="assets/images/wishlist-2.jpg" alt="image">
                        </div>
                        <div class="part-txt">
                            <a href="#">Lorem Ipsum is simply dummy</a>
                            <p class="price">1 x <span>$30</span></p>
                        </div>
                    </div>

                    <div class="box-btn">
                        <a href="javascript:void(0);">view full wish list</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>
<!-- -----------WISHLIST MODEL CODE END-------------- -->

<!-- -----------CART MODEL CODE START-------------- -->
<div class="cart-list">
    <button class="close"><svg aria-hidden="true" focusable="false" data-prefix="fal" data-icon="times-circle"
                role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"
                class="svg-inline--fa fa-times-circle fa-w-16 fa-fw fa-2x">
                <path fill="currentColor"
                    d="M256 8C119 8 8 119 8 256s111 248 248 248 248-111 248-248S393 8 256 8zm0 464c-118.7 0-216-96.1-216-216 0-118.7 96.1-216 216-216 118.7 0 216 96.1 216 216 0 118.7-96.1 216-216 216zm94.8-285.3L281.5 256l69.3 69.3c4.7 4.7 4.7 12.3 0 17l-8.5 8.5c-4.7 4.7-12.3 4.7-17 0L256 281.5l-69.3 69.3c-4.7 4.7-12.3 4.7-17 0l-8.5-8.5c-4.7-4.7-4.7-12.3 0-17l69.3-69.3-69.3-69.3c-4.7-4.7-4.7-12.3 0-17l8.5-8.5c4.7-4.7 12.3-4.7 17 0l69.3 69.3 69.3-69.3c4.7-4.7 12.3-4.7 17 0l8.5 8.5c4.6 4.7 4.6 12.3 0 17z"
                    class=""></path>
            </svg></button>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-xl-6 col-lg-6 col-md-8">
                <div class="box">
                    <h3>Shopping Cart</h3>
                    <div class="single-box">
                        <button class="cart-close"><i class="fas fa-times"></i></button>
                        <div class="part-img">
                            <img src="assets/images/wishlist-1.jpg" alt="image">
                        </div>
                        <div class="part-txt">
                            <a href="#">Lorem Ipsum is simply dummy</a>
                            <p class="price">1 x <span>$400</span></p>
                        </div>
                    </div>
                    <div class="single-box">
                        <button class="cart-close"><i class="fas fa-times"></i></button>
                        <div class="part-img">
                            <img src="assets/images/wishlist-2.jpg" alt="image">
                        </div>
                        <div class="part-txt">
                            <a href="#">Lorem Ipsum is simply dummy</a>
                            <p class="price">1 x <span>$300</span></p>
                        </div>
                    </div>

                    <div class="total">
                        <p>subtotal : <span class="amount">$1,025.00</span></p>
                        <p>Eco Tax (-2.00) : <span class="amount">$12.00</span></p>
                        <p>VAT (20%) : <span class="amount">$205.00</span></p>
                        <p>Total : <span class="amount">$1,242.00</span></p>
                    </div>
                    <div class="box-btn">
                        <a href="#">view cart</a>
                        <a href="#">checkout</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

<!-- -----------CART MODEL CODE END-------------- -->

    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
        <router-link to="/contact">Contact</router-link>
    </div> -->


    <router-view/>

<!-- -------------FOOTER CODE START------------- -->
<div class="footer footer-2">
    <div class="main-footer">
        <div class="container">
            <div class="row">
                <div class="col-xl-3 col-lg-3 col-sm-6">
                    <div class="f-about">
                        <div class="title">
                            <h2>About Us</h2>
                        </div>
                        <div class="part-txt">
                            <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make
                                a type specimen book.</p>
                            <a href="javascript:void(0);" class="read-more">Read More</a>
                        </div>
                    </div>
                </div>
                <div class="col-xl-3 col-lg-3 col-sm-6">
                    <div class="f-link">
                        <div class="title">
                            <h2>Information</h2>
                        </div>
                        <ul>
                            <li><a href="javascript:void(0);"><span><i class="icofont-curved-double-right"></i></span> About Us</a>
                            </li>
                            <li><a href="javascript:void(0);"><span><i class="icofont-curved-double-right"></i></span> Delivery
                                        Information</a></li>
                            <li><a href="javascript:void(0);"><span><i class="icofont-curved-double-right"></i></span> Privacy
                                        Policy</a></li>
                            <li><a href="javascript:void(0);"><span><i class="icofont-curved-double-right"></i></span> Terms &
                                        Conditions</a></li>
                            <li><a href="javascript:void(0);"><span><i class="icofont-curved-double-right"></i></span> Customer
                                        Service</a></li>
                            <li><a href="javascript:void(0);"><span><i class="icofont-curved-double-right"></i></span> Return
                                        Policy</a></li>
                            <li><a href="javascript:void(0);"><span><i class="icofont-curved-double-right"></i></span> New
                                        products</a></li>
                        </ul>
                    </div>
                </div>
                <div class="col-xl-3 col-lg-3 col-sm-6">
                    <div class="f-link">
                        <div class="title">
                            <h2>our policy</h2>
                        </div>
                        <ul>
                            <li><a href="javascript:void(0);"><span><i class="icofont-curved-double-right"></i></span> Help &
                                        Contact</a></li>
                            <li><a href="javascript:void(0);"><span><i class="icofont-curved-double-right"></i></span> Shipping &
                                        taxes</a></li>
                            <li><a href="javascript:void(0);"><span><i class="icofont-curved-double-right"></i></span> Return
                                        policy</a></li>
                            <li><a href="javascript:void(0);"><span><i class="icofont-curved-double-right"></i></span> Guest
                                        purchase</a></li>
                            <li><a href="javascript:void(0);"><span><i class="icofont-curved-double-right"></i></span> Affiliates</a>
                            </li>
                            <li><a href="javascript:void(0);"><span><i class="icofont-curved-double-right"></i></span> Legal
                                        Notice</a></li>
                            <li><a href="javascript:void(0);"><span><i class="icofont-curved-double-right"></i></span> Payment</a>
                            </li>
                        </ul>
                    </div>
                </div>
                <div class="col-xl-3 col-lg-3 col-sm-6">
                    <div class="news-letter f-about">
                        <div class="title">
                            <h2>Contact Us</h2>
                        </div>
                        <div class="part-txt mb-3">
                            <ul>
                                <li><span><svg aria-hidden="true" focusable="false" data-prefix="fas"
                                            data-icon="map-marker-alt" role="img" xmlns="http://www.w3.org/2000/svg"
                                            viewBox="0 0 384 512"
                                            class="svg-inline--fa fa-map-marker-alt fa-w-12 fa-fw fa-2x">
                                            <path fill="currentColor"
                                                d="M172.268 501.67C26.97 291.031 0 269.413 0 192 0 85.961 85.961 0 192 0s192 85.961 192 192c0 77.413-26.97 99.031-172.268 309.67-9.535 13.774-29.93 13.773-39.464 0zM192 272c44.183 0 80-35.817 80-80s-35.817-80-80-80-80 35.817-80 80 35.817 80 80 80z"
                                                class=""></path>
                                        </svg></span> 3d plus, Skodsborgvej 76, 9270 Klarup, Denmark</li>
                                <li><span><svg aria-hidden="true" focusable="false" data-prefix="fas"
                                            data-icon="phone-alt" role="img" xmlns="http://www.w3.org/2000/svg"
                                            viewBox="0 0 512 512"
                                            class="svg-inline--fa fa-phone-alt fa-w-16 fa-fw fa-2x">
                                            <path fill="currentColor"
                                                d="M497.39 361.8l-112-48a24 24 0 0 0-28 6.9l-49.6 60.6A370.66 370.66 0 0 1 130.6 204.11l60.6-49.6a23.94 23.94 0 0 0 6.9-28l-48-112A24.16 24.16 0 0 0 122.6.61l-104 24A24 24 0 0 0 0 48c0 256.5 207.9 464 464 464a24 24 0 0 0 23.4-18.6l24-104a24.29 24.29 0 0 0-14.01-27.6z"
                                                class=""></path>
                                        </svg></span> 0045 29890472</li>
                                <li><span><svg aria-hidden="true" focusable="false" data-prefix="fas"
                                            data-icon="envelope" role="img" xmlns="http://www.w3.org/2000/svg"
                                            viewBox="0 0 512 512"
                                            class="svg-inline--fa fa-envelope fa-w-16 fa-fw fa-2x">
                                            <path fill="currentColor"
                                                d="M502.3 190.8c3.9-3.1 9.7-.2 9.7 4.7V400c0 26.5-21.5 48-48 48H48c-26.5 0-48-21.5-48-48V195.6c0-5 5.7-7.8 9.7-4.7 22.4 17.4 52.1 39.5 154.1 113.6 21.1 15.4 56.7 47.8 92.2 47.6 35.7.3 72-32.8 92.3-47.6 102-74.1 131.6-96.3 154-113.7zM256 320c23.2.4 56.6-29.2 73.4-41.4 132.7-96.3 142.8-104.7 173.4-128.7 5.8-4.5 9.2-11.5 9.2-18.9v-19c0-26.5-21.5-48-48-48H48C21.5 64 0 85.5 0 112v19c0 7.4 3.4 14.3 9.2 18.9 30.6 23.9 40.7 32.4 173.4 128.7 16.8 12.2 50.2 41.8 73.4 41.4z"
                                                class=""></path>
                                        </svg></span> <a href="mailto:simon@3dplus.dk" class="__cf_email__">simon@3dplus.dk</a>
                                </li>
                            </ul>
                        </div>

                        <div class="social">
                            <a href="#" class="fb"><i class="fab fa-facebook-f"></i></a>
                            <a href="#" class="tw"><i class="fab fa-twitter"></i></a>
                            <a href="#" class="gl"><i class="fab fa-google-plus-g"></i></a>
                            <a href="#" class="ld"><i class="fab fa-linkedin-in"></i></a>
                            <a href="#" class="yt"><i class="fab fa-youtube"></i></a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="copyright">
        <div class="container">
            <div class="row">
                <div class="col-xl-6 col-lg-6 col-md-6 d-xl-flex d-lg-flex align-items-center">
                    <div class="part-txt">
                        <p>Copyright &copy; 2021 <span class="floatmatic-foot">floatmatic</span>. All Rights Reserved</p>
                    </div>
                </div>
                <div class="col-xl-6 col-lg-6 col-md-6">
                    <div class="part-img">
                        <img src="assets/images/card.png" alt="card">
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>
<!-- --------------FOOTER CODE END------------- -->

  </div>
</template>
<style>




</style>
