<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio - Bintang Ernawati Aritonang</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f2f5;
            color: #333;
        }

        header {
            background-color: #4CAF50;
            color: #fff;
            padding: 20px 0;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        h1 {
            font-size: 2.5rem;
            margin: 0;
        }

        p.subtitle {
            font-size: 1.2rem;
            margin-top: 10px;
        }

        main {
            max-width: 1200px;
            margin: 30px auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }

        section {
            margin-bottom: 40px;
        }

        h2 {
            font-size: 2rem;
            color: #4CAF50;
            margin-bottom: 20px;
        }

        .profile {
            display: flex;
            align-items: center;
            margin-bottom: 40px;
        }

        .profile img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            object-fit: cover;
            margin-right: 20px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }

        .profile div {
            max-width: 800px;
        }

        .portfolio-container, .experience-container, .organization-container {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }

        .portfolio-item, .experience-item, .organization-item {
            background-color: #f9f9f9;
            border-radius: 8px;
            overflow: hidden;
            width: calc(33.333% - 20px);
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }

        .portfolio-item:hover, .experience-item:hover, .organization-item:hover {
            transform: translateY(-10px);
        }

        .portfolio-item img, .experience-item img, .organization-item img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }

        .portfolio-item h3, .experience-item h3, .organization-item h3 {
            margin: 0;
            padding: 15px;
            font-size: 1.5rem;
            color: #333;
        }

        .portfolio-item p, .experience-item p, .organization-item p {
            padding: 0 15px 15px;
            font-size: 1rem;
            color: #666;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #4CAF50;
            color: #fff;
            margin-top: 40px;
            position: relative;
            bottom: 0;
        }

        footer a {
            color: #fff;
            text-decoration: underline;
            font-weight: bold;
        }

        @media (max-width: 768px) {
            .portfolio-item, .experience-item, .organization-item {
                width: 100%;
            }

            .profile {
                flex-direction: column;
                text-align: center;
            }

            .profile img {
                margin: 0 0 20px 0;
            }
        }
        .experience-container {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: space-between;
}

.experience-item {
    background-color: #f9f9f9;
    border-radius: 8px;
    padding: 20px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    max-width: 45%;
    flex: 1 1 45%;
}

.experience-item img {
    width: 100%;
    height: auto;
    border-radius: 8px;
}

.experience-item h3 {
    font-size: 1.2em;
    margin-top: 15px;
    color: #333;
}

.experience-item p {
    font-size: 1em;
    line-height: 1.5;
    color: #555;
}

@media (max-width: 768px) {
    .experience-item {
        max-width: 100%;
    }
}
a {
    color: #fff;
    background-color: #4d69c5;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
    transition: background-color 0.3s;
}

a:hover {
    background-color: #45a049;
}
.resize-image {
    width: 30%; 
    height: auto; 
}
.experience-container {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }

        .experience-item {
            background-color: #fff;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
            position: relative;
            padding: 15px;
            max-width: 45%;
            flex: 1 1 45%;
            z-index: 1; /* Ensure it stays above the blur */
        }

        .experience-item img {
            width: 100%;
            height: auto;
            transition: transform 0.3s ease;
        }

        .experience-item h3, .experience-item p {
            transition: transform 0.3s ease;
        }

        .experience-item:hover img,
        .experience-item:hover h3,
        .experience-item:hover p {
            transform: scale(1.1); /* Zoom in by 10% */
        }

        .experience-item:hover::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(255, 255, 255, 0.5); /* Semi-transparent background */
            backdrop-filter: blur(5px);
            z-index: -1; /* Behind the content */
            pointer-events: none; /* Ensure it doesn't interfere with mouse events */
        }
    </style>
</head>
<body>

    <header>
        <h1>Bintang Ernawati Aritonang</h1>
        <p class="subtitle">Management Student | Leadership Enthusiast | Digital Marketer</p>
        
        <!-- Link to the certificate -->
        <p><a href="Certificate.<html>
        </html>" target="_blank">Certificate</a></p>
    </header>
    
    <main>
        <section class="profile">
            <img src="profil.jpeg" alt="Profile Picture">
            <div>
                <p>Hello! I am Bintang Ernawati Aritonang, a sixth-semester Management major. I have studied various aspects of management, including human resource management and marketing. I have also learned about management theories and applied them through case studies and digital marketing strategies. In addition to my academic work, I am actively involved in organizational activities, where I have developed skills in leadership, decision-making, and team collaboration. I aim to combine my academic knowledge with practical experience to better prepare myself for future opportunities.</p>
            </div>
        </section>
<hr>
        <section>
            <h2>Education</h2>
            <p>Bachelor of Management - HKBP NOMMENSEN UNIVERSITY<br>
            Sixth Semester (Expected Graduation: 2025)</p>
            <ul>
                <li>Human Resource Management</li>
                <li>Marketing Strategies & Digital Marketing</li>
                <li>Leadership and Organizational Behavior</li>
            </ul>
            <hr>
            <p>Senior High School 1 Pagaran Natural Science<br>
            (2017 - 2020)</p>
            <ul>
               
            </ul>
        </section>

        <section>
            <h2>Personal Skills</h2>
            <ul>
                <li>Leadership and Team Collaboration</li>
                <li>Strategic Decision Making</li>
                <li>Problem Solving and Critical Thinking</li>
                <li>Digital Marketing and Social Media Strategies</li>
                <li>Interpersonal Communication Skills</li>
            </ul>
        </section>

        <section>
            <h2>Experience</h2>
            <div class="experience-container">
                <article class="experience-item">
                    <img src="debat.png" alt="Debate Competition" style="width: 50%; height: auto;">
                    <h3>Third Place Winner in Debate Competition at HKBP Nommensen University</h3>
                    <p>
                        I participated in a debate competition organized by the Faculty of Economics and Business at HKBP Nommensen University. The event focused on the theme "Potential of Lake Toba," and I secured third place. The competition was part of the anniversary celebrations for the faculty and provided a platform to showcase critical thinking, public speaking, and teamwork.
                    </p>
                </article>
        
                <article class="experience-item">
                    <img src="bea.png" alt="Science Writing Competition 2023" style="width: 50%; height: auto;">
                    <h3>Science Writing Competition 2023 - Bea Cukai</h3>
                    <p>
                        I participated in the Scientific Writing Competition organized by Bea Cukai in 2023. The competition, held online for Indonesian students, allowed me to explore the topic "The Role of Excise Extensification as a Supporter of Industrial Sustainability in Indonesia." This experience enhanced my research and analytical skills, contributing to my understanding of industry and policy.
                    </p>
                </article>
        
                <article class="experience-item">
                    <img src="healt.png" alt="Mental Health Ambassador National 2024" style="width: 50%; height: auto;">
                    <h3>Mental Health Ambassador National by Believe in Aura</h3>
                    <p>
                        As one of the 2024 National Mental Health Ambassadors organized by Believe in Aura, I believe that maintaining mental health is essential for everyone. Let's prioritize our well-being and take care of our mental health.
                    </p>
                </article>
        
                <article class="experience-item">
                    <img src="inden.png" alt="Independent Study Merdeka Campus 2024" style="width: 50%; height: auto;">
                    <h3>Independent Study Merdeka Campus 2024</h3>
                    <p>
                        The Independent Study program provides students with the opportunity to acquire specific and practical competencies directly from experts over the course of one semester through hands-on learning and practical activities. I am a student participating in the Independent Study program at the Merdeka Campus in 2024, batch 6, with the position of Digital Marketing Master at PT. International Consultant for one semester. The Independent Study at PT. International Consultant also includes lectures, mentoring, and enrichment classes. Together with friends from various universities, we were given the responsibility to assist small and medium enterprises (SMEs). What we learned in class was applied in field practice. In this program, we studied business introduction, the role of consultants, market analysis and segmentation, value propositions, the business model canvas, the fundamentals of digital marketing, social media strategies, content creation for YouTube and Instagram, visual graphics, social media effectiveness evaluation, advanced social media tools, content literacy, internet marketing strategies, email marketing, and basic Search Engine Optimization (SEO).
                    </p>
                </article>
            </div>
        </section>
        
    
        </section>

        <section>
            <h2>Organizations</h2>
            <div class="organization-container">
                <article class="organization-item">
                    <img src="inggris.png" alt="Organization 1" tyle="width: 50%; height: auto;">
                    <h3>NEC English UKM</h3>
                    <p>
                        I am a member of the NEC English UKM organization in 2023. This organization focuses on activities that help improve my English skills.
                    </p>
                </article>
        
                <article class="organization-item">
                    <img src="kmk.png" alt="Organization 2" tyle="width: 50%; height: auto;">
                    <h3>KMKb</h3>
                    <p>
                        I am a member of the KMKb organization and serve as the head of the events division, where I manage several KMK UMK activities in 2023.
                    </p>
                </article>
            </div>
        </section>
        

        <section>
            <h2>Portfolio</h2>
            <div class="portfolio-container">
                <article class="portfolio-item">
                    <img src="project1-thumbnail.jpg" alt="Project 1">
                    <h3>Project 1</h3>
                    <p>committe member for debate competition at the senior High School on 20 october 2021 hosted by G.A Education with the theme "the right solution to achice achiecement".</p>
                </article>

                <article class="portfolio-item">
                    <img src="project2-thumbnail.jpg" alt="Project 2">
                    <h3>Project 2</h3>
                    <p>in 2023, holding a welcoming event for studentsfrom the student activiti unit organization ad HKBP Nommensen University</p>
                </article>

            </div>
        </section>
    </main>

    <footer>
        <p>Contact: <a href="mailto:your.email@example.com">your.email@example.com</a> | LinkedIn: <a href="https://linkedin.com/in/yourprofile" target="_blank">View Profile</a> | GitHub: <a href="https://github.com/yourprofile" target="_blank">yourprofile</a></p>
    </footer>

</body>
</html>