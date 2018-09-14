# Context

Chef Amit is confronted to a big problem: due to his incredible number of bookings, maintaining a count of everything he has in his huge kitchen became a pain.
He would like a web application to help him manage an inventory of all the ingredients he possesses.

He wants to be able to:

* Add ingredients to his inventory
* Deal with quantities
* Change the name of his ingredients in case he ~~mispelled~~ misspelled them
* Remove the ingredients he has already used for cooking
* Handle uncountable ingredients as well (milk, olive oil, etc.)

He likes his applications to be intuitive :)

# What we ask for

* Build a small application to help chef Amit manage his stock.
* This application must use an express.js (or express-like) API server.
* Use MongoDB (along with mongoose for the ORM) (as we do at La Belle Assiette), to demonstrate that you have good schema design competencies.
* No need for user authentication.
* For the web application, use any framework you feel most comfortable with.
* No need to spend time on design. Plain Bootstrap is plenty enough.
* The data _cannot_ be stored (only) with the `localStorage` API. You must have an API server that handles the CRUD operations.
* More generally, apply any best-practice you know about the JS community and/or what you learned during your past experienced

The data structures and the file(s) format are totally up to you. Feel free to split (or not) the API server and the main application (two repositories).

You can use a bootstrap/generator to kickstart your app (e.g. create-react-app). We do however care about every file that you'll turn in, so don't create bloat (unused files/config).

When you're done, share your code with @saveman71 on GitHub.

# Final word

Don't spend too much time on this, really. If you feel like you have something that accurately represents what you can do, but don't have the time to polish it, it's okay, we'll accommodate.
