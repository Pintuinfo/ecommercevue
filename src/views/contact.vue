<template>
  <div class="contact-sec">
   <div class="breadcrumb-area bg-3">
        <div class="container">
            <div class="row justify-content-center">
                <div class="col-xl-5 col-lg-5">
                    <div class="breadcrumb-txt">
                        <h1>Contact Us</h1>
                        <ul>
                            <li class="active"><a href="index.html">Home</a></li>
                            <li><i class="fas fa-chevron-right"></i></li>
                            <li>Contact Us</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div class="contact">
        <div class="container">
            <div class="contact-box">
                <div class="row">
                    <div class="col-xl-4 col-lg-4 col-md-5">
                        <div class="contact-info">
                            <h2 class="title">Contact Info</h2>
                            <div class="single-box">
                                <div class="part-icon">
                                    <span><i class="fas fa-map-marker-alt"></i></span>
                                </div>
                                <div class="part-txt">
                                    <h3>Your Location</h3>
                                    <p>3d plus, Skodsborgvej 76, 9270 Klarup, Denmark</p>
                                </div>
                            </div>
                            <div class="single-box">
                                <div class="part-icon">
                                    <span><i class="fas fa-envelope"></i></span>
                                </div>
                                <div class="part-txt">
                                    <h3>Your Email</h3>
                                    <p><span>simon@3dplus.dk</span></p>
                                </div>
                            </div>
                            <div class="single-box">
                                <div class="part-icon">
                                    <span><i class="fas fa-phone"></i></span>
                                </div>
                                <div class="part-txt">
                                    <h3>Phone Number</h3>
                                    <p><span>0045 29890472</span></p>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-xl-8 col-lg-8 col-md-7">
                        <div class="contact-form">
                            <h2 class="title">Get in Touch</h2>
                            <form>
                                <input type="text" placeholder="Your Name *" required="">
                                <input type="tel" placeholder="Phone *" required="">
                                <input type="email" placeholder="Email *" required="">
                                <input type="text" placeholder="Subject *" required="">
                                <textarea placeholder="Message" required=""></textarea>
                                <button>SUBMIT NOW</button>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>


    <div class="google-map-sec">
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2172.431491390747!2d10.061047916083782!3d57.00991890180253!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x464ecc4a7ed2862b%3A0xd348439bc7ca13f8!2sSkodsborgvej%2076%2C%209270%20Klarup%2C%20Denmark!5e0!3m2!1sen!2sin!4v1626084950319!5m2!1sen!2sin"
            allowfullscreen="" loading="lazy"></iframe>
    </div>
  </div>
</template>


<script>
export default {
    name:"contact"
}
</script>
