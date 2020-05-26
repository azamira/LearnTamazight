# Learn Tamazight Moodle Website

This repository contains updates on the creation of a Moodle website for learning the Tamazight language. 

## Installation

We originally encountered a compatibility problem with macOS 10.15. The installation finally succeeded after manually modifying the original installation package provided by moodle and replacing the Mamp server with the latest release.

**Moodle Version:** Moodle 3.8

## Setup

### Home Page

The Setup of the home page contains temporary images and messages that will later be modified depending on what style and content is agreed on. what is currently displayed is just for testing and giving an idea of what it would look like in the furture. Colors, fonts and messages can be modified.

insert image of front page

### Dashboard 

The dashboard contains all the information that a student may need. The timeline section shows upcoming deadlines, the badges section shows the badges earned when completing tasks of learning the language (rewards). Sections can be removed and added depending on the need. 

insert image of dashboard 

## Users and Courses

### Authentication

```
Authentification plugin: Email-based Self-Registration
```
Insert login images

The following automated email confirmation message is sent to the user using the support contact email address:
```
Hi {$a->firstname}, A new account has been requested at '{$a->sitename}' using your email address. To confirm your new account, please go to this web address: {$a->link} In most mail programs, this should appear as a blue link which you can just click on. If that doesn't work, then cut and paste the address into the address line at the top of your web browser window. If you need help, please contact the site administrator, {$a->admin}
```

### Adding Courses

Any type of courses can be added ranging from single time activities like quizes and tests to Social format courses where there are discussions and meetings.

insert course images

### Managing Accounts

[TODO] 

### Roles and Permissions

[TODO]

### Enrollment

[TODO]
