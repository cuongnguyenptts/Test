# Started01
Tạo trang web cho người mới bắt đầu
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="nhanvat.css    ">
    <link rel="stylesheet" href="menu.css">
    <!-- <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css"> -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Piazzolla:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <script src="js/bootstrap.min.js"></script>
    <script src="js/jquery.min.jss"></script>
    <title>Nhân vật/one piecce</title>
    <script>
        function changecolor(color){
            const mau = document.querySelector('#mau');
            mau.style.background = color
        }

        function changecolor(color){
            const mau = document.querySelector('#mau');
            mau.style.background = color
        }

        function kiemtra(){
            var email = document.querySelector('#email').value;
            var check_email = email.indexOf("@");
            if(check_email < 1){
                document.querySelector('#erroremail').innerHTML=`!email không hợp lệ (Phải có '@')`;
                return false;
            }else{
                document.querySelector('#erroremail').innerHTML=``;
            }
        }
    </script>
</head>
<body id ="mau">  
    <div class="header">
        <div class="header-top">
            <div class="header-top-l">
                <img src="images/logo.png">
            </div>
            <div class="header-top-r">
                <div class="doimau">
                    <button style="background: #fff;" class="maunen" onclick= "changecolor('#fff')"></button>
                    <button style="background: #f4efe6;" class="maunen" onclick= "changecolor('#f4efe6')"></button>
                </div>
                <div class="search">
                    <input type="text" class="search-btn" placeholder="Nập từ muốn tìm kiếm" style=" width: 350px; height: 40px; border:1px solid black ">
                    <a href="">
                        <i class="fa fa-search" aria-hidden="true" style="vertical-align: middle; color: #fff; padding: 5px;"></i>
                    </a>
                </div> 
            </div>
        </div>
        <div class="header-bootom">
            <div class="menu">
                <ul>
                    <li><a href="trangchu.html">
                        <img src="images/menu5.png" style="width:100%;">
                        Trang chủ
                    </a></li>
                    <li><a href="doctruyen1.html">
                        <img src="images/menu3.png" style="width:100%;">
                        Đọc truyện
                    </a></li>
                    <li><a href="nhanvat.html">
                        <img src="images/menu1.png" style="width:100%;">
                        Nhân vật
                    </a></li>
                    <li><a href="sukien.html">
                        <img src="images/menu4.png" style="width:100%;">
                        Sự kiện
                    </a></li>
                    <li><a href="#">
                        <img src="images/menu2.png" style="width:100%;">
                        Mới nhất
                    </a></li>
                </ul>
            </div>
        </div>
    </div>
    <br><hr />
    <div class="tieude">
        <h1>Các Thành Viên Chính Thức Của Băng Hải Tặc Mũ Rơm</h1>    
    </div>
	<!-- <hr /><br> -->
		<div class="NhanVat">
			<div class="NV1">
				<div class="tenNV">
                    <h2>Monkey D.Luffy<h2>
                </div>
                <div class="anhNV">
                    <img src="images/Nhanvat-Anh1.jpg">
                    <p>Monkey D. Luffy  là nhân vật chính của One Piece và là thuyền trưởng của băng Hải tặc Mũ Rơm, anh có biệt danh là "Luffy Mũ Rơm". Luffy trở thành người người cao su sau khi vô tình ăn trái ác quỷ Gomu Gomu hệ Paramecia do Shanks lấy được. Luffy có ước mơ là trở thành Vua Hải tặc và là người tìm thấy kho báu "One Piece". Luffy lên đường tìm kiếm đồng đội để thành lập băng hải tặc của riêng mình, cuộc hành trình của Luffy bắt đầu và cái tên "Luffy Mũ Rơm" dần dần nổi tiếng trong toàn thế giới One Piece. Luffy thành thục cả ba loại Haki và có khả năng chiến đấu cao. Luffy có tính cách khá hài hước và đôi khi hơi ngốc nghếch, nhưng lại có khả năng ứng biến tuyệt vời. Luffy rất tin tưởng, yêu quý và tôn trọng các đồng đội của mình.<br><b>Số Tiền Truy Nã: 1.500.000.000 Beri</b></p>
                </div>
			</div>
			<div class="NV2">
				<div class="tenNV">
                    <h2>Roronoa Zoro<h2>
                </div>
                <div class="anhNV">
                    <img src="images/Nhanvat-Anh2.jpg">
                    <p>Roronoa Zoro là kiếm sĩ của băng hải tặc Mũ Rơm, anh là thành viên thứ hai của băng Mũ Rơm. Zoro theo "Tam Kiếm Phái" và có biệt danh là "Thợ săn Hải tặc Zoro", anh là chủ sở hữu của bốn thanh kiếm nằm trong các thanh kiếm quý của thế giới One Piece. Ước mơ của Zoro là hoàn thành lời hứa với người bạn thân quá cố, trở thành kiếm sĩ mạnh nhất thế giới. Zoro đã ra khơi để lên đường thực hiện ước mơ của mình, Luffy đã cứu Zoro và trở thành thuyền viên đầu tiên của băng hải tặc Mũ Rơm. Zoro có thể sử dụng 2 loại Haki là Haki quan sát và Haki vũ trang.<br><b>Số Tiền Truy Nã: 320.000.000 Beri</b></p>
                </div>
            </div>
			<div class="NV3">
				<div class="tenNV">
                    <h2>Nami<h2>
                </div>
                <div class="anhNV">
                    <img src="images/Nhanvat-Anh3.jpg">
                    <p>Nami là Hoa Tiêu của băng hải tặc Mũ Rơm. Cô là thành viên thứ ba của băng và có biệt danh là "Miêu tặc". Giấc mơ của Nami là hoàn thành bản đồ của toàn thế giới trong One Piece. Nami được đánh giá "thiên tài" trong lĩnh vực hàng hải và cực kì thông minh cùng với tài trộm cắp điệu nghệ, mặc cả giá tiền, đồng thời là có khả năng tự bản thân dự báo được thời tiết. Vũ khí mà Nami sử dụng có tên là Clima-Tact có khả năng điều khiển thời tiết. Nami là một trẻ mồ côi được nữ hải quân quá cố Bellemere nhận làm con nuôi. Sau một vài biến cố, Luffy và các thuyền viên nam khác đã theo chân Nami về quê hương của cô và tiêu diệt hoàn toàn băng hải tặc Arlong, đem lại tự do cho Nami cùng những người dân trên đảo.<br><b>Số Tiền Truy Nã: 66.000.000 Beri</b></p>
                </div>
			</div>
			<div class="NV4">
				<div class="tenNV">
                    <h2>Usopp<h2>
                </div>
                <div class="anhNV">
                    <img src="images/Nhanvat-Anh4.jpg">
                    <p>Usopp là xạ thủ của băng hải tặc Mũ Rơm và là thành viên thứ tư của băng. Biệt danh hiện tại của Usopp là "God". Nhân dạng khác mà trước đây Usopp dùng và có trên lệnh truy nã là "Sogeking" với biệt danh "Vua bắn tỉa". Ước mơ của Usopp là trở thành "Chiến binh dũng cảm của biển cả", bên cạnh đó là một lần được tới Elbaf. Usopp có tài thiện xạ bách phát bách trúng và cũng nhiều tài lẻ như khả năng hội họa, sáng chế, điêu khắc. Usopp gia nhập băng hải tặc Mũ Rơm và trở thành thuyền viên thứ ba sau khi sát cánh cùng nhóm Luffy đánh bại băng hải tặc Mèo Đen.<br><b>Số Tiền Truy Nã: 200.000.000 Beri</b></p>
                </div>
			</div>
			<div class="NV5">
				<div class="tenNV">
                    <h2>Sanji<h2>
                </div>
                <div class="anhNV">
                    <img src="images/Nhanvat-Anh5.jpg">
                    <p>Sanji là Đầu Bếp của băng hải tặc Mũ Rơm. Anh có biệt danh là “Sanji Chân Đen” và có sở trường chiến đấu bằng chân. Ước mơ của Sanji là tìm thấy vùng biển huyền thoại "All Blue". Sanji là một đầu bếp tài ba và giỏi trong cả chiến đấu lẫn nấu ăn. Sanji rất lịch thiệp với phụ nữ chuẩn với hình mẫu của người đàn ông kiểu Pháp. Sanji học kĩ năng nấu nướng và phong cách chiến đầu bằng chân được truyền lại từ Zeff. Sau cuộc đụng độ với băng hải tặc Krieg, Sanji quyết định gia nhập băng hải tặc Mũ Rơm và trở thành thuyền viên thứ tư của băng. Sanji có tên thật là Vinsmoke Sanji và là con trai thứ 3 của gia tộc Vinsmoke thuộc vương quốc Germa ở North Blue. Sanji có thể sử dụng 2 loại Haki thông thường là vũ trang và quan sát.<br><b>Số Tiền Truy Nã: 330.000.000 Beri</b></p>
                </div>
			</div>
			<div class="NV6">
				<div class="tenNV">
                    <h2>Tonytony Chopper<h2>
                </div>
                <div class="anhNV">
                    <img src="images/Nhanvat-Anh6.jpg">
                    <p>Tonytony Chopper là Bác sĩ của băng hải tặc Mũ Rơm và là thành viên thứ sáu của băng. Chopper có biệt danh "Kẻ yêu kẹo bông" Chopper, cậu sở hữu trái ác quỷ Hito Hito hệ Zoan. Chopper là một bác sĩ có tay nghề cao và nhờ vào Rumble Ball, Chopper có tới bảy nấc biến hóa thay vì ba dạng biến hình như các trái hệ Zoan thông thường. Ước mơ của Chopper là có thể chữa được tất cả mọi loại bệnh tất trên đời. Chopper nguyên gốc là một chú tuần lộc mũi xanh quê ở đảo Drum của Grand Line. Chopper kết thừa lý tưởng của vị bác sĩ Hiluluk và được Dr. Kureha nhận làm học trò coi như con đẻ. Chopper gặp Luffy và băng Mũ Rơm khi họ tới Drum chữa bệnh cho Nami. Sau cuộc chạm trán với băng hải tặc Bliking, Chopper gia nhập băng Mũ Rơm.<br><b>Số Tiền Truy Nã: 100 Beri</b></p>
                </div>
			</div>
			<div class="NV7">
				<div class="tenNV">
                    <h2>Nico Robin<h2>
                </div>
                <div class="anhNV">
                    <img src="images/Nhanvat-Anh7.jpg">
                    <p>Nico Robin là nhà Khảo Cổ Học của băng Mũ Rơm và là thành viên thứ bảy của băng hải tặc Mũ Rơm. Robin có biệt danh "Đứa con của quỷ", cô sở hữu trái ác quỷ Hana Hana hệ Paramecia, với khả năng mọc cánh tay từ xa. Robin có ước mơ là tìm ra Rio Poneglyph, khám phá ra toàn bộ lịch sự chân thực. Cô sống một cuộc đời cô độc và không hề tin tưởng bất cứ một ai cho tới khi gặp băng Mũ Rơm. Sau khi thảm họa Ohara xảy ra, toàn bộ cư dân và những học giả ở trên đảo đều bỏ mạng chỉ còn Robin là người sống sót duy nhất. Robin bị cả thế giới truy đuổi và phải dấn thân vào thế giới ngầm từ để tìm cách tồn tại. Sau sự kiện tại Alabasta, Robin tự nguyện gia nhập băng hải tặc Mũ Rơm và trở thành thuyền viên thứ sáu, rồi tái gia nhập băng sau cuộc chiến tại Enies Lobby kết thúc.<br><b>Số Tiền Truy Nã: 130.000.000 Beri</b></p>
                </div>
			</div>
			<div class="NV8">
				<div class="tenNV">
                    <h2>Franky<h2>
                </div>
                <div class="anhNV">
                    <img src="images/Nhanvat-Anh8.jpg">
                    <p>Franky là thợ đóng tàu của băng hải tặc Mũ Rơm và là thành viên thứ tám của băng. Biệt danh của anh là "Người máy" Franky, anh là một thợ đóng tàu tài ba và không chỉ dừng lại ở đó Franky còn giỏi ở nhiều mặt khác. Franky có ước mơ là đóng một con tàu có thể vượt qua mọi sóng gió của biển cả, đến được tận cùng thế giới. Sau này, khi Franky hoàn thành Thousand Sunny và là thành viên băng Mũ Rơm, ước mơ của anh trở thành có thể đưa được tàu Sunny đến tận cùng thế giới. Tên thật của anh là Cutty Flam, Franky đã từ bỏ tên thật của mình này sau bi kịch của người thầy quá cố. Ban đầu Franky gặp băng Mũ Rơm ở Water 7 với vai trò nhân vật phản diện, sau này Franky sát cánh cùng với băng Mũ Rơm trong cuộc chiến tại Enies Lobby và cuối cùng trở thành thuyền viên thứ bảy.<br><b>Số Tiền Truy Nã: 94.000.000 Beri</b></p>
                </div>
			</div>
			<div class="NV9">
				<div class="tenNV">
                    <h2>Brook<h2>
                </div>
                <div class="anhNV">
                    <img src="images/Nhanvat-Anh9.jpg">
                    <p>Brook là Nhạc Công của băng hải tặc Mũ Rơm và là thành viên thứ chín của băng. Brook có biệt danh là "Brook Ngân Nga" và là một nhạc công tài ba có thể chơi được nhiều loại nhạc cụ. Brook sở hữu trái ác quỷ Yomi Yomi  giúp cho Brook có thể hồi sinh lại một lần. Ước mơ của ông là được gặp lại chú cá voi Laboon năm xưa, hoàn thành tâm nguyện của băng Hải tặc Rumbar. Tất cả các thành viên trong băng cũ của Brook đều đã hi sinh trong một trận thủy chiến từ nhiều năm về trước. Brook đã sát cánh với băng Mũ Rơm trong biến cố ở Thriller Bark với băng hải tặc Moria và gia nhập băng hải tặc Mũ Rơm, trở thành thuyền viên thứ tám của băng. Trong hai năm luyện tập, Brook trở thành ca sĩ nổi tiếng trên toàn thế giới One Piece với nghệ danh "Soul King" Brook.<br><b>Số Tiền Truy Nã: 83.000.000 Beri</b></p>
                </div>
			</div>
			<div class="NV10">
				<div class="tenNV">
                    <h2>Jinbe<h2>
                </div>
                <div class="anhNV">
                    <img src="images/Nhanvat-Anh10.jpg">
                    <p>"Hiệp sĩ biển" Jinbe là một thành viên của băng hải tặc Mũ Rơm. Anh ta là một người đàn ông cá mập cá voi từng là thuyền trưởng thứ hai của Cướp biển Mặt trời sau Fisher Tiger, và là một cựu Shichibukai từ 11 năm trước cho đến Trận Marineford hai năm trước. Ước mơ của anh là được hoàn thành giấc mơ của cựu đội trưởng Fisher Tiger. Mong muốn cùng tồn tại, chung sống và bình đẳng giữa con người và người cá. Jinbe tiếp tục sống cuộc sống của mình với hy vọng nhìn thấy giấc mơ hoàn thành. Sau cái chết của Râu Trắng , phi hành đoàn của anh đã thành lập liên minh với Big Mom để bảo vệ Đảo Người Cá. Anh kết bạn với Monkey D. Luffy trong Trận chiến Marineford. Sau đó, anh chính thức trở thành thành viên của băng Mũ Rơm.<br><b>Số Tiền Truy Nã: 438.000.000 Beri</b></p>
                </div>
			</div>
        </div>
    
        <div class="footer">
            <div class="footer-left">
                <div class="footer-left-top">
                    <h3>ONE PIECE" được ra đời vào năm ... 
                        nhằm mục đích giúp những người yêu anime có thể cập nhật được những thông tin về truyện 
                        và có thể đọc được truyện bất cứ ở đâu miễn là bạn có internet!
                    </h3>
                </div>
                <div class="footer-left-bottom">
                    <h3 style="font-size: 20px; color:white;padding: 10px 0px 0px 30px;"><i style="color: blue; margin-right: 5px;" class="fa fa-envelope-o" aria-hidden="true"></i>Email: onepiece130203@gmail.com</h3>
                    <h3 style="font-size: 20px;color: white;padding: 10px 0px 0px 30px;"><i style="color: red; margin-right: 5px;" class="fa fa-map-marker" aria-hidden="true"></i>Đ/c: cổ nhuế - trường đại học mỏ địa chất</h3>
                </div>
            </div>
            <div class="footer-right">
                <div class="footer-right-left">
                    <div class="footer-right-left-top">
                        <img src="images/logo.png">
                    </div>
                    <div class="footer-right-left-bottom">
                        <a href=""><i style="margin-right:5px; color: red" class="fa fa-question-circle-o" aria-hidden="true"></i>Câu hỏi</a>
                        <a href=""><i style="margin-right:5px;" class="fa fa-handshake-o" aria-hidden="true"></i>Điều khoản</a>
                        <a href=""><i style="margin-right:5px; color: seagreen;" class="fa fa-filter" aria-hidden="true"></i>Hồ sơ</a>
                    </div>
                </div>
                <div class="footer-right-right">
                    <div class="footer-right-right-top">
                        <p style=" color: white;margin-top: 10px;font-size: 17px; margin-left: 60px;">Sign up to the newsletter and be the first one to know about new </p>
                        <input style="width: 300px;height: 30px; margin-left: 100px;margin-top: 10px; " id="email" placeholder=" Enter your email"/>
                        <button style="height: 30px; width: 90px; background: lightblue;" onclick="kiemtra()">Subsceribe</button>
                        <div id="erroremail" class="error"></div>
                    </div>
                    <div class="footer-right-right-bottom">
                            <i style="font-size:50px; margin-top: 20px; color: red;" class="fa fa-phone" aria-hidden="true"></i>
                            <p style="color: white; font-size: 18px;">0925251325<br>0825251325</p>
                        </div>
                </div>
            </div>
        </div>
</body>
</html>
```
