>> Description:
>> Started: 
>> Org:

>> Tags:

>> Setup: 
	$ python -m venv .pyenv
	$ .pyenv\Scripts\activate.bat

 	$ pip install django

	$ django-admin startproject crud_project .
	$ python manage.py startapp crud_app

	// Define the Models:
	EDIT_FILE("crud_app/models.py")	
		# --> See article for contents

	// Create the database tables for the models:
	$ python manage.py makemigrations
	$ python manage.py migrate

	// Implement the Views:
	EDIT_FILE("crud_app/views.py")	
		# --> See article for contents

	// Create the forms:
	CREATE_FILE("crud_app/forms.py")
	EDIT_FILE("crud_app/forms.py")	
		# --> See article for contents

	// Create URLs and Templates:
	CREATE_FILE("crud_app/urls.py")
	EDIT_FILE("crud_app/urls.py")
		# --> See article for contents

	CFREATE_DIR("crud_app/templates")
	EDIT_FILE("crud_app/templates/user_list.html")
	EDIT_FILE("crud_app/templates/user_detail.html")
	EDIT_FILE("crud_app/templates/user_form.html")
	EDIT_FILE("crud_app/templates/user_confirm_delete.html")
	EDIT_FILE("crud_app/templates/product_list.html")
	EDIT_FILE("crud_app/templates/product_detail.html")
	EDIT_FILE("crud_app/templates/product_form.html")
	EDIT_FILE("crud_app/templates/product_confirm_delete.html")
		# --> See article for contents

	// Configure URLs for the Project:
	EDIT_FILE("crud_project/urls.py")
		# --> See article for contents/updates to be done to tghe existing file

>> Run:
	// Run the Development Server:
	$ python manage.py runserver

>> Install:
>> Tests:

>> Take aways
>> Remarks
>> Errors 
>> Finished 
>> Lessons Learned

>> Working Details 
