function dis(akh)
{
    document.getElementById("result").value += akh
}
function akhil(a)
{
    if (a.key=='1'||a.key=='2'||a.key=='3'||a.key=='4'
    ||a.key=='5'||a.key=='6'||a.key=='7'||a.key=='8'
    ||a.key=='9'||a.key=='0'||a.key=='+'||a.key=='-'
    ||a.key=='.'||a.key=='*'||a.key=='/')
    {
        document.getElementById("result").value += a.key;
    }
}
    onkeyup = function (a)
    {
        if(a.key === "Enter"){
            solve();
        }
    }
function solve() {
    var x = document.getElementById("result").value;
    let total = 0;
    x = x.match(/[+\-]*(\.\d+|\d+(\.\d+)?)/g) || [];
    while(x.length)
    {
        total += parseFloat(x.shift());
    }
    document.getElementById("result").value =  total;
}
function clr(){
    document.getElementById("result").value = '';
   
}

