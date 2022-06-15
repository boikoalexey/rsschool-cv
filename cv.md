## Name: 
#### Alexey Boyko
## Сontacts:
#### Telegram: @AlexeyBoi
#### Discord: Alexey Boyko (@boikoalexey)
## Personal information:
He began his career in IT as a tester in a small startup, where he tested additional functions (widgets) developed for AmoCRM, as well as other CRM solutions for optimizing business processes of enterprises.

In the process, I learned HTML, CSS and JS at the level of creating simple sites, and also received training in QA testing from mentor Nikolay Krotov and the course “SQL and PostgreSQL for beginners” from BeOnMax authored by Ilya Fofanov.

Today I hold the position of a WEB tester, combining testing duties with the development of web applications on Vue 3.

## Skills:
HTML, CSS, JavaScript, Vue.js, Git
## Code example:

```
let arr = ['asdfsddf', 'qwr', 'rtyu'];

function each(arr, callback) {
	let result = [];
	
	for (let elem of arr) {
		result.push( callback(elem) );
	}
	
	return result;
}

let callback = function (str) {

    let strUpperCase = str[0].toUpperCase();
    let strFull = '';

    for (let i = 1; i <= str.length - 1; i++) {
        strFull += str[i];
    }
    return strUpperCase + strFull;
}

console.log(each(arr, callback));

```
## English language level:
А1. Breakthrough or beginner