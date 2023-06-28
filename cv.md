![Image](avataaars.png)
# 1.	Tanya Larina
## 2.	My Contacts:
* Email: tshnyagina@list.ru
* GitHub: @tyulari
* Discord: Tanya Larina (@tyulari)

## 3.	About Me:

I'm 31 years old. I am working a system analytics in a small IT company. I am interested in web development and try to develop my skills. I hope that this courses will help me to improve my knowledge in this field and find like-minded people.

## 4.	Skills:

* HTML, CSS
* JavaScript (Basic)
* Vue.js (Basic)
* Version control: Git, GitHub
* Editors: VS Code, WebStorm

## 5.	Code Example:

**Unique In Order:** Implement the function unique_in_order which takes as argument a sequence and returns a list of items without any elements with the same value next to each other and preserving the original order of elements.

For example:
```
uniqueInOrder('AAAABBBCCDAABBB') == ['A', 'B', 'C', 'D', 'A', 'B']
uniqueInOrder('ABBCcAD')         == ['A', 'B', 'C', 'c', 'A', 'D']
uniqueInOrder([1,2,2,3,3])       == [1,2,3]
```
My solution:
```
var uniqueInOrder=function(iterable){
  let arr = (Array.isArray(iterable)) ? (iterable) : iterable.split('');
  return arr.filter((el, index, array) => el != array[index+1]);
}
```
## 6.	Working Experience:
   * Freelance
   * "Coca-Cola HBC Russia", AP OCR Accountant (until 2016) 

## 7.	Education:

 * National Research University Higher School of Economics, Faculty of Business Informatics and Applied Mathematics,
Bachelor’s degree in Business Informatics
* National Research University Higher School of Economics, Faculty of Economics, pending Master’s degree in Finance
* JavaScript. Level 1. JavaScript fundamentals ([wwww.specialist.ru](https://www.specialist.ru/), 2021)
* JavaScript. Level 8. Vue.js - an open source JavaScript framework for developing web application ([wwww.specialist.ru](https://www.specialist.ru/), 2022)
* RS School, JS Course Stage 0 in progress

## 8.	Languages:
* Russian - Native
* English - Upper-Intermediate/B2 (Business English Certificate)
