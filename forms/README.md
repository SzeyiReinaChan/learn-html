## Getting Started

- Install the version of Node JS for your OS https://nodejs.org/en/download
- From a terminal run the following commands to check if the installation was successful:
  - `$ node -v`
  - `$ npm -v`
  - Set PATH environment variable to path/to/bin/node and path/to/bin/npm if the above commands failed to return the version number.
- In the terminal install dependencies using the command:
    `$ npm install`
- In the terminal run the local server using the command:
  - `node form-server.js`
- Open "form.html" in a browser. Enter username and password and click "Submit".

## Questions for you to answer
1. What is the purpose of the _action_ attribute in the _form_ tag?
- For the action attribute, when the user press the submit button, the data will get send to the server. In this case, it is sending to http://localhost:3000/login.
2. What is the purpose of the _method_ attribute in the _form_ tag?
- The method attrubute is use for user and server communication. In this case, the form is using GET to retrieve resource.
3. What is the purpose of the _name_ attribute in the _input_ tag?
- The name attribute is what the server use to identify the input value.
4. What is the purpose of the _type_ attrbute in the _input_ tag?
- The purpose od the type is to specify the type of input that it should be getting. 
5. What is the purpose of the _label_ tag?
- The label tag includes the text/name of the input.
6. What is the purpose of the _required_ attribute?
- The required attribute means that the those fill must be filled before processing.

