JESSICA SACKEY 1704965263
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <link rel="stylesheet" href="styles.css">
    <title></title>
  </head>
  <body>
    <h1 id="title">Survey Form</h1>
    <p id="description"><i>Thank you for taking the time to help us improve the platform</i></p>
    <form id="survey-form">
      <label for="name" id="name-label" >Name 
      <input type="text" id="name" required placeholder="Enter your name">
      </label>
      <label for="email" id="email-label">Email 
      <input type="email" id="email" required placeholder="Enter your email" pattern="[a-zA-z]{3, }@[a-zA-Z]{2, }.[a-zA-Z]{3}" title="Please enter a valid email address" >
      </label>
      <label for="number" id="number-label">Age <span class="optional">(optional)</span> 
      <input type="number" id="number" placeholder="Age" min="10" max="150">
      </label>
      <label for="dropdown" class="me">Which option best describes your current role? 
      <select id="dropdown">
      <option >Select current role</option>
        <option>Student</option>
        <option>Full Time Job</option>
        <option>Full Time Learner</option>
        <option>Prefer not to say</option>
        <option>Other</option>
      </select>
      </label>
     <div class="">Would you recommend to a friend? </div>
        <label for="">  <input type="radio" name="yesNo" value="Definitely" checked> Definitely</label>
      <label for=""> 
      <input type="radio" name="yesNo" value="Maybe"> Maybe</label>
      <label for=""> 
       <input type="radio" class="me" name="yesNo"  value="Not Sure"> Not Sure</label>
      <div>What would like to see improved? <span class="optional">(Check all that apply)</span></div>
      <input type="checkbox" value="A"> A
      <br> <input type="checkbox" value="B"> B
       <br> <input type="checkbox" value="C"> C
       <br>  <input type="checkbox" value="D"> D
         <br> <input type="checkbox" value="E"> E
      <div>Any comments or suggestions? </div>
      <textarea id="comments" placeholder="Enter your comment here..." rows="4"></textarea>
    <br>
      <button id="submit">Submit</button>
    </form>
  </body>
</html>
