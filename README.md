# DIY-Fitness-Tracker

<!-- index.jsp -->
<!DOCTYPE html>
<html lang="en">
<head>
<style>
body {
margin: 0;
}
form {
margin: 0;
align-items: center;
}
input {
padding: 5px;
}
table,
tr,
td {
padding: 200px;
}
.header {
margin: 0 auto;
}
button {
padding: 20px;
background-color: black;
color: white;
}
</style>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Item Profit Calculator</title>
</head>
<body>
<center><h1>ENTER ITEM DETAILS</h1><br>
<form action="calculateProfit.jsp" method="post">
<h2><label for="itemName">Item Name:</label></h2>
<h2><input type="text" id="itemName" name="itemName"
required><br></h2><br>
<h2><label for="itemId">Item ID:</label></h2>
<h2><input type="text" id="itemId" name="itemId"
required><br></h2><br>
<h2><label for="itemCost">Item Cost:</label></h2>
<h2><input type="number" id="itemCost" name="itemCost"
required><br></h2><br>
<h2><label for="sellingPrice">Selling Price:</label></h2>
<h2><input type="number" id="sellingPrice" name="sellingPrice"
required><br></h2><br>
<button type="submit">Calculate Profit</button>
</form></center>
</body>
</html>
