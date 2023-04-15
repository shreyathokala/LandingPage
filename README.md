# LandingPage
*{  margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Times New Roman', Times, serif;
    font-size: 18px;
}

body{
    background-image: url("bg1.jpg") ;
    height: 100vh;
    background-position: center center;
    background-size: 100% auto;
    font-family: 'Times New Roman', Times, serif;
    font-size: 18px;
    box-sizing: border-box;
}

.nav1{
    width: 100%;
    height: 40px;
    color:rgb(255, 255, 255);
    background-color: rgb(255,255,255);
    display: flex;
    justify-content: space-around;
    align-items: center;
    border-radius: 8px;
    position: sticky;
}

#logo{
    width: 120px;
    height: 40px;
    margin: 0 ;
}

.menu{
    text-decoration: none;
    color: darkblue;
    background-color: rgb(255, 255, 255);
    padding: 0 20px;
    justify-content: space-around;
}

.tab{
    width: 70px;
    text-align: center;
    padding: 0 30px;
    text-decoration: none;
    justify-content: space-around;
    border-radius: 6px;
    font-size: 18px;
}

#tb1{
    background-color: rgb(180, 180, 245);
    border-radius: 6px;
    color:orange;
}


.tab:hover{
    background-color: rgb(180, 180, 245);
    color: orange;
}


.nav1 i{
    cursor: pointer;
    margin:0 8px;
    width: 20px;
    height: 20;
    color: rgb(4, 135, 241);
    background-color: rgb(255,255,255);
    padding: 2px 2px;
}

.form{
    
    padding: 5px 10px;
    border:3px solid rgb(50, 205, 140);
    border-radius: 6px;
    background-color:rgb(216, 231, 250) ;
    width: 400px;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 12px;
    margin-left: 30px;
    margin-top: 18px;
    box-shadow: 8px solid rgb(4, 253, 191);
}

.form h3{
    text-transform:uppercase ;
    text-align: center;
    font-size: large;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    margin: 3px 5px;
    padding: 2px 2px;
}

.form span{
     display: block; 
     padding: 2px 2px;
     margin: 3px 5px;
     text-align: center;
     
}

.form input{
    margin: 3px 10px;
}

.btn{
    width: 350px;
    height: 25px;
    margin: 2px 5px;
    padding: 2px 5px ;
    text-align: center;
    align-items: center;
    background-color: rgb(0, 68, 255);
    border-radius: 6px;
}



.nav2{
    text-align: center;
    font-size: 9px;
    font-family: fantasy;
    background-color: rgb(12, 12, 12);
    border: 2px solid gray;
    box-sizing: border-box;
    border-radius: 6px;
    height: 30px;
    justify-content: space-between;
    padding: 5px 10px;
    margin: 3px 3px;
}

.nav2 span{
    margin: 3px 30px;
    font-family: sans-serif;
    color: tomato;
}

.nav2 p{
    color: white;
}

.content{
    color: white;
    margin-left: 40px;
    margin-right:40px;
    margin-top:30px ;
    text-align: center;
    /* border: 2px solid red; */
    display:block;
    width: 400px;
    float: right;
    padding: 5px 5px;
}

.content h3{
    margin:10px 5px;
}

.content p{
    font-size:12px;
    font-family: sans-serif;
    margin: 2px 5px;
}

.para1{
    text-align: center;
    font-size:10px;
    font-family: sans-serif;
    margin:8px 5px;
    color: rgb(243, 189, 89);
}
