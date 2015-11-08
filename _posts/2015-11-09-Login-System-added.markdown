---
layout: post
title:  "Login Sytem Added! [Explained]"
date:   2015-11-09 13:54:48
categories: sixth post
---

Hello Readers, 

This post lists down all the info about the login system created by us for the application. 

We have decided not to go for the registration process because already we have the login for our Dean Academics so the the new registration process would only be doing the same task again.

We do have a new database for the login hits we will just export every student details present in the dean academics database. 

For creating the login more secure we are not storing the raw password strings, but we store encrypted passwords and give a feature of changing your password [ not present in dean academics login ]. Below is the procedure of how we encrypt our password and store it in our database : 

```
$password = 'Your dean academics password' ;
```

```
$salt = 'random salt string' ;
```

```
$encypted_pass = sha1( $password.$salt ) ;
```

```
Store_in_DB ( $regno , $encypted_pass, $salt );  
```
 
For automating the export process and generating random salt string and encrypting the dean acads password we will write a script for smooth export. 
Now if you forgot your password or you wish to update your password, you can do it very easily by just providing your previous password. :)

I hope this explains the idea behind this login process. 

Thank you. 

