# AI Chatbot: Intelligent Chatbot for Company Performance Metrics

AI Chatbot is an innovative chatbot project leveraging OpenAI's advanced language model capabilities along with Langchain's ChatOpenAI framework. It's designed to assist users in querying company performance metrics effortlessly through natural language.

## Project Overview

The core functionality of ChatOpenAI revolves around processing user queries related to company performance metrics. The application takes user input, identifies key information such as the company name, performance metric, and time period, and organizes it into a structured JSON format.

## Key Features

- **Entity Recognition**: ChatOpenAI efficiently extracts the company name mentioned in the query, ensuring it's capitalized for consistency.
  
- **Parameter Identification**: The application accurately identifies the performance metric specified in the user query, enhancing data precision.
  
- **Dynamic Date Handling**: ChatOpenAI intelligently manages date information, defaulting to appropriate values if not explicitly mentioned in the query. It supports various date formats and relative date ranges for enhanced user flexibility.
  
- **Query Variations Handling**: The chatbot effectively handles variations in user queries, accommodating different spellings, abbreviations of company names, metric parameters, and date formats.
  
- **Chat History Management**: Implemented ChatMessageHistory feature retains a concise record of the previous four messages, optimizing memory usage while maintaining conversation context.

## Getting Started

To get started with ChatOpenAI, follow these steps:

1. **Clone the Repository**: Clone the repository to your local machine.
   
2. **Install Dependencies**: Ensure all necessary dependencies are installed (1st cell of the ipnyb file).
   
3. **Configure Environment**: Set up the necessary API keys.
   
4. **Run the Application**: Execute the cells one by one to start the chatbot.
   
5. **Interact with the Chatbot**: Once the application is running, interact with the chatbot by providing queries related to company performance metrics.

## Example Usage

Below is an example of how to interact with ChatOpenAI:

###### User Input
query = "What was the revenue of ACME Corporation last quarter?"

###### Output
{
    "entity": "ACME Corporation",
    "parameter": "revenue",
    "startDate": "2023-01-01",
    "endDate": "2023-03-31"
}
