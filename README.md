```
mkdir portfolio
cd portfolio
echo "<h1> My Portfolio </h1>" > home.html
echo '<?php include_once("home.html"); ?>' > index.php
echo '{}' > composer.json
git init
heroku login
heroku create cr-naye-kitten
heroku git:remote -a cr-naye-kitten
git add .
git commit -am "init"
git push
git push heroku
```
