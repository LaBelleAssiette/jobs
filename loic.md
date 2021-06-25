# Context

Chef Loïc is confronted to a big problem: due to his incredible number of bookings, maintaining a count of everything he has in his huge kitchen became a pain.
He needs a web application to help him manage an inventory of all the ingredients he possesses.

He wants to be able to:

* Add and remove ingredients to his inventory
* Deal with quantities
* Change the name of his ingredients in case he ~~mispelled~~ misspelled them

# What we ask for

* Build a minimal application to help chef Loïc manage his stock.
* This application must use an express.js (or express-like) API server.
* Use MongoDB (along with mongoose for the ORM) (as we do at La Belle Assiette), to demonstrate that you have good schema design competencies.
* No need for user authentication.
* For the web application, use any framework you feel most comfortable with, you're free to _not_ use a framework if the application still feels like an "app" (correct redirections, AJAX calls, etc.). At LBA we use React.
* No need to spend time on web design. Plain Bootstrap is plenty enough, we use it too and there is no shame in using this kind of libraries. Even better: if you show you can do a good design with just bootstrap, you'll fit right in ;)
* The data _cannot_ be stored (only) with the `localStorage` API. You must have an API server that handles the CRUD operations.

The data structures and the file(s) format are totally up to you, but keep in mind we'll take them into consideration.

You can use a bootstrap/generator to kickstart your app (e.g. create-react-app). We do however care about every file that you'll turn in, so don't create bloat (unused files/config).

When you're done, share your code with @saveman71 on GitHub.

# FAQ

## What will you evaluate my work on?

We want to see how you would code daily at La Belle Assiette. Apply any best-practice you know about the JS community and/or what you learned during your past experiences, and that would make sense in a production environment. We want beautiful, easy to understand code!
It's also very important that your project works "the first time". We don't mind debugging your code to be able to evaluate it, but as you imagine, this will lower your grade.
We evaluate each submission carefully and rank it on our own grading system.
In any case, even if you're not selected, we'll spend some time with you on the phone to explain what we liked/didn't like. Think of it like a school project, where you are graded and where you will get feedback on where to improve.

## How much time should I invest on this task?

We are aware that we are asking for a lot. We will accept that you leave out part of the implementation if you explain in the README or in comments what you were intending to add, and how you would have done it. However we'd still like to see your best work, so don't leave out too much! If you have time and other ideas, please add them!

## Do I need to write tests?

It's appreciated but not required. A few unit tests are enough to demonstrate you know how to use the test framework of your choice. At La Belle Assiette we use Jest!

## Do I really need to do this?

If you have a similar project **that you did alone** (CRUD operations, etc.) in Node.JS/express/Mongoose, feel free to share it with us :) We'll then tell you if we still need you to code this small project.
