# JAIDEV_SINGH-STUDENT_MANAGEMENT_FLASK_PYTHON
Student CRUD using python
Url : 127.0.0.1:5000
Method: POST,GET.
The whole Student Exam Management CRUD is based on Python,HTML,FLASK.
It contains CRUD with semester marks from (1-8).
With Add new student button you could add new student data.
With update button you could update data.
The graph button is also there with hard added values.
![index page](https://user-images.githubusercontent.com/120723984/211251538-76b2c29c-7970-4c24-ae65-b4154cc26578.png)
![Add page](https://user-images.githubusercontent.com/120723984/211251578-54ebff0c-5426-4a75-87b2-3ddd9ff7bbc0.png)
![sort page](https://user-images.githubusercontent.com/120723984/211251590-a57ab4ef-87d6-4b00-a95c-751b227113b1.png)
![graph page](https://user-images.githubusercontent.com/120723984/211251594-25996e32-05c9-43f4-8e3f-78248a846925.png)
<hr>
<h2> Usage </h2>

 

```
  from flask import Flask,render_template,request,redirect,url_for,flash
  from flask_sqlalchemy import SQLAlchemy
  @app.route('/',methods=['GET','POST'])
  #returns home page having student list
  @app.route('/insert',methods = ['POST'])
  #for adding the students data in registration form
  @app.route('/update',methods = ['GET','POST'])
  #for updating the data
  @app.route('/delete/<id>/', methods =['GET','POST'])
  #for deleting the data
  @app.route("/sort")
  #returns sorted list
  @app.route("/bar")
  #return the graph
  
```
<h2> Deployment </h2>

 

If you want to deploy this application in our local system we need to follow this below steps<br>
1. We need to download python and any IDE and the modules in it as per required.<br>
2. Then need to pull the code and execute it in the system.
