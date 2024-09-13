<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="portfolio.css">
</head>
<body>
    <!--navigation-->
    <nav> 
        <ul>
            <li> <a href="#">Home</a> </li>
            <li> <a href="#">Skills</a></li>
            <li> <a href="#">About me</a></li>
            <li> <a href="#">contacts</a></li>
        </ul>
            </nav>
    <!--header section-->
    <header>
        <h1> About Me</h1>
        <p> Hi am  Elijah Nyamweya,someone with a clear vision, driven by the desire to achieve more in the tech world. 
            I am ambitious, forward-thinking, and constantly striving to expand my  knowledge,
             and skills in technology.</p>
             <h2>Programming languages</h2>
             <p>These are some of the programming languages that am proficient in 
                <ul>
                    <li> Java- front end and backend web development</li>
                    <li>Python-data analysis,machine learning</li>
                    <li>HTML/CSS-website development and layout</li>
                    <li>SQL-managing databases</li>
                </ul>
             </p>

    </header>

    <!--main layout-->
    <section>
    <div class="main-content">
        <h1> Educational Background</h1>
        <p> I hold a degree in Molecular Biology and Forensic Technology from the Technical University of Mombasa,
             where I developed a strong foundation in scientific research, data analysis, and biotechnology. 
             My academic journey has equipped me with the critical thinking and problem-solving skills needed to excel in ,
             both biological sciences and forensic investigations.
             I am now leveraging this expertise to explore innovative solutions in the tech world,
            blending my background in science with cutting-edge technology.</p>
        <p> For more details you can download my cv here </p>
        <a href="#">my cv details</a>

    </div>
    <div class="main-content"> 
        <h1> My Interests</h1>
        <p>I am deeply passionate about technology and its transformative potential to solve complex problems and drive innovation. 
            With a strong background in molecular biology and forensic technology, I enjoy exploring the intersection of science and tech,
             particularly in areas such as telemedicine and software development </p>
    </div>
    <div class="main-content">
        <h1> My Projects</h1>
       <p>
       <p> 1. Telemedicine Platform<a href="#"> QwikMed</a>
        A comprehensive platform designed to connect patients with healthcare professionals, 
        through secure video consultations and real-time messaging.QwikMed aims to improve healthcare accessibility,
         especially in underserved regions.</p>
         <p>2. Mobile Money Transfer app<a href="#">Mcash</a>
         That streamlines money transfer services, enabling users to send and receive money securely. 
         With an intuitive interface, the app supports multiple currencies, 
         has built-in fraud detection mechanisms, and offers real-time transaction tracking.</p>
         <p>3. E-commerce solution<a href="#">Almacenar</a>
         My e-commerce project focuses on building a dynamic online store that caters to a wide range of consumer needs.
         The platform integrates payment gateways, user-friendly navigation, and personalized product recommendations,
          ensuring an optimal shopping experience for users. It's scalable, secure, and adaptable to various business models.</p>

        </p>

    </div>

        

    </section>
    <!--footer-->
    <footer>
        <h2> Reach Out Via Contact Form Below</h2>
        <form a href="#" class="toggle-button" onclick="toggleForm(show)">Contact Form</form> 
            
            <div class="contact-form 1">
                <h2>Contact Me</h2>
                <form action="contact" method="post">
                    <label for="name"> Name</label>
                    <input type="text" id="name" name="name" >
        
                    <label for="email">Email</label>
                    <input type="email" id="email" name="email">
        
                    <label for="message">Message</label>
                    <textarea id="message" name="message" rows="1"></textarea>
        
                    <button type="submit">Send Message</button>
                </div>
        </form>
        <br>
        <p> phone: <a href="tel">+254 748937165</a></p>
        
        <p>Email: <a href="mailto">ljhongeri04@gmail.com</a></p>
        
        <p>&copy; 2024 Your Website. All rights reserved.</p>
        
    </footer>
</body>
</html>
