# Frontend Mentor - 3-Column Preview Card Component solution

This is a solution to the 3-Column Preview Card Component challenge on Frontend Mentor. 
Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

### Links

- Solution URL: [Frontend Mentor](https://www.frontendmentor.io/solutions/nftpreview-card-component-with-htmlcss-C4nqBq0wy)
- Github Pages: [3-Column Preview Card Component](https://kanyshaiosmonova.github.io/Frontend-Mentor-Challenges/3-column-preview-card-component/index.html)


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- SVG Images
**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

This was very interesting for me. For mobile version we changed right and left corner of the top container and right/left of bottom container. But for laptop and desktop version we changes top left/bottom left of the top container and top/right and bottom/right of the bottom container. Amazing. So it's changes according to the screen.

```css
.top-container {
    background-color: var(--bright-orange);
    color: #fff;
    border-radius: 10px 10px 0 0;
 }
 ```
 ```css
 .bottom-container {
    background-color: var(--very-dark-cyan);
    color: #fff;
    border-radius: 0 0 10px 10px;
```
```css
@media (min-width:992px) {
    .top-container {
        border-radius: 10px 0 0 10px; 
    }
    .bottom-container {
        border-radius: 0 10px 10px 0;
    }
}
```

## Author

- Medium - [kanyshai_osmonova](https://medium.com/@kanyshai_osmonova)
- Frontend Mentor - [@kanyshaiosmonova](https://www.frontendmentor.io/profile/kanyshaiosmonova)
- Twitter - [@KaniOsmonova](https://twitter.com/Kaniosmonova)
**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Got feedback for me?

I love receiving feedback! I'm always looking to improve my coding skills. So if you have anything you'd like to mention, please email kanyshai.osmonova.kk@gmail.com
