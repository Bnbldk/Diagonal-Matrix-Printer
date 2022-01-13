# Diagonal-Matrix-Printer

This Algorithm was made for print (or use/check) a diagonal of a Matrix.

I was implementing a 4-in-a-row game and I would like to do a score checker in the diagonal (if there are 4 same elements in the diagonal in a row the player wins).

So this Algorithm can be implemented in multiple ways as a Matrix Diagonal Checker changing the print for any other function.



Matrix grid: 
				{ "00", "01", "02", "03", "04", "05", "06", "07", "08", "09" }
				{ "10", "11", "12", "13", "14", "15", "16", "17", "18", "19" }
				{ "20", "21", "22", "23", "24", "25", "26", "27", "28", "29" }
				{ "30", "31", "32", "33", "34", "35", "36", "37", "38", "39" }
				{ "40", "41", "42", "43", "44", "45", "46", "47", "48", "49" }
				{ "50", "51", "52", "53", "54", "55", "56", "57", "58", "59" }
				{ "60", "61", "62", "63", "64", "65", "66", "67", "68", "69" }
				{ "70", "71", "72", "73", "74", "75", "76", "77", "78", "79" }
				{ "80", "81", "82", "83", "84", "85", "86", "87", "88", "89" }
				{ "90", "91", "92", "93", "94", "95", "96", "97", "98", "99" }
        
Output:

// left to right
00 
10 01 
20 11 02 
30 21 12 03 
40 31 22 13 04 
50 41 32 23 14 05 
60 51 42 33 24 15 06 
70 61 52 43 34 25 16 07 
80 71 62 53 44 35 26 17 08 
90 81 72 63 54 45 36 27 18 09 
91 82 73 64 55 46 37 28 19 
92 83 74 65 56 47 38 29 
93 84 75 66 57 48 39 
94 85 76 67 58 49 
95 86 77 68 59 
96 87 78 69 
97 88 79 
98 89 
99 


// right to left
09 
19 08 
29 18 07 
39 28 17 06 
49 38 27 16 05 
59 48 37 26 15 04 
69 58 47 36 25 14 03 
79 68 57 46 35 24 13 02 
89 78 67 56 45 34 23 12 01 
99 88 77 66 55 44 33 22 11 00 
98 87 76 65 54 43 32 21 10 
97 86 75 64 53 42 31 20 
96 85 74 63 52 41 30 
95 84 73 62 51 40 
94 83 72 61 50 
93 82 71 60 
92 81 70 
91 80 
90 

