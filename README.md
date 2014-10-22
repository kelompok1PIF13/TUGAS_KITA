aTUGAS_KITA
==========
<!DOCTYPE html>
<html>
<title>SIMAK UNSIL</title>
<script src="SpryAssets/SpryMenuBar.js" type="text/javascript"></script>
<link href="SpryAssets/SpryMenuBarHorizontal.css" rel="stylesheet" type="text/css">
<style type="text/css">
body {
	background-image: url(ww.jpg);
}
a:link {
	color: blue;
}
body,td,th {
	color: white;
}

</style>
<style>
      myHero {
        display:block;
        background-color:grey;
        padding: 35px;
        font-size: 30px;
      }  
  </style>
<body bgcolor="black">

<h2>Universitas Siliwangi.</h2>

<myHero>WELCOME IN SILIWANGI OF UNIVERCITY</myHero>
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

<form action=# method=get>
NPM &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp : <input type=text name=nama  ><p>
Password&nbsp&nbsp  : <input type=text name=alamat><p>
<input type=submit value="login" name=submit>
<input type=reset value="ulangi" name=reset>
</form>

<script type="text/javascript">
var MenuBar1 = new Spry.Widget.MenuBar("MenuBar1", {imgDown:"SpryAssets/SpryMenuBarDownHover.gif", imgRight:"SpryAssets/SpryMenuBarRightHover.gif"});
  </script>
</body>
</html>


