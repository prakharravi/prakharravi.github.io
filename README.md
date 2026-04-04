<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Prakhar Ravi - GST Practitioner</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #f4f6f9;
}

@keyframes fadeIn {
    from {opacity: 0; transform: translateY(20px);}
    to {opacity: 1; transform: translateY(0);}
}

.header {
    background: linear-gradient(135deg, #0b2c4a, #1e4f7a);
    color: white;
    text-align: center;
    padding: 40px 20px;
    animation: fadeIn 1s ease;
}

.logo {
    width: 80px;
    margin-bottom: 10px;
}

.tagline {
    color: #ffc107;
}

.btn {
    display: inline-block;
    padding: 10px 15px;
    margin: 8px;
    background: #28a745;
    color: white;
    text-decoration: none;
    border-radius: 6px;
}

.card {
    background: white;
    margin: 20px auto;
    padding: 20px;
    border-radius: 12px;
    max-width: 900px;
}

.services {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px,1fr));
    gap: 15px;
}

.service-box {
    padding: 15px;
    border-radius: 10px;
    background: #fff;
    box-shadow: 0 0 5px #ccc;
}

.footer {
    text-align: center;
    padding: 15px;
    background: #0b2c4a;
    color: white;
}

.hello {
    text-align: center;
    font-size: 22px;
    font-weight: bold;
    margin: 15px;
}
</style>

</head>

<body>

<!-- HELLO WORLD -->
<div class="hello">Hello World 👋</div>

<!-- HEADER -->
<div class="header">
    <img src="https://cdn-icons-png.flaticon.com/512/3135/3135715.png" class="logo">

    <h1>👨‍💼 Prakhar Ravi</h1>
    <p>GST TAX PRACTITIONER (GOVT. CERTIFIED)</p>
    <p><b>B.Com | M.Com | LL.B (Ongoing)</b></p>
    <p class="tagline">Complete Taxation & Legal Services Under One Roof</p>

    <a href="tel:+916206178456" class="btn">📞 Call Now</a>
    <a href="https://wa.me/916206178456" target="_blank" class="btn">💬 WhatsApp</a>
    <a href="mailto:prakharraviadv@gmail.com" class="btn">📩 Email</a>

    <p id="time"></p>
</div>

<!-- ABOUT -->
<div class="card">
    <h2>🧩 About Me</h2>
    <p>I provide complete GST, ITR, Business Registration & Legal Compliance services with fast, reliable and affordable solutions.</p>
</div>

<!-- MY VISION -->
<div class="card">
    <h2>🎯 My Vision</h2>
    <p>
        My vision is to provide affordable and reliable taxation and legal services to every individual and business across India.
        I aim to simplify compliance and help clients grow their business without stress.
    </p>
</div>

<!-- SERVICES -->
<div class="card">
    <h2>💼 Services</h2>
    <div class="services">
        <div class="service-box">GST Registration</div>
        <div class="service-box">GST Return Filing</div>
        <div class="service-box">Income Tax Return (ITR)</div>
        <div class="service-box">DSC Digital Signature Certificate</div>
        <div class="service-box">MSME / Udyam Registration</div>
        <div class="service-box">PAN & Aadhaar Services</div>
        <div class="service-box">TDS Return & Compliance</div>
        <div class="service-box">Company / Firm Registration</div>
        <div class="service-box">Accounting & Compliance Services</div>
    </div>
</div>
<!-- WHY CHOOSE ME -->
<div class="card">
    <h2>⚡ Why Choose Me</h2>
    <ul>
        <li>✔ Fast & Reliable Service</li>
        <li>✔ Affordable Pricing</li>
        <li>✔ Expert GST & Tax Knowledge</li>
        <li>✔ End-to-End Compliance Support</li>
        <li>✔ 24x7 Client Support</li>
    </ul>
</div>
<!-- EXPERIENCE -->
<div class="card">
    <h2>📊 Experience</h2>
    <ul>
        <li>✔ 100+ ITR Filed</li>
        <li>✔ 50+ GST Clients</li>
        <li>✔ Fast Processing (24 Hours)</li>
        <li>✔ Software: Computax, Winman</li>
    </ul>
</div>

<!-- CONTACT -->
<div class="card">
    <h2>📍 Contact</h2>
    <p><b>📞 Mobile:</b> +91 6206178456</p>
    <p><b>📧 Email:</b> prakharraviadv@gmail.com</p>
    <p><b>📍 Location:</b> Patna, Bihar | Noida, Greater Noida | Karnataka | PAN India</p>

    <a href="tel:+916206178456" class="btn">📞 Call Now</a>
    <a href="https://wa.me/916206178456" target="_blank" class="btn">💬 WhatsApp</a>
</div>

<!-- GOOGLE FORM -->
<div class="card">
    <h2>📝 Client Form</h2>
    <p><b>👉 Fill form & get quick response</b></p>

    <iframe src="https://docs.google.com/forms/d/e/1FAIpQLScEFJsdDovna1hLj2YoKBO1YR_JbjVWVOuLgbs9sUGF6FBJbA/viewform?embedded=true" 
    width="100%" height="900" style="border:none; border-radius:10px;">
    Loading…
    </iframe>
</div>

<!-- FOOTER -->
<div class="footer">
    © 2026 Prakhar Ravi | GST Practitioner
</div>

<!-- TIME SCRIPT -->
<script>
function updateTime() {
    const now = new Date();
    document.getElementById("time").innerHTML = "🕒 " + now.toLocaleString();
}
setInterval(updateTime, 1000);
updateTime();
</script>

</body>
</html>
