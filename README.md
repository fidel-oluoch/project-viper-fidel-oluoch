<!DOCTYPE html>
<html lang="en">
 <head>
   <meta charset="UTF-8">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>viper cab company</title>
   <style>
    /* General Styles */
    body {
      font-family: 'Arial', sans-serif;
      margin: auto;
      color: white;
      line-height: 1.6;
      background-color: #080808;
    }

    header {
      background: linear-gradient(to right,  #090a0a,  #070707, #3c4146, #18f8ed, #09fcdc,#484d52, #070707,  #090a0a );
      color: whitesmoke;
      padding: 1rem 0;
      display: flex;
      align-items: center;
      justify-content: space-between;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    header .logo {
      font-size: 1.5rem;
      font-weight: bold;
      margin-left: 1rem;
      font-family: ESP;
    }

    header nav ul {
      list-style: none;
      display: flex;
      gap: 1.5rem;
      margin: 0;
    }

    header nav ul li a {
      text-decoration: none;
      color: white;
      font-weight: bold;
      transition: color 0.3s;
    }

    header nav ul li a:hover {
      color: #0c0c0c;
    }

    header .buttons {
      display: flex;
      gap: 1rem;
      margin-right: 1rem;
    }

    header .buttons button {
      background: rgb(8, 8, 8);
      color: #00f7ff;
      border: 1px solid rgb(25, 248, 248);
      padding: 0.5rem 1rem;
      border-radius: 5px;
      cursor: pointer;
      transition: all 0.3s;
    }

    header .buttons button:hover {
      background: #11fcfc;
      color: black;
      border: 1px solid black;
    }

    /* Hero Section */
    
    .hero {
      text-align:left;
      padding: 4rem 1rem;
      background: #0d0d0e;
      background-image: linear-gradient(to right,  #090a0a,  #18f8ed);
    }

    .hero h2 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
      color: #eaeaea;
    }

    .hero p {
      font-size: 1.2rem;
      margin-bottom: 2rem;
    }

    .rtr{
      text-align:left;
      display: grid;
      grid-template-rows : 1fr 1fr;
      justify-content: space-around;
      padding: auto;
    }

    .search-bar input, .search-bar button {
      padding: 0.8rem;
      margin: 0.5rem;
      border-radius: 5px;
      border: 1px solid #ddd;
    }

    .search-bar button {
      background: #0d0d0e;
      color: rgb(33, 222, 247);
      border: none;
      cursor: pointer;
      transition: background 0.3s;
    }

    .search-bar button:hover {
      background: #0edeec;
      color: rgb(12, 12, 12);
    }

    

    .image-0{
      max-width: 1px;
      border-radius: 2px;
      align-items: flex-end;
      display: grid;
      grid-template-columns: 1fr;
      flex-flow: column-reverse;
    }

    @media(max-width:600px) {
      
    }

    .abd-content{
      display: flex;
      flex-direction: row;
      justify-content:space-around;
      padding: 0.5cm;
      background-color: #070707;
      font-size:small;
      max-width:auto;
      height: 2cm;
    }

    /* Sections */
    section {
      padding: 2rem 1rem;
    }

    h2 {
      text-align: center;
      margin-bottom: 1rem;
    }

    /* Cards Section */
    .twist{
      color:  #18f8ed;
      font-family: ESP;
    }
    .cards {
      display: flex;
      gap: 15px;
      flex-wrap: wrap;
      flex-flow: row;
      justify-content: center;
      margin: 2rem 0;
    }

    .card {
      background:black;
      border: 1px solid black;
      border-radius: 5px;
      text-align: center;
      padding: 1rem;
      width: 200px;
      box-shadow: 0 4px 6px rgba(39, 221, 228, 0.685);
      transition: transform 0.3s, box-shadow 0.3s;
      color: #23e0ee;
    }

    .card:hover {
      transform: translateY(-10px);
      box-shadow: 0 6px 12px rgba(53, 238, 238, 0.918);
      background: #00b3a4;
    }

    .card img {
      width: 100%;
      height: 150px;
      object-fit:contain;
      border-radius: 5px 5px 0 0;
    }

    /* FAQ Section */
    details {
      margin: 1rem 0;
      padding: 1rem;
      background: #f4f4f4;
      border: 1px solid #ddd;
      border-radius: 5px;
    }

    details summary {
      font-weight: bold;
      cursor: pointer;
    }

    /* Blog Section */
    .blog article {
      margin-bottom: 1rem;
      padding: 1rem;
      background: #f9f9f9;
      border-radius: 5px;
      border: 1px solid #ddd;
    }
   
.subscribe-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    height: 3cm;
    background-color: #f0f0f0;
    font-family: Arial, sans-serif;
    background-color: #454647;
    padding: 20px;
    border-radius: 10px;
    text-align: center;
    width: 15cm;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.subscribe-container h2 {
    color: white;
    margin-bottom: 15px;
}

.subscribe-box {
    display: flex;
    align-items: center;
    background-color: white;
    border-radius: 50px;
    padding: 5px;
    overflow: hidden;
}

.subscribe-box input {
    border: none;
    padding: 10px;
    flex: 1;
    font-size: 16px;
    border-radius: 50px;
    outline: none;
    align-items: center;
}

.subscribe-box button {
    background-color: #007bff;
    border: none;
    color: white;
    padding: 10px 20px;
    cursor: pointer;
    border-radius: 50%;
    font-size: 18px;
}

.subscribe-box button:hover {
    background-color: #0056b3;
}

    footer {
      text-align: center;
      padding: 1rem;
      background: #1fafd3;
      color: white;
    }

    /* card-image a */
    .containerA {
      display: flex;
      max-width: 900px;
      width: 100%;
      background:black;
      flex-wrap: wrap;
      justify-content: center;
      margin: auto;
      color: #2bf7f7;
      box-shadow: 0 4px 6px rgba(39, 221, 228, 0.685);
      flex-direction: row-reverse;
    }
    
    .textA {
      flex: 1;
      padding: 20px;
    }
    
    .text h5 {
      margin-top: 0;
    }
    
    .imageA {
      flex: 1;
      display: flex;
      justify-content: center;
      align-items: center;
    }
    
    .image img {
      max-width: 100px;
      height: 10cm;
      
    }

    .testimonials {
    max-width: 600px;
    margin: auto;
    background: rgb(20, 241, 248);
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgb(17, 247, 247);
    position: relative;
    }

    h2.ac {
    color: #333;

     }

   .highlight.ac {
     color: blue;

     }

    .review-container {
      position: relative;
      height: 220px;
      overflow: hidden;
    }

    .review {
     display: none;
     text-align: center;
     opacity: 0;
     transition: opacity 0.5s ease-in-out;
    }

    .review.active {
      display: block;
      opacity: 1;
    }

    .review img {
     width: 50px;
     height: 50px;
     border-radius: 50%;
     margin-bottom: 10px;
    }

    .stars {
     color: gold;
     font-size: 20px;
    }

    button.ac {
     background-color: #007bff;
     color: white;
     border: none;
     padding: 10px;
     cursor: pointer;
     border-radius: 5px;
     position: absolute;
     top: 50%;
     transform: translateY(-50%);
     font-size: 18px;
     transition: 0.3s;
    }

    button:hover.ac {
     background-color: #0056b3;
    }

    .prev {
     left: 10px;
    }

    .next {
     right: 10px;
    }

    /* card-image c */
    .containerC {
      display: flex;
      max-width: 900px;
      width: 100%;
      background:black;
      overflow: hidden;
      flex-wrap: wrap;
      justify-content: center;
      margin: auto;
      color: #1ff8f8;
      box-shadow: 0 4px 6px rgba(31, 241, 248, 0.685);
    }
    
    .textC {
      flex: 1;
      padding: 20px;
    }
    
    .text h1 {
      margin-top: 0;
    }
    
    .imageC {
      flex: 1;
      display: flex;
      justify-content: center;
      align-items: center;
      
    }
    
    .image img {
      max-width: 150px;
      height: auto;
      
    }

    .footer {
      background-color: #00f7ff;
      color: white;
      padding: 5px 0;
      display:grid;
      grid-template-columns: 1fr 1fr 1fr;
      justify-content:space-between;
      inset-block: 3px;
    }

    .social-icons img{
      width: 20px;
      height: 20px;
    }

    .useful-links ul{
      list-style: none;
      padding: 0;
      color: white;
      text-decoration: none;
      font-size: 14px;
    }

    .map image {
      width: 5cm;;
      max-width: 900px;
      border-radius: 5cm;
    }

    .footerbotom {
      margin-top: 20px;
      border-top: #070707;
      width: 100%;
      align-items: baseline;
    }
   
    /* Responsive Design Improvements */
    @media (max-width: 1024px) {
        header {
            flex-direction: column;
            text-align: center;
        }
        header nav ul {
            flex-direction: column;
            gap: 0.5rem;
        }
        .hero {
            text-align: center;
            padding: 3rem 1rem;
        }
        .cards {
            flex-direction: column;
            align-items: center;
        }
        .containerA, .containerC {
            flex-direction: column;
            text-align: center;
        }
    }

    @media (max-width: 768px) {
        header nav ul {
            display: none; /* Hide menu on small screens */
        }
        .menu-toggle {
            display: block;
            cursor: pointer;
            font-size: 1.5rem;
            padding: 10px;
            color: white;
        }
        .hero h2 {
            font-size: 2rem;
        }
        .hero p {
            font-size: 1rem;
        }
        .cards {
            flex-wrap: wrap;
        }
    }

    @media (max-width: 480px) {
        .hero h2 {
            font-size: 1.5rem;
        }
        .hero p {
            font-size: 0.9rem;
        }
        .card {
            width: 90%;
        }
        .containerA, .containerC {
            padding: 1rem;
        }
        .footer {
            grid-template-columns: 1fr;
            text-align: center;
        }
    }
    </style>
    
 </head>
 <body>
     <header>
       <div class="logo">viper</div>
       <nav>
         <ul>
           <li><a href="#home">Home</a></li>
           <li><a href="#about">About</a></li>
           <li><a href="#Our services">Services</a></li>
           <li><a href="#faq">FAQ</a></li>
           <li><a href="#contact">Contact</a></li>
         </ul>
       </nav>
       <div class="buttons">
         <button id="login-btn">Log In</button>
         <button id="signup-btn">Sign Up</button>
       </div>
      </header>
       <main>
         <section class="hero" id="home">
           <div class="rtr">
             <h2>Moving The World,One Journey at a Time</h2>
             <p>Discover healthcare services tailored to your needs. Find doctors, book tests, and access your medical history—all in one place.</p>
           </div>
           <div class="search-bar">
             <input type="text" placeholder="Location" aria-label="Location">
             <input type="text" placeholder="Drivers name’s Name" aria-label="Driver’s Name">
             <button>Search</button>
           </div>
           <div class="image-0">
             <img src="c:\Users\OLUOCH\Pictures\driver-with-ai-generated-free-png.webp" alt="">
           </div>
           <div class="abd-content">
             <div class="adb1">
               <h4>Over 5000</h4>
               <p>drivers</p>
             </div>
             <div class="adb2">
               <h4>24/7</h4>
               <p>functional</p>
             </div>
             <div class="adb3">
               <h4>services offered</h4>
               <p>World-wide</p>
           </div>
         </section>
         <section class="services" id="about">
           <div class="twist">
             <h2>Our services</h2>
           </div>
           <div class="cards">
           <div class="card">
             <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTTOiByf4cl_WIui1jdpbZSKCtKdDm9Us_ -3A&s" alt="car">
             <h3>Mini-Viper</h3>
             <p>Atranspot motor that can only accomodate a maximum of it only accomodates 3 persengers per trip.</p>
           </div>
           <div class="card">
             <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQNzV7TBRG59mRxV40oNswzdvi5KBjSbzX3_Q&s" alt="luxary car">
             <h3>Classy-viper</h3>
             <p>With classy-viper,red-carpet apearence is assured in style and bomberdment, it only accomodates 1 persengers per trip.</p>
           </div>
           <div class="card">
             <img src="data:image/jpeg;base64,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" alt="Heart and Lung Care">
             <h3>Large-Viper</h3>
             <p>With larg-viper,both luxary and space is assured,it only accomodates 7 persengers per trip.</p>
           </div>
           <div class="card">
             <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS3XoFhfJncKbT75elb-gnBuVn5nyuN3YqStRetpUUrx8FFryFUI1ZJ48w_SwxyDA_iCe8&usqp=CAU" alt="lorry">
             <h3>mover-viper</h3>
             <p>mover-viper offers moving services coutry wide.it only accomodates 2 persengers(with lougage) per trip.</p>
           </div> 
         </section>
         <section class="Cards">
           <div class="containerA">
             <div class="textA">
               <h4>Why viper</h4>
               <h5>1. Strong Reputation & History</h5>
               <h5>2. Safety & Security</h5>
               <h5>3.The best cub companies prioritize the safety of children, with well-trained staff, clear safety protocols, and proper insurance.</h5>
               <h5>4. Qualified & Experienced Instructors</h5>
               <h5>5.A company with experienced, background-checked instructors ensures that children receive quality guidance and mentorship.</h5>
               <h5>6. Engaging & Educational Programs</h5>
               <h5>7. Affordable Pricing & Value for Money</h5>
               </p>
             </div>
             <div class="imageA">
               <img src="https://cdn.leonardo.ai/users/8e89f2a3-b9cf-4f06-ac44-370f713abeaf/generations/7f8eaa94-5203-4ae6-997c-d2c15405858e/segments/1:4:1/Flux_Dev_Create_an_image_of_a_confident_darkskinned_male_cab_d_0.jpeg?w=512" alt="Placeholder Image">
             </div>
           </div> 
           <div class="containerB">
             <section class="testimonials">
               <h2>What <span class="highlight">Our Members</span> Are Saying About Us</h2>
               <div class="review-container">
                 <div class="review active">
                   <img src="c:\Users\OLUOCH\Pictures\d3d1b039-0487-480e-b2e5-b955a6e57b9d.jpg" alt="User Image">
                   <h3>Jane Cooper</h3>
                   <p class="date">12/4/27</p>
                   <p class="comment">i love the services offered by viper.</p>
                 <div class="stars">★★★★★</div>
               </div>
               <div class="review">
                 <img src="c:\Users\OLUOCH\Pictures\b2617a9e-d28f-4d8d-a2b3-43fe9659b7cc.jpg" alt="User Image">
                 <h3>John Doe</h3>
                 <p class="date">23/5/27</p>
                 <p class="comment">Amazing service! Highly recommended.</p>
                 <div class="stars">★★★★</div>
               </div>
               <div class="review">
                 <img src="c:\New folder\New folder\New folder\New folder\New folder\b.jpg" alt="User Image">
                 <h3>John Doe</h3>
                 <p class="date">23/5/27</p>
                 <p class="comment">Amazing service! Highly recommended.</p>
                 <div class="stars">★★★★</div>
               </div>
               <div class="review">
                 <img src="c:\New folder\New folder\New folder\New folder\New folder\download (1).jpg" alt="User Image">
                 <h3>John Doe</h3>
                 <p class="date">23/5/27</p>
                 <p class="comment">Amazing service! Highly recommended.</p>
                 <div class="stars">★★★★</div>
               </div>
               <div class="review">
                 <img src="c:\New folder\New folder\New folder\New folder\New folder\download.jpg" alt="User Image">
                 <h3>John Doe</h3>
                 <p class="date">23/5/27</p>
                 <p class="comment">Amazing service! Highly recommended.</p>
                 <div class="stars">★★★★</div>
               </div>
               <div class="review">
                 <img src="c:\New folder\New folder\New folder\New folder\New folder\5t.jpg" alt="User Image">
                 <h3>John Doe</h3>
                 <p class="date">23/5/27</p>
                 <p class="comment">Amazing service! Highly recommended.</p>
                 <div class="stars">★★★★</div>
               </div>
               <div class="review">
                 <img src="c:\New folder\New folder\New folder\New folder\New folder\5.jpg" alt="User Image">
                 <h3>John Doe</h3>
                 <p class="date">23/5/27</p>
                 <p class="comment">Amazing service! Highly recommended.</p>
                 <div class="stars">★★★★</div>
               </div>
               <div class="review">
                 <img src="c:\New folder\New folder\New folder\New folder\New folder\i.png" alt="User Image">
                 <h3>John Doe</h3>
                 <p class="date">23/5/27</p>
                 <p class="comment">Amazing service! Highly recommended.</p>
                 <div class="stars">★★★★</div>
               </div>
               <div class="review">
                 <img src="c:\New folder\New folder\New folder\New folder\New folder\k.jpg" alt="User Image">
                 <h3>Sarah Smith</h3>
                 <p class="date">18/3/27</p>
                 <p class="comment">Great experience, will use again.</p>
                 <div class="stars">★★★★★</div>
               </div>
                 <div class="dots-container">
                 <span class="dot active" onclick="goToReview(0)"></span>
                 <span class="dot" onclick="goToReview(1)"></span>
                 <span class="dot" onclick="goToReview(2)"></span>
               </div>
             </section>
           </div>
           <div class="containerC">
             <div class="textC">
               <h1>Our future plans</h1>
               <p> Invest in new, fuel-efficient, and electric vehicles to offer eco-friendly and cost-effective transportation options.Develop a user-friendly mobile app and website with real-time tracking, automated booking, and secure payment options for convenience.Implement AI-driven safety monitoring, regular vehicle maintenance, and driver training programs to ensure passenger and cargo safety.Expand into new transportation sectors such as logistics, last-mile delivery, ride-sharing, or luxury transport services.Introduce membership plans, discounts, and rewards for frequent customers to build long-term customer relationships.</p>
             </div>
             <div class="imageC">
               <img src="c:\Users\OLUOCH\Pictures\2a5a4ef0-e281-49da-a9df-94a3e4950493.jpg" alt="Placeholder Image">
             </div>
           </div>
         </section>
         <div class="subscribe-container">
    <h2>Subscribe To Our Newsletter</h2>
    <div class="subscribe-box">
        <input type="email" id="email" placeholder="Enter your email">
        <button onclick="subscribe()">
            ➝
         </button>
       </div>
   </div>
       </main>
   <footer class="footer">
      <p>viper transport company</p>
      <p>viper transport company is a transportation company that is dedicated to provide their customers with top-nouch services,we are looking forward to bettering and improving the transport sector in and out of the counry.we welcome all customers to experience movement of a lifetime.</p>
      <div class="social-icons">
        <p>Follow Us</p>
        <a href="https://facebook.com" target="_blank"><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAMAAABEpIrGAAAAgVBMVEUAAAAQcP8IZf8IZ/8JZv8HZf8IZv8IZv8IaP8JZ/8HZv8IZv8FZf8YcP9FjP+TvP/g7P/////R4/9Vlf8QYP+Es/9kn/8IZv8nef8JZf8AYP/v9f/Q4v/B2P9GjP8HZv+yz//Q4/83g/8HZv/g6/+Dsv8HZf/n7//////////e6//ZLyHjAAAAK3RSTlMAEGCfz+//XyCQj98w/////////xD//6D/kBD/////7////8///5Cgz+/vONkvXQAAAPJJREFUeAF9kkUCwzAMBGVSGMrM3P//rxBaB+e6s0YREFJpw2y0cgS1cT3DQLmNWPjcwK/XA24RWIuEdg4j7OtHUX0NYedxko5+jCeZMc0En8FsVDDHSd1WDoFdIlogX46awopozWA+ythsd7s9ZxymJBkcs3wcMZC0YHDKhDNbKLowuGYC21zINIWUbQ7EwwJT7YogqgTTKaTY4tIp7HDIRadwwzVlKVyv11HG9cekFBxam8FbTInuQ4LCd3cL2Uzd+4UV/VkHfUIgMLRdQuBi7JsCxh5rQEAfrO9NYSWojruwBOOhDoR8PF+j0fuipNX+AmbCIviMIiwCAAAAAElFTkSuQmCC" alt="facebook"></a>
        <a href="https://twitter.com" target="_blank"><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAcCAAAAABXZoBIAAAA/0lEQVR4AbXPIazCMACE4d+L2qoZFEGSIGcRc/gJJB5XMzGJmK9EN0HMi+qaibkKVF1txdQe4g0YzPK5yyWXHL9TaPNQ89LojH87N1rbJcXkMF4Fk31UMrf34hm14KUeoQxGArALHTMuQD2cAWQfJXOpgTbksGr9ng8qluShJTPhyCdx63POg7rEim95ZyR68I1ggQpnCEGwyPicw6hZtPEGmnhkycqOio1zm6XuFtyw5XDXfGvuau0dXHzJp8pfBPuhIXO9ZK5ILUCdSvLYMpc6ASBtl3EaC97I4KaFaOCaBE9Zn5jUsVqR2vcTJZO1DdbGoZryVp94Ka/mQfE7f2T3df0WBhLDAAAAAElFTkSuQmCC" alt="twiter"></a> 
        <a href="https://www.instagram.com/" target="_blank"> <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAcCAMAAABF0y+mAAABWVBMVEVyHVFHcEx0Fvp8Fv1yFP1/FfyLCOyfBOmtAeS7AuDHAd3UANjZAs7rD6xyFvzjANTqAMHoA7l2F/yPFfx8GPmfD/zFF/XVWujoZuLyZt3pRt/yGdHyA8j1AKTViPj/9Pr////8g9f9A7r3DZz5vO794Pf+ruj9B6uzFPv7JLv+AJr+BI/+YMP/1vD+AIThG+n9GZn/vd3/YZz+AXP+GoT/r8r+AmT/b5z+HHH+I3f+G2P/ur7+FFD+Klb+fYv/wcr+LUf+LWX+AFn+Nzr+Ohz+RT7+inP+Si7/ztD+TxL/zbv+Wy//9fH+WgL+c1X+ZyX+PUv+Bzv+VXD+cxr/6eL+aQT+eAX+nDj+gwD+gxH+fSL+rYn+jwD+iwL+XhX/3rn/1bH9ZR/+lwP+nwH+xHH8ZC3+qAH+sAD+wAP+x1P+zGb+pl79mQn+uAD9J3T+ygD9O1n8pRL9twuaEkMNAAAAc3RSTlMBAF3G///////////GW9j//9nY/1r///////////7//////8b/////////////////////////////////////////////////////////////////////////////////xf///1v////////Y/9j/2VzGSus+GgAAAeNJREFUeAFFjEWiU0EQRc/tqu74V9wZ4TBiB6wG3wpzVoQ7zHCXeELypHH+KVchJAESaEs0IUv0Zv+7fwLgSAOk9ZFghcnfDw4AAg18cyhWCKNVob9NCZjQLWVrEGhJbJGDoCBpMwCrJTETAKBWgdeRGb4dmJW56PdI/KU1K4X15N+AFsW0+3/WVm7Pa0Pmu4Fh7HcbRIjMIhr3FItUGAH4SNZKjK32YjKpK3Iv0yUY0b8g0Vs0oK+8wbeyMBAQwVeo44R1z7XWq6rqpn5jiTmAeQO3iceg9zkYzKvc71iEmMFbqCJJ4tDcKFrLjX5D/MEdq8GpIUUgd/tgGboTgiUDPDZ44SXNpr0gWRcAgqEmEPJRNVPOxYaOth0oAHdCxWoOzslH+RCvlafYMgFUHvAIHoCjz16io80BrH/j0AAcJ9KWKkhn5sRyGjsDtr/sqyrsWNO1cW9/cDNLZgHLSzVvn+wMq9qbKKwy7TiIaKTW56pzW6Oa+N1OKEQdvvl2RyOE4DEOZurd1cHNeab27tyjOPfhFlucXP04ovF97B6jTOzdJwFLaNAff7N6c8incH1VpiSR67q2VgjzUU7JgbMTiQtFKmgAsCAuczlflmVZn7iGBFc1awB/p4tqUS3LDb8OPwBrSrZIO/KHZwAAAABJRU5ErkJggg==" alt="instagram"></a>
     </div>
     <div class="useful-links"> 
        <li><a href="#"></a>home</li>
        <li><a href="#"></a>about</li>
        <li><a href="#"></a>services</li>
        <li><a href="#">contacts</a></li>
     </div>
     <div class="contact us on">
       <p>Email: vipertransport@gmail.com</p>
       <p>Phone: +254700050050</p>
     </div>
     <div class="map image">
       <img src="data:image/webp;base64,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" alt="map of nairobi">
     </div>
     <div class="footerbotom " >
       <p>© viper tranport 2025 </p>
     </div>
   </footer>
   <script>
     // Interactive Log In and Sign Up Modals
     const loginBtn = document.getElementById("login-btn");
     const signupBtn = document.getElementById("signup-btn");
     const overlay = document.createElement("div");
     overlay.style.position = "fixed";
     overlay.style.top = 0;
     overlay.style.left = 0;
     overlay.style.width = "100%";
     overlay.style.height = "100%";
     overlay.style.background = "rgba(0, 0, 0, 0.5)";
     overlay.style.zIndex = 999;
     overlay.style.display = "none";
     document.body.appendChild(overlay);

     function createModal(title) {
      const modal = document.createElement("div");
      modal.style.position = "fixed";
      modal.style.top = "50%";
      modal.style.left = "50%";
      modal.style.transform = "translate(-50%, -50%)";
      modal.style.background = "#fff";
      modal.style.padding = "20px";
      modal.style.borderRadius = "10px";
      modal.style.boxShadow = "0 4px 8px rgba(0, 0, 0, 0.2)";
      modal.style.zIndex = 1000;

      const heading = document.createElement("h2");
      heading.textContent = title;

      const closeButton = document.createElement("button");
      closeButton.textContent = "Close";
      closeButton.style.marginTop = "10px";
      closeButton.style.background = "#007BFF";
      closeButton.style.color = "#fff";
      closeButton.style.border = "none";
      closeButton.style.padding = "10px";
      closeButton.style.borderRadius = "5px";
      closeButton.style.cursor = "pointer";

      closeButton.addEventListener("click", () => {
        modal.remove();
        overlay.style.display = "none";
      });
      let currentreview = 0;
     const review = document.querySelectorAll(".review");
     const totalReviews = reviews.length;

     // Function to show review with fade effect
     function showReview(index) {
     reviews.forEach((review, i) => {
     review.classList.remove("active");
     if (i === index) {
     review.classList.add("active");
             }
          });
     }
     // Previous Review Button
     function prevReview() {
     currentReview = (currentReview - 1 + totalReviews) % totalReviews;
     showReview(currentReview);
     }

     // Next Review Button
     function nextReview() {
     currentReview = (currentReview + 1) % totalReviews;
     showReview(currentReview);
     }

     // Auto-change reviews every 5 seconds
     setInterval(() => {
     nextReview();
     }, 5000);

     let currentReview = 0;
     const reviews = document.querySelectorAll(".review");
     const dots = document.querySelectorAll(".dot");

     // Function to show review with fade effect
     function showReview(index) {
       reviews.forEach((reviewi) => {
          review.classList.remove("active");
             dots[i].classList.remove("active");
               if (i === index) {
                  review.classList.add("active");
                     dots[i].classList.add("active");
                 }
         });

     updateStarRatings();
      }

     // Previous Review Button
     function prevReview() {
        currentReview = (currentReview - 1 + reviews.length) % reviews.length;
          showReview(currentReview);
      }

     // Next Review Button
     function nextReview() {
        currentReview = (currentReview + 1) % reviews.length;
          showReview(currentReview);
      }

     // Function to go to a specific review via dot navigation
     function goToReview(index) {
       currentReview = index;
       showReview(currentReview);
     }

     // Auto-change reviews every 5 seconds
     setInterval(() => {
       nextReview();
       }, 5000);

     // Initialize the first review
     showReview(currentReview);

     // Function to update star ratings dynamically
     function updateStarRatings() {
       reviews.forEach((review) => {
         const starsDiv = review.querySelector(".stars");
         const rating = review.getAttribute("data-rating");
          starsDiv.innerHTML = "★".repeat(rating) + "☆".repeat(5 - rating);
       });
     }

     // Initialize star ratings
     updateStarRatings();

     
     function subscribe() {
    let email = document.getElementById("email").value;
    if (email) {
        alert("Thank you for subscribing!");
        document.getElementById("email").value = "";
    } else {
        alert("Please enter a valid email address.");
    }
}
