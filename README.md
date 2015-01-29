var r1 = 100,
	g1 = 150,
	b1 = 220,
	r2 = 220,
	g2 = 150,
	b2 = 100,
	step = 20,
	i = 0,
	r, g, b;
	
for (i = 0; i < step; i++){
 r = Math.round(r1 + i*(r2 - r1)/step);
 g = Math.round(g1 + i*(g2 - g1)/step);
 b = Math.round(b1 + i*(b2 - b1)/step);
 document.write("<div style='background:rgb("+r+","+g+","+b+");height: 10px'></div>");
}	

	
	
	
	
	
	
	
	
	
