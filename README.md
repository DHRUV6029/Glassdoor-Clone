# Glassdoor Prototype

## Abstract

Glassdoor Prototype is a clone of real [Glassdoor](https://www.glassdoor.com) web application where current and former employees add reviews/photos of companies. It also allows us to create job alerts by asking interesting industry to its users. The application has three entities,

The application has the following features,
* **Backend**
    * Each backend route is secured using PassportJS meaning no unauthorized user can access it
    * `Kafka` is used to improve performance under a large number of concurrent user requests
    * To reduce the time taken by each request to be served is reduced using `Redis`
    * Some of the APIs use server-side pagination to decrease Frontend rendering load
    * To store the passwords of users securely `MySQL` is used and to retrieve all other information quickly `MongoDB` is used

* **Frontend**
    * The frontend heavily uses components in `ReactJS` to increase the reusability
    * Job/Company search is shown using `Pagination` so that the user does not get overwhelmed
    * A simple and user-friendly UI is developed in `HTML` and `CSS`
    * Admin dashboard is loaded with informative graphs (Bar, Wordcloud, etc.)
    * `Modals` are used to remove excessive back and forth to do a single task



## Technology Stack

#### Backend
* NodeJS
* PassportJS
* Kafka
* MongoDB
* MySQL
* Redis




## References

* https://nodejs.org/en/
* https://reactjs.org
* https://recharts.org/en-US/
* https://nivo.rocks
* http://www.passportjs.org
* https://www.mongodb.com
* https://www.mysql.com
* https://redis.io
* https://aws.amazon.com/ec2/
