# OrangeWork
Orange Work - improvement on a previous school project found [here](https://github.com/razzacktiger/CMPE-131-2_Term_Project-). Remastered in Flask, potentially django and react in the future. 

# Getting Started

* `git clone [URL]` - Clone the code from Git hub https://github.com/razzacktiger/CMPE-131-2_Term_Project-
## Libraries from linux terminal:
* `pip install flask` - Install flask 
* `pip install flask-wtf` - Install WTforms for flask
* `pip install wtforms` - Install WTforms
* `pip install email-validator` - Install email validation for Wtforms
* `pip install flask-markdown` - Install flask markdown
*  or `pip install markdown`  - Or install Markdown
* `pip install flask-login` - Install flask
* `pip install flask-sqlalchemy ` - Install SQLalchemy for Flask
* `pip install -u werkzeug` - Install Werkzeug for security
* `pip install datetime` - Install Datetime


# Initialize Database File
1. Before starting, navigate to the projectstart file.
1. `python3` Run python3 IDE 
1. `from myapp import db` import db object
1. `from myapp.models import User, Notes, Note, FlashCard, ToDo` import tables from models including the association tabel 'Notes'
1. `quit()` exit out of IDE 
1. navigate to the projectstart file
1. `python3 run.py` Using this you should be able to run the application
