# newRepository
…или создайте новый репозиторий в командной строке

echo "# newRepository" >> README.md

git init

git add README.md

git commit -m "first commit"

git branch -M main

git remote add origin https://github.com/VjacheslavRogov/newRepository.git

git push -u origin main


…или отправить существующий репозиторий из командной строки

git remote add origin https://github.com/VjacheslavRogov/newRepository.git

git branch -M main

git push -u origin main