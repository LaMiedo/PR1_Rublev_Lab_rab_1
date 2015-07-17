# PR1_Rublev_Lab_rab_1
<!DOCTYPE html>
<html>
<body>

<input></input>
<button type="button" id="btn">Evaluate</button>
<p id="area"></p>

<script>
function area(l) {
        var r=l/(2*Math.PI);
        s=Math.PI*r*r;
        return s;
}

function printArea(){
        var l = document.querySelector('input').value;
        document.getElementById("area").innerHTML ="Area = " + area(l);
}

document.getElementById("btn").addEventListener("click", printArea);
</script>

</body>
</html>
