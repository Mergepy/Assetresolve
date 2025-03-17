<?php
if ($_SERVER["REQUEST_METHOD"] == "POST") {
    $to = "bonchasx@gmail.com"; // Admin email
    $subject = "New Form Submission";

    // Capture form data
    $message = "<html><body>";
    $message .= "<h2 style='color: #333;'>New Form Submission Details</h2>";
    $message .= "<table style='width: 100%; border-collapse: collapse;'>";
    $message .= "<tr><th style='border: 1px solid #ddd; padding: 10px; background: #f4f4f4;'>Field</th><th style='border: 1px solid #ddd; padding: 10px; background: #f4f4f4;'>Value</th></tr>";

    $submittedData = "";
    foreach ($_POST as $key => $value) {
        $message .= "<tr><td style='border: 1px solid #ddd; padding: 10px;'>" . ucfirst($key) . "</td>
                     <td style='border: 1px solid #ddd; padding: 10px;'>" . htmlspecialchars($value) . "</td></tr>";

        $submittedData .= "<p><strong>" . ucfirst($key) . ":</strong> " . htmlspecialchars($value) . "</p>";
    }

    $message .= "</table>";
    $message .= "<p style='margin-top: 20px; font-size: 14px; color: #777;'>This is an automated email from your website form.</p>";
    $message .= "</body></html>";

    // Email headers for HTML email
    $headers = "From: assetresolve744@gmail.com\r\n";  // Change to your domain email
    $headers .= "Reply-To: assetresolve744@gmail.com\r\n";
    $headers .= "Content-Type: text/html; charset=UTF-8\r\n";

    // Send the email
    if (mail($to, $subject, $message, $headers)) {
        $status = "success";
    } else {
        $status = "error";
    }
} else {
    $status = "invalid";
}
?>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Submission Status</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .container {
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            max-width: 500px;
            text-align: center;
        }
        .icon {
            font-size: 50px;
            margin-bottom: 10px;
        }
        .success { color: #4CAF50; }
        .error { color: #D32F2F; }
        .message {
            font-size: 18px;
            margin-bottom: 15px;
        }
        .submitted-data {
            text-align: left;
            background: #f9f9f9;
            padding: 10px;
            border-radius: 5px;
            margin-top: 15px;
        }
        .home-btn {
            display: inline-block;
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #007BFF;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            transition: 0.3s;
        }
        .home-btn:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>

<div class="container">
    <?php if ($status == "success") { ?>
        <div class="icon success">✅</div>
        <h2>Details Submitted Successfully!</h2>
        <p class="message">Thank you! Your form has been submitted successfully.</p>
        <div class="submitted-data">
            <h3>Submission Details:</h3>
            <?php echo $submittedData; ?>
        </div>
    <?php } elseif ($status == "error") { ?>
        <div class="icon error">❌</div>
        <h2>Submission Failed</h2>
        <p class="message">Oops! Something went wrong. Please try again.</p>
    <?php } else { ?>
        <div class="icon error">⚠️</div>
        <h2>Invalid Request</h2>
        <p class="message">You are not allowed to access this page directly.</p>
    <?php } ?>

    <a href="/" class="home-btn">Go to Homepage</a>
</div>

</body>
</html>
