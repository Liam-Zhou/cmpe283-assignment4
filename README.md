# cmpe283-assignment4
1.For each member in your team, provide 1 paragraph detailing what parts of the lab that member implemented / researched. (You may skip this question if you are doing the lab by yourself). 

Only myself: Yilin Zhou (sjsuid:012571026)

2.Include a sample of your print of exit count output from dmesg from “with ept” and “without ept”. 

The sample of exit count output from dmesg from “with ept”:
```
[ 6592.276858] number_of_exits =11827
[ 6613.515049] number_of_exits =11827
[ 6613.519563] number_of_exits =83150
[ 6613.522361] number_of_exits =0
[ 6613.528014] number_of_exits =0
[ 6613.538615] number_of_exits =0
[ 6613.546675] number_of_exits =0
[ 6613.555053] number_of_exits =0
[ 6613.556881] number_of_exits =27469
[ 6613.559349] number_of_exits =0
[ 6613.568051] number_of_exits =0
[ 6613.573578] number_of_exits =151913
[ 6613.581611] number_of_exits =0
[ 6613.587085] number_of_exits =251169
[ 6613.588722] number_of_exits =0
[ 6613.595996] number_of_exits =0
[ 6613.598689] number_of_exits =0
[ 6613.602909] number_of_exits =0
[ 6613.604477] number_of_exits =0
[ 6613.605668] number_of_exits =0
[ 6613.611758] number_of_exits =0
[ 6613.613041] number_of_exits =0
[ 6613.619077] number_of_exits =0
[ 6613.623239] number_of_exits =0
[ 6613.625170] number_of_exits =0
[ 6613.628573] number_of_exits =0
[ 6613.631825] number_of_exits =0
[ 6613.639438] number_of_exits =0
[ 6613.644862] number_of_exits =0
[ 6613.649732] number_of_exits =25757
[ 6613.654489] number_of_exits =2
[ 6613.660427] number_of_exits =217460
[ 6613.671462] number_of_exits =15304
[ 6613.677628] number_of_exits =720748
[ 6613.685977] number_of_exits =0
[ 6613.694686] number_of_exits =0
[ 6613.706721] not defined exit number in SDM: 0
[ 6613.712776] number_of_exits =0
[ 6613.716794] number_of_exits =0
[ 6613.721343] not defined exit number in SDM: 0
[ 6613.725632] number_of_exits =0
[ 6613.740323] number_of_exits =24931
[ 6613.746213] number_of_exits =0
[ 6613.753027] not defined exit number in SDM: 0
[ 6613.759974] number_of_exits =0
[ 6613.764083] number_of_exits =0
[ 6613.772616] number_of_exits =0
[ 6613.775179] number_of_exits =6
[ 6613.777202] number_of_exits =2
[ 6613.782437] number_of_exits =154817
[ 6613.788190] number_of_exits =59307
[ 6613.791243] number_of_exits =0
[ 6613.794781] number_of_exits =0
[ 6613.802083] number_of_exits =0
[ 6613.807689] number_of_exits =0
[ 6613.809776] number_of_exits =3
[ 6613.810944] number_of_exits =3
[ 6613.813423] number_of_exits =0
[ 6613.816426] number_of_exits =0
[ 6613.821520] number_of_exits =0
[ 6613.824088] number_of_exits =0
[ 6613.825456] number_of_exits =0
[ 6613.826711] number_of_exits =0
[ 6613.827931] number_of_exits =0
[ 6613.829739] number_of_exits =0
[ 6613.832866] number_of_exits =0
[ 6613.834634] not defined exit number in SDM: 0
[ 6613.836964] number_of_exits =0
[ 6613.839479] number_of_exits =0
```
The sample of exit count output from dmesg from “without ept”:
```
[ 6965.710042] number_of_exits =1125038
[ 6965.728336] number_of_exits =198939
[ 6965.754108] number_of_exits =0
[ 6965.787420] number_of_exits =0
[ 6965.808676] number_of_exits =0
[ 6965.833772] number_of_exits =0
[ 6965.857406] number_of_exits =0
[ 6965.875610] number_of_exits =91546
[ 6965.897573] number_of_exits =0
[ 6965.920488] number_of_exits =0
[ 6965.938111] number_of_exits =295701
[ 6965.964782] number_of_exits =0
[ 6965.985808] number_of_exits =277390
[ 6966.013073] number_of_exits =0
[ 6966.040272] number_of_exits =122838
[ 6966.070395] number_of_exits =0
[ 6966.094383] number_of_exits =0
[ 6966.122788] number_of_exits =0
[ 6966.149095] number_of_exits =0
[ 6966.172608] number_of_exits =0
[ 6966.197304] number_of_exits =0
[ 6966.221513] number_of_exits =0
[ 6966.250356] number_of_exits =0
[ 6966.272768] number_of_exits =0
[ 6966.298267] number_of_exits =0
[ 6966.322786] number_of_exits =0
[ 6966.349161] number_of_exits =0
[ 6966.372152] number_of_exits =0
[ 6966.398389] number_of_exits =7080889
[ 6966.421723] number_of_exits =4
[ 6966.449536] number_of_exits =437469
[ 6966.473793] number_of_exits =16394
[ 6966.508581] number_of_exits =920742
[ 6966.536664] number_of_exits =0
[ 6966.564416] number_of_exits =0
[ 6966.592633] not defined exit number in SDM: 0
[ 6966.627486] number_of_exits =0
[ 6966.658188] number_of_exits =0
[ 6966.683745] not defined exit number in SDM: 0
[ 6966.711574] number_of_exits =0
[ 6966.733713] number_of_exits =37172
[ 6966.759002] number_of_exits =0
[ 6966.787230] not defined exit number in SDM: 0
[ 6966.812354] number_of_exits =0
[ 6966.839581] number_of_exits =0
[ 6966.863614] number_of_exits =0
[ 6966.889013] number_of_exits =12
[ 6966.925113] number_of_exits =4
[ 6966.948999] number_of_exits =165311
[ 6966.983905] number_of_exits =60491
[ 6967.011352] number_of_exits =0
[ 6967.036130] number_of_exits =0
[ 6967.060904] number_of_exits =0
[ 6967.084755] number_of_exits =0
[ 6967.106087] number_of_exits =7
[ 6967.131161] number_of_exits =6
[ 6967.155928] number_of_exits =0
[ 6967.181022] number_of_exits =0
[ 6967.204173] number_of_exits =86213
[ 6967.227867] number_of_exits =0
[ 6967.253901] number_of_exits =0
[ 6967.286214] number_of_exits =0
[ 6967.312432] number_of_exits =0
[ 6967.336142] number_of_exits =0
[ 6967.365144] number_of_exits =0
[ 6967.390491] not defined exit number in SDM: 0
[ 6967.418610] number_of_exits =0
[ 6967.443209] number_of_exits =0
```

3.What did you learn from the count of exits? Was the count what you expected? If not, why not? 

4.What changed between the two runs (ept vs no-ept)? 


