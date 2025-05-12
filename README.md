# NextGen-Web-Solutions
<!DOCTYPE html>
<html>
    <head>
        <title>Responsive Web Design</title>
        <!--viewport meta tag-->
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <nav class="navbar">
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
        <!-- Home Section -->
    <section id="home" class="box home-section">
        <h1>Welcome to Our Website</h1>
        <p>Discover our services and explore what we have to offer. We aim to provide valuable solutions tailored to your needs.</p>
        
        <div id="more-info">
        <h2>What We Do</h2>
        <p>Our company specializes in innovative solutions that drive business growth and technological advancement.</p>

        <h3>🌐 Web Development</h3>
        <p>We create **modern, responsive websites** tailored to your business needs. Our expertise includes:</p>
        <ul>
            <li>✨ Custom websites using HTML, CSS, JavaScript, and frameworks.</li>
            <li>🔗 E-commerce solutions for seamless online transactions.</li>
            <li>📱 Mobile-friendly designs using **CSS Grid and Flexbox**.</li>
            <li>🚀 Performance optimization for fast-loading sites.</li>
        </ul>

        <h3>📊 Business Strategy & Consulting</h3>
        <p>We help businesses **strategize, innovate, and grow** by offering expert consulting in:</p>
        <ul>
            <li>📈 Market analysis & competitor insights.</li>
            <li>💡 Business planning for startups and SMEs.</li>
            <li>📊 Financial modeling & cost analysis.</li>
            <li>⚡ Scaling strategies for sustainable growth.</li>
        </ul>

        <h3>🔍 SEO & Digital Marketing</h3>
        <p>Boost your visibility with our **SEO and digital marketing strategies**, including:</p>
        <ul>
            <li>🔝 Search engine optimization (SEO) for higher rankings.</li>
            <li>📢 Social media marketing campaigns.</li>
            <li>✍️ Content writing for brand engagement.</li>
            <li>📊 Data-driven insights to improve online presence.</li>
        </ul>

        <h3>⚙️ Tech Solutions & Automation</h3>
        <p>Enhance efficiency with our **custom tech solutions**, including:</p>
        <ul>
            <li>🤖 Automation tools for streamlined workflows.</li>
            <li>💾 Database management using **SQL**.</li>
            <li>📊 AI-driven analytics for business insights.</li>
            <li>🔧 Custom software solutions tailored to your needs.</li>
        </ul>

        <p>Ready to take your business to the next level? <strong>Contact us today!</strong></p>
    </div>>
    </section>

    <!-- Main Content Sections -->
    <main class="container">
        <section id="about" class="about-section">
            <h2>About Us</h2>
            <p>We are a dedicated team committed to providing high-quality solutions. With years of experience in web development, consulting, and business strategy, our mission is to create impactful and efficient solutions tailored to your needs.</p>
        </section>
        
        <section id="services" class="services-section">
            <h2>Our Services</h2>
            <p>We offer a range of services including:</p>
            <ul>
                <li>✨ Web Development – Custom and responsive websites.</li>
                <li>📊 Business Strategy – Consulting for startups and enterprises.</li>
                <li>🔍 SEO Optimization – Enhancing visibility and performance.</li>
                <li>⚡ Tech Solutions – Providing automated tools for efficiency.</li>
            </ul>
        </section>
         </main>
        <div class="div-container">
            <h1>Welcome to Responsive Web Design</h1>
            <p>This is a simple example of a responsive web design.</p>
   <img src="https://images.pexels.com/photos/1822458/pexels-photo-1822458.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
   alt="picture of a mountain climber">
        </div>
    <!--<img src="https://images.pexels.com/photos/31350298/pexels-photo-31350298/free-photo-of-scenic-road-to-yosemite-s-half-dome-at-sunset.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
     alt="picture of a scenic road at sunset">-->

     <div class="flex-container">
        <div class="item">What is Lorem Ipsum?
            Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</div>
        <div class="item">Why do we use it?
            It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English. Many desktop publishing packages and web page editors now use Lorem Ipsum as their default model text, and a search for 'lorem ipsum' will uncover many web sites still in their infancy. Various versions have evolved over the years, sometimes by accident, sometimes on purpose (injected humour and the like).</div>
        <div class="item">Where can I get some?
            There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look even slightly believable. If you are going to use a passage of Lorem Ipsum, you need to be sure there isn't anything embarrassing hidden in the middle of text. All the Lorem Ipsum generators on the Internet tend to repeat predefined chunks as necessary, making this the first true generator on the Internet. It uses a dictionary of over 200 Latin words, combined with a handful of model sentence structures, to generate Lorem Ipsum which looks reasonable. The generated Lorem Ipsum is therefore always free from repetition, injected humour, or non-characteristic words etc.</div>
     </div>

     <div class="grid container">
        <div class="grid-item1">Header</div>
        <div class="grid-item2">Menu</div>
        <div class="grid-item3">Main</div>
        <div class="grid-item4">Right</div>
        <div class="grid-item5">Footer</div>
     </div>
      <!-- Footer -->
    <footer class="footer">
        <h2>Contact Us</h2>
        <p>We’d love to hear from you! Reach out through:</p>
        <ul>
            <li> Email: joeymwangi7@gmail.com</li>
            <li> Phone: 0712687036</li>
            <li> Location: Nairobi, Kenya</li>
        </ul>
    </footer>
    </body>
</html>

style.css
/*fluid layout*/
.div-container{
    width: 100%;
    margin: 0 auto;
    background-color: aqua;
}

img{
    width: 100%;
    height: auto;
}

@media (max-width: 600px) {
    .div-container{
        width: 100%;
        background-color: grey;
    }
    
    body{
        background-color: lightsalmon;
        font-family : 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif, sans-serif;
    }
}
/* Navigation Bar */
.navbar {
    background-color: #333;
    padding: 1rem;
}

.navbar ul {
    display: flex;
    justify-content: center;
    list-style: none;
    padding: 0;
}

.navbar li {
    margin: 0 15px;
}

.navbar a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

/* Home Section */
/* General Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

/* Home Section Styling */
.home-section {
    background-image: url('https://images.pexels.com/photos/577585/pexels-photo-577585.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1');
    background-size: ;
    background-position: center;
    color: white;
    text-align: center;
    padding: 50px;
    border-radius: 8px;
}

/* Learn More Section */
#more-info {
    background-color: rgba(255, 255, 255, 0.9);
    color: #333;
    padding: 20px;
    border-radius: 10px;
    margin-top: 20px;
    max-width: 800px;
    margin-left: auto;
    margin-right: auto;
    box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2);
}

/* Section Titles */
#more-info h2, #more-info h3 {
    color: #ff6600;
    text-align: center;
    margin-bottom: 15px;
}

/* List Styling */
#more-info ul {
    list-style: none;
    padding: 0;
}

#more-info li {
    padding: 8px;
    background: rgba(255, 102, 0, 0.1);
    border-left: 4px solid #ff6600;
    margin-bottom: 8px;
}

/* Call-to-Action Button */
.cta-button {
    background-color: #ff6600;
    color: white;
    padding: 12px 24px;
    border: none;
    font-size: 18px;
    cursor: pointer;
    border-radius: 5px;
    margin-top: 20px;
    transition: all 0.3s ease-in-out;
}

.cta-button:hover {
    background-color: #e65c00;
    transform: scale(1.1);
}

/* About Us & Services Sections */
.about-section, .services-section {
    background-color: #d0e8ff; /* Light blue */
    padding: 40px;
    border-radius: 10px;
    text-align: center;
    margin: 20px auto;
    max-width: 900px;
    box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2);
}

/* Section Titles */
.about-section h2, .services-section h2 {
    color: #004080; /* Darker blue for contrast */
    font-size: 28px;
    margin-bottom: 15px;
}

/* Text Styling */
.about-section p, .services-section p {
    font-size: 18px;
    color: #333;
    line-height: 1.6;
}

/* List Styling in Services Section */
.services-section ul {
    list-style: none;
    padding: 0;
}

.services-section li {
    padding: 10px;
    background: rgba(0, 64, 128, 0.1);
    border-left: 5px solid #004080;
    margin-bottom: 10px;
    font-size: 18px;
}

/* Flexible layout */

.flex-container{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    background-color: lightblue;
    flex-wrap: wrap;
    gap: 20px;
}

.item{
    background-color: grey;
    padding: 20px;
    margin: 10px;
    flex: 1; /* This will make the items flexible */
}

@media (max-width: 768px) {
    .container {
        grid-template-columns: 1fr;
    }
    .navbar ul {
        flex-direction: column;
        align-items: center;
    }
}
/* Grid Layout */
.grid-container {
    display: grid;
    grid-template-areas: 'header header header'
     'menu main right' 
     'footer footer footer';
    grid-gap: 10px;
    padding: 10px;
}

.grid-item1{ grid-area: header; background-color: lightseagreen;}
.grid-item2{ grid-area: menu; background-color: lightcoral;}
.grid-item3{ grid-area: main; background-color: lightgoldenrodyellow;}
.grid-item4{ grid-area: right; background-color: lightgreen;}
.grid-item5{ grid-area: footer; background-color: lightsalmon;}

@media (max-width: 600px) {
    .grid-container {
        grid-template-areas: 'header' 
         'menu' 
         'main' 
         'right' 
         'footer';
    }
}

/* Footer Section */
.footer {
    background-color: #333;
    color: lightseagreen;
    text-align: center;
    padding: 20px;
    margin-top: 40px;
}

.footer ul {
    list-style: none;
    padding: 0;
}

.footer li {
    margin: 5px 0;
}
