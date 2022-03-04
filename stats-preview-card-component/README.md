# Frontend Mentor - Stats Preview Card Component

## Welcome! 👋
This is a solution to the Stats Preview Card Component challenge on Frontend Mentor

### Links

- Solution URL: [Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ/hub/profile-card-component-DlKuYRaH5)
- Github Pages: [Stats Preview Card Component ](https://kanyshaiosmonova.github.io/Frontend-Mentor-Challenges/stats-preview-card-component/index.html)


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- SVG Images, icons

### What I learned

```css
@media (min-width: 768px) {
    .container {
      display: flex;
      flex-direction: row-reverse;
      align-items: center;
      justify-content: center;
      padding: 0;
      text-align: left;
    }
  
    .container .picture {
      background: url("./images/image-header-desktop.jpg") no-repeat center/cover;
      min-width: 50%;
      border-radius: 0 10px 10px 0;
    }
  
    .container .picture .overlay {
      background-color: hsla(277, 64%, 61%, 0.7);
      height: 400px;
      border-radius: 0 10px 10px 0;
    }
  
    .container .card ul {
      padding-left: 20px;
      display: flex;
    }
    .container .card ul li {
      margin-right: 30px;
      font-size: 13px;
    }
  
    .container .card ul li span {
      display: block;
      text-transform: lowercase;
      font-weight: 700;
      font-family: "Lexend Deca", sans-serif;
      font-size: 24px;
      margin-bottom: 3px;
    }
  }
  
  @media (min-width: 992px) {
    body {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
    }
  
    .container .card:nth-child(2) {
      padding: 0 30px;
    }
  
    .container .card p {
      margin-bottom: 50px;
    }
  }
```

## Author

- Medium - [kanyshai_osmonova](https://medium.com/@kanyshai_osmonova)
- Frontend Mentor - [@kanyshaiosmonova](https://www.frontendmentor.io/profile/kanyshaiosmonova)
- Twitter - [@KaniOsmonova](https://twitter.com/Kaniosmonova)


## The challenge

I tried to build out this stats preview  card component and get it looking as close to the design as possible.

## Got feedback for me?

I love receiving feedback! I'm always looking to improve my coding skills. So if you have anything you'd like to mention, please email kanyshai.osmonova.kk@gmail.com
