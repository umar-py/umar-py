<!-- Advanced HTML GitHub Profile -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Umar S. Pathan | Tech Innovator</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #0f0f0f;
            color: #ffffff;
            text-align: center;
        }
        h1 {
            font-size: 3em;
            margin-bottom: 0;
        }
        .glitch {
            font-size: 3.5em;
            color: #f0f;
            animation: glitch 1s infinite;
        }
        @keyframes glitch {
            0% { text-shadow: 2px 0 red, -2px 0 blue; }
            25% { text-shadow: -2px 0 red, 2px 0 blue; }
            50% { text-shadow: 2px 0 blue, -2px 0 red; }
            75% { text-shadow: -2px 0 blue, 2px 0 red; }
        }
        .sub-title {
            font-size: 1.5em;
            color: #ff6347;
            margin-top: -10px;
        }
        .profile-pic {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            border: 5px solid #ff6347;
            margin-top: 10px;
        }
        .icon {
            height: 40px;
            margin: 10px;
            transition: transform 0.2s;
        }
        .icon:hover {
            transform: scale(1.2);
        }
        .projects, .skills {
            margin: 30px 0;
        }
        .projects h2, .skills h2 {
            color: #ff6347;
        }
        a {
            color: #00ffff;
            text-decoration: none;
            font-weight: bold;
        }
        .neon-button {
            border: 2px solid #ff6347;
            padding: 10px 20px;
            text-decoration: none;
            color: #ff6347;
            font-size: 1.2em;
            border-radius: 10px;
            margin-top: 20px;
            transition: background 0.3s, color 0.3s;
        }
        .neon-button:hover {
            background-color: #ff6347;
            color: white;
        }
        .fun-facts {
            background-color: #191919;
            padding: 20px;
            margin-top: 20px;
            border-radius: 10px;
        }
        .fun-facts h2 {
            color: #00ffff;
        }
        .contact-me {
            margin: 50px 0;
            color: #ff6347;
        }
        .contact-me h2 {
            font-size: 2em;
        }
        footer {
            margin-top: 50px;
            font-size: 1.2em;
            color: #7f8c8d;
        }
    </style>
</head>
<body>

    <h1 class="glitch">Umar S. Pathan</h1>
    <p class="sub-title">Tech Innovator | AI Enthusiast | Blockchain Explorer</p>

    <img src="https://imgur.com/your-profile-pic.jpg" alt="Profile Picture" class="profile-pic" />

    <p>Student at Diablo Valley College | Student ID: 2158983</p>
    <p><strong>Birth Date:</strong> 22/07/2007 | <strong>Gender:</strong> Male</p>

    <section class="skills">
        <h2>🛠️ Skills & Technologies</h2>
        <p>
            <img class="icon" src="https://img.icons8.com/color/48/000000/python.png" alt="Python">
            <img class="icon" src="https://img.icons8.com/color/48/000000/javascript.png" alt="JavaScript">
            <img class="icon" src="https://img.icons8.com/color/48/000000/react-native.png" alt="React">
            <img class="icon" src="https://img.icons8.com/color/48/000000/nodejs.png" alt="Node.js">
            <img class="icon" src="https://img.icons8.com/color/48/000000/github.png" alt="GitHub">
            <img class="icon" src="https://img.icons8.com/color/48/000000/docker.png" alt="Docker">
        </p>
    </section>

    <section class="projects">
        <h2>🌍 My Projects</h2>
        <ul>
            <li>🚀 <a href="https://github.com/yourusername/ai-chatbot">AI Powered Chatbot</a> - Real-time AI conversational agent.</li>
            <li>⛓️ <a href="https://github.com/yourusername/blockchain-student-verification">Blockchain for Students</a> - Secure identity verification using blockchain technology.</li>
            <li>🔐 <a href="https://github.com/yourusername/cybersecure">CyberSecure</a> - Protect web apps from modern cyber threats.</li>
        </ul>
    </section>

    <a href="https://www.linkedin.com/in/yourlinkedinprofile" class="neon-button">💼 Connect on LinkedIn</a>

    <section class="fun-facts">
        <h2>🤯 Fun Facts</h2>
        <ul>
            <li>I built my first robot at the age of 12 🤖</li>
            <li>My dream is to become the youngest tech billionaire by 2030 💸</li>
            <li>I can debug code for hours fueled only by coffee ☕</li>
        </ul>
    </section>

    <section class="contact-me">
        <h2>📞 Contact Me</h2>
        <p>📧 Email: <a href="mailto:umarspathan@diablovalleycollege.edu">umarspathan@diablovalleycollege.edu</a></p>
        <p>🐦 Twitter: <a href="https://twitter.com/yourusername">@yourusername</a></p>
    </section>

    <footer>
        <p>🔥 “The only way to do great work is to love what you do.” – Steve Jobs 🔥</p>
        <p>Profile Views: <img src="https://komarev.com/ghpvc/?username=yourusername&color=brightgreen" alt="Profile Views"></p>
    </footer>

</body>
</html>
