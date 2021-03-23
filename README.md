
# Budget Tracker
![MIT License](https://img.shields.io/badge/license-MIT%20License-blue.svg)

# Description

The purpose of this project was to create a budget tracker application that will add funds or subtract them. All of the information must be sent to a mongoDB. We need to implement an indexDB, a service worker, and be able to use the website offline. All of the front-end code was provided to us.

```Goals for this project:```

1. Use the template code and add an indexDB 
2. Use a service worker to cache files
3. Use a manifest for the images
4. Use the website offline

# Table of Contents
* [Installation](#installation)
* [Usage](#usage)
* [Credits](#credits)
* [Questions](#questions)
* [License](#license)

# Installation

No install required.

Use the heroku link [Budget Tracker](https://budgettracker5.herokuapp.com/)

# Usage
Use the heroku link [Budget Tracker](https://budgettracker5.herokuapp.com/)

When the link is clicked the user will be looking at this when they first enter.

![home page of website](/public/screenshots/homeSS.JPG)

The user can then type in the name of the transaction, and the amount they would like to store.

![home page of website](/public/screenshots/payDaySS.JPG)

The user can the press the add funds button when they want to submit a credit.

![home page of website](/public/screenshots/payConfirmSS.JPG)

If the user has an expense they would like to track they can enter the name and amount.

![home page of website](/public/screenshots/expenseSS.JPG)

After the expense is typed in the user can press subtract funds. The expense will then be subtracted from the total funds.

![home page of website](/public/screenshots/rentSS.JPG)

The indexDB will store the offline information and the service worker will provide the cached files. This will allow the user to use the website while they are offline. Once the user is back online the information that was stored in the indexDB will be pushed to the mongoDB tied in with this application.

![home page of website](/public/screenshots/devToolsSS.JPG)

# Credits
Created by: 
Andrew Boyle
[Git Hub Profile](https://github.com/Andyb2)

# Questions
If you have any questions about this project please email:
a.michael.boyle@gmail.com

# License

MIT License

    Copyright (c) [2021] [Andrew Boyle]

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.
  