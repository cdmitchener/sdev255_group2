 # SDEV 255: Team 2 Final Project

Prompt: Create a web application that allows students sign- up for college courses, and for teachers/staff to add, delete, and edit courses.


## Authors

- [Lauren T.](https://github.com/Keraunic-Tonic) -- Front end work
- [Chelsea M.](https://github.com/cdmitchener) -- Back end work
- [Marcus K.](https://github.com/DotDotDottt) -- Unable to contribute because the building blocks that he needed were not completed by Matthew; however, important to note that he had no further communication with us past 5/5.
- [Matthew L.](https://github.com/MStudent1) -- Failed to contribute. Was assigned middleware.

Notes about communication with Matthew in order to have evidence of his non-participation and an effort on our part to try and keep accountability
(It is important to also mention that this is not to throw anyone under the bus. It is for information and to give insight into the issues.):

5/11
Chelsea: "@mlanc15 Were you able to send the updates to Github so that we can write our discussion posts that are due today?"
Matthew: "Yeah
https://github.com/Keraunic-Tonic/SDEV-255-Team-2-Final-Project/tree/Updated-project-w/-user-schema/model"
Chelsea: "Awesome, thanks Matthew!"
Matthew: "I still gotta work on adding code to allow the user to interact with mongodb atlas and the user schema/model through the web application."
Chelsea: "Nothing shows up when I try to view it after running nodemon app. What could I be missing?"
Matthew: "Not sure, I'll figure it out sooner or later"
Chelsea: "Ok, I hate that chat doesn't give any indication of tone,  but I'm sure  you mean that in a laid-back way and not in a flippant way. Remember that Marcus will need time to do his part as well. The grade for all of us could be affected by the failure of not being able to get the app to even load, though I'm sure the instructor will take into consideration the effort put forward by each team member on an individual basis."

5/14
Matthew: "I need some help setting up the mongodb atlas collection. It won't let me login through the website."

5/15
Chelsea: "I’m out of state spending time with family. If you’re having trouble logging into the website, try resetting your password."
Matthew: "Figured it out, something was up with my internet connection to the website."

5/16
Chelsea: "@mlanc15 Haven't heard from ya, so just checking in to make sure you remembered that the middleware portion is due tonight, then @DotDotDot the final version is due Wednesday. I really hate having to nag, but want to make sure that we're on top of this since the end of the semester is upon us."
Matthew: "I'm struggling to figure out a couple of things."
Lauren: "Ok, what things are they?"
Matthew: "I'm not sure how to connect app.js to the user collection on Mongodb atlas"
Chelsea: "The user collection is already connected by referencing the attached url in the screenclip. It knows what collection to look at by defining a Schema and directing new objects to be defined as a user in the Users collection (or deleting existing objects by referring to them as a user as part of the Users collection). Does that make sense?"
Lauren: "Based on what I see in the most recent check in, you might need to use this code on line 17? Hopefully it helps, this is just what I had on my other two mongodb project files
const dbURI = "mongodb+srv://sdev255_team2:team2^@cluster0.d0eab.mongodb.net/sdev255_sp22?retryWrites=true&w=majority";
mongoose.connect(dbURI, {  useNewUrlParser: true, useUnifiedTopology: true })Laur
  // listen for requests after successful connection to DB
  .then((result) => app.listen(3000))
  .catch((err) => console.log(err));
Since we only have a little over an hour left, I think it may be best to call it in and submit what we have. We can tell the teacher in the comments on what we struggled with, but I don't think we're going to be able to finish everything by midnight tonight."
Matthew: "I'm gonna keep on working until I get it done. Perhaps we could turn it in again later?"
Lauren: "In general, I think it'll be better to have something not 100% done submitted before midnight tonight, and if you can turn in another more complete version before too late tomorrow, you should be able to submit a new attempt. Basically, it'll look better if we have something in Canvas vs. not having anything when the clock stricks 12, you know?"
Matthew: "Yeah, I apologize for not being able to get it done on time. I've been busy with other projects/final exams as well."
Lauren: "totally understandable. I've been caught up with work and other homework assignments as well. So if you'd like, you can keep working on what you can, and I'll go ahead and submit our most recent part of the repo"
Matthew: "Ok, I'll try my best on implementing the login features"
Chelsea: "@mlanc15 Agreed, it's understandable. I'm sorry if I came across as harsh the other day. I've been dealing with some stress from other things and life in general as well. We'll get it figured out."
Matthew: "Thank you for being understanding."

5/17
Lauren @ 1507: "Hey @mlanc15 , just wanted to check in to see how things are going"
Matthew @ 1706: "I'm caught up with some final exams at the moment"

As of 5/17 @ 2124 there has been no further communication.


