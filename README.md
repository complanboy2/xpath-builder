## PEGA XPath Builder

Install from [chrome webstore](https://chrome.google.com/webstore/detail/pega-xpath-builder/egkbiiglhcgopbejlhmekoopkjcgbgoj).


### View here


[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/0KbavKOiS_k/0.jpg)](https://www.youtube.com/watch?v=0KbavKOiS_k)

<a href="http://www.youtube.com/watch?feature=player_embedded&v=0KbavKOiS_k" target="_blank"><img src="http://img.youtube.com/vi/0KbavKOiS_k/0.jpg" alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

### INTRODUCTION
 
Being a PEGA developer, If I had to do any automation of my PEGA application then it has to be through UI only. Irrespective of the framework used for automation (RSpec or another Selenium based framework), most of the effort is being spent on identifying the UI elements uniquely. XPath is generally used for identifying these UI elements.
 
Identifying unique and reliable XPath and maintaining it is a manual and time taking task. Most of the time it is NOT straightforward, and we end up writing relative XPath(s). And, also these manual activities are prone to error and there is no standard way of building the XPaths.
 
Hence, I've developed this automated XPath builder. This will generate unique and reliable XPaths which are easy to build and maintain for all PEGA applications.

## MARKET RESEARCH
 
We evaluated Firebug/Chrome-Dev-Tools XPath finder, but they won’t provide us reliable XPaths and need maintenance for even minor UI changes. Their XPath generation completely depends on the number of number elements count. Thus the generated XPaths are of no use for enterprise applications.

PEGA applications support generation of data-test-id's and many other special attrubites to help in element identification. This XPath-Builder tool leverages these special attributes for building the XPaths automatically.
 
## WHY DO WE THINK THIS IS A BIG/TRANSFORMATIONAL IDEA ?
 
Usually (from PEGA application development perspective), we use both JUnits and RSpecs for test automation and around 30% of them are RSpecs (UI automation).  In daily test execution results, we have one or other RSpec failures and these turns out to be XPath issues in most of the case. This could be due to our recent changes or some other team’s changes.
  
Every time engineers spend considerable amount of time in framing/building new XPaths for the failing elements. Same is the case with writing new RSPecs too. Majority of the time spent in writing RSpecs is for identifying XPaths of all the new elements. Replacing this effort with a tool will reduce the manual effort drastically and also provides a reliable and standardized solution.
 
This is the case of our team, where majority of automation is done through JUnits. But framework teams or external customers, rely on UI automation predominantly (using Selenium or similar tools). Our tool will save time and manual resources considerably in developing tests and also such tests demand lesser maintenance.

## HOW TO USE
 
1. Navigate here using Chrome browser and click on “ADD TO CHROME”. A pop will appear and click on “Add Extension”. This will install this “Pega XPath Builder” chrome extension.
 
2. Login to Or Refresh any Pega Built Website (PRPC or PMF or PDN). Right click on webpage and click inspect.
 
3. From inspect window, you can click on Elements and on right side, you will find a new tab called (PEGA XPath Builder). If you window size is not big enough, you might need to click on >> symbol and find the tab.
 
4. Now, inspect any element like we do for finding XPaths manually and the corresponding xpath will be seen in the text shown on right side (Inside the PEGA XPath Builder tab).
 
5. You can copy the XPath of the selected element by clicking the “COPY TO CLIPBOARD” button.

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

### Support or Contact

Having trouble with install or usage? Please write to us, [contact support](mailto:complanboy2@gmail.com) and we’ll help you sort it out.
