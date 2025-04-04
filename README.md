html and js


<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>personal portfolio</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://kit.fontawesome.com/3b0c9a5478.js" crossorigin="anonymous"></script>
</head>

<body>
    <div id="header">
        <div class="container">
            <nav>
                <img src="images.jpg" alt="logo">
                <ul>
                    <li><a href="#header">home</a></li>
                    <li><a href="#about-me">about me</a></li>
                    <li><a href="#projects">projects</a></li>
                    <li><a href="#contact-me">contact me</a></li>
                </ul>
            </nav>
            <div class="header-text">
                <p> web developer and Ethical Hacker </p>
                <h1> Hi! I am <span>Yash Raj Bhatt</span>.<br> I am from Kashipur Uttrakhand </h1>
            </div>
        </div>
    </div>
    <div id="about-me">
        <div class="container">
            <div class="row">
                <div class="about-col-1">
                    <img src="WhatsApp Image 2025-03-30 at 10.44.26 PM-removebg-preview.jpg" alt="developer photo">
                </div>
                <div class="about-col-2">
                    <h1 class="sub-title"> About Me</h1>
                    <p>I am Yash Raj Bhatt, a passionate and driven Computer Science Engineer with a strong foundation
                        in web development and ethical hacking. I completed my B.Tech in Computer Science
                        Engineering from Quantum University, building a solid technical expertise in cybersecurity,
                        networking, and web development.

                        My academic journey began at Maria Assumpta Convent School, where I pursued my schooling under
                        the CBSE board, shaping my analytical and problem-solving abilities.

                        In addition to my technical skills, I possess strong communication skills and a natural
                        leadership quality, which enable me to collaborate effectively and take initiative in
                        challenging situations. My ability to lead and work within a team has been instrumental in both
                        my academic and extracurricular endeavors.

                        With a keen interest in technology, innovation, and cybersecurity, I am always eager to explore
                        new advancements and contribute effectively to the field.

                    </p>
                    <div class="tab-titles">
                        <p class="tab-links active-link" onclick="opentab(event, 'skills')">Skills</p>
                        <p class="tab-links" onclick="opentab(event, 'hobbies')">Hobbies</p>
                        <p class="tab-links" onclick="opentab(event, 'education')">Education</p>
                    </div>
                    <div class="tab-contents active-tab" id="skills">
                        <ul>
                            <li><span>web development:</span><br>"I have a strong skill set in web development,
                                with experience in designing, coding, and maintaining website. My expertise
                                includes programming languages, website development principles, and problem-solving
                                techniques. I enjoy building scalable, efficient, and user-friendly website solutions.
                                Throughout my learning journey, I have worked on various projects that have enhanced my
                                understanding of web technologies, databases, and website architecture. My passion for
                                website
                                development drives me to constantly explore new technologies and improve my coding
                                skills."

                            </li>
                            <li><span>Ethical Hacking:</span><br>"I have strong skills in ethical hacking, which involve
                                identifying and fixing security vulnerabilities in computer systems and networks. My
                                expertise includes penetration testing, network security, and threat analysis. I am
                                proficient in using tools like Kali Linux, Metasploit, Wireshark, and various
                                cybersecurity frameworks to assess and enhance security measures. My passion for ethical
                                hacking drives me to stay updated with the latest cybersecurity trends and techniques,
                                ensuring that I can help organizations protect their digital assets from cyber threats."

                            </li>
                        </ul>
                    </div>
                    <div class="tab-contents" id="hobbies">
                        <ul>
                            <li><span>Music:</span><br>"Music is my passion and a significant part of my life. I enjoy
                                exploring different genres, from classical to contemporary, and appreciate the art of
                                composition and sound production. Whether it's singing, playing instruments, or creating
                                beats, I find joy in expressing myself through music. It not only helps me relax but
                                also fuels my creativity and enhances my concentration. Music is more than just a hobby
                                for me—it's a way to connect with emotions, people, and culture."

                            </li>
                            <li><span>Sports:</span><br> "Sports play a vital role in my life, keeping me physically
                                active and mentally sharp. I enjoy engaging in various sports, as they not only help me
                                stay fit but also teach me discipline, teamwork, and perseverance. Whether it's playing
                                competitively or just for fun, I love the thrill of the game and the sense of
                                achievement that comes with improving my skills. Sports have also helped me develop a
                                strong sense of sportsmanship and resilience, which are valuable in all aspects of
                                life."

                            </li>
                        </ul>
                    </div>
                    <div class="tab-contents" id="education">
                        <ul>
                            <li><span>Schooling</span><br> I am a student of the Central Board of Secondary Education
                                (CBSE), studying at Maria Assumpta Convent School. My school is known for its emphasis
                                on academic excellence, discipline, and holistic development. It provides a
                                well-structured curriculum that helps students grow intellectually and personally. Being
                                a part of this institution has helped me develop strong foundational knowledge and
                                skills in various subjects."</li>
                            <li><span>Graduation:</span><br> "I am a B.Tech graduate from Quantum University,
                                specializing in Computer Science and Engineering (CSE). My education has provided me
                                with a strong foundation in programming, web development, networking, and
                                cybersecurity. Throughout my academic journey, I have gained hands-on experience in
                                web development, ethical hacking, and various emerging technologies. Quantum
                                University has equipped me with both theoretical knowledge and practical skills,
                                preparing me for challenges in the tech industry."
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div id="projects">
        <div class="container">
            <h1 class="sub-title">projects</h1>
            <div class="projects-lists">
                <div>
                    <i class="fa-solid fa-code-compare"></i>
                    <h2> OWASP risk calculator </h2>
                    <p> The OWASP Risk Calculator is a tool used to assess and prioritize security risks based on the
                        OWASP Risk Rating Methodology. This methodology helps security professionals determine the
                        likelihood and impact of a security vulnerability in web applications, networks, or systems.

                    </p>
                    <a href="#">Learn more</a>
                </div>
                <div>
                    <i class="fa-solid fa-code-compare"></i>
                    <h2> Credit Card Fraud Detection</h2>
                    <p>Credit card fraud detection is the process of identifying fraudulent transactions in real-time to
                        prevent financial losses.The goal is to detect fraudulent transactions from a dataset of credit
                        card transactions. </p>
                    <a href="#">Learn more</a>
                </div>
                <div>
                    <i class="fa-solid fa-code-compare"></i>
                    <h2>Social Media Platform </h2>
                    <p>A full-stack social media platform that allows users to connect, share, and interact through
                        posts, comments, and real-time messaging. This project is designed to simulate the core
                        functionality of modern social platforms like Instagram and Twitter, with user authentication,
                        media sharing, and a personalized feed.
                    </p>
                    <a href="#">Learn more</a>
                </div>
                <div>
                    <i class="fa-solid fa-code-compare"></i>
                    <h2>Job Portal System</h2>
                    <p>A comprehensive full-stack web application that connects job seekers and employers. It allows
                        companies to post jobs and candidates to search, apply, and manage applications — much like
                        Naukri.com, LinkedIn Jobs, or Indeed.

                    </p>
                    <a href="#">Learn more</a>
                </div>
                <div>
                    <i class="fa-solid fa-code-compare"></i>
                    <h2> Portfolio Website
                    </h2>
                    <p>A fully responsive, modern, and elegant personal portfolio website built to showcase my skills,
                        projects, achievements, and contact information. It serves as a digital résumé and an
                        interactive platform for potential employers, clients, or collaborators to learn more about me.


                    </p>
                    <a href="">Learn more</a>
                </div>
                <div>
                    <i class="fa-solid fa-code-compare"></i>
                    <h2>Brainwave-Based Authentication (Neurosecurity)
                    </h2>
                    <p>Instead of passwords, use brainwave patterns (EEG scans) for authentication.Hackers can not steal
                        or copy your unique brainwave patterns.Being tested in biometric security & futuristic access
                        control systems.</p>
                    <a href="#">Learn more</a>
                </div>
            </div>
        </div>
    </div>
    <div id="contact-me">
        <div class="container">
            <div class="row">
                <div class="contact-left">
                    <h1 class="sub-title"> contact me</h1>
                    <p><i class="fa-sharp fa-solid fa-paper-plane"></i> yashrajbhatt24@gmail.com</p>
                    <p> <i class="fa-solid fa-phone"></i> 7983395430</p>
                    <div class="social-icons">
                        <a href="https://www.facebook.com/share/15zyNeVFCy/"><i class="fa-brands fa-facebook"></i></a>
                        <a
                            href="https://www.linkedin.com/in/yash-raj-bhatt-063a09356?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app"><i
                                class="fa-brands fa-linkedin"></i></a>
                        <a href="https://youtube.com/@glitchbalak?si=FUsRZnZKo_GSAcsK"><i
                                class="fa-brands fa-youtube"></i></a>
                    </div><br><br>
                    <a href="path/to/your-cv.pdf" class="btn btn2" download>download cv</a>
                </div>
                <div class="contact-right">
                    <form >
                        <input type="text" name="Name" placeholder="your name" required>
                        <input type="email" name="Email" placeholder="your email" required>
                        <textarea name="Message" rows="6" placeholder="your message"></textarea>
                        <button type="submit" class="btn btn2">send</button>


                    </form>
                    <span id="msg"> </span>
                </div>
            </div>
        </div>

    </div>
    </div>
    <div class="copyright">
        <p> copyright <i class="fa-regular fa-copyright" class="btn3"></i> Yash Raj Bhatt <i
                class="fa-solid fa-heart"></i>love all who visit my website</p>
    </div>

    </div>

    <script>
        var tablinks = document.getElementsByClassName("tab-links");
        var tabcontents = document.getElementsByClassName("tab-contents");
        function opentab(event, tabname) {
            for (let tablink of tablinks) {
                tablink.classList.remove("active-link");
            }
            for (let tabcontent of tabcontents) {
                tabcontent.classList.remove("active-tab");
            }
            event.currentTarget.classList.add("active-link");
            document.getElementById(tabname).classList.add("active-tab");
        }
    </script>
    </body>
    </html>



    css 



    * {
    margin: 0;
    padding: 0;
    font-family: 'poppins', sans-serif;
    box-sizing: border-box;

}

body {
    background: #080808;
    color: #fff;
}

#header {
    width: 100%;
    height: 100vh;
    background-image: url(removebg-preview.jpg);
    background-size: cover;
    background-position: center;

}

.container {
    padding: 10px 10%;

}

nav {
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;

}

.logo {
    width: 110px;

}

nav ul li {
    display: inline-block;
    list-style: none;
    margin: 10px 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-size: 30px;
    position: relative;


}

nav ul li a::after {
    content: '';
    width: 0%;
    height: 3px;
    background: blueviolet;
    position: absolute;
    left: 0;
    bottom: -6px;
    transition: 0.5s;

}

nav ul li a:hover::after {
    width: 100%;
    ;

}

.header-text {
    margin-top: 20%;
    font-size: 30px;

}

.header-text h1 {
    font-size: 60px;
    margin-top: 20px;


}

.header-text h1 span {
    color: #ff004f
}

#about {
    padding: 80px 0;
    color: #ababab;
}

.row {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
}

.about-col-1 {
    flex-basis: 35%;

}

.about-col-1 img {
    width: 100%;
    height: 100%;
    border-radius: 15px;


}

.about-col-2 {
    flex-basis: 60%;

}

.sub-title {
    font-size: 60px;
    font-weight: 600;
    color: #fff;

}

.tab-titles {
    display: flex;
    margin: 20px 0 40px;


}

.tab-links {
    margin-right: 50px;
    font-size: 18px;
    font-weight: 500;
    cursor: pointer;
    position: relative;
}

.tab-links::after {
    content: '';
    width: 0;
    height: 3px;
    background: #ff004f;
    position: absolute;
    left: 0;
    bottom: -8px;
    transition: 0.5s;
}

.tab-links.active-link::after {
    width: 50%;
}

.tab-contents ul li {
    list-style-type: none;
    margin: 10px 0;
}

.tab-contents ul li span {
    color: #ff004f;
    font-size: 14px;

}

.tab-contents {
    display: none;

}

.tab-contents.active-tab {
    display: block;

}

#projects {
    padding: 30px 0;

}

.projects-lists {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    grid-gap: 40px;
    margin-top: 50px;

}

.projects-lists div {

    background: #262626;
    padding: 40px;
    font-size: 13px;
    font-weight: 300;
    border-radius: 10px;
    transition: background 0.5s, transform 0.5s;
}

.projects-lists div i {
    font-size: 50px;
    margin-bottom: 30px;

}

.projects-lists div h2 {
    font-size: 30px;
    font-weight: 500;
    margin-bottom: 15px;

}

.projects-lists div a {
    text-decoration: none;
    color: #fff;
    font-size: 12px;
    margin-top: 20px;
    display: inline-block;

}

.projects-lists div:hover {
    background: #ff004f;
    transform: translateY(-10px);

}

.contact-left{
    flex-basis: 35%;

}

.contact-right{
    flex-basis: 60%;

    
}

.contact-left p{
    margin-top: 30px;

}
.contact-left p i{
    color: #ff004f;
    margin-right: 15px;
    font-size: 25px;

}

.social-icons{
    margin-top: 30px;
}

.social-icons a{
    text-decoration: none;
    font-size: 30px;
    margin-right: 15px;
    color: #ababab;
    display: inline-block;
    transition: transform 0.5s;

}

.social-icons a:hover{
    color: #ff004f;
    transform: translateY(-5px);
}

.btn.btn2{
    display: inline-block;
    background: #ff004f;
    padding: 15px 30px;

}

.contact-right form{
    width:100%;
    }

    form input, textarea{
       
        width: 100%;
        border: 0;
        outline: none;
        background: #262626;
        padding: 15px;
        margin: 15px 0;
        color: #fff;
        font-size: 18px;
        border-radius: 6px;

    }

    form .btn2{
        padding: 14px 60px;
        font-size: 18px;
        margin-top: 20px;
        cursor: pointer;

    }

    .copyright{
        width: 100%;
        text-align: center;
        padding: 25px 0;
        background: #262626;
        font-weight: 300;
        margin-top: 20px;

    }

    .copyright i{
        color: #ff004f;
    }

    html{

        scroll-behavior:smooth;
    }

    #msg{
        color: #61b752;
        margin-top: -10px;
        display: block;

    }


