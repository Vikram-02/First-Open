<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body>
    <form action="./classexam.html" method="get">
      <fieldset>
        <legend>Contact From with patterns</legend>
        <div>
          <label for="name">Full Name</label>
          <input type="text" id="name" placeholder="Full Name" required />
        </div>
        <br />
        <div>
          <label for="mail">Email</label>
          <input
            type="email"
            id="mail"
            placeholder="Enter a email"
            pattern="^[A-Za-z0-9.-_]+@[A-Za-z0-9.-_]{3,}.[A-Za-z0-9]{2,}$"
            required
          />
          <p>Should be allow only gmail's</p>
        </div>
        <br />
        <div>
          <label for="age">Age</label>
          <input
            type="number"
            id="age"
            placeholder="Enter a Age"
            min="18"
            required
          />
        </div>
        <br />
        <p>Select your Gender</p>
        <div>
          <input type="radio" id="check" name="gender" />
          <label for="check">Male</label>
          <input type="radio" id="check1" name="gender" />
          <label for="check1">Female</label>
        </div>
        <br />
        <div>
          <label for="Message">Message</label>
          <textarea name="comment" id="Message"></textarea>
        </div>
        <div>
          <p>Fav Games</p>
          <input type="checkbox" id="fav" placeholder="Select your Fav Games" />
          <label for="fav">Cricket</label>
          <input type="checkbox" id="fav" placeholder="Select your Fav Games" />
          <label for="fav">Kabbai</label>
          <input type="checkbox" id="fav" placeholder="Select your Fav Games" />
          <label for="fav">Kho Kho</label>
          <input type="checkbox" id="fav" placeholder="Select your Fav Games" />
          <label for="fav">Chess</label>
        </div>
        <br />
        <button>Submit</button>
      </fieldset>
    </form>
  </body>
</html>

again i add the test file as a table format
