HTML

<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>🏆 Улугбек - Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <nav class="navbar">
        <div class="logo">Portfolio</div>
        <ul>
            <li><a href="#home" class="active">Главная</a></li>
            <li><a href="#about">Обо мне</a></li>
            <li><a href="#skills">Навыки</a></li>
            <li><a href="#projects">Проекты</a></li>
            <li><a href="#contacts">Контакты</a></li>
        </ul>
    </nav>

    <section id="home" class="hero section">
        <div class="left fade-in">
            <h1><span>Улугбек Кабилов</span></h1>
            <p>Учени́к 9-го класса, молодой программист</p>
            <div class="buttons">
                <a href="https://t.me/kobilovv701" class="btn">Связаться</a>
                <a href="https://github.com/ulugbekkabilov777-hue" class="btn btn-outline">GitHub</a>
            </div>
        </div>
        <div class="right fade-in delay-1">
            <div class="img-container">
                <img src="https://i.ibb.co/XkC7CNw9/photo-2025-12-03-17-35-54.jpg" alt="Ulugbek Kabilov">
            </div>
        </div>
    </section>

    <section id="about" class="section about-section">
        <h2 class="fade-in">Обо мне</h2>
        <p class="fade-in delay-1">
            Меня зовут <strong>Улугбек Кабилов</strong>. Я учусь в <strong>Mars IT School</strong> и начинающий разработчик. Для меня программирование — это создание современных систем, которые работают быстро, выглядят современно и приносят реальную пользу.
        </p>
        <p class="fade-in delay-2">
            Я увлекаюсь веб-разработкой, дизайном интерфейсов и архитектурой приложений. Моя цель — объединять навыки инженера и дизайнера, чтобы создавать продукты, которые облегчают жизнь людей.
        </p>
        <p class="fade-in delay-3">
            Навыки и интересы в программировании: <strong>UI/UX, Performance, Web Animations, Design Systems, Accessibility, Clean Code, Problem Solving, Full-Stack, Open Source, AI & Automation</strong>.
        </p>

        <div class="interests">
            <h3 class="fade-in delay-4">Шахматы</h3>
            <p class="fade-in delay-4-1">Шахматы занимают особое место среди моих увлечений. Люблю играть и практикую на платформе Chess.com.</p>

            <h3 class="fade-in delay-5">Бизнес</h3>
            <p class="fade-in delay-5-1">Я интересуюсь бизнесом, уверен в своих возможностях и стремлюсь стать успешным бизнесменом в будущем.</p>

            <h3 class="fade-in delay-6">Чемпион</h3>
            <p class="fade-in delay-6-1">С 4 лет я занимаюсь дзюдо и тренируюсь 5 раз в неделю. С Божьей помощью стараюсь стать чемпионом Узбекистана, Азии и мира.</p>
        </div>
    </section>

    <section id="skills" class="section">
        <h2 class="fade-in">Навыки</h2>
        <div class="skills-container fade-in delay-1">
            <div class="skill"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-original.svg" alt="HTML"><p>HTML</p></div>
            <div class="skill"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/css3/css3-original.svg" alt="CSS"><p>CSS</p></div>
            <div class="skill"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg" alt="JS"><p>JavaScript</p></div>
            <div class="skill"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" alt="Python"><p>Python</p></div>
            <div class="skill"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/cplusplus/cplusplus-original.svg" alt="C++"><p>C++</p></div>
            <div class="skill"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/java/java-original.svg" alt="Java"><p>Java</p></div>
            <div class="skill"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/azuresqldatabase/azuresqldatabase-original.svg" alt="SQL"><p>SQL</p></div>
            <div class="skill"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-original.svg" alt="PostgreSQL"><p>PostgreSQL</p></div>
        </div>
    </section>

    <section id="contacts" class="section">
        <h2 class="fade-in">Контакты</h2>
        <div class="contacts-container fade-in delay-1">
            <a href="https://t.me/kobilovv701">Telegram</a>
            <a href="https://www.instagram.com/__kabilovv/">Instagram</a>
            <a href="https://github.com/ulugbekkabilov777-hue">GitHub</a>
            <a href="#">Email</a>
            <a href="#">Chess.com</a>
            <a href="#">Lichess</a>
        </div>
    </section>

    <script src="script.js"></script>
</body>
</html>

CSS

*{
    margin: 0px; 
    padding:0; 
    box-sizing:border-box;
}

body{
    font-family:'Arial', sans-serif;
    background: linear-gradient(135deg, #0d0d0d, #111);
    color:rgb(81, 80, 80);
    scroll-behavior:smooth;
}

a{
    text-decoration:none; 
    color:white;
}


.navbar{
    display:flex; 
    justify-content:space-between; 
    align-items:center;
    padding:15px 50px; 
    background:rgba(20,20,20,0.9); 
    position:sticky; 
    top:0; 
    z-index:1000;
    box-shadow:0 0 25px rgba(0,255,255,0.2); 
    border-radius:0 0 18px 18px;
}
.navbar .logo{
    font-weight:bold; 
    font-size:22px; 
    color:rgb(0, 255, 255);
}

.navbar ul{
    list-style:none; 
    display:flex; 
    gap:35px;
}

.navbar a{
    transition:.3s; 
    font-size:18px;
}

.navbar a:hover, .navbar a.active{
    color:cyan; 
    font-weight:bold;
}


.hero{
    display:flex; 
    justify-content:space-between; 
    align-items:center;
    width:90%; 
    margin:60px auto; 
    padding:40px; 
    background:#111;
    border-radius:22px; 
    box-shadow:0 0 50px rgba(0,255,255,0.2);
}

.hero .left h1{
    font-size:42px; 
    margin-bottom:10px;
}

.hero .left h1 span{
    color:cyan;
}

.hero .left p{
    font-size:20px; 
    color:#ccc;
}

.buttons{
    display:flex; 
    gap:20px; 
    margin-top:20px; 
    flex-wrap:wrap;
}

.btn{
    padding:12px 25px; 
    border-radius:12px; 
    text-decoration:none; 
    color:cyan; 
    background:#1f1f1f; 
    transition:.3s;
}

.btn:hover{
    background:cyan; 
    color:#000;
}

.btn-outline{
    border:2px solid cyan; 
    background:transparent; 
    color:cyan;
}
.btn-outline:hover{
    background:cyan; 
    color:#000;
}

.right .img-container{
    width:200px; 
    height:200px;
    border-radius:50%; 
    overflow:hidden; 
    box-shadow:0 0 30px cyan; 
    transition:.3s;
}

.right .img-container img{
    width:100%; 
    height:100%; 
    object-fit:cover; 
    transition:.3s;
}

.right .img-container:hover img{
    transform:scale(1.1);
}


.about-section {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.7;
    color: #e0e0e0;
}

.about-section h2 {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    font-size: 32px;
    color: cyan;
    margin-bottom: 20px;
}

.about-section p {
    font-size: 18px;
    margin-bottom: 15px;
}

.about-section strong {
    color: #00ffff; 
}


.skills-container{
    display:flex; 
    gap:30px; 
    flex-wrap:wrap;
}

.skill{
    text-align:center; 
    cursor:pointer; 
    transition:.3s;
}

.skill img{
    width:100px; 
    height:100px;
}

.skill:hover{
    transform:scale(1.1);
}

.projects-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr)); 
    gap:25px;
}

.project{
    background:#1a1a1a; 
    padding:20px; 
    border-radius:12px; 
    box-shadow:0 0 15px rgba(0,255,255,0.1); 
    transition:.3s;
}

.project:hover{
    transform:scale(1.03);
}

.contacts-container{
    display:flex; 
    flex-wrap:wrap; 
    gap:15px; 
    margin-top:20px;
}

.contacts-container a{
    padding:10px 15px; 
    border-radius:10px; 
    color:cyan; 
    background:#1f1f1f; 
    transition:.3s;
}

.contacts-container a:hover{
    background:cyan; 
    color:#000;
}

@media(max-width:900px){
    .hero{flex-direction:column; text-align:center;}
    .right{margin-top:25px;}
}

.section {
    width:90%; 
    margin:60px auto; 
    padding:40px; 
    background:#111; 
    border-radius:22px; 
    box-shadow:0 0 40px rgba(0,255,255,0.15); 


    opacity:1; 
    transform:translateY(0); 
    transition:none; 
}


JS


document.addEventListener("DOMContentLoaded", () => {
    const fadeElements = document.querySelectorAll('.fade-in');

    const observerOptions = { threshold: 0.2 };

    const fadeObserver = new IntersectionObserver((entries, observer) => {
        entries.forEach(entry => {
            if(entry.isIntersecting){
                entry.target.classList.add('visible');
                observer.unobserve(entry.target);
            }
        });
    }, observerOptions);

    fadeElements.forEach(el => fadeObserver.observe(el));
});





