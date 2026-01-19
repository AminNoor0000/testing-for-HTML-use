<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Webpage</title>
    <style>
        /* General Page Styling */
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            color: #333;
            line-height: 1.6;
            padding: 40px;
            max-width: 800px;
            margin: auto;
        }

        h1 {
            color: #2c3e50;
            border-bottom: 2px solid #3498db;
            padding-bottom: 10px;
        }

        h2 {
            color: #2980b9;
            margin-top: 30px;
        }

        a {
            color: #3498db;
            text-decoration: none;
            font-weight: bold;
        }

        a:hover {
            text-decoration: underline;
        }

        img {
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            max-width: 100%;
            height: auto;
        }

        /* Table Styling */
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
            background-color: white;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        th, td {
            text-align: left;
            padding: 12px;
            border: 1px solid #ddd;
        }

        th {
            background-color: #3498db;
            color: white;
        }

        tr:nth-child(even) {
            background-color: #f2f2f2;
        }

        /* Button Styling */
        button {
            background-color: #3498db;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
            margin-top: 20px;
        }

        button:hover {
            background-color: #2980b9;
        }
    </style>
</head>
<body>

    <h1>Welcome to My Website</h1>
    <p>This is my first HTML webpage. I am learning how to build websites!</p>

    <h2>About Me</h2>
    <p>I am a beginner in web development.</p>

    <h2>Student List</h2>
    <table>
        <thead>
            <tr>
                <th>No.</th>
                <th>Name</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1</td>
                <td>HAZIM BIN ISHAK</td>
            </tr>
            <tr>
                <td>2</td>
                <td>MOHD AMIN BIN NOOR SHAMSULAINEE</td>
            </tr>
            <tr>
                <td>3</td>
                <td>MUHAMMAD IRFAN BIN ZULKARNAIN</td>
            </tr>
        </tbody>
    </table>

    <h2>My Favorite Website</h2>
    <a href="https://www.google.com" target="_blank">Visit Google</a>

    <h2>My Image</h2>
    <img src="https://via.placeholder.com/150" alt="Sample Image">

    <br>

    <button type="button" onclick="alert('Hello! Thanks for clicking.')">Click Me</button>

</body>
</html>
