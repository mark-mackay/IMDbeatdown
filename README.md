# IMDbeatdown

In order to install the application you must carry out the following steps..

### Copy the files to the relevant directory
-- Download the zip file and extract them where you want to place the application

### From the application folder install the dependencies..
npm install 

### Seed the database

from the same folder run the following to seed the database...

mongo < server/db/seeds.js 

### To run the express server(Do this from another terminal window in the same folder)...
npm run server:dev


### To run the mongodb server(Do this from another terminal window in the same folder)...

mongod

### Lastly To run the application itself (Do this from another terminal window in the same folder)...

npm run build

### Next open the website and enjoy....

http://localhost:3000/
