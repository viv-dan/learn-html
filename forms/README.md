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

- It is used to specify what has to be done when the user submits the form. For example it can be used to send request to a webserver with the data that is filled in the form tag.

2. What is the purpose of the _method_ attribute in the _form_ tag?

- It specifies the type of HTTP transaction. It tells how to send the data to the server. For example with a GET transaction or a POST transaction.

3. What is the purpose of the _name_ attribute in the _input_ tag?

- It specifies the data's key so that server can retrieve it with the same key specified in the name attribute. It helps identify the data and retrieve it. Kind of a reference to the data.

4. What is the purpose of the _type_ attrbute in the _input_ tag?

- It is used to specify the type of data that is being expected. for example a simple text or a password or an email and many more. Each type has a special function. password input type can mask the text that is being written into it.

5. What is the purpose of the _label_ tag?

- It is used to specify the name of the input to the end user who is interactign with a certain element in HTML. Can be thought of as a heading to an element too.

6. What is the purpose of the _required_ attribute?

- It is used to make sure the user mandatorily interacts with that HMTL element. For example if an input element has required attribute then user must enter some text for that input otherwise user can't move forward.
