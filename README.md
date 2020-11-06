# Client-side-animal-gallery
Create a starter Express server.

Copy the hello-express into a new project
Create a static gallery index.html in:
/public/gallery/index.html
Create a JSON GET endpoint on server.js:

GET `/api/v0/gallery`
Using `app.get()` and `response.json(['one', 'two', 'three'])`.

Create a custom module to require() an array of Lorem Picsum animal IDs.

Create gallery.js file in the project root.
Copy this animals array into this file and assign it to modules.export:
`animals = [237, 433, 577, 582, 593, 659, 718, 783, 790, 837, 1024, 1025, 1074, 1084];`
Load the custom module into server.js using `require()`.
Return the animals array to the client using `response.json(animals)`.

Test everything using Postman.

[Tony's link](https://github.com/sait-wbdv/in-class/tree/main/week09f/animal-fetch)
