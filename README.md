# portfolio
<!DOCTYPE html>
<html lang="en">
    <head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Welcome to Dhanashree's Portfolio</title>
    <style>
        body {
    font-family: 'Times New Roman', Times, serif;
    font-size:larger;
    list-style-image:initial;
    height: 500px;
    margin: 2;
    padding: 20px;
    background-image:-webkit-image-set("lavendarbg.jpg");
    color: black;
    text-align:center;

}

.container {
    width: 85%;
    margin:auto;
}

/* Header Styles */
header {
    color:whitesmoke;
    font-family: 'Times New Roman', Times, serif, Impact, 'Arial Narrow Bold', sans-serif;
    font-size:x-large;
    background-color:rgba(65, 5, 42, 0.815);
    padding: 5px;
    border-color: rgba(245, 243, 240, 0.959);
    background-attachment:fixed;
    border: whitesmoke double;
    box-shadow: #0a0a0a;
    text-align:center;
}

header h1 {
    margin: 1px;
    font-size: 1em;
    padding-inline-start: 10px;
}

header nav {
    margin-top: 10px;
}

header nav ul {
    padding: 0;
    list-style:none;
}

header nav ul li {
    text-decoration:dashed;
    display:inline;
    margin: 0 10px;
}
header nav ul li a {
   
    color:wheat;
    text-decoration: underline;
}
header nav ul li a:hover {
   text-decoration:underline;
}
/* Section Styles */
section {
    padding: 20px;
    background:whitesmoke;
    color: black;
    margin-bottom: 10px;
    border: dotted;
    border-radius: 10px;
    box-shadow: 10px 15px 20px 10px rgb(29, 28, 28);
    }
section h2 {
    text-align:center;
    margin-bottom: 20px;
}

section p {
    text-align: center;
}
/* Skills Styles */
#skills ul {
    list-style:circle;
    padding: 0;
    text-align: center;
}

#skills ul li {
    display: inline-block;
    background: #420352d3;
    color: #fff;
    padding: 10px 20px;
    margin: 5px;
    border-radius: 5px;
}
/* Project Styles */
.project {
    
    padding: 20px;
    margin-bottom: 20px;
}

/* Form Styles */
form {
    display: flex;
    flex-direction: column;
    align-items: center;
}

form label {
    margin: 5px 0;
}

form input, form textarea {
    padding: 10px;
    margin-bottom: 10px;
    border: 1px solid #0c0c0c;
    width: 100%;
    max-width: 600px;
    border-radius: 5px;
}

form input[type="submit"] {
    background: #37013b;
    color: #fff;
    border: 10px;;
    cursor:pointer;
    padding: 10px 20px;
    border-radius: 5px;
}
form input[type="submit"]:hover {
    box-decoration-break:clone;
    background: #070707;
}

/* Footer Styles */
footer {
    background:rgba(43, 2, 51, 0.377);
    color: whitesmoke;
    text-align: center;
    padding: 10px 0;
    margin-top: 10px;
    }

    </style>
    <link rel="stylesheet" href="webpage.html"></link>
</head>
<body style=" height: 600px;">
   
  <header>
   
    <div class="container">
        <h1>DHANASHREE KORDE</h1>
        <p>|Full Stack Web Developer|</p>
        <nav>
            <ul>
                <li><a href="About.html">About</a></li>
                <li><a href="Skills.html">Skills</a></li>
                <li><a href="Project.html">Projects</a></li>
                <li><a href="Contact.html">Contact</a></li>
            </ul>
        </nav>
    </div>
    <img src="profile.jpg" style="height: 390px;">
  </header>  
  <section id="about" class="container">
    <h2>About Me</h2>
    <p>Hello, Myself Dhanashree korde. I am 22 years old.
        I had recently completed my graduation in bachelor's of commerce degree from  KSD Model college 
        in year 2023 with 8.00 CGPI. 
        I live in kalyan.Currently I am persuing Full Stack Web Developer course from ITVedant Institue.
        My strength is that I am a keen learner and can complete my task on time.</p>
      <p>Talking about my hobbies I like painting and playing badminton.
         Also in free time I do surfing on interet to learn new things 
         as I believe gaining more knowledge as much as you can and keeping oneself updated makes us a better person in life.</p>
 </section>
 <section id="skills" class="container">
    <h2>Skills</h2>
    <ul>
        <li>MySQL</li>
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
    </ul>
     </section>
     <section id="projects" class="container">
        <h2>Projects</h2>
        <div class="project">
            <h3>| WEB DESIGNING |</h3>
            <p>In this project I have created a webpage named ITVedant Web Designing using HTML CSS. 
                The page consists of basic information about me.
                Further, I have accessed few tutorial links which directs you to the learning websites where you can easily practice or learn
                Webdesigning and java codes free of cost. Learning becomes fun and easy through those Learning Resources. 
                Last but not least I have also mentioned my contact details for example my LinkedIn profile where 
                by just clicking on the LinkedIn icon it helps the viewers to reach my LinkedIn profile page.
            </p>
         </div>
    </section>
    <section id="contact" class="container">
        <h2>Contact</h2>
        <form action="submit_form.php" method="post">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name">
            <label for="email">Email:</label>
            <input type="email" id="email" name="email">
            <label for="message">Message:</label>
            <textarea id="message" name="message"></textarea>
            <input type="submit" value="Send Message">

        </form>
    </section>
    <footer>
        <div class="container">
            <p> &#169copy ; 2024 Dhanashree korde. All rights reserved.</p>
        </div>
    </footer>


</body>
</html>
