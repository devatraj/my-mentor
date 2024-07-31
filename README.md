# My Mentor

Welcome to **My Mentor**, a full-stack web application dedicated to helping students find mentors, study pairs, and solutions to their academic queries. This platform allows students to ask doubts, join study groups, and engage in topic-specific discussions.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)

## Features

- **Group-Based Learning**: Seamlessly join topic-specific groups tailored for focused and in-depth discussions. Each group is meticulously organized to foster an environment conducive to learning and peer interaction.
- **Interactive Chat**: Experience the power of real-time communication with our interactive chat feature. Engage with peers, ask questions, and receive instant responses, all within a dynamic and user-friendly chat interface.
- **Create and Publish Groups**: Empower yourself by creating your own study groups. Publish these groups to invite others, fostering a community of learners who can collaborate and support each other.
- **User-Friendly Interface**: Navigate effortlessly through our intuitively designed interface. Our platform is crafted to provide a seamless user experience, ensuring that you can focus on what matters most – learning.
- **Secure and Reliable**: Built on the robust Django framework and utilizing the reliable SQLite3 database, our application ensures top-notch performance and security. Your data is safe, and the platform is designed to handle heavy usage without compromising on speed or efficiency.
![image](https://github.com/user-attachments/assets/b3e0c407-2349-46e6-9ef7-e496c32720ac)
![image](https://github.com/user-attachments/assets/c1add4ce-014d-429f-8843-ea089320e2cb)
![image](https://github.com/user-attachments/assets/10f0a6cf-d451-43f5-9aa3-fb47f17124ec)
![image](https://github.com/user-attachments/assets/2845dbc6-e880-4e5b-ab21-6229d57045a4)



## Tech Stack

Our application is built using a powerful and modern tech stack to ensure high performance, scalability, and a smooth user experience.

- **Frontend**: Developed using the latest HTML5 standards for structure, CSS3 for styling, and JavaScript for interactivity. Our frontend is responsive, ensuring optimal performance across all devices, from desktops to mobile phones.
- **Backend**: Powered by Django, a high-level Python web framework that promotes rapid development and clean, pragmatic design. Django's built-in features and its robust architecture allow us to develop a secure and scalable application efficiently.
- **Database**: Leveraging SQLite3, a lightweight, disk-based database that doesn’t require a separate server process. SQLite3 is highly reliable and full-featured, perfect for the needs of our application.
- **Real-Time Communication**: Implemented using WebSocket technology, allowing for real-time, bidirectional communication between the server and the client. This ensures that our chat feature is instant and responsive, providing a seamless user experience.
- **Security**: Employing the latest security practices and protocols, including HTTPS, to ensure that all data transmitted between the client and the server is encrypted and secure. Django's built-in security features, such as protection against SQL injection, cross-site scripting, and cross-site request forgery, are utilized extensively.

With this tech stack, we ensure that **My Mentor** is not only feature-rich but also secure, efficient, and scalable, ready to support a growing community of learners.


## Installation

Follow these steps to set up the project locally.

### Prerequisites

Ensure you have the following installed:

- Python (version 3.6 or above)
- pip (Python package installer)

### Steps

1. **Clone the repository**:

    ```bash
    git clone https://github.com/devatraj/My-Mentor.git
    cd My-Mentor
    ```

2. **Create a virtual environment**:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required packages**:

    ```bash
    pip install -r requirements.txt
    ```

4. **Apply migrations**:

    ```bash
    python manage.py migrate
    ```

5. **Run the development server**:

    ```bash
    python manage.py runserver
    ```

6. **Access the application**:

    Open your web browser and go to `http://127.0.0.1:8000`

### Creating Superuser

To manage the application, create a superuser:

```bash
python manage.py createsuperuser
