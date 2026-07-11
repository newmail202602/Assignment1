Frist prompt:
[I have made a professional web page about developer confarence 2026 which contain these parts navigation [ <nav> <div class="logo"><img src="./assets/logo.png" alt="Logo" /></div> <div> <ul> <li><a href="#speakers">Speakers</a></li> <li><a href="#schedule">Schedule</a></li> <li><a href="#tracks">Tracks</a></li> <li><a href="#venue">Venue</a></li> <li><a href="#blog">Blog</a></li> </ul> </div> <div> <button class="common-btn">Register Now</button> </div> </nav>] hero section [ <div class="hero-banner"> <div class="hero-heading"> <h1>Code. <em>Connect.</em> Creat</h1> <p class="head-paredraph"> Join 4,000+ engineers, founders and builders at the premier developer <br /> conference of 2026. Three days of cutting-edge talks, hand-on <br /> workshops and meaningful connections. </p> </div> <button class="common-btn">Registert Now</button> </div>} ] speakers section [ <section class="Speakers"> <h1>Meet The Speakers</h1> <div class="speakers-cards"> <div class="speakers-card"> <div><img src="./assets/andrej.png" alt="Andrej Karpathy" /></div> <div class="card-content"> <p class="blu">AI/ML</p> <h3>Andrej Karpathy</h3> <p class="ash">Pretraining team, Anthropic</p> </div> </div> <div class="speakers-card"> <div><img src="./assets/demis.png" alt="Demis Hassabis" /></div> <div class="card-content"> <p class="blu">ClOUD & DEVOPS</p> <h3>Demis Hassabis</h3> <p class="ash">Co-Founder and CEO, Google DeepMind</p> </div> </div> <div class="speakers-card"> <div><img src="./assets/gary.png" alt="Gary Maucus" /></div> <div class="card-content"> <p class="blu">FRONTEND</p> <h3>Gary Marcus</h3> <p class="ash">Staff Engineer, Vercel</p> </div> </div> <div class="speakers-card"> <div><img src="./assets/mustafa.png" alt="Mustafa Suleyman" /></div> <div class="card-content"> <p class="blu">SECURUTY</p> <h3>Mustafa Suleyman</h3> <p class="ash">CEO of Microsoft AI</p> </div> </div> </div> </section>] pricing section [<section class="pricing"> <div class="pricing-head"> <h1>Secure Your Spot</h1> <p class="ash">Early-bird pricing ends August 15, 2026.</p> </div> <div class="pricing-cards"> <div class="card"> <p class="ash">STANDARD</p> <h1>$399</h1> <p class="ash">per person</p> <hr /> <ul class="ash"> <li>Assess to all 3 conference days</li> <li>48 curated technical talks</li> <li>2 workshop sessions</li> <li>Networking lunch & coffee breaks</li> <li>Conference swag bag</li> <li>Digital recordings (30 days)</li> </ul> <button class="outline-btn">Get Standard</button> </div> <div class="card pro"> <p class="sky">PRO</p> <h1>$749</h1> <p>per person</p> <hr /> <ul> <li>Evrything in standard</li> <li>Unlimited workshop access</li> <li>Speaker meet and greet</li> <li>Vip networking dinner</li> <li>Lifetime recording access</li> <li>1-on-1 mentorship (30 min)</li> </ul> <button class="common-btn">Get Pro</button> </div> <div class="card"> <p class="ash">Team</p> <h1>$5,999</h1> <p class="ash">up to 10 people</p> <hr /> <ul class="ash"> <li>Evrything in pro (10 seats)</li> <li>Dedicated team lounge access</li> <li>Private workshop booking</li> <li>Company ligi on event page</li> <li>Recruitment booth (1 day)</li> <li>Priority customer support</li> </ul> <button class="outline-btn">Contact Us</button> </div> </div> </section>] suggest me one more section i can use in my professional web page]

second prompt:

how it should look the conference schedule ?

third prompt:

[ {
margin: 0px;
padding: 0px;
font-family: "Inter", sans-serif;
}
.common-btn {
color: #ffffff;
background-color: #1d4ed8;
border: none;
padding: 15px 45px;
border-radius: 10px;
font-weight: bolder;
}
.outline-btn {
color: #1d4ed8;
background-color: #ffffff;
border: 1px solid #1d4ed8;
padding: 15px 45px;
border-radius: 10px;
font-weight: bolder;
}
.common-btn:hover {
cursor: pointer;
color: black;
background: linear-gradient(20deg, rgb(76, 76, 247), rgb(153, 153, 153));
}
.outline-btn:hover {
color: black;
background: linear-gradient(20deg, #1d4ed8, rgb(149, 123, 182));
}
.common-text {
color: #575757;
}
/_ nav start _/
nav {
display: flex;
justify-content: space-between;
align-items: center;
background-color: #ffffff;
padding: 20px 4%;
}

nav ul li {
list-style: none;
}
nav ul li a {
text-decoration: none;
color: #575757;
}
nav ul {
display: flex;
gap: 20px;
/_ justify-content: space-between; _/
}
/_ hero starts _/
.hero-banner {
background-image:
linear-gradient(rgba(15, 15, 15, 0.6), rgba(0, 0, 0, 0.6)),
url(../assets/banner.jpg);
height: 100vh;

background-repeat: no-repeat;
background-size: cover;
background-position: center;
display: flex;
flex-direction: column;
align-items: center;
text-align: center;
justify-content: space-around;
color: white;
}
.hero-banner h1 {
font-size: 70px;
margin-bottom: 20px;
}
/_ Speakers Starts _/
.Speakers {
display: flex;
flex-direction: column;
align-items: center;
margin: 80px 2%;
}
.Speakers h1,
.pricing-head h1 {
font-size: 60px;
}
.speakers-cards {
display: grid;
grid-template-columns: repeat(2, 1fr);
/_ align-items: center;
justify-content: center; _/
gap: 30px;
margin-top: 50px;
}
.speakers-cards img {
height: 100%;
width: 100%;
object-fit: cover;
}
.speakers-card {
border: 1px solid #ebe8e8;
border-radius: 10px;
overflow: hidden;
}
.Speakers p {
font-size: 13px;
}
.blu {
color: #2563eb;
font-weight: bold;
}
.ash {
color: #575757;
}
.card-content {
padding: 20px 6%;
display: flex;
flex-direction: column;
gap: 10px;
}
/_ pricing _/
.pricing {
display: flex;
flex-direction: column;
align-items: center;
justify-content: center;
}
.pricing-head {
align-items: center;
display: flex;
flex-direction: column;
/_ justify-content: space-around; _/
gap: 15px;
}
.pricing-cards {
display: grid;
grid-template-columns: repeat(3, 1fr);
gap: 20px;
}
.card {
border: 1px solid #d6d6d6;
padding: 30px;
display: flex;
flex-direction: column;
gap: 20px;
border-radius: 20px;
margin-top: 40px;
}
.card ul {
padding: 0;
margin: 0;
list-style-position: inside;
line-height: 35px;
}
.card ul li::marker {
color: #1d4ed8;
}
.pro {
background-color: #0d1b2a;
color: #b6b6b6;
}
.sky {
color: #60a5fa;
}
.pro h1 {
color: white;
} this is my scc just recomand the conference section as my css
and then giv me a image ]

    forth prompt :

    give me rhe css and html
