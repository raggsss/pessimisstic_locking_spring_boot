## Rahul's supertokens assessment
=========================
 
- Create an API that takes a random ID and increments a number in a db against that ID. If the current number against that ID is even, it will add 3 to the number, otherwise, it will add 1 to the number.
- While that is happening, a cron job should go through all the existing IDs and remove IDs that have a count of greater than 10 and are currently an even number (including 10).
- Write tests to make sure your API and cronjob work.


### Installation

To install rahul.assessment, just mvn install on the project root directory.

### Runnning the application

Run SpringBootDemoApplication as a java application (default port 8081)


### Runninng test cases

Run RandomIDSpringTest as a junit application.


### H2-console embedded database

H2 is the in-memory database, i.e. it only exists when application is running.
For accessing / viewing the database, head over to http://localhost:8081/h2-console and provide the data as shown below


![alt custom_hooks](./images/super1.png)