# Learning Log

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Phasellus hendrerit. Pellentesque aliquet nibh nec urna. In nisi neque, aliquet vel, dapibus id, mattis vel, nisi. Sed pretium, ligula sollicitudin laoreet viverra, tortor libero sodales leo, eget blandit nunc tortor eu nibh. Nullam mollis. Ut justo. Suspendisse potenti.

Sed egestas, ante et vulputate volutpat, eros pede semper est, vitae luctus metus libero eu augue. Morbi purus libero, faucibus adipiscing, commodo quis, gravida id, est. Sed lectus. Praesent elementum hendrerit tortor. Sed semper lorem at felis. Vestibulum volutpat, lacus a ultrices sagittis, mi neque euismod dui, eu pulvinar nunc sapien ornare nisl. Phasellus pede arcu, dapibus eu, fermentum et, dapibus sed, urna.

## 8 May 2025

**Today's Focus**: Databases databases databases

**What I did today:** Worked on my Devjobs ASP.NET project that will use MongoDB for the data. It'll help me keep the knowledge fresh since getting my certification. That was for the Node.js path but I'm working through the C# path now. I also started looking at PostgreSQL since I'll need to learn a relational database if I want be a rockstar dev.

**Link(s):**
- [Devjobs web app](https://github.com/ntjnh/devjobs) (repo)
- [MongoDB C# Developer Path](https://learn.mongodb.com/learn/learning-path/using-mongodb-with-c-sharp) (MongoDB University)
  - MongoDB and the Document Model
- [PostgreSQL Tutorial](https://www.w3schools.com/postgresql/index.php) (W3Schools)

### 9-12 May 2025

**Today's Focus**: Databases again but also ASP.NET MVC routing 😒

**What I did today:** I really tried my best to resist using extra tools but I really struggled to get my MongoDB database working without using Entity Framework Core as well. I know it speeds things up and helps make things easier but I like to at least understand how to do things manually before I start using tools that make things quicker or easier. Anyway, it works now. I'm now going to figure out how to containerise the app as suggested by my mentor. The restrictions imposed by our office network means that I can't connect to my database while I'm in the office 🙃 ANYWAYS. I also reluctantly did my routing differently as well because again, the hard way wouldn't work so I used the easier way/followed the MS Learn tutorial for creating a Web API with MongoDB and made the necessary changes to make it work for a regular web app. It was vastly easier and I can see why it's the better way of doing things so...no regrets...not really! I did a little bit more of the PostgreSQL tutorial but not much. I'm actually slightly considering using it for this app if it means I'll be able to connect to it in the office lol

**Link(s):**
- [MongoDB C# Developer Path](https://learn.mongodb.com/learn/learning-path/using-mongodb-with-c-sharp)
  - Connecting to MongoDB in C#
- [PostgreSQL Tutorial: Create Demo Database](https://www.w3schools.com/postgresql/postgresql_create_demodatabase.php)
- Resources
  - [Create a web API with ASP.NET Core and MongoDB](https://learn.microsoft.com/en-us/aspnet/core/tutorials/first-mongo-app?view=aspnetcore-9.0&tabs=visual-studio)

## 13-14 May 2025

**Today's Focus**: Fighting with checkboxes in ASP.NET Core + PostgreSQL practice

**What I did today:** I finally manageed to get the checkbox working in the devjobs app. It's part of the search/filter. You check it to only display full time jobs. It was driving me insane but I eventually found the right documentation that helped me understand how checkboxes work in ASP.NET. It also ended up being using for some bug fixing I did for one of my work projects that involved an issue with some conditional checkboxes in an ASP.NET application so win win! I did a little bit of practice with postgres but not loads. I was mainly consumed by the issues I faced with the devjobs app. My next step is to polish the keyword search field because it only checks positions at the moment but I'm going to make it include company names as well. After that, pagination!

**Link(s):**
- Resources
  - [Add search to an ASP.NET Core MVC app](https://learn.microsoft.com/en-us/aspnet/core/tutorials/first-mvc-app/search?view=aspnetcore-9.0)
  - [Checkbox hidden input rendering](https://learn.microsoft.com/en-us/aspnet/core/mvc/views/working-with-forms?view=aspnetcore-9.0#checkbox-hidden-input-rendering)
  - [Add paging](https://learn.microsoft.com/en-us/aspnet/core/data/ef-mvc/sort-filter-page?view=aspnetcore-9.0#add-paging-to-students-index)
