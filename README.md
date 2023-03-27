# **My Porfolio**

## **Description**

* This project aimed to learn how to create an accessible website using HTML, and CSS and to practice git commands. The motive of this project was to produce a starting code from scratch to develop a portfolio website that will allow others to see my work progress for future jobs.

### **Code Refactor**

### HTML

- **Before**

```html
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="./assets/portfolio.css">
  <title>MyPortfolio</title>
</head>
  ```
- **After**

  * Added meta elements to add icons to give reader a visual icon link [FontaAwesome](https://fontawesome.com/search)

```html
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="./assets/portfolio.css">
  <script src="https://kit.fontawesome.com/b01ca0e7d7.js" crossorigin="anonymous"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <title>MyPortfolio</title>
</head>
 ```

### CSS

- **Before**

```css
.main-img{
  display: block;
  width: 800px;
  height: auto;
  border-radius: 20px;
  box-shadow: 0px 3px 50px 5px black;
  }
```
- **After**

  * Added Css variables function "var("")" to simplify code [Var fucntion](https://www.w3schools.com/css/css3_variables.asp)

```css
.main-img{
  display: block;
  width: 800px;
  height: auto;
  border-radius: 20px;
  box-shadow:var(--boxShade);
}
```

## **Technology Used**

| Technology Used         | Resource URL           | 
| ------------- |:-------------:| 
| HTML    | [https://developer.mozilla.org/en-US/docs/Web/HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)|  
| CSS     | [https://developer.mozilla.org/en-US/docs/Web/CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)      |   
| Git | [https://git-scm.com/](https://git-scm.com/)     |    
| Font| [https://fontawesome.com/](https://fontawesome.com/)|
| Boostrap| [https://getbootstrap.com/](https://getbootstrap.com/)|

## **Prerequisites**

**Install or open the internet browser of your choice.**

*  **Examples Below:**

- Google Chrome
- Safari
- OPera
- Mozilla Firefox
- Internet Explorer

### **Installing**

**Click the link below:** 

[Link to Website]()

## **Built With**

* [HTML Dev](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [HTML W3](https://www.w3schools.com/html/default.asp)   
* [CSS Dev](https://developer.mozilla.org/en-US/docs/Web/CSS)
* [CSS W3](https://www.w3schools.com/css/default.asp)

## **Visual**

![Site Langing Page]()

## **Author**

* **Kenneth Cruz** 


- [Link to Portfolio Site](#)
- [Link to Github](https://github.com/cruzkenneth504)
- [Link to LinkedIn](linkedin.com/in/cruzkenneth504)

       
## **License**

This project is licensed under the MIT License

## **Acknowledgments**

* [UCB BootCamp](https://bootcamp.berkeley.edu/)
* [DevTools](https://dev.to/)
* [Youtube](https://www.youtube.com/)
* [CssGradient](https://cssgradient.io/)
* [CssTricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

## **Test**

![Site test]()