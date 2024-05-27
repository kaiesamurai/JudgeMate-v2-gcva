## Inspiration

The inspiration for JudgeMate came from the need to streamline the hackathon judging process. With numerous submissions to review, judges often face challenges in evaluating each project thoroughly and fairly. We aimed to create a tool that leverages AI to assist judges in evaluating code quality, market potential, and overall project feasibility efficiently and accurately.

## What it does

JudgeMate is an AI-powered platform that simplifies the hackathon judging process. It provides judges with the following capabilities:

1. **Market Research Agent:** Quickly assesses the market potential of a project by analyzing its description and answering predefined questions about the target market, existing solutions, and project uniqueness.
2. **Code Analysis Agent:** Scans the project's codebase to evaluate the technologies used, adherence to hackathon rules, and code quality.
3. **Chat Agent:** Offers an interactive chat session where judges can ask questions and get comprehensive answers based on the combined knowledge of the market research and code analysis agents.
4. **Search Agent:** Enables judges to perform semantic searches using plain English queries, making it easier to find relevant projects among numerous submissions.

## How we built it

We built JudgeMate using the following technologies:

### Backend:
- **FlaskAPI:** For creating the RESTful API.
- **MongoDB:** For data storage and management.
- **Google Vertex AI:** For deploying and managing our AI models.
- **LangChains:** For building and integrating the AI agents.

### Frontend:
- **SvelteJS:** For building a responsive and dynamic user interface.
- **Tailwind CSS:** For styling the application with a modern and clean design.

## Challenges we ran into

1. **Integrating Multiple AI Models:** Ensuring smooth integration and communication between various AI models and agents.
2. **Data Privacy and Security:** Maintaining the privacy and security of the data processed by our platform.
3. **Scalability:** Designing the platform to handle a large number of project submissions without performance degradation.

## Accomplishments that we're proud of

1. **AI Integration:** Successfully integrating advanced AI models to create a comprehensive tool for hackathon judges.
2. **User-Friendly Interface:** Developing an intuitive and easy-to-use interface for judges to interact with the platform.
3. **Efficient Evaluation:** Streamlining the evaluation process, allowing judges to make informed decisions quickly and accurately.

## What we learned

1. **AI Model Training:** Gained insights into training and fine-tuning AI models for specific tasks.
2. **User Feedback:** The importance of user feedback in refining and improving the platform.
3. **Collaboration:** Effective collaboration between frontend and backend teams is crucial for the success of the project.

## What's next for JudgeMate

1. **Enhancing AI Capabilities:** Further improving the AI models to provide even more accurate and insightful evaluations.
2. **Expanding Features:** Adding new features such as detailed project reports and integration with popular hackathon platforms.
3. **User Testing:** Conducting extensive user testing to gather feedback and make continuous improvements.
4. **Scalability Improvements:** Enhancing the platform's scalability to handle larger hackathons with ease.




# JudgeMate - Frontend
#### YOUR TRUSTED ALLY FOR HACKATHON JUDGING
#
The backend code for the project can be found here

## What is JudgeMate?

JudgeMate streamlines the evaluation process for hackathon judges by leveraging AI to assist in code examination, market research, and providing interactive chat capabilities, along with an efficient semantic search functionality to navigate through numerous project submissions.

## How does it work?

JudgeMate uses Langchains and models in Google Vertex AI to build the following agents:

1. **Market Research Agent:** This agent uses the project description to ask a set of predefined questions about the idea, such as the size of the target market, existing solutions, and the uniqueness of the project. These questions provide judges with quick insights into the project's potential.

2. **Code Analysis Agent:** The code agent thoroughly scans the entire project's codebase and asks predefined questions about the technologies used, whether the project adheres to the hackathon's rules, and the quality of the code. This analysis helps judges evaluate the technical aspects of the project.

3. **Chat Agent:** This agent offers an interactive chat session where judges can ask questions and have a conversation. It combines the knowledge obtained from both the code analysis and market research agents, providing judges with comprehensive information to make informed decisions.

4. **Search Agent:** With a large number of submissions in a hackathon, finding specific projects can be challenging. The search agent enables judges to perform searches using plain English queries, making it easier to find relevant projects based on specific criteria.

## Technologies Used

The backend is using the following technologies:

- FlaskAPI
- MongoDB
- Google Vertex AI
- LangChains

The frontend is using the following technologies:

- SvelteJS
- Tailwind CSS

## Setup

To get started with the project, follow these steps:

1. Clone the repository: `git clone 
2. Install dependencies: `npm install`
3. Start the server: `npm run dev`

## Submission Video

# JudgeMate - Backend
#### YOUR TRUSTED ALLY FOR HACKATHON JUDGING
#
The frontend code for the project can be found here 


## What is JudgeMate?

JudgeMate streamlines the evaluation process for hackathon judges by leveraging AI to assist in code examination, market research, and providing interactive chat capabilities, along with an efficient semantic search functionality to navigate through numerous project submissions.

## How does it work?

JudgeMate uses Langchains and models in Google Vertex AI to build the following agents:

1. **Market Research Agent:** This agent uses the project description to ask a set of predefined questions about the idea, such as the size of the target market, existing solutions, and the uniqueness of the project. These questions provide judges with quick insights into the project's potential.

2. **Code Analysis Agent:** The code agent thoroughly scans the entire project's codebase and asks predefined questions about the technologies used, whether the project adheres to the hackathon's rules, and the quality of the code. This analysis helps judges evaluate the technical aspects of the project.

3. **Chat Agent:** This agent offers an interactive chat session where judges can ask questions and have a conversation. It combines the knowledge obtained from both the code analysis and market research agents, providing judges with comprehensive information to make informed decisions.

4. **Search Agent:** With a large number of submissions in a hackathon, finding specific projects can be challenging. The search agent enables judges to perform searches using plain English queries, making it easier to find relevant projects based on specific criteria.

## Technologies Used

The backend is using the following technologies:

- FlaskAPI
- MongoDB
- Google Vertex AI
- LangChains

## Setup

To get started with the project, follow these steps:

1. Clone the repository: `git clone 
2. Install dependencies: `pip install -r requirements.txt`
3. Create a `.env` file and add the following variable `GOOGLE_APPLICATION_CREDENTIALS=<path of the service worker json file>`
4. Start the server: `python server.py`
5. The server runs on port `8000`

