task-twitter-clone (Meteor)
===========================

This is a Meteor task to develop a simple twitter clone app.
The app code is empty and only test code is available.

How to work at the task
-----------------------

1. fork the repository
2. clone the forked repository
3. `cd meteor-task-twitter-clone`
4. `git submodule init && git submodule update`
5. `meteor`
6. wirte code for each task steps
7. commit and push

Task steps
----------

### step01: Title
- change HTML and H1 titles

### step02: Twitter authentication
- add Twitter authentication
- also configure it, and check if login is successful

### step03: Collection
- define a collection in both server and client

### step04: New post form
- show a form

### step05: Adding new posts
- when the form is submitted, add a post document to the collection
- use "Collection.insert"

### step06: Showing posts
- show posts in the collection

### step07: Permission check
- make it so that unauthenticated users cannot add a post
- use "Collection.allow"

### step08: User profile
- show username and profile image for each posts

### step09: Paging
- sort the posts in reverse chronological order
- only show some of posts and add "see more" feature (a.k.a. infinity scroll)
- use "publish" to publish only required posts

### step10: Notification
- show unread posts count or highlight unread posts
- use "cursor.observe"

### step11: Reply posts
- add "reply" feature to each posts
- add "in-reply-to" property to reply posts
- show reply posts by any means you want
