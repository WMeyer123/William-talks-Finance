<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>William Meyer - Digital Business Card</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            padding: 0;
            text-align: center;
            color: #333;
        }
        .card {
            background-color: #fff;
            border-radius: 10px;
            width: 300px;
            margin: 50px auto;
            padding: 20px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .card img {
            border-radius: 50%;
            width: 120px;
            height: 120px;
            border: 3px solid #333;
        }
        .card h1 {
            font-size: 24px;
            margin-top: 10px;
            color: #0077cc;
        }
        .card h2 {
            font-size: 18px;
            color: #555;
        }
        .card p {
            font-size: 14px;
            color: #555;
            margin: 10px 0;
        }
        .card a {
            text-decoration: none;
            color: #0077cc;
        }
        .card .button {
            display: inline-block;
            padding: 10px 20px;
            background-color: #0077cc;
            color: #fff;
            border-radius: 5px;
            text-decoration: none;
            margin-top: 20px;
        }
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        .container {
            width: 60%;
            margin: 20px auto;
            background: #fff;
            padding: 20px;
            box-shadow: 0px 0px 10px #aaa;
            border-radius: 8px;
        }
        h1, h2, h3 {
            color: #005B9F;
        }
        .contact-info {
            background: #005B9F;
            color: white;
            padding: 15px;
            text-align: center;
            border-radius: 5px;
        }
        .contact-info a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        .section {
            margin-bottom: 20px;
        }
        .meeting-form {
            background: #e6f2ff;
            padding: 15px;
            border-radius: 5px;
        }
        label {
            font-weight: bold;
        }
        input, textarea {
            width: 100%;
            padding: 8px;
            margin: 5px 0;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        button {
            background: #005B9F;
            color: white;
            padding: 10px;
            border: none;
            cursor: pointer;
            width: 100%;
            border-radius: 4px;
        }
        button:hover {
            background: #00407a;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>William Meyer</h1>
        <h3>Financial Planner at Lonfin Group | Authorised by Sanlam</h3>
        <hr>

        <div class="contact-info">
            <p><strong>Contact Me</strong></p>
            <p>Email: <a href="mailto:w.meyer@sanlam4u.co.za">w.meyer@sanlam4u.co.za</a></p>
            <p>Cell: <a href="tel:+27634229601">+27 63 422 9601</a></p>
        </div>

        <div class="section">
            <h2>About Me</h2>
            <p>I’m William Meyer, a driven individual who is dedicated and passionate about personal growth.  
               I believe in the power of hard work, perseverance, and continuous learning to achieve success.  
               Challenges motivate me, and I am always striving to push beyond my limits to grow and improve.  
               My goal is to make a meaningful impact in everything I do, inspiring those around me to pursue their ambitions  
               with confidence and determination. Success, for me, is not just about personal achievement but also about  
               uplifting others and making a positive difference in the world.</p>
        </div>

        <div class="section">
            <h2>Qualifications</h2>
            <ul>
                <li>BCom in Business Management</li>
                <li>2 Years of Experience in Financial Planning</li>
                <li>Authorised Financial Planner at Sanlam</li>
            </ul>
        </div>

        <div class="section">
            <h2>Services Offered</h2>
            <h3>Investment Solutions</h3>
            <ul>
                <li>Unit Trusts</li>
                <li>Tax-Free Savings Accounts</li>
                <li>Wealth and Portfolio Management</li>
            </ul>

            <h3>Retirement Planning</h3>
            <ul>
                <li>Retirement Annuities</li>
                <li>Pension and Provident Funds</li>
                <li>Preservation Funds</li>
            </ul>

            <h3>Insurance Solutions</h3>
            <ul>
                <li>Life Insurance</li>
                <li>Disability Cover</li>
                <li>Income Protection</li>
                <li>Severe Illness Cover</li>
            </ul>

            <h3>Estate and Legacy Planning</h3>
            <ul>
                <li>Wills and Trusts</li>
                <li>Estate Administration</li>
            </ul>

            <h3>Business Financial Planning</h3>
            <ul>
                <li>Business Assurance</li>
                <li>Key Person Insurance</li>
                <li>Buy-and-Sell Agreements</li>
            </ul>
        </div>

        <div class="section">
            <h2>Location</h2>
            <p>Find me at: <strong>1st Floor, Century Way, The Colosseum, Cape Town, South Africa</strong></p>
        </div>

        <div class="section meeting-form">
            <h2>Book a Meeting</h2>
            <form action="mailto:w.meyer@sanlam4u.co.za" method="post" enctype="text/plain">
                <label for="name">Name:</label>
                <input type="text" id="name" name="Name" required>

                <label for="surname">Surname:</label>
                <input type="text" id="surname" name="Surname" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="Email" required>

                <label for="contact">Contact Number:</label>
                <input type="tel" id="contact" name="Contact" required>

                <label for="message">Additional Details (Optional):</label>
                <textarea id="message" name="Message" rows="4"></textarea>

                <!-- New fields for selecting the date and time -->
                <label for="meeting-date">Preferred Meeting Day:</label>
                <input type="date" id="meeting-date" name="Meeting Day" required>

                <label for="meeting-time">Preferred Time:</label>
                <input type="time" id="meeting-time" name="Meeting Time" required>

                <button type="submit">Send Meeting Request</button>
            </form>
        </div>

        <div class="section">
            <h2>Connect with Me</h2>
            <p><a href="https://www.sanlam.com/" target="_blank">Visit Sanlam's Website</a></p>
            <p><a href="https://www.linkedin.com/in/william-meyer-a86677235/" target="_blank">Connect on LinkedIn</a></p>
        </div>
    </div>

</body>
</html>

