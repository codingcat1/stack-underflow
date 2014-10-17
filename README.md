#STACK UNDERFLOW
------------
####Created by [Catherine Tran] (https://github.com/tranc489) on September 22, 2014

#####Description:
Clone of the Stack Overflow site.  Meant for users to post questions and other users to post answers to those questions.  User who posted the question should be able to vote on their favorite answer.  Other users should be able to upvote or downvote on answers to questions, as well as comment on answers.


#####Instructions:
In terminal, clone by:
```console
$ git clone https://github.com/tranc489/stack-underflow.git
```
Install gems by running:
```console
$ bundle install
```
Create databases on current machine by running:
```console
$ rake db:create
$ rake db:migrate db:test:prepare
```
Start rails server by running:
```console
$ rails s
```
Enter `localhost:3000` in browser address bar.

Have fun!



#####Known Bugs/Functionalities not yet created, plus additional Notes:
- Currently, a user must be signed up and logged in in order to be able to see the button to create a new question.(will work on fixing so that user can see the button but gets an error message when after clicking it if they are not logged in).
- Creator of question cannot yet vote best answer to the question.
- Users cannot yet upvote on answers.
- Polymorphism not yet implemented.(Comments cannot have multiple comments)




####License:
MIT
