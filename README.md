<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Computer Minds - YouTube Channel</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #f8f9fa;
    }

    header {
      background-color: #1e3a8a;
      color: white;
      padding: 40px 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2.5em;
    }

    header p {
      margin: 8px 0;
      color: #cbd5e1;
    }

    .stats {
      margin-top: 10px;
      font-size: 14px;
    }

    .category-bar {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 15px;
      background-color: white;
      box-shadow: 0 2px 4px rgba(0,0,0,0.05);
    }

    .category-bar button {
      margin: 5px;
      padding: 10px 18px;
      border: none;
      background-color: #e0e7ff;
      color: #1e3a8a;
      border-radius: 20px;
      cursor: pointer;
      font-weight: 500;
    }

    .category-bar button:hover {
      background-color: #c7d2fe;
    }

    .video-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 20px;
      padding: 20px;
    }

    .video-card {
      background-color: white;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 2px 10px rgba(0,0,0,0.05);
      transition: transform 0.2s ease;
    }

    .video-card:hover {
      transform: translateY(-5px);
    }

    .video-thumb {
      position: relative;
    }

    .video-thumb img {
      width: 100%;
      display: block;
    }

    .video-duration {
      position: absolute;
      bottom: 8px;
      right: 8px;
      background: rgba(0,0,0,0.75);
      color: white;
      font-size: 12px;
      padding: 2px 6px;
      border-radius: 3px;
    }

    .video-info {
      padding: 15px;
    }

    .video-info h3 {
      margin: 0 0 10px 0;
      font-size: 16px;
    }

    .video-info p {
      font-size: 14px;
      color: #555;
    }

    .video-meta {
      font-size: 12px;
      color: #888;
      margin-top: 8px;
    }

    footer {
      text-align: center;
      padding: 20px;
      color: #666;
    }
  </style>
</head>
<body>

  <header>
    <h1>Computer-Minds</h1>
    <p>Exploring technology, programming, and innovation</p>
    <div class="stats">178 videos • 322 subscribers • 1,840,724 views</div>
    <div style="background-color: #1e3488; text-align: center; padding: 10px;">
    <a href="https://www.youtube.com/@computer-minds" target="_blank" style="color: #ffffff; font-weight: bold; font-size: 16px; text-decoration: none;">
      🔗 Visit Our Channel on YouTube
    </a>
	 </div>
  </header>

  <!-- Category Bar -->
  <div class="category-bar">
    <button onclick="filterCategory('all')">All Videos</button>
    <button onclick="filterCategory('programming')">Programming</button>
    <button onclick="filterCategory('ml')">AI & Machine Learning</button>
    <button onclick="filterCategory('web')">Web Development</button>
    <button onclick="filterCategory('cybersecurity')">Cybersecurity</button>
    <button onclick="filterCategory('tutorials')">Tutorials</button>
	<button onclick="filterCategory('computer')">Computer knowlge</button>
  </div>

  <!-- Video Grid -->
  <div class="video-grid" id="videoGrid">
    <!-- Example video card 1 -->
    <div class="video-card web">
      <div class="video-thumb">
        <iframe width="100%" height="200" src="https://www.youtube.com/embed/QIp5nR2NWvg" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <div class="video-duration">03:15</div>
      </div>
      <div class="video-info">
        <h3>Web Design Crash Course in 3 Minutes | Learn HTML, CSS & JavaScript Fast!</h3>
        <p>🎯 *Kickstart your Web Design journey in just 3 minutes!*</p>
        <div class="video-meta">554 views • 3 days ago</div>
      </div>
    </div>

    <!-- Example video card 2 -->
    <div class="video-card tutorials">
      <div class="video-thumb">
        <iframe width="100%" height="200" src="https://www.youtube.com/embed/pntXs70f6QE" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <div class="video-duration">22:18</div>
      </div>
      <div class="video-info">
        <h3>Operating Systems & Software Everything You Need To Know</h3>
        <p>Operating Systems & Software: Windows vs. macOS vs. Linux + Best Free OS & Essential Software </p>
        <div class="video-meta">379 views • 2 monts ago</div>
      </div>
    </div>

    <!-- Example video card 3 -->
    <div class="video-card programming">
      <div class="video-thumb">
        <iframe width="100%" height="200" src="https://www.youtube.com/embed/tnM5YRvKAvI" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <div class="video-duration">31:05</div>
      </div>
      <div class="video-info">
        <h3>Why Programmers Love Linux! (Top Reasons to Use Linux in 2025)</h3>
        <p>Why is Linux so popular among programmers?* If you’ve ever wondered why developers prefer Linux over Windows or macOS, this video is for you! .</p>
        <div class="video-meta">7.8K views • 1 week ago</div>
      </div>
    </div>
<!-- Example video card 4 -->
    <div class="video-card cybersecurity">
      <div class="video-thumb">
        <iframe width="100%" height="200" src="https://www.youtube.com/embed/WUjsJ46VIII" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <div class="video-duration">31:05</div>
      </div>
      <div class="video-info">
        <h3>🔰 Cybersecurity & Ethical Hacking for Beginners: Stay Safe Online in 2025! 🔐)</h3>
        <p>Are you worried about online security? In this in-depth 33-minute video, we cover everything you need to know about *Cybersecurity & Ethical Hacking* in 2025! From *Wi-Fi hacking* to **phishing scams**, **ransomware attacks**, and the best ways to protect yourself online, we've got you covered. .</p>
        <div class="video-meta">82 views • Apr 2, 2025</div>
      </div>
    </div>
<!-- Example video card 5 -->
    <div class="video-card tutorials ">
      <div class="video-thumb">
        <iframe width="100%" height="200" src="https://www.youtube.com/embed/XbqZ_QGlsjU" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <div class="video-duration">03:06</div>
      </div>
      <div class="video-info">
        <h3>How to Dual Boot Windows and Linux–Easy Step-by-Step Guide</h3>
        <p>Want to run both Windows and Linux on the same PC? In this quick 3-minute guide, I'll show you how to dual boot Windows and Linux easily. Learn how to partition your disk, install Linux alongside Windows, and choose your OS at startup.
</p>
        <div class="video-meta">279 views •27 fed 2025</div>
      </div>
    </div>
<!-- Example video card  -->
    <div class="video-card computer">
      <div class="video-thumb">
        <iframe width="100%" height="200" src="https://www.youtube.com/embed/cmH5O2RGZoA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <div class="video-duration">01:13</div>
      </div>
      <div class="video-info">
        <h3>Top 5 Free Operating System Alternatives You Must Try! | Best Open-Source OS</h3>
        <p>Top 5 Free Operating System Alternatives* that offer excellent performance, security, and customization. Whether you're a developer, student, or just want to try something new, these open-source OS options are worth checking out!</p>
        <div class="video-meta">187 views • 24 feb 2025</div>
      </div>
    </div>
<!-- Example video card  -->
    <div class="video-card cybersecurity">
      <div class="video-thumb">
        <iframe width="100%" height="200" src="https://www.youtube.com/embed/E9qEJv_Ai2I" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <div class="video-duration">06:21</div>
      </div>
      <div class="video-info">
        <h3>How Hackers Hack Wi-Fi & How to Secure Yours! 🔥 (Must-Watch)</h3>
        <p>Unlock the secrets of Wi-Fi security in just 8 minutes! In this engaging video, we reveal how hackers exploit vulnerable networks and share essential tips to protect yours from potential attacks. </p>
        <div class="video-meta">76 views • march 13 2025</div>
      </div>
    </div>
<!-- Example video card  -->
    <div class="video-card computer ">
      <div class="video-thumb">
        <iframe width="100%" height="200" src="https://www.youtube.com/embed/OpPbTNuPwXM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <div class="video-duration">03:48</div>
      </div>
      <div class="video-info">
        <h3>Routers vs. Switches:What’s the Difference? Explained in 3 Minutes!</h3>
        <p>🔹 Topics Covered:
✔ What is a Router?
✔ What is a Switch?</p>
        <div class="video-meta">136 views • 4 months ago</div>
      </div>
    </div>
<!-- Example video card  -->
    <div class="video-card computer ">
      <div class="video-thumb">
        <iframe width="100%" height="200" src="https://www.youtube.com/embed/VchLQ9neA2Q" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <div class="video-duration">03:15</div>
      </div>
      <div class="video-info">
        <h3>What is a Motherboard? Parts & Functions Explained!(Ultimate Guide)</h3>
        <p>Unlock the secrets of your computer's *motherboard* in our latest video, "Motherboards 101: Parts & Functions Explained!" </p>
        <div class="video-meta">118 views • 3 months ago</div>
      </div>
    </div>
<!-- Example video card  -->
    <div class="video-card computer ">
      <div class="video-thumb">
        <iframe width="100%" height="200" src="https://www.youtube.com/embed/LdJXkKDXWWY" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <div class="video-duration">04:30</div>
      </div>
      <div class="video-info">
        <h3>Best Budget Laptops for Students in 2025 💻📚 | Top Picks Under ₹40,000! </h3>
        <p>📌 Laptops Covered:
1️⃣ HP 15s
2️⃣ Lenovo IdeaPad 1
3️⃣ Acer Aspire 3
4️⃣ ASUS Vivobook Go
5️⃣ Infinix InBook Y1</p>
        <div class="video-meta">110 views • 1 months ago</div>
      </div>
    </div>
<!-- Example video card  -->
    <div class="video-card tutorials">
      <div class="video-thumb">
        <iframe width="100%" height="200" src="https://www.youtube.com/embed/oxIIWf7Ku5I" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <div class="video-duration">05:21</div>
      </div>
      <div class="video-info">
        <h3>Silicon Carbon Battery Explained – Future of Smartphone Charging in 2025!</h3>
        <p>Is naye battery tech se smartphones honge super fast charging wale, zyada backup ke saath aur patle design ke sath!
</p>
        <div class="video-meta"> 81views • 3 months ago</div>
      </div>
    </div>
<!-- Example video card  -->
    <div class="video-card computer ">
      <div class="video-thumb">
        <iframe width="100%" height="200" src="https://www.youtube.com/embed/ep-LBLcg8Ck" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <div class="video-duration">02:33</div>
      </div>
      <div class="video-info">
        <h3>Best Antivirus Software for PC in 2025 + Step-by-Step Installation Guide!</h3>
        <p>🔹 Top Antivirus Software in 2025:
✅ Norton 360 – Best overall protection
✅ Bitdefender – Lightweight & powerful
✅ McAfee – Strong real-time scanning
✅ Avast – Best free antivirus
✅ TotalAV – Budget-friendly with VPN</p>
        <div class="video-meta"> 68views • 3 months ago</div>
      </div>
    </div>
<!-- Example video card  -->
    <div class="video-card computer ">
      <div class="video-thumb">
        <iframe width="100%" height="200" src="https://www.youtube.com/embed/WcdLgrIpdic" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <div class="video-duration">04:07</div>
      </div>
      <div class="video-info">
        <h3>How to Install Windows 10/11 from USB in Just 4 Minutes! (Step-by-Step Guide)</h3>
        <p>Want to install Windows 10 or Windows 11 using a USB? In this quick 3-minute tutorial, I’ll show you the step-by-step process to create a bootable USB, boot from it, and install Windows effortlessly. Perfect for beginners and tech enthusiasts!</p>
        <div class="video-meta">64 views • 4 months ago</div>
      </div>
    </div>
<!-- Example video card  -->
    <div class="video-card tutorials ">
      <div class="video-thumb">
        <iframe width="100%" height="200" src="https://www.youtube.com/embed/HLOpt9pSS0A" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <div class="video-duration">06:52</div>
      </div>
      <div class="video-info">
        <h3>Operating System Explained 🔥 | Functions, History, Storage & System Structure | OS Basics 2025</h3>
        <p>✅ What is an Operating System?
✅ The History of Operating Systems
✅ Storage Structure in OS
✅ Functions of an Operating System
✅ Computer System Organization</p>
        <div class="video-meta">60 views • 26 may 2025</div>
      </div>
    </div>
<!-- Example video card  -->
    <div class="video-card computer ">
      <div class="video-thumb">
        <iframe width="100%" height="200" src="https://www.youtube.com/embed/uSYvJ5a6I-I" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <div class="video-duration">22:25</div>
      </div>
      <div class="video-info">
        <h3>Computer Networking & Internet Explained: IP Addresses,Routers,Wi-Fi,VPN & More!</h3>
        <p></p>
        <div class="video-meta">55 views •mar 12 2025 </div>
      </div>
    </div>
<!-- Example video card  -->
    <div class="video-card computer ">
      <div class="video-thumb">
        <iframe width="100%" height="200" src="https://www.youtube.com/embed//_2KsXJfT-g0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <div class="video-duration">02:28</div>
      </div>
      <div class="video-info">
        <h3>RAM vs ROM: What’s the Difference?</h3>
        <p>Ever wondered how RAM & ROM impact your computer's speed and proformance?</p>
        <div class="video-meta"> 52views •18 feb 2025 </div>
      </div>
    </div>
<!-- Example video card  -->
    <div class="video-card computer ">
      <div class="video-thumb">
        <iframe width="100%" height="200" src="https://www.youtube.com/embed/ww5OoFGjnzw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <div class="video-duration">03:21</div>
      </div>
      <div class="video-info">
        <h3>Power Supply & Cooling System in Computer | PSU & Cooling Explained </h3>
        <p>Want to keep your computer cool and efficient? Understanding the power supply unit (PSU)?</p>
        <div class="video-meta"> 47views •21 Feb 2025 </div>
      </div>
    </div>
<!-- Example video card  -->
    <div class="video-card ml ">
      <div class="video-thumb">
        <iframe width="100%" height="200" src="https://www.youtube.com/embed/cBC4OSCWVEs" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <div class="video-duration">05:14</div>
      </div>
      <div class="video-info">
        <h3>What is Machine Learning? Explained in simple Terms </h3>
        <p>Dive into the World of technology white our vedio,What is Machine Learning? Explained in simple Terms  </p>
        <div class="video-meta"> 41views • 4 apr 2025</div>
      </div>
    </div>
<!-- Example video card  -->
    <div class="video-card cybersecurity ">
      <div class="video-thumb">
        <iframe width="100%" height="200" src="https://www.youtube.com/embed/PhS69sHkDFA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <div class="video-duration">02:16</div>
      </div>
      <div class="video-info">
        <h3>Dark Web vs Deep Web:What’s the Difference? Hidden Internet Explained</h3>
        <p>The internet is much bigger than what we see on Google! in this Video we'll break down deep web and dark web.</p>
        <div class="video-meta"> 34views •10 mar 2025 </div>
      </div>
    </div>
<!-- Example video card  -->
    <div class="video-card cybersecurity ">
      <div class="video-thumb">
        <iframe width="100%" height="200" src="https://www.youtube.com/embed/h7GkFv997oM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <div class="video-duration">05:40</div>
      </div>
      <div class="video-info">
        <h3>What is Ransomware & How to Protect yourself.</h3>
        <p>Ransomware is one of the biggest cybersecurity threats today.</p>
        <div class="video-meta">25 views •29 mar 2025 </div>
      </div>
    </div>
<!-- Example video card  -->
    <div class="video-card computer ">
      <div class="video-thumb">
        <iframe width="100%" height="200" src="https://www.youtube.com/embed/_MJ4SHgFwsA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <div class="video-duration">05:23</div>
      </div>
      <div class="video-info">
        <h3>What is a Computer? | Computer kay Hota Hai | Easy Explained in English & Hindi.</h3>
        <p>Discover the fundamental concept of computers in our latest Video.</p>
        <div class="video-meta">26 views •14 mar 2025 </div>
      </div>
    </div>
<!-- Example video card  -->
    <div class="video-card cybersecurity ">
      <div class="video-thumb">
        <iframe width="100%" height="200" src="https://www.youtube.com/embed/xIjM7pDzMrA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <div class="video-duration">06:28</div>
      </div>
      <div class="video-info">
        <h3>What is Phishing? How to Avoid Online Scams & Stay Safe.</h3>
        <p>Discover the ins and outs of phishing scams in our latest video.</p>
        <div class="video-meta">16 views •23 mar 2025 </div>
      </div>
    </div>
<!-- Example video card  -->
    <div class="video-card cybersecurity">
      <div class="video-thumb">
        <iframe width="100%" height="200" src="https://www.youtube.com/embed/0v4I9_gP8DM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <div class="video-duration">04:42</div>
      </div>
      <div class="video-info">
        <h3>Cybersecurity Basics: 7 Tips to Stay Safe Online & Avoid Scams!</h3>
        <p>What to stay safe Online? Learn the 7 essential cybersecurity tips to protect your data.</p>
        <div class="video-meta"> 14 views •26 mar 2025 </div>
      </div>
    </div>
<!-- Example video card  -->
    <div class="video-card programming ">
      <div class="video-thumb">
        <iframe width="100%" height="200" src="https://www.youtube.com/embed/1K2Ef2In8J4" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <div class="video-duration">04:09</div>
      </div>
      <div class="video-info">
        <h3>Which Programming Language Should You Learn First?</h3>
        <p>Starting your coding journey but not sure which programming Language to pick first?</p>
        <div class="video-meta">12 views •2 may 2025 </div>
      </div>
    </div>
<!-- Example video card  -->
    <div class="video-card ml ">
      <div class="video-thumb">
        <iframe width="100%" height="200" src="https://www.youtube.com/embed/yMa1TJSDwzY" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <div class="video-duration">25:02</div>
      </div>
      <div class="video-info">
        <h3>AI,Machine Learning,Quantum Computing & the Metaverse Explained Simply!</h3>
        <p>Confused by buzzwords like AI,Machine Learning,Quantum Computing & the Metaverse Explained Simply!</p>
        <div class="video-meta">11 views •3 may 2025 </div>
      </div>
    </div>
<!-- Example video card  -->
    <div class="video-card cybersecurity  ">
      <div class="video-thumb">
        <iframe width="100%" height="200" src="https://www.youtube.com/embed/X6bq4Llm9k8" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <div class="video-duration">05:15</div>
      </div>
      <div class="video-info">
        <h3>what is Ethical Hacking? How to Become a white hat Hacker!</h3>
        <p>Ethical hacking is the practice of testung computer systems for security.</p>
        <div class="video-meta">10 views •1 Apr 2025 </div>
      </div>
    </div>
<!-- Example video card  -->
    <div class="video-card tutorials ">
      <div class="video-thumb">
        <iframe width="100%" height="200" src="https://www.youtube.com/embed/8lkwJVK7OyY" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <div class="video-duration">01:16:37</div>
      </div>
      <div class="video-info">
        <h3>💻 Ultimate Guide to Operating Systems, Networking & Cybersecurity (2025) | Windows vs Linux , more</h3>
        <p></p>
        <div class="video-meta"> 9 views •10 may 2025 </div>
      </div>
    </div>
<!-- Example video card  -->
    <div class="video-card web ">
      <div class="video-thumb">
        <iframe width="100%" height="200" src="https://www.youtube.com/embed/Fm5jhxyLsTU" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <div class="video-duration">03:35</div>
      </div>
      <div class="video-info">
        <h3>Comprehensive Website Design Course Installing Tools VS code | Browser | Extension</h3>
        <p>How to install Visual Studio Code (VS Code)
Setting up useful extensions like Live Server
Installing Google Chrome for testing
Introduction to Figma for UI/UX design</p>
        <div class="video-meta">6 views •7 jul 2025 </div>
      </div>
    </div>
<!-- Example video card  -->
    <div class="video-card programming ">
      <div class="video-thumb">
        <iframe width="100%" height="200" src="https://www.youtube.com/embed/kmFwu4-KfRw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <div class="video-duration">26:54</div>
      </div>
      <div class="video-info">
        <h3>Master Coding in 2025: Choose the Right Language – Python, Java or C++?</h3>
        <p>Are you confused about which programming language to learn first? In this 27-minute complete guide, we break down the pros and cons of *Python**, **Java**, and **C++* to help you make the best decision for your career or passion project. Whether you want to become a **full stack developer**, build apps, or create websites without any coding, this video covers it all!</p>
        <div class="video-meta">5 views • 10 jun 2025</div>
      </div>
    </div>
<!-- Example video card  -->
    <div class="video-card programming ">
      <div class="video-thumb">
        <iframe width="100%" height="200" src="https://www.youtube.com/embed/Rh2tq4P7QsQ?" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <div class="video-duration">05:03</div>
      </div>
      <div class="video-info">
        <h3>Python vs. Java vs. C++: Which Programming Language Should You Learn in 2025?</h3>
        <p>Confused between Python, Java, and C++? In this 5-minute video, we break down the key differences, uses, pros, and cons of each language to help you decide which one is best for your goals in 2025. Whether you're a beginner, student, or aspiring developer, this guide will point you in the right direction!</p>
        <div class="video-meta">5 views •4 may 2025 </div>
      </div>
    </div>
<!-- Example video card  -->
    <div class="video-card web">
      <div class="video-thumb">
        <iframe width="100%" height="200" src="https://www.youtube.com/embed//u9yT0f2qzWs" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <div class="video-duration">04:04</div>
      </div>
      <div class="video-info">
        <h3>HTML Basics Explained | Complete Web Design Course (Episode 3)</h3>
        <p>Welcome to Episode 3 of the Complete Web Design Course!
In this video, we’ll dive into *HTML Basics* — the backbone of every website. Whether you're just starting out or brushing up your skills, this tutorial is your first big step into the world of **web development**.
</p>
        <div class="video-meta"> 6 views •11 jul 2025 </div>
      </div>
    </div>
    <!-- Add more cards below with your own YouTube video IDs and details -->
  </div>

  <footer>
    &copy; 2025 Computer Minds. All rights reserved.
  </footer>

  <script>
    // Filter videos based on category
    function filterCategory(category) {
      const videos = document.querySelectorAll('.video-card');
      videos.forEach(video => {
        if (category === 'all' || video.classList.contains(category)) {
          video.style.display = 'block';
        } else {
          video.style.display = 'none';
        }
      });
    }
  </script>

</body>
</html>
