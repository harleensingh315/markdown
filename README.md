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
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
