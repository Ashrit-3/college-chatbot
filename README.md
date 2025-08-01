# college-chatbot
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>College Info Chatbot</title>
    <style>
      body {
        font-family: Arial, sans-serif;
        text-align: center;
        margin-top: 50px;
        background: #f2f6fc;
      }
      h1 {
        color: #003366;
      }
    </style>
    <!-- Dialogflow script -->
    <script src="https://www.gstatic.com/dialogflow-console/fast/messenger/bootstrap.js?v=1"></script>
  </head>
  <body>
    <h1>Ask Me Anything About College 📚</h1>
    
    <!-- Chat widget -->
    <df-messenger
      chat-title="CollegeBot"
      agent-id="YOUR-AGENT-ID-HERE"
      language-code="en"
    ></df-messenger>
  </body>
</html>
