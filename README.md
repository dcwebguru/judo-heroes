# judo-heroes
React - Judo Athletes - List &amp; Item Views

# 1) Bootstrap our Node.js project allowing us to add all the needed dependencies
git init

# 2) Add remote origin
git remote add origin https://github.com/dcwebguru/react-judo-heroes.git

# 3) Pull application files
git pull origin master

# 4) Start App
node_modules/.bin/http-server src/static

# 5) View App 
http://localhost:8080/



# OTHER COMMANDS
	
# Install babel, ejs, express, react and react-router
npm install --save babel-cli@6.11.x babel-core@6.13.x  \  

  babel-preset-es2015@6.13.x babel-preset-react@6.11.x ejs@2.5.x \  
  
  express@4.14.x react@15.3.x react-dom@15.3.x react-router@2.6.x

# Install Webpack [with its Babel loader extension] and http-server as a development dependencies
npm install --save-dev webpack@1.13.x babel-loader@6.2.x http-server@0.9.x

# Create .js bundles
NODE_ENV=production node_modules/.bin/webpack -p
