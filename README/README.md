Saad Choudhary - Personal Portfolio Website

Overview:
It is my Personal Portfolio Website and the product was made using HTML5 and CSS3 that demonstrates my abilities, projects and contact details. The site is mobile, tablet and desktop responsive.

1. Pages Overview
The portfolio consists of four separate pages:

Home Page (index.html)
Brief introduction and overview, Navigation to other pages

About Me Page (about.html)
Personal introduction, Profile photo (myphoto.jpeg), Embedded introductory video (intro.mp4), Highlights skills and interests

Projects Page (projects.html)
Displays 4 projects/assignments, Each project is presented in an <article> with a title and description

Contact Me Page (contact.html)
Contact form with Name, Email, Phone Number, and Comments. Validation applied for Email and Phone format.

2. CSS & Design
File Structure:
style.css – Base styles
mobile.css - Below 600px (mobiles)
tablet.css-601- 1024(tablet devices)
desktop.css -1025 and above (desktop devices)

All the CSS files deal with a particular viewport styling so that it is fluid and does not involve the use of Flexbox.

3. Responsiveness
Mobile: Smaller fonts, vertical navigation and small forms.
Tablet: Upright fonts, very slightly spacing.
Desktop: Bigger fonts, horizontal menu, full-width design.

3. Gradients

Header: Horizontal linear gradient
header {
    background: linear-gradient(90deg, #4e54c8, #8f94fb);
}

Project Articles: Angled gradient
article {
    background: linear-gradient(135deg, #f6d365, #fda085);
}

4. Color Scheme
Primary colors: #4e54c8 (blue-purple), #8f94fb (light purple)
Secondary colors: #f6d365 (yellow), #fda085 (orange)
Accent color: #ffd700 (gold)
Text color: #333
Background color: #f4f4f4

5. Images & Video

Profile Photo: myphoto.jpeg
Resized using .hero-photo CSS class
.hero-photo {
    max-width: 300px;
    width: 100%;
    height: auto;
    display: block;
    margin: 0 auto;
    border-radius: 10px;
}
Video: intro.mp4
Embedded with <video> tag, controls enabled, poster displayed before playback

6. Forms & Validation
Name, Email, Phone, and Comments fields
Email: type="email" ensures proper format
Phone: pattern="[0-9]{3}-[0-9]{3}-[0-9]{4}" validates 123-456-7890 format
Required fields enforced with required attribute

7. Author
Name: Saad Choudhary
Email: saad.choudhary@ontariotechu.net
Date: 2025