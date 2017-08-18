# Portfolio Part 2: Adventures in jQuery

It can be a drag to write HTML for a bunch of similar pieces of a website. It means writing a ton of lines of HTML that all look nearly identical, just changing a small piece of the HTML each time. For this part of the assignment, you'll use an array of objects and jQuery to create that HTML for you.

1. Make sure you have a JS file created, linked to your HTML. Get a `console.log` working.
2. Create an object representing data about a project. Some basic information you'll want to include: a project title, description, and a link to a picture (maybe a screenshot of the finished project).
3. Use the data in that object to construct an HTML string.
```js
let myHTML = `<h3>${project.title}</h3>`
```
