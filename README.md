
<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        body {
            font-family: Arial, sans-serif;
            background: #080d18;
            color: white;
        }

        header {
            background: #101827;
            padding: 20px 8%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
        }

        .logo {
            color: #00bfff;
            font-size: 25px;
            font-weight: bold;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
        }

        nav a:hover {
            color: #00bfff;
        }

        .hero {
            min-height: 80vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 30px;
        }

        .hero h1 {
            font-size: 45px;
            margin-bottom: 15px;
        }

        .hero span {
            color: #00bfff;
        }

        .hero p {
            color: #aaa;
            font-size: 18px;
        }

        .btn {
            display: inline-block;
            margin-top: 25px;
            padding: 12px 25px;
            background: #00bfff;
            color: #080d18;
            text-decoration: none;
            border-radius: 8px;
            font-weight: bold;
        }

        section {
            padding: 70px 10%;
            text-align: center;
        }

        h2 {
            color: #00bfff;
            font-size: 30px;
            margin-bottom: 25px;
        }

        .card {
            background: #101827;
            padding: 25px;
            margin: 15px auto;
            max-width: 600px;
            border-radius: 12px;
            border: 1px solid #1c3550;
        }

        .card p {
            color: #ccc;
            line-height: 1.8;
        }

        .skills {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 15px;
        }

        .skill {
            background: #142b43;
            color: #00bfff;
            padding: 15px 25px;
            border-radius: 8px;
        }

        footer {
            background: #101827;
            padding: 25px;
            text-align: center;
            color: #aaa;
        }
    </style>
</head>

<body>

    <header>
        <div class="logo">My Portfolio</div>

        <nav>
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#skills">Skills</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <div class="hero" id="home">
        <h1>Hello, I'm <span>My Name</span></h1>
        <p>Welcome to my personal portfolio website</p>
        <a href="#about" class="btn">Explore More</a>
    </div>

    <section id="about">
        <h2>About Me</h2>
        <div class="card">
            <p>
                สวัสดีค่ะ ฉันชื่อ นางสาวณฤพาน กฤษณปาณี
                กำลังศึกษาอยู่ชั้นมัธยมศึกษาปีที่ 6/13
                เว็บไซต์นี้จัดทำขึ้นเพื่อแนะนำตัวเอง
                และรวบรวมผลงานต่าง ๆ ของฉัน
            </p>
        </div>
    </section>

    <section id="skills">
        <h2>My Skills</h2>
        <div class="skills">
            <div class="skill">HTML</div>
            <div class="skill">CSS</div>
            <div class="skill">JavaScript</div>
            <div class="skill">Creativity</div>
        </div>
    </section>

    <section id="projects">
        <h2>My Projects</h2>
        <div class="card">
            <h3>Project 01</h3>
            <p>ผลงานการสร้างเว็บไซต์ด้วยภาษา HTML และ CSS</p>
        </div>

        <div class="card">
            <h3>Project 02</h3>
            <p>ผลงานการออกแบบเว็บไซต์และเทคโนโลยี</p>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <div class="card">
            <p>Email: example@gmail.com</p>
            <p>Facebook: My Facebook</p>
            <p>Instagram: My Instagram</p>
        </div>
    </section>

    <footer>
        <p>© 2026 My Portfolio | Created by Me</p>
    </footer>

</body>
</html>
