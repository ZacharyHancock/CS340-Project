# CS340-Project
Dashboard for Austin Animal Shelter using MongoDB, Python, and Dash. Built for CS-340


<ins>**Projection Description**</ins>

The Grazioso Salvare Dashboard is a web application that enables the user to filter and display data for animals from the Austin Animal Center. The features include data table filtering, a geolocation map, and a pie chart.

<ins>**Tools Used**</ins>

•	Python: Used for CRUD module to manipulate data in the database 

•	MongoDB: Used for storing the data of the animal center

•	Dash: Used for the framework of the interactive web application

<ins>**Steps Taken**</ins>

1.	Setup database and import AAC csv into MongoDB 

2.	Create CRUD module in Python (CR.py)

3.	Create interactive web layout with Dash, implement filters, geolocation maps, and pie chart, and ensure callbacks take in user inputs

4.	Debug and ensure functionality

<ins>**Challenges**</ins>

•	Filtering: initially had issues with implementing the interactive filters, adjusted the callbacks to ensure they work properly

•	Pie Chart: the visuals of the pie chart were initially not updated properly, adjusted the logic to ensure the proper visualization



https://github.com/user-attachments/assets/cf1c391e-a29d-4741-ace4-aa73723167da



<ins>**Reflection**</ins>

How do you write programs that are maintainable, readable, and adaptable? Especially consider your work on the CRUD Python module from Project One, which you used to connect the dashboard widgets to the database in Project Two. What were the advantages of working in this way? How else could you use this CRUD Python module in the future?

- Working on the CRUD Python Module taught me more about writing maintanable, readable, and adaptable code. Focusing on trying to make the code more abstract to ensure it can be utilzied in multiple different scenarios. Follwed the use of clear consistent function names, commenting where necessary to explain logic in the code, and ensured each function had one objective. I could reuse thie same CRUD modules in other projects where I need to create, read, update, and delete data from a database. This underlines the importance of abstraction

How do you approach a problem as a computer scientist? Consider how you approached the database or dashboard requirements that Grazioso Salvare requested. How did your approach to this project differ from previous assignments in other courses? What techniques or strategies would you use in the future to create databases to meet other client requests?

-I approach a problem by trying to break it down into pieces. For instance in the requirements for the dashboard I broke down each function on focused on the code pertaining to that until I got that specific function to work properly. THen moved onto the next one, like the saying: "how do you eat an elephant, one bite at a time." For this project the requirements felt more real-world, as the project was more concerned with desired features and not teachnical requirements. So I had to then understand and translate these requirments to what is required in the code to make it work. In the future, I would use the same step-by-step approach to gather the requirements, design the system, build the modules and data storage, then finally build the UI.

What do computer scientists do, and why does it matter? How would your work on this type of project help a company, like Grazioso Salvare, to do their work better?

- Computer scientitsts solve problems with tech. They build systems and applications to optimize processes, inform users, to make users more efficient. For Grazioso Salvare, these optimizations make it easier for users to access, modify, and create data so they can focus on their mission and have less of a hard time in worrying about the technical capabilites. Ultimately, making their ability to do their jobs easier.
