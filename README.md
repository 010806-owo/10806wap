<html>
<head>
    <title>0331筆記-JS輸入 </title>
    <meta charset="'UTF-8">
    <!--html註解-->
    <style>  /*CSS註解*/

    </style>
    <SCRipt>/*JS多行註解*/    //JS單行註解
    function hello() {
        alert("hello"+name)

         name=prompt("你是誰")
         while(name=="null || name == ") {
             name=prompt("哈摟哈摟")      }
         alert("你好"+name)

         if(confirm("你確定嗎?")) {
            alert("你按了確定你按了確定");
         }else{
            alert("你按了取消")
         }
         prompt("你是誰?,阿倫")
         }
         function hello(hello) {
         elm=document.getElementById("msg");
         elm.innerHTML="hello"+name;
         console.log(elm.outerHTML)
         }
         function add(a,b){
            return a+b;
         }
         function calc(){

            elm1=document.getElementById("n1")
            elm1=document.getElementById("n2")
            elmans=document.getElementById("ans")
            n1=parseInt(elm1.value);
            if(isNaN(n1)) n1=0;//NaN: Not a Number
            n2=parseInt(elm2.value)
            if(isNaN(n2)) n2=0;

            get("ans").value=add(n1,n2);


         }



    </SCRipt>
    
 
</head>
<body>
    <button onclick="hello('Jack');">打招呼!</button>
    <button onclick="hello('Jack');">打招呼!</button>
    <div id="msg"></div>
    <input type="text">
    <input type="password">
    <input type="datetime-local">
    <input type="number">
    <input type="color">
    <input type="file">
    <input type="text"  id="n1">+<input type="text" id="n2">
    <button onclick="cale();">等於</button>
    <input type="text" id="ans">
    
</body>


</html>
