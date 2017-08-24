# prime-number
generating the prime number using using javascript.
<html>
<body>
<script type="text/javascript">
function check(n){
for (c=2; c<=n - 1; c++){
if ( n%c == 0 ){
return false;
}
return true;
}
}

function prime(num){
if(check(num) == true){
document.write(num +"   is Prime Number" );
}else{
//document.write(num+" is Not Prime Number");
}
}

function maxnum(range){
for (i=1; i<=range; i++){
prime(i);
}
}

var range = 100;
maxnum(range);
</script>
</body>
</html>
