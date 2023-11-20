# Marketing-websitee
<html>
<head>
    <title>Marketing Website</title>
    <link rel="stylesheet" href="style.css">
    <style>
        body {
  font-family: Arial, sans-serif;
  background-color: #f0f0f0;
  
}
header{
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  font-size: 20px;
}
h1 {
  text-align: center;
  color: #4CAF50;
}
article{
  background-image: url(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS3U6keV8N2IeOM3xOJAb6xYJyLcKq4oYNM0g&usqp=CAU);
  background-position: right;
  background-repeat: no-repeat;
}

h2 {
  color: #2196F3;
}
p {
  margin: 10px;
}
.container {
  width: 80%;
  margin: auto;
  padding: auto;
}
.section{
  border: 1px solid #ccc;
  padding: 20px;
  margin: 20px;
}


.image {
  width: 500px;
  height: 250px;
}
.button {
  display: inline-block;
  background-color: #4CAF50;
  color: white;
  padding: 10px 20px;
  text-decoration: none;
}
.button:hover {
  background-color: #2196F3;
}
.nav {
  display: flex;
  justify-content: space-around;
  align-items: right;
  background-color: #2196F3;
  color: white;
  font-size: 20px;
}
.nav a {
  text-decoration: none;
  color: white;
  font-weight: bold;
}
.nav a:hover {
  color: #4CAF50;
}
.footer {

  background-color: #2196F3;
  color: white;
  padding: 10px;
}
.our-pricing{
  padding: 6rem 7%;
  background: #a69efaa4;
  
}
.our-pricing h1{
  color: white;
  font-size: 40px;
  text-align: center;
  margin-bottom: 25px;
}
.main-price{
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
  gap: 100px;
}
.inner-price{
flex: 1 1 300px;
padding: 5rem 1rem;
background: white;
text-align: center;
border-radius: 15px;
}

.inner-price:hover{
  box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
}

.inner-price h2{
  font-size: 30px;
  color: black;
  margin-bottom: 25px;
}
.inner-price p{
font-size: 1.5rem;
margin-bottom: 25px;
padding: 0 2rem ;
}

.inner-price a{
  background: var(--mainclr);
  font-size: 1.5rem;
  color: white;
  padding: 1.5rem 3rem;

}
.img {
    align-items: center;
}

.inner-price a:hover{
  background: var(--headerclr);
  border-radius: 15px;
}

.header.active{
  background: var(--headerclr);
  transition: all .9s ease-in-out;
}

@media (max-width:767px) {
  html{
      font-size: 55%;
  }
  .navbar{
      position: absolute;
      top: 100%;
      left: -300%;
      right: 0;
      width: 30rem;
      height: 100vh;
      background: var(--headerclr);
  }
.navbar a{
  display: block;
  margin: 1rem;
  padding: 1rem;
  color: white;
  font-size: 1.5rem;
}
.icons div{

  display: initial;
}

.main-home .right-home{
  width: 100%;
  margin-top: 0;
}
.main-home .right-home img{
  width: 100%;
  margin-top: -100px;
}
.main-home .left-home{
  width: 100%;
  margin-top: -100px;
}

.home{
  background: none;
}
.who{
  margin-top: 200px;
}
.inner-who-content{
  margin-top: 20px;
}
.who h1{
  margin-bottom: 15px;
}

}


    </style>
    
</head>
<body>
    <header>
    <h1 id="home">Marketing Website</h1>
    </header>
    <div class="container">
        <div class="nav">
            <a href="#home">Home</a>
            <a href="#products">Products</a>
            <a href="#support">Support</a>
            <a href="#contact">Contact Us</a>
        </div>
        <article>
        <div class="section">
            <h2>Welcome to our website!</h2>

        
            <p>We are a company that offers amazing products and services for your needs. <br>Whether you are looking for something fun, practical, or innovative, we have it all. <br>Browse our website and discover what we can do for you.</p>
    
        </div>
    </article>
        
        <div class="section">
            <h2 id="products">Our Products</h2>
            <p>We have a variety of products that suit different tastes and preferences. Here are some of our best-selling products:</p>
            <ul>
        
<div class="our-pricing">
    <h1>Our Products</h1>

    <div class="main-price">
        <div class="inner-price">
            <h2>Product A</h2>
            <p> A cool gadget that does something awesome.</p>
            <a href="#">Get now</a>
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSfIe9vLY5CaSM_5mQD1WBceojCUNJio16hSg&usqp=CAU">
        </div>

        <div class="inner-price">
            <h2>Product B</h2>
            <p> A stylish accessory that makes you look fabulous</p>
            <a href="#">Get now</a>
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR1M5gQ8wG13myYV_3EOGzH3MlqOpeaOg2XnfMl1ZI_ZYTxL-U6vXZ7ITcdMOI-CcuT5uw&usqp=CAU">
        </div>

        <div class="inner-price">
            <h2>Product C</h2>
            <p> A useful tool that solves a common problem</p>
            <a href="#">Get now</a>
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQw4t_pzRfa_ssSYInTAH0Oo3WnCUgdyUqWHw&usqp=CAU">
        </div>
    </div>
</div>

        <div class="section">
            <h2 id="support">Our Support</h2>
            <p>We care about our customers and we want to provide them with the best support possible. If you have any questions, issues, or feedback, please feel free to contact us. We are always happy to help you.</p>
            
            <p>You can also check out our FAQ page, where you can find answers to some of the most common questions we receive.</p>
            <p>Also drop your question below</p>
            <form action="https://example.com/support.php" method="POST">
                <!-- form fields go here -->
                <label>Your Question</label>
                <input type="text" placeholder="Enter your Question"><br>
                <input type="submit" value="Submit">
              </form>
              
        </div>
        <div class="section">
            <h2 id="contact">Contact Us</h2>
            <p>If you want to get in touch with us, you can use any of the following methods:</p>
            <ul>
                <li>Email: marketing@example.com</li>
                <li>Phone: +91 7018842605</li>
                <li>Address: 123 Main street </li>
            </ul>
            <p>We look forward to hearing from you and serving you better.</p>
        </div>
    
        <div class="footer">
            © 2023 Marketing Website. All rights reserved.
        </div>
    </div>
      </body>
          </html>
