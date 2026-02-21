# Link

Implementasi Style sheet juga memungkinkan anda mengubah penampilan link (teks yang diklik oleh user untuk lompat ke halaman lain)

● a:link menunjukan 
● a:visited menunjukan link yang telah diklik / kunjungi oleh user
● a:hover menunjukan link ketika dilewati user
● a:active menunjukan link ketika memperoleh focus

```
<HTML> 
	<HEAD> 
		<TITLE> Link Pseudo Class </TITLE> 
		<style>
			<!-- CSS -->
			a:link {color: blue;} 
			a:visited {color: red;} 
			a:hover {color: white;}
			a:active {color: yellow;}
			  
			.header {
			  padding: 10px 10px 10px 10px;
			  background-color: #33090D;
			  color: white;
			}
 		</style>
	</HEAD>

	<body>
	<div class=header>
	<h1>STMIK Kian Santang</h1>
	  <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Tentang Kami</a></li>
        <li><a href="#">Kontak Kami</a></li>
      </ul>
	</div>
	</body>
</HTML>
```

Kita dapat mengatus sejumlah properti teks pada class-class, teks-align, teks-decoration, teks-indent, text-transform.

# Output



