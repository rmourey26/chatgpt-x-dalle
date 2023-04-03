# chatgpt-x-dalle (CXD)

## CXD combines two of the best AI tools currently available - OpenAI's ChatGPT and DALLE - into one simple, easy to use app. Within seconds, users can toggle between 4 AI models including ChatGPT-3.5-turbo, GPT-3, CODEX, and of course DALLE image generator. The app also provides a great starting point for developers looking to build openai integrated software and applications. Please keep in mind that this is not a production level application and may contain issues/bugs. The app presently utilizes an Express server and a mixture of HTML and JS on the client side.

Need a React.js version? Check [here](https://github.com/rmourey26/chatgpt-react)


<a href="https://www.buymeacoffee.com/rmoureyjr" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="51" width="217"></a>


## Features
- User-friendly interface for making requests to the OpenAI API
- Responses are displayed in a chat-like format
- Select from models GPT-3.5-tubo, GPT-3, Codex, and DALLE image 
- Highlight code syntax

## Technologies Used
- Client Side - JS, HTML
- Server Side - Express
- Support for NixOS nix-shell
  - $ nix-shell 
  - if you're running NixOS, you already know what to do ;-)

## Setup
### Prerequisites
- Node.js
- OpenAI API Key
### Installation
1. Clone the repository:
```sh
git clone https://github.com/rmourey26/chatgpt-x-dalle
```
2. Install the dependencies:
```sh
npm install
```
3. Create a .env file in the root folder and add your OpenAI API key in the following format:
```sh
OPENAI_API_KEY=your_api_key
```
4. Start node server
```sh
node index.js
```
5. Now when you navigate to http://localhost:3001 you will see web response.

## Usage
- Type in the input field and press enter or click on the send button to make a request to the OpenAI API
- Use control+enter to add line breaks in the input field
- Responses are displayed in the chat-like format on top of the page
- Generate code, including translating natural language to code
- You can also create AI images using DALL·E models 

## Contributing

This project welcomes contributions and suggestions for improvements. If you have any ideas, please feel free to open an issue or create a pull request.

Thank you for your consideration.


