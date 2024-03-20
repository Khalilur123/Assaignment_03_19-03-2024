<!DOCTYPE html>

<html lang="en">

<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>assaignment-03</title>
<style> body {
  justify-content: center;
align-items: center;
height: 100vh;
margin: 0;
padding: 0;
font-family: Arial, sans-serif;
}

    .header {
        display: flex;
        justify-content: space-between;
        align-items: center;
        width: 1170px;
        color: rgb(52, 106, 206);
        padding: 10px 20px;
        font-size: larger;
        font-weight: bolder;
        
    
    }
    .left-text {
        flex: 1;
    }
    .right-icons {
        display: flex;
        align-items: center;
    }
    .icon {
        margin-right: 10px;
    }
    .icon img {
    width: 30px; 
    height: auto;
    }
    .button {
        background-color: #007bff;
        color: white;
        border: none;
        padding: 10px 20px;
        border-radius: 20px;
        cursor: pointer;
    }

 .background-div {
    width: 1170px; 
    height: 550px; 
    background-image: url('https://img.freepik.com/free-vector/abstract-paper-style-background_23-2150744372.jpg?w=996&t=st=1710848982~exp=1710849582~hmac=3aeca4a4c6b1631ee2e8f0d3829ff6572d8f9c62c7434c1111a482bb3564c814');
    background-size: cover; 
    background-position: center; 
    border-radius: 30px;
  }

  
  .container {
    padding: 20px;
    justify-content: center;
    align-items: center;
  }

  .content {
    color: white;
    font-size: 24px;
    text-align: center;
  }
  .conta {
    max-width: 1170px;
    color: white;
    margin: 0 auto;
    padding: 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 550px;
  }

  .left-section {
    flex: 1;
    padding-right: 20px;
    width: 565px;
    color: white;
  }

  .right-section {
    flex: 1;
    padding-left: 20px;
    border-left: 1px solid #ccc;
    width: 465px;
    color: white;
  }

  .header {
    font-size: 24px;
    font-weight: bold;
    margin-bottom: 20px;
    color: black;
  }

  .paragraph {
    margin-bottom: 20px;
  }

  .search-bar {
    width: 100%;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 30px;
    box-sizing: border-box;
    margin-bottom: 20px;
  }

  .right-box {
    background-color: #f0f0f0;
    padding: 20px;
    border-radius: 30px;
    color: black;
  }
  .secondheader {text-align: center;
  width: 1170px;
  }
  .gridcontainer {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 20px;
    max-width: 1170px;
    margin: 0 auto;
    padding: 20px;
  }

  .leftsection {
    display: grid;
    width: 770px;
    grid-template-columns: repeat(1, 1fr);
    gap: 10px;
  }

  .rightsection {
   
    display: grid;
    width: 380px;
    border-radius: 50px;
    grid-template-columns: 1fr;
    gap: 10px;
  }

  .blk {
    background-color: #f0f0f0;
    height: 250px;
    padding: 20px;
    border-radius: 30px;
  }
  .bllk {
    background-color: #f0f0f0;
    height: 400px;
    padding: 20px;
    border-radius: 30px;
  }

  .icn {
    font-size: 24px;
    margin-bottom: 10px;
  }

  .txt {
    font-size: 16px;
  }
</style>
</head>
<body>

<header class="header">
    <div class="left-text">
        ReTro
    </div>
    <div class="right-icons">
        <div class="icon">
            
            <img src="https://www.clipartmax.com/png/small/2-21103_home-house-silhouette-icon-building-transparent-background-home-icon.png" alt="Home">

        </div>
        <div class="icon">
            <img src="https://png.pngtree.com/png-vector/20190927/ourmid/pngtree-pencil-icon-png-image_1753753.jpg" alt="Edit">
        </div>
        <div class="icon">
            <img src="https://i.pinimg.com/736x/2c/6d/c1/2c6dc126da838e3632cc3e8d53d39989.jpg" alt="Sign In">
        </div>
        <div class="icon">
            <img src="https://png.pngtree.com/png-vector/20190307/ourmid/pngtree-vector-flag-icon-png-image_762945.jpg" alt="About">
        </div>
        <button class="button">Sign In</button>
    </div>
</header>
<main>
  
  <div class="container">
  <div class="background-div">
    <div class="content">
      <div class="conta">

  <div class="left-section">

    <div class="header">
      <h1 style="color: white">Welcome to the
      <br>
      <span style="color: blue; ">ReTro</span> forum</h1>
      </div>
    <p class="paragraph">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla convallis libero eget mauris pulvinar, quis tincidunt nulla semper.</p>
    <input type="text" class="search-bar" placeholder="Search here anything">
  </div>
  <div class="right-section">
    <div class="right-box">
      <div class="header">Registered Useres &nbsp; 01</div>
      <div class="header">Forum &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 05</div>
      <div class="header">Topics &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 01</div>
      <div class="header">Replies&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 01</div>
    </div>
  </div>
</div>
    
  </div>
    </div>
  </div>
</div>
    <div class="secondheader">
      <h2>
        Let's Discuss
      </h2>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla convallis libero eget mauris pulvinar, <br> quis tincidunt nulla semper.
      </p>
    </div>
    <div class="gridcontainer">
  <div class="leftsection">
    <div class="blk">
        <div style="display: flex;"> 
    <div style="margin-right: 20px;">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSX6idM5I7ijbZAKwo3gALd3s26yUCK7sIc4Q&usqp=CAU" alt="Icon" width="50px" height="50px">
    </div>
    <div>
      <p style="font-size: 16px; margin-bottom: 5px;"># Music Author: Awlad Hossain</p>
      <h3 style="margin-bottom: 5px;">10 Kids Unware of Their Halloween Costume</h3>
      <p style="margin-bottom: 20px;">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla convallis libero eget mauris pulvinar,</p>
      <hr style="margin-bottom: 20px;">
      <div style="display: flex; align-items: center;">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSzDaA-xqI2O12ThOyZ1XlKOYh_h6iGHDqEA5vR8Bx7Sg&s" alt="Icon" style="width: 30px; height: 30px; margin-right: 10px;">
        <p style="font-size: 16px; padding:10px;">560</p>
        <img src="https://img.icons8.com/?size=100&id=986&format=png" alt="Icon" style="width: 30px; height: 30px; margin-right: 10px;">
        <p style="font-size: 16px; padding:10px;">1568</p>
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRmKS7INnzTqDd3hURrEJPRxA_d6r2I8HqPuA&usqp=CAU" alt="Icon" style="width: 30px; height: 30px; margin-right: 10px;">
        <p style="font-size: 16px; padding:10px;">5 min</p>
        
        
      </div>
    </div>
  </div>
    </div>
    <div class="blk">
        <div style="display: flex;"> 
    <div style="margin-right: 20px;">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSX6idM5I7ijbZAKwo3gALd3s26yUCK7sIc4Q&usqp=CAU" alt="Icon" width="50px" height="50px">
    </div>
    <div>
      <p style="font-size: 16px; margin-bottom: 5px;"># Music Author: Awlad Hossain</p>
      <h3 style="margin-bottom: 5px;">10 Kids Unware of Their Halloween Costume</h3>
      <p style="margin-bottom: 20px;">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla convallis libero eget mauris pulvinar,</p>
      <hr style="margin-bottom: 20px;">
      <div style="display: flex; align-items: center;">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSzDaA-xqI2O12ThOyZ1XlKOYh_h6iGHDqEA5vR8Bx7Sg&s" alt="Icon" style="width: 30px; height: 30px; margin-right: 10px;">
        <p style="font-size: 16px; padding:10px;">560</p>
        <img src="https://img.icons8.com/?size=100&id=986&format=png" alt="Icon" style="width: 30px; height: 30px; margin-right: 10px;">
        <p style="font-size: 16px; padding:10px;">1568</p>
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRmKS7INnzTqDd3hURrEJPRxA_d6r2I8HqPuA&usqp=CAU" alt="Icon" style="width: 30px; height: 30px; margin-right: 10px;">
        <p style="font-size: 16px; padding:10px;">5 min</p>
        
        
      </div>
    </div>
  </div>
    </div>
    <div class="blk">
        <div style="display: flex;"> 
    <div style="margin-right: 20px;">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSX6idM5I7ijbZAKwo3gALd3s26yUCK7sIc4Q&usqp=CAU" alt="Icon" width="50px" height="50px">
    </div>
    <div>
      <p style="font-size: 16px; margin-bottom: 5px;"># Music Author: Awlad Hossain</p>
      <h3 style="margin-bottom: 5px;">10 Kids Unware of Their Halloween Costume</h3>
      <p style="margin-bottom: 20px;">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla convallis libero eget mauris pulvinar,</p>
      <hr style="margin-bottom: 20px;">
      <div style="display: flex; align-items: center;">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSzDaA-xqI2O12ThOyZ1XlKOYh_h6iGHDqEA5vR8Bx7Sg&s" alt="Icon" style="width: 30px; height: 30px; margin-right: 10px;">
        <p style="font-size: 16px; padding:10px;">560</p>
        <img src="https://img.icons8.com/?size=100&id=986&format=png" alt="Icon" style="width: 30px; height: 30px; margin-right: 10px;">
        <p style="font-size: 16px; padding:10px;">1568</p>
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRmKS7INnzTqDd3hURrEJPRxA_d6r2I8HqPuA&usqp=CAU" alt="Icon" style="width: 30px; height: 30px; margin-right: 10px;">
        <p style="font-size: 16px; padding:10px;">5 min</p>
        
        
      </div>
    </div>
  </div>
    </div>
    <div class="blk">
        <div style="display: flex;"> 
    <div style="margin-right: 20px;">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSX6idM5I7ijbZAKwo3gALd3s26yUCK7sIc4Q&usqp=CAU" alt="Icon" width="50px" height="50px">
    </div>
    <div>
      <p style="font-size: 16px; margin-bottom: 5px;"># Music Author: Awlad Hossain</p>
      <h3 style="margin-bottom: 5px;">10 Kids Unware of Their Halloween Costume</h3>
      <p style="margin-bottom: 20px;">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla convallis libero eget mauris pulvinar,</p>
      <hr style="margin-bottom: 20px;">
      <div style="display: flex; align-items: center;">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSzDaA-xqI2O12ThOyZ1XlKOYh_h6iGHDqEA5vR8Bx7Sg&s" alt="Icon" style="width: 30px; height: 30px; margin-right: 10px;">
        <p style="font-size: 16px; padding:10px;">560</p>
        <img src="https://img.icons8.com/?size=100&id=986&format=png" alt="Icon" style="width: 30px; height: 30px; margin-right: 10px;">
        <p style="font-size: 16px; padding:10px;">1568</p>
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRmKS7INnzTqDd3hURrEJPRxA_d6r2I8HqPuA&usqp=CAU" alt="Icon" style="width: 30px; height: 30px; margin-right: 10px;">
        <p style="font-size: 16px; padding:10px;">5 min</p>
        
        
      </div>
    </div>
  </div>
    </div>
    <div class="blk">
        <div style="display: flex;"> 
    <div style="margin-right: 20px;">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSX6idM5I7ijbZAKwo3gALd3s26yUCK7sIc4Q&usqp=CAU" alt="Icon" width="50px" height="50px">
    </div>
    <div>
      <p style="font-size: 16px; margin-bottom: 5px;"># Music Author: Awlad Hossain</p>
      <h3 style="margin-bottom: 5px;">10 Kids Unware of Their Halloween Costume</h3>
      <p style="margin-bottom: 20px;">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla convallis libero eget mauris pulvinar,</p>
      <hr style="margin-bottom: 20px;">
      <div style="display: flex; align-items: center;">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSzDaA-xqI2O12ThOyZ1XlKOYh_h6iGHDqEA5vR8Bx7Sg&s" alt="Icon" style="width: 30px; height: 30px; margin-right: 10px;">
        <p style="font-size: 16px; padding:10px;">560</p>
        <img src="https://img.icons8.com/?size=100&id=986&format=png" alt="Icon" style="width: 30px; height: 30px; margin-right: 10px;">
        <p style="font-size: 16px; padding:10px;">1568</p>
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRmKS7INnzTqDd3hURrEJPRxA_d6r2I8HqPuA&usqp=CAU" alt="Icon" style="width: 30px; height: 30px; margin-right: 10px;">
        <p style="font-size: 16px; padding:10px;">5 min</p>
        
        
      </div>
    </div>
  </div>
    </div>
    <div class="blk">
        <div style="display: flex;"> 
    <div style="margin-right: 20px;">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSX6idM5I7ijbZAKwo3gALd3s26yUCK7sIc4Q&usqp=CAU" alt="Icon" width="50px" height="50px">
    </div>
    <div>
      <p style="font-size: 16px; margin-bottom: 5px;"># Music Author: Awlad Hossain</p>
      <h3 style="margin-bottom: 5px;">10 Kids Unware of Their Halloween Costume</h3>
      <p style="margin-bottom: 20px;">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla convallis libero eget mauris pulvinar,</p>
      <hr style="margin-bottom: 20px;">
      <div style="display: flex; align-items: center;">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSzDaA-xqI2O12ThOyZ1XlKOYh_h6iGHDqEA5vR8Bx7Sg&s" alt="Icon" style="width: 30px; height: 30px; margin-right: 10px;">
        <p style="font-size: 16px; padding:10px;">560</p>
        <img src="https://img.icons8.com/?size=100&id=986&format=png" alt="Icon" style="width: 30px; height: 30px; margin-right: 10px;">
        <p style="font-size: 16px; padding:10px;">1568</p>
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRmKS7INnzTqDd3hURrEJPRxA_d6r2I8HqPuA&usqp=CAU" alt="Icon" style="width: 30px; height: 30px; margin-right: 10px;">
        <p style="font-size: 16px; padding:10px;">5 min</p>
        
        
      </div>
    </div>
  </div>
    </div>
    <div class="blk">
        <div style="display: flex;"> 
    <div style="margin-right: 20px;">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSX6idM5I7ijbZAKwo3gALd3s26yUCK7sIc4Q&usqp=CAU" alt="Icon" width="50px" height="50px">
    </div>
    <div>
      <p style="font-size: 16px; margin-bottom: 5px;"># Music Author: Awlad Hossain</p>
      <h3 style="margin-bottom: 5px;">10 Kids Unware of Their Halloween Costume</h3>
      <p style="margin-bottom: 20px;">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla convallis libero eget mauris pulvinar,</p>
      <hr style="margin-bottom: 20px;">
      <div style="display: flex; align-items: center;">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSzDaA-xqI2O12ThOyZ1XlKOYh_h6iGHDqEA5vR8Bx7Sg&s" alt="Icon" style="width: 30px; height: 30px; margin-right: 10px;">
        <p style="font-size: 16px; padding:10px;">560</p>
        <img src="https://img.icons8.com/?size=100&id=986&format=png" alt="Icon" style="width: 30px; height: 30px; margin-right: 10px;">
        <p style="font-size: 16px; padding:10px;">1568</p>
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRmKS7INnzTqDd3hURrEJPRxA_d6r2I8HqPuA&usqp=CAU" alt="Icon" style="width: 30px; height: 30px; margin-right: 10px;">
        <p style="font-size: 16px; padding:10px;">5 min</p>
        
        
      </div>
    </div>
  </div>
    </div>
    
  </div>
  <div class="rightsection">
    <div class="bllk">
      <div style="max-width: 1170px; margin: 20px auto; padding: 20px; border: 1px solid #ccc; border-radius: 5px;">
  <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 20px;">
    <div style="font-size: 24px;">Title</div>
    <div style="display: flex; align-items: center;">
      <span>Mark as read (4)</span>
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQlNPQyivWNXHxXH9FHCOl_AdeyiK957SA2lIQzVUZzJf-HW0IHCxhn_tA&s=10" alt="Icon" style="width: 40px; height: auto; margin-left: 10px;">
    </div>
  </div>

  <div style="display: grid; grid-template-columns: repeat(1, 1fr); gap: 20px;">
    <div style="display: flex; align-items: center; margin-bottom: 10px;">
      <div style="flex: 1; font-size: 16px;">10 Kids Unware of Their<br> Halloween Costume</div>
      <div style="margin-left: 10px;"><img src="https://img.icons8.com/?size=100&id=986&format=png" alt="Icon" style="width: 30px; height: auto;"></div>
    </div>
    <div style="display: flex; align-items: center; margin-bottom: 10px;">
      <div style="flex: 1; font-size: 16px;">10 Kids Unware of Their<br> Halloween Costume</div>
      <div style="margin-left: 10px;"><img src="https://img.icons8.com/?size=100&id=986&format=png" alt="Icon" style="width: 30px; height: auto;"></div>
    </div>
    <div style="display: flex; align-items: center; margin-bottom: 10px;">
      <div style="flex: 1; font-size: 16px;">10 Kids Unware of Their<br> Halloween Costume</div>
      <div style="margin-left: 10px;"><img src="https://img.icons8.com/?size=100&id=986&format=png" alt="Icon" style="width: 30px; height: auto;"></div>
    </div>
    <div style="display: flex; align-items: center; margin-bottom: 10px;">
      <div style="flex: 1; font-size: 16px;">10 Kids Unware of Their<br> Halloween Costume</div>
      <div style="margin-left: 10px;"><img src="https://img.icons8.com/?size=100&id=986&format=png" alt="Icon" style="width: 30px; height: auto;"></div>
    </div>
  </div>
</div>
    </div>
  </div>
</div>
<div>
  

<div style="display: flex; width: 1140px; margin: 10px auto; padding: 20px; background-color: #800000; border-radius: 20px;">
  <div style="flex: 1; padding: 20px; color: #fff;">
    <h1>Join Our Forum</h1>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla convallis libero eget mauris pulvinar</p>
    <button style="padding: 10px 20px; background-color: #007bff; color: white; border-radius: 20px; cursor: pointer;">Register Now</button>
  </div>
  <div style="flex: 1; padding: 20px; text-align: center;">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRtfDTvoFpMErTZs1ZLCV5F9qOvPu0D8JR_dYuAZtE27gA1rCMyQVuQr8Xr&s=10" alt="Picture" style="max-width: 100%; height: auto;">
  </div>
</div>
</div>
<div>
  <div class="secondheader">
      <h2>
        Latest Posts
      </h2>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla convallis libero eget mauris pulvinar, <br> quis tincidunt nulla semper.
      </p>
    </div>
</div>
<div>
  

<div style="width: 1170px; margin: 25px auto; display: flex; justify-content: space-between;">

  <div style="max-width: 380px; height: 500px; border: 3px solid #ccc; border-radius: 10px; overflow: hidden;">
    <div style="padding: 20px;">
      <div>
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS61u0AvDevn1WvQupCczp-3KINvypEUfK3J_51pBsUL_U2aWI4fvyQ8lo&s=10" alt="Picture" style="width: 100%; height: auto; border-radius: 10px;">
      </div>
      <div style="margin-top: 20px;">
        <div style="display: flex; align-items: center;">
          <img src="https://cdn0.iconfinder.com/data/icons/small-n-flat/24/678116-calendar-512.png" alt="Icon" style="width: 30px; height: 30px; margin-right: 10px;">
          <span>19 march 2024</span>
        </div>
        <div>
          <h2>I am so tired to doing all this, <br>
          im not sure that i can do</h2>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla convallis libero eget mauris pulvinar,</p>
        </div>
        <div style="display: flex; align-items: center;">
          <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRaZu5iacGxCFkz7GaRTtemqLs4f7QsPJe76fMg77SXgg&s" alt="Icon" style="width: 30px; height: 30px; margin-right: 10px;">
          <span>Cameroon Williamson</span>
        </div>
      </div>
    </div>
  </div>

  <div style="max-width: 380px; height: 500px; border: 3px solid #ccc; border-radius: 10px; overflow: hidden;">
    <div style="padding: 20px;">
      <div>
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS61u0AvDevn1WvQupCczp-3KINvypEUfK3J_51pBsUL_U2aWI4fvyQ8lo&s=10" alt="Picture" style="width: 100%; height: auto; border-radius: 10px;">
      </div>
      <div style="margin-top: 20px;">
        <div style="display: flex; align-items: center;">
          <img src="https://cdn0.iconfinder.com/data/icons/small-n-flat/24/678116-calendar-512.png" alt="Icon" style="width: 30px; height: 30px; margin-right: 10px;">
          <span>19 march 2024</span>
        </div>
        <div>
          <h2>I am so tired to doing all this, <br>
          im not sure that i can do</h2>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla convallis libero eget mauris pulvinar,</p>
        </div>
        <div style="display: flex; align-items: center;">
          <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRaZu5iacGxCFkz7GaRTtemqLs4f7QsPJe76fMg77SXgg&s" alt="Icon" style="width: 30px; height: 30px; margin-right: 10px;">
          <span>Cameroon Williamson</span>
        </div>
      </div>
      </div>
  </div>

  <div style="max-width: 380px; height: 500px; border: 3px solid #ccc; border-radius: 10px; overflow: hidden;">
    <div style="padding: 20px;">
      <div>
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS61u0AvDevn1WvQupCczp-3KINvypEUfK3J_51pBsUL_U2aWI4fvyQ8lo&s=10" alt="Picture" style="width: 100%; height: auto; border-radius: 10px;">
      </div>
      <div style="margin-top: 20px;">
        <div style="display: flex; align-items: center;">
          <img src="https://cdn0.iconfinder.com/data/icons/small-n-flat/24/678116-calendar-512.png" alt="Icon" style="width: 30px; height: 30px; margin-right: 10px;">
          <span>19 march 2024</span>
        </div>
        <div>
          <h2>I am so tired to doing all this, <br>
          im not sure that i can do</h2>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla convallis libero eget mauris pulvinar,</p>
        </div>
        <div style="display: flex; align-items: center;">
          <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRaZu5iacGxCFkz7GaRTtemqLs4f7QsPJe76fMg77SXgg&s" alt="Icon" style="width: 30px; height: 30px; margin-right: 10px;">
          <span>Cameroon Williamson</span>
        </div>
      </div>
      </div>
  </div>

</div>
</div>
<div>
  <div class="secondheader">
      <h2>
        ReTro
      </h2>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla convallis libero eget mauris pulvinar, <br> quis tincidunt nulla semper.
      </p>
      <body style="font-family: Arial, sans-serif; margin: 0; padding: 0;">

<div style="max-width: 1170px; margin: 20px auto; text-align: center;">
  <div style="display: inline-block;">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRhRjHIRI0-9PQh1F4fCzJiVbcMAVKPTcUiMvZRF9Gmfw&s" alt="Twitter" style="width: 30px; height: 30px;">
    <img src="https://upload.wikimedia.org/wikipedia/commons/5/51/Facebook_f_logo_%282019%29.svg" alt="Facebook" style="width: 30px; height: 30px;">
    <img src="https://freelogopng.com/images/all_img/1658587303instagram-png.png" alt="Instagram" style="width: 30px; height: 30px;">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTzxkrwhOuAmG45rep7_HUcCagiFiZavwahp949B2DWYg&s" alt="LinkedIn" style="width: 30px; height: 30px;">
  </div>
</div>
    </div>
</div>
</main>
<footer class="secondheader" style="text-align: center; padding: 20px;">
  <div style="border-top: 1px solid #ccc;">
  <p>2024  All rights reserved.</p>
</div>
</footer>
</body>
</html>

