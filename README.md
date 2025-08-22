## Starting programming with NodeJS

This is a project for starting programming with NodeJs.

## Pre-requisites
* Javascript


## Setup environment

### Installing NodeJs
* Download NodeJs installer from [nodejs.org](https://nodejs.org/en/download)
  * Run setup
  * Verify installation with command `node -v`

### Installing tools for coding
**Visual Studio Code**
* Download Visual Studio Code from [code.visualstudio.com](https://code.visualstudio.com/download)

**VS Code Extensions**
* Eslint

### Installing nodemon
* Install nodemon from [npmjs.com](https://www.npmjs.com/package/nodemon)
  * Open a terminal in Visual Studio Code
  * Run command "npm install -g nodemon"

 <img width="614" height="207" alt="image" src="https://github.com/user-attachments/assets/cad04b14-fdf3-4d35-bed2-a80bde752cad" />



## Terminal REPL ##

```
REPL = Read Eval Print Loop
```

To start running our code with NodeJs we need the use of the Terminal in VS Code.

1. Open VS Code
2. Go to menu _Terminal_ and Select option _New Terminal_
   
<img width="576" height="311" alt="image" src="https://github.com/user-attachments/assets/02be4e43-9d4a-4f1d-a561-e62fecf717cb" />

3. Run the command "node"

<img width="1910" height="545" alt="image" src="https://github.com/user-attachments/assets/68ab64e6-c25a-4e08-bba0-850446d83fe9" />


## My first file ##
1. Create a new folder in VS Code named "Examples"
2. Create a new file named "hello.js"
3. Add the function "helloWorld"
   
```JS
function helloWorld()
{
    let value1 = "hello"
    let value2 = " world"

    console.log(valor1 + valor2)
}
```
4. Save your changes
5. Go to Terminal and run command "node hello.js"

<img width="868" height="511" alt="image" src="https://github.com/user-attachments/assets/afb7f151-2740-47ac-8b08-c35d2ea6a266" />


