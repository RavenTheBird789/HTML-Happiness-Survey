** start of undefined **

<!Doctype html>
<html lang="en">
  <head>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <h1 id="title">Happiness Survey Form</h1>
<p id="description">Thank you for taking the time to let us know how happy you are.</p>
<form id="survey-form" >
  <div class="form-group">
  <label id="name-label" for="name">Enter Your Name: <input id="name" name="name" type="text" placeholder="name" required />
</label></div>

<div><label id="email-label" for="email">Enter Your Email: <input id="email" name="email" type="email" placeholder="email" required /></label></div>

<div><label id="number-label" for="age">Input your age (optional): <input id="number" type="number" name="age" min="3" max="120" placeholder="age" /></label></div> 

<div>
  <fieldset>
    On a scale of 1-5, how happy would you say you are?<select id="dropdown" class="form-control" required>
      <option disabled selected value>Select a number</option>
      <option>1</option>
      <option>2</option>
      <option>3</option>
      <option>4</option>
      <option>5</option>
    </select>
  </fieldset>
</div>

<fieldset>
            <legend>Would you consider yourself happy?</legend>
            <input id="yes" type="checkbox" name="yes" value="yes" checked> <label for="yes">Yes</label>
            <input id="no" type="checkbox" name="no" value="no"> <label for="no">No</label>
            <input id="sometimes" type="checkbox" name="sometimes" value="sometimes"> <label for="sometimes">Sometimes</label>
          </fieldset>

<div class="form-group">
  <fieldset>
            <legend>Do you suffer from suicidal thoughts?</legend>
            <label ><input id="yes" type="radio" name="yes-no" value="yes" checked> Yes</label>
            <label><input id="no" type="radio" name="yes-no" value="no"> No</label>
  </fieldset>
</div>

<div class="form-group">
  <p>Is there anything you'd like to add regarding why you answered the way that you did or do you have any additional questions or comments?</p>
      <textarea
        id="comments"
        class="input-textarea"
        name="comment"></textarea>
</div>

<button id="submit">Submit</button>
</form>
  </body>
</html>

** end of undefined **

** start of undefined **

h1{
  text-align: center;
}

p{
  text-align: center;
}

body{
background-color: rgb(225,225,0) 
}


** end of undefined **

