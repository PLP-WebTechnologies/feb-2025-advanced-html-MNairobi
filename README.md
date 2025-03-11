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
    <title>Advanced HTML5 Elements and Forms</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>Welcome to Advanced HTML5</h1>
    </header>
    
    <!-- Navigation Section -->
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    
    <!-- Main Content Section -->
    <main>
        <section id="home">
            <h2>About Advanced HTML5</h2>
            <p>HTML5 introduces new elements for multimedia, forms, and semantic markup.</p>
        </section>
        
        <!-- Ordered List with Roman Numerals -->
        <section>
            <h2>Ordered List Example</h2>
            <ol type="I">
                <li>COle Palmer</li>
                <li>Noni Maduke</li>
                <li>Enzo Fernades</li>
            </ol>
        </section>
        
        <!-- External Image -->
        <section>
            <h2>Image from Pexels</h2>
            <img src="https://www.pexels.com/photo/facade-of-fc-chelsea-in-london-14433620/" alt="Chelsea FC" width="600">
        </section>
        
        <!-- Table of Contacts -->
        <section>
            <h2>Contact List</h2>
            <table border="1">
                <tr>
                    <th>Name</th>
                    <th>Address</th>
                    <th>Mobile</th>
                    <th>Email</th>
                </tr>
                <tr>
                    <td>Nick Kiriinya</td>
                    <td>82 Meru</td>
                    <td>0757964069</td>
                    <td>nick@example.com</td>
                </tr>
                <tr>
                    <td>Mercy KArimi</td>
                    <td>82 Meru</td>
                    <td>0726786670</td>
                    <td>mercy@example.com</td>
                </tr>
                <tr>
                    <td>Faith Kendi</td>
                    <td>82 Maua</td>
                    <td>0756276288</td>
                    <td>faith@example.com</td>
                </tr>
                <tr>
                    <td>Carol Kaimura</td>
                    <td>32 Nanyuki</td>
                    <td>0710843789</td>
                    <td>carol@example.com</td>
                </tr>
                <tr>
                    <td>Ian Kimathi</td>
                    <td>65 Kibirichia</td>
                    <td>0736257237</td>
                    <td>ian@example.com</td>
                </tr>
            </table>
        </section>
        
        <!-- Registration Form -->
        <section>
            <h2>Registration Form</h2>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" placeholder="Enter your name" required>
                <br>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" placeholder="Enter your email" required>
                <br>
                
                <label for="password">Password:</label>
                <input type="password" id="password" name="password" placeholder="Enter your password" required>
                <br>
                
                <label for="dob">Date of Birth:</label>
                <input type="date" id="dob" name="dob" required>
                <br>
                
                <label>Gender:</label>
                <input type="radio" name="gender" value="male"> Male
                <input type="radio" name="gender" value="female"> Female
                <br>
                
                <label for="country">Country:</label>
                <select id="country" name="country">
                    <option value="kenya">KENYA</option>
                    <option value="usa">USA</option>
                    <option value="uk">UK</option>
                    <option value="canada">Canada</option>
                </select>
                <br>
                
                <label>Interests:</label>
                <input type="checkbox" name="interests" value="sports"> Sports
                <input type="checkbox" name="interests" value="music"> Music
                <input type="checkbox" name="interests" value="coding"> Coding
                <br>
                
                <input type="submit" value="Register">
            </form>
        </section>
    </main>
    
    <!-- Footer Section -->
    <footer>
        <p>Contact us at: <a href="mailto:nicholuskiriinya7@gmail.com">nicholuskiriinya7@gmail.com"</a></p>
    </footer>
</body>
</html>
