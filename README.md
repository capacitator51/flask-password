# flask-password

Flask Password is a password generator based on the [XKCD 936](https://xkcd.com/936/) comic.

Flask Password runs as a web application atop the [Flask](https://palletsprojects.com/p/flask/) Python framework. For a
complete list of requirements, see `requirements.txt`. The code is available [on GitHub](https://github.com/synackray/flask-password).

## Demo
A demo of Flask Password can be found [here](https://www.icarustech.com/flask-password/).

## Screenshots

![Screenshot of English default settings](docs/media/default_en.png "English Defaults")

![Screenshot of Italian default settings](docs/media/default_it.png "Italian Defaults")

![Screenshot of English with spaces](docs/media/spaces_en.png "English Spaces")

# Installation

1. Browse to the flask-password project folder.
2. Create Python Virtual Environment [(venv)](https://docs.python.org/3/library/venv.html) and activate it.
3. Install the package requirements by running `pip install -r requirements.txt`.
4. Install Gunicorn. An example script of a systemd service script is provided in [docs/flask-password.service](docs/flask-password.service)
5. Install a web server. An Example script of NGINX proxied to Gunicorn is provided in [docs/nginx.conf](docs/nginx.conf)