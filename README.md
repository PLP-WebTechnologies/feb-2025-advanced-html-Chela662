<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Complete Webpage Example</title>
</head>
<body>
  <h1>Welcome to Our Webpage</h1>

  <!-- Multimedia Section -->
  <h2>Multimedia Section</h2>
  <h3>Audio Player</h3>
  <audio controls>
    <source src="audiofile.mp3" type="audio/mp3">
    Your browser does not support the audio element.
  </audio>

  <h3>Video Player</h3>
  <video controls width="600">
    <source src="videofile.mp4" type="video/mp4">
    Your browser does not support the video element.
  </video>

  <!-- Registration Form Section -->
  <h2>Registration Form</h2>
  <form action="/submit" method="post">
    <label for="username">Username:</label>
    <input type="text" id="username" name="username" required minlength="3"><br>

    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required><br>

    <label for="password">Password:</label>
    <input type="password" id="password" name="password" required minlength="6"><br>

    <label for="age">Age:</label>
    <input type="number" id="age" name="age" required><br>

    <button type="submit">Submit</button>
  </form>

  <!-- Image Section -->
  <h2>Image Embedding</h2>
  <img src="5.jpg">
  <!-- Table Section -->
  <h2>Student Information</h2>
  <table border="1">
    <tr>
      <th>Name</th>
      <th>Age</th>
      <th>Grade</th>
    </tr>
    <tr>
      <td>Cynthia</td>
      <td>30</td>
      <td>A</td>
    </tr>
    <tr>
      <td>Alvin</td>
      <td>20</td>
      <td>B</td>
    </tr>
  </table>

  <!-- List Section -->
  <h2>Fruits List</h2>
  <ul>
    <li>Apple</li>
    <li>Banana</li>
    <li>Orange</li>
  </ul>

  <h2>Steps to Follow</h2>
  <ol>
    <li>First step</li>
    <li>Second step</li>
    <li>Third step</li>
  </ol>

</body>
</html>
