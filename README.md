# LPU-WebSite-Automation
I tried to perform the Automation testing of Lovely Professional Univeristy Website , Using the Selenium WebDriver.

# Initialization and Setup:

ChromeDriver is initialized to start the browser.
Window Maximization and Implicit Wait settings are applied to handle browser interactions more efficiently.
Actions class is used for performing complex actions like mouse movements and clicks.

# Navigation and Interaction:

The script navigates to the specified URL: https://ums.lpu.in/lpuums/.
It performs various actions such as entering text into input fields, clicking buttons, and navigating through different sections of the webpage.
Thread.sleep(10000) is used for waiting purposes but should ideally be replaced with explicit waits.

# Element Interactions:

Finding Elements: Various methods such as findElement(By.className()), findElement(By.xpath()), and findElement(By.cssSelector()) are used to locate elements on the webpage.
Click Actions: The Actions class is used for interacting with elements that may require mouse hover or complex actions.
Condition Checks: Checks if certain elements are displayed to verify successful navigation or page load.

# Verification:

The code includes verification steps to ensure that the correct pages are displayed after navigation actions. This involves checking if specific elements are visible and displaying appropriate messages.


#Selenium WebDriver:

Selenium WebDriver is a tool for automating web applications for testing purposes, but is not limited to just that. It supports multiple browsers like Chrome, Firefox, and Edge.
It interacts with web elements by simulating user actions such as clicking, typing, and navigating.

# Locating Elements:

By ID: By.id("elementId")
By Name: By.name("elementName")
By Class Name: By.className("className")
By Tag Name: By.tagName("tagName")
By Link Text: By.linkText("linkText")
By Partial Link Text: By.partialLinkText("partialLinkText")
By XPath: By.xpath("//xpathExpression")
By CSS Selector: By.cssSelector("cssSelector")

# Waits:

# Implicit Wait: 
Applied globally and tells the WebDriver to wait for a specified amount of time before throwing a NoSuchElementException.
# Explicit Wait: '
Applied to specific elements and conditions. Used to wait for a particular condition to be met (e.g., visibility of an element).

# Actions Class:

Used to perform complex user interactions like drag and drop, hover over elements, and multiple actions in a single sequence.

# Error Handling and Debugging:

Use try-catch blocks to handle exceptions and add logging for debugging purposes.
