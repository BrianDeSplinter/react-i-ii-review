### Remember

Answer these on your own, then compare answers as a group

1.  What is React?
      React is a Javascript library created by Facebook for building component based websites. Allows you to create dynamic SPA's (single page applications)

2.  What is create-react-app?
      It is the command to create a new React project, it brings in all react libraries and sets up the tools to create a new project

3.  What is Component Based Architecture?
      It is a way to break up the code into chunks that do individual tasks to make it easier to debug and easier to read

4.  What is JSX?
      JSX is the language that React uses that has syntax similar to HTML so it can run JS and HTML together

5.  What is the virtual DOM?
      It is a copy of the DOM that runs in react that can render each component individually so the whole page doesn't have to refresh it then compares to the DOM and reconciles it as needed

6.  What is unidirectional (one-way) data flow?
      Data flows from parent to child

### Understand

Discuss these questions in pairs if you have a 4-person group

7.  Summarize what happens when you run `create-react-app my-app`
      Create a default blank React application called "my-app"

8.  Summarize the steps for forking and cloning a repo with an existing React app. How does this process differ from the process of creating a new React app on your laptop?
      To fork and clone is the same but then you must navigate into directory and run command 'npm i' to install the React tools because GitHub doesn't have all the base data in every repo.

9.  Explain what this code does:


```jsx
import React from "react";

const Mentor = props => (
  <div className="mentor-container">
    <h1 className={props.title === "Lead Mentor" ? "lead" : ""}>Tim Biles</h1>
    <ul>
      <li>Fort Worth, TX</li>
      <li>My email address is timbilestimbiles@gmail.com</li>
    </ul>
  </div>
);

export default Mentor;
```

10.  Explain how data is passed from a parent component to a child component.
        Props
        
### Apply

Try these on your own, but work together if you start to get stuck.

11.  Use `create-react-app` to create a new React application called `student-directory`

12.  Use the code from `Mentor` above to create a new functional, stateless component called `User` with a list of friends. Hard code the list of friends, do not use state or props.

### Analyze, Evaluate, Create

Discuss these questions as a group

13. What are the benefits and drawbacks of using a tool like create-react-app?

14. Compare and contrast JSX with other templating options, such as those used in Angular or Vue

15. Compare and contrast one-way data flow with two-way data binding.
