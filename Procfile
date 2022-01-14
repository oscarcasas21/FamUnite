web: gunicorn CCMS.wsgi --recognizer -
web: target/universal/stage/bin/my-app -Dhttp.port=${PORT}
heroku addons:create bucketeer:hobbyist
