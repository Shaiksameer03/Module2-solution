<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        .title-region {
            background-color: #3498db; /* Set your desired background color */
            padding: 20px;
            text-align: center;
            color: #ffffff; /* Set text color for better visibility */
        }

        .content {
            width: 80%; /* Set your desired width */
            margin: 20px auto; /* Center the content */
            float: left;
        }

        @media only screen and (max-width: 600px) {
            /* Adjust styles for smaller screens */
            .content {
                width: 100%;
                float: none; /* Clear the float for better stacking on smaller screens */
            }
        }
    </style>
    <title>Responsive Design</title>
</head>
<body>

    <div class="title-region">
        <h1>Thank you coursera</h1>
    </div>
    <div class="content">
        <p>This is the main content area of coursera.</p>
    </div>

    <div class="sidebar">
        <p>This is the sidebar area of coursera.</p>
    </div>

</body>
</html
