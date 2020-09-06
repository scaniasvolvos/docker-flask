# docker-flask
Guide for dockerizing sample Flask application

**Step 1:** docker build -t docker-flask:latest .

**Step 2:** docker run --name flaskapp -v$PWD/app:/app -p5000:5000 docker-flask:latest


