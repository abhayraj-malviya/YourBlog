# YourBlog
It is a web application for building using Flask.

### Check live demo of the code by Clicking [here](https://theblogbyyou.herokuapp.com/)

![Image demo|700](https://github.com/abhayrajmalviya/YourBlog/blob/main/profilepage.png)



### for using the sqlite db on local system

- edit Config.py and replace SQLALCHEMY_DATABASE_URI with the code below
> SQLALCHEMY_DATABASE_URI = os.environ.get('DATABASE_URL', '').replace('postgres://', 'postgresql://') or 'sqlite:///' + os.path.join(basedir, 'app.db')
