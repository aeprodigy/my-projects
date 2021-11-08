# my-projects
my journey
<!DOCTYPE html>
<!DOCTYPE html>
<html>
<head>
	<title>day 01</title>
	<script type="text/javascript">
		var mike = new Array("mambwe","mike","prodigy");
		document.write(mike[0]);
		document.write(mike[0]);
		function numx(name_one,name_two){
			
			document.write(name_one+ " this is it  "+name_two);
		}
		alert('day_one of a 100 days of code');
		numx("prodigy","michael");

	</script>
</head>
<body>
	<h1>DAY ONE OF A 100 DAYS OF CODE</h1>
	<P>On the first day of the hundred days of code i was dealing with the Functions and Arrays,off of the lessons i got from the newBoston.looking forward on day 2 of the 100 days of code.i have extended to learn the date Object too on the first day of code.</P>
	<br>
	<br>
<script type="text/javascript">
	 function eight(one, two){
        document.write(one+" is better than "+ two +"<br/>");
    }  
    eight("mike","bullbar"); 
</script>
<script type="text/javascript">
	var first=2;
	var second =5;
	if(first>second)
	{
		document.write("this is correct");
	}
	else{
		document.write("this is so wrong");
	}
	var second = new Array(1,2,4,6,90,78,0,123,4);
	document.write(second[4]);
</script>
<h1>The date Object</h1>
<script type="text/javascript">
	/*function printSumthing(){//this function is used to print"worked"every after 1s.,we use the setInterval function to call our first function.
		document.write("Worked!");
	}
setInterval("printSumthing()",1000);//the setInterval gives the exact time interval.*/
function printTime(){
	var now = new Date();
	var hours = now.getHours();
	var mins = now.getMinutes();
	var seconds = now.getSeconds();
	document.write(hours+":"+mins+":"+seconds+"<br />");
}
setInterval("printTime()", 1000);

</script>
</body>
</html>
