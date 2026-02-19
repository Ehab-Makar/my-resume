# my-resume<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ehab Makar | Senior BI & Data Analyst</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        .gradient-text { background: linear-gradient(90deg, #2563eb, #7c3aed); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
        .skill-card:hover { transform: translateY(-5px); transition: all 0.3s ease; }
    </style>
</head>
<body class="bg-gray-50 text-gray-800 font-sans">

    <header class="bg-white shadow-sm sticky top-0 z-50">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <h1 class="text-2xl font-bold gradient-text">Ehab Makar</h1>
            <nav class="hidden md:flex space-x-6 font-medium">
                <a href="#about" class="hover:text-blue-600">About</a>
                <a href="#experience" class="hover:text-blue-600">Experience</a>
                <a href="#skills" class="hover:text-blue-600">Skills</a>
                <a href="#contact" class="bg-blue-600 text-white px-4 py-2 rounded-lg hover:bg-blue-700">Contact Me</a>
            </nav>
        </div>
    </header>

    <section class="bg-white py-20">
        <div class="container mx-auto px-6 text-center">
            <h2 class="text-5xl font-extrabold mb-4">Senior Business Intelligence & <span class="text-blue-600">Data Analyst</span></h2>
            <p class="text-xl text-gray-600 max-w-2xl mx-auto mb-8">Over a decade of experience transforming vast datasets into strategic decisions across UAE government and private sectors.</p>
            <div class="flex justify-center space-x-4">
                <span class="bg-blue-100 text-blue-700 px-3 py-1 rounded-full text-sm font-semibold">Power BI Expert</span>
                <span class="bg-blue-100 text-blue-700 px-3 py-1 rounded-full text-sm font-semibold">SQL Developer</span>
                <span class="bg-blue-100 text-blue-700 px-3 py-1 rounded-full text-sm font-semibold">MIS Specialist</span>
            </div>
        </div>
    </section>

    <section id="about" class="py-16 container mx-auto px-6">
        <div class="bg-blue-600 rounded-2xl p-8 md:p-12 text-white shadow-xl">
            <h3 class="text-3xl font-bold mb-6 italic text-center">"Leveraging data to unlock innovative opportunities and solve critical challenges."</h3>
            <p class="text-lg leading-relaxed opacity-90">
                Seasoned specialist with deep expertise in Power BI, SQL, and automation. Proven track record in conducting root cause analyses and delivering actionable insights that drive business success in the vibrant landscape of the UAE.
            </p>
        </div>
    </section>

    <section id="experience" class="py-16 bg-gray-100">
        <div class="container mx-auto px-6">
            <h3 class="text-3xl font-bold mb-12 text-center underline decoration-blue-500">Professional Journey</h3>
            
            <div class="space-y-8">
                <div class="bg-white p-8 rounded-xl shadow-md border-l-4 border-blue-600">
                    <div class="flex justify-between items-start mb-4">
                        <div>
                            <h4 class="text-xl font-bold">Senior Business Intelligence & Data Analyst</h4>
                            <p class="text-blue-600 font-semibold">Ministry of Human Resources & Emiratisation (Reach3C)</p>
                        </div>
                        <span class="text-gray-500 font-medium">02/2024 – Present</span>
                    </div>
                    <ul class="list-disc ml-5 space-y-2 text-gray-700">
                        <li>Developed mission-critical BI reports and predictive models using SQL and Power BI.</li>
                        <li>Automated daily approvals/declines MIS reporting for key business metrics.</li>
                        <li>Identified and escalated governance risks to senior management.</li>
                    </ul>
                </div>

                <div class="bg-white p-8 rounded-xl shadow-md border-l-4 border-gray-400">
                    <div class="flex justify-between items-start mb-4">
                        <div>
                            <h4 class="text-xl font-bold">BI & Data Analyst</h4>
                            <p class="text-blue-600 font-semibold">MOHRE (Teleperformance)</p>
                        </div>
                        <span class="text-gray-500 font-medium">06/2021 – 01/2024</span>
                    </div>
                    <p class="text-gray-700">Built Power BI infrastructure and automated QA dashboards. Reduced workload through advanced technological solutions and Power Apps integration.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="skills" class="py-16 container mx-auto px-6">
        <h3 class="text-3xl font-bold mb-12 text-center">Technical Arsenal</h3>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <div class="skill-card bg-white p-6 rounded-xl shadow-lg text-center">
                <i class="fas fa-chart-line text-4xl text-blue-600 mb-4"></i>
                <h4 class="text-xl font-bold mb-2">BI & Reporting</h4>
                <p class="text-gray-600 text-sm">Power BI (DAX/Power Query), Looker Studio, SSRS, Paginated Reports.</p>
            </div>
            <div class="skill-card bg-white p-6 rounded-xl shadow-lg text-center">
                <i class="fas fa-database text-4xl text-purple-600 mb-4"></i>
                <h4 class="text-xl font-bold mb-2">Data Management</h4>
                <p class="text-gray-600 text-sm">Advanced SQL (T-SQL), ETL Processes, Star/Snowflake Schemas.</p>
            </div>
            <div class="skill-card bg-white p-6 rounded-xl shadow-lg text-center">
                <i class="fas fa-robot text-4xl text-green-600 mb-4"></i>
                <h4 class="text-xl font-bold mb-2">Automation</h4>
                <p class="text-gray-600 text-sm">Power Automate, Power Apps, Google Apps Script, MS Planner Integration.</p>
            </div>
        </div>
    </section>

    <footer id="contact" class="bg-gray-900 text-white py-12">
        <div class="container mx-auto px-6 text-center">
            <h3 class="text-2xl font-bold mb-4">Let's Connect</h3>
            <p class="mb-6 text-gray-400">Based in Dubai, UAE | Egyptian National</p>
            <div class="flex justify-center space-x-6 text-2xl">
                <a href="mailto:Ehab.Makar.2017@gmail.com" class="hover:text-blue-400"><i class="fas fa-envelope"></i></a>
                <a href="https://www.linkedin.com/public-profile/settings?l" target="_blank" class="hover:text-blue-400"><i class="fab fa-linkedin"></i></a>
                <a href="tel:+971562330601" class="hover:text-blue-400"><i class="fas fa-phone"></i></a>
            </div>
            <p class="mt-10 text-sm text-gray-500">&copy; 2026 Ehab Makar. Created for Professional Review.</p>
        </div>
    </footer>

</body>
</html>
