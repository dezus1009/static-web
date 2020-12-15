<!DOCTYPE html>
<html>

<head>
	<title>web của mỡ</title>
	<meta charset="utf-8">
</head>

<head>
	<style>
		* {
			box-sizing: border-box;
		}

		body {
			margin: 0;

		}


		input[type=text] {
			width: 100%;
			box-sizing: border-box;
			border: 3px solid #CCC;
			border-radius: 20px;
			font-size: 16px;
			background-color: white;
			background-image: url('searchicon.png');
			background-position: 10px 10px;
			background-repeat: no-repeat;
			padding: 10px 20px 12px 40px;
		}

		.box1 {
			float: left;
			width: 30%;
			margin-bottom: -15px;
		}

		.box2 {
			width: 130px;
			float: left;
			width: 35%;
			padding: 50px;
			height: 100px;
		}

		.box3 {
			float: left;
			width: 35%;
			padding: 50px;
			height: 100px;
			color: red;
		}


		.timkiem::after {
			overflow: hidden;
			content: "";
			clear: both;
			display: table;
		}

		}

		.menu {
			overflow: hidden;
			font-family: Arial, Helvetica, sans-serif;
			margin: 0px auto;
			background: #F0FFFF;

		}


		.menu a {
			float: right;
			font-size: 16px;
			color: white;
			text-align: center;
			padding: 14px 16px;
			text-decoration: none;
			background-color: white;

		}

		.dropdown {
			float: left;
			overflow: hidden;
			background: #008080;
		}

		.dropdown .dropbtn {
			font-size: 16px;
			border: none;
			outline: none;
			color: white;
			padding: 14px 16px;
			background-color: inherit;
			font: inherit;
			margin: 0;
		}

		.menu a:hover,
		.dropdown:hover .dropbtn:hover {
			background-color: #FF0000;

		}

		.dropdown-content {
			display: none;
			position: absolute;
			width: 100%;
			left: 0;
			box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0);
			z-index: 1;
		}



		.dropdown:hover .dropdown-content {
			display: block;

		}

		.column {
			float: left;
			width: 15%;
			padding: 5px;
			background-color: #ADD8E6;
			height: auto;
		}

		.column h3 {
			text-align: center;
			margin: 5px;

		}

		.column a {
			float: none;
			color: black;
			padding: 10px;
			text-decoration: none;
			display: block;
			text-align: left;
		}

		.column a:hover {
			background-color: #696969;
			color: white;
		}

		.row:after {
			content: "";
			display: table;
			clear: both;
		}

		/* sản phẩm */
		.sp {

			margin-left: 20px;
			overflow: hidden;
			float: left;
			margin-bottom: 0px;

		}

		.ten {
			width: 290px;
			height: 150px;
			margin-left: 20px;
			overflow: hidden;
			float: left;
			margin-bottom: 5px;
		}

		.ten p {
			text-align: center;
			font-family: "Lucida Console", Courier, monospace;


		}

		.giasp {

			text-align: right;
			font-size: 16px;
			font-family: "Lucida Console", Courier, monospace;
		}

		.ten button {
			color: white;
			text-align: center;
			background: #008080;
			float: right;
			border: 2px solid #BBBBBB;

		}

		.tensp {
			text-align: center;
			font-family: "Times New Roman", Times, serif font-size: 17px;
			color: #2F4F4F#008080;
		}

		.footer {
			font-family: "Lucida Console", Courier, monospace;
			background: #008080;

			height: auto;
			overflow: hidden;
			content: "";
			clear: both;
			display: table;
			color: #E6E6FA;
		}

		.footer1 {
			float: left;
			width: 24%;
			padding: 30px;
		}

		.footer2 {

			float: left;
			width: 24%;
			padding: 30px;

		}

		.footer3 {
			float: left;
			width: 24%;
			padding: 30px;
		}

		.footer4 {
			float: left;
			width: 24%;
			padding: 30px;
	</style>
</head>

<body>
	<div class="container">
		<div class="timkiem">
			<div class="box1">
				<a href="#"><img src="logo.png" alt="" width="300" height="130" style="float: right;"></a>
			</div>
			<div class="box2">
				<form>
					<input type="text" name="search" placeholder="Bạn cần tìm gì...?">
				</form>
			</div>
			<div class="box3">
				<h2> Liên Hệ: 0358100337 </h2>
			</div>

		</div>

		<div class="menu">
			<ul>
				<div class="dropdown">
					<a class="dropbtn" href="#home">SẢN PHẨM MỚI </a>
				</div>
				<div class="dropdown">
					<button class="dropbtn">pro
						<i class="fa fa-caret-down"></i>
					</button>
					<div class="dropdown-content">
						<div class="row">
							<div class="column">
								<h3>Tuna</h3>
								<a href="#">basic</a>
								<a href="#">spe</a>
								<a href="#">high</a>
							</div>
							<div class="column">
								<h3>BALI</h3>
								<a href="#">mini</a>
								<a href="#">largers</a>
								<a href="#">mas</a>
							</div>
						</div>
					</div>
				</div>

				<div class="dropdown">
					<button class="dropbtn">bear
						<i class="fa fa-caret-down"></i>
					</button>
					<div class="dropdown-content">
						<div class="row">
							<div class="column">
								<h3>LVL</h3>
								<a href="#">dropa</a>
								<a href="#">ssmi</a>
								<a href="#">brods</a>
							</div>
							<div class="column">
								<h3>QJ</h3>
								<a href="#">nothi</a>
								<a href="#">ckaki</a>
								<a href="#">sprchi</a>
							</div>
							<div class="column">
								<h3>dama</h3>
								<a href="#">damm</a>
								<a href="#">saigin</a>
								<a href="#">mongu</a>
							</div>
						</div>
					</div>
				</div>

				<div class="dropdown">
					<button class="dropbtn">deer
						<i class="fa fa-caret-down"></i>
					</button>
					<div class="dropdown-content">
						<div class="row">
							<div class="column">
								<h3>GGO</h3>
								<a href="#">Goom</a>
								<a href="#">emi</a>
								<a href="#">cats</a>
							</div>
							<div class="column">
								<h3>CAS</h3>
								<a href="#">han</a>
								<a href="#">sff</a>
								<a href="#">tuna</a>
							</div>
							<div class="column">
								<h3>SAN</h3>
								<a href="#">Sandaler</a>
								<a href="#">ani</a>
								<a href="#">baka</a>
							</div>
						</div>
					</div>
				</div>
				<div class="dropdown">
					<a class="dropbtn" href="#news">baer </a>
				</div>
				<div class="dropdown">
					<a class="dropbtn" href="#news">deer</a>
				</div>
				<div class="dropdown">
					<a class="dropbtn" href="#news"> tiger </a>
				</div>
				<div class="dropdown">
					<a class="dropbtn" href="#news"> tuna</a>
				</div>

				<div class="dropdown">
					<a class="dropbtn" href="#news">pikachu </a>
				</div>
				<div class="dropdown">
					<a class="dropbtn" href="#news">event </a>
				</div>
		</div>
		</ul>

	</div>



	<div class="ảnh">
		<img src="15.jpg" alt="" width="100%" height="600"
			style="float: center;padding-top: 20px; margin-bottom: 20px;">
		<img src="16.jpg" alt="" width="48%" height="500" style="float: left;margin-left:20px; margin-bottom: 20px; ">
		<img src="17.jpg" alt="" width="48%" height="500" style="float: right; margin-right:20px; margin-bottom: 20px;">
	</div>

	<div class="sản phẩm">
		<div style="color: 	#DC143C">
			<center><strong>TOP các sản phẩm HOT nhất/ MỚI nhất</strong></center>
		</div>
		<div style="margin-left: 20px; color: #000080">
			<h2>animanto</h2>
		</div>
		<div class="ao">
			<a class="sp" href="#"><img src="11.jpg" alt="" width="290" height="300px"></a>
			<a class="sp" href="#"><img src="12.jpg" alt="" width="290" height="300px"></a>
			<a class="sp" href="#"><img src="13.jpg" alt="" width="290" height="300px"></a>
			<a class="sp" href="#"><img src="14.jpg" alt="" width="290" height="300px"></a>
		</div>
		<div class="tenao">
			<div class="ten">
				<p class="tensp">Set basic #A1</p>
				<h2 class="giasp">200.000₫</h2>
				<button>Đặt hàng</button>

			</div>
			<div class="ten">
				<p>clones #A2</p>
				<h2 class="giasp">180.000₫</h2>
				<button>Đặt hàng</button>
			</div>
			<div class="ten">
				<p>fa-ke #A3</p>
				<h2 class="giasp">300.000₫</h2>
				<button>Đặt hàng</button>
			</div>
			<div class="ten">
				<p>like au #A4</p>
				<div class="gia">
					<h2 class="giasp">800.000₫</h2>
					<button>Đặt hàng</button>

				</div>
			</div>
			<div class="tenao">
				<div class="ten">
					<p class="tensp">momoo #G1</p>
					<h2 class="giasp">300.000₫</h2>
					<button>Đặt hàng</button>

				</div>
				<div class="ten">
					<p>vvc#G2</p>
					<h2 class="giasp">999.000₫</h2>
					<button>Đặt hàng</button>
				</div>
				<div class="ten">
					<p>mms #G3</p>
					<h2 class="giasp">200.000₫</h2>
					<button>Đặt hàng</button>
				</div>
				<div class="ten">
					<p>gga #G4</p>
					<div class="gia">
						<h2 class="giasp">900.000₫</h2>
						<button>Đặt hàng</button>

					</div>
				</div>
				<div style="margin-left: 20px; color: #000080">
					<h2>normals</h2>
				</div>
				<div class="ao">
					<a class="sp" href="#"><img src="4.jpg" alt="" width="290" height="300px"></a>
					<a class="sp" href="#"><img src="2.jpg" alt="" width="290" height="300px"></a>
					<a class="sp" href="#"><img src="6.jpg" alt="" width="290" height="300px"></a>
					<a class="sp" href="#"><img src="9.jpg" alt="" width="290" height="300px"></a>
				</div>
				<div class="tenao">
					<div class="ten">
						<p class="tensp">sket #T1</p>
						<h2 class="giasp">700.000₫</h2>
						<button>Đặt hàng</button>

					</div>
					<div class="ten">
						<p>tdio#T2</p>
						<h2 class="giasp">599.000₫</h2>
						<button>Đặt hàng</button>
					</div>
					<div class="ten">
						<p>ala #T3</p>
						<h2 class="giasp">399.000₫</h2>
						<button>Đặt hàng</button>
					</div>
					<div class="ten">
						<p>taama #T4</p>
						<div class="gia">
							<h2 class="giasp">150.000₫</h2>
							<button>Đặt hàng</button>

						</div>
					</div>
					<div style="margin-left: 20px; color: #000080">
						<h2>hệ pro</h2>
					</div>
					<div class="ao">
						<a class="sp" href="#"><img src="1.jpg" alt="" width="290" height="300px"></a>
						<a class="sp" href="#"><img src="2.jpg" alt="" width="290" height="300px"></a>
						<a class="sp" href="#"><img src="3.jpg" alt="" width="290" height="300px"></a>
						<a class="sp" href="#"><img src="4.jpg" alt="" width="290" height="300px"></a>
					</div>
					<div class="tenao">
						<div class="ten">
							<p class="tensp">Gentle Monster Dreamer Hoff 01 #K1</p>
							<h2 class="giasp">170.000₫</h2>
							<button>Đặt hàng</button>

						</div>
						<div class="ten">
							<p>RSG #K2</p>
							<h2 class="giasp">150.000₫</h2>
							<button>Đặt hàng</button>
						</div>
						<div class="ten">
							<p>hanel #K3</p>
							<h2 class="giasp">399.000₫</h2>
							<button>Đặt hàng</button>
						</div>
						<div class="ten">
							<p>faa #K4</p>
							<div class="gia">
								<h2 class="giasp">300.000₫</h2>
								<button>Đặt hàng</button>

							</div>
						</div>
						<div style="margin-left: 20px; color: #000080">
							<h2>ĐỒNG QUAN</h2>
						</div>
						<div class="ao">
							<a class="sp" href="#"><img src="5.jpg" alt="" width="290" height="300px"></a>
							<a class="sp" href="#"><img src="6.jpg" alt="" width="290" height="300px"></a>
							<a class="sp" href="#"><img src="7.jpg" alt="" width="290" height="300px"></a>
							<a class="sp" href="#"><img src="9.jpg" alt="" width="290" height="300px"></a>
						</div>
						<div class="tenao">
							<div class="ten">
								<p class="tensp">sda #H1</p>
								<h2 class="giasp">500.000₫</h2>
								<button>Đặt hàng</button>

							</div>
							<div class="ten">
								<p>tama #H2</p>
								<h2 class="giasp">599.000₫</h2>
								<button>Đặt hàng</button>
							</div>
							<div class="ten">
								<p>lala #H3</p>
								<h2 class="giasp">300.000₫</h2>
								<button>Đặt hàng</button>
							</div>
							<div class="ten">
								<p>hofy #H4</p>
								<div class="gia">
									<h2 class="giasp">800.000₫</h2>
									<button>Đặt hàng</button>

								</div>
							</div>
							<div style="margin-left: 20px; color: #000080">
								<h2>pogi</h2>
							</div>
							<div class="ao">
								<a class="sp" href="#"><img src="1.jpg" alt="" width="290" height="300px"></a>
								<a class="sp" href="#"><img src="2.jpg" alt="" width="290" height="300px"></a>
								<a class="sp" href="#"><img src="3.jpg" alt="" width="290" height="300px"></a>
								<a class="sp" href="#"><img src="4.jpg" alt="" width="290" height="300px"></a>
							</div>
							<div class="tenao">
								<div class="ten">
									<p class="tensp">mặt tự nhiên #V1</p>
									<h2 class="giasp">699.000₫</h2>
									<button>Đặt hàng</button>

								</div>
								<div class="ten">
									<p>Lofy #V2</p>
									<h2 class="giasp">499.000₫</h2>
									<button>Đặt hàng</button>
								</div>
								<div class="ten">
									<p>sopi #V3</p>
									<h2 class="giasp">799.000₫</h2>
									<button>Đặt hàng</button>
								</div>
								<div class="ten">
									<p>bình an #V4</p>
									<div class="gia">
										<h2 class="giasp">800.000₫</h2>
										<button>Đặt hàng</button>

									</div>
								</div>
								<div style="margin-left: 20px; color: #000080">
									<h2>MŨ(NÓN)</h2>
								</div>
								<div class="ao">
									<a class="sp" href="#"><img src="1.jpg" alt="" width="290" height="300px"></a>
									<a class="sp" href="#"><img src="2.jpg" alt="" width="290" height="300px"></a>
									<a class="sp" href="#"><img src="3.jpg" alt="" width="290" height="300px"></a>
									<a class="sp" href="#"><img src="4.jpg" alt="" width="290" height="300px"></a>
								</div>

								<div>
									<img src="20.jpg" alt="" width="55%" height="350"
										style="float: left;margin-left:20px; margin-bottom: 100px; ">
									<img src="21.jpg" alt="" width="40%" height="400"
										style="float: right; margin-right:20px; margin-bottom: 20px;">
								</div>
								<div class="footer">

									<div class="footer1">
										<a>GIỚI THIỆU</a>

										<p>MỠ - Gấu bông </p>

										<p>Đẹp - Đẳng Cấp là phương châm phục vụ của chúng tôi</p>

										<p>Hàng chất lượng cao cấp là cam kết của chúng tôi </p>
									</div>
									<div class="footer2">
										<a>CHÍNH SÁCH</a>

										<p>Nhận hàng thanh toán, đặt cọc trước chỉ 10%</p>

										<p>Nếu đặt cọc trước 30% được giảm giá 5%</p>

										<p>Đặt cọc trước 50% được giảm giá 10%</p>

										<p>Đặt cọc trước 100% được giảm giá 15%</p>

									</div>
									<div class="footer3">
										<a>LIÊN HỆ</a>

										<p> sđt: 0123456789</p>

										<p> Gmail: mongaochoa@gmail.com</p>

										<p><a href="https://www.facebook.com/profile.php?id=100026030002521">FB:Mỡ</a>
										</p>
									</div>
									<div class="footer4">
										<a>ĐỊA CHỈ</a>

										<p>18 phố viên, phường Đức Thắng, quận Bắc Từ Liêm, thủ đô Hà Nội, Việt Nam</p>
									</div>

								</div>
</body>

</html>
