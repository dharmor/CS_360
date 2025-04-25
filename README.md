## CS-360  Mobile Architect & Programming
# Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
Developed as an inventory tracking application, it uses a password and user ID to authenticate an end user to ensure only authorized edits are made.
Using the application, a user can add, remove, increase, and decrease items in a database after logging in.
The application can send a user an alert if the stock reaches '0'. The SMS message is sent to users whose phone number is set in the settings Activity. The inventory is organized into a table view alphabetically.
## 
# What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
The application uses five screens: a login, a tableview display of inventory, settings, adding items, and updating items.
I designed the application to be intuitive, so there is little or no learning curve. I also used a color scheme that consists of blues and grays. This seems to work well and is easy on the eyes when viewing.
I used a common layout for all the screens and kept everything simple, which lead to the success of the application.
## 
# How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?
The approach I used is what I typically use when writing a program. I read the specifications. Think about how it could work and picture it in my head. Once I do that, I start to code, I start with a very simple aspect of the application. In this case, I started with the database. This was needed on every page, and it gave me a firm idea of how the database would integrate into the application.
For me, in the future, I have to get a program logically working in my head before I start to program. I typically use this method as it works for me, and I get an idea of how different aspects will or should work.

## 
# How did you test to ensure your code was functional? Why is this process important and what did it reveal?
I would have liked to have done some Junit testing, but time was against me, and I couldn’t do it. So, I did what I typically do, use break points throughout the code and print the variable’s content and where the program is at using print or log statements.
The process I used turned out to be more important when I was writing the program. Being new to developing Android apps at times, the app would crash. The error messages were not very helpful, so stepping through and commenting out sections of code that were added really helped. In several cases, I was trying to access a component on a page that hadn’t yet finished starting, resulting in a null exception, but the error did not point to where the error was. Stepping through the code helped figure that out.

## 
# Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?
In my opinion, the explanation given by the textbook on using fragments wasn’t really helpful. I wanted to use them but didn't know how; this is something I’ll be looking into. The fragments would have helped with creating the data table. So, I created the entire table programmatically. This made the table dynamic and all I had to do was call one method to create the table when it had changed.
## 
# In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
## 
The most successful part of the program was creating the data table dynamically, using only code. In order for that to work right, a deep understanding of the database and how the components work to display the information was needed. In addition, I learned some new things like storing identification information in the component, so I was able to determine what was clicked on.
