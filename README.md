# liveordiebyr
## Analysis of Covid futures based on calculator here: 	https://gabgoh.github.io/COVID/index.html									

by Samuel A. Shapero, PhD Bioengineering														
														
### Effects of R														
Assumptions, mostly from here	https://medium.com/@tomaspueyo/coronavirus-the-hammer-and-the-dance-be9337092b56 										
* Population						331785754											
* Initial infectious				10000											
* R0								3.0										
* Intervention date (days)		20									
* I_inc							4.88		
* I_inf							2.9						
* CFR								1.6% (for functioning system) to 4.02% (for failed system)											
* Days from incubation to death 	32											
* Hospital stay (days)			10.3							
* Recovery for mild cases (days)	11.1							
* Hospitalization rate			14											
* Time to hospitalization (days)	5											
* Containment works at 10,000 infectuous														
														
R | Deaths (1000s) | Days til containment | Peak hosp. (1000s) |Assumed morbidity rate
--------|---------------|-----------------------|-------|--------
2.4		|	11591	|	144	|	15980	|	4
2.31	|	11394	|	148	|	15290	|	4
2.19	|	11090	|	156	|	14280	|	4
2.1		|	10820	|	162	|	13440	|	4
1.98	|	10403	|	172	|	12230	|	4
1.89	|	10030	|	182	|	11230	|	4
1.8		|	9594	|	193	|	10165	|	4
1.71	|	9081	|	long|	9020	|	4
1.59	|	8240	|	long|	7380	|	4
1.5		|	7446	|	long|	6070	|	4
1.41	|	6447	|	long|	4730	|	4
1.29	|	3716	|	long|	2708	|	3.2
1.2		|	1846	|	long|	1453	|	2.5
1.11	|	724		|	long|	586		|	2
0.99	|	212		|	long|	154.3	|	1.8
0.9		|	96.3	|	long|	119		|	1.6
0.81	|	52.8	|	142	|	102		|	1.4
0.69	|	35.2	|	96	|	89.3	|	1.4
0.6		|	28.5	|	78	|	82.9	|	1.4
0.51	|	24.2	|	67	|	77.9	|	1.4
0.39	|	20.4	|	57	|	72.5	|	1.4
0.33	|	19.0	|	55	|	70.4	|	1.4
							

X = Deaths are undercounted, due to model cutting off after 218 days

Y = peak hospitalizations undercounted, due to model cutting off after 218 days

Z = Extrapolated relationship between hospital cases and morbidity, based only on granularity of model

### Impacts of 7 day delay of Strong Hammer
R | Deaths (1000s) | Days til containment | Peak hosp. (1000s) |Assumed morbidity rate
--------|---------------|-----------------------|-------|--------
0.69	|	184.1	|	128	|	334		|	2
