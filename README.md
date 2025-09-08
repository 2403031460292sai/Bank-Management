# Bank-Management
abcd
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MyBank - Dashboard</title>
</head>
<body bgcolor="#f5f7fa" text="#333">

  <!-- Header -->
  <table width="100%" bgcolor="#004080" cellpadding="15">
    <tr>
      <td align="left">
        <font color="white" size="6"><b>MyBank</b></font>
      </td>
      <td align="right">
        <a href="#" style="color:white; text-decoration:none; margin:10px;">Home</a>
        <a href="#" style="color:white; text-decoration:none; margin:10px;">Accounts</a>
        <a href="#" style="color:white; text-decoration:none; margin:10px;">Transactions</a>
        <a href="#" style="color:white; text-decoration:none; margin:10px;">Customers</a>
        <a href="#" style="color:white; text-decoration:none; margin:10px;">Logout</a>
      </td>
    </tr>
  </table>

  <!-- Customer Details -->
  <h2 align="center"><font color="#004080">Customer Details</font></h2>
  <table border="1" width="80%" align="center" cellspacing="0" cellpadding="10">
    <tr bgcolor="#004080">
      <th><font color="white">Customer ID</font></th>
      <th><font color="white">Name</font></th>
      <th><font color="white">Account Number</font></th>
      <th><font color="white">Balance</font></th>
    </tr>
    <tr align="center" bgcolor="white">
      <td>101</td><td>Rahul Sharma</td><td>1234567890</td><td>₹85,000</td>
    </tr>
    <tr align="center" bgcolor="#f9f9f9">
      <td>102</td><td>Priya Verma</td><td>1234567891</td><td>₹1,20,500</td>
    </tr>
    <tr align="center" bgcolor="white">
      <td>103</td><td>Amit Kumar</td><td>1234567892</td><td>₹55,300</td>
    </tr>
    <tr align="center" bgcolor="#f9f9f9">
      <td>104</td><td>Sneha Patil</td><td>1234567893</td><td>₹2,15,000</td>
    </tr>
  </table>

  <!-- Transactions -->
  <h2 align="center"><font color="#004080">Recent Transactions</font></h2>
  <table border="1" width="90%" align="center" cellspacing="0" cellpadding="10">
    <tr bgcolor="#004080">
      <th><font color="white">Transaction ID</font></th>
      <th><font color="white">Customer</font></th>
      <th><font color="white">Type</font></th>
      <th><font color="white">Amount</font></th>
      <th><font color="white">Date</font></th>
      <th><font color="white">Status</font></th>
    </tr>
    <tr align="center" bgcolor="white">
      <td>T001</td><td>Rahul Sharma</td><td>Credit</td><td>₹15,000</td><td>05 Sep 2025</td><td><font color="green"><b>Success</b></font></td>
    </tr>
    <tr align="center" bgcolor="#f9f9f9">
      <td>T002</td><td>Priya Verma</td><td>Debit</td><td>₹5,000</td><td>04 Sep 2025</td><td><font color="green"><b>Success</b></font></td>
    </tr>
    <tr align="center" bgcolor="white">
      <td>T003</td><td>Amit Kumar</td><td>Debit</td><td>₹12,000</td><td>03 Sep 2025</td><td><font color="red"><b>Failed</b></font></td>
    </tr>
    <tr align="center" bgcolor="#f9f9f9">
      <td>T004</td><td>Sneha Patil</td><td>Credit</td><td>₹25,000</td><td>01 Sep 2025</td><td><font color="green"><b>Success</b></font></td>
    </tr>
  </table>

  <!-- Footer -->
  <table width="100%" bgcolor="#004080" cellpadding="15" style="margin-top:20px;">
    <tr>
      <td align="center">
        <font color="white">&copy; 2025 MyBank. All rights reserved.</font>
      </td>
    </tr>
  </table>

</body>
</html>
