# index.html
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <center><div>
    <h1><center>Employee Registration Form</center></h1>
    <form action="www.Example.com">
        <center><input type="radio" name="Gender" checked>Mr.<input type="radio" name="Gender">Mrs.<input type="radio" name="Gender">Ms.</center>
        <table >
        <tr>
            <td><label for="First Name">First Name</label></td>
            <td><input type="text" placeholder="First Name"></td>
        </tr>
        <tr>
            <td><label for="Last Name">Last Name</label></td>
            <td><input type="text" placeholder="Last Name"></td>
        </tr>
        <tr>
            <td><label for="Mail Address1">Mail Address1</label></td>
            <td><input type="Email"></td>
        </tr>
        <tr>
            <td><label for="Mail Address2">Mail Address2</label></td>
            <td><input type="email"></td>
        </tr>
        <tr>
            <td><label for="City">City</label></td>
            <td><input type="text"></td>
        </tr>
        <tr>
            <td><label for="State">State</label></td>
            <td><select name="State" id="State">
                <option value="kar">karachi</option>
                <option value="lhr">Lahore</option>
                <option value="mul">Multan</option>
                <option value="Phr">Peshawar</option>
                <option value="kpk">Khyber Pakhtunkhuwa</option>
                <option value="Qt">Quetta</option></td>
        </tr>
        <tr>
            <td><label for="Zip">Zip</label></td>
            <td><input type="text"></td>
        </tr>
        <tr>
            <td><label for="Upload Photo">Upload Photo</label></td>
            <td><input type="file"></td>
        </tr>
        <tr>
            <td><label for="E-Mail">E-Mail</label></td>
            <td><input type="text"></td>
        </tr>
        <tr>
            <td><label for="Mobile">Mobile</label></td>
            <td><input type="tel" placeholder="+92"></td>
        </tr>
        <tr>
            <td><label for="Languages Known">Languages Known</label></td>
            <td><input type="checkbox" checked>English <br>
                <input type="checkbox">Urdu <br>
                <input type="checkbox">Hindi <br>
                <input type="checkbox">Spanish</td>
        </tr>
        <tr>
            <td><label for="Additional information">Additional information</label></td>
            <td><textarea name="Additional information" id="Additional information" placeholder="Optional"></textarea></td>
        </tr>
    </table>
    <button>Sumbit</button> <button>Reset</button>
    </form>
    </div></center>
</body>
</html>
