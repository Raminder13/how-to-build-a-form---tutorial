## FORM
In ```HTML```, a ```form``` is an element that allows users to input and submit data to a web server.
It typically contains various types of ```input fields```, such as text boxes, checkboxes, radio buttons,
dropdown lists, and buttons, which enable users to enter information such as their name,
email address, password, etc. Once the user has completed the form, they can submit it by
clicking the ```submit button```, which sends the data to the server for processing.

### How to build a form using HTML and CSS
To create a form using HTML and CSS, follow these steps:

1. Create a new HTML document by opening a text editor and typing the following code:
```HTML
<body>
    <main>
        <div class="container contact-box">
            <form>
              <h2>Form</h2>
              <input type="text" placeholder="Your name">
              <input type="Email" placeholder="Your email">
              <input type="text" placeholder="Phone number">
              <textarea placeholder="Message"></textarea>
              <a href="mailto:example123@gmail.com">Send</a>
            </form>
        </div>
      </main>
</body>
```
2. In this example, we've created a basic contact form with three fields: name, email, and message. The form element contains the input fields and a submit button. Each input field is created using the label and input elements.

3.Now let's add some CSS to style the form. Create a new CSS file and link it to the HTML document by adding the following code in the head section:
```CSS
    <link rel="stylesheet" href="index.css">
```
4. In the CSS file, we can add styling for the form elements. Here's an example of some basic styling:
```CSS
* {
    margin: 0;
    padding: 0;
}

main {
    height: calc(100vh);
    background-color: #f2f2f2;
    display: grid;
    place-items: center;
   
 }
 
 .contact-box {
   display: grid;
   height: 490px;
   width: 300px;
   background-color: #fff;
   border-radius: 10px;
   text-align: center;
 }
 
 input[type], textarea
 {
   height: 50px;
   width: 200px;
   margin: 10px;
   border-radius: 10px;
   padding: 0 30px;
 }

 form a {
    background-color: #808080;
    color: #000;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
    margin-top: 70px;
    font-size: 24px;
    font-weight: 600;
 }

 form {
    margin-top: 30px;
 }

 textarea {
    margin-bottom: 30px;
 }
 ```
 
 Save both the HTML and CSS files, and open the HTML document in your web browser. You should now see a basic contact form with some styling applied.
