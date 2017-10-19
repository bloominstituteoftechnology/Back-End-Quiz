# Back End Quiz

### Please follow the directions.
* Write all of your responses to the questions in a `server.js` file. You can comment out your responses to the written questions like so:

```
// 1.) Your Answer
// 2.) Your Answer again
```
* For the code part just write your code like you normally would. 
* When you're done with the project, save your server.js file and create a private Gist on your github. Then DM the gist to Ryan.
* No stress here! Just simply have fun! We're doing this so that can potentially make things better here at Lambda School!

## Written Response Questions
 * In your own words, please write out your response to the following questions:
   * 1 - What is Node?
   * 2 - What is Express? What does it do for us as developers?
   * 3 - What is `body-parser` and what does it do?
   * 4 - What does CRUD stand for and how do you represent each part of CRUD in terms of an API?
   * 5 - What is MongoDB?
   * 6 - Name two major differences between noSQL and SQL style databases.
   * 7 - What is Mongoose?
   * 8 - Describe what Schema does for us.
   * 9 - What is the difference between a document, a collection, and a database?
   * 10 - Describe ONE "Ah-ha!" moment you've had this past month.

## Code Challenge
  * Inside your `server.js` file where you just responed to all those questions. Build a node/express server that would persist content to a database, and allow you to perform CRUD operations.
  * You can be as creative as you want with this. There is no direction in regards to what type of data you are able to store. If you want to make a `pokemon` directory, do it! Have fun!
  * You can simply build your model at the top of the file after you've included your necessary pacakages. Normally you'd do this in another file, but I want to see this in one Gist so keep it clean.

  ```
  const MySchema = mongoose.Schema({});
  const Thing = mongoose.model('Thing', MySchema);
  ```
  * Feel free to use Resources. But don't reference any old code you've written. Google and the interwebs will suffice for you to find the information you need. PLEASE DO NOT: Copy and paste solutions to your file. 
