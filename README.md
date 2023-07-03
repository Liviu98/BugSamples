# BugSamples

Below are some Bug samples that I wrote from my experience.

---

# A customer can access information of other customers

**Priority & Severity**

_P1_ High

**Description**

When pressing the “Customer login” button, it will be noticed that the list of all clients is displayed and selecting any customer will allow the user to log in.

_Steps to reproduce:_
1. Go to https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login.
2. Enter “Customer Login”.
3. Press the “Your Name” field.
4. Scroll down to see the list of clients.
5. Press on one of the customer’s names listed.

_Expected results:_

The user should have access to view his personal accounts only.

_Actual results_

The user can view several customer name lists and access them.

https://github.com/Liviu98/BugSamples/assets/129300621/2490fb55-91e0-4111-b8c4-30721e23041c

---

# The translation of the text is not completed

**Priority & Severity**

_P2_ Medium

_Description_

When changing the language of the website, It will be noticed that not all text fields are translated.

_Steps to reproduce_

1. Go to “https://juice-shop.herokuapp.com/#/ ”.
2. Press “Choose language”.
3. Press “Bahasa Indonesia”.
   
_Expected results_

The webpage should translate all text

_Actual results_

The translation of the text is not completed.

![Bahasa Indonesia BUG](https://github.com/Liviu98/BugSamples/assets/129300621/587cb544-aaba-42b1-93bc-79424f39f590)

---

# The text in the “About us” section is not customized

**Priority & Severity**

_P2_ Medium

_Description_

The text in the “About us” section, is not customized.

_Steps to reproduce_

1. Go to “https://juice-shop.herokuapp.com/#/ ”.
2. Press the “Open side menu” button.
3. Press the “About us” button.

_Expected results_

The page should display information regarding the site (history, scop, team, etc.).

_Actual results_

There is a standard text area created “Lorem ipsum”, but the text is not customized.

![About us BUG](https://github.com/Liviu98/BugSamples/assets/129300621/5fc6b991-71f1-4d61-9d5e-10d0e6e4bd46)

---

# The picture in photo wall is not displayed.

**Priority & Severity**

_P2_ Medium

_Description_

First picture in not displayed in the picture wall.

_Steps to reproduce_

1. Go to “https://juice-shop.herokuapp.com/#/ ”.
2. Press the “Open side menu” button.
3. Press the “Picture wall” button.

_Expected results_

The page should display all pictures.

_Actual results_

First picture is not diplayed.

![Bug poze](https://github.com/Liviu98/BugSamples/assets/129300621/43555386-5d41-4b45-b5a6-3ad689f216d3)

---

# The loading time of the web page is too long due to loading files multiple times

**Priority & Severity** 
_P3_ Low

_Description_

When trying to enter the web application, it will be noticed that it take a long time for the page to load

_Steps to reproduce_

1. Go to https://fieni.ro/.
2. Press F12.
3. Select Network.
4. Make sure that the ticks on the “Preserved log”, “Disable cache” and “All” are selected.
5. Press F5.
6. Filter by size.

_Expected results_

The recommended loading time for web pages is ~3 seconds.

_Actual result_

The loading time of the web page is too long due to loading files multiple times.

![Fieni Load test bug](https://github.com/Liviu98/BugSamples/assets/129300621/360cbc08-88c7-4150-9afc-508d84f1f09d)

# There are incorrectly framed text while using devices

**Priority & Severity**

_P1_ High

_Description_

When trying to enter the website, on different devices, it will be noticed that the padding is not adjusted properly for all the text.

_Steps to reproduce_

1. Go to https://comunavorona.ro/.
2. Press F12.
3. Press the “Toggle device toolbar” button.
4. Scroll down, the webpage.

_Expected results_

The text is framed correctly, and readable.

_Actual results_

There are some articles, with text that is incorrectly framed.

https://github.com/Liviu98/BugSamples/assets/129300621/da74db2c-6ea3-4fec-9537-7f388572fe19







