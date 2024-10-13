<h1 align="center" id="title">Blog</h1>

<h2 id="description">Description</h2>

<p>

</p>

## 🔧 Github Commands :-

`Step 1` : SSH Configuration.

```
ssh-keygen -t ed25519 -C "ex@gmail.com"
```

```
cat ~/.ssh/id_ed25519.pub
```

```
git config --global user.email "ex@gmail.com"
```

```
git config --global user.name "ex"
```

`Step 2` : Starting Git.

```
git init
```

```
git add .
```

```
git commit -m "first commit"
```

```
git branch -M main
```

```
git remote add origin git@github.com:Ma7en/crowd-funding.git
```

```
git push -u origin main
```

`Step 3` : Clone.

```
git clone git@github.com:Ma7en/iti-final-project-backend.git
```

`Step 4` : Pull.

```
git pull -r origin main
```

```
Accept Both Changes
```

```
git rebase --continue
```

```
git config --global pull.rebase true
```

`Step 5` : Tag.

```
git checkout main
```

```
git tag
```

```
git tag -a v1.0 -m "Version 1.0"
```

```
git push origin v1.0
```

---

## 🛠️ Installation Steps :-

<h3 align="center"> Ubuntu </h3>

`Step 1` : Install and activate VirtualEnvironment.

```
pip install virtualenv
```

```
virtualenv venv
```

```
source venv/bin/activate
```

`Step 2` : Install Packages.

```
pip install flask
```

```
pip install flask-shell-ipython
```

```
pip install -U Flask-SQLAlchemy
```

```
pip install Flask-Migrate
```

```
pip install psycopg2-binary
```

```
pip install Flask-WTF
```

```
pip install bootstrap-flask
```

```
pip install flask-restful
```

```
pip install Flask-Login
```

`Step 3` : Install requiremental Packages.

```
pip freeze > requirements.txt
```

```
pip install -r requirements.txt
```

`Step 4` : Create Project.

```

```

```

```

`Step 5` : Create Apps.

```

```

`Step 6` : Create Database.

```
su - postgres
```

```
psql
```

```
CREATE USER flask_project WITH PASSWORD 'flask@@1';
```

```
alter user fayoum superuser;
```

```
alter user fayoum createdb;
```

```
\q
```

```
psql -U flask_project -h localhost -p5432 -W -d postgres
```

```
flask@@1
```

```
create database flask_full_blog;
```

`Step 7` : Create Migrate.

```
cd app
```

```
flask db init
```

```
flask db migrate -m 'create blog db'
```

```
flask db upgrade
```

`Step 8` : Run Server.

```
export FLASK_APP=blog
```

```
flask run --debug
```

<h3 align="center"> Windows </h3>

`Step 1` : Install and activate VirtualEnvironment.

```
pip install virtualenv
```

```
virtualenv wvenv
```

```
wvenv\Scripts\activate
```

`Step 2` : Install Packages.

```
pip install flask
```

```
pip install flask-shell-ipython
```

```
pip install -U Flask-SQLAlchemy
```

```
pip install Flask-Migrate
```

```
pip install psycopg2-binary
```

```
pip install Flask-WTF
```

```
pip install bootstrap-flask
```

```
pip install flask-restful
```

```
pip install Flask-Login
```

`Step 3` : Install requiremental Packages.

```
pip freeze > wrequirements.txt
```

```
pip install -r wrequirements.txt
```

`Step 4` : Create Project.

```

```

```

```

`Step 5` : Create Apps.

```

```

`Step 6` : Create Database.

```
su - postgres
```

```
psql
```

```
CREATE USER flask_project WITH PASSWORD 'flask@@1';
```

```
alter user fayoum superuser;
```

```
alter user fayoum createdb;
```

```
\q
```

```
psql -U flask_project -h localhost -p5432 -W -d postgres
```

```
flask@@1
```

```
create database flask_full_blog;
```

`Step 7` : Create Migrate.

```
cd app
```

```
flask db init
```

```
flask db migrate -m 'create blog db'
```

```
flask db upgrade
```

`Step 8` : Run Server.

```
set FLASK_APP=blog
```

```
flask run --debug
```

---

## 🧐 Features :

<ul>
<li>
    <b>User Authentication:</b> Secure registration, login, and password recovery.
</li>
<li>
    <b>Project Creation:</b>
</li>
<li>
    <b>Project Management:</b> Features for viewing, commenting, rating, and reporting projects.
</li>
<li>
    <b>Homepage:</b> Displays featured, latest, and categorized projects.
</li>
<li>
    <b>Search:</b> Allows users to find projects by title or tag.
</li>
<li>
    <b>Additional Features:</b> user profiles, and notifications.
</li>
</ul>

---

## 💻 Built with :-

Technologies used in the project:

-   flask Framework
-   Postgres Database

---

<p align="left"><img src="https://profile-counter.glitch.me/flask-full-blog-4/count.svg" alt="desphixs" /></p>

---

## Contributors

<table>
    <tr>
        <td>
            <img src="https://avatars.githubusercontent.com/u/91129862?v=4"></img>
        </td>
    </tr>
    <tr>
        <td>
            <a href="https://github.com/Ma7en">Mazen Saad</a>
        </td>
    </tr>
</table>
