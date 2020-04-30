# tableinfo
display two different table formats
<!DOCTYPE html>
<html>
<head>
 <style>   
table, th, td {
  border: 1px solid black; align:  center;
}
</style>

<style>
  table {
    font-family: arial, sans-serif;
    border-collapse: collapse;
    width: 100%;
  }
  
  td, th {
    border: 1px solid #dddddd;
    text-align: left;
    padding: 8px;
  }
  
  tr:nth-child(even) {
    background-color: #dddddd;
  }
  </style>
</head>
<body>

<table>
  <tr>
    <th><h2>Month</h2></th>
    <th><h2>Savings</h2></th>
    <th><h2>Interest</h2></th>
    <th><h2>Compound</h2></th>
    <th><h2>Time</h2></th>
  </tr>
  <tr>
    <td>January</td>
    <td>$100</td>
    <td>15%</td>
    <td>$15</td>
    <td>2 month</td>
    
  </tr>
  <tr>
    <td>February</td>
    <td>$100</td>
    <td>8%</td>
    <td>$24</td>
    <td>1 month</td>  
  </tr>
   <tr>
    <td>March</td>
    <td>$120</td>
     <td>11%</td>
    <td>$35</td>
     <td>3 month</td>
  </tr>
   <tr>
    <td>April</td>
    <td>$140</td>
      <td>3%</td>
    <td>$28</td>
      <td>1 month</td>
  </tr>
  <tr>
    <td>May</td>
    <td>$160</td>
     <td>3%</td>
    <td>$37</td>
     <td>1 month</td>
  </tr>
   <tr>
    <td>June</td>
    <td>$200</td>
      <td>7%</td>
    <td>$32</td>
       <td>3 month</td>
    
  </tr>
   <tr>
    <td>July</td>
    <td>$240</td>
      <td>9%</td>
    <td>$72</td>
      <td>3 month</td>
   
  </tr>
   <tr>
    <td>August</td>
    <td>$280</td>
      <td>4%</td>
    <td>$39</td>
      <td>2 month</td>
   
  </tr>
   <tr>
    <td>September</td>
    <td>$320</td>
      <td>6%</td>
    <td>$54</td>
       <td>4 month</td>
    
  </tr>
   <tr>
    <td>October</td>
    <td>$360</td>
      <td>6%</td>
    <td>$75</td>
      <td>2 month</td>
    
  </tr>
   <tr>
    <td>November</td>
    <td>$400</td>
      <td>13%</td>
    <td>$84</td>
      <td>3 month</td>
    
    
  </tr>
   <tr>
    <td>December</td>
    <td>$440</td>
      <td>14%</td>
    <td>$98</td>
      <td>1month</td>
   
  </tr>
</table>

<table>
  <body>

    <h2>Contact Table</h2>
    
    <table>
      <tr>
        <th>Company</th>
        <th>Contact</th>
        <th>Country</th>
      </tr>
      <tr>
        <td>Alfreds Futterkiste</td>
        <td>Maria Anders</td>
        <td>Germany</td>
      </tr>
      <tr>
        <td>Centro comercial Moctezuma</td>
        <td>Francisco Chang</td>
        <td>Mexico</td>
      </tr>
      <tr>
        <td>Ernst Handel</td>
        <td>Roland Mendel</td>
        <td>Austria</td>
      </tr>
      <tr>
        <td>Island Trading</td>
        <td>Helen Bennett</td>
        <td>UK</td>
      </tr>
      <tr>
        <td>Laughing Bacchus Winecellars</td>
        <td>Yoshi Tannamuri</td>
        <td>Canada</td>
      </tr>
      <tr>
        <td>Magazzini Alimentari Riuniti</td>
        <td>Giovanni Rovelli</td>
        <td>Italy</td>
      </tr>
    </table>
    
</body>
    </html>
