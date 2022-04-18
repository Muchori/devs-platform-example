## Developer interaction platform

Demo to the web [here](https://devs-interaction-platform.herokuapp.com/)

Is a web page like github where developers can have their projects and interact with each other :

- [x] Users can be able to create an account by registering and access the account by lo
      gging.
- [x] Updating account.
- [x] Uploading projects and technologies used, editing and delete if need arises.
- [x] Uploading skills.
- [x] Users can send messages to other users.
- [x] Users can give reviews on other developers projects
- [x] Users can also upvote or downvote a project

## Project uses MVT-Model View Template architecture

## Setup

The first thing to do is to clone the repository:

```sh
$ git clone https://github.com/Muchori/devs-platform-example.git
$ cd devs-platform-example
```

Create a virtual environment to install dependencies in and activate it:

```sh
$ python3 -m venv env
$ source env/bin/activate
```

Then install the dependencies:

```sh
(env)$ pip install -r requirements.txt
```

Note the `(env)` in front of the prompt. This indicates that this terminal
session operates in a virtual environment set up by `venv`.

Once `pip` has finished downloading the dependencies:

```sh
(env)$ cd project
(env)$ python manage.py runserver
```

And navigate to `http://127.0.0.1:8000/`.
