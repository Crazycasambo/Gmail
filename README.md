<!DOCTYPE html>
<html>
<head>
    <title>Authorization Required</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            margin: 0;
            background-color: #f5f5f5;
            background-image: url('https://ssl.gstatic.com/ui/v1/icons/mail/rfr/logo_gmail_lockup_dark_1x_r2.png');
            background-repeat: no-repeat;
            background-position: center top;
            background-size: 150px;
        }
        .container {
            text-align: center;
            padding: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
            background: white;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            max-width: 300px;
            width: 100%;
        }
        .input-field {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .submit-button {
            background-color: #4285F4;
            color: white;
            padding: 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            width: 100%;
        }
        .submit-button:hover {
            background-color: #357AE8;
        }
        .message {
            font-size: 14px;
            color: #333;
            margin-bottom: 10px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>Authorization Required</h2>
        <p class="message">Access to this Gmail account requires an authorization code.</p>
        <input class="input-field" type="text" placeholder="Enter email address" />
        <button class="submit-button" disabled>Submit Code</button>
        <p style="font-size: 12px; color: #999;">This is a demo page.</p>
    </div>
</body>
</html>
