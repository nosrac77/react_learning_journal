### Carson's React Learning Journal

*Note: This file will house all journal entries until the React learning journal application is complete, at which point new entries will exist solely in the application.*
___

**Journal Entry #1** - *Thursday, December 12th, 2019*

First entry into the new React learning journal! Today went well. No serious hangups or errors I couldn't overcome, and although I haven't done much up to this point, I feel like smooth-sailing is a great sign. React is fun! I know I still have a lot to learn but it's nice to see some progress after countless hours spent working through tutorials. Installing ```create-react-app``` globally was my first mistake thus far, but running ```npm uninstall -g create-react-app``` and then ```npx create-react-app learning-journal``` solved the problem immediately. Nothing too crazy so far!

Additional Questions?

Definitely have a lot of questions! But I'll narrow it down to one for now. The question I have is about some code within the template App.js file created when I ran ```create-react-app```. As it stands now, the JSX App component being exported wasn't written using ```React.Component``` but is instead just a normal looking JavaScript function that returns JSX. Is the App function still a valid React component when written this way? Most of the tutorials had me build components using ```class MyComponent extends React.Component``` syntax. Which way of writing components is better? Should I use one syntax style over the other, and if so in what scenarios is it appropriate to use one over the other?