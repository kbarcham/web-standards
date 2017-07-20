## Tools for testing

The Web Accessibility Standard Test Suite includes some automated testing, which can test about 25% of accessibility requirements.

Automated testing is really easy, so let’s start with the manual testing.

The tools we’re using for manual testing are the:

* Chrome’s built-in developer tools — to inspect a web page’s code
* Web Developer extension for Chrome — a semi-automated testing tool
* Chrome Device Mode — to simulate viewport sizes, and 
* aXe extension for Chrome — the automated testing tool.

### Developer tools

When you need to inspect the code, use built-in developer tools.

1. As a general rule, right-click on an element in the web page.
2. Select the option to inspect to open the developer tools. 
3. The element you clicked on will be highlighted. 

[Explore Chrome’s developer tools](https://developers.google.com/web/tools/chrome-devtools/) 

[Inspect and edit pages and styles in Chrome](https://developers.google.com/web/tools/chrome-devtools/inspect-styles/)

We recommend opening the developer tools either as a separate window or at the bottom of the screen. 

 If you’re new to using developer tools, try them out before starting the tests. And be sure to attend one or more of the self-assessment clinics that will be offered and ask for a demo.

### Web Developer extension

The web developer extension for Chrome has various features to help simplify accessibility testing. We’ll use it to speed up checking headings, lists and image alt text. But it’s well worth looking at the other things it has to offer.

#### Get the extension

[Download the Chrome extension](https://chrome.google.com/webstore/detail/web-developer/bfbameneiokkgbdmiekhjnmfkcnldhhm).

#### Use the extension

Once you’ve installed the extension, you can access it using the cog icon on the toolbar to the right of the address bar (shown below).

![Screenshot showing Web Developer Extension in Chrome](img/chrome-wd-ext.jpg)

##### What you need to know

* The highlighted area at the top is the menu. The Outline menu is shown.
* Any selected item will have a green tick next to it.
* To get rid of the pop up menu, just click in the page.

### Test with multiple viewport sizes

Accessibility issues that only appear on smaller screens will get picked up this way. As well as testing your pages at your browser’s normal desktop size, you also need to test at the following widths: 

* 320px - the size of a small screen mobile phone like an iPhone 5 in portrait mode
* 768px - roughly the size of a tablet like an iPad in portrait mode.

To simulate a mobile or tablet experience on a desktop computer, you can resize your browser to approximately the size of a tablet or a smartphone. You can also use some browsers’ built-in tools, like Chrome’s Device Mode, to help with this. 

#### [Using Chrome’s Device Mode]

[Using Chrome's Device Mode to simulate mobile devices](https://developers.google.com/web/tools/chrome-devtools/device-mode/)

To use the Device Mode in Chrome:

1. Open the developer tools.
2. Device Mode is the second button on the left-hand side of the toolbar at the top.![Screenshot showing device mode button in Chrome](img/device-mode.jpg)

3. The browser will switch into Device Mode and the web page screen size will change. 

4. Choose the viewport size you need by:

    1. Clicking on dropdown on the toolbar above the smaller web page.

    2. Choose the device size you need.

![Screenshot showing responsive menu changing to iPad device in Chrome](img/responsive-menu.jpg)