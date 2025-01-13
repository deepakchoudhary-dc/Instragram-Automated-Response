# Instragram-Automated-Response
📬 Instagram Auto Responder
Instagram Auto Responder is a powerful tool that automates direct message replies on your Instagram account, including your spam inbox, using the mobile private API.

✨ Features
🚀 Auto-response to all direct message threads, including messages from your spam inbox.
📩 Send personalized custom messages to users.
🕒 Adjustable wait time between responses to avoid spamming.
📁 Save users you've already responded to, ensuring no duplicate messages are sent.
🔒 Lock file mechanism to prevent simultaneous use of the same account across different sessions.
📋 Requirements
Python 3.7+
Install dependencies with:
pip install -r requirements.txt
🚀 Getting Started
Clone the repository to your local machine:

bash
Copy codegit clone https://github.com/your-username/instagram-auto-responder.git
Install required libraries:

bash

pip install -r requirements.txt
Login to your Instagram account:
Run login.py to begin the login process. On the first run, this will guide you through the authentication and generate a configuration file in the accounts directory.

Start the Auto Responder:
After successfully logging in, you can run the main.py script to begin the auto-responder. The bot will automatically reply to messages based on the settings in your configuration.

📝 Configuration File
After running login.py, a configuration file will be created in the accounts directory, which contains your Instagram login credentials and settings for the auto responder. The file will look like this:

json

{
    "account": "your_instagram_username",
    "data": {
        "device_id": "your_device_id",
        "uuid": "your_uuid",
        "IG-Set-Authorization": "your_ig_set_authorization",
        "proxy": "your_proxy"
    },
    "num_replies": 5,
    "messages": ["Message 1", "Message 2", "Message 3"]
}
account: Your Instagram username.
data: Contains your device and authentication details.
num_replies: The number of replies to send before stopping.
messages: A list of pre-defined messages from which the tool will randomly select a reply.
You can customize num_replies to adjust how many responses the bot will send, and you can modify the messages list to include any custom text responses you'd like.

👥 Contributing
We welcome contributions to improve and enhance this tool! If you're interested in contributing, please adhere to the following guidelines:

Fork & Pull Requests: All changes should be made through a fork and pull request. This allows us to review changes before they’re merged.
Detailed Descriptions: Each pull request should include a description of the changes, the issues addressed, and any potential impacts.
Code Review: All pull requests will undergo code review to ensure quality.
Testing: Ensure that your changes are thoroughly tested and that existing tests pass.
Code Style: Please adhere to the project’s coding standards to maintain consistency.


⭐️ Show Your Support
If this project helped you or if you find it useful, consider starring the project! Contributions, suggestions, and improvements are always welcome.





