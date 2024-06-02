# hospital-managment-website-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Complete Responsive Hospital Website</title>

    <!-- Font Awesome CDN link  -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">

    <!-- Custom CSS file link  -->
    <link rel="stylesheet" href="style.css">

</head>
<body>
    
<!-- Header section starts  -->

<header class="header">

    <a href="#" class="logo"> <i class="fas fa-heartbeat"></i> <strong>WC</strong>medical </a>

    <nav class="navbar">
        <a href="#home">home</a>
        <a href="#about">about</a>
        <a href="#services">services</a>
        <a href="#doctors">doctors</a>
        <a href="#appointment">appointment</a>
        <a href="#review">review</a>
        <a href="#blogs">blogs</a>
    </nav>

    <div id="menu-btn" class="fas fa-bars"></div>

</header>

<!-- Header section ends -->

<!-- Home section starts  -->

<section class="home" id="home">

    <div class="image">
        <img src="image/home-img.svg" alt="">
    </div>

    <div class="content">
        <h3>We Take Care of Your Healthy Life</h3>
        <p>A person who has good physical health is likely to have bodily functions and processes working at their peak.</p>
    </div>

</section>

<!-- Home section ends -->

<!-- Icons section starts  -->

<section class="icons-container">

    <div class="icons">
        <i class="fas fa-user-md"></i>
        <h3>Doctors at Work</h3>
    </div>

    <div class="icons">
        <i class="fas fa-users"></i>
        <h3>Satisfied Patients</h3>
    </div>

    <div class="icons">
        <i class="fas fa-procedures"></i>
        <h3>Bed Facility</h3>
    </div>

    <div class="icons">
        <i class="fas fa-hospital"></i>
        <h3>Available Hospitals</h3>
    </div>

</section>

<!-- Icons section ends -->

<!-- About section starts  -->

<section class="about" id="about">

    <h1 class="heading"> <span>About</span> Us </h1>

    <div class="row">

        <div class="image">
            <img src="image/about-img.svg" alt="">
        </div>

        <div class="content">
            <h3>Take the World's Best Quality Treatment</h3>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Iure ducimus, quod ex cupiditate ullam in assumenda maiores et culpa odit tempora ipsam qui, quisquam quis facere iste fuga, minus nesciunt.</p>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Natus vero ipsam laborum porro voluptates voluptatibus a nihil temporibus deserunt vel?</p>
        </div>

    </div>

</section>

<!-- About section ends -->

<!-- Services section starts  -->

<section class="services" id="services">

    <h1 class="heading"> Our <span>Services</span> </h1>

    <div class="box-container">

        <div class="box">
            <i class="fas fa-notes-medical"></i>
            <h3>Free Checkups</h3>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ad, omnis.</p>
        </div>

        <div class="box">
            <i class="fas fa-ambulance"></i>
            <h3>24/7 Ambulance</h3>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ad, omnis.</p>
        </div>

        <div class="box">
            <i class="fas fa-user-md"></i>
            <h3>Expert Doctors</h3>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ad, omnis.</p>
        </div>

        <div class="box">
            <i class="fas fa-pills"></i>
            <h3>Medicines</h3>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ad, omnis.</p>
        </div>

        <div class="box">
            <i class="fas fa-procedures"></i>
            <h3>Bed Facility</h3>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ad, omnis.</p>
        </div>

        <div class="box">
            <i class="fas fa-heartbeat"></i>
            <h3>Total Care</h3>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ad, omnis.</p>
        </div>

    </div>

</section>

<!-- Services section ends -->

<!-- Doctors section starts  -->

<section class="doctors" id="doctors">

    <h1 class="heading"> Our <span>Doctors</span> </h1>

    <div class="box-container">

        <div class="box">
            <img src="image/doc-1.jpg" alt="">
            <h3>Win Coder</h3>
            <span>Expert Doctor</span>
        </div>

        <!-- Add other doctor boxes similarly -->

    </div>

</section>

<!-- Doctors section ends -->

<!-- Footer section starts  -->

<section class="footer">

    <div class="box-container">

        <div class="box">
            <h3>Quick Links</h3>
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#services">Services</a>
            <a href="#doctors">Doctors</a>
            <a href="#appointment">Appointment</a>
            <a href="#review">Review</a>
            <a href="#blogs">Blogs</a>
        </div>

        <div class="box">
            <h3>Our Services</h3>
            <a href="#">Dental Care</a>
            <a href="#">Massage Therapy</a>
            <a href="#">Cardiology</a>
            <a href="#">Diagnosis</a>
            <a href="#">Ambulance Service</a>
        </div>

        <div class="box">
            <h3>Appointment Info</h3>
            <a href="#">+8801688238801</a>
            <a href="#">+8801782546978</a>
            <a href="#">wincoder9@gmail.com</a>
            <a href="#">sujoncse26@gmail.com</a>
            <a href="#">Sylhet, Bangladesh</a>
        </div>

        <div class="box">
            <h3>Follow Us</h3>
            <a href="#">Facebook</a>
            <a href="#">Twitter</a>
            <a href="#">Instagram</a>
            <a href="#">Linkedin</a>
            <a href="#">Pinterest</a>
        </div>

    </div>

    <div class="credit">Created by <span>Win Coder</span> | All rights reserved</div>

</section>

<!-- Footer section ends -->


<!-- JS file link  -->
<script src="js/script.js"></script>

</body>
</html>
 CSS CODE -
 :root{
    --green:#16a085;
    --black:#444;
    --light-color:#111;
    --box-shadow:.5rem .5rem 0 rgba(22, 160, 133, .2);
    --text-shadow:.4rem .4rem 0 rgba(0, 0, 0, .2);
    --border:.2rem solid var(--green);
}
*{
    font-family: 'Poppins', sans-serif;
    margin:0; padding: 0;
    box-sizing: border-box;
    outline: none; border: none;
    text-transform: capitalize;
    transition: all .2s ease-out;
    text-decoration: none;
}
html{
    font-size: 62.5%;
    overflow-x: hidden;
    scroll-padding-top: 7rem;
    scroll-behavior: smooth;
}
section{
    padding:2rem 9%;
}
section:nth-child(even){
    background: #f5f5f5;
}
.heading{
    text-align: center;
    padding-bottom: 2rem;
    text-shadow: var(--text-shadow);
    text-transform: uppercase;
    color:var(--black);
    font-size: 5rem;
    letter-spacing: .4rem;
}
.heading span{
    text-transform: uppercase;
    color:var(--green);
}
.btn{
    display: inline-block;
    margin-top: 1rem;
    padding: .5rem;
    padding-left: 1rem;
    border:var(--border);
    border-radius: .5rem;
    box-shadow: var(--box-shadow);
    color:var(--green);
    cursor: pointer;
    font-size: 1.7rem;
    background: #fff;
}

.btn span{
    padding:.7rem 1rem;
    border-radius: .5rem;
    background: var(--green);
    color:#fff;
    margin-left: .5rem;}
.btn:hover{
    background: var(--green);
    color:#fff;}
.btn:hover span{
    color: var(--green);
    background:#fff;
    margin-left: 1rem;}
.header{
    padding:2rem 9%;
    position: fixed;
    top:0; left: 0; right: 0;
    z-index: 1000;
    box-shadow: 0 .5rem 1.5rem rgba(0, 0, 0, .1);
    display: flex;
    align-items: center;
    justify-content: space-between;
    background: #33d9b2;}
.header .logo{
    font-size: 2.5rem;
    color: var(--black);}
.header .logo i{
    color: #c0392b;}
.header .navbar a{
    font-size: 1.7rem;
    color: var(--light-color);
    margin-left: 2rem;
}
.header .navbar a:hover{
    color:red;}
#menu-btn{
    font-size: 2.5rem;
    border-radius: .5rem;
    background: var(--green);
    color:#fff;
    padding: 1rem 1.5rem;
    cursor: pointer;
    display: none;}
.home{
    display: flex;
    align-items: center;
    flex-wrap: wrap;
    gap:1.5rem;
    padding-top: 10rem;}
.home .image{
    flex:1 1 45rem;}
.home .image img{
    width: 100%;
}

.home .content{
    flex:1 1 45rem;
}

.home .content h3{
    font-size: 4.5rem;
    color:var(--black);
    line-height: 1.8;
    text-shadow: var(--text-shadow);
}

.home .content p{
    font-size: 1.7rem;
    color:var(--light-color);
    line-height: 1.8;
    padding: 1rem 0;
}
.icons-container{
    display: grid;
    gap:2rem;
    grid-template-columns: repeat(auto-fit, minmax(20rem, 1fr));
    padding-top: 5rem;
    padding-bottom: 5rem;
}
.icons-container .icons{
    border:var(--border);
    box-shadow: var(--box-shadow);
    border-radius: .5rem;
    text-align: center;
    padding: 2.5rem;}
.icons-container .icons i{
    font-size: 4.5rem;
    color:var(--green);
    padding-bottom: .7rem;}
.icons-container .icons h3{
    font-size: 4.5rem;
    color:var(--black);
    padding: .5rem 0;
    text-shadow: var(--text-shadow);}
.icons-container .icons p{
    font-size: 1.7rem;
    color:var(--light-color);}
.about .row{
    display: flex;
    align-items: center;
    flex-wrap: wrap;
    gap:2rem;}
.about .row .image{
    flex:1 1 45rem;}
.about .row .image img{
    width: 100%;}
.about .row .content{
    flex:1 1 45rem;}
.about .row .content h3{
    color: var(--black);
    text-shadow: var(--text-shadow);
    font-size: 4rem;
    line-height: 1.8;}
.about .row .content p{
    color: var(--light-color);
    padding:1rem 0;
    font-size: 1.5rem;
    line-height: 1.8;}
.services .box-container{
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(27rem, 1fr));
    gap:2rem;}
.services .box-container .box{
    background:#fff;
    border-radius: .5rem;
    box-shadow: var(--box-shadow);
    border:var(--border);
    padding: 2.5rem;}
.services .box-container .box i{
    color: var(--green);
    font-size: 5rem;
    padding-bottom: .5rem;}
.services .box-container .box h3{
    color: var(--black);
    font-size: 2.5rem;
    padding:1rem 0;
}

.services .box-container .box p{
    color: var(--light-color);
    font-size: 1.4rem;
    line-height: 2;
}
.doctors .box-container{
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(30rem, 1fr));
    gap:2rem;
}
.doctors .box-container .box{
    text-align: center;
    background:#fff;
    border-radius: .5rem;
    border:var(--border);
    box-shadow: var(--box-shadow);
    padding:2rem;
}
.doctors .box-container .box img{
    height: 20rem;
    border:var(--border);
    border-radius: .5rem;
    margin-top: 1rem;
    margin-bottom: 1rem;
}

.doctors .box-container .box h3{
    color:var(--black);
    font-size: 2.5rem;
}
.doctors .box-container .box span{
    color:var(--green);
    font-size: 1.5rem;
}
.doctors .box-container .box .share{
    padding-top: 2rem;
}
.doctors .box-container .box .share a{
    height: 5rem;
    width: 5rem;
    line-height: 4.5rem;
    font-size: 2rem;
    color:var(--green);
    border-radius: .5rem;
    border:var(--border);
    margin:.3rem;
}
.doctors .box-container .box .share a:hover{
    background:var(--green);
    color:#fff;
    box-shadow: var(--box-shadow);
}
.appointment .row{
    display: flex;
    align-items: center;
    flex-wrap: wrap;
    gap:2rem;
}
 
.appointment .row .image{
    flex:1 1 45rem;
}

.appointment .row .image img{
    width: 100%;
}

.appointment .row form{
    flex:1 1 45rem;
    background: #fff;
    border:var(--border);
    box-shadow: var(--box-shadow);
    text-align: center;
    padding: 2rem;
    border-radius: .5rem;
}
.appointment .row form .message{
    margin-bottom: 2rem;
    border-radius: .5rem;
    padding: 1.5rem 1rem;
    font-size: 1.7rem;
    text-align: center;

}
.appointment .row form h3{
    color:var(--black);
    padding-bottom: 1rem;
    font-size: 3rem;
}

.appointment .row form .box{
    width: 100%;
    margin:.7rem 0;
    border-radius: .5rem;
    border:var(--border);
    font-size: 1.6rem;
    color: var(--black);
    text-transform: none;
    padding: 1rem;
}

.appointment .row form .btn{
    padding:1rem 4rem;
}

.review .box-container{
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(27rem, 1fr));
    gap:2rem;
}

.review .box-container .box{
    border:var(--border);
    box-shadow: var(--box-shadow);
    border-radius: .5rem;
    padding:2.5rem;
    background: #fff;
    text-align: center;
    position: relative;
    overflow: hidden;
    z-index: 0;
}

.review .box-container .box img{
    height: 10rem;
    width: 10rem;
    border-radius: 50%;
    object-fit: cover;
    border:.5rem solid #fff;
}

.review .box-container .box h3{
    color:#fff;
    font-size: 2.2rem;
    padding:.5rem 0;
}

.review .box-container .box .stars i{
    color:#fff;
    font-size: 1.5rem;
}

.review .box-container .box .text{
    color:var(--light-color);
    line-height: 1.8;
    font-size: 1.6rem;
    padding-top: 4rem;
}

.review .box-container .box::before{
    content: '';
    position: absolute;
    top:-4rem; left: 50%;
    transform:translateX(-50%);
    background:var(--green);
    border-bottom-left-radius: 50%;
    border-bottom-right-radius: 50%;
    height: 25rem;
    width: 120%;
    z-index: -1;
}

.blogs .box-container{
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(30rem, 1fr));
    gap:2rem;
}

.blogs .box-container .box{
    border:var(--border);
    box-shadow: var(--box-shadow);
    border-radius: .5rem;
    padding: 2rem;
}

.blogs .box-container .box .image{
    height: 20rem;
    overflow:hidden;
    border-radius: .5rem;
}

.blogs .box-container .box .image img{
    height: 100%;
    width: 100%;
    object-fit: cover;
}

.blogs .box-container .box:hover .image img{
    transform:scale(1.2);
}

.blogs .box-container .box .content{
    padding-top: 1rem;
}

.blogs .box-container .box .content .icon{
    padding: 1rem 0;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.blogs .box-container .box .content .icon a{
    font-size: 1.4rem;
    color: var(--light-color);
}

.blogs .box-container .box .content .icon a:hover{
    color:var(--green);
}

.blogs .box-container .box .content .icon a i{
    padding-right: .5rem;
    color: var(--green);
}

.blogs .box-container .box .content h3{
    color:var(--black);
    font-size: 3rem;
}

.blogs .box-container .box .content p{
    color:var(--light-color);
    font-size: 1.5rem;
    line-height: 1.8;
    padding:1rem 0;
}

.footer .box-container{
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(22rem, 1fr));
    gap:2rem;
}

.footer .box-container .box h3{
    font-size: 2.5rem;
    color:var(--black);
    padding: 1rem 0;
}

.footer .box-container .box a{
    display: block;
    font-size: 1.5rem;
    color:var(--light-color);
    padding: 1rem 0;
}

.footer .box-container .box a i{
    padding-right: .5rem;
    color:var(--green);
}

.footer .box-container .box a:hover i{
    padding-right:2rem;
}

.footer .credit{
    padding: 1rem;
    padding-top: 2rem;
    margin-top: 2rem;
    text-align: center;
    font-size: 2rem;
    color:var(--light-color);
    border-top: .1rem solid rgba(0, 0, 0, .1);
}

.footer .credit span{
    color:var(--green);
}

/* media queries  */
@media (max-width:991px){

    html{
        font-size: 55%;
    }

    .header{
        padding: 2rem;
    }

    section{
        padding:2rem;
    }

}
@media (max-width:768px){
    #menu-btn{
        display: initial;
    }
    .header .navbar{
        position: absolute;
        top:115%; right: 2rem;
        border-radius: .5rem;
        box-shadow: var(--box-shadow);
        width: 30rem;
        border: var(--border);
        background: #fff;
        transform: scale(0);
        opacity: 0;
        transform-origin: top right;
        transition: none;
    }

    .header .navbar.active{
        transform: scale(1);
        opacity: 1;
        transition: .2s ease-out; }
    .header .navbar a{
        font-size: 2rem;
        display: block;
        margin:2.5rem;
    }}
@media (max-width:450px){
    html{
        font-size: 50%;
    }

}