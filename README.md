# HTML-Work
<!DOCTYPE html>
<html>
<head>
<style>


body {margin: 0;}


li

.dropdown {
  display: inline-block;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f9f9f9;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
}
.dropdown-content .right {float: right;}

.dropdown-content a {
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  text-align: center;
}

.dropdown-content a:hover {background-color: #f1f1f1;}

.dropdown:hover .dropdown-content {
  display: block;
}

ul.topnav {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: rgb(180, 180, 180);
}

ul.topnav li {float: left;}

ul.topnav li a {
  display: block;
  color: black;
  text-align: center;
  text-decoration: none;
}

ul.topnav li a:hover:not(.active) {text-decoration: underline;}

ul.topnav li a.active { }

ul.topnav li.right {float: right;}

@media screen and (max-width: 600px) {
  ul.topnav li.right,
  ul.topnav li {float: none;}
}
</style>
</head>
<body>

<ul class="topnav">
<bre>
  <li> <a href="#REFINITIV<sup>TM</sup>">REFINITIV<sup>TM</sup> </a>
  <a href="#PRICEIT ONLINE">PRICEIT ONLINE</a>
  </li>
  </bre>
  <li style="padding: 14px 16px"><a href="#MONITORING">MONITORING</a></li>
  <li style="padding: 14px 16px"><a href="#REPORTING">REPORTING</a></li>
  <li style="float:right;padding:10px 50px 10px 10px;"
     class="dropdown">
    <a  href="javascript:void(0)"> Viktor Melnyk</a>
    <div class="dropdown-content">
      <a href="#">Settings</a>
      <a href="#">Legal Entities</a>
      <a href="#">User Account</a>
      <a href="#">Help</a>
      <a href="#">Log out</a>
    </div>
  </li>
      </ul>
    <p style="margin:0";
    class="color:green">reporting works.</p>

</body>
</html>
