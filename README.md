<?php
include 'components/connect.php';
session_start();

if(isset($_SESSION['user_id'])){
    $user_id = $_SESSION['user_id'];
}else{
    $user_id = '';
}


?>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>home</title>
    <!-- font awesoeme cdn link -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css">
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <!-- header section -->
    <?php include 'components/user_header.php' ?>


    <!-- home section -->

<section class="home">

<div class="home-slider">
    <div class="w">
        <div class="slide">

        <div class="content">
            <span> order online</span>
            <h3> delicious pizza</h3>
            <a href="menu.php" class="btn"> see menu</a>
        </div>
        <div class="image">
            <img src="images/elements/13.jpg" alt="">
        </div>
        </div>
    </div>
</div>
<div class="home-slider">
    <div class="w">
        <div class="slide">

        <div class="content">
            <span> order online</span>
            <h3> delicious chizzey</h3>
            <a href="menu.php" class="btn"> see menu</a>
        </div>
        <div class="image">
            <img src="images/elements/17.jpg" alt="">
        </div>
        </div>
    </div>
</div><div class="home-slider">
    <div class="w">
        <div class="slide">

        <div class="content">
            <span> order online</span>
            <h3> delicious roasted chicken</h3>
            <a href="menu.php" class="btn"> see menu</a>
        </div>
        <div class="image">
            <img src="images/elements/12.jpg" alt="">
        </div>
        </div>
    </div>
</div>
</section>

    footer section


</body>
</html>
