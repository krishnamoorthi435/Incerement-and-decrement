<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
    .b1,.b2,.b3{
        padding: 10px 25px;
        border-radius: 100px;
        color: rgb(0, 17, 255);
        background-color: rgb(157, 255, 0);
        text-align: center;
        display: inline-block;
        cursor: pointer;
    }
    .b1:hover,.b2:hover,.b3:hover{
        color: aliceblue;
        background-color: black;
    }
    #s1{
        padding-top: 50px;
        border: 2px solid black;
        width: 20%;

    }
    #p1{
        padding: 15px 25px;
        border: 2px solid black;
        background-color: aqua;
        margin-left: 55%;
        font-weight: bolder;
    }
</style>
<body>
    <div>
        <button class="b1" onclick="increment()">Increment</button>
        <button  class="b2"onclick="dec()">Decrement</button>
        <button class="b3" onclick="reset()">Reset</button>
    </div>
    <br>
<div>
    <span id="p1"></span>
</div>
</body>
<script>
    let cnt=0;
    function increment(){
        cnt= cnt + 1;
        document.getElementById("p1").innerHTML=cnt;
    }
    function dec(){
        cnt=cnt-1;
        document.getElementById('p1').innerHTML=cnt;
    }
    function reset(){
        cnt=0;
        document.getElementById('p1').innerHTML=cnt;
    }
</script>
</html>
