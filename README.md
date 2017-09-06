
# How to Create a README.md using Markdown
1. New repository
1. Type repository name
1. Check checkbox "Initialize this repository with a README"
1. To edit the readme.md file, click README.md
1. Click the pencil icon 
1. Type in your text using GitHub Flavored Markdown.  
* Refer to: [GitHub Markdown](https://guides.github.com/features/mastering-markdown/)




# Comp 2112 - Lab1
## Showing how console.table works

Below is an example of an array of objects and how to display it using console.table
```js
const colleges = [
   {'college' : 'Georgian', 'city' : 'Barrie', 'population' : 10000 },
   {'college' : 'Seneca', 'city' : 'Toronto', 'population' : 12000 },
   {'college' : 'George Brown', 'city' : 'Toronto', 'population' : 15000 }   
];

console.table(colleges);
```

The output would be:
![screenshot of console.table](/images/consoleTable.JPG)

