# feb-2025-avasjcript-events-and-basic-interactivity
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JavaScript Events and Interactivity</title>
    <style>
        /* Basic styles for the webpage */
        body {
            font-family: Arial, sans-serif;
            padding: 20px;
        }
        .interactive-button {
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            background-color: lightblue;
            border: none;
            border-radius: 5px;
        }
        .hover-text {
            margin-top: 20px;
            font-size: 18px;
            color: #333;
        }
        .form-container {
            margin-top: 30px;
        }
        input[type="text"], button {
            padding: 10px;
            font-size: 16px;
            margin: 5px;
        }
        .error-message {
            color: red;
            font-size: 14px;
        }
    </style>
</head>
<body>

    <!-- Interactive button that changes text on click -->
    <button class="interactive-button" id="changeTextButton">Click Me to Change Text</button>
    <p id="message">Hello, click the button above!</p>

    <!-- Text that changes on hover -->
    <div class="hover-text" id="hoverText">
        Hover over the button below to change this text.
    </div>
    
    <button id="hoverButton">Hover Me!</button>

    <!-- Form with input field and submit button -->
    <div class="form-container">
        <h3>Form Validation Example</h3>
        <form id="sampleForm" action="#">
            <label for="userName">Enter your name: </label>
            <input type="text" id="userName" name="userName" required>
            <button type="submit">Submit</button>
        </form>
        <p class="error-message" id="errorMessage"></p>
    </div>

    <script>
        // 1. Event Listener to change the text when the button is clicked
        document.getElementBy
