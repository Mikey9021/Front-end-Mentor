 Frontend Mentor - QR Code Component Solution

This project is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges provide an excellent platform to enhance coding skills by working on realistic projects.

## Table of Contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Useful Resources](#useful-resources)
- [Author](#author)

## Overview
This project serves as a beginner-level solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Specifically designed for front-end developers, this challenge aims to provide a hands-on experience in creating a QR code component.

### Screenshot

![Screenshot 1](QR_Component/images/Screenshot%202024-01-11%20at%2019-04-25%20QR.png)
![Screenshot 2](QR_Component/images/Screenshot%202024-01-11%20at%2019-04-50%20QR.png)


### Links

- Solution URL:[Vercel Live Site](https://front-end-mentor-j1tg.vercel.app/)

## My Process
- Create a Repository
- Planned out the project
- Created Project Files
- Structured the page
- Added styling
- Encoded the QR-code
- Replaced place holder image
- Push to github
- Enable github pages
- Hosted site on Vercel
### Built With

- HTML5 
- CSS 
- Flexbox
- [QR code encoder](https://goqr.me/#t=url)

## Useful Resources

- [W3Schools](https://www.w3schools.com/) - This resource provides excellent explanations and real-world use cases for HTML, CSS, and JavaScript, making it a valuable learning tool.

## Author

- Michael-Angelo Obeng-Konadu
  - Frontend Mentor: [@Mikey9021](https://www.frontendmentor.io/profile/Mikey9021)
  
### What I Learned

During this project, I focused on [Working on my CSS styling, specifically the flex box to arrange elements on the page. I also employed the use "divs" to separate elements into containers. the process overall help me structure the page properly before styling.]. Here are some code snippets I'm proud of:

```html
   <!-- Wrap the QR code and text in a container -->
    <div class="qr-component">
       
        <!-- Display the QR code image -->
        <div id="qr-code-container">
            <img src="images/qrcode(4).png" alt="QR Code Image" id="qr-code"/>
        </div>

         <!-- Display the text below the QR code -->
        <div id="qr-code-text"> 
            <h1 >Improve your front-end skills by building projects</h1>
            <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level.</p>
        </div>
</div>


  /* Style the QR code container */
  #qr-code-container {
    width: fit-content;
    display: flex;
    flex-direction: column;
    background-color: #3890f5;
    padding: 25px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    margin: 0 auto;
    max-width: 500px;
  }

 /* Style the QR component container */
  .qr-component {
    max-width: 200px;
    display: flex;
    flex-direction: column;
    margin: 0;
    padding-left:5px ;
    padding-right: 5px;
    padding-bottom: 12.5px;
    padding-top: 12.5px;
    justify-content: center;
    background-color: rgb(253, 253, 253);
    border-radius: 10px;
  }


