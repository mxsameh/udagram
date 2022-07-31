# Steps to Create a pipeline

![circleci pipeline](./screenshots/Screenshot%20from%202022-07-29%2022-21-11.png)

<br>

----
1- Link the project's github repo to my circleCi account
![circleci pipeline](./screenshots/Screenshot%20from%202022-07-29%2016-35-38.png)

<br>

2- Set circleCi env variables

![circleci pipeline](./screenshots/Screenshot%20from%202022-07-31%2019-16-27.png)

<br>
3- we added env variables to be added to the eb environment

![circleci pipeline](./screenshots/Screenshot%20from%202022-07-31%2012-59-23.png)

<br>


![circleci pipeline](./screenshots/Screenshot%20from%202022-07-31%2012-58-02.png)

<br>

## What does the pipeline do?

- first we install the frontend and backend dependencies
- then we build both our frontend and api 
- we set the environment variables to the elastick beanstack
- then we deploy both the frontend and api code that we build before