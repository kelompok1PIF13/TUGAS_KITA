aTUGAS_KITA
==========
<!DOCTYPE html>
<html>
<script src="SpryAssets/SpryMenuBar.js" type="text/javascript"></script>
<link href="SpryAssets/SpryMenuBarHorizontal.css" rel="stylesheet" type="text/css">
<style type="text/css">
body {
	background-image: url(pmb.jpg);
}
a:link {
	color: #ffffff;
}
body,td,th {
	color: #ff0000;
}
</style>
<body bgcolor="#ff0000">

<h1>WELCOME IN SILIWANGI OF UNIVERSITY</h1>

<p>Siliwangi University.</p>
<ul id="MenuBar1" class="MenuBarHorizontal">
  <li><a href="#">Beranda</a>  </li>
  <li><a href="#" class="MenuBarItemSubmenu">PMB Online</a>
    <ul>
      <li><a href="#">Panduan Pendaftaran</a></li>
      <li><a href="#" class="MenuBarItemSubmenu">Program</a>
        <ul>
          <li><a href="#">Diploma (D3)</a></li>
          <li><a href="#">Sarjana (S1)</a></li>
          <li><a href="#">Pascasarjana (S2)</a></li>
        </ul>
      </li>
      <li><a href="#">Cara Registrasi</a></li>
    </ul>
  </li>
  <li><a class="MenuBarItemSubmenu" href="#">Informasi</a>
    <ul>
      <li><a class="MenuBarItemSubmenu" href="#">Hasil PMB</a>
        <ul>
          <li><a href="#">Item 3.1.1</a></li>
          <li><a href="#">Item 3.1.2</a></li>
        </ul>
      </li>
</ul>
  </li>
  <li><a href="#">Monitoring</a></li>
  <li><a href="#">Akademik</a></li>
  <li><a href="#">F.A.Q</a></li>
  <li><a href="#">Hubungi</a></li>
</ul>
<p>&nbsp; </p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<form name="form1" method="post" action="">
  <p>NPM : 
    <label for="textfield2"></label>
  <input type="text" name="textfield" id="textfield2">
</p>
  <p>Password : 
    <label for="textfield3"></label>
    <input type="text" name="textfield2" id="textfield3">
  </p>
<p>&nbsp;</p>
<script type="text/javascript">
var MenuBar1 = new Spry.Widget.MenuBar("MenuBar1", {imgDown:"SpryAssets/SpryMenuBarDownHover.gif", imgRight:"SpryAssets/SpryMenuBarRightHover.gif"});
  </script>
</body>
</html>
