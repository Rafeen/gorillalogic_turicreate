# gorillalogic_turicreate

 1. **Dependencies**  
      - Linux/MacOS
      - Python 3.6  
      - turicreate
	- flask
	- flask-uploads  
  	- Flask-SQLAlchemy
  	- flask-marshmallow  
  	- marshmallow-sqlalchemy
       
  2. **Steps to run**
	  - Clone the repository
       - Create a virtual environment in to project folder ([here](http://docs.python-guide.org/en/latest/starting/install3/osx/#pipenv-virtual-environments))
       - Activate virtual environment  
      - run `pip install -r requirements.txt`
      - run the project with `FLASK_APP=app.py FLASK_DEBUG=1 flask run` command.
   3. **Steps to Test**
	   - If everything is working fine, open your browser and enter [http://127.0.0.1:5000](http://127.0.0.1:5000/). You should get a response like this:
	   ![](https://gorillalogic.com/wp-content/uploads/2018/10/2flask_not_found.png)

		- Open [Postman](https://www.postman.com/) 
		- Send a post request to this url
			 [http://127.0.0.1:5000/gorillas/face-recognition/api/v1.0/user/register](http://127.0.0.1:5000/gorillas/face-recognition/api/v1.0/user/register)
		- add the following details to postman request body 

> Upload 2 or more photos, mugshots are recomended

![](https://gorillalogic.com/wp-content/uploads/2018/10/4negative_result_register.png)

## For more details go to  [How to Build a Face Recognition App in iOS Using CoreML and Turi Create Part 2](https://gorillalogic.com/blog/how-to-build-a-face-recognition-app-in-ios-using-coreml-and-turi-create-part-2/?fbclid=IwAR0-kp79dcB9zQZLMscIYTX22uzKJrhbAWTcnk0X3AdvkR1NlUqoOZ-WNuw)


