# index.html


<title>Advanced HTML5 Elements and Forms</title>
Advanced HTML5 Elements and Forms
<!-- Ordered List with Roman Numerals -->
<section>
    <h2>Ordered List with Roman Numerals</h2>
    <ol type="I">
        <li>First item</li>
        <li>Second item</li>
        <li>Third item</li>
        <li>Fourth item</li>
        <li>Fifth item</li>
    </ol>
</section>

<!-- External Image from Pexels -->
<section>
    <h2>Image from Pexels</h2>
    <img src="https://images.pexels.com/photos/335037/pexels-photo-335037.jpeg" alt="Beautiful Landscape" width="600">
</section>

<!-- Table of 5 Contacts -->
<section>
    <h2>Contact Table</h2>
    <table border="1">
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
                <td>123 Main St, City</td>
                <td>123-456-7890</td>
                <td>john.doe@email.com</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>456 Elm St, City</td>
                <td>234-567-8901</td>
                <td>jane.smith@email.com</td>
            </tr>
            <tr>
                <td>Mark Taylor</td>
                <td>789 Oak St, City</td>
                <td>345-678-9012</td>
                <td>mark.taylor@email.com</td>
            </tr>
            <tr>
                <td>Lucy Adams</td>
                <td>101 Pine St, City</td>
                <td>456-789-0123</td>
                <td>lucy.adams@email.com</td>
            </tr>
            <tr>
                <td>Paul Brown</td>
                <td>202 Cedar St, City</td>
                <td>567-890-1234</td>
                <td>paul.brown@email.com</td>
            </tr>
        </tbody>
    </table>
</section>

<!-- Registration Form -->
<section>
    <h2>Registration Form</h2>
    <form action="/submit_form" method="POST" id="registrationForm">
        <!-- Name Field -->
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your name" required>
        <br>

        <!-- Email Field -->
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email" required>
        <br>

        <!-- Password Field -->
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Enter your password" required>
        <br>

        <!-- Date Field -->
        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required>
        <br>

        <!-- Dropdown Menu -->
        <label for="country">Country:</label>
        <select id="country" name="country" required>
            <option value="us">United States</option>
            <option value="ca">Canada</option>
            <option value="uk">United Kingdom</option>
            <option value="au">Australia</option>
        </select>
        <br>

        <!-- Radio Buttons -->
        <fieldset>
            <legend>Gender:</legend>
            <input type="radio" id="male" name="gender" value="male" required>
            <label for="male">Male</label>
            <br>
            <input type="radio" id="female" name="gender" value="female" required>
            <label for="female">Female</label>
        </fieldset>
        <br>

        <!-- Checkboxes -->
        <fieldset>
            <legend>Interests:</legend>
            <input type="checkbox" id="sports" name="interests" value="sports">
            <label for="sports">Sports</label>
            <br>
            <input type="checkbox" id="music" name="interests" value="music">
            <label for="music">Music</label>
            <br>
            <input type="checkbox" id="travel" name="interests" value="travel">
            <label for="travel">Travel</label>
        </fieldset>
        <br>

        <!-- Submit Button -->
        <button type="submit">Submit</button>
    </form>
</section>

<!-- Footer Section -->
<footer>
    <p>&copy; 2025 Your Company</p>
</footer>

