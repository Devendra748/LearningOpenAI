# LearningOpenAI
## Create openApiKey
To generate an OpenAPI key, it is necessary to create an OpenAI account, proceed to the profile section, and then access the View API Keys option. Subsequently, it becomes possible to generate your own unique API key.

## function get_completion(prompt, model="gpt-3.5-turbo") 
The function "get_completion" takes a prompt as input and utilizes the OpenAI API to generate a completion based on the specified model (default: gpt-3.5-turbo). The temperature parameter controls the randomness of the model's output. The function returns the content of the generated completion.

## function get_completion_from_messages(messages, model="gpt-3.5-turbo", temperature=0)
The function "get_completion_from_messages" takes a list of messages as input and uses the specified language model to generate a completion. It returns the content of the generated message, controlled by the temperature parameter for output randomness.

# Additional functions of chat bot
## function collect_messages(_)
This function collects user input, generates a response using a language model, updates the conversation context, and displays the user's prompt and the assistant's response in a panel.

### Install the Package by : **pip install panel**

## Graphical User Interface of Chat Bot
The given code snippet demonstrates the usage of the Panel library for creating a graphical user interface (GUI). It imports the necessary dependencies, defines a system message, collects user input, and creates an interactive conversation widget displayed in a dashboard layout.
