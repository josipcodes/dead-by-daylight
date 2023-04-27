# Testing

Return back to the [README.md](README.md) file.

## Code Validation

### HTML

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.

#### Initial state

| Page | Screenshot | Notes |
| --- | --- | --- |
| Home | ![screenshot](documentation/validation/index-validation-1.png) | Section lacks header h2-h6 warning |
| Characters | ![screenshot](documentation/validation/characters-validation-1.png) | Section lacks header h2-h6 warning |
| Glossary | ![screenshot](documentation/validation/glossary-validation-1.png) | Section lacks header h2-h6 warning |
| Streaming | ![screenshot](documentation/validation/streaming-validation-1.png) | Section lacks header h2-h6 warning |
| Subscribe | ![screenshot](documentation/validation/subscribe-validation-1.png) | Section lacks header h2-h6 warning |
| Subscribed | ![screenshot](documentation/validation/subscribed-validation-1.png) | Section lacks header h2-h6 warning |

#### Troubleshooting 

| Page | Screenshot | Notes |
| --- | --- | --- |
| Home | ![screenshot](documentation/validation/index-validation-2.png) | Empty heading |

#### Final State 

| Page | W3C URL | Screenshot | Notes |
| --- | --- | --- | --- |
| Home | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjosipcodes.github.io%2Fdead-by-daylight%2Findex.html) | ![screenshot](documentation/validation/index-validation-3.png) | Pass: No Errors |
| Characters | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjosipcodes.github.io%2Fdead-by-daylight%2Fcharacters.html) | ![screenshot](documentation/validation/characters-validation-2.png) | Pass: No Errors |
| Glossary | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjosipcodes.github.io%2Fdead-by-daylight%2Fglossary.html) | ![screenshot](documentation/validation/glossary-validation-2.png) | Pass: No Errors |
| Streaming | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjosipcodes.github.io%2Fdead-by-daylight%2Fstreaming.html) | ![screenshot](documentation/validation/streaming-validation-2.png) | Pass: No Errors |
| Subscribe | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjosipcodes.github.io%2Fdead-by-daylight%2Fsubscribe.html) | ![screenshot](documentation/validation/subscribe-validation-2.png) | Pass: No Errors |
| Subscribed | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjosipcodes.github.io%2Fdead-by-daylight%2Fsubscribed.html) | ![screenshot](documentation/validation/subscribed-validation-2.png) | Pass: No Errors |

### CSS

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate my CSS file.

| File | Jigsaw URL | Screenshot | Notes |
| --- | --- | --- | --- |
| style.css | [Jigsaw](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fjosipcodes.github.io%2Fdead-by-daylight) | ![screenshot](documentation/validation/css-validation.png) | Pass: No Errors |

## Browser Compatibility

I've tested my deployed project on multiple browsers to check for compatibility issues.

| Browser | Index | Characters | Glossary | Streaming | Subscribe | Subscribed | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Chrome | ![screenshot](documentation/compatibility/chrome-index.png) | ![screenshot](documentation/compatibility/chrome-characters.png) | ![screenshot](documentation/compatibility/chrome-glossary.png) | ![screenshot](documentation/compatibility/chrome-streaming.png) | ![screenshot](documentation/compatibility/chrome-subscribe.png) | ![screenshot](documentation/compatibility/chrome-subscribed.png) | Works as expected |
| Firefox | ![screenshot](documentation/compatibility/firefox-index.png) | ![screenshot](documentation/compatibility/firefox-characters.png) | ![screenshot](documentation/compatibility/firefox-glossary.png) | ![screenshot](documentation/compatibility/firefox-streaming.png) | ![screenshot](documentation/compatibility/firefox-subscribe.png) | ![screenshot](documentation/compatibility/firefox-subscribed.png) | Works as expected |
| Edge | ![screenshot](documentation/compatibility/edge-index.png) | ![screenshot](documentation/compatibility/edge-characters.png) | ![screenshot](documentation/compatibility/edge-glossary.png) | ![screenshot](documentation/compatibility/edge-streaming.png) | ![screenshot](documentation/compatibility/edge-subscribe.png) | ![screenshot](documentation/compatibility/edge-subscribed.png) | Works as expected |
| Brave | ![screenshot](documentation/compatibility/brave-index.png) | ![screenshot](documentation/compatibility/brave-characters.png) | ![screenshot](documentation/compatibility/brave-glossary.png) | ![screenshot](documentation/compatibility/brave-streaming.png) | ![screenshot](documentation/compatibility/brave-subscribe.png) | ![screenshot](documentation/compatibility/brave-subscribed.png) | Works as expected |
| Opera | ![screenshot](documentation/compatibility/opera-index.png) | ![screenshot](documentation/compatibility/opera-characters.png) | ![screenshot](documentation/compatibility/opera-glossary.png) | ![screenshot](documentation/compatibility/opera-streaming.png) | ![screenshot](documentation/compatibility/opera-subscribe.png) | ![screenshot](documentation/compatibility/opera-subscribed.png) | Works as expected |

Additional test performed on Safari:

| Browser | Characters | Notes |
| --- | --- | --- |
| Safari | ![screenshot](documentation/compatibility/safari-characters.png) | Works as expected |

## Responsiveness

I've tested my deployed project on multiple devices to check for responsiveness issues.

| Device | Screenshot | Notes |
| --- | --- | --- |
| Mobile (DevTools) | ![screenshot](documentation/responsiveness/mobile.png) | Works as expected |
| Tablet (DevTools) | ![screenshot](documentation/responsiveness/tablet.png) | Works as expected |
| Desktop | ![screenshot](documentation/responsiveness/desktop.png) | Works as expected |
| iPad Air (DevTools) | ![screenshot](documentation/responsiveness/ipad-air.png) | Works as expected |
| iPhone SE (DevTools) | ![screenshot](documentation/responsiveness/iphone-se.png) | Works as expected |
| Samsung Galaxy s22 | ![screenshot](documentation/responsiveness/samsung-galaxy.png) | Works as expected |

## Lighthouse Audit

I've tested my deployed project using the Lighthouse Audit tool to check for any major issues.

| Page | Size | Screenshot | Notes |
| --- | --- | --- | --- |
| Home | Mobile | ![screenshot](documentation/lighthouse/lighthouse-mobile-home.png) | Some minor warnings |
| Home | Desktop | ![screenshot](documentation/lighthouse/lighthouse-desktop-home.png) | Some minor warnings |
| Characters | Mobile | ![screenshot](documentation/lighthouse/lighthouse-mobile-characters.png) | Some minor warnings |
| Characters | Desktop | ![screenshot](documentation/lighthouse/lighthouse-desktop-characters.png) | Some minor warnings |
| Glossary | Mobile | ![screenshot](documentation/lighthouse/lighthouse-mobile-glossary.png) | Slower response time due to large images, cache policy, render-blocking resources |
| Glossary | Desktop | ![screenshot](documentation/lighthouse/lighthouse-desktop-glossary.png) | Slower response time due to large images, cache policy, render-blocking resources |
| Streaming | Mobile | ![screenshot](documentation/lighthouse/lighthouse-mobile-streaming.png) | Slower response time due to large images, cache policy, render-blocking resources |
| Streaming | Desktop | ![screenshot](documentation/lighthouse/lighthouse-desktop-streaming.png) | Slower response time due to large images, cache policy, render-blocking resources |
| Subscribe | Mobile | ![screenshot](documentation/lighthouse/lighthouse-mobile-subscribe.png) | Slower response time due to large images |
| Subscribe | Desktop | ![screenshot](documentation/lighthouse/lighthouse-desktop-subscribe.png) | Slower response time due to large images |
| Subscribed | Mobile | ![screenshot](documentation/lighthouse/lighthouse-mobile-subscribed.png) | Auto-refresh impacting accessibility |
| Subscribed | Desktop | ![screenshot](documentation/lighthouse/lighthouse-desktop-subscribed.png) | Auto-refresh impacting accessibility |

## Bugs

- Floating footer

    ![screenshot](documentation/bugs/bug-footer.png)

    - To fix this, I needed to override user agent stylesheet.
```css
body {
    margin: 0;
}
```
- Inline button

    ![screenshot](documentation/bugs/bug-submit.png)
    ![screenshot](documentation/bugs/bug-button.png)

    - To fix this, I needed to override user agent stylesheet by setting the display to block.
```css
#submit-button {
    display: block;
}
```

**Resolved Issues**

| Bug | Status |
| --- | --- |
| When validating HTML with a semantic `section` element, the validator warns about lacking a header `h2-h6`. | Closed after adding aria-label to the `h2-h6` elements. |
| Image size slows down the page loading time. | Closed after compressing images. |
| Class `image-position` creates `overflow-x` on smaller screens. | Closed after removing horizontal padding. To note, this issue was not showing during testing and was captured by my mentor. |


**Open Issues**

| Issue | Explanation |
| --- | --- |
| Early commits often contain 50+ characters | This was left unresolved to present the learning curve. |


## Unfixed Bugs

| Bug | Reason for not resolving |
| --- | --- |
| Nav elements span over two lines on devices smaller than ~ 300px in width | Low chances of the user encountering this issue. |
| Header styling creates `overflow-x` issue on devices smalle than ~ 300px in width. | Low chances of the user encountering this issue. |

