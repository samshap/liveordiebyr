# liveordiebyr
Analysis of Covid futures based on calculator here: 	https://gabgoh.github.io/COVID/index.html									
by Samuel Shapero, Georgia Tech Research Institute														
														
Effects of R														
Assumptions, mostly from here	https://medium.com/@tomaspueyo/coronavirus-the-hammer-and-the-dance-be9337092b56 										
Population						328484431											
Initial infectious				10000											
R0								2.43							Impacts of delay of Strong Hammer				
Intervention date (days)		20							Assumptions				
I_inc							4.88							Intervention date		27		
I_inf							2.9							Otherwise same				
CFR								1.29% (for functioning system) to 4.02% (for failed system)											
Days from incubation to death 	32											
Hospital stay (days)			10.3							R	Thousands of Deaths	Date of containment	Thousands of Peak Hosp	Morbidity Rate
Recovery for mild cases (days)	11.1							0.61	20.4	128	82.4	0.9
Hospitalization rate			13.71											
Time to hospitalization (days)	5											
Containment works at 1000 infectuous														
														
R	Deaths	Days til	Peak		Assumed morbidity
	(1000s)	containment	hosp.		rate
						(1000s)
2.43	11570	170		15770		4.03									
2.31	11309	178		14850		4.03									
2.21	11060	185		14060		4.03									
2.11	10780	195		13190		4.03									
1.99	10350	long	11990		4.03									
1.90	9950	long	10960		4.03									
1.80	9460	long	9830		4.03									
1.70	8950	long	8600		4.03									
1.60	8150	long	7310		4.03									
1.51	7210	long	5940		4.03			Notes						
1.39	5560	long	4160		4.03		X	X = Deaths are undercounted, due to model cutting off after 218 days						
1.29	2074	long	2530		3.24		X	Extrapolated relationship between hospital cases and morbidity, based on granularity of model, not 						
1.19	1070	long	1160		2.48		X	Y = peak hospitalizations undercounted, due to model cutting off after 218 days						
1.09	250 	long	277			1.68		X,Y							
1.00	46.5	long	52			0.9			X							
0.90	21.3	long	41			0.9									
0.80	12.9	190		35.6		0.9									
0.70	9.3 	133		32.4		0.9									
0.61	7.4 	104		30.1		0.9									
0.51	6.3 	86		28.4		0.9									
0.39	5.3 	71		26.7		0.9									
0.34	5.1 	67		26.1		0.9									

Impacts of 7 day delay of Strong Hammer	
0.61	20.4	128		82.4		0.9
