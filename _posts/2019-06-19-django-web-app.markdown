---
layout: post_update
title:  "Django Web Application"
date:   2019-06-19 20:01:40 +0300
categories: portfolio
author: Jireh
---

Over the summer, during my internship, I was tasked to build a web application for the company that I was working with. My task was to create a membership portal for current subscribers, where they could view and interact with purchased content.  

During the past semester, as part of the [50.003 Elements of Software Construction][50-003] module, where my group and I worked together to create a ticketing platform for [Accenture Digital][acnapi], we used the Python [Django Framework][django] as part of the tech stack. Since I was relatively more familiar with this framework as compared to other frameworks, this was my main reason for choosing to build the web application on Django.  

Through building the web application, I was able to explore other libraries in Django, including the [Django REST Framework][drf] for quick backend rendering, as well as utilising [django-excel][django-excel] to populate a database from a pre-defined table format. One very useful thing about Django is its [built-in authentication system][django-authentication], which made creating the login process, including the resetting and changing of passwords a lot simpler. By using [Colorlib's login template][colorlib-template], all I really needed to do was to link the front-end design with the Django backend.  

Django also allows building sites with [Bootstrap][bootstrap], which was my frontend framework of choice for this particular project.

The main features of this particular web application are shown below. Do note that sensitive information has been omitted for security and confidentiality reasons. 

**1. Membership Login**  

* Login Page  

![Login Page](/assets/img/django/django-login.png)

* Reset Password Page  

![Forget Password Page](/assets/img/django/forget-password.png)  

* Reset Password Success  

![Reset Password Success Page](/assets/img/django/forget-password-success.png)  

* Change Password Page  

![Change Password Page](/assets/img/django/change-password.png)

{:start="2"}
**2. Administrator Pages** 

![Administrator Management Page](/assets/img/django/admin-directory.png)

* Create new users  

* Manage existing users (for administrators only)  

![User Management Page](/assets/img/django/user-management.png)  

* Manage existing administrators (for super-administrators only)  

![Staff Management Page](/assets/img/django/staff-management.png)  

* Manage existing super-administrators (for super-administrators only)  

![Superstaff Management Page](/assets/img/django/superstaff-management.png)

* Update permissions
* Populate database via .xlsx file  

![Upload Excel Page](/assets/img/django/upload-excel.png)  

{:start="3"}
**3. Subscription Page: for existing subscribers to purchase products**

![Subscription Page](/assets/img/django/subscribe.png)

{:start="4"}
**4. Contact Us Page**  

![Contact Page](/assets/img/django/contact.png)  

{:start="5"}
**5. Content Page: articles were scraped from the main content website and displayed here.**  

![Blog Page](/assets/img/django/blog.png)  


[50-003]: https://istd.sutd.edu.sg/undergraduate/courses/50003-elements-of-software-construction
[acnapi]: https://beta.acnapi.io/
[django]: https://www.djangoproject.com/
[drf]: https://www.django-rest-framework.org/
[django-excel]: https://github.com/pyexcel-webwares/django-excel
[colorlib-template]: https://colorlib.com/wp/template/login-form-v14/
[bootstrap]: https://getbootstrap.com/
[django-authentication]: https://docs.djangoproject.com/en/2.2/topics/auth/