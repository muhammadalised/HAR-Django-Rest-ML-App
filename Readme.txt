1. Install the requirements from requirements.txt file in your conda or python virtual environment. (I used conda env)
2. You can save the model using notebook (code provided at the end of .ipynb file)
3. To use the model in Django API, just copy the saved model file and put it in DjangoRestML/models
4. Start the django server by entering the following command:
	python manage.py runserver
5. move to this url
	http://127.0.0.1:8000/App/predict/
6. Click on options button
7. Copy the the entry from api_test_xx file(your input should be in this format) and paste it into content box
8. Click on post and you will see the predicted label on page.
