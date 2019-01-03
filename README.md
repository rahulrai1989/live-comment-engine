# live-comment-engine
This repository allows you to implement live comments/chat without refreshing the page. The tech stack used is :
> Vue.js
> Pusher
> Laravel Echo
> Web socket

Due to these packages, this solution comes out to be very fast and efficient.

## Steps to install
Following are the steps you need to follow to have it running.
### Clone the repo
> git clone https://github.com/rahulrai1989/live-comment-engine.git

### Get into the repo
> cd PROJECT-NAME

### Install dependencies
> composer Install

### Migrate tables
> php artisan migrate

### Run Seeder
> php artisan db:seed

## Steps to see it running
> Run you application on web browser.
> Register
> Throught the top right navigation, click on manage posts and you will be able to see the list of posts.
> Click on serial id of any post and get into the post decription.
> Comment on the post.
> Every post have different channel, so the other user opening the same posts will be able to see the live real-time comment engine working. And since the channel is private so it can be done only after logging in.

