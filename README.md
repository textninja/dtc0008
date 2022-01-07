# Daily Tech Challenge #8 

For today's tech challenge, I'm installing and configuring rails to see how much
I can get done with the framework in an evening. I don't have experience with
Rails, but I do have experience with Ruby, so hopefully that will come in handy.

## Progress log

Immediately, I achieved the following:

![Image of the default rails screen](app/assets/images/001-first-screen.png)

I did that by running `rails new dtc0008` followed by `rails serve`. Please,
hold the applause.

Next, I followed the Ruby on Rails intro tutorial to generate blog post
scaffolding. After running `rails generate scaffold post title:string
content:text`, I wound up with a whole lot of extra files to study and a
database migration job to complete with `rails db:migrate`. After that, little
changed on the front end, but behind the scenes I assume a whack of tables were
created in SQLite or whatever the default is.
