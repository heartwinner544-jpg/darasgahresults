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
// Normalize names (ignore dots, partials, caps)
function normalize(str){
  return str.toLowerCase().replace(/[^a-z]/g,"");
}

// ================= Complete Results Array 1st–10th =================
const results = [
// ========== 1st Class ==========
{c:"1st",n:"Aisha Shabir",p:"Shabir Ah Mir",sub:["Nazirah Tajweed","Seerat Mubadiyat"],marks:[50,50],maxTotal:100},
{c:"1st",n:"Anam-ul-Haq",p:"Fayaz Ah Gojree",sub:["Nazirah Tajweed","Seerat Mubadiyat"],marks:[35,50],maxTotal:100},
{c:"1st",n:"Irfan Arif",p:"M. Arif Khan",sub:["Nazirah Tajweed","Seerat Mubadiyat"],marks:[20,49],maxTotal:100},
{c:"1st",n:"Farhan Rasheed",p:"Ab Rasheed Mir",sub:["Nazirah Tajweed","Seerat Mubadiyat"],marks:[49,35],maxTotal:100},
{c:"1st",n:"Iram Mukhtiyar",p:"Mukhtiyar Ah Khan",sub:["Nazirah Tajweed","Seerat Mubadiyat"],marks:[32,48],maxTotal:100},
{c:"1st",n:"Afan Ashraf",p:"M. Ashraf Mir",sub:["Nazirah Tajweed","Seerat Mubadiyat"],marks:[47,28],maxTotal:100},
{c:"1st",n:"Ab Wajid Bhat",p:"Towseef Ah Bhat",sub:["Nazirah Tajweed","Seerat Mubadiyat"],marks:[12,45],maxTotal:100},
{c:"1st",n:"Usman Aijaz",p:"Aijaz Ah Khan",sub:["Nazirah Tajweed","Seerat Mubadiyat"],marks:[40,43],maxTotal:100},
{c:"1st",n:"Kulsama Irshad",p:"Irshad Ah Bhat",sub:["Nazirah Tajweed","Seerat Mubadiyat"],marks:[39,45],maxTotal:100},
{c:"1st",n:"Ayan Masood",p:"Masood Ah Mir",sub:["Nazirah Tajweed","Seerat Mubadiyat"],marks:[24,43],maxTotal:100},
// (yahi tarah baki 1st class ke saare students add karne hain)

// ========== 2nd Class ==========
{c:"2nd",n:"Hashim Naseer",p:"Naseer Ah Khawaja",sub:["Nazirah Tajweed","Seerat Mubadiyat"],marks:[48,48],maxTotal:100},
{c:"2nd",n:"Hyder Naseer",p:"Naseer Ah Khawaja",sub:["Nazirah Tajweed","Seerat Mubadiyat"],marks:[46,48],maxTotal:100},
{c:"2nd",n:"Ayan Tariq",p:"Tariq Ah Lone",sub:["Nazirah Tajweed","Seerat Mubadiyat"],marks:[47,42],maxTotal:100},
// (yahi tarah baki 2nd class ke saare students add karne hain)

// ========== 3rd Class ==========
{c:"3rd",n:"Ahtisham-ul-Haq",p:"Fayaz Ah Gojree",sub:["Nazirah Tajweed","Seerat Mubadiyat"],marks:[36,50],maxTotal:100},
// (saare 3rd class ke students add karo)

// ========== 4th Class (4 subjects, 200 marks) ==========
{c:"4th",n:"Aijaz Ah Mir",p:"Showket Ah Mir",sub:["Nazirah","Seerat","Mubadiyat","Tajweed"],marks:[34,48,48,47],maxTotal:200},
// (saare 4th class students add karo)

// ========== 5th Class (4 subjects, 200 marks) ==========
{c:"5th",n:"Moeen ul Islam",p:"M. Shafi Malik",sub:["Nazirah","Seerat","Mubadiyat","Tajweed"],marks:[20,32,17,15],maxTotal:200},
// (saare 5th class students add karo)

// ========== 6th Class (5 subjects,
