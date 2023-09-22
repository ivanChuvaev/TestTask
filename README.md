# Test Task application

application is splitted to backend and frontend parts

both backend and frontend are stored in separated repositories and added to main application as submodules

to initialize application you should run these commands while current working directory (CWD) is TestTask
```
git submodule init
git submodule update
cd ./TestTask-backend && npm i && cd ..
cd ./TestTask-frontend && npm i && cd ..
```
to run application you should run both backend and frontend, they will block terminal so you need to run them in separate terminals or run them concurrently

command that will run backend, while CWD is TestTask
```
cd ./TestTask-backend && npm start
```
command that will run frontend, while CWD is TestTask
```
cd ./TestTask-frontend && npm run dev
```