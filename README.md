# yulin
<!doctype html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>s</title>
	<script type="text/javascript">
    var str = "";
    str += "<table width=600px  border=1 rules = all  align = center>";
    for (var x= 1;x<=9;x++){

    str += "<tr>";
       for(var y=1;y<=x;y++){


    str += "<td>"+y+"&times;"+x+"="+x*y+"</td>";
    
      }
    str += "</tr>";
    //str +="<br />";
    }
    str += "</table>";
    document.write(str);
    
	</script>
</head>
<body>
	
</body>
</html>
