# TinyPost

`TinyPost` is a simple microblogging service written in `Flask`. TinyPost has multiuser support, users can create account on the site using a their email-id and create posts of their own. The API is backed by a simple HTML-CSS front end using `Jinja` templating engine.

## Usage

Make sure python and pip is already installed on the machine and then proceed with the installation of dependencies as given below. 

1. Install the dependencies
```
$ pip install -r requirements.txt
```

2. Create the database(if using sqlite)
```
$ python
>>> from flaskblog import db
>>> db.create_all()
```

3. Run the server!
```
$ python run.py
```

### Few screenshots:

Homepage
![Homepage](https://github.com/jahnavikolli/TinyPost/blob/master/examples/1.png?raw=true)
_____________________________________________________________________________________

User Account
![Homepage](https://github.com/jahnavikolli/TinyPost/blob/master/examples/5.png?raw=true)
_____________________________________________________________________________________

Registration
![Homepage](https://github.com/jahnavikolli/TinyPost/blob/master/examples/3.png?raw=true)
_____________________________________________________________________________________

New Post
![Homepage](https://github.com/jahnavikolli/TinyPost/blob/master/examples/2.png?raw=true)
_____________________________________________________________________________________

Login
![Homepage](https://github.com/jahnavikolli/TinyPost/blob/master/examples/4.png?raw=true)
