# index.html



<!--Creating a multimedia-rich webpage involves incorporating various elements like audio, video, forms, images, tables, and lists. Below is a sample HTML code that demonstrates how to achieve this-->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Multimedia Rich Webpage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        .container {
            max-width: 800px;
            margin: auto;
        }
        table {
            width: 100%;
            border-collapse: collapse;
        }
        table, th, td {
            border: 1px solid black;
        }
        th, td {
            padding: 10px;
            text-align: left;
        }
        ul {
            list-style-type: disc;
            padding-left: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Welcome to My Multimedia Rich Webpage</h1>

        <!-- Audio Element -->
        <h2>Audio</h2>
        <audio controls>
            <source src="audio/sample.mp3" type="audio/mpeg">
            Your browser does not support the audio element.
        </audio>

        <!-- Video Element -->
        <h2>Video</h2>
        <video width="600" controls>
            <source src="video/sample.mp4" type="video/mp4">
            Your browser does not support the video element.
        </video>

        <!-- Registration Form with Validation -->
        <h2>Registration Form</h2>
        <form action="/submit" method="post">
            <label for="username">Username:</label><br>
            <input type="text" id="username" name="username" required><br><br>

            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email" required><br><br>

            <label for="password">Password:</label><br>
            <input type="password" id="password" name="password" required minlength="8"><br><br>

            <input type="submit" value="Register">
        </form>

        <!-- Embedded Image -->
        <h2>Image</h2>
        <img src="images/sample.jpg" alt="Sample Image" width="600">

        <!-- Embedded Table -->
        <h2>Table</h2>
        <table>
            <tr>
                <th>Name</th>
                <th>Age</th>
                <th>City</th>
            </tr>
            <tr>
                <td>John Doe</td>
                <td>30</td>
                <td>New York</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>25</td>
                <td>Los Angeles</td>
            </tr>
        </table>

        <!-- List -->
        <h2>List</h2>
        <ul>
            <li>Item 1</li>
            <li>Item 2</li>
            <li>Item 3</li>
        </ul>
    </div>
</body>
</html>
