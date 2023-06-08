# results-summary-component-main

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](/design/desktop-design.jpg)

### Links

- Solution URL: [solution URL](https://karimabdelghanyhefnawy1.github.io/results-summary-component-main/)
- Live Site URL: [live site URL](https://www.frontendmentor.io/solutions/project2-BFqzSnERKD)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

```html
  <body>
    <div class="hero">
      <div class="card">
        <div class="info">
          <h1>Your Result</h1>
          <div class="circal">
            <p class="result">76</p>
            <p class="paragraph">of 100</p>
          </div>
          <div class="contant">
            <h2>Great</h2>
            <p class="paragraph">
              You scored higher than 65% of the people who have taken these
              tests
            </p>
          </div>
        </div>
        <div class="father">
          <h3>Summary</h3>
          <div class="reaction">
            <div class="flex">
              <img class="flash" src="images/icon-reaction.svg" alt="flash">
              <p>Reaction</p>
            </div>
            <span>80/100</span>
          </div>
          <div class="memory">
            <div class="flex">
              <img class="brain"  src="images/icon-memory.svg" alt="brain">
              <p>Memory</p>
            </div>
            <span>92/100</span>
          </div>
          <div class="verbal">
            <div class="flex">
              <img class="comment" src="images/icon-verbal.svg" alt="comment">
              <p>Verbal</p>
            </div>
            <span>61/100</span>
          </div>
          <div class="visual">
            <div class="flex">
              <img class="eye" src="images/icon-visual.svg"alt="eye">
              <p>Visual</p>
            </div>
            <span>80/100</span>
          </div>
          <button type="button">Continue</button>
        </div>
        </div>
      </div>
    </div>
  </body>
```
```css
.hero{
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 1rem;
}
.card{
    width: 50vw;
    border-radius: 1rem;
    background-color: var(--maincolor);
    box-shadow: 0 0 1rem 0 hsl(0, 0%, 84%) ;
    display: flex;
    flex-direction: row;
}
```
### Continued development

### seful resources

## Author
[KarimAbdelghanyHefnawy1] (https://github.com/karimabdelghanyhefnawy1?tab=following)
 
