# Portfolio Part 2: Adventures in jQuery

It can be a drag to write HTML for a bunch of similar pieces of a website. It means writing a ton of lines of HTML that all look nearly identical, just changing a small piece of the HTML each time. For this part of the assignment, you'll use an array of objects and jQuery to create that HTML for you.

Your overall goal is to use an array of objects, where each object has data about a single project. You'll loop through that array, constructing HTML about that project and adding it to the page.

Please have <strong> at least </strong> three project objects that you are looping through on your page. Your projects should have at least a name, an image, and a link to your project.

Note that these don't have to be actual projects that you've done. Feel free to make them up if you don't have three to add to your page. 

Please start by writing pseudocode for how your code will look. How will you approach this problem? Put this pseudocode in your JS file, in the form of a comment.

<details><summary>Sample pseudocode here!</summary>

```
Create a JS file and link it. Within that file,
create this array of objects with information about projects.
After the document is ready,
  Loop over that array of objects. For each object,
    Construct an HTML string representing that project
    Add it to the page
Done

```

</details>

Now that you've thought about how to solve the problem, here are some steps you might take to get this working.

1. Make sure you have a JS file created, linked to your HTML. Get a `console.log` working.
2. Create an object representing data about a project. Some basic information you'll want to include: a project title, description, and a link to a picture (maybe a screenshot of the finished project).
3. Use the data in that object to construct an HTML string.
```js
let myHTML = `<h3>${project.title}</h3>`;
// with more for the other pieces of data you have about your project
```
4. Append that HTML string somewhere on your page. (If nothing's happening, make sure you're adding your content after the document is ready!)
5. Once you're satisfied that you can add ONE project to the page, extend your object into an array of objects, and loop through those objects. You shouldn't have to change your code from steps 3 and 4 much, except that they're now in a loop.

This is what's _required_ for Monday. If you get through this and still need more challenges, options include:
* Incorporate flex layout in your portfolio
* Re-do your portfolio's CSS with Bootstrap
  -Incorporate Bootstrap JS components for modals/carousels/whatever features interest you
* Add more information about each project & incorporate that in what you append to the page
* Add projects from earlier in the week to your portfolio. Make a page that sings the bottles of beer song, or that generates Shakespearian insults and puts them on the page. Take those pure-JS exercises you worked on earlier, and incorporate them with HTML/jQuery to make them part of your site.
* Literally anything else that makes this portfolio into a more interesting or useful site for you to work on

On Monday, we will pair up and you'll review each others' code, so you might also want to make sure your code is ready to be read/understood by a classmate.
