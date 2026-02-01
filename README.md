<html lang="en">
<head>
<meta charset="utf-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1"/>
<title>Academic Transcript — Fall 2025</title>

<style>
:root{
  --green:#005239;
  --line:#d9dee7;
  --soft:#f6f8fb;
  --text:#111;
}

body{
  margin:0;
  font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Helvetica,Arial;
  background:#f3f6f5;
  color:var(--text);
}

.sheet{
  max-width:1000px;
  margin:30px auto;
  background:white;
  border-radius:14px;
  box-shadow:0 20px 60px rgba(0,0,0,.08);
  overflow:hidden;
  position:relative;
}

/* watermark */
.sheet::before{
  content:"";
  position:absolute;
  inset:0;
  background:url("logo.png") center 45%/520px no-repeat;
  opacity:.05;
}

.header{
  background:linear-gradient(90deg,var(--green),#0a7a3c);
  color:white;
  padding:18px 24px;
  display:flex;
  justify-content:space-between;
  align-items:center;
}

.header img{
  height:46px;
}

button{
  background:rgba(255,255,255,.15);
  border:1px solid rgba(255,255,255,.25);
  color:white;
  padding:8px 12px;
  border-radius:8px;
  cursor:pointer;
}

.content{ padding:22px; }

.section-title{
  font-weight:700;
  margin:16px 0 8px;
}

.grid{
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:10px;
  margin-bottom:20px;
}

.box{
  border:1px solid var(--line);
  border-radius:10px;
  padding:10px;
  background:var(--soft);
}

.k{font-size:12px;color:#666}
.v{font-weight:700}

table{
  width:100%;
  border-collapse:collapse;
}

th,td{
  padding:12px;
  border-bottom:1px solid var(--line);
  text-align:left;
  font-size:14px;
  color:#111;
}

th{ background:#eef2f7; }

.footer{
  font-size:12px;
  color:#666;
  margin-top:14px;
}

@media print{
  button{display:none}
}

@media(max-width:800px){
  .grid{grid-template-columns:1fr}
}
</style>
</head>

<body>

<div class="sheet">

  <div class="header">
    <div style="display:flex;align-items:center;gap:12px">
      <img src="logo.png">
      <div>
        <b>George Mason University</b><br>
        <small>Office of the Registrar • Academic Transcript (Unofficial Copy)</small>
      </div>
    </div>
    <button onclick="window.print()">Print / Save PDF</button>
  </div>

  <div class="content">

    <div class="section-title">Student Information</div>
    <div class="grid">
      <div class="box"><div class="k">Name</div><div class="v">Junjie Song</div></div>
      <div class="box"><div class="k">G-Number</div><div class="v">G086619</div></div>
      <div class="box"><div class="k">College</div><div class="v">CEC – College of Engineering and Computing</div></div>
      <div class="box"><div class="k">Major</div><div class="v">Computer Science</div></div>
      <div class="box"><div class="k">Track</div><div class="v">Cybersecurity</div></div>
      <div class="box"><div class="k">Term</div><div class="v">Fall 2025</div></div>
    </div>

    <div class="section-title">Term Summary</div>
    <div class="grid">
      <div class="box"><div class="k">Term GPA (4.0)</div><div class="v">3.67</div></div>
      <div class="box"><div class="k">Credits Earned</div><div class="v">18</div></div>
      <div class="box"><div class="k">Courses</div><div class="v">6</div></div>
    </div>

    <div class="section-title">Coursework</div>
    <table>
      <tr><th>Course</th><th>Credits</th><th>Grade</th><th>Quality Points</th></tr>
      <tr><td>ENGH 302</td><td>3</td><td>A-</td><td>11.1</td></tr>
      <tr><td>CS 362</td><td>3</td><td>A</td><td>12.0</td></tr>
      <tr><td>CS 405</td><td>3</td><td>A</td><td>12.0</td></tr>
      <tr><td>CS 302</td><td>3</td><td>B+</td><td>9.9</td></tr>
      <tr><td>MATH 401</td><td>3</td><td>A-</td><td>11.1</td></tr>
      <tr><td>IT 309</td><td>3</td><td>B+</td><td>9.9</td></tr>
    </table>

    <div class="footer">
      Personal unofficial transcript • For private viewing only
    </div>

  </div>
</div>

</body>
</html>
