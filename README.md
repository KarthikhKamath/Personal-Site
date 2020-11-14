<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Forms</title>
</head>
<h1>Form</h1>

<body>
    <form action="backend.php"></form>
    <!-- here name means the data that backend gets from these inputs -->

    <br><label for="name"> Name</label>
    <div> <input type="text" name="user name" id="name"></div>
    <br>
    <div> Class:<input type="number" name="user class"></div>
    <br>
    <div>Roll Number:<input type="number"></div>
        <br>
        <div>DOB:<input type="date" name= "birth date"></div>
        <br>
        <div>Gender: Male<input type="radio" name="gender">Female<input type="radio" name="gender">Other<input type="radio" name="gender"></div>
            <br>
            <div>Email: <input type="email" name=" email"></div>
            <br>
            <div>Eligible: <input type="checkbox" name="Eligibility"></div>
            <br>
            <br>
            <input type="submit" name="submit">
            
            
            <input type="reset" name="reset Now">
</body>
                       
</html>
