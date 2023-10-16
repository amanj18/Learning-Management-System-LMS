# Learning management system using django web framework

![1694373426380](static/README/1694373426380.png "Home Page")
![image](https://github.com/Amanj-18/Learning-Management-System-LMS/assets/89749348/cee67381-4ce3-486b-98c6-a22736e44fc1)
![image](https://github.com/Amanj-18/Learning-Management-System-LMS/assets/89749348/b512ce9d-f53f-438a-b516-5b4a7cc94b7d)
![image](https://github.com/Amanj-18/Learning-Management-System-LMS/assets/89749348/34ef4fb0-2ca3-418d-9b6b-5babdf776f5f)
![image](https://github.com/Amanj-18/Learning-Management-System-LMS/assets/89749348/ed8e6253-e467-416f-9f31-4c42f385ffac)
![image](https://github.com/Amanj-18/Learning-Management-System-LMS/assets/89749348/db123270-7d23-4a78-9edd-19dcc2955f1e)
![image](https://github.com/Amanj-18/Learning-Management-System-LMS/assets/89749348/edfeafb4-7033-4911-b25a-a17e57dbe3c9)
![image](https://github.com/Amanj-18/Learning-Management-System-LMS/assets/89749348/73e58af5-93f8-442d-b446-2f276066a07b)
![image](https://github.com/Amanj-18/Learning-Management-System-LMS/assets/89749348/d6e833c2-346b-41ae-8d04-da6597dd6dc0)
![image](https://github.com/Amanj-18/Learning-Management-System-LMS/assets/89749348/0ee6b35e-af6c-4459-b1bd-a51e033d84f8)
![image](https://github.com/Amanj-18/Learning-Management-System-LMS/assets/89749348/6751e749-21c9-4fde-aba1-db8a211d282f)
![image](https://github.com/Amanj-18/Learning-Management-System-LMS/assets/89749348/b2ebd091-e476-4be6-9392-f8422987c007)
![image](https://github.com/Amanj-18/Learning-Management-System-LMS/assets/89749348/f5c574e2-98d3-4afa-a7d9-666398031f7c)
![image](https://github.com/Amanj-18/Learning-Management-System-LMS/assets/89749348/d06ff8ce-5542-4f4b-9e17-a8a5e2c57ee3)
![image](https://github.com/Amanj-18/Learning-Management-System-LMS/assets/89749348/1799d7fe-95e5-4dd7-be74-84a075dbe955)



Current features
----------------

* News And Events
* The admin can Add Students
* The admin can Add Lecturers
* Students can Add and Drop courses
* Lecturers submit students score (Attendance, Mid exam, Final exam, assignment)
* The system calculat students Total, Avarage, point, and grade automaticaly
* Also, the system tells the student whether he/she pass, fail or pass with a warning
* Assessment result
* Grade result
* Upload video and documentations for each course
* PDF generator for students registration slip and grade result
* Storing of quiz results under each user
* Question order randomisation
* Previous quiz scores can be viewed on category page
* Correct answers can be shown after each question or all at once at the end
* Logged in users can return to an incomplete quiz to finish it and non-logged in users can complete a quiz if their session persists
* The quiz can be limited to one attempt per user
* Questions can be given a category
* Success rate for each category can be monitored on a progress page
* Explanation for each question result can be given
* Pass marks can be set
* Multiple choice question type
* True/False question type
* Essay question type
* Custom message displayed for those that pass or fail a quiz
* Custom permission (view_sittings) added, allowing users with that permission to view quiz results from users
* A marking page which lists completed quizzes, can be filtered by quiz or user, and is used to mark essay questions

# Pre-requisites:

> The following programs are required to run the project

- [Any Python-3 version](https://www.python.org/downloads/)
- [PostgreSQL database](https://www.postgresql.org/download/)

# Installation

- Clone the repo with `git clone https://github.com/adilmohak/django-lms.git`
- Create and activate a python virtual environment
- `pip install -r requirements.txt`
- Create `.env` file inside the root directory and include the following variables

```config
DB_NAME=[YOUR_DB_NAME]
DB_USER=[DB_ADMIN_NAME]
DB_PASSWORD=[DB_PASSWORD]
DB_HOST=localhost
DB_PORT=
USER_EMAIL=[YOUR_EMAIL]
USER_PASSWORD=[EMAIL_PASSWORD]
STRIPE_SECRET_KEY=LEAVE_THIS_BLANK_FOR_NOW
STRIPE_PUBLISHABLE_KEY=LEAVE_THIS_BLANK_FOR_NOW
```

- `python manage.py makemigrations`
- `python manage.py migrate`
- `python manage.py runserver`

Last but not least, go to this address http://127.0.0.1:8000

### References

- Quiz part: https://github.com/tomwalker/django_quiz

# Connect with me

<div>
<a href="https://www.linkedin.com/in/anandjaiswar02" target="_blank">
<img src=https://img.shields.io/badge/linkedin-%231E77B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white alt=linkedin style="margin-bottom: 5px;" />
</a>
<a href="https://github.com/anand-3399" target="_blank">
<img src=https://img.shields.io/badge/github-%2324292e.svg?&style=for-the-badge&logo=github&logoColor=white alt=github style="margin-bottom: 5px;" />
</a>
<a href="https://www.facebook.com/anand360" target="_blank">
<img src=https://img.shields.io/badge/facebook-%232E87FB.svg?&style=for-the-badge&logo=facebook&logoColor=white alt=facebook style="margin-bottom: 5px;" />
</a>
</div>

### Show your support by ⭐️ this project!
