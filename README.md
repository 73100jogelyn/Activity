<!DOCTYPE html>
<html lang="en">
<xml version="1.0" encoding="UTF-8">
<html>
<head>
<title>fibonacci.html</title>	
</head>
<body style ="background-image:url(https://mathsolutions.com/wp-content/uploads/iStock-174900085-1000x667.jpg);" >
    <h3 style="text-align:center; color:rgba(8, 8, 8, 0.479)"> Fibonacci Sequence </h3>
    <script type="text/javascript">
      
      var limit = prompt("Enter the limit 'n' to generate the fibonacci sequence :", " ");
      //1,1,2,3,5,8...
      var a,b,result;
        var  a=0;
        var  b=1;
        

        document.write("The limit entered to generate the fibonacci sequence is: ",limit, "<br/>");
        document.write("The fibonacci sequence : ");
        document.write("",a," ");
        document.write("",b," ");

        var i,result;
        for(var i=2;i<limit;i++)
        {
            result=a+b;
            document.write("",result," ");
            a=b;
            b=result;
        }
        </script>
</body>
</html>
