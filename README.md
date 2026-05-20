<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CV - Zisan Islam Chowdhury</title>
    <!-- Font Awesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary-color: #1a2a6c; /* Navy Blue */
            --accent-color: #007bff;
            --text-dark: #333;
            --text-light: #666;
            --bg-color: #f8f9fa;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-dark);
            line-height: 1.6;
            margin: 0;
            padding: 20px;
        }

        .cv-wrapper {
            max-width: 900px;
            margin: 0 auto;
            background: white;
            padding: 40px;
            box-shadow: 0 4px 20px rgba(0,0,0,0.08);
            border-radius: 10px;
            border-top: 8px solid var(--primary-color);
        }

        header {
            text-align: center;
            border-bottom: 2px solid #eee;
            padding-bottom: 20px;
            margin-bottom: 30px;
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
            color: var(--primary-color);
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        .contact-info {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 15px;
            margin-top: 10px;
            font-size: 0.95rem;
            color: var(--text-light);
        }

        .contact-info span i {
            color: var(--accent-color);
            margin-right: 5px;
        }

        section {
            margin-bottom: 25px;
        }

        h2 {
            font-size: 1.25rem;
            color: var(--primary-color);
            border-bottom: 2px solid var(--accent-color);
            display: inline-block;
            margin-bottom: 15px;
            padding-right: 20px;
        }

        /* Table Styling */
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 10px;
        }

        th {
            background-color: #f1f1f1;
            text-align: left;
            padding: 12px;
            color: var(--primary-color);
        }

        td {
            padding: 12px;
            border-bottom: 1px solid #eee;
        }

        /* Skills Tags */
        .skills-container {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            padding: 0;
            list-style: none;
        }

        .skills-container li {
            background: var(--primary-color);
            color: white;
            padding: 6px 15px;
            border-radius: 20px;
            font-size: 0.9rem;
            transition: transform 0.2s;
        }

        .skills-container li:hover {
            transform: translateY(-3px);
            background: var(--accent-color);
        }

        /* Project & Strengths List */
        .custom-list {
            padding-left: 20px;
        }

        .custom-list li {
            margin-bottom: 8px;
        }

        .declaration {
            font-style: italic;
            font-size: 0.9rem;
            color: var(--text-light);
            margin-top: 40px;
            padding: 15px;
            background: #fdfdfd;
            border-left: 4px solid #ddd;
        }

        .signature {
            margin-top: 20px;
            font-weight: bold;
            color: var(--primary-color);
        }

        /* Responsive Design */
        @media (max-width: 600px) {
            .cv-wrapper { padding: 20px; }
            header h1 { font-size: 1.8rem; }
            .contact-info { flex-direction: column; align-items: center; gap: 5px; }
            th, td { padding: 8px; font-size: 0.85rem; }
        }
    </style>
</head>
<body>

    <div class="cv-wrapper">
        
        <header>
            <h1>Zisan Islam Chowdhury</h1>
            <div class="contact-info">
                <span><i class="fas fa-envelope"></i> zisanislamchowdhury@gmail.com</span>
                <span><i class="fas fa-phone"></i> 01887476092</span>
                <span><i class="fas fa-map-marker-alt"></i> Chittagong, Bangladesh</span>
            </div>
        </header>

        <section>
            <h2><i class="fas fa-bullseye"></i> Career Objective</h2>
            <p>To build a successful career as a Computer Science Engineer by gaining practical experience, improving technical skills, and contributing to innovative projects.</p>
        </section>

        <section>
            <h2><i class="fas fa-graduation-cap"></i> Educational Qualification</h2>
            <table>
                <thead>
                    <tr>
                        <th>Degree</th>
                        <th>Institution</th>
                        <th>Year</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td><strong>B.Sc in CSE</strong></td>
                        <td>Premier University</td>
                        <td>2024 - Present</td>
                    </tr>
                    <tr>
                        <td><strong>HSC</strong></td>
                        <td>Enayet Bazar Mohila College</td>
                        <td>2023</td>
                    </tr>
                    <tr>
                        <td><strong>SSC</strong></td>
                        <td>Jamalkhan Kusumkumari City Corp. Girls High School</td>
                        <td>2021</td>
                    </tr>
                </tbody>
            </table>
        </section>

        <section>
            <h2><i class="fas fa-laptop-code"></i> Technical Skills</h2>
            <ul class="skills-container">
                <li>C Programming</li>
                <li>Basic Data Structures</li>
                <li>HTML5</li>
                <li>Problem Solving</li>
                <li>Git (Version Control)</li>
            </ul>
        </section>

        <section>
            <h2><i class="fas fa-project-diagram"></i> Projects</h2>
            <ul class="custom-list">
                <li><strong>Student Result Management System:</strong> Developed using C to manage student academic records efficiently.</li>
                <li><strong>Simple Calculator:</strong> A CLI-based application for basic mathematical operations.</li>
            </ul>
        </section>

        <section>
            <h2><i class="fas fa-star"></i> Strengths</h2>
            <ul class="custom-list">
                <li>Hardworking & Dedicated</li>
                <li>Quick Learner & Adaptable</li>
                <li>Effective Communication Skills</li>
            </ul>
        </section>

        <div class="declaration">
            <p>I hereby declare that the above information is true and correct to the best of my knowledge.</p>
            <div class="signature">
                <p>Signature: ____________________<br>
                Zisan Islam Chowdhury</p>
            </div>
        </div>

    </div>

</body>
</html>
# portfolio-
