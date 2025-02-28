<!DOCTYPE html>
 <html> //
 <style>
 * {
 box-sizing: border-box;
 }
 body{
 margin: 0;
 font-family: Arial;
 }
 .header {
 text-align: center;
 padding: 32px;
 }
 .row {
 display: -ms-fexbox;
 display: fex;-ms-fex-wrap: wrap;
 fex-wrap: wrap;
 padding: 0 4px;
 }
 .column {-ms-fex: 25%;
 f+5%;
 max-width: 25%;
 padding: 0 4px;
 }
 .column img {
 margin-top: 8px;
 vertcal-align: middle;
width: 100%;
 }
 @media screen and (max-width: 800px) {
 .column {-ms-fex: 50%;
 fex: 50%;
 max-width: 50%;
 }
 @media screen and (max-width: 600px) {
 .column {-ms-fex: 100%;
 fex: 100%;
 max-width: 100%;
 }
 }
 </style>
 <body>
 <div class="header">
 <h1>Responsive Image Grid</h1>
 <p>Resize the browser window to see the responsive efect.</p>
 </div>
 <div class="row">
 <div class="column">
 <img 
src="https://cdn.pixabay.com/photo/2023/08/01/17/59/french-bulld
 og-8163486_960_720.jpg" style="width:30%">
 <img 
src="https://cdn.pixabay.com/photo/2023/12/11/12/03/exit-sign-84
 43453_960_720.jpg" style="width:30%">
 <img 
src="https://cdn.pixabay.com/photo/2023/09/03/15/16/rofous-82308
81_960_720.jpg" style="width:30%">
 <img 
src="https://cdn.pixabay.com/photo/2023/06/14/23/12/sunset-80640
 78_960_720.jpg" style="width:30%">
 <img 
src="https://cdn.pixabay.com/photo/2022/04/03/14/22/city-7109073
 _1280.jpg" style="width:30%">
 <img 
src="https://cdn.pixabay.com/photo/2012/11/02/13/02/car-63930_12
 80.jpg" style="width:30%">
 <img 
src="https://cdn.pixabay.com/photo/2024/01/17/12/06/car-8514314_
 960_720.png" style="width:30%">
 <img 
src="https://th.bing.com/th/id/OIP.3Y4vngdkYgbj3adSMpKqzAHaFE?rs
 =1&pid=ImgDetMain" style="width:30%">
 <img 
src="https://cdn.pixabay.com/photo/2024/08/02/16/44/rose-8940207
 _1280.jpg" style="width:30%">
 </div>
 </body>
 </html>
