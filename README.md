<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DUCAT |  HOME</title>
    <style>
     *{
    margin: 0px;
    padding-left: 0px;
} 
body{
    margin: 0;
}
.navbar {
    display: flex;
    margin: -8px;
    padding-left: 10px;
 }
.logo {
    padding-left: 131px;
    padding-top: 37px;
}
.logo img {
    width: 110px;
    height: 48px;
    padding-left: 0px;
}
.manu_itam ul{
    display: flex;
    padding: 20px;
    padding: 20px;
    font-size: 1.1rem;
}
.contact_us{
    background-color: #ffcc00;
    border-radius: 20px;
    height: 5px;
    width: 89px;
    align-items: center;
    font-weight: bold;
}
.manu_itam {
    padding-left: 196px;
}
.manu_itam {
    padding-top: 15px;
}
.manu_itam li{
    padding: 20px;
    list-style: none;
}
.body{
    
    display: flex;
    width: 100vw;
    align-items: center;
    
}
.ducat_img{
    width: 50%;
    padding-right: 20px;
    
}
.itam {
    width: 50%;
    padding-left: 100px;
    text-align: justify;
}
.itam h1{
    padding-left: 30px;
    padding-right: 30px;
    font-weight: bold;
    font-size: 2.6rem;
}
.ducat_img img {
    width: 628px;
    height: 500px;
}
.search {
    padding-left: 285px;
    margin: -117px;
    position: absolute;
    
}
.search input{
    height: 60px;
    width: 400px;
    border: none;
    background-color: #e5f4fc;
    border-radius: 10px 0 0 10px;
    padding-left: 0px;
    font-size: 1.1rem;
}

.search button{
    height: 60px;
    width: 50PX;
    margin: 0;
    font-size: 5px;
    border: none;
    background-color: #23a6f0;
    border-radius: 0 10px 10px 0;

}  
.icon_contact i{
    display: block;
    
    
}

.icon_contact {
    background-color: #14599e;
    font-size: 1.6rem;
    color: white;
    height: 115px;
    width: 36px;
    padding-left: 7px;
    position: sticky;
    display: grid;
    align-content: space-evenly;
    justify-content: space-between;
    float: right;
    border-radius: 10px 0 0 10px;
    margin-top: -400px;
}

.itam_info{
    display: flex;
    margin: 0px;
    background-color: #14599e;
}
.info_img {
    display: flex;
    align-items: center;
    margin-top: 22px;
    margin-left: 20px;
    margin-right: 78px;
    padding-left: 83px;
    padding-bottom: 20px;
}
.info_img img{
    height: 45px;
    width: 45px;
}
    
       
    </style>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
</head>
<body>
    <nav class="navbar">
        <div class="logo">
            <img src="./ducatlogo.png" alt="logo">
        </div>
        <div class="manu_itam">
            <ul>
                <li>Home</li>
                <li>About us</li>
                <li>Courses</li>
                <li>Certificate</li>
                <li>Placements</li>
                <li>Blog</li>
                <li class="contact_us">Contact Us</li>
            </ul>
        </div>
    </nav>
    <div class="body">
        <div class="itam">
            <h1>Unlock your potential with us and watch your career dreams come to life.</h1>
        </div>
        <div class="ducat_img">
            <img src="./ducat img.webp" alt="ducat image">
        </div>
    </div>
    <div class="search">
        <input type="text" placeholder="Search your favourite coures today.">
        <button><span class="material-symbols-outlined icon">
            search
            </span>
            </button>
    </div>
  
    <div class="icon_contact">
    <i class="fa fa-envelope "></i>
    <i class="fa fa-phone "></i>
    <i class="fa fa-whatsapp "></i>
    </div>
    

    <div class="itam_info">
        <div class="info_img">
            <img src="./ducat 1.png">
            <p>Learn The Essential Skills</p>
        </div>
        <div class="info_img">
            <img src="./ducat 2.png">
            <p>Earn Certificates And Degrees</p>
        </div>
        <div class="info_img">
            <img src="./ducat 3.png">
            <p>Get Ready for The Next Careers</p>
        </div>
        <div class="info_img">
            <img src="./ducat 4.png">
            <p>Master at Different Areas</p>
        </div>
        
    </div>
</body>
</html>
