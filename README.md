# Website



      <!DOCTYPE html>
<html lang="en">
<head>
    
    <title>Details</title>
</head>
<body>
    <form action="usermessage.html">
        <fieldset>
            <legend>Personal Details</Details></legend>
        <label for="FName">FName</label>
        <input type="text"  required placeholder="Ex:sachin" id="Fname" name="Fname">
       <br><br>

        <label for="LName">LName</label>
        <input type="text"  required placeholder="Ex:sharma" id="Lname" name="Lname">
       <br><br>

        <label for="Age">Age</label>
        <input type="Number" placeholder="Ex:18-60" id="age" name="age">
       <br><br>

        <label for="Email">Email</label>
        <input type="text" id="Email" name="Email">
        <br><br>

        <label for="Contact">Contact</label>
        <input type="text"  required id="contact" name="contact" pattern="[6-9]{1}[0-9]{9}">

        <br><br>
    </fieldset>
        <input type="submit">
    
</body>
</html>
