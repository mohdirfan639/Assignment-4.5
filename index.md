Assignment 4.5 — Multi-Page College Club Website
1. Project folder structure
Create a folder named Assignment-4.5 and arrange the files like this:

Assignment-4.5/

index.html

about.html

registration.html

contact.html

css/

style.css

images/

favicon.png

2. Home page — index.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home | College Coding Club</title>
    <meta name="description" content="Welcome to the College Coding Club. Explore coding activities, events, workshops and student opportunities.">
    <link rel="icon" type="image/png" href="images/favicon.png">
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <header>
        <h1>College Coding Club</h1>
        <p>Learn, Code, Innovate!</p>
    </header>

    <nav>
        <a href="index.html">Home</a>
        <a href="about.html">About Us</a>
        <a href="registration.html">Registration</a>
        <a href="contact.html">Contact</a>
    </nav>

    <main>
        <section class="hero">
            <h2>Welcome to Our Coding Club</h2>
            <p>Join a community of students who love technology,
               programming, creativity and problem-solving.</p>
            <a class="btn" href="registration.html">Join the Club</a>
        </section>

        <section>
            <h2>Our Activities</h2>
            <div class="cards">
                <article class="card">
                    <h3>💻 Coding Workshops</h3>
                    <p>Learn HTML, CSS, JavaScript and programming basics.</p>
                </article>
                <article class="card">
                    <h3>🏆 Coding Competitions</h3>
                    <p>Test your skills and solve interesting challenges.</p>
                </article>
                <article class="card">
                    <h3>🤝 Group Projects</h3>
                    <p>Work with fellow students to build useful projects.</p>
                </article>
            </div>
        </section>

        <section>
            <h2>Upcoming Events</h2>
            <div class="table-wrap">
                <table>
                    <thead>
                        <tr>
                            <th>Event</th>
                            <th>Date</th>
                            <th>Venue</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>HTML & CSS Workshop</td>
                            <td>10 November 2026</td>
                            <td>Computer Lab</td>
                        </tr>
                        <tr>
                            <td>Programming Quiz</td>
                            <td>18 November 2026</td>
                            <td>Seminar Hall</td>
                        </tr>
                        <tr>
                            <td>Project Exhibition</td>
                            <td>25 November 2026</td>
                            <td>College Auditorium</td>
                        </tr>
                    </tbody>
                </table>
            </div>
            <p class="note">The events and dates are sample information for this project.</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 College Coding Club. All rights reserved.</p>
    </footer>
</body>
</html>
3. About page — about.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us | College Coding Club</title>
    <meta name="description" content="Learn about the College Coding Club, its mission, activities, and student membership.">
    <link rel="icon" type="image/png" href="images/favicon.png">
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <header>
        <h1>About Our Club</h1>
        <p>Building skills and creating opportunities</p>
    </header>

    <nav>
        <a href="index.html">Home</a>
        <a href="about.html">About Us</a>
        <a href="registration.html">Registration</a>
        <a href="contact.html">Contact</a>
    </nav>

    <main>
        <section>
            <h2>Who We Are</h2>
            <p>The College Coding Club is a student community dedicated
               to learning programming, exploring technology and
               developing practical problem-solving skills.</p>
        </section>

        <section>
            <h2>Our Mission</h2>
            <p>Our mission is to encourage creativity, teamwork,
               technical knowledge and innovation among students.</p>
        </section>

        <section>
            <h2>What We Do</h2>
            <ul>
                <li>Organize coding workshops and seminars.</li>
                <li>Conduct programming quizzes and competitions.</li>
                <li>Build websites and software projects.</li>
                <li>Help students learn from one another.</li>
            </ul>
        </section>

        <section>
            <h2>Club Information</h2>
            <div class="info-box">
                <p><strong>Club Name:</strong> College Coding Club</p>
                <p><strong>Established:</strong> 2024 (sample)</p>
                <p><strong>Faculty Coordinator:</strong> Faculty Coordinator</p>
                <p><strong>Membership:</strong> Open to interested students</p>
                <p><strong>Meetings:</strong> Weekly, as scheduled</p>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 College Coding Club. All rights reserved.</p>
    </footer>
</body>
</html>
4. Registration page — registration.html
This page includes student details, course selection, a membership preference, and a submit button.


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration | College Coding Club</title>
    <meta name="description" content="Register for the College Coding Club using our student membership form.">
    <link rel="icon" type="image/png" href="images/favicon.png">
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <header>
        <h1>Club Registration</h1>
        <p>Become a member of our coding community</p>
    </header>

    <nav>
        <a href="index.html">Home</a>
        <a href="about.html">About Us</a>
        <a href="registration.html">Registration</a>
        <a href="contact.html">Contact</a>
    </nav>

    <main>
        <section class="form-section">
            <h2>Student Registration Form</h2>
            <p>Fill in your details to express your interest in joining.</p>

            <form action="#" method="post">
                <label for="fullname">Full Name</label>
                <input type="text" id="fullname" name="fullname"
                       placeholder="Enter your full name" required>

                <label for="email">Email Address</label>
                <input type="email" id="email" name="email"
                       placeholder="student@example.com" required>

                <label for="roll">Roll Number</label>
                <input type="text" id="roll" name="roll"
                       placeholder="Enter your roll number" required>

                <label for="course">Course / Department</label>
                <select id="course" name="course" required>
                    <option value="">Select your course</option>
                    <option value="BCA">BCA</option>
                    <option value="BTech">B.Tech</option>
                    <option value="BSc">B.Sc.</option>
                    <option value="MCA">MCA</option>
                    <option value="Other">Other</option>
                </select>

                <label for="year">Year of Study</label>
                <select id="year" name="year" required>
                    <option value="">Select your year</option>
                    <option value="1">First Year</option>
                    <option value="2">Second Year</option>
                    <option value="3">Third Year</option>
                    <option value="4">Fourth Year</option>
                </select>

                <fieldset>
                    <legend>Preferred Activity</legend>
                    <label class="choice">
                        <input type="radio" name="activity" value="Web Development" required>
                        Web Development
                    </label>
                    <label class="choice">
                        <input type="radio" name="activity" value="Programming">
                        Programming
                    </label>
                    <label class="choice">
                        <input type="radio" name="activity" value="UI Design">
                        UI Design
                    </label>
                </fieldset>

                <label for="reason">Why do you want to join?</label>
                <textarea id="reason" name="reason" rows="4"
                          placeholder="Tell us about your interests"></textarea>

                <label class="choice">
                    <input type="checkbox" name="agreement" required>
                    I confirm that the information provided is correct.
                </label>

                <button type="submit">Submit Registration</button>
            </form>
            <p class="note">Demo form: a backend is needed to store or send submissions.</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 College Coding Club. All rights reserved.</p>
    </footer>
</body>
</html>
5. Contact page — contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us | College Coding Club</title>
    <meta name="description" content="Contact the College Coding Club for membership, activities, events and other enquiries.">
    <link rel="icon" type="image/png" href="images/favicon.png">
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <header>
        <h1>Contact Us</h1>
        <p>We would love to hear from you</p>
    </header>

    <nav>
        <a href="index.html">Home</a>
        <a href="about.html">About Us</a>
        <a href="registration.html">Registration</a>
        <a href="contact.html">Contact</a>
    </nav>

    <main>
        <section>
            <h2>Get in Touch</h2>
            <div class="info-box">
                <p><strong>Email:</strong>
                    <a href="mailto:codingclub@example.com">codingclub@example.com</a>
                </p>
                <p><strong>Location:</strong> College Computer Science Department</p>
                <p><strong>Office Hours:</strong> Monday to Friday, 10 AM to 4 PM (sample)</p>
                <p><strong>Faculty Coordinator:</strong> Contact the college office</p>
            </div>
        </section>

        <section>
            <h2>Send an Enquiry</h2>
            <form action="#" method="get">
                <label for="name">Your Name</label>
                <input type="text" id="name" name="name" required>

                <label for="contact-email">Your Email</label>
                <input type="email" id="contact-email" name="email" required>

                <label for="message">Your Message</label>
                <textarea id="message" name="message" rows="5" required></textarea>

                <button type="submit">Send Enquiry</button>
            </form>
            <p class="note">Demo enquiry form: connect a backend to deliver messages.</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 College Coding Club. All rights reserved.</p>
    </footer>
</body>
</html>
6. CSS styling — css/style.css
Use one shared stylesheet for all four pages to maintain consistent colors, navigation, tables, and forms.


css

* {
    box-sizing: border-box;
}

body {
    margin: 0;
    font-family: Arial, Helvetica, sans-serif;
    line-height: 1.6;
    color: #263244;
    background-color: #f4f7fb;
}

header {
    background: linear-gradient(135deg, #123b72, #2878c8);
    color: white;
    text-align: center;
    padding: 32px 16px;
}

header h1 {
    margin: 0;
    font-size: 2.2rem;
}

header p {
    margin-bottom: 0;
}

nav {
    background-color: #102b4e;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 6px;
    padding: 12px;
}

nav a {
    color: white;
    text-decoration: none;
    padding: 10px 16px;
    border-radius: 5px;
}

nav a:hover,
nav a:focus {
    background-color: #2878c8;
}

main {
    width: min(100% - 32px, 1000px);
    margin: 28px auto;
}

section {
    background-color: white;
    padding: 24px;
    margin-bottom: 24px;
    border-radius: 10px;
    box-shadow: 0 3px 12px rgba(0, 0, 0, 0.06);
}

h2 {
    color: #174a82;
    margin-top: 0;
}

.hero {
    text-align: center;
    padding: 48px 24px;
}

.btn,
button {
    display: inline-block;
    background-color: #1768ac;
    color: white;
    padding: 12px 20px;
    border: none;
    border-radius: 5px;
    text-decoration: none;
    cursor: pointer;
    font-size: 1rem;
}

.btn:hover,
button:hover {
    background-color: #104c80;
}

.cards {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 16px;
}

.card {
    padding: 18px;
    background-color: #eef5ff;
    border-radius: 8px;
}

.card h3 {
    margin-top: 0;
    color: #174a82;
}

.table-wrap {
    overflow-x: auto;
}

table {
    width: 100%;
    border-collapse: collapse;
}

th,
td {
    border: 1px solid #d5deea;
    padding: 12px;
    text-align: left;
}

th {
    background-color: #174a82;
    color: white;
}

tbody tr:nth-child(even) {
    background-color: #f0f5fb;
}

.info-box {
    background-color: #eef5ff;
    padding: 16px;
    border-left: 4px solid #2878c8;
    border-radius: 5px;
}

.form-section {
    max-width: 700px;
    margin: auto;
}

form label,
form input:not([type="radio"]):not([type="checkbox"]),
form select,
form textarea {
    display: block;
    width: 100%;
}

form label {
    margin: 14px 0 6px;
    font-weight: bold;
}

form input:not([type="radio"]):not([type="checkbox"]),
form select,
form textarea {
    padding: 11px;
    border: 1px solid #bac7d8;
    border-radius: 5px;
    font: inherit;
    background-color: white;
}

form input:focus,
form select:focus,
form textarea:focus {
    outline: 2px solid #2878c8;
    outline-offset: 1px;
}

fieldset {
    margin: 18px 0;
    border: 1px solid #bac7d8;
    border-radius: 5px;
    padding: 12px;
}

form label.choice {
    display: flex;
    align-items: center;
    gap: 9px;
    font-weight: normal;
}

form label.choice input {
    width: auto;
}

.note {
    color: #596779;
    font-size: 0.9rem;
}

footer {
    background-color: #102b4e;
    color: white;
    text-align: center;
    padding: 18px;
    margin-top: 35px;
}

footer p {
    margin: 0;
}

@media (max-width: 600px) {
    header h1 {
        font-size: 1.7rem;
    }

    nav {
        flex-direction: column;
        text-align: center;
    }

    nav a {
        display: block;
    }

    section {
        padding: 18px;
    }
}
7. Add the favicon
Place a real PNG image at:

images/favicon.png

Use a small square icon, such as a blue background with a white letter C. All four HTML pages already link to the same favicon.

8. Test your website
Save all five code files in their correct locations.

Open index.html in your browser.

Click Home, About Us, Registration, and Contact to verify that every page opens.

Confirm the events table appears on the home page.

Fill out the registration form and check that required fields validate. The demo form will not store registrations without a backend.

Confirm the favicon appears in the browser tab and the layout works on a narrow screen.

9. Final submission checklist
Submission checklist
0/8


index.html — Home page

about.html — Club introduction

registration.html — Student registration form

contact.html — Contact details

css/style.css — Shared styling

images/favicon.png — Favicon image

Screenshot showing the website and browser-tab favicon

All internal links and metadata checked
Before submitting: Replace the sample club details, email address, and event dates with your actual college information if required. Take your own browser screenshot after running the website; the screenshot is a separate deliverable from the code.


ChatGPT is AI and can make mistakes.



No file chosenNo file chosenNo file chosen
Chat with ChatGPT