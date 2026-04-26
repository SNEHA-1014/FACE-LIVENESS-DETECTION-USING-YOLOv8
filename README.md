<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Face Liveness Detection using YOLOv8</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, Helvetica, sans-serif;
}

body{
    background:linear-gradient(135deg,#0f172a,#1e293b,#111827);
    color:white;
    line-height:1.6;
}

.container{
    width:90%;
    max-width:1100px;
    margin:auto;
    padding:40px 0;
}

header{
    text-align:center;
    padding:60px 20px;
}

header h1{
    font-size:3rem;
    margin-bottom:15px;
    color:#38bdf8;
}

header p{
    font-size:1.2rem;
    color:#cbd5e1;
    max-width:800px;
    margin:auto;
}

.section{
    background:rgba(255,255,255,0.05);
    margin:25px 0;
    padding:30px;
    border-radius:16px;
    box-shadow:0 8px 20px rgba(0,0,0,0.3);
    backdrop-filter:blur(10px);
}

.section h2{
    color:#22d3ee;
    margin-bottom:20px;
    font-size:2rem;
}

.features{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.card{
    background:#1e293b;
    padding:20px;
    border-radius:14px;
    transition:0.3s;
}

.card:hover{
    transform:translateY(-8px);
    background:#0f172a;
}

.card h3{
    color:#38bdf8;
    margin-bottom:10px;
}

ul{
    padding-left:20px;
}

code, pre{
    display:block;
    background:#0f172a;
    color:#22d3ee;
    padding:15px;
    border-radius:10px;
    overflow-x:auto;
    margin-top:10px;
}

footer{
    text-align:center;
    padding:30px;
    color:#94a3b8;
    margin-top:30px;
}

.btn{
    display:inline-block;
    margin-top:20px;
    padding:12px 25px;
    background:#38bdf8;
    color:#000;
    font-weight:bold;
    border-radius:10px;
    text-decoration:none;
    transition:0.3s;
}

.btn:hover{
    background:#22d3ee;
    transform:scale(1.05);
}

@media(max-width:768px){
    header h1{
        font-size:2.2rem;
    }
}
</style>
</head>

<body>

<div class="container">

<header>
    <h1>🚀 Face Liveness Detection using YOLOv8</h1>
    <p>
        Secure authentication with real-time AI-powered liveness detection. 
        Prevent spoofing attacks using photos, videos, or masks with the power of YOLOv8.
    </p>
    <a href="https://github.com/SNEHA-1014/FACE-LIVENESS-DETECTION-USING-YOLOv8" class="btn">🔗 View on GitHub</a>
</header>

<section class="section">
    <h2>📌 Overview</h2>
    <p>
        Face Liveness Detection is a crucial security layer for modern authentication systems.
        Traditional methods can be bypassed using fake photos or replay videos.
        This project uses <strong>YOLOv8</strong> for fast, accurate, and real-time face liveness detection.
    </p>
</section>

<section class="section">
    <h2>🌟 Features</h2>
    <div class="features">
        <div class="card">
            <h3>🎯 YOLOv8 Detection</h3>
            <p>Advanced deep learning model for high accuracy detection.</p>
        </div>

        <div class="card">
            <h3>⚡ Real-Time</h3>
            <p>Instant response with optimized performance.</p>
        </div>

        <div class="card">
            <h3>🔐 Anti-Spoofing</h3>
            <p>Stops unauthorized access using fake faces.</p>
        </div>

        <div class="card">
            <h3>🐍 Python Based</h3>
            <p>Fully developed in Python for easy customization.</p>
        </div>
    </div>
</section>

<section class="section">
    <h2>🧠 Tech Stack</h2>
    <ul>
        <li>Python</li>
        <li>YOLOv8</li>
        <li>OpenCV</li>
        <li>Deep Learning</li>
        <li>Computer Vision</li>
    </ul>
</section>

<section class="section">
    <h2>🔧 Installation</h2>
<pre>
git clone https://github.com/SNEHA-1014/FACE-LIVENESS-DETECTION-USING-YOLOv8.git
cd FACE-LIVENESS-DETECTION-USING-YOLOv8
pip install -r requirements.txt
</pre>
</section>

<section class="section">
    <h2>💡 Usage</h2>
<pre>
python main.py
</pre>
</section>

<section class="section">
    <h2>📁 Project Structure</h2>
<pre>
FACE-LIVENESS-DETECTION-USING-YOLOv8/
│── main.py
│── models/
│── utils/
│── requirements.txt
│── README.md
</pre>
</section>

<section class="section">
    <h2>🎯 Applications</h2>
    <ul>
        <li>Secure Login Systems</li>
        <li>Banking Authentication</li>
        <li>Mobile Face Unlock</li>
        <li>Office Attendance</li>
        <li>Fraud Prevention</li>
    </ul>
</section>

<section class="section">
    <h2>👩‍💻 Author</h2>
    <p><strong>Sneha</strong></p>
    <p>GitHub: @SNEHA-1014</p>
</section>

<footer>
    ⭐ If you like this project, give it a star on GitHub!
</footer>

</div>

</body>
</html>
