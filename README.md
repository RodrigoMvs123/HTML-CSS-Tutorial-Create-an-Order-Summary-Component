# HTML-CSS-Tutorial-Create-an-Order-Summary-Component

https://www.youtube.com/watch?v=SR5GxoFhIAU
https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj

https://raw.githubusercontent.com/RodrigoMvs123/HTML-CSS-Tutorial-Create-an-Order-Summary-Component/main/README.md

https://github.com/RodrigoMvs123/HTML-CSS-Tutorial-Create-an-Order-Summary-Component/blame/main/README.md


index.html 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Order Summary Component</title>  
    <link rel= "stylesheet" href="styles.css">
</head>

<body>
 <div class="Card">
     <img class="hero-image" src="Images/illustration-hero.svg" alt="Hero Image">
     <div>class="container">
     <h2 class="title">Order Summary</h2>
     <p class="order_description">You can now listen to millions of songs, audiobooks, and podcasts on any device anywhere you like!  </p>
     <div class="plan-container">
         <img src="images/Illustration-hero.svg" alt="icon-music">
         <div class="plan-description">
             <strong>Annual plan</strong>
             <P>$59.99/year</P>
         </div>
         <a href="#">Change</a>
     </div>
     <button class="proceed-button">Proceed to payment</button>
      <button class="cancel button">Cancel order</button>
      </div>  
    </div>
</body>
</html>


Styles.css

@import url("https//fonts.googleapis.com/css2?family=Red+Hat+Display:wght@500;700;900&display=swap");

:root {
--pale-blue: hsl(225, 100%, 94%);
--bright-blue: hsl(245, 75%, 52%);
--very-pale-blue: hsl(225, 100%, 98%);
--desaturated-blue: hsl(224, 23%, 55%);
--dark-blue: hsl(223, 47%, 23%);
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    background-image: url(.\images\pattern-background-desktop.svg);
    background-repeat: no repeat;
    background-size: cover;
    background-color var(--pale-blue); 
    font-family: "Red Hat Display", sans-serif;
    font-size: 16px;
}


.card {
    width:450px;
    background-color: white;
    color: var(--desaturated-blue);
    border-radius: 20px;
    overflow: hidden;
    margin: 50px auto;

}

.title{
    color: var(--dark-blue);
    font-weight: 900;
    font-size: 32px;
}

.hero-image {
    width: 100%;    
}

.container {
    padding: 30px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    text-align: center;
    font-size: 18px;    
}

.container > * {
    margin: 13px 0;
}

.order-description{
    line-height: 25px;
}

.plan-container {
    font-size: 16px;
    background-color: var(--very-pale-blue);
    padding: 25px;
    border-radius: 12px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
}

.plan-container a {
    color: var(--bright-blue);
    font-size: 13px;
    font-weight: 700;
}

.plan-container a:hover {
    opacity: 0.8;
    text-decoration: none;
}

.plan-container strong {
    color: var(--dark-blue);
}

.plan-description {
    line-height: 20px;
    margin-right: 75px;
}

button {
    width: 100%;
    border: nome;
    font-weight: 700;
    font-size: 0.9rem;
    border-radius: 12px;
    cursor: pointer;
}

.proceed-button {
    background-color: var(--bright-blue);
    padding: 1rem 0;
    color: white;
    box-shadow: 0 20px 30px -8px rgb(197, 189, 245);
}

.proceed-button: hover{
    opacity: 0.8;

}

.cancel-button {
   background-color: white;
   color: var(--desaturated-blue);
   margin-top: 22px;
}

.cancel-button: hover {
    color: black;
}


Illustration-hero.svg
https://res.cloudinary.com/dz209s6jk/image/upload/q_auto:good,w_900/Challenges/gh4wbxnbnf9wqezb0b6y.jpg

https://cdn-icons-png.flaticon.com/512/282/282151.png

