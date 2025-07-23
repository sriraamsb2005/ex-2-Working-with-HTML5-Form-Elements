# ex-2-Working-with-HTML5-Form-Elements
HTML5 provides tags like &lt;form>, &lt;input>, &lt;label>, and supports new types like email, date. It includes attributes like required, placeholder, and tags like &lt;datalist> for better user input.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BELL SCHOOL Admission Form</title>
</head>
<body>
    <div style="text-align: center;">
        <img src="bell.jpeg" alt="Bell School Logo" width="200" height="200">
    </div>
    <div>
        <h1 style="text-align:center; background-color:powderblue">BELL MATRICULATION SCHOOL</h1>
        <h1 style="text-align: center; color: red;">School Admission Form</h1>
        <form>
            <fieldset>
                <legend><h2 style="color: green;">Personal Information:</h2></legend>
                <label for="fname">FIRST NAME:</label><br>
                <input type="text" id="fname" name="fname"><br>
                <label for="lname">LAST NAME:</label><br>
                <input type="text" id="lname" name="lname"><br>
                <label for="age">AGE:</label><br>
                <input type="number" id="age" name="age"><br
                <label for="email">ENTER YOUR GMAIL:</label><br>
                <input type="email" id="email" name="email"><br>
                <label for="phone">Phone Number:</label><br>
                <input type="tel" id="phone" name="phone"><br>
                <label for="country">Country:</label><br>
                <select id="country" name="country">
                    <option value="india">India</option>
                    <option value="usa">USA</option>
                    <option value="uk">UK</option>
                    <option value="australia">Australia</option>
                </select><br>
                <label for="dob">Date of Birth:</label><br>
                <input type="date" id="dob" name="dob"><br>
                <label>Gender:</label><br>
                <input type="radio" id="male" name="gender" value="Male">
                <label for="male">Male</label>
                <input type="radio" id="female" name="gender" value="Female">
                <label for="female">Female</label><br>
                <label for="website">Student's Personal Website (if any):</label><br>
                <input type="url" id="website" name="website"><br>
                <label for="search">Search Your Location:</label><br>
                <input type="search" id="search" name="search"><br>
                <label for="photo">Upload Your Passport Size Photo:</label><br>
                <input type="file" id="photo" name="photo"><br>
                <label for="comments">Additional Comments:</label><br>
                <textarea id="comments" name="comments" rows="4" cols="40"></textarea><br>
                <label for="progress">Application Completion Progress:</label><br>
                <progress id="progress" value="70" max="100">70%</progress><br><br>
                <input type="submit" value="Submit">
                <input type="reset" value="Reset">
            </fieldset>
            <fieldset>
                <legend><h2 style="color: green;">Extra Curricular Activities</h2></legend>
                <input type="checkbox" id="sports" name="activities" value="Sports">
                <label for="sports">Is your son/daughter interested in sports</label><br>
                <input type="checkbox" id="arts" name="activities" value="Arts">
                <label for="arts">Is your son/daughter interested in arts</label><br>
                <input type="checkbox" id="music" name="activities" value="Music">
                <label for="music">Is your son/daughter interested in music</label><br>
            </fieldset>
        </form>
    </div>
</body>
</html>
