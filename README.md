<!DOCTYPE html>
<html>
<head>
    <title>PHẦN MỀM QUẢN LÝ THIẾT BỊ</title>
</head>
<body>
    <table width="1500" border="1" cellspacing="0" cellspacing="0" align="center">
       <tr>
         <td colspan="2">
            <table width="1500" cellspacing="0" cellspacing="0">    
            <img width="1500" src="http://thptgiolinh.quangtri.edu.vn/upload/32290/20180106/viet2.png"/>
        </td>
       </tr>
        <tr>
            <Td style="background-color:rgb(4, 97, 46);">
            <tdalign="center">
          <h2 style="color:rgb(0, 0, 255);" align="center"> <b>TRANG NHẬP PHIẾU BÁO SỬ DỤNG THIẾT BỊ MÔN ĐỊA LÝ</b></h2>
          <h3 style="color:Yellow;" align="center">Thiết kế và quản lý: Trần Trọng Hà - Phó Hiệu trưởng</h3>
            </tdalign>
           </td>
        </tr>
    </table>
  </body>
  <html>
<head>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
</head>
<body>
    <table width="1500" cellspacing="0" cellspacing="0" align="center">
        <div id="banner" " align="center">
            <script type="text/javascript">
             document.write('<a  href="https://docs.google.com/spreadsheets/d/19iS8dtsVLImQyByC9WwKiN3s_RcgYhnMX3vlYk4G66Y/edit#gid=68579796">XEM DANH SÁCH ĐĂNG KÝ</a>')
             document.write('<a  href="https://docs.google.com/spreadsheets/d/19iS8dtsVLImQyByC9WwKiN3s_RcgYhnMX3vlYk4G66Y/edit#gid=68579796">XEM DANH SÁCH ĐĂNG KÝ</a>')
            </script>
        </div>
        <tr>
            <td width="450" align="center"><html>
                <img width="450" src="http://thptgiolinh.quangtri.edu.vn/upload/32290/20220905/1B147249-02D6-4948-BF62-220C12B41F21_d35c3.jpeg"/>
                <img width="450" src="http://thptgiolinh.quangtri.edu.vn/upload/32290/20220905/3482D9DF-7DF3-4446-96BC-DA97B20F5E64_05895.jpeg"/>
               
            </td>
            <td width="500"> 
            <div class="exam1" >
                <body>
                    
                <div id="dangky" class="exam1">
                    <div class="row">
                     <h4 style="color:rgb(0, 0, 255);" align="center"> <b>GIÁO VIÊN NHẬP THÔNG TIN ĐỂ ĐĂNG KÝ MƯỢN THIẾT BỊ</b></h4>
                     <h4 style="color:rgb(0, 0, 255);" align="center"> Lưu ý: Giáo viên cần điền đầy đủ các thông tin trước khi lưu đăng ký</h4>
                     <!--Cách 1: HIỂN THỊ THÔNG BÁO DẠNG POUPUP -->
                             <script type="text/javascript">
                                 var submitted=false;
                             </script>
                             <iframe id="hidden_iframe" name="hidden_iframe" onload="if(submitted){alert('Bạn đã đăng ký mượn thiết bị thành công!');}" style="display: none;"></iframe>
                             <!--Cách 2: HIỂN THỊ THÔNG BÁO DẠNG LINK-->
                            
                         <div class=" wow fadeInRight animated" style="visibility: visible; animation-name: fadeInRight;">
                         <script type="text/javascript">
                             var submitted=false;
                         </script>
                         <iframe id="hidden_iframe" name="hidden_iframe" onload="if(submitted){window.location='thongbao.html';}" style="display: none;"></iframe>
                         <!--Cách 2: End HIỂN THỊ THÔNG BÁO DẠNG LINK-->
                         <form onsubmit="submitted=true;" target="hidden_iframe" class="text-left"  role="form" id="ss-form" method="GET" action="https://script.google.com/macros/s/AKfycbzlonEKo5plWOU2HQpSaLK7YgyFV9CS7sC_zl3vkeycHTxwlWeb4hsg3IMkJ6JFQ93L/exec">
                           
                            <div class="exam1">
                                 <div>
                                     <label for="name" style="color:MediumSeaGreen;">HỌ VÀ TÊN:</label><br>
                                     <input title="" required="" class="form-control" placeholder=" Họ và tên... " dir="auto" id="Họ và tên giáo viên" value="" name="Họ và tên giáo viên" type="text">
                                 </div>
                             </div>
                             
                             <div class="exam1">
                                 <div>
                                     <label for="name" style="color:MediumSeaGreen;">TÊN THIẾT BỊ CẦN SỬ DỤNG:</label><br>
                                     <input title="" required="" class="form-control" placeholder=" Tên TB cần sử dụng... " dir="auto" id="Tên TB cần sử dụng" value="" name="Tên TB cần sử dụng" type="text">
                                 </div>
                             </div>
                             
                             <div class="exam1">
                                 <div>
                                     <label for="name" style="color:MediumSeaGreen;">SỐ LƯỢNG:</label><br>
                                     <input title="" required="" class="form-control" placeholder="Số lượng thiết bị cần mượn" dir="auto" id="Số lượng" value="" name="Số lượng" type="number" min="1" max="17">
                                 </div>
                             </div>
                             
                             <div class="exam1">
                                 <div>
                                     <label for="name" style="color:MediumSeaGreen;">NGÀY SỬ DỤNG:</label><br>
                                     <input title="" required="" class="form-control" placeholder="Ngày sử dụng" dir="auto" id="Ngày sử dụng" value="" name="Ngày sử dụng" type="date">
                                 </div>
                             </div>
             
                             <div class="exam1">
                                 <div>
                                     <label for="name" style="color:MediumSeaGreen;">BUỔI DẠY:</label><br>
                                     <input title="" required="" class="form-control" placeholder="Buổi" dir="auto" id="Buổi" value="" name="Buổi" type="text">
                                 </div>
                             </div>
             
                             <div class="exam1">
                                 <div>
                                     <label for="name" style="color:MediumSeaGreen;">TIẾT THEO PPCT:</label><br>
                                     <input title="" required="" class="form-control" placeholder="Tiết PPCT" dir="auto" id="Tiết PPCT" value="" name="Tiết PPCT" type="text" min="1" max="1000">
                                 </div>
                             </div>
             
                             <div class="exam1">
                                 <div>
                                     <label for="name" style="color:MediumSeaGreen;">LỚP DẠY:</label><br>
                                     <input title="" required="" class="form-control" placeholder="Lớp dạy" dir="auto" id="Lớp" value="" name="Lớp" type="text">
                                 </div>
                             </div>
             
                             <div class="exam1">
                                 <div>
                                     <label for="name" style="color:MediumSeaGreen;">TIẾT THEO TKB:</label><br>
                                     <input title="" required="" class="form-control" placeholder="Tiết TKB" dir="auto" id="Tiết TKB" value="" name="Tiết TKB" type="number" min="1" max="5">
                                 </div>
                             </div>
                                
                             <div class="clear"></div>
             
                                <div class="form-group text-center">
                                     <input class="btn btn-primary dangkybt" id="ss-submit" value="Gửi đăng ký" name="submit" type="submit">
                                 </div>
                                
                         </form>
                        
                        </div>
                 </div>
                 </body>
            </div>
            </td>
            <td width="400" align="center">
                <img width="400" src="http://thptgiolinh.quangtri.edu.vn/upload/32290/20220905/FC3438A2-AE84-4A6E-A36D-C5554D50DDCF_801a5.jpeg"/>
                <img width="400" src="http://thptgiolinh.quangtri.edu.vn/upload/32290/20220905/CADACA5B-2219-4FE4-8F7C-8222EE0AC536_eb1bc.jpeg"/>
                
            </td>
        </tr>
        <tr>
            <td>4</td>
            <td>5</td>
            <td>6</td>
        </tr>
    </table>
   
</body> 
</html>
