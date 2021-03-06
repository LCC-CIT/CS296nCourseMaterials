# Term Project Requirements 

**Web Development 2: ASP.NET**

Your web site should meet the following requirements:

1. **Rich Media**
   Include some kind of interactive “rich” media. This could be as simple as images the user can click on, and/or various images that are displayed in response to user input. It could involve video or sound or jQuery animations, or some other media besides text.

2. **Data-driven**
   To be data-driven means that the content of one or more of your web pages contains content derived from information stored in a database. 
   In addition:

   - Users should be able to enter data that will be stored in the database.
   - Some of the data entered by users should be visible to other users. 
   - Users should be able to do some kind of searching of the database.

     An example would be a classified advertising site where users could enter items for sale and other users would be able to see those items and search for items by key words in the item description.

3. **Complexity**
   Be moderately complex&mdash;not too simple, but not too hard to build. Here are some criteria:

   - The database should have  4 to 6 domain models.

   - The total number of fields in the domain models should be between 12 and 30.
   - There should be between 10 and 15 web pages.
   - The web site should have some kind of consistent navigation that appears on each page.

4. **Identity**
   Require authentication and authorization. This means there will be a way for users to register and log in. There should be at least three levels of authorization:

   - Guest: these users don’t need to log in, but will only be able to access a limited number of pages and/or features. (This does not need an Identity Role.)
   - Member: these users can access anything except the pages/features that are only for administrators.
   - Administrator: these users can access everything.

5. ~~**Consume a Web Service**~~

   - ~~At least one page of the site will pull data from a web API&mdash;like a weather forecast or stock prices.~~

6. **Security**
   Use Zap to test your app. Do these tests on your own machine, not on a public web server.

   - Be sure to test your app with yourself logged into the app in a non-admin role.

   - Mitigate any high-priority security risks.
   - Provide a document containing screen shots and notes on mitigation.

7. **Publish to a server**

   - Publish your web app to Azure or some other web host.

   



**Notes**

- The term project must be different from the web app you used in your weekly lab assignments and different from the instructors examples or the textbook examples.

- Good coding practices, such as using unit tests, are expected in the term project.

 

------

[![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/) 
​ASP.NET Core MVC course materials written by [Brian Bird](https://profbird.dev), 2020 and revised 2021, are licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/). 

------

