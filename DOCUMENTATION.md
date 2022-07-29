# Steps to deploy a full stack application
![aws infrastructure](./screenshots/Screenshot%20from%202022-07-29%2013-54-57.png)

---
<br>
1- First of all I have created my postgres database using aws RDS service <br>

![aws RDS](./screenshots/Screenshot%20from%202022-07-29%2015-56-18.png)

<br>

2- I have Created an s3 bucket to host my frontend files and uploaded all my files after building

![aws s3 bucket](./screenshots/Screenshot%20from%202022-07-29%2013-57-16.png)

<br>

3- I Created an Elastick beanstack nodejs environment to host my server & configured the env variables

![eb env](./screenshots/Screenshot%20from%202022-07-29%2014-27-36.png)

<br>
eb env variables

![eb environmet variables](./screenshots/Screenshot%20from%202022-07-29%2015-56-43.png)

<br>

4- I have linked my project's github repo to my circleCi account
![circleci pipeline](./screenshots/Screenshot%20from%202022-07-29%2016-35-38.png)

<br>
