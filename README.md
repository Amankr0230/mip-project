<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flipkart</title>
    <link rel="stylesheet" href="style.css">
    <link rel="icon" type="image/x-icon" href="favicon.ico">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

    <style>
        *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    }

.dropdown{
    position: relative;
    display: inline-block;
    overflow: visible;
}
.dropdown-conent{
    display: none;
    position: absolute;
    background-color: white;
    min-width: 250px;
    text-align: left;
    overflow: visible;
    padding-left: 5px;
    font-family: Roboto,Arial,sans-serif;

}
.dropdown:hover .dropdown-conent{
    display: block;
    align-self: center;
    overflow: visible;
}

.dropdown .dropdown-conent p{
    padding-top: 10px;
    padding-bottom: 10px;
}

header{ 
    /* padding-top: 6px; */
    background-color:blue;
    /* margin-top: auto;
    margin-bottom: auto; */
    
}

.logo img{
    width: 98px;
    margin-right: 10px;
    display: inline-block;
    margin-left: 155px;
    
}

.search{
    display: inline;
}
.search input{
    border: none;
    padding-top: 10px;
    padding-bottom: 10px;
    padding-left: 15px;
    padding-right: 10px;
    margin-left: 5px;
    margin-right: 58px;
    width: 470px;
    margin-bottom: 10px;
    margin-top: -50px;
}

div{
    display: inline-block;
    margin-bottom: 10px;
    padding-bottom: 10px;
    padding-top: 6px;
}

div span{
    color: white;
    font-weight: bold;
    margin-right: 50px;
}
.cart img{
    width: 30px;
    margin-right: 0px;
    margin-left: 100px;

    
}

 .bar h4 {
    text-align: center;
    margin-left: 0px;
    border:2px solid black;
    border-style: none;
} 

.bar div:hover{
    color: #2874f0;
}

.bar img{
    margin-left: 34px;
    border:2px solid red;
    border-style: none;
}

.slider{
    background-color: #F1F3F6;
    
    padding-left: 100px;
}


/* Slideshow container */
.slideshow-container {
    max-width: 1000px;
    position: relative;
    margin: auto;
  }
  
  /* Next & previous buttons */
  .prev, .next {
    cursor: pointer;
    position: absolute;
    top: 50%;
    width: auto;
    padding: 16px;
    margin-top: -22px;
    color: black;
    background-color: white;
    font-weight: bold;
    font-size: 30px;
    transition: 0.6s ease;
    border-radius: 8px;
    user-select: none;
    border: 2rem;
  }
  
  .prev{
      margin-left: 12px;
  }
  /* Position the "next button" to the right */
  .next {
    right: 0;
    margin-right: -260px;
    border-radius: 8px;

  }
  
  /* Fading animation */
  .fade {
    -webkit-animation-name: fade;
    -webkit-animation-duration: 1.5s;
    animation-name: fade;
    animation-duration: 1.5s;
  }
  
  @-webkit-keyframes fade {
    from {opacity: .4} 
    to {opacity: 1}
  }
  
  @keyframes fade {
    from {opacity: .4} 
    to {opacity: 1}
  }
  
  /* On smaller screens, decrease text size */
  @media only screen and (max-width: 300px) {
    .prev, .next,.text {font-size: 11px}
  }
  /* img {vertical-align: middle;} */

  .slideshow-container img{
      margin-left: 28px;
      padding-left: 10px;
  }

  .slider img{
      margin-bottom: -25px;
      padding-bottom: -15px;
  }

  .top1 {
      margin: 3px;
      background-color: white;


  }
.top1 h1{
    width: 300px;
    margin-left: 50px;
}

.top1 h1 ,button{
    display: inline;
    position: relative;
}

  .top1 button{
      background-color: #2874f0;
      color: white;
      padding-left: 10px;
      padding-bottom: 10px;
      padding-top: 10px;
      padding-right: 10px;
      border: none;
      margin-left: 700px;
  }

  .topDeal{
      background-color: #F1F3F6;
      border:2px solid black;
      padding-left:90px;
  }

  .content .t1,.t2,.t3,.t4,.t5{
      text-align: center;
      background-color: white;
      /* margin-left: 10px; */
      margin-top: -25px;
  }
.green{
    color: green;
}

/* <!-- footer --> */
footer{
    background-color: #172337;
    height: 332;
}
.footer-row{
    width: 100%;
    height: 270px;
    display: flex;
    padding: 30px 60px;
}
.footer-row2{
    display: flex;
    border-top: 1px solid #454d5e;
    justify-content: space-evenly;
}
.footer-col-1{
    width: 15%;
}
.footer-col-2{
    width: 15%;
}
.footer-col-3{
    width: 15%;
}
.footer-col-4{
    width: 10%;
}
.footer-col-5{
    width: 20%;
    border-left:1px solid #454d5e ;
    height: 120px;
    padding-left: 25px;
}
.footer-col-6{
    width: 20%;
    padding-left: 50px;
}
.footer-heading p{
 color: #878787;
 font-size: 12px;
 font-weight: 400;
 text-align: left;
 padding: 10px 0px;
 cursor: pointer;
 text-transform: uppercase;
}
.footer-list a{
    text-align: left;
    display: block;
    text-decoration: none;
   text-transform: capitalize;
    color: white;
    font-size: 12px;
    font-weight: 400;
    padding: 5px 0px;
}
.footer-list a:hover{
    text-decoration: underline;
}
.footer-list  p{
    text-align: left;
    display: block;
    color: white;
    font-size: 12px;
    font-weight: 100px;
    padding:5px 0px;
    line-height: 20px;
    cursor: pointer;
}
.footer-list-address p{
    text-align: left;
    display: block;
    color: white;
    font-size: 12px;
    font-weight: 100px;
    line-height: 20px;
     cursor: pointer;
}
.footer-list-address span{
    color: rgb(60,109,245);
    cursor: pointer;
}
.footer-row2-col p{
  color: white;
    font-size: 15px;
    font-weight: 100px;
    line-height: 20px;
     cursor: pointer;
      text-align: center;
      line-height: 50px;
      letter-spacing: .7px;
}
.fa-shopping-bag, .fa-star, .fa-gift ,.fa-question-circle{
    color: #ffd700;
    cursor: pointer;
   padding-right: 10px;
   padding-left:10px;
   
   font-size: 15px;
}

.ashop{
    color:#172337;
    text-decoration: none;
}
a:hover{
    color:blue;
    
}
.search{
    width: 500px;
    height:30px;
    margin-left:30px;
    margin-top:20px;
    border-radius: 5px;
    
}
.log{
    margin-left:50px;
    border:2px solid black;
    background-color: white;
    padding-right:15px;
    padding-left:15px;
    border-style:none;
    border-radius: 10px;
}


    </style>
</head>
<body>
    <header>
        <nav>
            <div class="logo">
                <img src="https://static-assets-web.flixcart.com/www/linchpin/fk-cp-zion/img/fk-plus_3b0baa.png" alt="" srcset="">
            </div>
            <div class="dropdown">
                <span>Categories</span>
                <div class="dropdown-conent">
                    <p> <img src="https://cdn4.iconfinder.com/data/icons/social-messaging-ui-color-and-shapes-3/177800/130-512.png " width="25px" >  My Profile</p>
                    <p>SuperCoin</p>
                    <p>Flipkart Plus Zone</p>
                    <p>Orders</p>
                    <p>Wishlist</p>
                    <p>My chats</p>
                    <p>Coupons</p>
                    <p>Gift Card</p>
                    <p>Notification</p>
                    <p>Logout</p>
                </div>
            </div>

            <div class="dropdown">
                <span>More</span>
                <div class="dropdown-conent">
                    <p>Notification Preference</p>
                    <p>Sell on Flipkart</p>
                    <p>24x7 Customer Care</p>
                    <p>Advertise</p>
                    <p>Download App/p>
                </div>
            </div>
            <div class="log">login</div>
            <div class="alls">
            <input type="search"  content="search" class="search">
            <div class="fa fa-search" style="color:black; border:1px solid black; height: 29px;border-radius:15px;background-color: white; padding-bottom:1px;width:30px;padding-left: 8px; border-style: none;"></div>
            </div>
            <div class="cart">
                <img src="https://www.pngkey.com/png/full/231-2317482_white-shopping-cart-png-download-buy-icon-white.png" alt="" srcset="">
                <span>Cart</span>
            </div>
        </nav>
    </header>

    <section class="bar">
        <div class="topoffer">
            <img src="https://rukminim1.flixcart.com/flap/128/128/image/f15c02bfeb02d15d.png?q=100" alt="Avatar" style="width:53%">
              <h4><b>Top Offer</b></h4>
          </div>

          <div class="grocery">
              <img src="https://rukminim1.flixcart.com/flap/128/128/image/29327f40e9c4d26b.png?q=100" alt="" style="width:53%">
              <h4><b>Grocery</b></h4>
          </div>

          <div class="mobiles">
              <img src="https://rukminim1.flixcart.com/flap/128/128/image/22fddf3c7da4c4f4.png?q=100" style="width:53%">
              <h4><b>Mobile</b></h4>
          </div>

          <div class="fashion">
            <img src="https://rukminim1.flixcart.com/flap/128/128/image/82b3ca5fb2301045.png?q=100" style="width:53%">
            <h4><b>Fashion</b></h4>
          </div>

          <div class="electronics">
            <img src="https://rukminim1.flixcart.com/flap/128/128/image/69c6589653afdb9a.png?q=100" style="width:53%">
            <h4><b>Electronics</b></h4>
          </div>
          <div class="home">
            <img src="https://rukminim1.flixcart.com/flap/128/128/image/ab7e2b022a4587dd.jpg?q=100" style="width:53%">
            <h4><b>Home</b></h4>
          </div>

          <div class="appliances">
            <img src="https://rukminim1.flixcart.com/flap/128/128/image/0ff199d1bd27eb98.png?q=100" style="width:53%">
            <h4><b>Appliances</b></h4>
          </div>

          <div class="travel">
            <img src="https://rukminim1.flixcart.com/flap/128/128/image/71050627a56b4693.png?q=100" style="width:53%">
            <h4><b>Travel</b></h4>
          </div>
          <div class="beauty">
            <img src="https://rukminim1.flixcart.com/flap/128/128/image/dff3f7adcf3a90c6.png?q=100" style="width:53%">
            <h4><b>Beauty, Toys & More</b></h4>
          </div>
    </section>

    <section class="slider">
            <div class="slideshow-container">

                <div class="mySlides fade">
                  <img src="https://th.bing.com/th/id/OIP.LvaTr6wKaYNoBy0ZSZXUXgHaDW?w=350&h=158&c=7&r=0&o=5&dpr=1.35&pid=1.7" style="width:1200px", height="270px">
                </div>
                
                <div class="mySlides fade">
                  <img src="https://mir-s3-cdn-cf.behance.net/project_modules/disp/b0b6e217784937.5676ca4a7dbba.jpg" style="width:1200px", height="270px">
                </div>
                
                <div class="mySlides fade">
                    <img src="https://storiesflistgv2.azureedge.net/stories/2019/09/Banner-01-800x360.jpg" style="width:1200px", height="270px">
                </div>
                
                <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
                <a class="next" onclick="plusSlides(1)">&#10095;</a>
                </div>
    
                <script>
                var slideIndex = 1;
                showSlides(slideIndex);
                
                function plusSlides(n) {
                  showSlides(slideIndex += n);
                }
                

                function showSlides(n) {
                  var i;
                  var slides = document.getElementsByClassName("mySlides");
                  var dots = document.getElementsByClassName("dot");
                  if (n > slides.length) {slideIndex = 1}    
                  if (n < 1) {slideIndex = slides.length}
                  for (i = 0; i < slides.length; i++) {
                      slides[i].style.display = "none";  
                  }
                  for (i = 0; i < dots.length; i++) {
                      dots[i].className = dots[i].className.replace(" active", "");
                  }
                  slides[slideIndex-1].style.display = "block";  
                  dots[slideIndex-1].className += " active";
                }
                </script>
                  </section>
                  <br>
                       <section class="topDeal">
                            <div class="top1">
                              <h1>Top Deals On Fashion</h1>
                              <button>VIEW ALL</button>
                            </div>
                  <hr>
                  <br>
                            <div class="content">
                              <div class="t1">
                                <img src="https://rukminim1.flixcart.com/image/300/300/k5vcya80/cargo/f/3/k/36-k2s-465-10394-maartiza-original-imafcyz5qyjjk2ph.jpeg?q=70" style="width:53%">
                                <h4><b>Best of Brands!</b></h4>
                                <p class="green"> Min 50% Off </p>
                                <p>Men's Clothing</p>
                                <a href="#" class="ashop">Shop Now!</a>
                            </div>
                    
                            <div class="t2">
                                <img src="https://rukminim1.flixcart.com/image/300/300/khp664w0/jacket/n/c/f/m-58969702-puma-original-imafxmgqzj7eahht.jpeg?q=70" style="width:53%">
                                <h4><b>GAP, Puma, Roadster....</b></h4>
                                <p class="green">Min 55% Off</p>
                                <p>Jackets, Sweatshirts & m...</p>
                                <a href="#" class="ashop">Shop Now!</a>
                            </div>
                    
                            <div class="t3">
                                <img src="https://rukminim1.flixcart.com/image/300/300/kltryq80/kids-t-shirt/q/9/a/8-9-years-ktb-singham-original-imagyv6vvzxquqp6.jpeg?q=70" style="width:53%">
                                <h4><b>Men's T-shirts</b></h4>
                                <p class="green">30-60% Off</p>
                                <p>Widest Range</p>
                                <a href="#" class="ashop">Shop Now!</a>
                            </div>
                            <div class="t4">
                                <img src="https://rukminim1.flixcart.com/image/300/300/kao98cw0/ethnic-set/y/u/c/42-kdhl-kurta-dhotipant-abh-lifestyle-original-imafs76yzgewevah.jpeg?q=70" style="width:53%">
                                <h4><b>Peter England, British....</b></h4>
                                <p class="green">Min 35% Off</p>
                                <a href="#" class="ashop">Shop Now!</a>
                              </div>
                  
                            <div class="t5">
                                <img src="https://rukminim1.flixcart.com/image/300/300/kly2aa80/track-pant/g/n/d/m-trackpant9013-vitaan-original-imagyydmyng5gzce.jpeg?q=70" style="width:53%">
                                <h4><b>Men's Track Pant</b></h4>
                                <p class="green">Min 60% off</p>
                                <p>Shop Now!</p>
                              </div>
                            </div>
                            </div>
                      </section> 
                      
                       <section class="topDeal">
                            <div class="top1">
                              <h1>Men's Footwear</h1>
                              <button>VIEW ALL</button>
                            </div>
                  <hr>
                  <br>
                            <div class="content">
                              <div class="t1">
                                <img src="https://rukminim1.flixcart.com/image/300/300/kg15ocw0-0/shoe/d/m/k/749794-001nike-nike-wolf-grey-black-white-original-imafwcae3h5xerag.jpeg?q=70" style="width:53%">
                                <h4><b>Nike, Skechers & more</b></h4>
                                <p class="green"> Upto 40% Off </p>
                                <p>Men's Sports Shoes..</p>
                                <a href="#" class="ashop">Shop Now!</a>
                            </div>
                            <div class="t2">
                                <img src="https://rukminim1.flixcart.com/image/300/300/knrsjgw0/sandal/v/w/3/3-205089-4-crocs-light-grey-candy-pink-original-imag2dc2wwtuwzam.jpeg?q=70" style="width:53%">
                                <h4><b>CROCS</b></h4>
                                <p class="green">Min 30% Off</p>
                                <p>Clogs, Sandals & more</p>
                                <a href="#" class="ashop">Shop Now!</a>
                            </div>
                    
                            <div class="t3">
                                <img src="https://rukminim1.flixcart.com/image/300/300/jx3kn0w0/slipper-flip-flop/8/y/b/368272-8-puma-ponderosa-pine-black-white-original-imafhmr9n22rakag.jpeg?q=70" style="width:53%">
                                <h4><b>Puma, Asian & more</b></h4>
                                <p class="green">From ₹199</p>
                                <p>Slippers -Flip-Flops</p>
                                <a href="#" class="ashop">Shop Now!</a>
                            </div>
                    
                            <div class="t4">
                                <img src="https://rukminim1.flixcart.com/image/300/300/jvv9zm80/sandal/j/g/w/gd-2665117camel-40-woodland-camel-original-imafgztfhjdp6xmg.jpeg?q=70" style="width:53%">
                                <h4><b>Woodland, Crocs ....</b></h4>
                                <p class="green">Min 50% Off</p>
                                <p>Slippers & Floaers</p>
                                <a href="#" class="ashop">Shop Now!</a>
                              </div>
                  
                            <!-- <div class="t5">
                                <img src="https://rukminim1.flixcart.com/image/300/300/krxtrww0/shoe/3/b/o/10-sx0677g-sparx-turkeyblueblack-original-imag5mcfzuvssh8y.jpeg?q=70" style="width:53%">
                                <h4><b>Seaon's Best Seller/b></h4>
                                <p class="green">From 149</p>
                                <p>Shoes, Sandals & more</p>
                              </div> -->
                            </div>
                            </div>
                      </section> 
                  
                      <footer>  <div class="footer-row">
                        <div class="footer-col-1">
                            <div class="footer-heading">
                                 <p>ABOUT</p>
                            </div>
                            <div class="footer-list">
                                <a href="#">Contact Us</a>
                                <a href="#">About Us</a>
                                <a href="#">Careers</a>
                                <a href="#">Flipkart Stories</a>
                                <a href="#">Press</a>
                                <a href="#">Flipkart Wholesale</a>
                            </div>
                        </div>
                        <div class="footer-col-2">
                            <div class="footer-heading">
                                 <p>HELP</p>
                            </div>
                            <div class="footer-list">
                                <a href="#">Payments</a>
                                <a href="#">Shipping</a>
                                <a href="#">Cancellation & Returns</a>
                                <a href="#">FAQ</a>
                                <a href="#">Report Infringement</a>
                                
                            </div>
                        </div>
                        <div class="footer-col-3">
                            <div class="footer-heading">
                                 <p>POLICY</p>
                            </div>
                            <div class="footer-list">
                                <a href="#">Return Policy</a>
                                <a href="#">Terms Of Use</a>
                                <a href="#">Security</a>
                                <a href="#">Privacy</a>
                                <a href="#">Sitemap</a>
                                <a href="#">EPR Compliance</a>
                            </div>
                        </div>
                        <div class="footer-col-4">
                            <div class="footer-heading">
                                 <p>SOCIAL</p>
                            </div>
                            <div class="footer-list">
                                <a href="#">Facebook</a>
                                <a href="#">Twitter</a>
                                <a href="#">YouTube</a>
                               
                            </div>
                        </div>
                
                        <div class="footer-col-5">
                            <div class="footer-heading">
                                 <p>Mail Us</p>
                            </div>
                            <div class="footer-list">
                                 <p>Flipkart Internet Private Limited,
                                    Buildings Alyssa, Begonia &
                                    Clove Embassy Tech Village,
                                    Outer Ring Road, Devarabeesanahalli Village,
                                    Bengaluru, 560103,
                                    Karnataka, India</p>
                               
                            </div>
                        </div>
                
                        <div class="footer-col-6">
                            <div class="footer-heading">
                                 <p>Registered Office Address</p>
                            </div>
                            <div class="footer-list-address">
                             <p>Flipkart Internet Private Limited,</p>
                             <p>Buildings Alyssa, Begonia &</p>
                             <p>Clove Embassy Tech Village,</p>
                             <p>Outer Ring Road, Devarabeesanahalli Village,</p>
                             <p>Bengaluru, 560103,</p>
                             <p>Karnataka, India</p>
                             <p>CIN : U51109KA2012PTC066107</p>
                             <p> Telephone:<span> 1800 202 9898</span></p>
                               
                            </div>
                        </div>
                    </div>
                    <div class="footer-row2">
                        <div class="footer-row2-col">
                            <p> <i class="fas fa-shopping-bag"></i>Sell On Flipkart</p>
                        </div>
                        <div class="footer-row2-col">
                            <p><i class="fas fa-star"></i>Advertise</p>
                        </div>
                        <div class="footer-row2-col">
                            <p><i class="fas fa-gift"></i>Gift Cards</p>
                        </div>
                        <div class="footer-row2-col">
                            <p><i class="fas fa-question-circle"></i>Help Center</p>
                        </div>
                        <div class="footer-row2-col">
                            <p>© 2007-2021 Flipkart.com</p>
                        </div>
                        <div class="footer-row2-col">
                            <img src="https://static-assets-web.flixcart.com/www/linchpin/fk-cp-zion/img/payment-method_69e7ec.svg" alt="payments">
                        </div>
                    </div>
                </footer>
                
              
              
              </body>
              </html>                                    
