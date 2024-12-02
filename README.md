PART 1: MULTIMEDIA SECTION

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Audio and Video Example</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 20px;
        }
        .media-section {
            margin: 20px auto;
            max-width: 600px;
        }
    </style>
</head>
<body>
    <h1>Media Elements: Audio and Video</h1>

    <div class="media-section">
        <h2>Audio Player</h2>
        <audio controls>
            <source src="audio-sample.mp3" type="audio/mpeg">
            Your browser does not support the audio element.
        </audio>
        <p>Listen to this audio track!</p>
    </div>

    <div class="media-section">
        <h2>Video Player</h2>
        <video controls poster="video-poster.jpg" width="100%">
            <source src="video-sample.mp4" type="video/mp4">
            <source src="video-sample.webm" type="video/webm">
            Your browser does not support the video element.
        </video>
        <p>Watch this video!</p>
    </div>

</body>
</html>
PART 2: REGISTRATION FORM

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration Form</title>
</head>
<body>
    <form action="/submit-registration" method="post">
        <h1>Register</h1>

        <label for="fullName">Full Name</label><br>
        <input type="text" id="fullName" name="fullName" required maxlength="50" placeholder="Enter your full name"><br><br>

        <label for="email">Email Address</label><br>
        <input type="email" id="email" name="email" required placeholder="Enter your email"><br><br>

        <label for="password">Password</label><br>
        <input type="password" id="password" name="password" required minlength="8" placeholder="Enter a password"><br><br>

        <label for="age">Age</label><br>
        <input type="number" id="age" name="age" required min="18" placeholder="Enter your age"><br><br>

        <label>Gender</label><br>
        <input type="radio" id="male" name="gender" value="Male" required>
        <label for="male">Male</label><br>
        <input type="radio" id="female" name="gender" value="Female" required>
        <label for="female">Female</label><br>
        <input type="radio" id="other" name="gender" value="Other" required>
        <label for="other">Other</label><br><br>

        <input type="checkbox" id="terms" name="terms" required>
        <label for="terms">I agree to the terms and conditions</label><br><br>

        <button type="submit">Register</button>
    </form>
</body>
</html>
