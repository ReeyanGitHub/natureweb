<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA==" crossorigin="anonymous" referrerpolicy="no-referrer" />

</head>
<body>
    <div class="back">
        <div class="top">
            <h1>island</h1>
            <div class="nav">
                <h4><a href="#">Our Tours</a></h4>
                <h4><a href="#">About Us</a></h4>
                <h4><a href="#">Booking</a></h4>
                <h4><a href="#">FAQ</a></h4>
            </div>
            <i class="fa fa-bars" aria-hidden="true"></i>

        </div>
        <div class="mid">
            <div class="midmid">
                <h1>Explore the sights of the Azores</h1>
                <h3>A place where nature and adventure units</h3>
                <h4><a href="#">Book Now</a></h4>
            </div>
            
                          
        </div>
    </div>
    
</body>
</html>




//CSS

*{
    margin: 0;
    padding: 0;
}
html, body{
    height: 100%;
    width: 100%;
    box-sizing: border-box;
    font-family: "Gilroy";
    overflow-x: hidden;
    overflow-y: hidden;
}
.back{
    height: 100%;
    width: 100%;
   /* background-color: red;*/
}
.top{
    height: 90px;
    width: 100%;
    /*background-color: blue;*/
    display: flex;
    align-items: center;
    justify-content: space-between;
}
.nav{
    display: flex;
    gap: 30px;
    cursor: pointer;
}
i{
    padding: 30px;
    font-size: 25px;
    cursor: pointer;
    position: relative;
    
    
    
    /*border:3px solid green;*/
    padding: 1px;
    margin: 30px;
    transition: all ease-in-out 0.3s;
    
}
.top h1{
    padding: 30px;
    font-size: 34px;
    /*background-color: pink;*/
    padding: 1px;
    margin: 30px;
}
.nav h4 a{
    text-decoration: none;
    color: black;
    transition: all ease-in-out 0.15s;
}
.nav h4 a:hover{
    color:rgb(174, 233, 11);
}

i::after{
    content: "";
    position: absolute;
    
    height: 3px;
    width: 0%;
    
    background-color: rgb(174, 233, 11);
    left: -70%;
    bottom: -30%;
    transition: all ease-in-out 0.3s;
    
    
}
i:hover::after{
    width: 120%;
    left: -10%;
    bottom: -30%;
    
}
.mid{
    height: 80vh;
    width: 95%;
    background-image: url(https://images.unsplash.com/photo-1597682610725-67db32854b13?q=80&w=1470&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D);
    object-fit: center;
    margin: 30px;
    position: absolute;
    display: flex;
    align-items: center;
    justify-content: center;

    border-radius: 15px;
    
}
 /**img{
    display: block;
    height: 100%;
    width: 100%;
    object-fit: cover;
    border-radius: 15px;
    
}
*/
.midmid{
    height: 85%;
    width: 100%;
    /*background-color: rebeccapurple;*/
    display: flex;
    flex-direction: column;
    margin: 40px;
    row-gap: 30px;
    
}
.midmid h1{
    font-size: 80px;
    width: 660px;
    margin-bottom: 0px;
    color: white;

}
.midmid h4{
    border: 2px solid black;
    border-radius: 20px;
    width: 100px;
    padding: 10px 25px 10px 25px;
    display: flex;
    justify-content: center;
    color: black;
    position: relative;
    transition: all ease-in-out 0.3s;
    overflow: hidden;
    cursor: pointer;
}    
.midmid h4::after{
    content: "";
    position: absolute;
    background-color: white;
    height: 100%;
    width: 100%;
    top: 0;
    left: -100%;
    border-radius: 20px;
    transition: all ease-in-out 0.3s;


}
.midmid h4:hover::after{
    top: 0;
    left: 0;
}
.midmid h4 a{
    z-index: 99;
    text-decoration: none;
    color: black;
}
