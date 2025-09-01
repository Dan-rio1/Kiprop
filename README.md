<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

</head>
<body>
    <form action="/register" method="post" novalidate>
        <h1>User Registration Form</h1>
    
        <fieldset>
            <legend>Personal Information</legend>
            <div class="form-group">
                <label for="firstname">First Name:</label> 
                <input type="text" id="firstname" name="firstname">
                
            </div>
            <div class="form-group">
                <label for="lastname">Last Name:</label> 
                <input type="text" id="lastname" name="lastname">

            </div>
            <div class="form-group">
                <label for="birthdate">Date of Birth:</label> 
                <input type="date" id="birthdate" name="birthdate">

            </div>
            <div class="form-group">
                <label for="age">Age:</label> 
                <input type="number" id="age" name="age">

            </div>
            <div class="form-group">
                <label for="gender">Gender:</label><br>
                <input type="radio" id="gender" name="gender" value="Male"> 
                <label for="male">Male</label><br>
                <input type="radio" id="gender" name="gender" value="female"> 
                <label for="female">Female</label>

            </div>
            <div class="form-group">
                <label for="profilephoto">Profile Photo:</label> 
                <input type="file" id="profilephoto" name="profilephoto">

            </div>
        </fieldset>
        <fieldset>
            <legend>Contact & Address Information</legend>
            <div class="form-group">
                <label for="emailaddress">Email Address:</label> 
                <input type="text" id="emailaddress" name="emailaddress">

            </div>
            <div class="form-group">
                <label for="phonenumber">Phone Number:</label> 
                <input type="number" id="phonenumber" name="phonenumber">

            </div>
            <div class="form-group">
                <label for="personalwebsite">Personal Website:</label> 
                <input type="text" id="personalwebsite" name="personalwebsite" placeholder="https://example.com">

            </div>
            <div class="form-group">
                <label for="streetaddress">Street Address:</label> 
                <input type="text" id="streetaddress" name="streetaddress">

            </div>
            <div class="form-group">
                <label for="city">City:</label> <input type="text" id="city" name="city">

            </div>
            <div class="form-group">
                <label for="country">Country:</label>
                <select name="selectcountry" id="selectcountry">
                    <option value="ke">Kenya</option>
                    <option value="ug">Uganda</option>
                    <option value="tz">Tanzania</option>
                    <option value="sa">South Africa</option>
                </select>
                

            </div>
            <div class="form-group">
                <label for="zip/postalcode">Zip/Postal Code</label> 
                <input type="number" id="zip/postalcode" name="zip/postalcode">

            </div>
            <div class="form-group">
                <label for="preferencecontacttime">Preference Contact Time:</label> 
                <input type="time" id="preferencecontacttime" name="preferencecontacttime">

            </div>
        </fieldset>
        <fieldset>
            <legend>Preferences & Interests</legend>
            <div class="form-group">
                <label for="favoritecolor">Fvourite Color:</label> 
                <input type="color" id="favouritecolor" name="favouritecolor" value="#FF0000">

            </div>
            <div class="form-group">
                <label for="experiencelevel">Experience Level(1-10)</label>
                <input type="range" id="experiencelevel" name="experiencelevel" min="1" max="10" value="5">

            </div>
            <div class="form-group">
                <label for="birthmonth">Birth Month:</label>
                <input type="month" id="birthmonth" name="birthmonth">

            </div>
            <div class="form-group">
                <label for="availableweek">Available Week:</label>
                <input type="week" id="availableweek" name="availableweek">

            </div>
            <div class="form-group">
                <label for="keywords">Search Keywords:</label>
                <input type="text" id="keywords" name="keywords" placeholder="Enter keywords">

            </div>
            <div class="form-group">
                <label for="interests">Interests(Select all that apply):</label><br>
                <input type="checkbox" id="interests" name="interests" value="Technology">
                <label for="technology">Technology</label><br>
                <input type="checkbox" id="interests" name="interests" value="sports">
                <label for="sports">Sports</label><br>
                <input type="checkbox" id="interests" name="interests" value="travel">
                <label for="travel">Travel</label><br>
                <input type="checkbox" id="interests" name="interests" value="music">
                <label for="music">Music</label><br>
                <input type="checkbox" id="interests" name="interests" value="reading">
                <label for="reading">Reading</label><br>
                <input type="checkbox" id="interests" name="interests" value="cooking">
                <label for="cooking"> Cooking</label>


            </div>
            <div class="form-group">
                <label for="educationlevel">Education Level:</label>
                <select name="educationlevel" id="select-education-level">
                    <option value="Primary-school">Primary School</option>
                    <option value="secondary">Secondary School</option>
                    <option value="degree">Bachelor's Degree</option>
                    <option value="masters">Masters</option>
                </select>

            </div>
            <div class="form-group">
                <label for="password">Create Password:</label>
                <input type="text" id="password" name="Password">

            </div>
            <div class="form-group">
                <label for="password">Confirm Password:</label>
                <input type="text" id="password" name="password">

            </div>
        </fieldset>
        <fieldset>
            <legend>Feedback & Additional Information</legend>
            <div class="form-group">
                <label for="about">Tell us about yourself:</label><br>
                <textarea name="about" id="about" placeholder="Write-a brief introduction about yourself..."></textarea>

            </div>
            <div class="form-group">
                <label for="suggestions">Suggestions for improvement:</label><br>
                <textarea name="suggestions" id="suggestions" placeholder="Any-suggestions-or-feedback..."></textarea>

            </div>
            <div class="form-group">
                <label for="registration">Registration Date &Time:</label>
                <input type="datetime" id="registration" name="registration">

            </div>
            <div class="form-group">
                <label for="about">How did you hear about us?</label>
                <select name="about" id="about">
                    <option value="facebook">Facebook</option>
                    <option value="twitter">Twitter</option>
                    <option value="intagram">Instagram</option>
                    <option value="friend">Friend</option>
                </select>

            </div>
            <div class="form-group">
                <label for="upload">Upload Resume(Optional)</label>
                <input type="file" id="upload" name="upload">

            </div>
            <div class="form-group">
                <input type="checkbox" id="subscribe" name="subscribe">
                <label for="subscribe">Subscribe to our newsletter</label><br>
                <input type="checkbox" id="terms" value="terms">
                <label for="terms">I agree to the Terms and Conditions</label><br>
                <input type="checkbox" id="privacy" value="privacy">
                <label for="privacy">I agree to the Privacy Policy</label>

            </div>
        </fieldset>
        <div class="form-action">
            <button type="register">Register</button>
            <button type="clear">Clear Form</button>

        </div>
        
    </form>
    
</body>
</html>
