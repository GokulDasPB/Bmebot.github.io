<html>
<head>
    <title>Your Website</title>
</head>
<body>
    <!-- Header -->
    <header>
        <div id="logo-container">
            <img src="MyBME BOT.png" alt="BMEbot Logo">
            <script>
        // JavaScript code for image resizing
        var logo = document.getElementById("header-logo");
                    // Function to resize the image
        function resizeImage() {
            var maxWidth = 150; // Set your desired max width
            var maxHeight = 150; // Set your desired max height
            var width = logo.width;
            var height = logo.height;
            // Check if the current dimensions exceed the desired maximums
            if (width > maxWidth || height > maxHeight) {
                // Calculate the new dimensions while preserving the aspect ratio
                if (width / maxWidth > height / maxHeight) {
                    height = height * maxWidth / width;
                    width = maxWidth;
                } else {
                    width = width * maxHeight / height;
                    height = maxHeight;
                }
                // Apply the new dimensions to the image
                logo.width = width;
                logo.height = height;
            }
        }
        // Call the resize function when the image loads
        logo.onload = resizeImage;
        </div>
        <div id="header-text">
            <h1>BMEbot</h1>
            <p>Your Biomedical Buddy in Bytes!</p>
        </div>
    </header>
<p>BMEbotis your friendly guide to the fascinating world of biomedical engineering. Learn, explore, and discover with us!</p>
    <!-- Your Content Goes Here -->

    <!-- JavaScript -->
    <script>
    </script>
</body>
</html>
<html>
<head>
    <title>Newsletter Subscription</title>
    <style>
        /* Add custom CSS styles for the form and button */
        body {
            background: linear-gradient(90deg, #0097b2, #7ed957);
            text-align: center;
        }
        .newsletter-form {
            background-color: #fff;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
            max-width: 400px;
            margin: 0 auto;
        }
        .input-container {
            display: flex;
            justify-content: center;
            align-items: center;
            margin-bottom: 15px;
        }
        input[type="email"] {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button[type="submit"] {
            background-color: #0097b2;
            color: #fff;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <div class="newsletter-form">
        <h2>The Bulletin</h2>
        <p>A free Newsletter loaded with actionable steps to help you in your Biomedical career and also in your personal life. Become smarter in your professional and personal life with this weekly newsletter in just 5 mins or less. Join 100+ Subscribers Today !</p>
        <form id="subscription-form">
            <div class="input-container">
                <input type="email" id="email" name="email" placeholder="Enter your email" required>
            </div>
            <div class="input-container">
                <button type="submit">Subscribe</button>
            </div>
        </form>
    </div>

    <script>
        // JavaScript code for handling form submission (no Google Sheets integration)
        document.getElementById("subscription-form").addEventListener("submit", function (e) {
            e.preventDefault();
            const email = document.getElementById("email").value;
            // Here, you can add code to send the email to your server or Google Sheets.
            // This example only collects the email value.
            console.log("Subscribed with email:", email);
            // Clear the email input after submission
            document.getElementById("email").value = "";
        });
    </script>
</body>
</html>



.
<script type="text/javascript">
  (function(d, t) {
      var v = d.createElement(t), s = d.getElementsByTagName(t)[0];
      v.onload = function() {
        window.voiceflow.chat.load({
          verify: { projectID: '64f5a0eb99d6da00085c957d' },
          url: 'https://general-runtime.voiceflow.com',
          versionID: 'production'
        });
      }
      v.src = "https://cdn.voiceflow.com/widget/bundle.mjs"; v.type = "text/javascript"; s.parentNode.insertBefore(v, s);
  })(document, 'script');
</script>
