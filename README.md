# 14.MVC

## Notes 
- MVC (MODEL, VIEW, CONTROLLER) - Model is the data, View is the UI, Controller is the link between the model and views. 
- Error 1054: missing a tabel/column to fix this: 
    - db/schema.sql 
    - there will be no tabels to upload a tabel restart server (npm start)
    - enter in data or seeds 
    - all is well. 

- in homepage.handlebars: Note the use of {{#each}} to begin the loop and {{/each}} to define where it ends. Any HTML code in between (e.g., the li element) will be repeated for every item in posts. Refresh the page, and you might be surprised to see that it already works. 
     