# *Words we learned so far:*

## W1D1
* __Web App__: A website that has a server behind it and has some data that is going to live somewhere in a database between times you visit. 
* __The Cloud__: the cloud is essentially a computer that holds other 'virtual' computers within it. This is possible because computer processing power is powerful enough that we are able to split up a processor into several 'smaller virtual processors'.
* __Version Control__: a way of keeping track of changes in code across time or developers.
* __Git__: a type of version control that allows us to track changes and go back to previous versions.
* __GitHub__: an online cloud-based software to host git repos.
* __Front End__: the things the user sees - e.g. html, css, javascript
* __Back End__: the code that talks to the database and runs the web server, in our case ruby, rails & active record.
* __Database__: the technology that holds our data to be dynamically displayed on the page by our app.
* __Heroku__: a cloud based service that we can use to host web apps.
* __Open Source__: a type of technology where anyone can view or request a change to the software.
* __IDE__: Integrated Development Environment, a one stop shop for updating code, running your webserver and interacting with the commandline.
* __Cloud9__: our cloud-based IDE of choice for this course. 
* __Boilerplate__: a basic set up to work with for any particular web app framework (e.g. Sinatra). 
* __Stack__: the different technologies and languages to a working web application. Different companies have different "stacks".

## W1D2
* __Semantic__: Semantic means *meaning*... to eleborate, it provides 'context' behind the text and content that you decide to stuff into an html page. In order for a browser to 'see' a page like we do, they require the meaning behind the content so that they some particular text is a header for example. 
* __Element__: An element is a complete HTML tag. This could be something like `<p>I'm a paragraph</p>` or a self-closing tag such as `<img src="..." >`
* __Nesting__: When you stuff HTML elements inside of other elements, that's called nesting. This is a common practice and in some occasions it's required such as in `<ul>` tags and `<form>` tags. Make sure to indent your code as you nest to make debugging.
* __Cloud 9__: Cloud 9 is your IDE (integrated developer environment). It's an online service that you will develop your finstagram apps on. 
* __IDE__: an ide is your one stop shop for developing. it is generally an application that has everything you need from writing.

## W2D1
* __CSS__: Cascading style sheets, or the style language of the web.
* __Selector__: the html element(s)/tag(s) that are being targeted and styled with the CSS language, elements can be selected by their tag name, class and or id as well as several other pseudo-selectors (<--more advanced css). IE:
```
  <h1 class="titles" id="main-title">Hello World</h1>
 /*selecting by tag name*/ 
 h1 {
   ...
  }
  /*selecting by class*/
  .titles {
   ...
  }
  /*selecting by id*/
  #main-title {
   ...
  }
```
* __Property__: the styling rules that can be applied to a selector. IE: border, background color, text color etc.
* __Property Value__: the different values that a CSS Property may have. IE:
```
  /*property: value*/
  background-color: red;
  background-color: blue;
```
* __Box model__: The way that css thinks about each element on the page. [see this link for the perfect metaphor for the box model!](https://medium.freecodecamp.org/css-box-model-explained-by-living-in-a-boring-suburban-neighborhood-9a9e692773c1?gi=8dfe07df3608)
* __Padding__: The space within an element.
* __Margin__: The space betweeen an element and other things.
* __Stylesheet__: A collection of css that we can add to the `head` section of our page to apply the style rules within it.
* __Class tag__: A way of linking a style rule to a piece of html.
* __Id tag__: A unique way of linking a style rule to a piece of html. Useful to make sure that you aren't accidentally applying the same rule where you didn't intend to.

## W2D2
* __Ruby__: a programming language - the one we will be using to program our finstagram in!
* __Integers__: A data type in Ruby. Refers to whole numbers e.g. -1, 0, 343, 1828281, -123
* __Floats__: A data type in Ruby. Refers to numbers with decimal points e.g. -1.9912, 0.001, 3.934
* __Booleans__: A data type in Ruby. Can only be true or false.
* __Strings__: A data type in Ruby. The way to store and work with text e.g. “Hi i’m a string”, ‘I\’m also a string’
* __Operators__: The way to do math in programming.
* __Concatination__: Joining strings together.
* __Variables__: How we temporarily store information (not in the database... or at least maybe not yet) so that we can store information for use later in our code.
* __Snake Case__: The way that we name variables in Ruby. Developers are strict about following standards (aka conventions) like this so that it's easier to read each others code. 
* __String Interpolation__: A way to include the result of your variable right into your strin
g! E.g. "Hello, #{first_name} welcome to my fancy customized sentence!". 
* ____: 
* __Control Flow__: The way that we help the computer do if/else logic to make decisions about what to do in a given situation. This is also sometimes call "conditional logic".
* __Methods__: The way to store a set of code that we can reuse at another point in time in our code so that we don't have to repeat ourselves as often. Ruby has a LOT of built in methods that you can use so you don't have to write a bunch of complicated code to do fancy things. In other languages these are sometimes call functions.
* __Argument__: The fancy name for a variable that we use within a method as a placeholder. 
* __Returning__: The name for the end result of what a method "spits out" at the end when it finishes evaluating. Ruby is a bit different than other languages in that the last line of code that runs in a method is the result that the method returns.
* __Hash__: A fancy way to hold data in Ruby so that you can return it later. They are stored in "key value pairs", where the key (that you as a developer can predict) will be on the left, and the value (that may be entered by the user) is stored on the right. This lets us access data from our app in an easy way. Think of it like super organization for your data. 
* __Array__: A list of things - it could be a list of strings, a list of numbers, a list of hashes or even a list of lists (an array of arrays)! You access this by referring it's position in the list, which in programming will ALWAYS start at 0. 


## W3D1
* __ERB__: Embedded Ruby - the way we connect our ruby code to our html to display templates.
* __<%= yield %>__: A special variable that will load in an erb file with "subcontent" into our base html page.
* __Instance variable__: A way to let a variable's data be "seen" by the erb template by adding an `@` symbol in front of the variable name.
* __Alligator tags__: the symbols we wrap our ruby code in within our html so it knows where the html stops and the ruby starts (and vice versa!). For ruby logic, it looks like this: `<% rubycode %>`, and for an individual piece of data we want to show on the page we use `<%= data %>`
* __DRY__: Don't repeat yourself! One of the many reminders to ourselves not to re-type things if we don't have to, because we are ~~lazy~~ efficient.
* __View__: The shorthand term for our ERB file. It means "the thing the user _views_".
* __Actions__: Our list of things to "do" when a certain view is accessed, located in our actions.rb file and broken up into different `get '/something' do ... some code ... end` blocks
* __Iterators__: What we call a method that loops over a set of data in some way so we can DO something with it in our 'do block'

## W3D2
* __Database__: In a nutshell is a place where data can be stored **persistently**
* __Persistance__: In the database realm, persistance means data that will not be lost if the computer loses power. Think hard drive, that's a persistance storage mechanism
* __Relational Database__: A particular type of database that organizes data like an Excel Sheet:  tables, columns and rows.
* __Table__: is a container for holding all data that describes a particular thing. In finstagram we have tables for users, posts, comments etc.
* __Columns/Fields__: All of the seperate properties that belong to a table to describe the things being stored in the table. For example in a users table we may have columns named name, username, email, password etc.
* __Rows__: each individual record inside a table. They are generally given some type of unique identifier like an auto-incrementing 'id' number
* __ORM__: a programmatic way of interacting with a database minus all of the SQL. ORM stands for Object Relational Mapper. It 'Models' a representation of a table in the database and provides a generally easy programming interface (with methods) to interact with to perform CRUD
* __Active Record__: is the ORM that we are using inside of our applications. It is a ORM built in Ruby which allows us to use Ruby code to interact with a SQL database
* __Query__: is an interaction with the database. We query the database to insert data, remove data, update data, and retrieve data
* __Active Record Model__: is functionally a *Ruby Class* that represents or **models** a particular table in the database. It inherits special powers from the ActiveRecord class to provide us with a huge set of methods that allow us to interact with the database.
* __Class__: This is something that's generally apart of all Object Orientated Languages. A Class is generally a *blueprint* of a 'thing'. It contains methods and properties that describe the thing. We could have a `class House` which may have properties like `number_of_floors` or `square_footage` as well as methods like `def open_door` or `def turn_off_all_lights`
  
## W4D1
* __Query__: The word to describe how to retrieve specific data from a database.
* __Associations__: How we describe relationships between types of data in our database.
* __Class__: The object-oriented way to create objects that has access to methods and contain data.
* __Inheritance__: The way we allow our classes to have access to the methods of other Classes... without having to retype it all.
* __Instance method__: A method that lives within a class. Each "instance" of that class (aka an object) can "call" (use) that method without impacting the way other objects behave.
* __Validations__: How we check that the data being entered into the database for each class meets specific criteria, so that it's nice and clean and tidy in our database.

## W5D2
* __Session__: A unique, secret identifier that allows the browser to know about a user in between pages as long as that user is logged in.
* __Cookie__: The browser's data that it stores about the user.
* __Helpers__: Sinatra's word for Ruby methods that any view can access (for security and confusion reasons we don't usually do that!) 

## W6D1
* __Media Query__: A way to target specific styling at different browser sizes
* __Permissions__: How we control which users are allowed to see which pages
* __HTTP Codes__: Numbers that correspond to different responses from the server
