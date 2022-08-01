# Quizzy

## Functions


### Teacher
- Teacher has to first SignUp and then Login (Approval required by system admin, Then only teacher can login)
- After Login, can see Total Number Of Student, Course, Questions are there in system on Dashboard.
- Can Add, View, Delete Course/Exams.
- Can Add Questions To Respective Courses With Options, Correct Answer, And Marks.
- Can View And Delete Questions Too.


### Student
- Student has to first SignUp and then Login.
- After Login, Can See How Many Courses/Quiz And Questions Are There In System On Dashboard.
- Can Give Exam Any Time.
- Can View Marks Of Each Quiz.
- Question Pattern Is MCQ With 4 Options And 1 Correct Answer.
---

## HOW TO RUN THIS PROJECT
- Install Python3 (Dont Forget to Tick Add to Path while installing Python)
- Open Terminal and Execute Following Commands :
```
python -m pip install -r requirements. txt
```
- Download This Project Zip Folder and Extract it
- Move to project folder in Terminal. Then run following Commands :
```
py manage.py createsuperuser (Create admin for giving permission to the groups.)
py manage.py makemigrations
py manage.py migrate
py manage.py runserver
```
- Now enter following URL in Your Browser Installed On Your Pc
```
http://127.0.0.1:8000/

```
## Demo Video
https://user-images.githubusercontent.com/74965209/182106879-f3b99529-0465-4fab-993a-48f158ea84ee.mp4



