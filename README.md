<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
.calculator-body{
    width: 250px;
    background-color: #3D3D5C;
    Margin:20px auto;
    border-radius: 10px;
    padding: 10px;px;
    padding-top: 30px;
}
.Screen{
    background-color: #a1af77;
    text-align: right;
    width: 320px;
    display: block;
    margin: 0auto;
    font-size: 25px;
    padding: 10px;
    margin-bottom: 20px;
}
.button-container{
    height: 200px;
    display: flex;
    flex-direction: coloumn;
    flex-wrap: wrap;
    justify-content: space-between;
    align-items: centre;
}
.btn{
    width:50px;
    text-align: center;
    padding: 2px 0;
    font-size: 20px;
    margin:3px;
    border: 0.5px solid black;
    border-radius: 5px;
    cursor: pointer;
}
.btn:hover{
    box-shadow: 0 05px;
    transition: 5;
}
</style>
<body>
    <div class="calculator-body">
        <input type="text"value="0"class="screen"/>
         <button class="btn">AC</button>
         <button class="btn">0</button>
         <button class="btn">1</button>
         <button class="btn">2</button>
         <button class="btn">3</button>

         <button class="btn">4</button>
         <button class="btn">5</button>
         <button class="btn">6</button>
         <button class="btn">7</button>
         <button class="btn">8</button>
         
         <button class="btn">9</button>
         <button class="btn">0</button>
         <button class="btn">M+</button>
         <button class="btn">/</button>
         <button class="btn">%</button>
         
         <button class="btn">X</button>
         <button class="btn">-</button>
         <button class="btn">+</button>
         <button class="btn">=</button>
    </div>    
 </div>
</body>
</html>
