
|AAC #   | Checklist items   |How to check   |
|---|---|---|
| AAC1  | Can navigation to all interactive content occur when using the keyboard?  | Use Tab and Shift + Tab to navigate through links, buttons and form controls and press Enter to check for activation  |
|AAC1   |Can complex components be navigated using the arrow keys? e.g. expanding combo boxes, navigating Tabs   | Use arrow keys and spacebar to navigate through buttons and form controls  |
| AAC2  | Can a popup be opened and closed solely from the keyboard?  | 1. Use <kbd>Tab</kbd> and <kbd>Shift</kbd> + Tab to navigate to open and close popup<br>1. Use Enter or Escape to close the popup   |
|AAC2   |Can tooltips and hover content be triggered from the keyboard?   | Use <kbd>Tab</kbd> and <kbd>Shift</kbd> + Tab to navigate to open hover content  |
|AAC3   | Is the page title and "Coles" in the tab bar in some format?  | Look at the browser tab to see the title text in use  |
| AAC4  |When the Tab key is pressed is the keyboard focus clearly identified on all focusable elements?   | Use Tab and Shift + Tab to navigate through links, buttons and form controls  |
| AAC5  | Are `<ol>`,`<ul>` elements used for related collections of information such as links, or product items?  | Right click and select Inspect Select the 1st item in a related collection and inspect the HTML, check for `<ol>` or `<ul>` elements  |
|AAC5   |Do prominent visual headings use heading elements such as `<h1>`, `<h2>` etc?   | Right click and select Inspect Select a prominent visual heading and inspect the HTML, check for `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>` Check the headings are applied in sequence   |
|AAC6   |Does the screenreader announce each form controls label?   |Open NVDA Use Tab and Shift + Tab to navigate through form controls Check the form control label is announced by NVDA when focused on the form control   |
|AAC6   |Does the screenreader announce a data format (if required)?   | Open NVDA Use <kbd>Tab</kbd> and <kbd>Shift</kbd> + <kbd>Tab</kbd> to navigate through form controls Check the form control label data format (if one exists) is announced by NVDA when focused on the form control  |
|AAC7   | Whenever something significant has changed on the page is it announced by the screen reader? e.g. search results displaying while searching, errors displaying after activating submit button.  | Open NVDA Use Tab and Shift + Tab to navigate through page controls Trigger a significant change Check the change is announced by NVDA   |
|AAC8   | Is the core page content still viewable and navigable at 400% browser zoom?  | Using Chrome, change the browser zoom to 400%  |
|AAC9   | Do all descriptive `<img>` screenreader announcements have an ALT text description?  | Right click and select Inspect Select an image (`<img>`) element and inspect the HTML, check an ALT attribute exists with sufficient text   |
|AAC9   | Do all descriptive `<svg>` screenreader announcements have an aria-label description?  | Right click and select Inspect Select an image (`<svg>`) element and inspect the HTML, check an aria-label attribute exists with sufficient text  |
|AAC10   | Is the core page content still viewable and navigable in portrait and landscape orientation?  |Right click and select Inspect Select Toggle device toolbar Select Rotate   |
