# Learn Tamazight Moodle Website

This repository contains updates on the creation of a Moodle website for learning the Tamazight language. 

## Installation

We originally encountered a compatibility problem with macOS 10.15. The installation finally succeeded after manually modifying the original installation package provided by moodle and replacing the Mamp server with the latest release.

**Moodle Version:** Moodle 3.8

## Setup

### Home Page:

The Setup of the home page contains temporary images and messages that will later be modified depending on what style and content is agreed on. what is currently displayed is just for testing and giving an idea of what it would look like in the furture. Colors, fonts and messages can be modified.

![alt tag](https://user-images.githubusercontent.com/54814645/82956812-ea784600-9fb1-11ea-9450-e8632fb8deea.png)

When you scroll down:
![alt tag](https://user-images.githubusercontent.com/54814645/82956898-1f849880-9fb2-11ea-9642-c0c67f358529.png)

### Dashboard:

The dashboard contains all the information that a student may need. The timeline section shows upcoming deadlines, the badges section shows the badges earned when completing tasks of learning the language (rewards). Sections can be removed and added depending on the need. 

![alt tag](https://user-images.githubusercontent.com/54814645/82957251-dd0f8b80-9fb2-11ea-9485-e487ad86ddf3.png)

## Users and Courses

### Authentication:

```
Authentification plugin: Email-based Self-Registration
```
![alt tag](https://user-images.githubusercontent.com/54814645/82957307-f7496980-9fb2-11ea-9897-d85b6801345f.png)

![alt tag](https://user-images.githubusercontent.com/54814645/82957314-fb758700-9fb2-11ea-8ba3-4b377939c2d3.png)

![alt tag](https://user-images.githubusercontent.com/54814645/82957390-23fd8100-9fb3-11ea-9a09-d00deaed686e.png)

The following automated email confirmation message is sent to the user using the support contact email address:
```
Hi {$a->firstname}, A new account has been requested at '{$a->sitename}' using your email address. To confirm your new account, please go to this web address: {$a->link} In most mail programs, this should appear as a blue link which you can just click on. If that doesn't work, then cut and paste the address into the address line at the top of your web browser window. If you need help, please contact the site administrator, {$a->admin}
```

### Adding Courses:

Courses are organized under categories, which could be levels in case of learning a language. Any type of courses can be added ranging from single time activities like quizes and tests to Social format courses where there are discussions and meetings.

![alt tag](https://user-images.githubusercontent.com/54814645/82957494-5effb480-9fb3-11ea-8883-ca6851ecaca1.png)

![alt tag](https://user-images.githubusercontent.com/54814645/82956966-4216b180-9fb2-11ea-9a44-8ee472e66c7d.png)

When you click on course description:
![alt tag](https://user-images.githubusercontent.com/54814645/82956968-44790b80-9fb2-11ea-98d7-c893484bdbda.png)

When you go to the course:
![alt tag](https://user-images.githubusercontent.com/54814645/82957152-a46fb200-9fb2-11ea-9018-9d567fcf62d2.png)

### Managing Accounts

[TODO] 

### Roles and Permissions

[TODO]

### Enrollment

[TODO]
