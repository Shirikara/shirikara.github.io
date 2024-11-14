<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to My Webpage</title>
    <style>
        /* Full-page background color */
        body {
            background-color: #f0f2f5; /* Light background color */
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            font-family: Arial, sans-serif;
        }

        /* Centered container for content */
        .content-container {
            max-width: 600px;
            background-color: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Light shadow effect */
            text-align: center;
        }

        /* Social icon container */
        .social-container {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 10px;
            margin-top: 20px;
        }

        /* Profile picture and sourdough bread image styling */
        img {
            border-radius: 8px;
            margin: 10px 0;
        }

        /* Hover effect for icons */
        .social-container a:hover img {
            transform: scale(1.1); /* Zoom effect on hover */
        }

        /* Link styling */
        a {
            color: #0a66c2; /* LinkedIn blue for links */
            text-decoration: none;
        }
        
        /* Title styling */
        h1 {
            color: #333;
        }
    </style>
</head>
<body>
    <div class="content-container">
        <h1>Welcome to my webpage!</h1>
        <img src="https://github.com/Shirikara/shirikara.github.io/raw/main/wiz%20(388).jpg" alt="My Profile Picture" width="200">

        <p>I am Shiri, a Ph.D. student at the Weizmann Institute working on breast cancer and single-cell proteomics.</p>
        <p>Analyzing human samples from the clinic makes me feel closer to the applicational opportunities of basic science.</p>

        <p>💻 Data-driven person specializing in R, Python, and MATLAB</p>
        <p>🔬 5+ years of experience in mass spectrometry</p>
        <p>✏️ Part-time scientific writer at Davison Institute, believing that promoting science education is as important as being a scientist.</p>
        <p>🌱 I am a plant-lover</p>
        <p>🧘 I enjoy practicing yoga</p>
        <p>🍞 Since I have my own sourdough, "Tamagotchi," I haven't bought a bread loaf even once.</p>

        <p>📝 Check out my latest preprint in <a href="https://www.biorxiv.org/content/10.1101/2024.11.01.621461v1" target="_blank">_BiorXiv_</a></p>

        <hr>

        <div class="social-container">
            <!-- LinkedIn icon -->
            <p>Here is my LinkedIn account:</p>
            <a href="https://www.linkedin.com/in/shiri-karagach-73b381138/" target="_blank">
                <img src="https://github.com/user-attachments/assets/6d8a0342-dbf6-4261-9ab9-8f4222535718" alt="LinkedIn Logo" width="40">
            </a>
            
            <!-- Twitter (X) icon -->
            <p>Here is my Twitter account:</p>
            <a href="https://twitter.com/SKaragach" target="_blank">
                <img src="https://img.freepik.com/free-vector/new-twitter-logo-x-icon-black-background_1017-45427.jpg?t=st=1730800278~exp=1730803878~hmac=5448a6040160db7e9baca77a228b669ebc855fd20239ae9fa911f7af86f516e2&w=996" alt="Twitter Logo" width="40">
            </a>
        </div>

        <p>My sourdough bread ❤️</p>
        <img src="https://github.com/Shirikara/shirikara.github.io/raw/main/IMG_20230601_082702.jpg" alt="My Sourdough Bread" width="200">

        <p>This webpage was created as part of the <a href="https://github.com/szabgab/wis-python-course-2024-11" target="_blank">Python course</a><br>
        given by: <a href="https://szabgab.com/" target="_blank">szabgab</a> <br>
        at the <a href="https://www.weizmann.ac.il/pages/" target="_blank">Weizmann Institute of Science</a></p>
    </div>
</body>
</html>
