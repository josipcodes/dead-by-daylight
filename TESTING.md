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

| Browser | Screenshot | Notes |
| --- | --- | --- |
| Chrome | ![screenshot](documentation/compatibility/testing-chrome.png) | Works as expected |
| Firefox | ![screenshot](documentation/compatibility/testing-mozilla.png) | Works as expected |
| Edge | ![screenshot](documentation/compatibility/testing-edge.png) | Works as expected |
| Brave | ![screenshot](documentation/compatibility/testing-brave.png) | Works as expected |
| Safari | ![screenshot](documentation/compatibility/testing-safari.png) | Works as expected |
| Opera | ![screenshot](documentation/compatibility/testing-opera.png) | Works as expected |

## Responsiveness

⚠️⚠️⚠️⚠️⚠️ START OF NOTES (to be deleted) ⚠️⚠️⚠️⚠️⚠️

Use this space to discuss testing the live/deployed site on various device sizes.

The minimum requirement is for the following 3 tests:
- Mobile
- Tablet
- Desktop

**IMPORTANT**: You must provide screenshots of the tested responsiveness, to "prove" that you've actually tested them.

Using the "amiresponsive" mockup image (or similar) does not suffice the requirements.
Consider using some of the built-in device sizes in the Developer Tools.

If you have tested the project on your actual mobile phone or tablet, consider also including screenshots of these as well.
It showcases a higher level of manual tests, and can be seen as a positive inclusion!

Sample responsiveness testing documentation:

🛑🛑🛑🛑🛑 END OF NOTES (to be deleted) 🛑🛑🛑🛑🛑

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
| Home | Mobile | ![screenshot](documentation/lighthouse-home-mobile.png) | Some minor warnings |
| Home | Desktop | ![screenshot](documentation/lighthouse-home-desktop.png) | Few warnings |
| About | Mobile | ![screenshot](documentation/lighthouse-about-mobile.png) | Some minor warnings |
| About | Desktop | ![screenshot](documentation/lighthouse-about-desktop.png) | Few warnings |
| Gallery | Mobile | ![screenshot](documentation/lighthouse-gallery-mobile.png) | Slow response time due to large images |
| Gallery | Desktop | ![screenshot](documentation/lighthouse-gallery-desktop.png) | Slow response time due to large images |
| x | x | x | repeat for any other tested pages/sizes |

## Bugs

⚠️⚠️⚠️⚠️⚠️ START OF NOTES (to be deleted) ⚠️⚠️⚠️⚠️⚠️

It's very important to document any bugs you've discovered while developing the project.
Make sure to include any necessary steps you've implemented to fix the bug(s) as well.

For JavaScript and Python applications, it's best to screenshot the errors to include them as well.

**PRO TIP**: screenshots of bugs are extremely helpful, and go a long way!

🛑🛑🛑🛑🛑 END OF NOTES (to be deleted) 🛑🛑🛑🛑🛑

- JS Uncaught ReferenceError: `foobar` is undefined/not defined

    ![screenshot](documentation/bug01.png)

    - To fix this, I _____________________.

- JS `'let'` or `'const'` or `'template literal syntax'` or `'arrow function syntax (=>)'` is available in ES6 (use `'esversion: 11'`) or Mozilla JS extensions (use moz).

    ![screenshot](documentation/bug02.png)

    - To fix this, I _____________________.

- Python `'ModuleNotFoundError'` when trying to import module from imported package

    ![screenshot](documentation/bug03.png)

    - To fix this, I _____________________.

- Django `TemplateDoesNotExist` at /appname/path appname/template_name.html

    ![screenshot](documentation/bug04.png)

    - To fix this, I _____________________.

- Python `E501 line too long` (93 > 79 characters)

    ![screenshot](documentation/bug04.png)

    - To fix this, I _____________________.

### GitHub **Issues**

⚠️⚠️⚠️⚠️⚠️ START OF NOTES (to be deleted) ⚠️⚠️⚠️⚠️⚠️

An improved way to manage bugs is to use the built-in **Issues** tracker on your GitHub repository.
To access your Issues, click on the "Issues" tab at the top of your repository.
Alternatively, use this link: https://github.com/josipcodes/dead-by-daylight/issues

If using the Issues tracker for your bug management, you can simplify the documentation process.
Issues allow you to directly paste screenshots into the issue without having to first save the screenshot locally,
then uploading into your project.

You can add labels to your issues (`bug`), assign yourself as the owner, and add comments/updates as you progress with fixing the issue(s).

Once you've sorted the issue, you should then "Close" it.

When showcasing your bug tracking for assessment, you can use the following format:

🛑🛑🛑🛑🛑 END OF NOTES (to be deleted) 🛑🛑🛑🛑🛑

**Fixed Bugs**

All previously closed/fixed bugs can be tracked [here](https://github.com/josipcodes/dead-by-daylight/issues?q=is%3Aissue+is%3Aclosed).

| Bug | Status |
| --- | --- |
| [JS Uncaught ReferenceError: `foobar` is undefined/not defined](https://github.com/josipcodes/dead-by-daylight/issues/1) | Closed |
| [Python `'ModuleNotFoundError'` when trying to import module from imported package](https://github.com/josipcodes/dead-by-daylight/issues/2) | Closed |
| [Django `TemplateDoesNotExist` at /appname/path appname/template_name.html](https://github.com/josipcodes/dead-by-daylight/issues/3) | Closed |

**Open Issues**

Any remaining open issues can be tracked [here](https://github.com/josipcodes/dead-by-daylight/issues).

| Bug | Status |
| --- | --- |
| [JS `'let'` or `'const'` or `'template literal syntax'` or `'arrow function syntax (=>)'` is available in ES6 (use `'esversion: 11'`) or Mozilla JS extensions (use moz).](https://github.com/josipcodes/dead-by-daylight/issues/4) | Open |
| [Python `E501 line too long` (93 > 79 characters)](https://github.com/josipcodes/dead-by-daylight/issues/5) | Open |

## Unfixed Bugs

⚠️⚠️⚠️⚠️⚠️ START OF NOTES (to be deleted) ⚠️⚠️⚠️⚠️⚠️

You will need to mention unfixed bugs and why they were not fixed.
This section should include shortcomings of the frameworks or technologies used.
Although time can be a big variable to consider, paucity of time and difficulty understanding
implementation is not a valid reason to leave bugs unfixed.

If you've identified any unfixed bugs, no matter how small, be sure to list them here.
It's better to be honest and list them, because if it's not documented and an assessor finds the issue,
they need to know whether or not you're aware of them as well, and why you've not corrected/fixed them.

Some examples:

🛑🛑🛑🛑🛑 END OF NOTES (to be deleted) 🛑🛑🛑🛑🛑

- On devices smaller than 375px, the page starts to have `overflow-x` scrolling.

    ![screenshot](documentation/unfixed-bug01.png)

    - Attempted fix: I tried to add additional media queries to handle this, but things started becoming too small to read.

- For PP3, when using a helper `clear()` function, any text above the height of the terminal does not clear, and remains when you scroll up.

    ![screenshot](documentation/unfixed-bug02.png)

    - Attempted fix: I tried to adjust the terminal size, but it only resizes the actual terminal, not the allowable area for text.

- When validating HTML with a semantic `section` element, the validator warns about lacking a header `h2-h6`. This is acceptable.

    ![screenshot](documentation/unfixed-bug03.png)

    - Attempted fix: this is a known warning and acceptable, and my section doesn't require a header since it's dynamically added via JS.

⚠️⚠️⚠️⚠️⚠️ START OF NOTES (to be deleted) ⚠️⚠️⚠️⚠️⚠️

If you legitimately cannot find any unfixed bugs or warnings, then use the following sentence:

🛑🛑🛑🛑🛑 END OF NOTES (to be deleted) 🛑🛑🛑🛑🛑

There are no remaining bugs that I am aware of.
