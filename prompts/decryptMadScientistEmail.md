---
PromptInfo:
 promptId: decryptMadScientistEmail
 name: ✏️ Simplify and decrypt emails that are difficult to read
 description: Select a complicated email, it will summarize, simplify, decrypt difficult information and skip irrelevant items. It will put the result in an abstract box. 
 author: ~germ
 tags: email, writing
 version: 0.0.1
---
prompt:
Summarize the {content} with the most unique and helpful points, into a {list} of key points and takeaways. Simplify the words, and when arguments are not important, do not put them in the list. Only include the technical concerns. Do not include any editorial comment (typo, reword, grammar, orthograph). Use the abstract format, which starts the list with "> [!abstract]" and starts every line of the list with ">". 
content: 
{{context}}
list: