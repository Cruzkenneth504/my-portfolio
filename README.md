# **My Porfolio**

## **Description**

* This project aimed to learn how to create an accessible website using HTML, and CSS and to practice git commands. The motive of this project was to help me produce a starting code 

### **Code Refactor**

### HTML

- **Before**

```html

    <ul>
      <li>
        <a href="#search-engine-optimization">Search Engine Optimization</a>
            </li>
              <li>
                 <a href="#online-reputation-management">Online Reputation Management</a>
              </li>
            <li>
        <a href="#social-media-marketing">Social Media Marketing</a>
        </li>
    </ul>

```
- **After**

  * Added semantic 'nav' layout to improve code reading [<nav></nav>semantic element](https://www.w3schools.com/html/html5_semantic_elements.asp). 

```html

 <nav>
    <ul>
      <li>
        <a href="#search-engine-optimization">Search Engine Optimization</a>
            </li>
              <li>
                 <a href="#online-reputation-management">Online Reputation Management</a>
              </li>
            <li>
        <a href="#social-media-marketing">Social Media Marketing</a>
        </li>
    </ul>
   </nav>

```

### CSS

- **Before**

```css

.header .container {
    padding-top: 15px;
    margin-right: 20px;
    float: right;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    font-size: 20px;
}

```
- **After**

  * Removed class element '.header' and replaced it with element selector 'header'.  [Css element selector](https://www.w3schools.com/html/html5_semantic_elements.asp).

```css
header .container {
    padding-top: 15px;
    margin-right: 20px;
    float: right;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    font-size: 20px;
}
```

## **Technology Used**

| Technology Used         | Resource URL           | 
| ------------- |:-------------:| 
| HTML    | [https://developer.mozilla.org/en-US/docs/Web/HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)|  
| CSS     | [https://developer.mozilla.org/en-US/docs/Web/CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)      |   
| Git | [https://git-scm.com/](https://git-scm.com/)     |    



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

[Link to Website](https://cruzkenneth504.github.io/marketing-promo/)

## **Built With**

* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [HTML](https://www.w3schools.com/html/default.asp)   
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
* [CSS](https://www.w3schools.com/css/default.asp)

## **Visual**

![Site Langing Page](./assets/images/site.gif)

## **Authors**

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

## **Test**

![Site test](./assets/images/test.gif)