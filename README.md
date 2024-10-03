# week-3-assigment
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Telemedicine Services</title>
    <link rel="stylesheet" href="logo.css">
</head>
<body>
    <header>
        <div class="logo"><img src="https://th.bing.com/th/id/OIP.KMXfNfPHBYE09zCGNpMMGwHaHa?rs=1&pid=ImgDetMain"></div>
        <h1>Telemedicine Services</h1>
        <nav class="navbar">
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
        <div class="hamburger" onclick="toggleMenu()">☰</div>
    </header>
    <div class="container">
        <main class="content">
            <h2>Welcome to Telemedicine</h2>
            <p>Telemedicine is the ability of healthcare providers to meet with patients remotely via telephone or video.

                This practice has been around almost as long as telephones but has become more popular and practical during the COVID-19 pandemic.
                
                Improvements in technology and changes to insurance reimbursement rulings have helped increase the acceptance of telemedicine. Without it, doctors and therapists wouldn’t be able to connect with patients as easily, especially during the pandemic.
                
                As telemedicine has become widespread, professionals and patients have grown more comfortable connecting virtually...</p>
          <h2>Benefits of Telemedicine</h2>
            <p>Discover the benefits of accessing healthcare from home.
                Telemedicine isn’t meant to take the place of face-to-face visits. While it does have some disadvantages, which we’ll get into later, its benefits are undeniable.

They include:
<br>
1. Easy access to specialists
Not everyone has an ongoing relationship with a doctor they can call when they need one. Many online medical networks offer round-the-clock access to all kinds of specialists, without an appointment, at any time of day or night.
<br>
2. Lower cost
Doctors and therapists can be expensive, even for people with good health insurance. Telemedicine appointments typically cost less than in-person visits do. This reduces out-of-pocket costs, removing a barrier to care.
<br>
3. Medical access for people without health insurance
Not having adequate health insurance can be an obstacle to seeing a doctor. Many online companies provide cash-pay telemedicine, which doesn’t require health insurance or referrals.
<br>
4. Medical access for people in rural areas
Country living has many benefits, but fast access to medical care isn’t always one of them. For people who live many miles from the nearest medical facility, telemedicine provides a way to meet with a doctor quickly.
<br>
This saves time and allows people to stay off the road when driving conditions are less than optimal, such as during a snowstorm or hailstorm.
<br>
5. Medical access for people in underserved urban areas
The trend of hospital closures in inner-city neighborhoods has affected thousands of Americans, especially communities of color and people without health insurance.
<br>
Telemedicine helps break this cycle by providing a way for people to see a doctor before they get extremely sick.
<br>
6. Reduced exposure to pathogens
Hours-long waits in doctors’ waiting rooms with other patients can contribute to the spread of COVID-19, the flu, and other viruses. Telehealth keeps patients at home, avoiding exposure to viruses and germs. This helps protect medical professionals as well.
<br>
7. Middle-of-the-night care for babies and children
Babies have a knack for spiking fevers or getting sick in the middle of the night. Rather than rely on an internet search, parents can use telehealth services to connect quickly with doctors who can give answers and provide a diagnosis, and even a prescription, when needed.
<br>
8. No need for childcare
Parents get sick, too, and it can be challenging to take little ones along to a doctor’s visit. Telehealth eliminates this need, as well as the additional cost of childcare.
<br>
9. Doctors get to stay home too
During the pandemic, many medical offices have closed or reduced their hours. Cybersecurity tools such as virtual private networks have enabled doctors and therapists to treat patients safely from their home offices. This access also allows doctors and patients to connect after hours and on weekends.
<br>
10. Reduced medical overhead costs
For doctors, telemedicine helps lower office costs, such as the need for front desk help.
            </p>
        <h2>Disadvantages</h2>
            <p>
                Telemedicine isn’t perfect and doesn’t eliminate the need for other types of healthcare, such as emergency care, which requires a hospital or urgent care facility.
                <br>
<b>Disadvantages of telehealth:</b>
                <br>
Telemedicine doesn’t allow doctors to take blood or urine samples. For people with chronic conditions who take medications, this can hamper necessary changes to dosages. It also may prolong the time before a new diagnosis is made.
                <br>
Doctors can’t use a stethoscope to listen to your heart or breathing, take your blood pressure, or take other vitals.
                <br>
Doctors also rely on visual assessments, which may be harder to perform virtually.
                <br>
Other tests, such as mammograms, Pap smears, sonograms, and eye pressure exams for glaucoma, must be done in person.
                <br>
Children who receive services such as speech therapy may have trouble concentrating or working with their therapists remotely.
                <br>
Insurance coverage or reimbursement is not guaranteed and varies from state to state...
            </p>
        </main>
        <aside class="sidebar">
            <h3>Additional Resources</h3>
            <ul>
                <li><a href="#faq">FAQs</a></li>
                <li><a href="#blog">Blog</a></li>
            </ul>
            <input type="text" placeholder="Search...">
        </aside>
    </div>
    <footer>
        <p>&copy; 2024 Telemedicine Services. All rights reserved.</p>
        <p>Follow us on <a href="#">Social Media</a></p>
    </footer>
    <script src="script.js"></script>
</body>
</html>

#css

* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, sans-serif;
}


header {
    display: flex;
    flex-direction: column;
    align-items: center;
    background: #007BFF;
    color: white;
    padding: 10px;
}
.logo {
    width: 150px; /* Adjust as needed */
    height: auto; /* Maintain aspect ratio */
    background-size: contain; /* Ensure the logo fits within the element */
    background-repeat: no-repeat; /* Prevent repeating */
}


.navbar {
    display: flex;
    justify-content: center;
}

.navbar ul {
    list-style: none;
}

.navbar li {
    margin: 0 15px;
}

.container {
    display: flex;
    flex-direction: row;
}

.content {
    flex: 3;
    padding: 20px;
}

.sidebar {
    flex: 1;
    padding: 20px;
    background: bisque;
}

footer {
    text-align: center;
    padding: 10px;
    background: #333;
    color: white;
}

.hamburger {
    display: none;
    cursor: pointer;
}

h2 {
    color: blueviolet;
}
/* Media Queries */
@media (max-width: 765px) {
    .navbar ul {
        display: none;
        flex-direction: column;
        text-align: center;
    }

    .navbar.active ul {
        display: flex;
    }

    .hamburger {
        display: block;
    }

    .container {
        flex-direction: column;
    }

    .sidebar {
        order: -1; /* Move sidebar above content on mobile */
    }
}
