# NashWD-1B

## DREAM VACATION WEBSITE
[TERMINAL HELP](https://github.com/sarah-codebug/NashWD-1A)

#### Your mission is create a webpage for your dream vacation.
1. Find a spot where you would like to vacation 
2. Via the terminal, create a new folder on your desktop called `coding`.
3. `cd` into your `coding` folder and create another folder called `NashWD-1B`
4. `cd` into your `NashWD-1B` folder and create a `dream-vacay.html` file.
4. Use the `subl` command to open the file in Sublime. 
5. Click on the `dream-vacay.html` file, type `html` in the file, and hit `tab`. 
    * If that didn't autofill html for you, copy and paste this into your html file: 
    ``` HTML
      <!DOCTYPE html>     
      <html>
         <head>
           <title></title>
         </head>
         <body>
         </body>
      </html>
    ```
6. Add a title for your page in the `title` html element with the name of your dream vacation spot. 
7. Use `open dream-vacay.html` from your terminal to see your file in your web browser!

# THE CODE
> Don't worry if your vacation site doesn't look great, you'll be adding the styles later. 

Your vacation page should include the following:

* You will be writing all of your HTML inside of the `<body>` tag. For example:
    ``` HTML
      <!DOCTYPE html>     
      <html>
         <head>
           <title></title>
         </head>
         <body>
           <!-- write your HTML code here -->
         </body>
      </html>
    ```
* A heading with the name of your destination.
* A paragraph explaining some attraction and/or fun facts about your destination.
* A picture of the destination. Or many pictures if you'd like!
* An unordered list of some sort (local attractions, animals in the area...).
* An ordered list (best restaurants, best hotels, best beaches).
* Links to 3 other similar destinations to suggest to your visitors.
* Create a form that allows people to write a comment on your page. (Note: This will not actually function yet)
> *HINT!!! you will be using `<form method="post">` don't worry about the `action` attribute yet, we'll talk about those later! [Here](https://www.w3schools.com/html/html_forms.asp) is a good example
* Use `touch` to create another html file inside your `NashWD-1B` folder. You can call it something like `application.html`. We are going to create an application for your friend to "apply" to go on this trip with you (ALL EXPENSES PAID).
* Open `application.html` in sublime. Use `html` tab to create your base HTML. 
* Add a header to your `application.html` that says something like "Apply to vacation with me!"
* Open `application.html` in Chrome to make sure your header worked!
* Now let's add a link to apply on your `dream-vacay.html` that brings the user to this page `application.html`. You will need to use an `<a>` tag. It will look something like this: `<a href="application.html">Apply!</a>`
* In `application.html` 
    * add a paragraph tag that explains the purpose of this application.
    * Create a `<form>` 
    * Explore the different `<input>` types that can be used in a form. Here's a [good list of the different input types](https://www.w3schools.com/html/html_form_input_types.asp).
    * Add at least 4 different input types to your application form. Get creative! What qualities are you looking for in a travel buddy?
* Use an `<iframe>` to add a video to your site. Here's a [great link](https://www.w3schools.com/html/html_youtube.asp) with some added features for YouTube videos.
    

#### EXTENSION

* Add a `<table>` of expenses summarizing how much this trip would cost. (You can make these up if you would like to! A luxurious trip to Paris for $5.00 :)) 
> *Check out this image if you need inspiration* ![table](/table-image.png) 
* Begin styling your website!
    * Note: You'll need to create a `style.css` page for your CSS styling.
    * Once you've created `style.css` you need to link your CSS file to our HTML file. If you've forgotten how to do that, check out this [link](https://teamtreehouse.com/community/htmlcss-linking).



