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
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 8px;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>

    <!-- Ordered list with Roman numerals -->
    <h2>Ordered List</h2>
    <ol type="I">
        <li>First Item</li>
        <li>Second Item</li>
        <li>Third Item</li>
    </ol>

    <!-- External Image -->
    <h2>Image</h2>
    <img src="https://images.pexels.com/photos/35600/pexels-photo.jpg" alt="Beautiful Landscape" width="600">

    <!-- Table of Contacts -->
    <h2>Contact List</h2>
    <table>
        <thead>
            <tr>
                <th>Name</th>
                <th>Address</th>
                <th>Mobile</th>
                <th>Email</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>John Doe</td>
                <td>123 Elm St, Springfield</td>
                <td>(555) 123-4567</td>
                <td>john.doe@example.com</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>456 Oak St, Springfield</td>
                <td>(555) 234-5678</td>
                <td>jane.smith@example.com</td>
            </tr>
            <tr>
                <td>Sam Wilson</td>
                <td>789 Pine St, Springfield</td>
                <td>(555) 345-6789</td>
                <td>sam.wilson@example.com</td>
            </tr>
            <tr>
                <td>Amy Brown</td>
                <td>321 Maple St, Springfield</td>
                <td>(555) 456-7890</td>
                <td>amy.brown@example.com</td>
            </tr>
            <tr>
                <td>Tom Harris</td>
                <td>654 Cedar St, Springfield</td>
                <td>(555) 567-8901</td>
                <td>tom.harris@example.com</td>
            </tr>
        </tbody>
    </table>

    <!-- Registration Form -->
    <h2>Registration Form</h2>
    <form action="#" method="post">
        <label for="name">Name:</label><br>
        <input type="text" id="name" name="name" placeholder="Enter your name" value="David Maina" required><br><br>

        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" placeholder="Enter your email" value="daudikerr@gmail.com" required><br><br>

        <label for="password">Password:</label><br>
        <input type="password" id="password" name="password" placeholder="Enter your password" value="codeguru" required><br><br>

        <label for="dob">Date of Birth:</label><br>
        <input type="date" id="dob" name="dob" value="2025-04-04" required><br><br>

        <label for="gender">Gender:</label><br>
        <input type="radio" id="male" name="gender" value="male" required>
        <label for="male">Male</label>
        <input type="radio" id="female" name="gender" value="female">
        <label for="female">Female</label><br><br>

        <label for="country">Country:</label><br>
        <select id="country" name="country" required>
            <option value="">Select your country</option>
            <option value="usa">USA</option>
            <option value="uk">UK</option>
            <option value="canada">Canada</option>
            <option value="aus">Australia</option>
        </select><br><br>

        <label for="interests">Interests:</label><br>
        <input type="checkbox" id="music" name="interests" value="music">
        <label for="music">Music</label>
        <input type="checkbox" id="sports" name="interests" value="sports">
        <label for="sports">Sports</label>
        <input type="checkbox" id="reading" name="interests" value="reading">
        <label for="reading">Reading</label><br><br>

        <input type="submit" value="Register">
    </form>

</body>
</html>
