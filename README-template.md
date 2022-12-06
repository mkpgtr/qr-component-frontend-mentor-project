# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot




**Note:THe screenshots are not showing directly on Github. To view them, please download them from : https://github.com/mkpgtr/qr-component-frontend-mentor-project/tree/main/screenshots**


### Links

- Solution URL: (https://github.com/mkpgtr/qr-component-frontend-mentor-project)
- Live Site URL: (https://fm-qr-component-by-manish-panda.netlify.app/)

## My process

### Built with

- HTML5 
- CSS
- Flexbox
- 
- Mobile-first design



### What I learned

1) I learnt to center a div horizontally using ```css 
<style>

  div { 
    margin: 0 auto;
  }
  </style>
  ```

2) I learnt to use flexbox in its very basic form and used it for centering a div using 



.parent{
  display:flex;
  align-items:center;
  justify-content:center;
}

</style>

3) I used max-width property on the paragraph element inside the .qr-component-text div and centered it with text-align:justify

``` <style>
  .qr-component-text{
    text-align:justify;
    max-width:85%;
  }
 </style> ```


4) I selected nested elements like this : ``` 
.qr-component-text p{ 
  // some-css
} ``` 

to select the p tag inside the div with class of .qr-component
```

5) Used a figma design file for the first time and maybe that's why my visual styling might not be very accurate.



```



### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

I want to understand how to make use of the information provided in the starter files about mobile and desktop versions. My design is not as accurate as it's meant to be and not understanding how to use the mobile : 375px and Desktop 1440px might be a reason for that.

I used max-width:375px and min-width:375 just to make my css work on these two break-points.

I needed this project to get started with front-end mentor so I guess I did not use the text-shadow property. I was impatient and did not have the calm to understand text-shadow and all the offset values.






## Author

-Github : www.github.com/mkpgtr


## Acknowledgments

I coded this whole thing all by myself as I have been watching tutorials and doing simple css stuff. This was just a nice exposure to how frontend mentor works after I purchased the PRO subscription. However, I got to realize that I need to learn markdown and version control stuff better to really harness the power of online community and really have fun with writing code.
 
