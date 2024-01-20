Repository: alx-backend-user-data

* authors detail
name: Amsal Fitsum
email: amsalfessha21@gmail.com
date: 01/02/2024
phone number: +251961046155

# Create project directory and readme.
mkdir ./alx-backend-user-data/
touch ./alx-backend-user-data/README.md

cd alx-backend-user-data

# Create repository.
git init
git add .
git commit -m 'first commit by amsi'
git remote add origin <REMOTE_URL>
git push

# Create gitignore file.
touch .gitignore

echo '*/__pycache__/
' > .gitignore
