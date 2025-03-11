# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Registration Page</title>
        <style>
            body {
                font-family: 'Poppins', sans-serif;
                margin: 0;
                padding: 20px;
                background: linear-gradient(135deg, #f5f7fa, #c3cfe2);
                color: #333;
            }
            header {
                background: #4a90e2;
                color: white;
                text-align: center;
                padding: 1.5em;
                font-size: 1.5em;
                font-weight: bold;
            }
            main {
                max-width: 900px;
                margin: 30px auto;
                background: white;
                padding: 25px;
                border-radius: 12px;
                box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
            }
            h2 {
                color: #4a90e2;
                border-bottom: 2px solid #ddd;
                padding-bottom: 5px;
            }
            img {
                width: 100%;
                max-height: 300px;
                object-fit: cover;
                border-radius: 12px;
            }
            table {
                width: 100%;
                border-collapse: collapse;
                margin-top: 20px;
                background: white;
            }
            th, td {
                border: 1px solid #ddd;
                padding: 12px;
                text-align: left;
            }
            th {
                background: #4a90e2;
                color: white;
            }
            form {
                margin-top: 20px;
            }
            label {
                display: block;
                margin-top: 12px;
                font-weight: bold;
            }
            input, select {
                width: 100%;
                padding: 10px;
                margin-top: 5px;
                border: 1px solid #ccc;
                border-radius: 6px;
            }
            button {
                margin-top: 20px;
                background: #4a90e2;
                color: white;
                padding: 12px;
                border: none;
                border-radius: 6px;
                cursor: pointer;
                font-size: 1em;
                font-weight: bold;
            }
            button:hover {
                background: #357ab7;
            }
        </style>
    </head>
    <body>
        <header>
            <h1>Welcome to Our Registration Page</h1>
        </header>
        
    <main>
        <h2>Our Services</h2>
        <ol type="I">
            <li>Web Development</li>
            <li>Graphic Design</li>
            <li>SEO Optimization</li>
            <li>Cloud Computing</li>
            <li>Cybersecurity</li>
        </ol>
        
        <h2>Featured Image</h2>
        <img src="https://images.pexels.com/photos/3183197/pexels-photo-3183197.jpeg" alt="Professional Workspace">
        
        <h2>Contact List</h2>
        <table>
            <tr>
                <th>Name</th>
                <th>Address</th>
                <th>Mobile</th>
                <th>Email</th>
            </tr>
            <tr>
                <td>Wambua Michael</td>
                <td>123 Karatina, City</td>
                <td>+2541234567890</td>
                <td>sylvester@gmail.com</td>
            </tr>
            <tr>
                <td>Wambua Michael</td>
                <td>123 Karatina, City</td>
                <td>+2541234567890</td>
                <td>sylvester@gmail.com</td>
            </tr>
            <tr>
                <td>Wambua Michael</td>
                <td>123 Karatina, City</td>
                <td>+2541234567890</td>
                <td>sylvester@gmail.com</td>
            </tr>
            <tr>
                <td>Wambua Michael</td>
                <td>123 Karatina, City</td>
                <td>+2541234567890</td>
                <td>sylvester@gmail.com</td>
            </tr>
            <tr>
                <td>Wambua Michael</td>
                <td>123 Karatina, City</td>
                <td>+2541234567890</td>
                <td>sylvester@gmail.com</td>
            </tr>
        </table>
        
        <h2>Registration Form</h2>
        <form>
            <label for="name">Full Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your full name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>
            
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter a secure password" required>
            
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required>
            
            <label for="gender">Gender:</label>
            <select id="gender" name="gender" required>
                <option value="">Select Gender</option>
                <option value="male">Male</option>
                <option value="female">Female</option>
                <option value="other">Other</option>
            </select>
            
            <label>Preferred Contact Method:</label>
            <input type="radio" id="phone" name="contact" value="phone" required>
            <label for="phone">Phone</label>
            <input type="radio" id="emailContact" name="contact" value="email" required>
            <label for="emailContact">Email</label>
            
            <label>Interests:</label>
            <input type="checkbox" id="coding" name="interests" value="coding">
            <label for="coding">Coding</label>
            <input type="checkbox" id="design" name="interests" value="design">
            <label for="design">Design</label>
            <input type="checkbox" id="gaming" name="interests" value="gaming">
            <label for="gaming">Gaming</label>
            
            <button type="submit">Register</button>
        </form>
     </main>
    </body>
    </html>

