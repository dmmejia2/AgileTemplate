# Agile Project Template

# Install Node.js
1. https://nodejs.org/en/ (Use Version Recommended for Most Users)

# Clone GitHub Repository
1. Install Git onto your machine
2. Create a local folder on your machine (local repository)
3. Navigate to local folder on your machine
4. Clone repository
5. git clone git@github.com:dmmejia2/AgileTemplate.git

# Open VS Code (or Similar)
1. Open the project
2. Open the terminal in VS Code
3. Run the following Command: npm init -y //(New Files will be created)
4. Run the follwoing Command: npm i webpack webpack-cli -D //package.json & package-lock.json will be created

# Update package.json file
1. Add the following line under ""Scripts": { "test": .......,"
2. "build": "webpack"
3. It should look like this:
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "build": "webpack"
  },

# Build Webpack
1. Run the following command: npm run build
2. This will create "bundle.js" in your 'dist' folder (Do not modify this file)

# Install Live Server Plugin
1. Install a plugin called "Live Server"
2. Install it by going to the extensions button and searching for "Live Server"

# Update index.js
1. Add a console.log statement: console.log("ENTER NAME HERE configured everything!")
2. Save the file
3. Go to index.html
4. Right click anywhere on the file and select "Open With Live Server"

# View Developer Tools
1. Use the browser of your choice
2. Open up developer tools (Google How to do this on your favorite web browser if you don't know how)
3. Refresh
4. Verify that you read your messages logged in the console
