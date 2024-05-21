<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form</title>
</head>
<body><h1>The form</h1>
    <form action="http://www.google.com">
        
        Name:
        <input type="text" name="" id="" placeholder="harry" required maxlength="10" autocomplete="off">
        <br>
        password:
        <input type="password" value="12064523" readonly>
        <br>
        Email: <input type="email" value="ranahari836@gmail.com" disabled>
        <br>
        favourite palce:
        <input type="checkbox">kathmandu
        <input type="checkbox">pokhara
        <input type="checkbox">dhangadhi
        <br>
        gender:
        <input type="radio" name="gender"> male
        <input type="radio" name="gender"> female
        <input type="radio" name="gender"> other
        <br>
        Age:
        <input type="number" max="30" min="20">
        <br>
        <input type="date">
        <br>
        <input type="number">
        <br>
        <input type="file" name="" id="" accept="image/*">
        <br>
        <input type="file" name="" id="" multiple>
        <br>
        <select>
            <option value="">kathmandu</option>
            <option value=""> pokhara</option>
            <option value="">dhangadhi</option>
        </select>
       
        <br>
        <textarea name="" id="">comment here</textarea>
        <br>
        <input type="submit" value="click">
    </form>
    
</body>
</html>