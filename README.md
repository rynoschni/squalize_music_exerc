# squalize_music_exerc

Exercise: Sequelize Music App
Sequelize Exercises
Creating Models
Using the Sequelize CLI, generate models and relationship migrations for the following database:

Artist
Artist Name
Album
Album Name
Year
Artist ID
Track
Track Name
Track Duration
Album ID
Create Routes
Next, we will be creating new routes so that we can submit data to our server, and then create the data in the database. You can either create an HTML form to submit the data, or use Postman.

Make sure you think about validation. Should the entry be created if some/all of the fields are empty?

Build a "Create Artist" Route
Create a route that accepts a POST request that will store a new artist in the database.

Build a "Create Album" Route
Create a route that accepts a POST request that will store the new album in the database. It should respond with an error if the artist id does not exist.

Build a "Create Track" Route
Create a route that accepts a POST request that will store the new track in the database. It should respond with an error if the album id does not exist.
