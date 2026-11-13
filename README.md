# Assignment-4
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>JobHub - Find Your Next Job</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<!-- Navigation Bar -->
<header>
<div class="logo">💼 JobHub</div>

<nav>
<a href="#home">Home</a>
<a href="#jobs">Find Jobs</a>
<a href="#companies">Companies</a>
<a href="#about">About</a>
<a href="#contact">Contact</a>
</nav>

<div class="auth">
<a href="#login">Login</a>
<button>Register</button>
</div>
</header>

<!-- Hero Section -->
<section class="hero" id="home">
<div class="hero-text">
<span class="tag">🔍 Find Your Next Opportunity</span>

<h1>Your <span>Next Job</span><br>
Is Closer Than You Think</h1>

<p>
Discover amazing job opportunities,
connect with top companies, and take
the next step in your career.
</p>

<div class="search-box">
<input type="text" id="keyword"
placeholder="Job title, keyword or company">

<input type="text" id="location"
placeholder="Location">

<button onclick="searchJobs()">Search Jobs</button>
</div>

<div class="popular">
Popular searches:
<span>Frontend Developer</span>
<span>Backend Developer</span>
<span>UI/UX Designer</span>
<span>Remote Jobs</span>
</div>
</div>

<div class="hero-image">
<img src="https://images.unsplash.com/photo-1534528741775-53994a69daeb?w=600"
alt="Job seeker">
</div>
</section>

<!-- Featured Jobs -->
<section class="featured" id="jobs">
<div class="section-heading">
<div>
<h2>Featured Jobs</h2>
<p>Handpicked opportunities from top companies</p>
</div>
<a href="#jobs">View All Jobs →</a>
</div>

<div class="job-container" id="jobContainer">

<div class="job-card">
<div class="company-icon blue"> </> </div>
<p>TechVision</p>
<h3>Frontend Developer</h3>
<small>📍 Lagos, Nigeria • Remote</small>
<span class="type">Full-time</span>
<h4>₦300,000 – ₦500,000 / month</h4>
</div>

<div class="job-card">
<div class="company-icon purple">▥</div>
<p>GrowthPlus</p>
<h3>Backend Developer</h3>
<small>📍 Abuja, Nigeria • Remote</small>
<span class="type">Full-time</span>
<h4>₦400,000 – ₦700,000 / month</h4>
</div>

<div class="job-card">
<div class="company-icon pink">✎</div>
<p>CreativeLabs</p>
<h3>UI/UX Designer</h3>
<small>📍 Port Harcourt, Nigeria • Remote</small>
<span class="type contract">Contract</span>
<h4>₦200,000 – ₦400,000 / month</h4>
</div>

<div class="job-card">
<div class="company-icon green">⚑</div>
<p>BrightMedia</p>
<h3>Digital Marketing Specialist</h3>
<small>📍 Lagos, Nigeria • Hybrid</small>
<span class="type">Full-time</span>
<h4>₦250,000 – ₦450,000 / month</h4>
</div>

</div>
<p id="noResults" hidden>No matching jobs found.</p>
</section>

<!-- Benefits Section -->
<section class="benefits" id="about">

<div class="benefit">
<div class="benefit-icon">🔍</div>
<h3>Easy to Search</h3>
<p>Filter jobs by location, category,
experience and more.</p>
</div>

<div class="benefit">
<div class="benefit-icon">🛡️</div>
<h3>Trusted Companies</h3>
<p>Work with verified and reputable
employers.</p>
</div>

<div class="benefit">
<div class="benefit-icon">📈</div>
<h3>Grow Your Skills</h3>
<p>Access resources and tips to
boost your career.</p>
</div>

<div class="benefit">
<div class="benefit-icon">👥</div>
<h3>Join Our Community</h3>
<p>Connect with other job seekers
and professionals.</p>
</div>

<div class="alerts" id="contact">
<h3>✈️ Get Job Alerts</h3>
<p>Be the first to know about new
opportunities in your field.</p>

<form id="subscribeForm">
<input type="email" placeholder="Enter your email"
required>
<button type="submit">Subscribe Now</button>
</form>
<p id="message"></p>
</div>

</section>

<footer>
<p>© 2026 JobHub. All Rights Reserved.</p>
</footer>

<script src="script.js"></script>
</body>
</html>

