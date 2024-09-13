# Testing
> [!NOTE]  
> Return back to the [README.md](README.md) file.

Through our comprehensive testing process, we have meticulously examined the functionality, performance, and usability of **GluteniPedia**. We are confident that the website operates reliably and efficiently across different platforms, devices, and browsers. Our testing approach has addressed key aspects of the user experience, ensuring that the site works well under normal conditions and can handle various user scenarios without compromising stability.

This rigorous process allows us to legitimately believe that **GluteniPedia** is well-tested, reliable, and ready to meet the needs of its users.

## Code Validation
### HTML
I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.

| Directory | File | Screenshot | Notes |
| --- | --- | --- | --- |
|  | 404.html | ![screenshot](documentation/validation/404-validate.png) | |
|  | about.html | ![screenshot](documentation/validation/about-validate.png) | |
|  | celebrities.html | ![screenshot](documentation/validation/celebrities-validate.png) | |
|  | diagnose.html | ![screenshot](documentation/validation/diagnose-validate.png) | |
|  | index.html | ![screenshot](documentation/validation/index-validate.png) | |
|  | privacy-policy.html | ![screenshot](documentation/validation/privacy-policy-validate.png) | |
|  | recipe.html | ![screenshot](documentation/validation/recipe-validate.png) | |
|  | recipes.html | ![screenshot](documentation/validation/recipes-validate.png) | |
|  | subscribe.html | ![screenshot](documentation/validation/subscribe-validate.png) | |
|  | subscription-confirmation.html | ![screenshot](documentation/validation/confirmation-validate.png) | |

### CSS
I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.

| Directory | File | Screenshot | Notes |
| --- | --- | --- | --- |
| assets | style.css | ![screenshot](documentation/validation/css-validate.png) | |

## Browser Compatibility
I've tested my deployed project on multiple browsers to check for compatibility issues.

| Browser | Home | Recipes | Celebrities | Subscribe | Notes |
| --- | --- | --- | --- | --- | --- |
| Chrome | ![screenshot](documentation/browsers/chrome.home.png) | ![screenshot](documentation/browsers/chrome-recipes.png) | ![screenshot](documentation/browsers/chrome-celebrities.png) | ![screenshot](documentation/browsers/chrome-subscribe.png) | Works as expected |
| Firefox | ![screenshot](documentation/browsers/firefox-home.png) | ![screenshot](documentation/browsers/firefox-recipes.png) | ![screenshot](documentation/browsers/firefox-celebrities.png) | ![screenshot](documentation/browsers/firefox-subscribe.png) | Works as expected |
| Safari | ![screenshot](documentation/browsers/safari-home.png) | ![screenshot](documentation/browsers/safari-recipes.png) | ![screenshot](documentation/browsers/safari-celebrities.png) | ![screenshot](documentation/browsers/safari-subscribe.png) | Works as expected |

## Responsiveness
I've tested my deployed project on multiple devices to check for responsiveness issues.

| Device | Home | Recipes | Celebrities | Subscribe | Notes |
| --- | --- | --- | --- | --- | --- |
| Mobile (DevTools) | ![screenshot](documentation/responsiveness/mobile-home.png) | ![screenshot](documentation/responsiveness/mobile-recipes.png) | ![screenshot](documentation/responsiveness/mobile-celebrities.png) | ![screenshot](documentation/responsiveness/mobile-subscribe.png) | Works as expected |
| iPad (DevTools) | ![screenshot](documentation/responsiveness/ipad-home.png) | ![screenshot](documentation/responsiveness/ipad-recipes.png) | ![screenshot](documentation/responsiveness/ipad-celebrities.png) | ![screenshot](documentation/responsiveness/ipad-subscribe.png) | Works as expected |
| Desktop | ![screenshot](documentation/responsiveness/desktop-home.png) | ![screenshot](documentation/responsiveness/desktop-recipes.png) | ![screenshot](documentation/responsiveness/desktop-celebrities.png) | ![screenshot](documentation/responsiveness/desktop-subscribe.png) | Works as expected |
| XL Monitor | ![screenshot](documentation/responsiveness/xl-home.png) | ![screenshot](documentation/responsiveness/xl-recipes.png) | ![screenshot](documentation/responsiveness/xl-celebrities.png) | ![screenshot](documentation/responsiveness/xl-subscribe.png) | Works as expected |
| 4K Monitor | ![screenshot](documentation/responsiveness/4k-home.png) | ![screenshot](documentation/responsiveness/4k-recipes.png) | ![screenshot](documentation/responsiveness/4k-celebrities.png) | ![screenshot](documentation/responsiveness/4k-subscribe.png) | Noticable scaling issues |
| Google Pixel 7 Pro | ![screenshot](documentation/responsiveness/pixel7-home.png) | ![screenshot](documentation/responsiveness/pixel7-recipes.png) | ![screenshot](documentation/responsiveness/pixel7-celebrities.png) | ![screenshot](documentation/responsiveness/pixel7-subscribe.png) | Works as expected |
| iPhone 14 Pro Max | ![screenshot](documentation/responsiveness/iphone14pm-home.png) | ![screenshot](documentation/responsiveness/iphone14pm-recipes.png) | ![screenshot](documentation/responsiveness/iphone14pm-celebrities.png) | ![screenshot](documentation/responsiveness/iphone14pm-subscribe.png) | Works as expected |

## Lighthouse Audit
I've tested my deployed project using the Lighthouse Audit tool to check for any major issues.

| Page | Mobile | Desktop | Notes |
| --- | --- | --- | --- |
| Home | ![screenshot](documentation/lighthouse/lighthouse-home-mobile.png) | ![screenshot](documentation/lighthouse/lighthouse-home-desktop.png) | Slow response time due to large images |
| Recipes | ![screenshot](documentation/lighthouse/lighthouse-recipes-mobile.png) | ![screenshot](documentation/lighthouse/lighthouse-recipes-desktop.png) | Slow response time due to large images |
| Celebrities | ![screenshot](documentation/lighthouse/lighthouse-celebrities-mobile.png) | ![screenshot](documentation/lighthouse/lighthouse-celebrities-desktop.png) | Slow response time due to large images |
| Subscribe | ![screenshot](documentation/lighthouse/lighthouse-subscribe-mobile.png) | ![screenshot](documentation/lighthouse/lighthouse-subscribe-desktop.png) | Some minor warnings |

## Bugs
- JS Uncaught ReferenceError: `foobar` is undefined/not defined

    ![screenshot](documentation/bugs/bug01.png)

    - To fix this, I _____________________.

## Unfixed Bugs

- On devices smaller than 375px, the page starts to have `overflow-x` scrolling.

    ![screenshot](documentation/bugs/unfixed-bug01.png)

    - Attempted fix: I tried to add additional media queries to handle this, but things started becoming too small to read.

> [!NOTE]  
> There are no remaining bugs that I am aware of.
