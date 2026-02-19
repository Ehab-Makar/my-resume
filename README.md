<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ehab | Power BI Developer</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}

body {
    background-color: #f5f7fa;
    color: #1f2937;
    line-height: 1.6;
}

header {
    background: linear-gradient(135deg, #0f172a, #1e3a8a);
    color: white;
    padding: 80px 20px;
    text-align: center;
}

header h1 {
    font-size: 42px;
    font-weight: 700;
}

header p {
    margin-top: 15px;
    font-size: 18px;
    opacity: 0.9;
}

.btn {
    display: inline-block;
    margin-top: 25px;
    padding: 12px 25px;
    background: white;
    color: #1e3a8a;
    text-decoration: none;
    font-weight: 600;
    border-radius: 6px;
    transition: 0.3s ease;
}

.btn:hover {
    background: #e0e7ff;
}

section {
    padding: 70px 20px;
    max-width: 1100px;
    margin: auto;
}

.section-title {
    text-align: center;
    margin-bottom: 40px;
    font-size: 30px;
    font-weight: 600;
    color: #1e3a8a;
}

.about p {
    text-align: center;
    max-width: 800px;
    margin: auto;
}

.skills {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 20px;
    margin-top: 30px;
}

.skill-box {
    background: white;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.05);
    text-align: center;
}

.projects {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 25px;
}

.project-card {
    background: white;
    padding: 25px;
    border-radius: 8px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.05);
}

.project-card h3 {
    margin-bottom: 15px;
    color: #1e3a8a;
}

.contact {
    text-align: center;
}

footer {
    background: #0f172a;
    color: white;
    text-align: center;
    padding: 20px;
    margin-top: 40px;
    font-size: 14px;
}

@media(max-width: 600px) {
    header h1 {
        font-size: 28px;
    }
}
</style>
</head>

<body>

<header>
    <h1>Ehab</h1>
    <p>Power BI Developer & Data Analyst</p>
    <a href="#projects" class="btn">View My Work</a>
</header>

<section class="about">
    <h2 class="section-title">About Me</h2>
    <p>
        I am a Power BI Developer and Data Analyst with 8+ years of experience in Business Intelligence,
        KPI tracking, and performance optimization. I specialize in DAX, SQL, and data modeling,
        helping organizations transform raw data into strategic insights that drive real business impact.
    </p>
</section>

<section>
    <h2 class="section-title">Core Skills</h2>
    <div class="skills">
        <div class="skill-box">Power BI & DAX</div>
        <div class="skill-box">Power Query & ETL</div>
        <div class="skill-box">SQL & Data Modeling</div>
        <div class="skill-box">KPI & Performance Analytics</div>
        <div class="skill-box">Dashboard Design</div>
        <div class="skill-box">Automation & Optimization</div>
    </div>
</section>

<section id="projects">
    <h2 class="section-title">Projects</h2>
    <div class="projects">

        <div class="project-card">
            <h3>Executive KPI Dashboard</h3>
            <p>Built an interactive Power BI dashboard to provide real-time KPI visibility for leadership teams.
            Reduced manual reporting time by 40%.</p>
        </div>

        <div class="project-card">
            <h3>Contact Center Analytics</h3>
            <p>Developed performance tracking dashboards for FCR, SLA, and agent productivity,
            enabling data-driven coaching decisions.</p>
        </div>

        <div class="project-card">
            <h3>Financial Performance Dashboard</h3>
            <p>Automated financial reporting through integrated data models and optimized DAX measures,
            improving reporting accuracy.</p>
        </div>

    </div>
</section>

<section class="contact">
    <h2 class="section-title">Contact</h2>
    <p>Email: your@email.com</p>
    <p>LinkedIn: linkedin.com/in/yourprofile</p>
</section>

<footer>
    © 2026 Ehab | Power BI Developer
</footer>

</body>
</html>
