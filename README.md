[Company Registration Form.html](https://github.com/user-attachments/files/33679057/Company.Registration.Form.html)
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Company Registration Form</title>
</head>
<body>

    <h1>Company Registration Form</h1>
    <p>Please fill in the form below to register your company.</p>

    <form action="#" method="post">

        <fieldset>
            <legend>Company Information</legend>

            <label for="companyName">Company Name:</label><br>
            <input type="text" id="companyName" name="companyName"
                   value="Teresa Tech Solutions"
                   required minlength="2">
            <br><br>

            <label for="registrationNumber">Registration Number:</label><br>
            <input type="text" id="registrationNumber"
                   name="registrationNumber"
                   value="CPR/2026/123456" required>
            <br><br>

            <label for="companyType">Company Type:</label><br>
            <select id="companyType" name="companyType" required>
                <option value="">-- Select Company Type --</option>
                <option value="sole-proprietorship">Sole Proprietorship</option>
                <option value="partnership">Partnership</option>
                <option value="limited-company" selected>Limited Company</option>
                <option value="other">Other</option>
            </select>
            <br><br>

            <label for="businessEmail">Company Email:</label><br>
            <input type="email" id="businessEmail"
                   name="businessEmail"
                   value="info@teresatech.example" required>
            <br><br>

            <label for="phone">Phone Number:</label><br>
            <input type="tel" id="phone" name="phone"
                   value="0100320708"
                   pattern="[0-9+() -]{10,15}"
                   title="Enter a valid phone number."
                   required>
            <br><br>

            <label for="address">Company Address:</label><br>
            <textarea id="address" name="address"
                      rows="4" cols="35" required>Nakuru, Kenya</textarea>
            <br><br>

        </fieldset>

        <br>

        <fieldset>
            <legend>Owner Information</legend>

            <label for="ownerName">Full Name of Owner:</label><br>
            <input type="text" id="ownerName" name="ownerName"
                   value="Teresa Wachira"
                   required minlength="2">
            <br><br>

            <label for="ownerEmail">Owner's Email:</label><br>
            <input type="email" id="ownerEmail"
                   name="ownerEmail"
                   value="teresa@example.com" required>
            <br><br>

            <label for="ownerPhone">Owner's Phone Number:</label><br>
            <input type="tel" id="ownerPhone" name="ownerPhone"
                   value="0100320708"
                   pattern="[0-9+() -]{10,15}"
                   title="Enter a valid phone number."
                   required>
            <br><br>

        </fieldset>

        <br>

        <input type="checkbox" id="declaration"
               name="declaration" required>

        <label for="declaration">
            I confirm that the information provided is correct.
        </label>

        <br><br>

        <button type="submit">Register Company</button>
        <button type="reset">Clear Form</button>

    </form>

</body>
</html>
```
