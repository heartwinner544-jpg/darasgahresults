<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Darasgah Result Portal</title>
<style>
body{font-family:Arial,sans-serif;padding:20px;background:#f5f5f5;}
h2{text-align:center;color:#2e6da4;}
select,input,button{padding:8px;margin:5px 0;width:100%; max-width:300px;}
#output{margin-top:20px;padding:15px;background:white;border-radius:8px;box-shadow:0 0 5px rgba(0,0,0,0.1);}
table{width:100%;border-collapse:collapse;margin-top:10px;}
th,td{border:1px solid #ccc;padding:8px;text-align:center;}
th{background:#2e6da4;color:white;}
.pass{color:green;font-weight:bold;}
.fail{color:red;font-weight:bold;}
</style>
</head>
<body>

<h2>Darasgah Result Portal</h2>

<label>Class:</label>
<select id="classSelect">
  <option value="">Select Class</option>
  <option>1st</option>
  <option>2nd</option>
  <option>3rd</option>
  <option>4th</option>
  <option>5th</option>
  <option>6th</option>
  <option>7th</option>
  <option>8th</option>
  <option>10th</option>
</select>

<label>Student Name:</label>
<input type="text" id="studentName" placeholder="Type Student Name">

<label>Parent Name:</label>
<input type="text" id="parentName" placeholder="Type Parent Name">

<button onclick="findResult()">Search Result</button>

<div id="output"></div>

<script>
// Normalize names (ignore dots, 
