# ***** eslint-prettier-airbnb-react-setup ***** #

# Install eslint and prettier globally:
npm i -g eslint & npm i -g prettier

# Change the settings in Visual Studio Code:
Install ESLint, prettier extension in VS Code ⇒ settings ⇒ search with “format on save” ⇒ give tick on format on save 

Search with prettier ⇒ give tick on “Prettier: single quote” , “Prettier: semi” 

# Create a package.json file:
Open a terminal with project directory ⇒ Create a package.json file with npm init -y or npm init and follow the mentioned steps 

# Install airbnb with eslint & create a .eslintrc.json file :
Open a terminal with project directory ⇒ type the code to create a .eslintrc.json file 
eslint --init
Or 
npx eslint --init

During this process, follow the enforce style guide and popular style guide.

# Install other packages:
Open package.json file and paste the codes inside the scripts …
 
"lint": "npm i -D prettier && npm i -D eslint-plugin-prettier && npm i -D eslint-config-prettier"

Then run the code from terminal ...
npm run lint

# Check the react version in package.json and .eslintrc file:
set the react version same both in package.json and .eslintrc.json file

# Now create config files for prettier :
# .prettierrc file :
Create a file named .prettierrc ⇒ Open the .prettierrc → include the rules as many as you want same as 

{
    "singleQuote": true,
    "trailingComma": "es5",
    "semi": true,
    "tabWidth": 2,
    "jsxSingleQuote": false,
    "quoteProps": "as-needed",
    "arrowParens": "avoid"
}

# .prettierignore file:
Create a .prettierignore file and set the file inside this folder same as .gitignore …

// Ignore artifacts:
build
coverage 

# .eslintignore file:
Create a .eslintignore file and copy the code from .gitignore file and paste inside it.

# **** NOTEBOOK **** #
# In Visual Studio Code :
To sort or organize import modules or dependency, use keyboard shortcut alt + shift + o

Follow the <a href="https://github.com/Mozahedul/setup-eslint-airbnb-prettier_in_react/blob/main/package.json">package.json</a> 
and <a href="https://github.com/Mozahedul/setup-eslint-airbnb-prettier_in_react/blob/main/.eslintrc.json">.eslintrc.json</a>


 
