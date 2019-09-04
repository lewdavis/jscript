
<html>
<script language="JavaScript">
var ct= 1;  
var price = 100.00;
var sale = 0.9;
do
{document.write("Day " + parseFloat(ct) + " had a sale price of "  + parseFloat(price) + "<br>");
price = parseFloat(price) * parseFloat(sale);
ct = ct + 1;}
while (ct < 4)
document.write("Day " + ct + " Price is: " + price + "<br>");
</script>
</html>

