## Function to easily import all required Node.js Models automatically with one line in App.js

### About the Project

Node.js often requires you to import or require various data models for the application and server to operate correctly. This can often mean individually requiring each model in App.js.

And what if a model changes, a new one is needed, or an old one is no longer neccessary? Typically, there would be no other choice but to manually change the required models in App.js.

Instead, we can initalize all needed models by importing them in one central location, then automatically require all of them using a function. We can then import that function into App.js.
Not only can we require all our models in one line, but even if models change we don't need to change any code in App.js. We can just add or delete to the required list of models our function should import.

### Technologies Used
- Node.js
- Express.js