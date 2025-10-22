# math-test
<label for="userName">Name:</label>
<input type="text" id="userName" name="userName" placeholder="Enter your name" required>
<form>
  <h3>Question 1: What is the capital of France?</h3>
  <input type="radio" id="q1a" name="question1" value="Paris">
  <label for="q1a">Paris</label><br>
  <input type="radio" id="q1b" name="question1" value="London">
  <label for="q1b">London</label><br>
  <input type="radio" id="q1c" name="question1" value="Rome">
  <label for="q1c">Rome</label><br>

  <h3>Question 2: Which planet is known as the Red Planet?</h3>
  <input type="radio" id="q2a" name="question2" value="Earth">
  <label for="q2a">Earth</label><br>
  <input type="radio" id="q2b" name="question2" value="Mars">
  <label for="q2b">Mars</label><br>
  <input type="radio" id="q2c" name="question2" value="Jupiter">
  <label for="q2c">Jupiter</label><br>

  <h3>Question 3: What is the largest ocean on Earth?</h3>
  <input type="radio" id="q3a" name="question3" value="Atlantic Ocean">
  <label for="q3a">Atlantic Ocean</label><br>
  <input type="radio" id="q3b" name="question3" value="Indian Ocean">
  <label for="q3b">Indian Ocean</label><br>
  <input type="radio" id="q3c" name="question3" value="Pacific Ocean">
  <label for="q3c">Pacific Ocean</label><br>

  <br>
  <input type="submit" value="Submit Answers">
</form>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Word Problem</title>
</head>
<body>

    <h1>Solve the Problem!</h1>

    <p>A farmer has 20 chickens and 10 cows. Each chicken has 2 legs, and each cow has 4 legs. If the farmer also has 5 pigs, and each pig has 4 legs, how many legs are there in total on the farm?</p>

    <form action="/submit_answer" method="post">
        <label for="user_answer">Your Answer:</label><br>
        <textarea id="user_answer" name="user_answer" rows="10" cols="50" placeholder="Type your detailed answer here..."></textarea><br><br>
        <input type="submit" value="Submit Answer">
    </form>

</body>
</html>
