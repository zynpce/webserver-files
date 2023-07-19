node -v
npm -v

cd webserver-files
sudo chmod 777 server.js

<!-- update databese credentials from server.js file -->

sudo npm install
sudo npm start

/api/log
/api/logs

CREATE TABLE logs (
  id INT AUTO_INCREMENT PRIMARY KEY,
  name VARCHAR(255),
  timestamp DATETIME
);
