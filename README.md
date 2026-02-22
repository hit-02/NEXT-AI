# Agent AI: A Full-Stack Web-Based Q&A AI Agent for PDF Document Queries

An AI-powered application that enables users to interact with PDF documents via a conversational UI. This project is designed to simplify document analysis, allowing users to query PDF content in real-time, leveraging advanced natural language processing and retrieval techniques.


## Tech Stack

#### Front-End:
- **React.js**: For building an interactive and responsive user interface.
- **Ant Design**: For creating a visually appealing and easy-to-use experience.

#### Back-End:
- **Express & Node.js**: For building the server-side logic and RESTful API services.
- **SIn-Memory Vector Store**: For caching embeddings and optimizing document query retrieval.

#### AI & NLP:
- **OpenAI GPT- 5.0 Turbo API**:  For processing user queries and generating natural language responses.
- **Langchain**: For managing document loading, splitting, and retrieval processes.

#### Other Tools:
- **Multer**: For handling file uploads.
- **PDF-Lib**: For reading and interacting with PDF documents.
- **Axios**: For making API calls.



## Installation

Install the dependencies:
```
npm install
```
To run this project locally, in the root directory:
```
npm start
```
To run the server, navigate to the server directory:
```
cd server
```
Install the dependencies:
```
node server.js
```
Then Run
```
node server.js
```
Or to run the server and front-end all together:
```
npm run dev
```



