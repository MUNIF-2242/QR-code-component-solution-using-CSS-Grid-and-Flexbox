# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Solution URL](https://github.com/MUNIF-2242/QR-code-component-solution-using-CSS-Grid-and-Flexbox.git)
- Live Site URL: [Live site URL](https://qr-code-solution-css-grid.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<main class="container" role="main">
  <div class="card">
    <img src="images/image-qr-code.png" alt="qr-code">
    <h1>Improve your front-end skills by building projects</h1>
    <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level.</p>
  </div>
</main>
```

```css
@import url('https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap');

body {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-family: 'Outfit', sans-serif;
  display: grid;
  min-height: 100vh;
  /* grid-template-columns: 1fr 14fr 1fr;
   grid-template-rows: 1fr 8fr 1fr;*/
}
.container{
  background: hsl(212, 45%, 89%);
  /*  grid-column-start: 2;
    grid-row-start: 2;*/
  display: grid;
  justify-content: center;
  align-items: center;
}
.card{
  display: flex;
  flex-direction: column;
  background: hsl(0, 0%, 100%);
  width: 300px;
  padding: 20px;
  border-radius: 15px;
}
.card > img:nth-child(1) {
  border-radius: 15px;
}
.card > h1:nth-child(2) {
  margin: 40px 20px 20px 20px;
  text-align: center;
  font-size: 1.4rem;
  font-weight: 700;
  color: hsl(218, 44%, 22%);
}
.card > p:nth-child(3) {
  margin: 0 20px 20px 20px;
  text-align: center;
  font-size: 1rem;
  font-weight: 400;
  color: hsl(220, 15%, 55%);
}


```
```js
const proudOfThisFunc = () => {
  console.log('🎉')
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [px/em/rem](https://www.joshwcomeau.com/css/surprising-truth-about-pixels-and-accessibility/) - This post is all about px/em/rem.


**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author
- MD MUNIF HASAN
- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
