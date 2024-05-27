# How to run this project on your system

First clone the project and extract the files on your system.

Then open powershell on the same folder and run the command  ( pip install -r req.txt  )

Be sure that the  libraries are properly installed :

asgiref,

click,

cmake,

Django,

dlib,

face-recognition,

face-recognition-models,

numpy,

opencv-python,

Pillow,

playsound,

pytz,

sqlparse .

After that open project on vs code and in new terminal run the command  ( python manage.py runserver  ). Make sure that you are in the same directory othervise no such file or directory present error will show. For this you can run the command- cd face_recognition_attendance_system-dev 

The id and password for admin login is (id=toutou) and (password=toutou), however you can change it by running the command (python manage.py createsuperuser)
