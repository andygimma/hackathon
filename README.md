# hackathon

Blueprint API can be found at

http://docs.kiron.apiary.io/


Backend: (Golang + Postgres)
https://github.com/Inflatablewoman/kiron (included as submodule)

Prerequirements:
golang 1.4

clone git@github.com:Inflatablewoman/kiron.git

A few steps:
source project   -- sets PWD to active GO path

scripts/build.sh -- builds the project
scripts/run.sh   -- runs the server

(when the server is running)
scripts/test.sh  -- runs unit tests


Frontend: (React-Redux)

clone git@github.com:Inflatablewoman/kiron-application-management-frontend.git
npm install && webpack
