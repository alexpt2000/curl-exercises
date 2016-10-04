
git init

git add .

git commit -m "first commit"

git remote add origin https://github.com/alexpt2000/curl-exercises.git

git push -u origin master


Task 2
curl -o http-easy.html http://www.jmarshall.com/easy/

Task 3
curl -v -o duckduckgo.txt http://www.duckduckgo.com

Task 4
curl -v -o science.txt https://duckduckgo.com/?q=GMIT&t=h_&ia=about

Task 5
curl -L -H "Accept: application/json" "http://duckduckgo.com/?q=gmit&format=json" > gmit.json


Task 6 
curl -o bootstrap.min.js https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js

curl -o bootstrap.min.css https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css

python -m http.server

http://localhost:8000/
