<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lance Howell P. Villaran | Netflix-Style Portfolio</title>
    <link rel="stylesheet" href="Bio.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>

    <!-- Welcome Page -->
    <div id="welcome-page" class="welcome-page">
        <div class="welcome-content">
            <h1>Welcome to My Biography</h1>
            <p>Discover my journey, skills, hobbies, and more!</p>
            <button class="proceed-btn" onclick="showMainInterface()">Proceed</button>
        </div>
    </div>

    <!-- Main Interface (initially hidden) -->
    <div id="main-interface" class="main-interface" style="display: none;">

        <!-- Netflix-style Navigation Bar -->
        <nav class="netflix-nav">
            <div class="nav-container">
                <div class="nav-logo">LHV</div>
                <div class="nav-menu">
                    <button class="nav-item active" onclick="showSection('home')">Home</button>
                    <button class="nav-item" onclick="showSection('about')">About</button>
                    <button class="nav-item" onclick="showSection('hobbies')">Hobbies</button>
                    <button class="nav-item" onclick="showSection('online-games')">Online Games</button>
                    <button class="nav-item" onclick="showSection('skills')">Skills</button>
                    <button class="nav-item" onclick="showSection('education')">Education</button>
                    <button class="nav-item" onclick="showSection('social')">Connect</button>
                </div>
            </div>
        </nav>

        <!-- Hero Banner (Netflix-style) -->
        <header class="hero-banner" id="home">
            <div class="hero-content">
                <div class="profile-container">
                    <img src="https://scontent.fmnl17-1.fna.fbcdn.net/v/t39.30808-6/291251551_169091632282098_1994314744446273968_n.jpg?_nc_cat=100&ccb=1-7&_nc_sid=6ee11a&_nc_eui2=AeFnyYSKTRK_02ITRCU5eDe48oc9w8ImLA7yhz3DwiYsDt1Wp4mqOm3Inf0X-9g4dcE1ZTig0iTDRWJ9gJQKaTZi&_nc_ohc=QyDpCb5lWKMQ7kNvgG1XWsY&_nc_oc=Adkdo7ncoV9mQM3j6N-TRY23hrhewE0vM0FRqVDLPtCwSnxUkslZWurm05lDV6wTxUU&_nc_zt=23&_nc_ht=scontent.fmnl17-1.fna&_nc_gid=cZ2RA6vJHGS6FEakt31t7w&oh=00_AYEDn15RoUn_OgnUC0TZVm5nhOdmg9QrmufghgMLK-bB3Q&oe=67F072A4" alt="Lance Howell P. Villaran" class="hero-profile">
                </div>
                <div class="hero-text">
                    <h1 class="hero-title">LANCE HOWELL P. VILLARAN</h1>
                    <h2 class="hero-subtitle">2CPE - A | Computer Engineering Student</h2>
                    <div class="hero-buttons">
                        <button class="hero-btn play-btn" onclick="showSection('about')">
                            <i class="fas fa-info-circle"></i> More Info
                        </button>
                        <button class="hero-btn list-btn" onclick="showSection('skills')">
                            <i class="fas fa-list"></i> My Skills
                        </button>
                    </div>
                    <p class="hero-description">Tech Enthusiast | Creative Problem Solver | Future Engineer</p>
                </div>
            </div>
        </header>

        <!-- Content Sections (Netflix-style rows) -->
        <main class="content-container">
            <!-- About Me Section -->
            <section class="content-row" id="about">
                <h2 class="row-title">About Me</h2>
                <div class="row-content">
                    <div class="info-card">
                        <div class="card-content">
                            <h3>Who Am I?</h3>
                            <p>Hello! I'm <strong>Lance Howell P. Villaran</strong>, a passionate developer and creative thinker with a love for building digital experiences that matter.</p>
                        </div>
                    </div>
                    <div class="info-card">
                        <div class="card-content">
                            <h3>My Passion</h3>
                            <p>With a background in computer science and a never-ending curiosity for technology, I specialize in creating solutions that bridge the gap between functionality and aesthetics.</p>
                        </div>
                    </div>
                    <div class="info-card">
                        <div class="card-content">
                            <h3>My Interests</h3>
                            <p>When I'm not coding, you can find me exploring new anime series, gaming, or experimenting with new musical instruments.</p>
                        </div>
                    </div>
                </div>
            </section>

            <!-- Hobbies Section -->
            <section class="content-row" id="hobbies">
                <h2 class="row-title">My Hobbies</h2>
                <div class="row-content">
                    <div class="hobby-card">
                        <div class="hobby-icon"><i class="fas fa-gamepad"></i></div>
                        <div class="hobby-info">
                            <h3>Gaming</h3>
                            <p>I enjoy playing various video games, from competitive shooters to immersive RPGs.</p>
                        </div>
                    </div>
                    <div class="hobby-card">
                        <div class="hobby-icon"><i class="fas fa-music"></i></div>
                        <div class="hobby-info">
                            <h3>Music</h3>
                            <p>Playing guitar and piano helps me relax and express my creativity.</p>
                        </div>
                    </div>
                    <div class="hobby-card">
                        <div class="hobby-icon"><i class="fas fa-film"></i></div>
                        <div class="hobby-info">
                            <h3>Anime</h3>
                            <p>Watching anime is one of my favorite ways to unwind and get inspired.</p>
                        </div>
                    </div>
                    <div class="hobby-card">
                        <div class="hobby-icon"><i class="fas fa-code"></i></div>
                        <div class="hobby-info">
                            <h3>Coding</h3>
                            <p>I love experimenting with new technologies and building personal projects.</p>
                        </div>
                    </div>
                </div>
            </section>

            <!-- Online Games Section -->
            <section class="content-row" id="online-games">
                <h2 class="row-title">Favorite Online Games</h2>
                <div class="row-content">
                    <div class="game-card">
                        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Valorant_logo.svg/1200px-Valorant_logo.svg.png" alt="Valorant">
                        <div class="game-info">
                            <h3>Valorant</h3>
                            <p>Tactical FPS by Riot Games</p>
                            <a href="https://playvalorant.com/" target="_blank" class="game-link">Visit Site</a>
                        </div>
                    </div>
                    <div class="game-card">
                        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5e/Genshin_Impact_logo.svg/1200px-Genshin_Impact_logo.svg.png" alt="Genshin Impact">
                        <div class="game-info">
                            <h3>Genshin Impact</h3>
                            <p>Open-world action RPG</p>
                            <a href="https://genshin.hoyoverse.com/" target="_blank" class="game-link">Visit Site</a>
                        </div>
                    </div>
                    <div class="game-card">
                        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/7a/League_of_Legends_logo.png/1200px-League_of_Legends_logo.png" alt="League of Legends">
                        <div class="game-info">
                            <h3>League of Legends</h3>
                            <p>MOBA by Riot Games</p>
                            <a href="https://www.leagueoflegends.com/" target="_blank" class="game-link">Visit Site</a>
                        </div>
                    </div>
                    <div class="game-card">
                        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/4a/Dota_2_Logo.png/1200px-Dota_2_Logo.png" alt="Dota 2">
                        <div class="game-info">
                            <h3>Dota 2</h3>
                            <p>Strategy MOBA by Valve</p>
                            <a href="https://www.dota2.com/home" target="_blank" class="game-link">Visit Site</a>
                        </div>
                    </div>
                </div>
            </section>

            <!-- Skills Section -->
            <section class="content-row" id="skills">
                <h2 class="row-title">My Skills</h2>
                <div class="skills-row">
                    <div class="skill-card">
                        <div class="skill-icon"><i class="fab fa-html5"></i></div>
                        <div class="skill-info">
                            <h3>HTML5</h3>
                            <div class="skill-meter">
                                <div class="skill-level" style="width: 95%"></div>
                            </div>
                        </div>
                    </div>
                    <div class="skill-card">
                        <div class="skill-icon"><i class="fab fa-css3-alt"></i></div>
                        <div class="skill-info">
                            <h3>CSS3</h3>
                            <div class="skill-meter">
                                <div class="skill-level" style="width: 90%"></div>
                            </div>
                        </div>
                    </div>
                    <div class="skill-card">
                        <div class="skill-icon"><i class="fab fa-js"></i></div>
                        <div class="skill-info">
                            <h3>JavaScript</h3>
                            <div class="skill-meter">
                                <div class="skill-level" style="width: 85%"></div>
                            </div>
                        </div>
                    </div>
                    <div class="skill-card">
                        <div class="skill-icon"><i class="fab fa-react"></i></div>
                        <div class="skill-info">
                            <h3>React</h3>
                            <div class="skill-meter">
                                <div class="skill-level" style="width: 80%"></div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>

            <!-- Education Section -->
            <section class="content-row" id="education">
                <h2 class="row-title">Education</h2>
                <div class="edu-row">
                    <div class="edu-card">
                        <div class="edu-icon"><i class="fas fa-graduation-cap"></i></div>
                        <div class="edu-details">
                            <h3>Bachelor of Science in Computer Engineering</h3>
                            <p>University of Example | 2022 - Present</p>
                            <p>Specialized in Software Development and Hardware Systems</p>
                        </div>
                    </div>
                    <div class="edu-card">
                        <div class="edu-icon"><i class="fas fa-certificate"></i></div>
                        <div class="edu-details">
                            <h3>Certifications</h3>
                            <ul>
                                <li>Full Stack Web Development</li>
                                <li>AWS Certified Cloud Practitioner</li>
                                <li>Certified Scrum Master</li>
                            </ul>
                        </div>
                    </div>
                </div>
            </section>

            <!-- Social Media Section -->
            <section class="content-row" id="social">
                <h2 class="row-title">Connect With Me</h2>
                <div class="social-row">
                    <a href="https://www.facebook.com/share/18h3R4z4k2/" target="_blank" class="social-card facebook">
                        <i class="fab fa-facebook-f"></i>
                        <span>Facebook</span>
                    </a>
                    <a href="https://www.threads.net/@lance_villaran" target="_blank" class="social-card threads">
                        <i class="fab fa-threads"></i>
                        <span>Threads</span>
                    </a>
                    <a href="https://www.instagram.com/lance_villaran?igsh=MXFxcTd4MHZ5b3N0Zw==" target="_blank" class="social-card instagram">
                        <i class="fab fa-instagram"></i>
                        <span>Instagram</span>
                    </a>
                    <a href="https://www.tiktok.com/@lancehowellvillar61?_t=ZS-8v8pe5F4MSu&_r=1" target="_blank" class="social-card tiktok">
                        <i class="fab fa-tiktok"></i>
                        <span>TikTok</span>
                    </a>
                </div>
            </section>
        </main>
    </div>

    <script>
        // Show welcome page initially
        document.addEventListener('DOMContentLoaded', function() {
            document.getElementById('welcome-page').style.display = 'flex';
            document.getElementById('main-interface').style.display = 'none';
        });

        // Switch to main interface
        function showMainInterface() {
            document.getElementById('welcome-page').style.display = 'none';
            document.getElementById('main-interface').style.display = 'block';
            showSection('home');
        }

        // Smooth scrolling to sections
        function showSection(sectionId) {
            const section = document.getElementById(sectionId);
            if (section) {
                // Update active nav item
                document.querySelectorAll('.nav-item').forEach(item => {
                    item.classList.remove('active');
                });
                document.querySelector(`.nav-item[onclick="showSection('${sectionId}')"]`).classList.add('active');
                
                // Scroll to section
                section.scrollIntoView({ behavior: 'smooth' });
            }
        }

        // Netflix-style hover effects
        document.querySelectorAll('.info-card, .skill-card, .edu-card, .hobby-card, .game-card').forEach(card => {
            card.addEventListener('mouseenter', function() {
                this.style.transform = 'scale(1.05)';
                this.style.zIndex = '10';
            });
            
            card.addEventListener('mouseleave', function() {
                this.style.transform = 'scale(1)';
                this.style.zIndex = '1';
            });
        });

        // Hero banner animation
        window.addEventListener('scroll', function() {
            const hero = document.querySelector('.hero-banner');
            const scrollPosition = window.scrollY;
            hero.style.backgroundPositionY = `${scrollPosition * 0.5}px`;
        });
    </script>

</body>
</html>
