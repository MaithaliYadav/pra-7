<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tube Rates | Profile Page</title>
    <style>
        /* 1. Background & General Layout */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #eef2f3; /* Light professional background */
            margin: 0;
            padding: 0;
            color: #333;
        }

        /* 2. Navigation Styling */
        nav {
            background-color: #1a2a6c; /* Deep blue background */
            padding: 1rem;
            text-align: center;
            border-bottom: 5px solid #f2a900; /* Contrast gold border */
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
            padding: 8px 12px;
            border-radius: 5px;
            transition: background 0.3s;
        }
        nav a:hover {
            background-color: #f2a900;
            color: #1a2a6c;
        }

        /* 3. Profile Card Layout */
        .profile-card {
            max-width: 600px;
            margin: 50px auto;
            background: #ffffff;
            padding: 40px;
            border: 2px solid #ddd; /* Layout border */
            border-radius: 15px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
            text-align: center;
        }

        /* 4. Circular Border & Avatar */
        .avatar {
            width: 100px;
            height: 100px;
            background: #1a2a6c;
            border: 4px solid #f2a900;
            border-radius: 50%; /* Perfect circle */
            margin: 0 auto 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 2rem;
            font-weight: bold;
        }

        /* 5. Text Styling */
        h1 {
            margin: 0;
            color: #1a2a6c;
            text-transform: uppercase;
            letter-spacing: 2px;
        }
        .usn-text {
            color: #666;
            font-style: italic;
            margin-bottom: 20px;
        }

        /* 6. Rates Table (Border Layouts) */
        table {
            width: 100%;
            border-collapse: collapse; /* Merges borders */
            margin-top: 25px;
        }
        th, td {
            padding: 12px;
            border: 1px solid #ccc; /* Table grid borders */
            text-align: left;
        }
        th {
            background-color: #f8f9fa;
            color: #1a2a6c;
        }
        tr:nth-child(even) {
            background-color: #f9f9f9; /* Zebra striping background */
        }
    </style>
</head>
<body>

    <!-- Navigation -->
    <nav>
        <a href="#">Dashboard</a>
        <a href="#">Tube Inventory</a>
        <a href="#">Rate Card</a>
        <a href="#">Contact Support</a>
    </nav>

    <!-- Main Profile Layout -->
    <div class="profile-card">
        <div class="avatar">MY</div>
        <h1>Maithali.S.Yadav</h1>
        <p class="usn-text">USN: CS25153 | Section: C</p>
        <hr style="border: 0; border-top: 1px solid #eee;">

        <h3>Current Tube Rates</h3>
        <table>
            <thead>
                <tr>
                    <th>Material Type</th>
                    <th>Standard Rate</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Galvanized Steel</td>
                    <td>₹450 / meter</td>
                </tr>
                <tr>
                    <td>Copper Precision</td>
                    <td>₹1,200 / meter</td>
                </tr>
                <tr>
                    <td>PVC Flexible</td>
                    <td>₹85 / meter</td>
                </tr>
            </tbody>
        </table>
    </div>

</body>
</html>
