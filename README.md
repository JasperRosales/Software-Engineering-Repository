# Software-Engineering-Repository

This project is done by the following members:
- Jasper Rosales
- John Aaron Caay
- Mar Franklin Caraig
- Nino Joseph Agquiz

## Setup 

First run the package manager installer
```
npm install
```

This will install all the packages needed by the project

To run the project use the command below
```
npm run dev //then proceed to use live server on index.html
```

This is the one used to run the tailwind cli by the command above
```
npx @tailwindcss/cli -i ./src/css/input.css -o ./src/css/output.css --watch
```

## For Group Mates
If you are checking for updates always sync or git pull or fetch, so that changes can be seen and managed to avoid conflicts ( Use either GUI of github or using git in terminal
```
git fetch origin //this fetches every branch in the origin repo
```
Do this once you have done fetch and want to update the branch, you dont need to do git fetch again if you have done it before. 
``` 
git checkout -b tailwind origin/tailwind //checks the branch and creates if not done yet by 
git pull origin tailwind //pulls the exact tailwind repo
```

To check or switch to what branch you are at use this
``` 
git branch //to check branches (the one highlighted is where you at
git switch <branch> //in our case (git switch tailwind) 
```

# Reminders
- Use git pull to check for changes
- Use Convinient Naming Convensions like ch1-title-text, ch2-img-container, etc..
- DO NOT TOUCH THE OUTPUT.CSS!!!!
