401 JS --  Lab 29 Todo
===

## Submission Instructions
  * continue working from lab 28
  * open a **new branch** and create **new pull request** and submit a link on canvas
  
## Feature Tasks 
Refactor and add the following components. 



#### NoteForm 
Modify the NoteForm component so that can be used for updating a note as well as creating a note 

#### Refactor the NoteItem 
If the user double clicks on the notes content it should switch to the Edit View  
* Default view  
  * Display the notes title, content and a delete button
* Edit View 
  * Show the NoteForm and a Cancel Button
  * onComplete the noteform should update the notes title or content

#### Modal 
* Create a modal component that uses `this.props.children` to define the content of the modal
* Use the modal some where in you app

#### App Component Tree
Your components should be nested in the following layout  
``` 
App
  Landing
  Dashboard
    NoteForm
    NoteList
      [NoteItem]
        NoteForm
```


####  Documentation  
Write a description of the project in your README.md
