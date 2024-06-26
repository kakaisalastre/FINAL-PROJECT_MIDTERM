<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/remixicon@4.2.0/fonts/remixicon.css" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
    <title>Web Design Mastery | Responsive Portfolio</title>
</head>
<body>
    <nav>
        <div class="nav_content">
            <div class="logo"><a href="#">Khyla</a></div>
            <label for="check" class="checkbox">
                <i class="ri-menu-line"></i>
            </label>
            <input type="checkbox" name="check" id="check">
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </div>
    </nav>
    
    <section id="header" class="section">
        <div class="section_container">
            <div class="header-text">
                <h1>Hello, I'm <span>Khyla<br>a</span> Web Developer</h1>
                <div class="section_container">
                    <div class="action_btns">
                    </div>
                </div>
                <div class="image">
                    <img src="https://scontent.fbag4-1.fna.fbcdn.net/v/t1.15752-9/440139778_454213797169707_1714795442042345566_n.jpg?_nc_cat=108&ccb=1-7&_nc_sid=5f2048&_nc_ohc=l6MaAaWqiJoAb4hDeAe&_nc_ht=scontent.fbag4-1.fna&oh=03_Q7cD1QEoVOdHiI6v5e-wHYXyXU1_fy2bIA_Z7Lb13kbol5Yl3A&oe=664DE68B" alt="profile"/>
                </div>
            </div>
        </div>
    </section>

    <section id="about" class="section">
        <div class="section_container">
            <div class="content">
                <h2 class="section_title">About Me</h2>
                <p>Welcome to my web developer portfolio! I'm Khyla, a skilled and 
                    creative web developer with a passion for creating beautiful,
                     responsive, and user-friendly websites, I've worked on a 
                     variety of web projects, ranging from personal blogs to 
                     e-commerce platforms.</p>
            </div>
        </div>
    </section>
    
    <section id="skills" class="section">
        <div class="section_container">
            <div class="content">
                <h2 class="section_title">Skills</h2>
                <div class="skill">
                    <div class="name">HTML</div>
                    <div class="progress-bar">
                        <div class="progress" id="htmlProgress" style="width: 80%;"></div>
                        <div class="percent" id="htmlPercent">80%</div>
                    </div>
                </div>
                <div class="skill">
                    <div class="name">CSS</div>
                    <div class="progress-bar">
                        <div class="progress" id="cssProgress" style="width: 50%;"></div>
                        <div class="percent" id="cssPercent">50%</div>
                    </div>
                </div>
                <div class="skill">
                    <div class="name">JavaScript</div>
                    <div class="progress-bar">
                        <div class="progress" id="jsProgress" style="width: 80%;"></div>
                        <div class="percent" id="jsPercent">70%</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="portfolio" class="section">
        <div class="section_container">
            <h2 class="sub-title">Portfolio</h2>
            <span>My Recent Work</span>
            <div class="work-list">
                <div class="work">
                    <img src="https://scontent.fmnl17-1.fna.fbcdn.net/v/t1.15752-9/440108759_405095535714649_215878164779112245_n.jpg?_nc_cat=101&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeEaVdRiNtBKhPWk_w2HI9zPbcrXLD8GJYxtytcsPwYljDRS18Ku8Vl5t23DvmVLnB1Blnu8Oulz1CHbtx58B2KV&_nc_ohc=BUjJfM-QXRkAb66L63N&_nc_ht=scontent.fmnl17-1.fna&oh=03_Q7cD1QHEjDf1tMm2qMPpE2SYna_RaOhSnxeCYKqapc9-wjbxYg&oe=664E983A">
                    <div class="layer"></div>
                </div>
                <div class="work">
                    <img src="https://scontent.fmnl17-1.fna.fbcdn.net/v/t1.15752-9/438231556_724005092983111_1110513058503303807_n.jpg?_nc_cat=100&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeFtj_mDOKsrCO2ZYpoTlBYvfQk2TPOpaw99CTZM86lrD2RmIJZk3ss3fnBFr-ueOIFk4V44pldPB_yiRs1Gn4dj&_nc_ohc=3KWOxiXCdYsAb74VT5h&_nc_ht=scontent.fmnl17-1.fna&oh=03_Q7cD1QHv4pgUHjmeCIi4ubKSr6HEOlcMfP-MzL8iecaMTmTeew&oe=664E9E0D">
                    <div class="layer"></div>
                </div>
                <div class="work">
                    <img src="https://scontent.fmnl17-4.fna.fbcdn.net/v/t1.15752-9/437970774_965712794923191_2832052138953689055_n.jpg?_nc_cat=105&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeGicw9mLZZOG5XtgTFh4Y6BUfuU3oYOjaBR-5Tehg6NoCctPctO4xjLosC5-MTSD-9zGOjFJG50c0j3dXgdsAtU&_nc_ohc=nnXXJ_iA_E0Q7kNvgG21bLO&_nc_ht=scontent.fmnl17-4.fna&oh=03_Q7cD1QH9IY_lE3awy_EHyJJ-_GaaO2IGi1AStcvPgcl_HE5qSg&oe=664EF65A">
                    <div class="layer"></div>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="section">
        <div class="section_container">
            <div class="row">
                <div class="contact-left">
                    <h1 class="section_title">Contact Me</h1>
                    <p><i class="ri-mail-line"></i> khylabautista02@email.com</p>
                    <p><i class="ri-phone-line"></i> +639298780830</p>
                    <p><i class="ri-map-pin-line"></i> Las Pinas Talon Tres, Urbanville</p>
                </div>
                <div class="contact_form">
                    <form action="https://api.web3forms.com/submit" method="POST">
                        <input type="hidden" name="access_key" value="20579234-aab0-4b11-8164-3c15f91dcd37">
                        <input type="text" name="name" placeholder="Your Name">
                        <input type="email" name="email" placeholder="Your Email">
                        <textarea name="message" placeholder="Your Message"></textarea>
                        <button type="submit">Send Message</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

</body>
</html>
