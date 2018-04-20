# 100 Days of Code - Log

### Day 0: 14 April 2018

**Progress**: 3 hours so far

**Thoughts:** Working on the cat app: https://www.freecodecamp.org/challenges/ditch-custom-css-for-bootstrap

### Day 1 15 April 2018

**Progress**: 8 hours so far

**Thoughts:** Working on css, bootstrap and the individual projects. Hating codepen so going to try to contact 100 days to see if using another method is ok

### Day 2 16 April 2018

**Progress**: Bored

**Thoughts:** Working on basic JavaScript - bored...
**Yay apparently I don't have to use code pen later on :) I can use surge or GitHub pages**

### Day 3 17 April 2018

**Progress**: Tired and had to work late so didn't manage as much as I would have liked to

**Thoughts:** Working on basic JavaScript - bored...(same as yesterday)

### Day 4 18 April 2018

**Progress**: Tired and had to work late (again)

**Thoughts:** Working on functions in JavaScript (more fun than yesterday)

### Day 5 19 April 2018

**Progress**: Tired and had to work late (again)

**Thoughts:** Working on JavaScript switch, objects and conditions - nearly there.

## Day 6 20 April 2018

**Progress**: Working on algorithms

**Thoughts:**I'm obviously rusty with algorithms which shows how much I was needing the practice - on the 8th one and my brain is starting to hurt!

<link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css">
<style>
  .red-text {
    color: red;
  }

  h2 {
    font-family: Lobster, Monospace;
  }

  p {
    font-size: 16px;
    font-family: Monospace;
  }

  .thick-green-border {
    border-color: green;
    border-width: 10px;
    border-style: solid;
    border-radius: 50%;
  }

  .smaller-image {
    width: 100px;
  }
</style>

<div class="container-fluid">
  <h2 class="red-text text-center">CatPhotoApp</h2>

  <p>Click here for <a href="#">cat photos</a>.</p>

  <a href="#"><img class="smaller-image thick-green-border" src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back. "></a>

  <img src="https://bit.ly/fcc-running-cats" class="img-responsive" alt="Three kittens running towards the camera. ">
  <div class="row">
    <div class="col-xs-4">
      <button class="btn btn-block btn-primary">Like</button>
    </div>
    <div class="col-xs-4">
      <button class="btn btn-block btn-info">Info</button>
    </div>
    <div class="col-xs-4">
      <button class="btn btn-block btn-danger">Delete</button>
    </div>
  </div>
  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>
  <form action="/submit-cat-photo">
    <label><input type="radio" name="indoor-outdoor"> Indoor</label>
    <label><input type="radio" name="indoor-outdoor"> Outdoor</label>
    <label><input type="checkbox" name="personality"> Loving</label>
    <label><input type="checkbox" name="personality"> Lazy</label>
    <label><input type="checkbox" name="personality"> Crazy</label>
    <input type="text" placeholder="cat photo URL" required>
    <button type="submit">Submit</button>
  </form>
</div>
