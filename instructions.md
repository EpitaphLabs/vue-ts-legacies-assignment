# Memorial Information Gathering
Build a platform for gathering information on users about their life.
Users will be presented with a question. They can respond with text answers.
They may skip a question or end the process.
Once they submit a response, they can browse all previous questions and response or they can ask for a new question.

##Technology Stack
- Vue 3
- Typescript
- Tailwind css (optional)

## Step 1: Implement a Frontend Experience
Implement a frontend experience that is appealing to users.
Use fake data for this portion

1. Question and Response Form
- A Form that asks a user a question, allows then to skip the question, cancel or submit.
- Add form validation.
- Add elements that make for an attractive user experience.

2. Response Browser 
- Add a page that lists all previous responses to questions.
- Allow the user to modify or delete previous responses
- allow the user to sort or filter the responses by various criteria.

## Step 2: Mock up api calls with a vue 3 composable function to get questions and submit response
Mockup a vue 3 Composable function(s) that calls an api to preform actions required for the app

1. Get Question
- endpoint /get-question
- returns type Question

2. Submit Response
- endpoint /respond
- returns an error on failure

3. Responses
- endpont /responses
- returns type Array<Question>
