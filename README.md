🎉 Event Nest 🎉
Where events come alive!

Welcome to Event Nest, a dynamic and user-friendly web application that simplifies the process of organizing, registering, and participating in events. Whether you're hosting or attending, Event Nest provides a seamless experience with real-time communication and participant engagement.

🌟 Key Features
🗓 Event Organization & Registration
Effortlessly create and register for events using a sleek, user-friendly interface.
View events displayed as interactive cards on the homepage, dynamically updating based on your participation.

💬 Real-Time Chatrooms
Engage in event-specific chatrooms that offer a Discord-like interface, with a list of participants and an interactive chat window.
Username prompt before joining chats ensures personalized communication.
Messages are stored non-volatilely, meaning they remain visible even after page refreshes.

🧑‍💼 Profile & Badges
Track your event history on your personalized profile page, displaying past and upcoming events.
Earn exclusive badges for event participation:
🔴 Red Badge: Register for more than 5 events.
🟡 Gold Badge: Register for more than 10 events.

🌍 Multilingual Support
Event Nest is accessible to a diverse audience with multilingual support, making it easy for users from different regions to organize and participate.

📅 Event Detail Page
Each event comes with a detailed page that shows:
Registered participants list.
A convenient location button for quick navigation.
Dynamic buttons styled to enhance user experience.

💬 Public Chatroom
Participate in community-wide conversations with our public chatroom feature, designed for seamless group discussions without any online/offline user distinction.


⚙️ Tech Stack
Technology	Purpose
Flask	Backend framework powering the server and routing.
SocketIO	Enabling real-time communication for chatrooms.
SQLAlchemy	ORM for efficient database management.
MySQL	Database for storing event and user information.
HTML/CSS/JS	Frontend technologies for crafting the UI/UX.
Docker	(Planned) Containerization for easy deployment.

🏗️ Installation Guide
1. Clone the Repository
bash
Copy code
git clone https://github.com/your-username/event-nest.git
cd event-nest

3. Set Up a Virtual Environment
bash
Copy code
python3 -m venv venv
source venv/bin/activate  # For Linux/Mac
venv\Scripts\activate     # For Windows

5. Install Dependencies
bash
Copy code
pip install -r requirements.txt

7. Set Up the Database
Make sure you have MySQL installed and running.
Configure your database settings in the .env file (create one if not present):
bash
Copy code
DB_USER=yourusername
DB_PASSWORD=yourpassword
DB_NAME=event_nest

9. Run the Flask Application
bash
Copy code
flask run
Navigate to http://127.0.0.1:5000 in your browser to access Event Nest.

📸 Screenshots
Homepage with Event Cards

Event Detail Page

Chat Room Interface

🔑 Features Breakdown
Event Creation
Simple, intuitive form for creating events with fields for event title, description, date, and maximum number of participants.
Dynamic Event Cards
Events displayed as interactive cards on the homepage, which update based on the user’s participation. These cards are fully dynamic, showcasing upcoming and past events in real time.
Badging System
Your profile reflects your involvement with cool badges based on the number of events you’ve registered for, adding a fun, gamified element to event participation.
Real-Time Chat
Join event-specific chatrooms that feel like Discord, with a participant list on the left and messages on the right. Engage in live conversation with fellow attendees.
Admin Dashboard (Planned)
A streamlined interface for managing users and events, allowing admins to track user activity and oversee event logistics.
🌍 Multilingual Capabilities
We're committed to inclusivity—Event Nest supports multiple languages to ensure users from all backgrounds can easily navigate and participate. More languages are on the way!

🤖 Future Improvements
AI-Powered Suggestions for events based on user interests and past participation.
Mobile App for on-the-go event management and participation.
Enhanced Admin Tools for event organizers.
Notification System for event reminders and updates.
🤝 Contributing
We welcome contributions from the community! Please read our CONTRIBUTING.md for guidelines on how to contribute to Event Nest.

📄 License
This project is licensed under the MIT License. See the LICENSE file for more details.

✨ Join the Event Nest Community!
Have questions, feedback, or ideas? Feel free to reach out to us via Discord or open an issue on GitHub.

Designed and developed with ❤️ by TEAM.

