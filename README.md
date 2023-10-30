# Learning management system using django web framework

![1694373426380](static/README/1694373426380.png "Home Page")
![image](https://github.com/Amanj-18/Learning-Management-System-LMS/assets/89749348/c9d37b37-0c0f-4abb-abe9-cb975b183c7f)
![image](https://github.com/Amanj-18/Learning-Management-System-LMS/assets/89749348/1ef0f430-2b9c-4106-89cc-9c2ff204632e)
![image](https://github.com/Amanj-18/Learning-Management-System-LMS/assets/89749348/3673e252-8176-4a92-aec3-f3095445440f)
![image](https://github.com/Amanj-18/Learning-Management-System-LMS/assets/89749348/4e100db9-0527-4060-bbe8-1a17c9c97b79)
![image](https://github.com/Amanj-18/Learning-Management-System-LMS/assets/89749348/74c8f940-67e8-4451-a233-f98445498791)
![image](https://github.com/Amanj-18/Learning-Management-System-LMS/assets/89749348/12166d89-da2a-4b1c-9f95-e6aa337881c0)
![image](https://github.com/Amanj-18/Learning-Management-System-LMS/assets/89749348/b76877ed-29fc-44c0-8201-5517aacab222)
![image](https://github.com/Amanj-18/Learning-Management-System-LMS/assets/89749348/e4f8170d-8be8-4963-b155-df85f008784c)
![image](https://github.com/Amanj-18/Learning-Management-System-LMS/assets/89749348/04222a2d-7103-412b-8698-b0eaab4e7337)
![image](https://github.com/Amanj-18/Learning-Management-System-LMS/assets/89749348/81b56b4f-72e9-4e51-b109-bf0854689892)



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
