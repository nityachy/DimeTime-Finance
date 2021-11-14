# DimeTime-Finance
Finance site for youth 

# Inspiration

The lack of school curriculum present on personal finance inspired us to create Dime Time. It is important for the youth of the world to be introduced to proper money management, as it is a skill that will take them far in their lives. However, it is also a skill that is underemphasized in education. For instance, nearly 50 percent of high school seniors say that they wish they had learned personal finance in school, yet only 17 states mandate personal finance courses for high schoolers. We have recognized this problem both through such statistics and through our personal experiences, and we hope that Dime Time will help young people across all backgrounds improve their financial literacy.

# What it does

Dime Time is a guide and simulator for youth. Kids can earn money to grow their virtual bank through chores and watching educational videos, and they can recognize how this money might be used by spending it on items such as groceries or entertainment (e.g. going to the movies). Dime Time also provides a variety of resources in its Learning and Budgeting sections that children and parents alike can use to further their knowledge of personal finance; these resources cover topics from financial risk assessment and insurance to budgeting and credit. Finally, Dime Time has a Bank section, which allows users to better monitor how they are using their money by viewing their spending and earning history, along with their current balance.

# How we built it

We built Dime Time using Handlebars, HTML/CSS, JavaScript, and SQL. The application framework we used was Express. The site pages are constructed as Handlebars templates, using CSS stylesheets, while JavaScript was used to keep track of important information in the backend and allow the user to interact with the page elements. We had three tables (for the users, duties, and spending options) in MariaDB, which we operated on using SQL. Finally, both encrypted and unencrypted cookies were used to store and update information in the browser.

# Challenges we ran into

A lot of challenges when working on the front end happened when we were trying to create our cards. It took a good chunk of time as it was a trial and error process in getting the cards to look the way we wanted them to. Another challenge was version control: At times, it was difficult to collate the code we had written in such a way that everything was updated and the backend could communicate properly with the frontend. The fact that we used different names for certain elements was also a source of difficulty. SQL presented several challenges as well, such as with the stored procedures not updating the tables correctly.

# Accomplishments that we're proud of

Despite the challenges, we are proud that we were able to achieve a working website that has most of the elements and functionality we had envisioned. We are also proud that although there were some details we had differing visions of, we were able to sort out all misunderstandings and discrepancies through consistent communication. It was very rewarding to see how all the different aspects of the website that we worked on meshed together and interacted with each other to create the final product.

# What we learned

Coding-wise, we learned many new tips in styling page elements, including the use of forms, tables, background images, and borders. Coming into this project with a relatively brief background on how endpoints, routers, and Handlebars worked, we learned and practiced how to use cookies and tables to enhance the functionality of the site. Above all, we learned the importance of talking out our ideas. Through exchanging our thoughts and clarifying ideas with one another, we were able to figure out exactly what our goal was for the site. This helped us get our individual tasks done on time and accomplish all the checkpoints we had for our project.

# What's next for Dime Time

In order to keep our interactive site fun for all, future steps include both expanding on the current features and elements we have, as well as implementing new ones. We aim to add more options for earning and spending that are reflective of real life: Rent and student debt in spending, for example, and stocks in earning. In addition, we hope to expand our library of video and article resources. As for new features, we could establish consequences for certain financial decisions or outcomes (e.g. if the user fails to pay rent), or have a system that occasionally gives the user an unexpected expense. In the Bank section, we could add an interactive element that provides a template for the user to budget their money. We also hope to create new web pages and more activities, such as games, to motivate kids to stay on our site.
