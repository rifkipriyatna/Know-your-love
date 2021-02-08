<html >
<head>
				<title>Judul halaman</title>
				<link rel="stylesheet" href=" javaript.css">
				<style>
								body{
				background-color:gainsboro;
}

.judul{
				position:absolute;
				left:0;
				right:0;
				top:0;
				background-color:#e8491d;
				padding:7px;
}

.jud{
				text-align:center;
				font-size:20px;
				color:white;
				margin-top:10px;
				font-family:cursive,"Brush Script MT";
}

.boy{
				width:30px;
				height:30px;
				border-radius:60px;
				margin-top:-30px;
			  float:right;
}

.tombol{
				margin-left:20px;
				margin-top:-45px;
				display:flex;
				justify-content:space-between;
				flex-direction:column;
				width:22px;
				height:22px;
				background-color:#e8491d;
}

.tombol span{
				width:16px;
				height:3px;
				background-color:white;
				display:block;
				margin-right:10px;
				margin-left:-5px;
}

.mulai{
				margin-top:px;
				text-decoration:none;
				border:none;
				position:absolute;
				left:47%;
				margin-top:100px;
				margin-left:px;
				color:white;
 font-size:15px;
				background:none;
				
				
}
.luv{
				background-color:#ff5e00;
				text-align:center;
				padding:20px;
				color:white;
				
				margin-left:-20px;
				margin-right:-9px;
				
}

.isi{
				background-color:#ff5e00;
				text-align:center;
				color:white;
				padding:20px;
				margin-left:-20px;;
				margin-right:-9px;
				margin-top:-20px;
				font-size:11px;
				
}

.header{
				background-color:#ff5e00;
				margin-top:-85px;
				border-radius:0px 0px 0px 0px;
				margin-left:%;
}

.lope{
				font-size:140px;		
				margin-left:27%;	
}

.hr{
				padding:3px;
				margin-left:-20px;
				margin-right:-9px;
				margin-top:-10px;
}

.hrr{
				padding:3px;
				margin-right:-9px;
				margin-left:-20px;
				
}

.sosmed{
				background-color:#ff5e00;
				color:white;	
				position:absolute;
				left:0;
				right:0;
				text-align:center;
}

.sosmed ul li{
				display:inline-block;
				justify-content:space-between;
}

.fb{
				width:30px;
				height:30px;
				text-decoration:none;
				border-radius:50px;
				margin-left:-250px;
				margin-top:-25px;
}

.ig{
				width:30px;
				height:30px;
				text-decoration:none;
				border-radius:50px;
				margin-left:-150px;
				margin-top:-25px;
}

.wa{
				width:30px;
				height:30px;
				text-decoration:none;
				border-radius:50px;
				margin-right:-180px;
				margin-top:-25px;
}

.gm{
				width:30px;
				height:30px;
				text-decoration:none;
				border-radius:50px;
				margin-right:-60px;
				margin-top:-25px;
}

.yt{
				width:30px;
				height:30px;
				text-decoration:none;
				border-radius:50px;
				margin-left:-50px;
				margin-top:-25px;
}

.sos{
				font-size:13px;
}

				</style>
</head>
<body>
				<div class="judul">
							  <h3 class="jud">Know Your Love</h3>
							  <div class="toggle">
							  				<button class="tombol">
							  				<span></span>
							  				<span></span>
							  				<span></span>
							  				</button>
							  </div>	
				</div>
				<br><br>
				<div class="header">
				<p class="luv">Selamat Datang di KNOW YOUR LOVE</p>
				<p class="isi">Know Your Love adalah sebuah website yang bisa mengetahui carachter jodoh mu dengan memasukan bulan lahir seseorang,Cara penggunaanya adalah klik mulai lalu isi sesuai bulan lahir anda,selesai</p>
				</div>
				<hr class="hr">
				<p class="lope">🖤
				<button onclick="myFunction()" class="mulai">Mulai</button></p>
				<hr class="hrr">
				<div class="sosmed">
				<p class="sos">Create:6  Februari 2021</p>
				<br>
				<ul>
								<li><a href="https://www.facebook.com/profile.php?id=100011548591895"><img src="https://raw.githubusercontent.com/rifkipriyatna/test/main/fb.png"  class="fb"></a></li>
								<li><a href="https://www.instagram.com/invites/contact/?i=8z0pugk0jumb&utm_content=3f70xoh"><img class="ig" src="https://raw.githubusercontent.com/rifkipriyatna/test/main/ig.jpeg"></a></li>
							<li><a href="https://youtube.com/channel/UCVYoaKAPM9-4IlNA91fpUVg"><img class="yt" src="https://raw.githubusercontent.com/rifkipriyatna/test/main/ty.jpeg"></a></li>
						<li><a href="https://www.priyatnarifki@gmail.com"><img class="gm" src="https://raw.githubusercontent.com/rifkipriyatna/test/main/gmail.png"></a></li>
							<li> <a href="https://wa.me/qr/PFZ5F7WWOLIOE1">	<img class="wa" src="https://raw.githubusercontent.com/rifkipriyatna/test/main/wa.jpg"></a></li></ul>
				
				<script> 
								function myFunction(){
								var jawab = prompt("Masukan Bulan Lahir Kamu Dengan Huruf KAPITAL");
								 var hadiah = ""; switch(jawab){ case "JANUARI": hadiah = " memiliki kepribadian yang kuat dan ambisius Pasanganmu akan selalu percaya jika kamu mampu mengubahnya menjadi orang yang lebih baik"; 
								 break; case "FEBRUARI": hadiah = " sosok yang penuh dengan semangat Bahkan kamu tidak bisa berlama-lama diam dan tidak melakukan kegiatan apa pun. Karena kamu menyukai sesuatu hal baru, kamu selalu mengajak pasanganmu untuk melakukan beberapa kegiatan agar hubunganmu tidak membosankan."; 
								 break; case "MARET": hadiah = " sosok yang emosional dan penuh kasih sayang Pasanganmu akan merasa bahagia saat berada bersamamu, karena kamu termasuk orang yang selalu berjuang dan tidak pernah menyerah ketika mengadapi masalah.";
								 break; case "APRIL": hadiah = " Sosok orang yang ramah dan menyenangkan lahir di bulan April Kamu tidak pernah terburu-buru dalam menjalin sebuah hubungan karena kamu tidak ingin terluka."; 
								 break; case "MEI": hadiah = " tipe manusia yang selalu menginspirasi banyak orang Dalam persoalan asmara, kamu selalu menginginkan pasangan yang bisa diandalkan.";
							  break; case "JUNI": hadiah = " dia selalu dicintai banyak orang karena sikapnya yang romantis Namun sifatnya yang pencemburu sering kali membuatnya menjadi buta.";
							  break; case "JULI": hadiah = " seseorang yang terlihat mandiri Bahkan sulit bagi pasanganmu untuk menarik perhatianmu Orang yang terlahir di bulan Juli rela melajang jika tidak mendapatkan pasangan yang sempurna. ";
							  break; case "AGUSTUS": hadiah = " memiliki selera humor yang tinggi Pasangan yang mendapatkanmu akan merasa sangat beruntung, karena kamu adalah orang yang menyenangkan";
							  break; case "SEPTEMBER": hadiah = " orang yang terlahir di bulan ini akan mengharapkan seorang pasangan yang cerdas dan berkomitmen.";
							  break; case "OKTOBER": hadiah = " orang yang mengumbar aura positif, walaupun terkadang muncul sifat keras kepalamu Namun itu tak jadi masalah, siapapun lawan jenis yang melihat senyumanmu akan selalu menaruh hati kepadamu.";
							  break; case "NOVEMBER": hadiah = " selalu melakukan sesuatu yang membuat pasanganmu bahagia dan merasa puas karena kamu sosok orang yang jujur Ini sangat intuitif, kamu tahu kapan waktu yang tepat untuk berbuat sesuatu";
							  break; case "DESEMBER": hadiah = " orang yang mudah bosan, itu sebabnya kamu mencari pasangan yang bisa membuat hidupmu berwarna Selain itu kamu harus mencari orang yang sabar dan dapat mengispirasi hidupmu agar menjadi lebih baik dari sebelumnya";
								 break; default: document.write("<p>Harap perhatikan dengan baik dan gunakan huruf KAPITAL</p>"); } 
								 if(hadiah === ""){ document.write("<p>Isi bulan kelahiran mu dengan huruf KAPITAL</p>"); }
								  else { document.write("<h2>Tipe carachteristik jodoh kamu adalah" + hadiah + "</h2>"); }} </script>



