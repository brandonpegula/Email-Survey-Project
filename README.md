Email Survey Service

Getting Started.

run yarn install within the server folder.
cd into the client folder, run yarn install.
create a dev.js file within config. This is where the API key's will be stored.
API key structure: PASTE BELOW CONTENTS INTO dev.js file.
module.exports = { googleClientID: googleClientSecret: mongoURI: cookieKey: };

Add your keys and run 'yarn dev' within the server folder.
This command will run the server and launch the development enviornment in your browser.