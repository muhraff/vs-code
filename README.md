# vs-code
VS-Code Tips &amp; Tricks 


### Remove empty lines in Visual Studio Code

Reference: https://stackoverflow.com/questions/36350324/visual-studio-code-delete-all-blank-lines-regex

Extensions: https://marketplace.visualstudio.com/items?itemName=usernamehw.remove-empty-lines

Method 1:

- In the find box type `\n\n`
- In the replace box type `\n`
- Make sure the 'Use Regular Expression' is selected
- Select 'Replace All' button
 
Method 2:

- In the find box type `^(\s)*$\n`
- Leave the replace box empty
- Make sure the 'Use Regular Expression' is selected
- Select 'Replace All' button 

