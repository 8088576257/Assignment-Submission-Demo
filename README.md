
<!DOCTYPE html>
<head>
    <title>Welcome to HTML</title>
    <style>
        h1{
            color: Red;
        }
        img{
            height: 200px;
            width: 300px;
        }
        #a{
            color: darkslateblue;
            border: 5px solid red;
            border-left-width: 5px;
        }
        .table{
            background-color: lightgreen;
            border: 2px solid black;
        }
        p{
            color: darkblue;
            background-color: beige;
            border: 2px dotted crimson;
        }
    </style>
</head>
    <h1>My first page on HTML</h1>
<body>
    <a href="https://www.google.com/">Click image to open Google<br><img src="Google.jpg"></a><br>
    <p>Table Data</p>
    <table>
        <!--!st row-->
        <tr class="table">
            <th>Name</th>
            <th>Phone no.</th>
            <th>Email</th>
            <th>Location</th>
        </tr>
        <!--2nd row-->
        <tr class="table"> 
            <td>Shreyansh</td>
            <td>9565xxx517</td>
            <td>sh*******@gmail.com</td>
            <td>Lucknow</td>
        </tr>
        <!--3rd row-->
        <tr class="table">
            <td>Rock</td>
            <td>8299****73</td>
            <td>ro******@gmail.coom</td>
            <td>California</td>
        </tr>
        <!--4th row-->
        <tr class="table">
            <td>Anjali</td>
            <td>9452****00</td>
            <td>an******a@gmail.com</td>
            <td>Delhi</td>
        </tr>
        <!--5th row-->
        <tr class="table">
            <td>Soni</td>
            <td>9082****71</td>
            <td>so******a@gmail.com</td>
            <td>Mumbai</td>
        </tr>
    </table>
    <p id="a">Contact for more details</p>
</body>
</html>
