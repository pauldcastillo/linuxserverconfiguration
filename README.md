# Linux Server Configuration

### PURPOSE:
Details of linux server configuration for Udacity full stack engineering course.

### How to Access:
* Basic IP address: 54.212.222.247
*Note:* The Gamerater (i.e. Item Catalog) is accessible at the above URL, but login will not function.
* Valid URL: http://54.212.222.247.xip.io
*Note:* The above URL can be accessed. Logging into the app will function on the above URL.
* SSH port:2200

### Installed Software
* Apache2
* Flask
* GIT
* PIP
* SQLAlchemy

### Configuration Changes
- Disallowed all ports but 80, 123, and 2200
- Added 'grader' user with sudo access and ssh login.
- Disabled remote root login.
- Setup mod_wsgi configuration according to Flask documentation.

### Outside Resources
[Flask mod_wsgi setup](http://flask.pocoo.org/docs/0.12/deploying/mod_wsgi/)
[Udacity Knowledge Forums](https://knowledge.udacity.com/)
