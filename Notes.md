### Nodejs E2E Backend - Production Setup
1. Overview
2. Node Project
3. Git and Github
4. Husky
5. Typescript
6. Folder Structure
7. Commit Lint
8. ES Lint
9. Prettier
10. Project Enviroment 
11. ExpressJS
12. Global error handler
13. 404 handler
14. Logger
15. Source Map
16. Colorful terminal
17. MongoDB
18. Database Log Storage
19. Database Migration
20. Health Endpoint
21. Security - HelmetJS
22. Security - CORS
23. Security - Rate Limiting
24. Dependency Updates
25. Docker setup.

## Overview
Here we discuss the different aspects of the production server setup in nodejs.

## Node Project
- Install NodeJS on your system. Also download the LTS version.
- Check if nodejs is intalled. Open the terminal and run `node -v`
- Run `npm init` and answer some questions about the server.
- This configuration will be stored in the `package.json` file.

## Git and Github Setup
- Make sure that git is installed.
- Create a git repository using `git init`
- Commit the files using commands `git add .` and `git commit -m "feat: Node Project Setup"`
- Create a new repository on github website
- Add remote origin to the repository.

## Husky Setup
- It is a github tool and it has some utilities regarding git commits.
- Like formatting code, detecting errors before commits and many more.
- Use `npm i husky lint-staged -D` to install dependencies.
- Run `npx husky init` to start husky and it will create a `.husky` folder.
- Inside that folder, we have a `pre-commit` file with all the commands which will run before commits.
- For now we will add a test command to simulate dummy tests.
