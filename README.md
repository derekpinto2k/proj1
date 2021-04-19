# README #

A "getting started" project for CIS 322, introduction to software engineering, at the University of Oregon.

### What do I need?  Where will it work? ###

* Windows 10 note: The new Windows bash on ubuntu looks promising. If you are running Windows 10, please give this a try and let me know if the Ubuntu/bash environment is suitable for CIS 322 develpment. 
 '''
------I coded this assignment in ubuntu 18.04 LTS  on windows 10. Sources say the version 20 of ubuntu is unstable
 '''

### Assignment ###
* Fork this repository to create your own repository on Bitbucket. (Read the documentation as needed, and create an account on Bitbucket if you don't have one. You should've already done finished this as part of Project 0.) 
* Clone your repository onto the machine you want to work on.
* Add the following functionality in pageserver.py. (a) If URL ends with `name.html` or `name.css` (i.e., if `path/to/name.html` is in document path (from DOCROOT)), send content of `name.html` or `name.css` with proper http response. (b) If `name.html` is not in current directory Respond with 404 (not found). (c) If a page starts with one of the symbols(~ // ..), respond with 403 forbidden error. For example, `url=localhost:5000/..name.html` or `/~name.html` would give 403 forbidden error.
* Make and test your changes. Use both automated tests (the script in the 'tests' directory) and some manual tests.
* Revise this README.md file: Erase what is no longer relevant and add identifying information. If you have concerns about adding your email ID, let the instructors know.
  
  ```
  ## Author: Derek Pinto, dpinto@uoregon.edu ##
  ```
  
### Grading Rubric ###

* Your code works as expected: 100 points

* For every wrong functionality (i.e., (a), (b), and (c) above), 20 points will be docked off. 

* If none of the functionalities work, 40 points will be given. Assuming the credentials.ini is submitted with the correct URL of your repo.

* If credentials.ini is missing, 0 will be assigned.

