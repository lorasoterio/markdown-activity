#  **Comparative Study on Bus Seat Reservation System with AI Chatbot vs Manual Booking**

---

## **Project Description**

This project presents a **comparative analysis** between two booking approaches:
1. An **AI Chatbot-integrated Bus Seat Reservation System**.
2. The traditional **Manual Booking Process**.

The purpose of this study is to evaluate the **efficiency, user experience, and accuracy** between both systems.  
By leveraging conversational AI, the chatbot aims to assist users in:
- Reserving bus seats through guided conversation.
- Inquiring about bus schedules, fares, and seat availability.
- Reducing human error and processing time compared to manual transactions.

The study ultimately seeks to identify whether integrating an **AI-driven helpdesk assistant** can streamline transportation services and enhance user satisfaction.

---

## **Features**

- **AI Chatbot Assistant** – Helps users inquire and book bus seats through conversation.  
- **Seat Visualization System** – Displays seat availability using color indicators (e.g., green = available, red = reserved).  
- **Booking Management** – Allows users to confirm, cancel, and modify seat reservations.  
- **Automated Inquiry Handling** – Provides instant responses to frequently asked questions.  
- **Admin Dashboard** – Enables admins to manage buses, schedules, and booking records.  
- **Comparative Evaluation Module** – Collects and compares user data between chatbot-assisted and manual booking.

## **Installation Steps**

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/bus-seat-reservation-chatbot.git

# 2. Navigate to the project directory
cd bus-seat-reservation

# 3. Install Pipenv if you haven’t yet
pip install pipenv

# 4. Create a new virtual environment and install dependencies
pipenv install

# 5. Activate the virtual environment
pipenv shell

# 6. Configure environment variables
DB_NAME=dbname
DB_USER=postgres
DB_PASSWORD=password
DB_HOST=localhost
DB_PORT=port
OPENAI_API_KEY=openai_api_key
DIALOGFLOW_PROJECT_ID=project_id

# 7.Run database migrations
python manage.py migrate

# 8. Start the backend server
python manage.py runserver


```

![App Screenshot](images/screenshot.png) 
![App Screenshot](images/screenshot2.png)


---

## Technologies Used
| Layer              | Tools / Frameworks                          |
| :----------------- | :------------------------------------------ |
| **Frontend**       | HTML, CSS, JavaScript, React.js             |
| **Backend**        | Python (Django)                             |
| **Database**       | PostgreSQL                                  |
| **AI Integration** | Dialogflow, OpenAI API, or Custom NLP Model |

---

# Contributors
- Lora Soterio
- Mikyla Dasco
- Jecel Baitan
- Vea Santillan
- Mark Lawrence Pider
- Vougn Jeric Jardinero