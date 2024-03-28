<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
<style>
    *{
        margin: 0px;
        font-family: Arial, Helvetica, sans-serif;
        border: border-box;
    }

    .navbar{
        height: 60px;
        background-color: #0f1111;
        color: white;
        display: flex;
        align-items: center;
        justify-content: space-evenly;
    }

    .navlogout{
        height: 60px;
        width: 100px;
    }

    .log{
        height: 55px;
        width: 100%;
        background-image: url("Amazon-Emblem.jpg");
        background-size: cover;
    }
    
    .border{
        border: 2px solid transparent;
        border-radius: 5px;
    }

    .border:hover{
        border: 2px solid white;
        border-radius: 5 px;

    }

    .add-top{
        color: #cccccc;
        font-size: 0.85rem;
        margin-left: 15px;
    }

    .add-bot{
        color: #FFFFFF;
        font-size: 1rem;
        margin-left: 3px;
    }

    .addicon{
        display: flex ;
        align-items: center;
    }

    .nav-search{
        display: flex;
        width: 620px;
        height: 40px;
        border-top-right-radius: 4px;
        border-bottom-right-radius: 4px;
        justify-content: space-evenly;
        
    }

    .Search-select{
        border-top-left-radius: 4px;
        border-bottom-left-radius: 4px;
        background-color: #f3f3f3;
        width: 45px;
        text-align: center;
        border: none;
    }

    .Search-input{
        width: 100%;
        font-size: 1rem;
        border: none;
    }

    .searchicon{
        width: 45px;
        /* height: 40px; */
        display: flex;
        align-items: center;
        justify-content: center;
        font-size: 1.2rem;
        background-color: #febd68;
        border-top-right-radius: 4px;
        border-bottom-right-radius: 4px;
        color: #0f1111;
    }

    .flag{
        background-color: white;
        height: 18px;
        width: 30px;
        background-image: url("image.png");
        background-size: cover;
    }

    .lan{
        display: flex;
        justify-content: space-evenly;

    }

    .lan-f{
        font-size: 18px;
    }

    .lang-ar{
        margin-top: 5px;
        margin-left: 2px;
    }

    .si{
        font-size: 14px;
    }

    span{
        font-size: 12px;
    }

    .ca{
        margin-top: 9px;
        font-size: 15px;
    }

    .cart{
        display: flex;
        justify-content: space-evenly;
    }

    .panel{
        height: 39px;
        color: white;
        display: flex;
        background-color: #222f3d;
        align-items: center;
        justify-content: space-evenly;
    }

    .paop p{
        display: inline;
        margin-left: 15px;
        
    }

    .paop{
        width: 70%;
        font-size: 0.85rem;
    }

    .meal{
        width: 60px;
        
    }

    .shop{
        font-size: 0.9rem;
        font-weight: 700;
    }

    .main{
        height: 400px;
        background-image: url("main.jpg");
        background-size: cover;
    }
    
    .items{
        background-color: #e2e7e6;
        display: flex;
        justify-content: space-evenly;
        flex-wrap: wrap;

    }

    .box{
        width: 30%;
        height: 370px;
        background-color: white;
        padding: 20px 0px 15px;
        margin: 15px;
    }

    .box h2{
        font-size: 21px;
        
        margin-left: 10px;
        margin-right: 10px;
    }

    

    .it1{
        height: 300px;
        /* width: 300px; */
        margin-left: 10px;
        margin-right: 10px;
        background-image: url("item2.jpg");
        background-size: cover;
        margin-top: 1rem;
        margin-bottom: 1rem;
    }

    .it2{
        height: 300px;
        /* width: 300px; */
        margin-left: 10px;
        margin-right: 10px;
        background-image: url("item\ 3.jpg");
        background-size: cover;
        margin-top: 1rem;
        margin-bottom: 1rem;
    }

    .it3{
        height: 300px;
        /* width: 300px; */
        margin-left: 10px;
        margin-right: 10px;
        background-image: url("item\ 4.jpg");
        background-size: cover;
        margin-top: 1rem;
        margin-bottom: 1rem;
    }

    .it4{
        height: 300px;
        /* width: 300px; */
        margin-left: 10px;
        margin-right: 10px;
        background-image: url("item\ 5.jpg");
        background-size: cover;
        margin-top: 1rem;
        margin-bottom: 1rem;
    }

    .it5{
        height: 300px;
        /* width: 300px; */
        margin-left: 10px;
        margin-right: 10px;
        background-image: url("item6.jpg");
        background-size: cover;
        margin-top: 1rem;
        margin-bottom: 1rem;
    }

    .it6{
        height: 300px;
        /* width: 300px; */
        margin-left: 10px;
        margin-right: 10px;
        background-image: url("item1.jpg");
        background-size: cover;
        margin-top: 1rem;
        margin-bottom: 1rem;
    }

    .box p{
        color: rgb(42, 109, 209);
        margin-left: 10px;
        margin-right: 10px;
    }

    .navfoobtt{
        background-color: #37475A;
        height: 49px;
        display: flex;
        justify-content: center;
        align-items: center;
        color: white;
        font-size: 13px;
    }

    footer{
        background-color: #232F3E;
        color: #DDDDDD;
    }

    .foot-content{
        height: 400px;
        display: flex;
        justify-content: space-around;
        align-items: center;
    }

    .foot-con1{
        height: 310px;
        width: 136px;
        display: flex;
        flex-direction: column;
        /* margin-left: 20px; */

    }

    .foot-bor p{
        font-size: 16px;
        color: #DDDDDD;
        margin-top: 10px;
        font-size: 14px;
    }

    .foot-cont2{
        height: 310px;
        width: 180px;
        /* margin-left: 150px; */
    }

    .foot-cont3{
        height: 310px;
        width: 222px;
        /* margin-left: 150px; */
    }

    .foot-cont4{
        height: 310px;
        width: 157px;
        /* margin-left: 150px; */
    }

    #fo-bor{
        color: white;
        font-size: 16px;
    }

    .foot-bar{
        height: 68px;
        display: flex;
        justify-content: space-evenly;
        align-items: center;
    }

    .f-logo{
        height: 40px;
        width: 75px;
        background-image: url("Amazon-Emblem.jpg");
        background-size: cover;
    }

    ._fo-cont{
        width: 450px;
        display: flex;
        align-items: center;
        justify-content: space-evenly;
       
    }
    ._fo-cont1{
        height: 40px;
        width: 117px;
        border: 1px solid white;
        display: flex;
        align-items: center;
        justify-content: space-evenly;
    }

    ._fo-cont2{
        height: 35px;
        width: 150px;
        border: 1px solid white;
        display: flex;
        align-items: center;
        justify-content: space-evenly;
    }

    ._fo-cont3{
        height: 35px;
        width: 140px;
        border: 1px solid white;
        display: flex;
        align-items: center;
        justify-content: space-evenly;
    }

    ._fo-cont3 div{
        background-image: url("image.png");
        background-size: contain;
        border-image-repeat: none;
        height: 12px;
        width: 20px;
    }

    .end{
        height: 70px;
        margin-top: 40px;
        background-color: #0f1111;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;

    }

    .div1{
        display: flex;
        justify-content: center;
    }

    .div1 p{
        margin-left: 10px;
        font-size: 12px;
    }

    .div2{
        display: flex;
        justify-content: center;
    }

    .div2 p{
        font-size: 12px;
    }

</style>
</head>
<body>
    <header>
    <div class="navbar">

        <div class="navlogout border" >
            <div class="log"></div>
            </div>

            <div class="navadd border">
                <p class="add-top">Deliver to</p>
                <div class="addicon">
                    <i class="fa-solid fa-location-dot"></i>
                <p class="add-bot">India</p>
                </div>
            </div>

            <div class="nav-search border">
                <select name="All" class="Search-select">
                    <option>All</option>
                    <input type="text" class="Search-input" placeholder="Search Amazon">
                </select>
                <div class="searchicon">
                    <i class="fa-solid fa-magnifying-glass"></i>
                </div>
            </div>

            <div class="lan border">
                <div class="flag">

                </div>
                <p class="lan-f">ES</p>
                <div class="lang-ar">
                    <i class="fa-solid fa-caret-down"></i>
                </div>
            </div>

            <div class="nav-sign border">
                <p><span >Hello, identify yourself</span></p>
                <p class="si">Accounts And Lists <i class="fa-solid fa-caret-down"></i></p>
            </div>

            <div class="order border">
                <p><span>Returns</span></p>
                <p class="si">and Orders</p>
            </div>

            <div class="cart border">
                <i style="font-size: 28px;" class="fa-brands fa-opencart"></i>
                <p class="ca"> Cart</p>
            </div>
    </div>

    <div class="panel">
        <div class="meal border">
            <i class="fa-solid fa-bars"></i>  ALL
        </div>
        <div class="paop ">
            <p>Today's Deals</p>
            <p>Customer Service</p>
            <p>Registery</p>
            <p>Gift Cards</p>
            <p>Sell</p>
        </div>
        <div class="shop border">
            Shop Deals In Electronics
        </div>
    </div>
</header>

<div class="main">
</div>

<div class="items">
    <div class="box1 box">
        <h2> Deals In PCs</h2>
        <div class="it1"></div>
        <p>shop now</p>
    </div>
    <div class="box2 box">
        <h2> Fill your Easter basket with joy</h2>
        <div class="it2"></div>
        <p>shop gifts</p>
    </div>
    <div class="box3 box">
        <h2> Top Deal's</h2>
        <div class="it3"></div>
        <p>see all deals</p>
    </div>
    <div class="box4 box">
        <h2> Players paradise start's here</h2>
        <div class="it4"></div>
        <p>shop vedio games</p>
    </div>
    <div class="box5 box">
        <h2> A Whole New Way To Work</h2>
        <div class="it5"></div>
        <p>shop personal computer's</p>
    </div>
    <div class="box6 box">
        <h2> Headsets</h2>
        <div class="it6"></div>
        <p>see more</p>
    </div>
    <!-- <div class="box3 box">
        <h2> Deals In PCs</h2>
        <div class="it1"></div>
        <p>see more</p>
    </div>
    <div class="box4 box">
        <h2> Deals In PCs</h2>
        <div class="it1"></div>
        <p>see more</p>
    </div> -->
   
</div>

<footer>
    <div class="navfoobtt">
        <p>Back to top</p>
    </div>

    <div class="foot-content">

        <div class="foot-con1 foot-bor">
            <p id="fo-bor">Get to kow us</p> 
            <p>careers</p>
            <p>Blog</p>
            <p>About Amazon</p>
            <p>Investor relations </p>
            <p>Amazon devices </p>
            <p>Amazon science </p>

        </div>

        <div class="foot-cont2 foot-bor">
            <p id="fo-bor">Make Money With Us</p> 
            <p>Sell product on Amazon</p>
            <p>Sell on Amazon Bussiness</p>
            <p>Sell Apps on Amazon</p>
            <p>Become an Affiliate</p>
            <p>Advitise your products </p>
            <p>Self Publish with US</p>
            <p>Host On Amazon Hub</p>
            <p>>See More make money <br> with us</p>
        </div>

        <div class="foot-cont3 foot-bor">
            <p id="fo-bor">Amazon Payment Products</p>
            <p>Amazon Bussiness card</p>
            <p>Shop with Points</p>
            <p>Reload Your Balance</p>
            <p>Amazon Currency Converter</p> 
        </div>

        <div class="foot-cont4 foot-bor">
            <p id="fo-bor">Let Us Help You</p>
            <p>Amazon and Covid- <br>19</p>
            <p>Your account</p>
            <p>Your Orders</p>
            <p>Shipping Rates & <br>Policies</p>
            <p>Retuens & <br>Replacements</p>
            <p>Manage Your  <br>Content and Devices</p>
            <p>Amazon Assistant</p>
            <p>Help</p>

        </div>

    </div>
<hr>
    <div class="foot-bar">
        <div class="f-logo"></div>
        <div class="_fo-cont">
            <div class="_fo-cont1">
                <i class="fa-solid fa-globe"></i> English <i style="margin-top: 5px;" class="fa-solid fa-caret-up"></i>
            </div>

            <div class="_fo-cont2">
                $ USD - U.S. Doller
            </div>

            <div class="_fo-cont3">
                <div></div>
                United States
            </div>
        </div>
    </div>

    <div class="end">
       <div class="div1">
        <p>Conditions of use </p><p>Privacy Notice</p><p>Your ads Privacy choices</p>
       </div> 

       <div class="div2">
        <p><i class="fa-solid fa-copyright"></i> 1996-2024,Amazon.com, Inc. or its affiliates</p>
       </div>
    </div>
</footer>
</body>
</html>
