# CKEditor 5 custom build sample in Flask
To add CKEditor 5 to your Flask app you just need to load editor build file as a standard static JavaScript file. It's as simple as that.
      
## Installation
Provided that you are familliar with installing Python, creating virtual environments and installing packages with `pip` now you need to:  
- install packages listed in `requirements.txt`:  
`pip install -r requirements.txt`
  
- run `export FLASK_APP=app.py`
  
- run `flask run`
  
- go to `localhost:5000` and enjoy
  
## Using CKEditor 5
This sample uses custom editor build created with [Online Builder](https://ckeditor.com/ckeditor-5/online-builder/). 
The template with the loading sacript is located in `templates/editor.html`. You can also change the toolbar configuration there. If you want to use another type or customize the editor, you'll need to create and build it first. You can find those information in CKEditor docs on [installing plugins](https://ckeditor.com/docs/ckeditor5/latest/builds/guides/integration/installing-plugins.html) and [creating custom builds](https://ckeditor.com/docs/ckeditor5/latest/builds/guides/development/custom-builds.html). When youre done with customizing the editor, just use it in your Flask app as a static JS asset.  