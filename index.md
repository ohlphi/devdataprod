---
title       : The storm app
subtitle    : An app showing the financial and human impact of weather events in the USA
author      : Philip Ohlsson
job         : Anayst
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## The Storm App

The Storm App lets you check the financial and human impact weather events have had on states in the United States between 1950 to 2011.

Simply choose whether you wish to check the financial impact of weather events by selecting: 

- Property Damage
- Crop Damage or
- Property and Crop Damage combined

Or choose the human impact of weather events by selecting: 

- Fatalities
- Injuries or
- Fatalities and Injuries combined

--- .class #id


## Slide 2

Why is it not working?



<div id = 'chart37430fed6b9' class = 'rChart nvd3'></div>
<script type='text/javascript'>
 $(document).ready(function(){
      drawchart37430fed6b9()
    });
    function drawchart37430fed6b9(){  
      var opts = {
 "dom": "chart37430fed6b9",
"width":    800,
"height":    400,
"x": "Year",
"y": "value",
"group": "State",
"type": "lineChart",
"id": "chart37430fed6b9" 
},
        data = [
 {
 "X": 3101,
"State": "AK",
"Year": 1950,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3102,
"State": "AK",
"Year": 1951,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3103,
"State": "AK",
"Year": 1952,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3104,
"State": "AK",
"Year": 1953,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3105,
"State": "AK",
"Year": 1954,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3106,
"State": "AK",
"Year": 1955,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3107,
"State": "AK",
"Year": 1956,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3108,
"State": "AK",
"Year": 1957,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3109,
"State": "AK",
"Year": 1958,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3110,
"State": "AK",
"Year": 1959,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3111,
"State": "AK",
"Year": 1960,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3112,
"State": "AK",
"Year": 1961,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3113,
"State": "AK",
"Year": 1962,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3114,
"State": "AK",
"Year": 1963,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3115,
"State": "AK",
"Year": 1964,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3116,
"State": "AK",
"Year": 1965,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3117,
"State": "AK",
"Year": 1966,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3118,
"State": "AK",
"Year": 1967,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3119,
"State": "AK",
"Year": 1968,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3120,
"State": "AK",
"Year": 1969,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3121,
"State": "AK",
"Year": 1970,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3122,
"State": "AK",
"Year": 1971,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3123,
"State": "AK",
"Year": 1972,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3124,
"State": "AK",
"Year": 1973,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3125,
"State": "AK",
"Year": 1974,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3126,
"State": "AK",
"Year": 1975,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3127,
"State": "AK",
"Year": 1976,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3128,
"State": "AK",
"Year": 1977,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3129,
"State": "AK",
"Year": 1978,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3130,
"State": "AK",
"Year": 1979,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3131,
"State": "AK",
"Year": 1980,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3132,
"State": "AK",
"Year": 1981,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3133,
"State": "AK",
"Year": 1982,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3134,
"State": "AK",
"Year": 1983,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3135,
"State": "AK",
"Year": 1984,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3136,
"State": "AK",
"Year": 1985,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3137,
"State": "AK",
"Year": 1986,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3138,
"State": "AK",
"Year": 1987,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3139,
"State": "AK",
"Year": 1988,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3140,
"State": "AK",
"Year": 1989,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3141,
"State": "AK",
"Year": 1990,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3142,
"State": "AK",
"Year": 1991,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3143,
"State": "AK",
"Year": 1992,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3144,
"State": "AK",
"Year": 1993,
"variable": "Injuries",
"value":              3 
},
{
 "X": 3145,
"State": "AK",
"Year": 1994,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3146,
"State": "AK",
"Year": 1995,
"variable": "Injuries",
"value":              5 
},
{
 "X": 3147,
"State": "AK",
"Year": 1996,
"variable": "Injuries",
"value":             29 
},
{
 "X": 3148,
"State": "AK",
"Year": 1997,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3149,
"State": "AK",
"Year": 1998,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3150,
"State": "AK",
"Year": 1999,
"variable": "Injuries",
"value":             14 
},
{
 "X": 3151,
"State": "AK",
"Year": 2000,
"variable": "Injuries",
"value":             18 
},
{
 "X": 3152,
"State": "AK",
"Year": 2001,
"variable": "Injuries",
"value":             13 
},
{
 "X": 3153,
"State": "AK",
"Year": 2002,
"variable": "Injuries",
"value":              4 
},
{
 "X": 3154,
"State": "AK",
"Year": 2003,
"variable": "Injuries",
"value":              3 
},
{
 "X": 3155,
"State": "AK",
"Year": 2004,
"variable": "Injuries",
"value":             12 
},
{
 "X": 3156,
"State": "AK",
"Year": 2005,
"variable": "Injuries",
"value":              7 
},
{
 "X": 3157,
"State": "AK",
"Year": 2006,
"variable": "Injuries",
"value":              2 
},
{
 "X": 3158,
"State": "AK",
"Year": 2007,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3159,
"State": "AK",
"Year": 2008,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3160,
"State": "AK",
"Year": 2009,
"variable": "Injuries",
"value":              2 
},
{
 "X": 3161,
"State": "AK",
"Year": 2010,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3162,
"State": "AK",
"Year": 2011,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3163,
"State": "AL",
"Year": 1950,
"variable": "Injuries",
"value":             15 
},
{
 "X": 3164,
"State": "AL",
"Year": 1951,
"variable": "Injuries",
"value":             13 
},
{
 "X": 3165,
"State": "AL",
"Year": 1952,
"variable": "Injuries",
"value":            116 
},
{
 "X": 3166,
"State": "AL",
"Year": 1953,
"variable": "Injuries",
"value":            248 
},
{
 "X": 3167,
"State": "AL",
"Year": 1954,
"variable": "Injuries",
"value":             36 
},
{
 "X": 3168,
"State": "AL",
"Year": 1955,
"variable": "Injuries",
"value":             27 
},
{
 "X": 3169,
"State": "AL",
"Year": 1956,
"variable": "Injuries",
"value":            203 
},
{
 "X": 3170,
"State": "AL",
"Year": 1957,
"variable": "Injuries",
"value":            192 
},
{
 "X": 3171,
"State": "AL",
"Year": 1958,
"variable": "Injuries",
"value":              3 
},
{
 "X": 3172,
"State": "AL",
"Year": 1959,
"variable": "Injuries",
"value":              8 
},
{
 "X": 3173,
"State": "AL",
"Year": 1960,
"variable": "Injuries",
"value":              2 
},
{
 "X": 3174,
"State": "AL",
"Year": 1961,
"variable": "Injuries",
"value":             28 
},
{
 "X": 3175,
"State": "AL",
"Year": 1962,
"variable": "Injuries",
"value":             10 
},
{
 "X": 3176,
"State": "AL",
"Year": 1963,
"variable": "Injuries",
"value":             76 
},
{
 "X": 3177,
"State": "AL",
"Year": 1964,
"variable": "Injuries",
"value":             31 
},
{
 "X": 3178,
"State": "AL",
"Year": 1965,
"variable": "Injuries",
"value":             44 
},
{
 "X": 3179,
"State": "AL",
"Year": 1966,
"variable": "Injuries",
"value":             17 
},
{
 "X": 3180,
"State": "AL",
"Year": 1967,
"variable": "Injuries",
"value":             97 
},
{
 "X": 3181,
"State": "AL",
"Year": 1968,
"variable": "Injuries",
"value":             46 
},
{
 "X": 3182,
"State": "AL",
"Year": 1969,
"variable": "Injuries",
"value":             16 
},
{
 "X": 3183,
"State": "AL",
"Year": 1970,
"variable": "Injuries",
"value":             16 
},
{
 "X": 3184,
"State": "AL",
"Year": 1971,
"variable": "Injuries",
"value":             16 
},
{
 "X": 3185,
"State": "AL",
"Year": 1972,
"variable": "Injuries",
"value":             95 
},
{
 "X": 3186,
"State": "AL",
"Year": 1973,
"variable": "Injuries",
"value":            408 
},
{
 "X": 3187,
"State": "AL",
"Year": 1974,
"variable": "Injuries",
"value":            959 
},
{
 "X": 3188,
"State": "AL",
"Year": 1975,
"variable": "Injuries",
"value":            142 
},
{
 "X": 3189,
"State": "AL",
"Year": 1976,
"variable": "Injuries",
"value":             61 
},
{
 "X": 3190,
"State": "AL",
"Year": 1977,
"variable": "Injuries",
"value":            144 
},
{
 "X": 3191,
"State": "AL",
"Year": 1978,
"variable": "Injuries",
"value":             49 
},
{
 "X": 3192,
"State": "AL",
"Year": 1979,
"variable": "Injuries",
"value":             44 
},
{
 "X": 3193,
"State": "AL",
"Year": 1980,
"variable": "Injuries",
"value":             26 
},
{
 "X": 3194,
"State": "AL",
"Year": 1981,
"variable": "Injuries",
"value":             90 
},
{
 "X": 3195,
"State": "AL",
"Year": 1982,
"variable": "Injuries",
"value":             18 
},
{
 "X": 3196,
"State": "AL",
"Year": 1983,
"variable": "Injuries",
"value":            105 
},
{
 "X": 3197,
"State": "AL",
"Year": 1984,
"variable": "Injuries",
"value":             78 
},
{
 "X": 3198,
"State": "AL",
"Year": 1985,
"variable": "Injuries",
"value":             49 
},
{
 "X": 3199,
"State": "AL",
"Year": 1986,
"variable": "Injuries",
"value":             36 
},
{
 "X": 3200,
"State": "AL",
"Year": 1987,
"variable": "Injuries",
"value":              5 
},
{
 "X": 3201,
"State": "AL",
"Year": 1988,
"variable": "Injuries",
"value":             59 
},
{
 "X": 3202,
"State": "AL",
"Year": 1989,
"variable": "Injuries",
"value":            499 
},
{
 "X": 3203,
"State": "AL",
"Year": 1990,
"variable": "Injuries",
"value":            170 
},
{
 "X": 3204,
"State": "AL",
"Year": 1991,
"variable": "Injuries",
"value":             52 
},
{
 "X": 3205,
"State": "AL",
"Year": 1992,
"variable": "Injuries",
"value":             76 
},
{
 "X": 3206,
"State": "AL",
"Year": 1993,
"variable": "Injuries",
"value":             18 
},
{
 "X": 3207,
"State": "AL",
"Year": 1994,
"variable": "Injuries",
"value":            287 
},
{
 "X": 3208,
"State": "AL",
"Year": 1995,
"variable": "Injuries",
"value":            305 
},
{
 "X": 3209,
"State": "AL",
"Year": 1996,
"variable": "Injuries",
"value":            116 
},
{
 "X": 3210,
"State": "AL",
"Year": 1997,
"variable": "Injuries",
"value":             68 
},
{
 "X": 3211,
"State": "AL",
"Year": 1998,
"variable": "Injuries",
"value":            298 
},
{
 "X": 3212,
"State": "AL",
"Year": 1999,
"variable": "Injuries",
"value":             19 
},
{
 "X": 3213,
"State": "AL",
"Year": 2000,
"variable": "Injuries",
"value":            222 
},
{
 "X": 3214,
"State": "AL",
"Year": 2001,
"variable": "Injuries",
"value":            169 
},
{
 "X": 3215,
"State": "AL",
"Year": 2002,
"variable": "Injuries",
"value":            158 
},
{
 "X": 3216,
"State": "AL",
"Year": 2003,
"variable": "Injuries",
"value":             17 
},
{
 "X": 3217,
"State": "AL",
"Year": 2004,
"variable": "Injuries",
"value":             28 
},
{
 "X": 3218,
"State": "AL",
"Year": 2005,
"variable": "Injuries",
"value":             36 
},
{
 "X": 3219,
"State": "AL",
"Year": 2006,
"variable": "Injuries",
"value":             29 
},
{
 "X": 3220,
"State": "AL",
"Year": 2007,
"variable": "Injuries",
"value":             99 
},
{
 "X": 3221,
"State": "AL",
"Year": 2008,
"variable": "Injuries",
"value":            138 
},
{
 "X": 3222,
"State": "AL",
"Year": 2009,
"variable": "Injuries",
"value":             58 
},
{
 "X": 3223,
"State": "AL",
"Year": 2010,
"variable": "Injuries",
"value":             85 
},
{
 "X": 3224,
"State": "AL",
"Year": 2011,
"variable": "Injuries",
"value":           2167 
},
{
 "X": 3225,
"State": "AR",
"Year": 1950,
"variable": "Injuries",
"value":             49 
},
{
 "X": 3226,
"State": "AR",
"Year": 1951,
"variable": "Injuries",
"value":              7 
},
{
 "X": 3227,
"State": "AR",
"Year": 1952,
"variable": "Injuries",
"value":            731 
},
{
 "X": 3228,
"State": "AR",
"Year": 1953,
"variable": "Injuries",
"value":              9 
},
{
 "X": 3229,
"State": "AR",
"Year": 1954,
"variable": "Injuries",
"value":             38 
},
{
 "X": 3230,
"State": "AR",
"Year": 1955,
"variable": "Injuries",
"value":             33 
},
{
 "X": 3231,
"State": "AR",
"Year": 1956,
"variable": "Injuries",
"value":             19 
},
{
 "X": 3232,
"State": "AR",
"Year": 1957,
"variable": "Injuries",
"value":             30 
},
{
 "X": 3233,
"State": "AR",
"Year": 1958,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3234,
"State": "AR",
"Year": 1959,
"variable": "Injuries",
"value":             39 
},
{
 "X": 3235,
"State": "AR",
"Year": 1960,
"variable": "Injuries",
"value":             58 
},
{
 "X": 3236,
"State": "AR",
"Year": 1961,
"variable": "Injuries",
"value":            100 
},
{
 "X": 3237,
"State": "AR",
"Year": 1962,
"variable": "Injuries",
"value":              4 
},
{
 "X": 3238,
"State": "AR",
"Year": 1963,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3239,
"State": "AR",
"Year": 1964,
"variable": "Injuries",
"value":              7 
},
{
 "X": 3240,
"State": "AR",
"Year": 1965,
"variable": "Injuries",
"value":            225 
},
{
 "X": 3241,
"State": "AR",
"Year": 1966,
"variable": "Injuries",
"value":              2 
},
{
 "X": 3242,
"State": "AR",
"Year": 1967,
"variable": "Injuries",
"value":             28 
},
{
 "X": 3243,
"State": "AR",
"Year": 1968,
"variable": "Injuries",
"value":            723 
},
{
 "X": 3244,
"State": "AR",
"Year": 1969,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3245,
"State": "AR",
"Year": 1970,
"variable": "Injuries",
"value":             85 
},
{
 "X": 3246,
"State": "AR",
"Year": 1971,
"variable": "Injuries",
"value":             29 
},
{
 "X": 3247,
"State": "AR",
"Year": 1972,
"variable": "Injuries",
"value":              3 
},
{
 "X": 3248,
"State": "AR",
"Year": 1973,
"variable": "Injuries",
"value":            396 
},
{
 "X": 3249,
"State": "AR",
"Year": 1974,
"variable": "Injuries",
"value":            114 
},
{
 "X": 3250,
"State": "AR",
"Year": 1975,
"variable": "Injuries",
"value":             86 
},
{
 "X": 3251,
"State": "AR",
"Year": 1976,
"variable": "Injuries",
"value":            124 
},
{
 "X": 3252,
"State": "AR",
"Year": 1977,
"variable": "Injuries",
"value":              7 
},
{
 "X": 3253,
"State": "AR",
"Year": 1978,
"variable": "Injuries",
"value":             34 
},
{
 "X": 3254,
"State": "AR",
"Year": 1979,
"variable": "Injuries",
"value":             59 
},
{
 "X": 3255,
"State": "AR",
"Year": 1980,
"variable": "Injuries",
"value":            113 
},
{
 "X": 3256,
"State": "AR",
"Year": 1981,
"variable": "Injuries",
"value":             10 
},
{
 "X": 3257,
"State": "AR",
"Year": 1982,
"variable": "Injuries",
"value":            218 
},
{
 "X": 3258,
"State": "AR",
"Year": 1983,
"variable": "Injuries",
"value":             13 
},
{
 "X": 3259,
"State": "AR",
"Year": 1984,
"variable": "Injuries",
"value":             89 
},
{
 "X": 3260,
"State": "AR",
"Year": 1985,
"variable": "Injuries",
"value":             21 
},
{
 "X": 3261,
"State": "AR",
"Year": 1986,
"variable": "Injuries",
"value":             35 
},
{
 "X": 3262,
"State": "AR",
"Year": 1987,
"variable": "Injuries",
"value":            111 
},
{
 "X": 3263,
"State": "AR",
"Year": 1988,
"variable": "Injuries",
"value":            125 
},
{
 "X": 3264,
"State": "AR",
"Year": 1989,
"variable": "Injuries",
"value":             22 
},
{
 "X": 3265,
"State": "AR",
"Year": 1990,
"variable": "Injuries",
"value":             14 
},
{
 "X": 3266,
"State": "AR",
"Year": 1991,
"variable": "Injuries",
"value":             21 
},
{
 "X": 3267,
"State": "AR",
"Year": 1992,
"variable": "Injuries",
"value":              2 
},
{
 "X": 3268,
"State": "AR",
"Year": 1993,
"variable": "Injuries",
"value":             14 
},
{
 "X": 3269,
"State": "AR",
"Year": 1994,
"variable": "Injuries",
"value":             21 
},
{
 "X": 3270,
"State": "AR",
"Year": 1995,
"variable": "Injuries",
"value":             25 
},
{
 "X": 3271,
"State": "AR",
"Year": 1996,
"variable": "Injuries",
"value":            169 
},
{
 "X": 3272,
"State": "AR",
"Year": 1997,
"variable": "Injuries",
"value":            456 
},
{
 "X": 3273,
"State": "AR",
"Year": 1998,
"variable": "Injuries",
"value":             24 
},
{
 "X": 3274,
"State": "AR",
"Year": 1999,
"variable": "Injuries",
"value":            187 
},
{
 "X": 3275,
"State": "AR",
"Year": 2000,
"variable": "Injuries",
"value":             26 
},
{
 "X": 3276,
"State": "AR",
"Year": 2001,
"variable": "Injuries",
"value":             42 
},
{
 "X": 3277,
"State": "AR",
"Year": 2002,
"variable": "Injuries",
"value":             28 
},
{
 "X": 3278,
"State": "AR",
"Year": 2003,
"variable": "Injuries",
"value":             21 
},
{
 "X": 3279,
"State": "AR",
"Year": 2004,
"variable": "Injuries",
"value":             23 
},
{
 "X": 3280,
"State": "AR",
"Year": 2005,
"variable": "Injuries",
"value":             36 
},
{
 "X": 3281,
"State": "AR",
"Year": 2006,
"variable": "Injuries",
"value":             86 
},
{
 "X": 3282,
"State": "AR",
"Year": 2007,
"variable": "Injuries",
"value":             49 
},
{
 "X": 3283,
"State": "AR",
"Year": 2008,
"variable": "Injuries",
"value":            243 
},
{
 "X": 3284,
"State": "AR",
"Year": 2009,
"variable": "Injuries",
"value":             77 
},
{
 "X": 3285,
"State": "AR",
"Year": 2010,
"variable": "Injuries",
"value":             69 
},
{
 "X": 3286,
"State": "AR",
"Year": 2011,
"variable": "Injuries",
"value":            120 
},
{
 "X": 3287,
"State": "AZ",
"Year": 1950,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3288,
"State": "AZ",
"Year": 1951,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3289,
"State": "AZ",
"Year": 1952,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3290,
"State": "AZ",
"Year": 1953,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3291,
"State": "AZ",
"Year": 1954,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3292,
"State": "AZ",
"Year": 1955,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3293,
"State": "AZ",
"Year": 1956,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3294,
"State": "AZ",
"Year": 1957,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3295,
"State": "AZ",
"Year": 1958,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3296,
"State": "AZ",
"Year": 1959,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3297,
"State": "AZ",
"Year": 1960,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3298,
"State": "AZ",
"Year": 1961,
"variable": "Injuries",
"value":              3 
},
{
 "X": 3299,
"State": "AZ",
"Year": 1962,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3300,
"State": "AZ",
"Year": 1963,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3301,
"State": "AZ",
"Year": 1964,
"variable": "Injuries",
"value":              9 
},
{
 "X": 3302,
"State": "AZ",
"Year": 1965,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3303,
"State": "AZ",
"Year": 1966,
"variable": "Injuries",
"value":              9 
},
{
 "X": 3304,
"State": "AZ",
"Year": 1967,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3305,
"State": "AZ",
"Year": 1968,
"variable": "Injuries",
"value":              8 
},
{
 "X": 3306,
"State": "AZ",
"Year": 1969,
"variable": "Injuries",
"value":              2 
},
{
 "X": 3307,
"State": "AZ",
"Year": 1970,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3308,
"State": "AZ",
"Year": 1971,
"variable": "Injuries",
"value":             43 
},
{
 "X": 3309,
"State": "AZ",
"Year": 1972,
"variable": "Injuries",
"value":             18 
},
{
 "X": 3310,
"State": "AZ",
"Year": 1973,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3311,
"State": "AZ",
"Year": 1974,
"variable": "Injuries",
"value":             40 
},
{
 "X": 3312,
"State": "AZ",
"Year": 1975,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3313,
"State": "AZ",
"Year": 1976,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3314,
"State": "AZ",
"Year": 1977,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3315,
"State": "AZ",
"Year": 1978,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3316,
"State": "AZ",
"Year": 1979,
"variable": "Injuries",
"value":              3 
},
{
 "X": 3317,
"State": "AZ",
"Year": 1980,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3318,
"State": "AZ",
"Year": 1981,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3319,
"State": "AZ",
"Year": 1982,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3320,
"State": "AZ",
"Year": 1983,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3321,
"State": "AZ",
"Year": 1984,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3322,
"State": "AZ",
"Year": 1985,
"variable": "Injuries",
"value":             24 
},
{
 "X": 3323,
"State": "AZ",
"Year": 1986,
"variable": "Injuries",
"value":              2 
},
{
 "X": 3324,
"State": "AZ",
"Year": 1987,
"variable": "Injuries",
"value":              4 
},
{
 "X": 3325,
"State": "AZ",
"Year": 1988,
"variable": "Injuries",
"value":             29 
},
{
 "X": 3326,
"State": "AZ",
"Year": 1989,
"variable": "Injuries",
"value":              3 
},
{
 "X": 3327,
"State": "AZ",
"Year": 1990,
"variable": "Injuries",
"value":             24 
},
{
 "X": 3328,
"State": "AZ",
"Year": 1991,
"variable": "Injuries",
"value":              4 
},
{
 "X": 3329,
"State": "AZ",
"Year": 1992,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3330,
"State": "AZ",
"Year": 1993,
"variable": "Injuries",
"value":             12 
},
{
 "X": 3331,
"State": "AZ",
"Year": 1994,
"variable": "Injuries",
"value":             26 
},
{
 "X": 3332,
"State": "AZ",
"Year": 1995,
"variable": "Injuries",
"value":             67 
},
{
 "X": 3333,
"State": "AZ",
"Year": 1996,
"variable": "Injuries",
"value":             53 
},
{
 "X": 3334,
"State": "AZ",
"Year": 1997,
"variable": "Injuries",
"value":            160 
},
{
 "X": 3335,
"State": "AZ",
"Year": 1998,
"variable": "Injuries",
"value":             11 
},
{
 "X": 3336,
"State": "AZ",
"Year": 1999,
"variable": "Injuries",
"value":             61 
},
{
 "X": 3337,
"State": "AZ",
"Year": 2000,
"variable": "Injuries",
"value":             44 
},
{
 "X": 3338,
"State": "AZ",
"Year": 2001,
"variable": "Injuries",
"value":             27 
},
{
 "X": 3339,
"State": "AZ",
"Year": 2002,
"variable": "Injuries",
"value":             11 
},
{
 "X": 3340,
"State": "AZ",
"Year": 2003,
"variable": "Injuries",
"value":             36 
},
{
 "X": 3341,
"State": "AZ",
"Year": 2004,
"variable": "Injuries",
"value":             18 
},
{
 "X": 3342,
"State": "AZ",
"Year": 2005,
"variable": "Injuries",
"value":             17 
},
{
 "X": 3343,
"State": "AZ",
"Year": 2006,
"variable": "Injuries",
"value":             26 
},
{
 "X": 3344,
"State": "AZ",
"Year": 2007,
"variable": "Injuries",
"value":              6 
},
{
 "X": 3345,
"State": "AZ",
"Year": 2008,
"variable": "Injuries",
"value":             82 
},
{
 "X": 3346,
"State": "AZ",
"Year": 2009,
"variable": "Injuries",
"value":             19 
},
{
 "X": 3347,
"State": "AZ",
"Year": 2010,
"variable": "Injuries",
"value":             38 
},
{
 "X": 3348,
"State": "AZ",
"Year": 2011,
"variable": "Injuries",
"value":             26 
},
{
 "X": 3349,
"State": "CA",
"Year": 1950,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3350,
"State": "CA",
"Year": 1951,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3351,
"State": "CA",
"Year": 1952,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3352,
"State": "CA",
"Year": 1953,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3353,
"State": "CA",
"Year": 1954,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3354,
"State": "CA",
"Year": 1955,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3355,
"State": "CA",
"Year": 1956,
"variable": "Injuries",
"value":              2 
},
{
 "X": 3356,
"State": "CA",
"Year": 1957,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3357,
"State": "CA",
"Year": 1958,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3358,
"State": "CA",
"Year": 1959,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3359,
"State": "CA",
"Year": 1960,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3360,
"State": "CA",
"Year": 1961,
"variable": "Injuries",
"value":              3 
},
{
 "X": 3361,
"State": "CA",
"Year": 1962,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3362,
"State": "CA",
"Year": 1963,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3363,
"State": "CA",
"Year": 1964,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3364,
"State": "CA",
"Year": 1965,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3365,
"State": "CA",
"Year": 1966,
"variable": "Injuries",
"value":             10 
},
{
 "X": 3366,
"State": "CA",
"Year": 1967,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3367,
"State": "CA",
"Year": 1968,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3368,
"State": "CA",
"Year": 1969,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3369,
"State": "CA",
"Year": 1970,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3370,
"State": "CA",
"Year": 1971,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3371,
"State": "CA",
"Year": 1972,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3372,
"State": "CA",
"Year": 1973,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3373,
"State": "CA",
"Year": 1974,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3374,
"State": "CA",
"Year": 1975,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3375,
"State": "CA",
"Year": 1976,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3376,
"State": "CA",
"Year": 1977,
"variable": "Injuries",
"value":              4 
},
{
 "X": 3377,
"State": "CA",
"Year": 1978,
"variable": "Injuries",
"value":              7 
},
{
 "X": 3378,
"State": "CA",
"Year": 1979,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3379,
"State": "CA",
"Year": 1980,
"variable": "Injuries",
"value":              4 
},
{
 "X": 3380,
"State": "CA",
"Year": 1981,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3381,
"State": "CA",
"Year": 1982,
"variable": "Injuries",
"value":              3 
},
{
 "X": 3382,
"State": "CA",
"Year": 1983,
"variable": "Injuries",
"value":             34 
},
{
 "X": 3383,
"State": "CA",
"Year": 1984,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3384,
"State": "CA",
"Year": 1985,
"variable": "Injuries",
"value":              4 
},
{
 "X": 3385,
"State": "CA",
"Year": 1986,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3386,
"State": "CA",
"Year": 1987,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3387,
"State": "CA",
"Year": 1988,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3388,
"State": "CA",
"Year": 1989,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3389,
"State": "CA",
"Year": 1990,
"variable": "Injuries",
"value":              8 
},
{
 "X": 3390,
"State": "CA",
"Year": 1991,
"variable": "Injuries",
"value":              3 
},
{
 "X": 3391,
"State": "CA",
"Year": 1992,
"variable": "Injuries",
"value":              6 
},
{
 "X": 3392,
"State": "CA",
"Year": 1993,
"variable": "Injuries",
"value":            288 
},
{
 "X": 3393,
"State": "CA",
"Year": 1994,
"variable": "Injuries",
"value":             65 
},
{
 "X": 3394,
"State": "CA",
"Year": 1995,
"variable": "Injuries",
"value":             66 
},
{
 "X": 3395,
"State": "CA",
"Year": 1996,
"variable": "Injuries",
"value":             55 
},
{
 "X": 3396,
"State": "CA",
"Year": 1997,
"variable": "Injuries",
"value":            139 
},
{
 "X": 3397,
"State": "CA",
"Year": 1998,
"variable": "Injuries",
"value":            251 
},
{
 "X": 3398,
"State": "CA",
"Year": 1999,
"variable": "Injuries",
"value":            274 
},
{
 "X": 3399,
"State": "CA",
"Year": 2000,
"variable": "Injuries",
"value":            313 
},
{
 "X": 3400,
"State": "CA",
"Year": 2001,
"variable": "Injuries",
"value":            241 
},
{
 "X": 3401,
"State": "CA",
"Year": 2002,
"variable": "Injuries",
"value":            362 
},
{
 "X": 3402,
"State": "CA",
"Year": 2003,
"variable": "Injuries",
"value":            444 
},
{
 "X": 3403,
"State": "CA",
"Year": 2004,
"variable": "Injuries",
"value":            107 
},
{
 "X": 3404,
"State": "CA",
"Year": 2005,
"variable": "Injuries",
"value":             55 
},
{
 "X": 3405,
"State": "CA",
"Year": 2006,
"variable": "Injuries",
"value":            123 
},
{
 "X": 3406,
"State": "CA",
"Year": 2007,
"variable": "Injuries",
"value":            181 
},
{
 "X": 3407,
"State": "CA",
"Year": 2008,
"variable": "Injuries",
"value":             60 
},
{
 "X": 3408,
"State": "CA",
"Year": 2009,
"variable": "Injuries",
"value":             79 
},
{
 "X": 3409,
"State": "CA",
"Year": 2010,
"variable": "Injuries",
"value":             37 
},
{
 "X": 3410,
"State": "CA",
"Year": 2011,
"variable": "Injuries",
"value":             48 
},
{
 "X": 3411,
"State": "CO",
"Year": 1950,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3412,
"State": "CO",
"Year": 1951,
"variable": "Injuries",
"value":              2 
},
{
 "X": 3413,
"State": "CO",
"Year": 1952,
"variable": "Injuries",
"value":              6 
},
{
 "X": 3414,
"State": "CO",
"Year": 1953,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3415,
"State": "CO",
"Year": 1954,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3416,
"State": "CO",
"Year": 1955,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3417,
"State": "CO",
"Year": 1956,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3418,
"State": "CO",
"Year": 1957,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3419,
"State": "CO",
"Year": 1958,
"variable": "Injuries",
"value":              5 
},
{
 "X": 3420,
"State": "CO",
"Year": 1959,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3421,
"State": "CO",
"Year": 1960,
"variable": "Injuries",
"value":              3 
},
{
 "X": 3422,
"State": "CO",
"Year": 1961,
"variable": "Injuries",
"value":              2 
},
{
 "X": 3423,
"State": "CO",
"Year": 1962,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3424,
"State": "CO",
"Year": 1963,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3425,
"State": "CO",
"Year": 1964,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3426,
"State": "CO",
"Year": 1965,
"variable": "Injuries",
"value":              5 
},
{
 "X": 3427,
"State": "CO",
"Year": 1966,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3428,
"State": "CO",
"Year": 1967,
"variable": "Injuries",
"value":              8 
},
{
 "X": 3429,
"State": "CO",
"Year": 1968,
"variable": "Injuries",
"value":              2 
},
{
 "X": 3430,
"State": "CO",
"Year": 1969,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3431,
"State": "CO",
"Year": 1970,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3432,
"State": "CO",
"Year": 1971,
"variable": "Injuries",
"value":              9 
},
{
 "X": 3433,
"State": "CO",
"Year": 1972,
"variable": "Injuries",
"value":              3 
},
{
 "X": 3434,
"State": "CO",
"Year": 1973,
"variable": "Injuries",
"value":              5 
},
{
 "X": 3435,
"State": "CO",
"Year": 1974,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3436,
"State": "CO",
"Year": 1975,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3437,
"State": "CO",
"Year": 1976,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3438,
"State": "CO",
"Year": 1977,
"variable": "Injuries",
"value":              3 
},
{
 "X": 3439,
"State": "CO",
"Year": 1978,
"variable": "Injuries",
"value":              3 
},
{
 "X": 3440,
"State": "CO",
"Year": 1979,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3441,
"State": "CO",
"Year": 1980,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3442,
"State": "CO",
"Year": 1981,
"variable": "Injuries",
"value":             44 
},
{
 "X": 3443,
"State": "CO",
"Year": 1982,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3444,
"State": "CO",
"Year": 1983,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3445,
"State": "CO",
"Year": 1984,
"variable": "Injuries",
"value":             29 
},
{
 "X": 3446,
"State": "CO",
"Year": 1985,
"variable": "Injuries",
"value":              5 
},
{
 "X": 3447,
"State": "CO",
"Year": 1986,
"variable": "Injuries",
"value":             13 
},
{
 "X": 3448,
"State": "CO",
"Year": 1987,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3449,
"State": "CO",
"Year": 1988,
"variable": "Injuries",
"value":              8 
},
{
 "X": 3450,
"State": "CO",
"Year": 1989,
"variable": "Injuries",
"value":              3 
},
{
 "X": 3451,
"State": "CO",
"Year": 1990,
"variable": "Injuries",
"value":             76 
},
{
 "X": 3452,
"State": "CO",
"Year": 1991,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3453,
"State": "CO",
"Year": 1992,
"variable": "Injuries",
"value":              5 
},
{
 "X": 3454,
"State": "CO",
"Year": 1993,
"variable": "Injuries",
"value":              3 
},
{
 "X": 3455,
"State": "CO",
"Year": 1994,
"variable": "Injuries",
"value":             52 
},
{
 "X": 3456,
"State": "CO",
"Year": 1995,
"variable": "Injuries",
"value":             41 
},
{
 "X": 3457,
"State": "CO",
"Year": 1996,
"variable": "Injuries",
"value":             62 
},
{
 "X": 3458,
"State": "CO",
"Year": 1997,
"variable": "Injuries",
"value":             67 
},
{
 "X": 3459,
"State": "CO",
"Year": 1998,
"variable": "Injuries",
"value":             45 
},
{
 "X": 3460,
"State": "CO",
"Year": 1999,
"variable": "Injuries",
"value":             44 
},
{
 "X": 3461,
"State": "CO",
"Year": 2000,
"variable": "Injuries",
"value":             34 
},
{
 "X": 3462,
"State": "CO",
"Year": 2001,
"variable": "Injuries",
"value":             57 
},
{
 "X": 3463,
"State": "CO",
"Year": 2002,
"variable": "Injuries",
"value":             42 
},
{
 "X": 3464,
"State": "CO",
"Year": 2003,
"variable": "Injuries",
"value":             21 
},
{
 "X": 3465,
"State": "CO",
"Year": 2004,
"variable": "Injuries",
"value":             48 
},
{
 "X": 3466,
"State": "CO",
"Year": 2005,
"variable": "Injuries",
"value":             35 
},
{
 "X": 3467,
"State": "CO",
"Year": 2006,
"variable": "Injuries",
"value":             20 
},
{
 "X": 3468,
"State": "CO",
"Year": 2007,
"variable": "Injuries",
"value":             22 
},
{
 "X": 3469,
"State": "CO",
"Year": 2008,
"variable": "Injuries",
"value":             99 
},
{
 "X": 3470,
"State": "CO",
"Year": 2009,
"variable": "Injuries",
"value":             29 
},
{
 "X": 3471,
"State": "CO",
"Year": 2010,
"variable": "Injuries",
"value":             15 
},
{
 "X": 3472,
"State": "CO",
"Year": 2011,
"variable": "Injuries",
"value":             22 
},
{
 "X": 3473,
"State": "CT",
"Year": 1950,
"variable": "Injuries",
"value":              3 
},
{
 "X": 3474,
"State": "CT",
"Year": 1951,
"variable": "Injuries",
"value":             17 
},
{
 "X": 3475,
"State": "CT",
"Year": 1952,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3476,
"State": "CT",
"Year": 1953,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3477,
"State": "CT",
"Year": 1954,
"variable": "Injuries",
"value":              2 
},
{
 "X": 3478,
"State": "CT",
"Year": 1955,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3479,
"State": "CT",
"Year": 1956,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3480,
"State": "CT",
"Year": 1957,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3481,
"State": "CT",
"Year": 1958,
"variable": "Injuries",
"value":              2 
},
{
 "X": 3482,
"State": "CT",
"Year": 1959,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3483,
"State": "CT",
"Year": 1960,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3484,
"State": "CT",
"Year": 1961,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3485,
"State": "CT",
"Year": 1962,
"variable": "Injuries",
"value":             50 
},
{
 "X": 3486,
"State": "CT",
"Year": 1963,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3487,
"State": "CT",
"Year": 1964,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3488,
"State": "CT",
"Year": 1965,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3489,
"State": "CT",
"Year": 1966,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3490,
"State": "CT",
"Year": 1967,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3491,
"State": "CT",
"Year": 1968,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3492,
"State": "CT",
"Year": 1969,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3493,
"State": "CT",
"Year": 1970,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3494,
"State": "CT",
"Year": 1971,
"variable": "Injuries",
"value":              2 
},
{
 "X": 3495,
"State": "CT",
"Year": 1972,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3496,
"State": "CT",
"Year": 1973,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3497,
"State": "CT",
"Year": 1974,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3498,
"State": "CT",
"Year": 1975,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3499,
"State": "CT",
"Year": 1976,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3500,
"State": "CT",
"Year": 1977,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3501,
"State": "CT",
"Year": 1978,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3502,
"State": "CT",
"Year": 1979,
"variable": "Injuries",
"value":            500 
},
{
 "X": 3503,
"State": "CT",
"Year": 1980,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3504,
"State": "CT",
"Year": 1981,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3505,
"State": "CT",
"Year": 1982,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3506,
"State": "CT",
"Year": 1983,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3507,
"State": "CT",
"Year": 1984,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3508,
"State": "CT",
"Year": 1985,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3509,
"State": "CT",
"Year": 1986,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3510,
"State": "CT",
"Year": 1987,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3511,
"State": "CT",
"Year": 1988,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3512,
"State": "CT",
"Year": 1989,
"variable": "Injuries",
"value":            124 
},
{
 "X": 3513,
"State": "CT",
"Year": 1990,
"variable": "Injuries",
"value":              7 
},
{
 "X": 3514,
"State": "CT",
"Year": 1991,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3515,
"State": "CT",
"Year": 1992,
"variable": "Injuries",
"value":              3 
},
{
 "X": 3516,
"State": "CT",
"Year": 1993,
"variable": "Injuries",
"value":              4 
},
{
 "X": 3517,
"State": "CT",
"Year": 1994,
"variable": "Injuries",
"value":              4 
},
{
 "X": 3518,
"State": "CT",
"Year": 1995,
"variable": "Injuries",
"value":              3 
},
{
 "X": 3519,
"State": "CT",
"Year": 1996,
"variable": "Injuries",
"value":              7 
},
{
 "X": 3520,
"State": "CT",
"Year": 1997,
"variable": "Injuries",
"value":              6 
},
{
 "X": 3521,
"State": "CT",
"Year": 1998,
"variable": "Injuries",
"value":              5 
},
{
 "X": 3522,
"State": "CT",
"Year": 1999,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3523,
"State": "CT",
"Year": 2000,
"variable": "Injuries",
"value":             27 
},
{
 "X": 3524,
"State": "CT",
"Year": 2001,
"variable": "Injuries",
"value":              5 
},
{
 "X": 3525,
"State": "CT",
"Year": 2002,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3526,
"State": "CT",
"Year": 2003,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3527,
"State": "CT",
"Year": 2004,
"variable": "Injuries",
"value":              2 
},
{
 "X": 3528,
"State": "CT",
"Year": 2005,
"variable": "Injuries",
"value":              6 
},
{
 "X": 3529,
"State": "CT",
"Year": 2006,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3530,
"State": "CT",
"Year": 2007,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3531,
"State": "CT",
"Year": 2008,
"variable": "Injuries",
"value":              7 
},
{
 "X": 3532,
"State": "CT",
"Year": 2009,
"variable": "Injuries",
"value":             58 
},
{
 "X": 3533,
"State": "CT",
"Year": 2010,
"variable": "Injuries",
"value":             37 
},
{
 "X": 3534,
"State": "CT",
"Year": 2011,
"variable": "Injuries",
"value":              7 
},
{
 "X": 3535,
"State": "DE",
"Year": 1950,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3536,
"State": "DE",
"Year": 1951,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3537,
"State": "DE",
"Year": 1952,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3538,
"State": "DE",
"Year": 1953,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3539,
"State": "DE",
"Year": 1954,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3540,
"State": "DE",
"Year": 1955,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3541,
"State": "DE",
"Year": 1956,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3542,
"State": "DE",
"Year": 1957,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3543,
"State": "DE",
"Year": 1958,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3544,
"State": "DE",
"Year": 1959,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3545,
"State": "DE",
"Year": 1960,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3546,
"State": "DE",
"Year": 1961,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3547,
"State": "DE",
"Year": 1962,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3548,
"State": "DE",
"Year": 1963,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3549,
"State": "DE",
"Year": 1964,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3550,
"State": "DE",
"Year": 1965,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3551,
"State": "DE",
"Year": 1966,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3552,
"State": "DE",
"Year": 1967,
"variable": "Injuries",
"value":              7 
},
{
 "X": 3553,
"State": "DE",
"Year": 1968,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3554,
"State": "DE",
"Year": 1969,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3555,
"State": "DE",
"Year": 1970,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3556,
"State": "DE",
"Year": 1971,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3557,
"State": "DE",
"Year": 1972,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3558,
"State": "DE",
"Year": 1973,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3559,
"State": "DE",
"Year": 1974,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3560,
"State": "DE",
"Year": 1975,
"variable": "Injuries",
"value":              3 
},
{
 "X": 3561,
"State": "DE",
"Year": 1976,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3562,
"State": "DE",
"Year": 1977,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3563,
"State": "DE",
"Year": 1978,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3564,
"State": "DE",
"Year": 1979,
"variable": "Injuries",
"value":              5 
},
{
 "X": 3565,
"State": "DE",
"Year": 1980,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3566,
"State": "DE",
"Year": 1981,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3567,
"State": "DE",
"Year": 1982,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3568,
"State": "DE",
"Year": 1983,
"variable": "Injuries",
"value":              9 
},
{
 "X": 3569,
"State": "DE",
"Year": 1984,
"variable": "Injuries",
"value":             10 
},
{
 "X": 3570,
"State": "DE",
"Year": 1985,
"variable": "Injuries",
"value":              2 
},
{
 "X": 3571,
"State": "DE",
"Year": 1986,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3572,
"State": "DE",
"Year": 1987,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3573,
"State": "DE",
"Year": 1988,
"variable": "Injuries",
"value":             32 
},
{
 "X": 3574,
"State": "DE",
"Year": 1989,
"variable": "Injuries",
"value":              3 
},
{
 "X": 3575,
"State": "DE",
"Year": 1990,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3576,
"State": "DE",
"Year": 1991,
"variable": "Injuries",
"value":              2 
},
{
 "X": 3577,
"State": "DE",
"Year": 1992,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3578,
"State": "DE",
"Year": 1993,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3579,
"State": "DE",
"Year": 1994,
"variable": "Injuries",
"value":              4 
},
{
 "X": 3580,
"State": "DE",
"Year": 1995,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3581,
"State": "DE",
"Year": 1996,
"variable": "Injuries",
"value":              8 
},
{
 "X": 3582,
"State": "DE",
"Year": 1997,
"variable": "Injuries",
"value":              3 
},
{
 "X": 3583,
"State": "DE",
"Year": 1998,
"variable": "Injuries",
"value":             14 
},
{
 "X": 3584,
"State": "DE",
"Year": 1999,
"variable": "Injuries",
"value":             33 
},
{
 "X": 3585,
"State": "DE",
"Year": 2000,
"variable": "Injuries",
"value":             55 
},
{
 "X": 3586,
"State": "DE",
"Year": 2001,
"variable": "Injuries",
"value":             35 
},
{
 "X": 3587,
"State": "DE",
"Year": 2002,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3588,
"State": "DE",
"Year": 2003,
"variable": "Injuries",
"value":              2 
},
{
 "X": 3589,
"State": "DE",
"Year": 2004,
"variable": "Injuries",
"value":              5 
},
{
 "X": 3590,
"State": "DE",
"Year": 2005,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3591,
"State": "DE",
"Year": 2006,
"variable": "Injuries",
"value":             12 
},
{
 "X": 3592,
"State": "DE",
"Year": 2007,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3593,
"State": "DE",
"Year": 2008,
"variable": "Injuries",
"value":             56 
},
{
 "X": 3594,
"State": "DE",
"Year": 2009,
"variable": "Injuries",
"value":             28 
},
{
 "X": 3595,
"State": "DE",
"Year": 2010,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3596,
"State": "DE",
"Year": 2011,
"variable": "Injuries",
"value":              2 
},
{
 "X": 3597,
"State": "FL",
"Year": 1950,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3598,
"State": "FL",
"Year": 1951,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3599,
"State": "FL",
"Year": 1952,
"variable": "Injuries",
"value":              9 
},
{
 "X": 3600,
"State": "FL",
"Year": 1953,
"variable": "Injuries",
"value":             36 
},
{
 "X": 3601,
"State": "FL",
"Year": 1954,
"variable": "Injuries",
"value":              6 
},
{
 "X": 3602,
"State": "FL",
"Year": 1955,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3603,
"State": "FL",
"Year": 1956,
"variable": "Injuries",
"value":             21 
},
{
 "X": 3604,
"State": "FL",
"Year": 1957,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3605,
"State": "FL",
"Year": 1958,
"variable": "Injuries",
"value":             69 
},
{
 "X": 3606,
"State": "FL",
"Year": 1959,
"variable": "Injuries",
"value":            105 
},
{
 "X": 3607,
"State": "FL",
"Year": 1960,
"variable": "Injuries",
"value":              9 
},
{
 "X": 3608,
"State": "FL",
"Year": 1961,
"variable": "Injuries",
"value":             10 
},
{
 "X": 3609,
"State": "FL",
"Year": 1962,
"variable": "Injuries",
"value":            136 
},
{
 "X": 3610,
"State": "FL",
"Year": 1963,
"variable": "Injuries",
"value":              4 
},
{
 "X": 3611,
"State": "FL",
"Year": 1964,
"variable": "Injuries",
"value":             65 
},
{
 "X": 3612,
"State": "FL",
"Year": 1965,
"variable": "Injuries",
"value":              8 
},
{
 "X": 3613,
"State": "FL",
"Year": 1966,
"variable": "Injuries",
"value":            535 
},
{
 "X": 3614,
"State": "FL",
"Year": 1967,
"variable": "Injuries",
"value":            148 
},
{
 "X": 3615,
"State": "FL",
"Year": 1968,
"variable": "Injuries",
"value":             56 
},
{
 "X": 3616,
"State": "FL",
"Year": 1969,
"variable": "Injuries",
"value":             10 
},
{
 "X": 3617,
"State": "FL",
"Year": 1970,
"variable": "Injuries",
"value":             14 
},
{
 "X": 3618,
"State": "FL",
"Year": 1971,
"variable": "Injuries",
"value":            125 
},
{
 "X": 3619,
"State": "FL",
"Year": 1972,
"variable": "Injuries",
"value":            115 
},
{
 "X": 3620,
"State": "FL",
"Year": 1973,
"variable": "Injuries",
"value":             94 
},
{
 "X": 3621,
"State": "FL",
"Year": 1974,
"variable": "Injuries",
"value":             71 
},
{
 "X": 3622,
"State": "FL",
"Year": 1975,
"variable": "Injuries",
"value":             79 
},
{
 "X": 3623,
"State": "FL",
"Year": 1976,
"variable": "Injuries",
"value":             32 
},
{
 "X": 3624,
"State": "FL",
"Year": 1977,
"variable": "Injuries",
"value":             18 
},
{
 "X": 3625,
"State": "FL",
"Year": 1978,
"variable": "Injuries",
"value":            155 
},
{
 "X": 3626,
"State": "FL",
"Year": 1979,
"variable": "Injuries",
"value":             69 
},
{
 "X": 3627,
"State": "FL",
"Year": 1980,
"variable": "Injuries",
"value":             59 
},
{
 "X": 3628,
"State": "FL",
"Year": 1981,
"variable": "Injuries",
"value":             33 
},
{
 "X": 3629,
"State": "FL",
"Year": 1982,
"variable": "Injuries",
"value":             39 
},
{
 "X": 3630,
"State": "FL",
"Year": 1983,
"variable": "Injuries",
"value":             60 
},
{
 "X": 3631,
"State": "FL",
"Year": 1984,
"variable": "Injuries",
"value":              4 
},
{
 "X": 3632,
"State": "FL",
"Year": 1985,
"variable": "Injuries",
"value":             58 
},
{
 "X": 3633,
"State": "FL",
"Year": 1986,
"variable": "Injuries",
"value":             39 
},
{
 "X": 3634,
"State": "FL",
"Year": 1987,
"variable": "Injuries",
"value":             24 
},
{
 "X": 3635,
"State": "FL",
"Year": 1988,
"variable": "Injuries",
"value":             40 
},
{
 "X": 3636,
"State": "FL",
"Year": 1989,
"variable": "Injuries",
"value":             18 
},
{
 "X": 3637,
"State": "FL",
"Year": 1990,
"variable": "Injuries",
"value":             20 
},
{
 "X": 3638,
"State": "FL",
"Year": 1991,
"variable": "Injuries",
"value":             34 
},
{
 "X": 3639,
"State": "FL",
"Year": 1992,
"variable": "Injuries",
"value":            111 
},
{
 "X": 3640,
"State": "FL",
"Year": 1993,
"variable": "Injuries",
"value":            139 
},
{
 "X": 3641,
"State": "FL",
"Year": 1994,
"variable": "Injuries",
"value":            207 
},
{
 "X": 3642,
"State": "FL",
"Year": 1995,
"variable": "Injuries",
"value":            149 
},
{
 "X": 3643,
"State": "FL",
"Year": 1996,
"variable": "Injuries",
"value":            234 
},
{
 "X": 3644,
"State": "FL",
"Year": 1997,
"variable": "Injuries",
"value":            189 
},
{
 "X": 3645,
"State": "FL",
"Year": 1998,
"variable": "Injuries",
"value":            526 
},
{
 "X": 3646,
"State": "FL",
"Year": 1999,
"variable": "Injuries",
"value":             90 
},
{
 "X": 3647,
"State": "FL",
"Year": 2000,
"variable": "Injuries",
"value":             55 
},
{
 "X": 3648,
"State": "FL",
"Year": 2001,
"variable": "Injuries",
"value":            123 
},
{
 "X": 3649,
"State": "FL",
"Year": 2002,
"variable": "Injuries",
"value":             59 
},
{
 "X": 3650,
"State": "FL",
"Year": 2003,
"variable": "Injuries",
"value":            125 
},
{
 "X": 3651,
"State": "FL",
"Year": 2004,
"variable": "Injuries",
"value":            889 
},
{
 "X": 3652,
"State": "FL",
"Year": 2005,
"variable": "Injuries",
"value":             57 
},
{
 "X": 3653,
"State": "FL",
"Year": 2006,
"variable": "Injuries",
"value":             92 
},
{
 "X": 3654,
"State": "FL",
"Year": 2007,
"variable": "Injuries",
"value":            173 
},
{
 "X": 3655,
"State": "FL",
"Year": 2008,
"variable": "Injuries",
"value":             48 
},
{
 "X": 3656,
"State": "FL",
"Year": 2009,
"variable": "Injuries",
"value":             84 
},
{
 "X": 3657,
"State": "FL",
"Year": 2010,
"variable": "Injuries",
"value":             74 
},
{
 "X": 3658,
"State": "FL",
"Year": 2011,
"variable": "Injuries",
"value":             66 
},
{
 "X": 3659,
"State": "GA",
"Year": 1950,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3660,
"State": "GA",
"Year": 1951,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3661,
"State": "GA",
"Year": 1952,
"variable": "Injuries",
"value":             34 
},
{
 "X": 3662,
"State": "GA",
"Year": 1953,
"variable": "Injuries",
"value":            618 
},
{
 "X": 3663,
"State": "GA",
"Year": 1954,
"variable": "Injuries",
"value":            217 
},
{
 "X": 3664,
"State": "GA",
"Year": 1955,
"variable": "Injuries",
"value":              5 
},
{
 "X": 3665,
"State": "GA",
"Year": 1956,
"variable": "Injuries",
"value":              2 
},
{
 "X": 3666,
"State": "GA",
"Year": 1957,
"variable": "Injuries",
"value":             22 
},
{
 "X": 3667,
"State": "GA",
"Year": 1958,
"variable": "Injuries",
"value":             19 
},
{
 "X": 3668,
"State": "GA",
"Year": 1959,
"variable": "Injuries",
"value":              9 
},
{
 "X": 3669,
"State": "GA",
"Year": 1960,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3670,
"State": "GA",
"Year": 1961,
"variable": "Injuries",
"value":             19 
},
{
 "X": 3671,
"State": "GA",
"Year": 1962,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3672,
"State": "GA",
"Year": 1963,
"variable": "Injuries",
"value":             17 
},
{
 "X": 3673,
"State": "GA",
"Year": 1964,
"variable": "Injuries",
"value":             22 
},
{
 "X": 3674,
"State": "GA",
"Year": 1965,
"variable": "Injuries",
"value":              3 
},
{
 "X": 3675,
"State": "GA",
"Year": 1966,
"variable": "Injuries",
"value":             18 
},
{
 "X": 3676,
"State": "GA",
"Year": 1967,
"variable": "Injuries",
"value":              7 
},
{
 "X": 3677,
"State": "GA",
"Year": 1968,
"variable": "Injuries",
"value":             12 
},
{
 "X": 3678,
"State": "GA",
"Year": 1969,
"variable": "Injuries",
"value":             39 
},
{
 "X": 3679,
"State": "GA",
"Year": 1970,
"variable": "Injuries",
"value":             18 
},
{
 "X": 3680,
"State": "GA",
"Year": 1971,
"variable": "Injuries",
"value":             49 
},
{
 "X": 3681,
"State": "GA",
"Year": 1972,
"variable": "Injuries",
"value":             50 
},
{
 "X": 3682,
"State": "GA",
"Year": 1973,
"variable": "Injuries",
"value":            197 
},
{
 "X": 3683,
"State": "GA",
"Year": 1974,
"variable": "Injuries",
"value":            180 
},
{
 "X": 3684,
"State": "GA",
"Year": 1975,
"variable": "Injuries",
"value":            248 
},
{
 "X": 3685,
"State": "GA",
"Year": 1976,
"variable": "Injuries",
"value":              3 
},
{
 "X": 3686,
"State": "GA",
"Year": 1977,
"variable": "Injuries",
"value":             22 
},
{
 "X": 3687,
"State": "GA",
"Year": 1978,
"variable": "Injuries",
"value":              6 
},
{
 "X": 3688,
"State": "GA",
"Year": 1979,
"variable": "Injuries",
"value":             12 
},
{
 "X": 3689,
"State": "GA",
"Year": 1980,
"variable": "Injuries",
"value":             12 
},
{
 "X": 3690,
"State": "GA",
"Year": 1981,
"variable": "Injuries",
"value":              6 
},
{
 "X": 3691,
"State": "GA",
"Year": 1982,
"variable": "Injuries",
"value":             11 
},
{
 "X": 3692,
"State": "GA",
"Year": 1983,
"variable": "Injuries",
"value":             24 
},
{
 "X": 3693,
"State": "GA",
"Year": 1984,
"variable": "Injuries",
"value":             65 
},
{
 "X": 3694,
"State": "GA",
"Year": 1985,
"variable": "Injuries",
"value":             23 
},
{
 "X": 3695,
"State": "GA",
"Year": 1986,
"variable": "Injuries",
"value":             51 
},
{
 "X": 3696,
"State": "GA",
"Year": 1987,
"variable": "Injuries",
"value":              2 
},
{
 "X": 3697,
"State": "GA",
"Year": 1988,
"variable": "Injuries",
"value":             15 
},
{
 "X": 3698,
"State": "GA",
"Year": 1989,
"variable": "Injuries",
"value":            118 
},
{
 "X": 3699,
"State": "GA",
"Year": 1990,
"variable": "Injuries",
"value":             58 
},
{
 "X": 3700,
"State": "GA",
"Year": 1991,
"variable": "Injuries",
"value":             75 
},
{
 "X": 3701,
"State": "GA",
"Year": 1992,
"variable": "Injuries",
"value":            160 
},
{
 "X": 3702,
"State": "GA",
"Year": 1993,
"variable": "Injuries",
"value":            517 
},
{
 "X": 3703,
"State": "GA",
"Year": 1994,
"variable": "Injuries",
"value":             68 
},
{
 "X": 3704,
"State": "GA",
"Year": 1995,
"variable": "Injuries",
"value":            341 
},
{
 "X": 3705,
"State": "GA",
"Year": 1996,
"variable": "Injuries",
"value":             35 
},
{
 "X": 3706,
"State": "GA",
"Year": 1997,
"variable": "Injuries",
"value":             35 
},
{
 "X": 3707,
"State": "GA",
"Year": 1998,
"variable": "Injuries",
"value":            318 
},
{
 "X": 3708,
"State": "GA",
"Year": 1999,
"variable": "Injuries",
"value":             52 
},
{
 "X": 3709,
"State": "GA",
"Year": 2000,
"variable": "Injuries",
"value":            312 
},
{
 "X": 3710,
"State": "GA",
"Year": 2001,
"variable": "Injuries",
"value":             50 
},
{
 "X": 3711,
"State": "GA",
"Year": 2002,
"variable": "Injuries",
"value":             38 
},
{
 "X": 3712,
"State": "GA",
"Year": 2003,
"variable": "Injuries",
"value":            249 
},
{
 "X": 3713,
"State": "GA",
"Year": 2004,
"variable": "Injuries",
"value":             56 
},
{
 "X": 3714,
"State": "GA",
"Year": 2005,
"variable": "Injuries",
"value":             78 
},
{
 "X": 3715,
"State": "GA",
"Year": 2006,
"variable": "Injuries",
"value":             22 
},
{
 "X": 3716,
"State": "GA",
"Year": 2007,
"variable": "Injuries",
"value":             63 
},
{
 "X": 3717,
"State": "GA",
"Year": 2008,
"variable": "Injuries",
"value":            109 
},
{
 "X": 3718,
"State": "GA",
"Year": 2009,
"variable": "Injuries",
"value":             38 
},
{
 "X": 3719,
"State": "GA",
"Year": 2010,
"variable": "Injuries",
"value":             24 
},
{
 "X": 3720,
"State": "GA",
"Year": 2011,
"variable": "Injuries",
"value":            187 
},
{
 "X": 3721,
"State": "HI",
"Year": 1950,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3722,
"State": "HI",
"Year": 1951,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3723,
"State": "HI",
"Year": 1952,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3724,
"State": "HI",
"Year": 1953,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3725,
"State": "HI",
"Year": 1954,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3726,
"State": "HI",
"Year": 1955,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3727,
"State": "HI",
"Year": 1956,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3728,
"State": "HI",
"Year": 1957,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3729,
"State": "HI",
"Year": 1958,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3730,
"State": "HI",
"Year": 1959,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3731,
"State": "HI",
"Year": 1960,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3732,
"State": "HI",
"Year": 1961,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3733,
"State": "HI",
"Year": 1962,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3734,
"State": "HI",
"Year": 1963,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3735,
"State": "HI",
"Year": 1964,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3736,
"State": "HI",
"Year": 1965,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3737,
"State": "HI",
"Year": 1966,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3738,
"State": "HI",
"Year": 1967,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3739,
"State": "HI",
"Year": 1968,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3740,
"State": "HI",
"Year": 1969,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3741,
"State": "HI",
"Year": 1970,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3742,
"State": "HI",
"Year": 1971,
"variable": "Injuries",
"value":              4 
},
{
 "X": 3743,
"State": "HI",
"Year": 1972,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3744,
"State": "HI",
"Year": 1973,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3745,
"State": "HI",
"Year": 1974,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3746,
"State": "HI",
"Year": 1975,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3747,
"State": "HI",
"Year": 1976,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3748,
"State": "HI",
"Year": 1977,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3749,
"State": "HI",
"Year": 1978,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3750,
"State": "HI",
"Year": 1979,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3751,
"State": "HI",
"Year": 1980,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3752,
"State": "HI",
"Year": 1981,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3753,
"State": "HI",
"Year": 1982,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3754,
"State": "HI",
"Year": 1983,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3755,
"State": "HI",
"Year": 1984,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3756,
"State": "HI",
"Year": 1985,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3757,
"State": "HI",
"Year": 1986,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3758,
"State": "HI",
"Year": 1987,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3759,
"State": "HI",
"Year": 1988,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3760,
"State": "HI",
"Year": 1989,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3761,
"State": "HI",
"Year": 1990,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3762,
"State": "HI",
"Year": 1991,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3763,
"State": "HI",
"Year": 1992,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3764,
"State": "HI",
"Year": 1993,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3765,
"State": "HI",
"Year": 1994,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3766,
"State": "HI",
"Year": 1995,
"variable": "Injuries",
"value":              7 
},
{
 "X": 3767,
"State": "HI",
"Year": 1996,
"variable": "Injuries",
"value":             10 
},
{
 "X": 3768,
"State": "HI",
"Year": 1997,
"variable": "Injuries",
"value":              4 
},
{
 "X": 3769,
"State": "HI",
"Year": 1998,
"variable": "Injuries",
"value":              7 
},
{
 "X": 3770,
"State": "HI",
"Year": 1999,
"variable": "Injuries",
"value":              7 
},
{
 "X": 3771,
"State": "HI",
"Year": 2000,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3772,
"State": "HI",
"Year": 2001,
"variable": "Injuries",
"value":              6 
},
{
 "X": 3773,
"State": "HI",
"Year": 2002,
"variable": "Injuries",
"value":              3 
},
{
 "X": 3774,
"State": "HI",
"Year": 2003,
"variable": "Injuries",
"value":              9 
},
{
 "X": 3775,
"State": "HI",
"Year": 2004,
"variable": "Injuries",
"value":              5 
},
{
 "X": 3776,
"State": "HI",
"Year": 2005,
"variable": "Injuries",
"value":              7 
},
{
 "X": 3777,
"State": "HI",
"Year": 2006,
"variable": "Injuries",
"value":              2 
},
{
 "X": 3778,
"State": "HI",
"Year": 2007,
"variable": "Injuries",
"value":              5 
},
{
 "X": 3779,
"State": "HI",
"Year": 2008,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3780,
"State": "HI",
"Year": 2009,
"variable": "Injuries",
"value":              2 
},
{
 "X": 3781,
"State": "HI",
"Year": 2010,
"variable": "Injuries",
"value":              5 
},
{
 "X": 3782,
"State": "HI",
"Year": 2011,
"variable": "Injuries",
"value":              7 
},
{
 "X": 3783,
"State": "IA",
"Year": 1950,
"variable": "Injuries",
"value":              5 
},
{
 "X": 3784,
"State": "IA",
"Year": 1951,
"variable": "Injuries",
"value":             17 
},
{
 "X": 3785,
"State": "IA",
"Year": 1952,
"variable": "Injuries",
"value":              5 
},
{
 "X": 3786,
"State": "IA",
"Year": 1953,
"variable": "Injuries",
"value":             19 
},
{
 "X": 3787,
"State": "IA",
"Year": 1954,
"variable": "Injuries",
"value":              4 
},
{
 "X": 3788,
"State": "IA",
"Year": 1955,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3789,
"State": "IA",
"Year": 1956,
"variable": "Injuries",
"value":              9 
},
{
 "X": 3790,
"State": "IA",
"Year": 1957,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3791,
"State": "IA",
"Year": 1958,
"variable": "Injuries",
"value":              2 
},
{
 "X": 3792,
"State": "IA",
"Year": 1959,
"variable": "Injuries",
"value":              7 
},
{
 "X": 3793,
"State": "IA",
"Year": 1960,
"variable": "Injuries",
"value":              5 
},
{
 "X": 3794,
"State": "IA",
"Year": 1961,
"variable": "Injuries",
"value":             24 
},
{
 "X": 3795,
"State": "IA",
"Year": 1962,
"variable": "Injuries",
"value":              5 
},
{
 "X": 3796,
"State": "IA",
"Year": 1963,
"variable": "Injuries",
"value":              2 
},
{
 "X": 3797,
"State": "IA",
"Year": 1964,
"variable": "Injuries",
"value":             73 
},
{
 "X": 3798,
"State": "IA",
"Year": 1965,
"variable": "Injuries",
"value":             55 
},
{
 "X": 3799,
"State": "IA",
"Year": 1966,
"variable": "Injuries",
"value":            176 
},
{
 "X": 3800,
"State": "IA",
"Year": 1967,
"variable": "Injuries",
"value":             36 
},
{
 "X": 3801,
"State": "IA",
"Year": 1968,
"variable": "Injuries",
"value":            636 
},
{
 "X": 3802,
"State": "IA",
"Year": 1969,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3803,
"State": "IA",
"Year": 1970,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3804,
"State": "IA",
"Year": 1971,
"variable": "Injuries",
"value":             27 
},
{
 "X": 3805,
"State": "IA",
"Year": 1972,
"variable": "Injuries",
"value":              3 
},
{
 "X": 3806,
"State": "IA",
"Year": 1973,
"variable": "Injuries",
"value":             21 
},
{
 "X": 3807,
"State": "IA",
"Year": 1974,
"variable": "Injuries",
"value":            106 
},
{
 "X": 3808,
"State": "IA",
"Year": 1975,
"variable": "Injuries",
"value":              7 
},
{
 "X": 3809,
"State": "IA",
"Year": 1976,
"variable": "Injuries",
"value":             17 
},
{
 "X": 3810,
"State": "IA",
"Year": 1977,
"variable": "Injuries",
"value":             23 
},
{
 "X": 3811,
"State": "IA",
"Year": 1978,
"variable": "Injuries",
"value":             47 
},
{
 "X": 3812,
"State": "IA",
"Year": 1979,
"variable": "Injuries",
"value":            114 
},
{
 "X": 3813,
"State": "IA",
"Year": 1980,
"variable": "Injuries",
"value":              8 
},
{
 "X": 3814,
"State": "IA",
"Year": 1981,
"variable": "Injuries",
"value":             12 
},
{
 "X": 3815,
"State": "IA",
"Year": 1982,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3816,
"State": "IA",
"Year": 1983,
"variable": "Injuries",
"value":             35 
},
{
 "X": 3817,
"State": "IA",
"Year": 1984,
"variable": "Injuries",
"value":            109 
},
{
 "X": 3818,
"State": "IA",
"Year": 1985,
"variable": "Injuries",
"value":             31 
},
{
 "X": 3819,
"State": "IA",
"Year": 1986,
"variable": "Injuries",
"value":             33 
},
{
 "X": 3820,
"State": "IA",
"Year": 1987,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3821,
"State": "IA",
"Year": 1988,
"variable": "Injuries",
"value":             93 
},
{
 "X": 3822,
"State": "IA",
"Year": 1989,
"variable": "Injuries",
"value":             15 
},
{
 "X": 3823,
"State": "IA",
"Year": 1990,
"variable": "Injuries",
"value":             22 
},
{
 "X": 3824,
"State": "IA",
"Year": 1991,
"variable": "Injuries",
"value":             26 
},
{
 "X": 3825,
"State": "IA",
"Year": 1992,
"variable": "Injuries",
"value":              6 
},
{
 "X": 3826,
"State": "IA",
"Year": 1993,
"variable": "Injuries",
"value":             28 
},
{
 "X": 3827,
"State": "IA",
"Year": 1994,
"variable": "Injuries",
"value":             26 
},
{
 "X": 3828,
"State": "IA",
"Year": 1995,
"variable": "Injuries",
"value":             17 
},
{
 "X": 3829,
"State": "IA",
"Year": 1996,
"variable": "Injuries",
"value":             29 
},
{
 "X": 3830,
"State": "IA",
"Year": 1997,
"variable": "Injuries",
"value":             33 
},
{
 "X": 3831,
"State": "IA",
"Year": 1998,
"variable": "Injuries",
"value":            216 
},
{
 "X": 3832,
"State": "IA",
"Year": 1999,
"variable": "Injuries",
"value":             54 
},
{
 "X": 3833,
"State": "IA",
"Year": 2000,
"variable": "Injuries",
"value":             35 
},
{
 "X": 3834,
"State": "IA",
"Year": 2001,
"variable": "Injuries",
"value":             42 
},
{
 "X": 3835,
"State": "IA",
"Year": 2002,
"variable": "Injuries",
"value":              4 
},
{
 "X": 3836,
"State": "IA",
"Year": 2003,
"variable": "Injuries",
"value":             93 
},
{
 "X": 3837,
"State": "IA",
"Year": 2004,
"variable": "Injuries",
"value":             30 
},
{
 "X": 3838,
"State": "IA",
"Year": 2005,
"variable": "Injuries",
"value":             20 
},
{
 "X": 3839,
"State": "IA",
"Year": 2006,
"variable": "Injuries",
"value":             44 
},
{
 "X": 3840,
"State": "IA",
"Year": 2007,
"variable": "Injuries",
"value":             15 
},
{
 "X": 3841,
"State": "IA",
"Year": 2008,
"variable": "Injuries",
"value":            146 
},
{
 "X": 3842,
"State": "IA",
"Year": 2009,
"variable": "Injuries",
"value":             30 
},
{
 "X": 3843,
"State": "IA",
"Year": 2010,
"variable": "Injuries",
"value":            158 
},
{
 "X": 3844,
"State": "IA",
"Year": 2011,
"variable": "Injuries",
"value":             35 
},
{
 "X": 3845,
"State": "ID",
"Year": 1950,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3846,
"State": "ID",
"Year": 1951,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3847,
"State": "ID",
"Year": 1952,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3848,
"State": "ID",
"Year": 1953,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3849,
"State": "ID",
"Year": 1954,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3850,
"State": "ID",
"Year": 1955,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3851,
"State": "ID",
"Year": 1956,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3852,
"State": "ID",
"Year": 1957,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3853,
"State": "ID",
"Year": 1958,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3854,
"State": "ID",
"Year": 1959,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3855,
"State": "ID",
"Year": 1960,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3856,
"State": "ID",
"Year": 1961,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3857,
"State": "ID",
"Year": 1962,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3858,
"State": "ID",
"Year": 1963,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3859,
"State": "ID",
"Year": 1964,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3860,
"State": "ID",
"Year": 1965,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3861,
"State": "ID",
"Year": 1966,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3862,
"State": "ID",
"Year": 1967,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3863,
"State": "ID",
"Year": 1968,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3864,
"State": "ID",
"Year": 1969,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3865,
"State": "ID",
"Year": 1970,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3866,
"State": "ID",
"Year": 1971,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3867,
"State": "ID",
"Year": 1972,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3868,
"State": "ID",
"Year": 1973,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3869,
"State": "ID",
"Year": 1974,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3870,
"State": "ID",
"Year": 1975,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3871,
"State": "ID",
"Year": 1976,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3872,
"State": "ID",
"Year": 1977,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3873,
"State": "ID",
"Year": 1978,
"variable": "Injuries",
"value":              2 
},
{
 "X": 3874,
"State": "ID",
"Year": 1979,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3875,
"State": "ID",
"Year": 1980,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3876,
"State": "ID",
"Year": 1981,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3877,
"State": "ID",
"Year": 1982,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3878,
"State": "ID",
"Year": 1983,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3879,
"State": "ID",
"Year": 1984,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3880,
"State": "ID",
"Year": 1985,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3881,
"State": "ID",
"Year": 1986,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3882,
"State": "ID",
"Year": 1987,
"variable": "Injuries",
"value":              9 
},
{
 "X": 3883,
"State": "ID",
"Year": 1988,
"variable": "Injuries",
"value":             38 
},
{
 "X": 3884,
"State": "ID",
"Year": 1989,
"variable": "Injuries",
"value":              8 
},
{
 "X": 3885,
"State": "ID",
"Year": 1990,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3886,
"State": "ID",
"Year": 1991,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3887,
"State": "ID",
"Year": 1992,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3888,
"State": "ID",
"Year": 1993,
"variable": "Injuries",
"value":             14 
},
{
 "X": 3889,
"State": "ID",
"Year": 1994,
"variable": "Injuries",
"value":              4 
},
{
 "X": 3890,
"State": "ID",
"Year": 1995,
"variable": "Injuries",
"value":             24 
},
{
 "X": 3891,
"State": "ID",
"Year": 1996,
"variable": "Injuries",
"value":              3 
},
{
 "X": 3892,
"State": "ID",
"Year": 1997,
"variable": "Injuries",
"value":              9 
},
{
 "X": 3893,
"State": "ID",
"Year": 1998,
"variable": "Injuries",
"value":              9 
},
{
 "X": 3894,
"State": "ID",
"Year": 1999,
"variable": "Injuries",
"value":             14 
},
{
 "X": 3895,
"State": "ID",
"Year": 2000,
"variable": "Injuries",
"value":              6 
},
{
 "X": 3896,
"State": "ID",
"Year": 2001,
"variable": "Injuries",
"value":              7 
},
{
 "X": 3897,
"State": "ID",
"Year": 2002,
"variable": "Injuries",
"value":             27 
},
{
 "X": 3898,
"State": "ID",
"Year": 2003,
"variable": "Injuries",
"value":              4 
},
{
 "X": 3899,
"State": "ID",
"Year": 2004,
"variable": "Injuries",
"value":              6 
},
{
 "X": 3900,
"State": "ID",
"Year": 2005,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3901,
"State": "ID",
"Year": 2006,
"variable": "Injuries",
"value":              4 
},
{
 "X": 3902,
"State": "ID",
"Year": 2007,
"variable": "Injuries",
"value":              6 
},
{
 "X": 3903,
"State": "ID",
"Year": 2008,
"variable": "Injuries",
"value":              5 
},
{
 "X": 3904,
"State": "ID",
"Year": 2009,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3905,
"State": "ID",
"Year": 2010,
"variable": "Injuries",
"value":             72 
},
{
 "X": 3906,
"State": "ID",
"Year": 2011,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3907,
"State": "IL",
"Year": 1950,
"variable": "Injuries",
"value":             31 
},
{
 "X": 3908,
"State": "IL",
"Year": 1951,
"variable": "Injuries",
"value":             58 
},
{
 "X": 3909,
"State": "IL",
"Year": 1952,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3910,
"State": "IL",
"Year": 1953,
"variable": "Injuries",
"value":             13 
},
{
 "X": 3911,
"State": "IL",
"Year": 1954,
"variable": "Injuries",
"value":             19 
},
{
 "X": 3912,
"State": "IL",
"Year": 1955,
"variable": "Injuries",
"value":             10 
},
{
 "X": 3913,
"State": "IL",
"Year": 1956,
"variable": "Injuries",
"value":             34 
},
{
 "X": 3914,
"State": "IL",
"Year": 1957,
"variable": "Injuries",
"value":            330 
},
{
 "X": 3915,
"State": "IL",
"Year": 1958,
"variable": "Injuries",
"value":             25 
},
{
 "X": 3916,
"State": "IL",
"Year": 1959,
"variable": "Injuries",
"value":             19 
},
{
 "X": 3917,
"State": "IL",
"Year": 1960,
"variable": "Injuries",
"value":             26 
},
{
 "X": 3918,
"State": "IL",
"Year": 1961,
"variable": "Injuries",
"value":            144 
},
{
 "X": 3919,
"State": "IL",
"Year": 1962,
"variable": "Injuries",
"value":             10 
},
{
 "X": 3920,
"State": "IL",
"Year": 1963,
"variable": "Injuries",
"value":            110 
},
{
 "X": 3921,
"State": "IL",
"Year": 1964,
"variable": "Injuries",
"value":              6 
},
{
 "X": 3922,
"State": "IL",
"Year": 1965,
"variable": "Injuries",
"value":            217 
},
{
 "X": 3923,
"State": "IL",
"Year": 1966,
"variable": "Injuries",
"value":             50 
},
{
 "X": 3924,
"State": "IL",
"Year": 1967,
"variable": "Injuries",
"value":           1074 
},
{
 "X": 3925,
"State": "IL",
"Year": 1968,
"variable": "Injuries",
"value":            135 
},
{
 "X": 3926,
"State": "IL",
"Year": 1969,
"variable": "Injuries",
"value":              4 
},
{
 "X": 3927,
"State": "IL",
"Year": 1970,
"variable": "Injuries",
"value":             16 
},
{
 "X": 3928,
"State": "IL",
"Year": 1971,
"variable": "Injuries",
"value":             48 
},
{
 "X": 3929,
"State": "IL",
"Year": 1972,
"variable": "Injuries",
"value":             70 
},
{
 "X": 3930,
"State": "IL",
"Year": 1973,
"variable": "Injuries",
"value":              9 
},
{
 "X": 3931,
"State": "IL",
"Year": 1974,
"variable": "Injuries",
"value":             66 
},
{
 "X": 3932,
"State": "IL",
"Year": 1975,
"variable": "Injuries",
"value":             78 
},
{
 "X": 3933,
"State": "IL",
"Year": 1976,
"variable": "Injuries",
"value":            118 
},
{
 "X": 3934,
"State": "IL",
"Year": 1977,
"variable": "Injuries",
"value":             61 
},
{
 "X": 3935,
"State": "IL",
"Year": 1978,
"variable": "Injuries",
"value":              4 
},
{
 "X": 3936,
"State": "IL",
"Year": 1979,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3937,
"State": "IL",
"Year": 1980,
"variable": "Injuries",
"value":              7 
},
{
 "X": 3938,
"State": "IL",
"Year": 1981,
"variable": "Injuries",
"value":             48 
},
{
 "X": 3939,
"State": "IL",
"Year": 1982,
"variable": "Injuries",
"value":            213 
},
{
 "X": 3940,
"State": "IL",
"Year": 1983,
"variable": "Injuries",
"value":             43 
},
{
 "X": 3941,
"State": "IL",
"Year": 1984,
"variable": "Injuries",
"value":             30 
},
{
 "X": 3942,
"State": "IL",
"Year": 1985,
"variable": "Injuries",
"value":             25 
},
{
 "X": 3943,
"State": "IL",
"Year": 1986,
"variable": "Injuries",
"value":             20 
},
{
 "X": 3944,
"State": "IL",
"Year": 1987,
"variable": "Injuries",
"value":             69 
},
{
 "X": 3945,
"State": "IL",
"Year": 1988,
"variable": "Injuries",
"value":             30 
},
{
 "X": 3946,
"State": "IL",
"Year": 1989,
"variable": "Injuries",
"value":             90 
},
{
 "X": 3947,
"State": "IL",
"Year": 1990,
"variable": "Injuries",
"value":            379 
},
{
 "X": 3948,
"State": "IL",
"Year": 1991,
"variable": "Injuries",
"value":             30 
},
{
 "X": 3949,
"State": "IL",
"Year": 1992,
"variable": "Injuries",
"value":             61 
},
{
 "X": 3950,
"State": "IL",
"Year": 1993,
"variable": "Injuries",
"value":              8 
},
{
 "X": 3951,
"State": "IL",
"Year": 1994,
"variable": "Injuries",
"value":             31 
},
{
 "X": 3952,
"State": "IL",
"Year": 1995,
"variable": "Injuries",
"value":            364 
},
{
 "X": 3953,
"State": "IL",
"Year": 1996,
"variable": "Injuries",
"value":            106 
},
{
 "X": 3954,
"State": "IL",
"Year": 1997,
"variable": "Injuries",
"value":             62 
},
{
 "X": 3955,
"State": "IL",
"Year": 1998,
"variable": "Injuries",
"value":            218 
},
{
 "X": 3956,
"State": "IL",
"Year": 1999,
"variable": "Injuries",
"value":            186 
},
{
 "X": 3957,
"State": "IL",
"Year": 2000,
"variable": "Injuries",
"value":             37 
},
{
 "X": 3958,
"State": "IL",
"Year": 2001,
"variable": "Injuries",
"value":             34 
},
{
 "X": 3959,
"State": "IL",
"Year": 2002,
"variable": "Injuries",
"value":             93 
},
{
 "X": 3960,
"State": "IL",
"Year": 2003,
"variable": "Injuries",
"value":            101 
},
{
 "X": 3961,
"State": "IL",
"Year": 2004,
"variable": "Injuries",
"value":             47 
},
{
 "X": 3962,
"State": "IL",
"Year": 2005,
"variable": "Injuries",
"value":             71 
},
{
 "X": 3963,
"State": "IL",
"Year": 2006,
"variable": "Injuries",
"value":             87 
},
{
 "X": 3964,
"State": "IL",
"Year": 2007,
"variable": "Injuries",
"value":             85 
},
{
 "X": 3965,
"State": "IL",
"Year": 2008,
"variable": "Injuries",
"value":             46 
},
{
 "X": 3966,
"State": "IL",
"Year": 2009,
"variable": "Injuries",
"value":             44 
},
{
 "X": 3967,
"State": "IL",
"Year": 2010,
"variable": "Injuries",
"value":             67 
},
{
 "X": 3968,
"State": "IL",
"Year": 2011,
"variable": "Injuries",
"value":             44 
},
{
 "X": 3969,
"State": "IN",
"Year": 1950,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3970,
"State": "IN",
"Year": 1951,
"variable": "Injuries",
"value":              6 
},
{
 "X": 3971,
"State": "IN",
"Year": 1952,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3972,
"State": "IN",
"Year": 1953,
"variable": "Injuries",
"value":             12 
},
{
 "X": 3973,
"State": "IN",
"Year": 1954,
"variable": "Injuries",
"value":              4 
},
{
 "X": 3974,
"State": "IN",
"Year": 1955,
"variable": "Injuries",
"value":             29 
},
{
 "X": 3975,
"State": "IN",
"Year": 1956,
"variable": "Injuries",
"value":             52 
},
{
 "X": 3976,
"State": "IN",
"Year": 1957,
"variable": "Injuries",
"value":              3 
},
{
 "X": 3977,
"State": "IN",
"Year": 1958,
"variable": "Injuries",
"value":              4 
},
{
 "X": 3978,
"State": "IN",
"Year": 1959,
"variable": "Injuries",
"value":              0 
},
{
 "X": 3979,
"State": "IN",
"Year": 1960,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3980,
"State": "IN",
"Year": 1961,
"variable": "Injuries",
"value":             27 
},
{
 "X": 3981,
"State": "IN",
"Year": 1962,
"variable": "Injuries",
"value":             54 
},
{
 "X": 3982,
"State": "IN",
"Year": 1963,
"variable": "Injuries",
"value":             53 
},
{
 "X": 3983,
"State": "IN",
"Year": 1964,
"variable": "Injuries",
"value":              4 
},
{
 "X": 3984,
"State": "IN",
"Year": 1965,
"variable": "Injuries",
"value":           1820 
},
{
 "X": 3985,
"State": "IN",
"Year": 1966,
"variable": "Injuries",
"value":              1 
},
{
 "X": 3986,
"State": "IN",
"Year": 1967,
"variable": "Injuries",
"value":             16 
},
{
 "X": 3987,
"State": "IN",
"Year": 1968,
"variable": "Injuries",
"value":             25 
},
{
 "X": 3988,
"State": "IN",
"Year": 1969,
"variable": "Injuries",
"value":             13 
},
{
 "X": 3989,
"State": "IN",
"Year": 1970,
"variable": "Injuries",
"value":             13 
},
{
 "X": 3990,
"State": "IN",
"Year": 1971,
"variable": "Injuries",
"value":             15 
},
{
 "X": 3991,
"State": "IN",
"Year": 1972,
"variable": "Injuries",
"value":             20 
},
{
 "X": 3992,
"State": "IN",
"Year": 1973,
"variable": "Injuries",
"value":              2 
},
{
 "X": 3993,
"State": "IN",
"Year": 1974,
"variable": "Injuries",
"value":            837 
},
{
 "X": 3994,
"State": "IN",
"Year": 1975,
"variable": "Injuries",
"value":             29 
},
{
 "X": 3995,
"State": "IN",
"Year": 1976,
"variable": "Injuries",
"value":             74 
},
{
 "X": 3996,
"State": "IN",
"Year": 1977,
"variable": "Injuries",
"value":              5 
},
{
 "X": 3997,
"State": "IN",
"Year": 1978,
"variable": "Injuries",
"value":              6 
},
{
 "X": 3998,
"State": "IN",
"Year": 1979,
"variable": "Injuries",
"value":              3 
},
{
 "X": 3999,
"State": "IN",
"Year": 1980,
"variable": "Injuries",
"value":             61 
},
{
 "X": 4000,
"State": "IN",
"Year": 1981,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4001,
"State": "IN",
"Year": 1982,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4002,
"State": "IN",
"Year": 1983,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4003,
"State": "IN",
"Year": 1984,
"variable": "Injuries",
"value":              7 
},
{
 "X": 4004,
"State": "IN",
"Year": 1985,
"variable": "Injuries",
"value":             12 
},
{
 "X": 4005,
"State": "IN",
"Year": 1986,
"variable": "Injuries",
"value":             51 
},
{
 "X": 4006,
"State": "IN",
"Year": 1987,
"variable": "Injuries",
"value":              5 
},
{
 "X": 4007,
"State": "IN",
"Year": 1988,
"variable": "Injuries",
"value":             33 
},
{
 "X": 4008,
"State": "IN",
"Year": 1989,
"variable": "Injuries",
"value":             39 
},
{
 "X": 4009,
"State": "IN",
"Year": 1990,
"variable": "Injuries",
"value":            235 
},
{
 "X": 4010,
"State": "IN",
"Year": 1991,
"variable": "Injuries",
"value":             32 
},
{
 "X": 4011,
"State": "IN",
"Year": 1992,
"variable": "Injuries",
"value":             79 
},
{
 "X": 4012,
"State": "IN",
"Year": 1993,
"variable": "Injuries",
"value":              7 
},
{
 "X": 4013,
"State": "IN",
"Year": 1994,
"variable": "Injuries",
"value":             81 
},
{
 "X": 4014,
"State": "IN",
"Year": 1995,
"variable": "Injuries",
"value":            115 
},
{
 "X": 4015,
"State": "IN",
"Year": 1996,
"variable": "Injuries",
"value":             35 
},
{
 "X": 4016,
"State": "IN",
"Year": 1997,
"variable": "Injuries",
"value":              6 
},
{
 "X": 4017,
"State": "IN",
"Year": 1998,
"variable": "Injuries",
"value":             42 
},
{
 "X": 4018,
"State": "IN",
"Year": 1999,
"variable": "Injuries",
"value":             14 
},
{
 "X": 4019,
"State": "IN",
"Year": 2000,
"variable": "Injuries",
"value":             22 
},
{
 "X": 4020,
"State": "IN",
"Year": 2001,
"variable": "Injuries",
"value":             36 
},
{
 "X": 4021,
"State": "IN",
"Year": 2002,
"variable": "Injuries",
"value":            153 
},
{
 "X": 4022,
"State": "IN",
"Year": 2003,
"variable": "Injuries",
"value":             10 
},
{
 "X": 4023,
"State": "IN",
"Year": 2004,
"variable": "Injuries",
"value":             55 
},
{
 "X": 4024,
"State": "IN",
"Year": 2005,
"variable": "Injuries",
"value":            288 
},
{
 "X": 4025,
"State": "IN",
"Year": 2006,
"variable": "Injuries",
"value":             28 
},
{
 "X": 4026,
"State": "IN",
"Year": 2007,
"variable": "Injuries",
"value":              4 
},
{
 "X": 4027,
"State": "IN",
"Year": 2008,
"variable": "Injuries",
"value":             59 
},
{
 "X": 4028,
"State": "IN",
"Year": 2009,
"variable": "Injuries",
"value":              8 
},
{
 "X": 4029,
"State": "IN",
"Year": 2010,
"variable": "Injuries",
"value":             15 
},
{
 "X": 4030,
"State": "IN",
"Year": 2011,
"variable": "Injuries",
"value":             60 
},
{
 "X": 4031,
"State": "KS",
"Year": 1950,
"variable": "Injuries",
"value":             26 
},
{
 "X": 4032,
"State": "KS",
"Year": 1951,
"variable": "Injuries",
"value":            115 
},
{
 "X": 4033,
"State": "KS",
"Year": 1952,
"variable": "Injuries",
"value":              3 
},
{
 "X": 4034,
"State": "KS",
"Year": 1953,
"variable": "Injuries",
"value":              3 
},
{
 "X": 4035,
"State": "KS",
"Year": 1954,
"variable": "Injuries",
"value":              2 
},
{
 "X": 4036,
"State": "KS",
"Year": 1955,
"variable": "Injuries",
"value":            275 
},
{
 "X": 4037,
"State": "KS",
"Year": 1956,
"variable": "Injuries",
"value":             52 
},
{
 "X": 4038,
"State": "KS",
"Year": 1957,
"variable": "Injuries",
"value":             36 
},
{
 "X": 4039,
"State": "KS",
"Year": 1958,
"variable": "Injuries",
"value":             24 
},
{
 "X": 4040,
"State": "KS",
"Year": 1959,
"variable": "Injuries",
"value":              5 
},
{
 "X": 4041,
"State": "KS",
"Year": 1960,
"variable": "Injuries",
"value":            121 
},
{
 "X": 4042,
"State": "KS",
"Year": 1961,
"variable": "Injuries",
"value":             15 
},
{
 "X": 4043,
"State": "KS",
"Year": 1962,
"variable": "Injuries",
"value":             16 
},
{
 "X": 4044,
"State": "KS",
"Year": 1963,
"variable": "Injuries",
"value":              3 
},
{
 "X": 4045,
"State": "KS",
"Year": 1964,
"variable": "Injuries",
"value":             42 
},
{
 "X": 4046,
"State": "KS",
"Year": 1965,
"variable": "Injuries",
"value":             55 
},
{
 "X": 4047,
"State": "KS",
"Year": 1966,
"variable": "Injuries",
"value":            513 
},
{
 "X": 4048,
"State": "KS",
"Year": 1967,
"variable": "Injuries",
"value":             40 
},
{
 "X": 4049,
"State": "KS",
"Year": 1968,
"variable": "Injuries",
"value":             16 
},
{
 "X": 4050,
"State": "KS",
"Year": 1969,
"variable": "Injuries",
"value":             77 
},
{
 "X": 4051,
"State": "KS",
"Year": 1970,
"variable": "Injuries",
"value":              5 
},
{
 "X": 4052,
"State": "KS",
"Year": 1971,
"variable": "Injuries",
"value":             13 
},
{
 "X": 4053,
"State": "KS",
"Year": 1972,
"variable": "Injuries",
"value":             17 
},
{
 "X": 4054,
"State": "KS",
"Year": 1973,
"variable": "Injuries",
"value":             53 
},
{
 "X": 4055,
"State": "KS",
"Year": 1974,
"variable": "Injuries",
"value":            187 
},
{
 "X": 4056,
"State": "KS",
"Year": 1975,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4057,
"State": "KS",
"Year": 1976,
"variable": "Injuries",
"value":              4 
},
{
 "X": 4058,
"State": "KS",
"Year": 1977,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4059,
"State": "KS",
"Year": 1978,
"variable": "Injuries",
"value":              6 
},
{
 "X": 4060,
"State": "KS",
"Year": 1979,
"variable": "Injuries",
"value":             20 
},
{
 "X": 4061,
"State": "KS",
"Year": 1980,
"variable": "Injuries",
"value":              5 
},
{
 "X": 4062,
"State": "KS",
"Year": 1981,
"variable": "Injuries",
"value":             42 
},
{
 "X": 4063,
"State": "KS",
"Year": 1982,
"variable": "Injuries",
"value":             21 
},
{
 "X": 4064,
"State": "KS",
"Year": 1983,
"variable": "Injuries",
"value":             29 
},
{
 "X": 4065,
"State": "KS",
"Year": 1984,
"variable": "Injuries",
"value":             45 
},
{
 "X": 4066,
"State": "KS",
"Year": 1985,
"variable": "Injuries",
"value":             14 
},
{
 "X": 4067,
"State": "KS",
"Year": 1986,
"variable": "Injuries",
"value":             28 
},
{
 "X": 4068,
"State": "KS",
"Year": 1987,
"variable": "Injuries",
"value":             61 
},
{
 "X": 4069,
"State": "KS",
"Year": 1988,
"variable": "Injuries",
"value":             33 
},
{
 "X": 4070,
"State": "KS",
"Year": 1989,
"variable": "Injuries",
"value":              5 
},
{
 "X": 4071,
"State": "KS",
"Year": 1990,
"variable": "Injuries",
"value":            123 
},
{
 "X": 4072,
"State": "KS",
"Year": 1991,
"variable": "Injuries",
"value":            271 
},
{
 "X": 4073,
"State": "KS",
"Year": 1992,
"variable": "Injuries",
"value":             88 
},
{
 "X": 4074,
"State": "KS",
"Year": 1993,
"variable": "Injuries",
"value":             23 
},
{
 "X": 4075,
"State": "KS",
"Year": 1994,
"variable": "Injuries",
"value":             39 
},
{
 "X": 4076,
"State": "KS",
"Year": 1995,
"variable": "Injuries",
"value":             32 
},
{
 "X": 4077,
"State": "KS",
"Year": 1996,
"variable": "Injuries",
"value":             18 
},
{
 "X": 4078,
"State": "KS",
"Year": 1997,
"variable": "Injuries",
"value":             35 
},
{
 "X": 4079,
"State": "KS",
"Year": 1998,
"variable": "Injuries",
"value":             32 
},
{
 "X": 4080,
"State": "KS",
"Year": 1999,
"variable": "Injuries",
"value":            182 
},
{
 "X": 4081,
"State": "KS",
"Year": 2000,
"variable": "Injuries",
"value":             72 
},
{
 "X": 4082,
"State": "KS",
"Year": 2001,
"variable": "Injuries",
"value":             49 
},
{
 "X": 4083,
"State": "KS",
"Year": 2002,
"variable": "Injuries",
"value":              9 
},
{
 "X": 4084,
"State": "KS",
"Year": 2003,
"variable": "Injuries",
"value":            128 
},
{
 "X": 4085,
"State": "KS",
"Year": 2004,
"variable": "Injuries",
"value":             37 
},
{
 "X": 4086,
"State": "KS",
"Year": 2005,
"variable": "Injuries",
"value":             40 
},
{
 "X": 4087,
"State": "KS",
"Year": 2006,
"variable": "Injuries",
"value":             28 
},
{
 "X": 4088,
"State": "KS",
"Year": 2007,
"variable": "Injuries",
"value":             96 
},
{
 "X": 4089,
"State": "KS",
"Year": 2008,
"variable": "Injuries",
"value":             32 
},
{
 "X": 4090,
"State": "KS",
"Year": 2009,
"variable": "Injuries",
"value":             38 
},
{
 "X": 4091,
"State": "KS",
"Year": 2010,
"variable": "Injuries",
"value":             27 
},
{
 "X": 4092,
"State": "KS",
"Year": 2011,
"variable": "Injuries",
"value":             22 
},
{
 "X": 4093,
"State": "KY",
"Year": 1950,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4094,
"State": "KY",
"Year": 1951,
"variable": "Injuries",
"value":             11 
},
{
 "X": 4095,
"State": "KY",
"Year": 1952,
"variable": "Injuries",
"value":             21 
},
{
 "X": 4096,
"State": "KY",
"Year": 1953,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4097,
"State": "KY",
"Year": 1954,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4098,
"State": "KY",
"Year": 1955,
"variable": "Injuries",
"value":             13 
},
{
 "X": 4099,
"State": "KY",
"Year": 1956,
"variable": "Injuries",
"value":             16 
},
{
 "X": 4100,
"State": "KY",
"Year": 1957,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4101,
"State": "KY",
"Year": 1958,
"variable": "Injuries",
"value":             12 
},
{
 "X": 4102,
"State": "KY",
"Year": 1959,
"variable": "Injuries",
"value":              6 
},
{
 "X": 4103,
"State": "KY",
"Year": 1960,
"variable": "Injuries",
"value":             12 
},
{
 "X": 4104,
"State": "KY",
"Year": 1961,
"variable": "Injuries",
"value":             66 
},
{
 "X": 4105,
"State": "KY",
"Year": 1962,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4106,
"State": "KY",
"Year": 1963,
"variable": "Injuries",
"value":              7 
},
{
 "X": 4107,
"State": "KY",
"Year": 1964,
"variable": "Injuries",
"value":             35 
},
{
 "X": 4108,
"State": "KY",
"Year": 1965,
"variable": "Injuries",
"value":             11 
},
{
 "X": 4109,
"State": "KY",
"Year": 1966,
"variable": "Injuries",
"value":              2 
},
{
 "X": 4110,
"State": "KY",
"Year": 1967,
"variable": "Injuries",
"value":              7 
},
{
 "X": 4111,
"State": "KY",
"Year": 1968,
"variable": "Injuries",
"value":            398 
},
{
 "X": 4112,
"State": "KY",
"Year": 1969,
"variable": "Injuries",
"value":             15 
},
{
 "X": 4113,
"State": "KY",
"Year": 1970,
"variable": "Injuries",
"value":             15 
},
{
 "X": 4114,
"State": "KY",
"Year": 1971,
"variable": "Injuries",
"value":            130 
},
{
 "X": 4115,
"State": "KY",
"Year": 1972,
"variable": "Injuries",
"value":              9 
},
{
 "X": 4116,
"State": "KY",
"Year": 1973,
"variable": "Injuries",
"value":             15 
},
{
 "X": 4117,
"State": "KY",
"Year": 1974,
"variable": "Injuries",
"value":           1306 
},
{
 "X": 4118,
"State": "KY",
"Year": 1975,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4119,
"State": "KY",
"Year": 1976,
"variable": "Injuries",
"value":             11 
},
{
 "X": 4120,
"State": "KY",
"Year": 1977,
"variable": "Injuries",
"value":             23 
},
{
 "X": 4121,
"State": "KY",
"Year": 1978,
"variable": "Injuries",
"value":             17 
},
{
 "X": 4122,
"State": "KY",
"Year": 1979,
"variable": "Injuries",
"value":             33 
},
{
 "X": 4123,
"State": "KY",
"Year": 1980,
"variable": "Injuries",
"value":             14 
},
{
 "X": 4124,
"State": "KY",
"Year": 1981,
"variable": "Injuries",
"value":             10 
},
{
 "X": 4125,
"State": "KY",
"Year": 1982,
"variable": "Injuries",
"value":             22 
},
{
 "X": 4126,
"State": "KY",
"Year": 1983,
"variable": "Injuries",
"value":              7 
},
{
 "X": 4127,
"State": "KY",
"Year": 1984,
"variable": "Injuries",
"value":             14 
},
{
 "X": 4128,
"State": "KY",
"Year": 1985,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4129,
"State": "KY",
"Year": 1986,
"variable": "Injuries",
"value":             81 
},
{
 "X": 4130,
"State": "KY",
"Year": 1987,
"variable": "Injuries",
"value":             28 
},
{
 "X": 4131,
"State": "KY",
"Year": 1988,
"variable": "Injuries",
"value":             15 
},
{
 "X": 4132,
"State": "KY",
"Year": 1989,
"variable": "Injuries",
"value":             25 
},
{
 "X": 4133,
"State": "KY",
"Year": 1990,
"variable": "Injuries",
"value":             23 
},
{
 "X": 4134,
"State": "KY",
"Year": 1991,
"variable": "Injuries",
"value":             41 
},
{
 "X": 4135,
"State": "KY",
"Year": 1992,
"variable": "Injuries",
"value":             13 
},
{
 "X": 4136,
"State": "KY",
"Year": 1993,
"variable": "Injuries",
"value":              5 
},
{
 "X": 4137,
"State": "KY",
"Year": 1994,
"variable": "Injuries",
"value":              9 
},
{
 "X": 4138,
"State": "KY",
"Year": 1995,
"variable": "Injuries",
"value":            131 
},
{
 "X": 4139,
"State": "KY",
"Year": 1996,
"variable": "Injuries",
"value":             77 
},
{
 "X": 4140,
"State": "KY",
"Year": 1997,
"variable": "Injuries",
"value":             50 
},
{
 "X": 4141,
"State": "KY",
"Year": 1998,
"variable": "Injuries",
"value":             29 
},
{
 "X": 4142,
"State": "KY",
"Year": 1999,
"variable": "Injuries",
"value":             35 
},
{
 "X": 4143,
"State": "KY",
"Year": 2000,
"variable": "Injuries",
"value":            121 
},
{
 "X": 4144,
"State": "KY",
"Year": 2001,
"variable": "Injuries",
"value":             31 
},
{
 "X": 4145,
"State": "KY",
"Year": 2002,
"variable": "Injuries",
"value":             60 
},
{
 "X": 4146,
"State": "KY",
"Year": 2003,
"variable": "Injuries",
"value":             57 
},
{
 "X": 4147,
"State": "KY",
"Year": 2004,
"variable": "Injuries",
"value":             17 
},
{
 "X": 4148,
"State": "KY",
"Year": 2005,
"variable": "Injuries",
"value":            142 
},
{
 "X": 4149,
"State": "KY",
"Year": 2006,
"variable": "Injuries",
"value":             46 
},
{
 "X": 4150,
"State": "KY",
"Year": 2007,
"variable": "Injuries",
"value":             40 
},
{
 "X": 4151,
"State": "KY",
"Year": 2008,
"variable": "Injuries",
"value":             76 
},
{
 "X": 4152,
"State": "KY",
"Year": 2009,
"variable": "Injuries",
"value":             29 
},
{
 "X": 4153,
"State": "KY",
"Year": 2010,
"variable": "Injuries",
"value":             12 
},
{
 "X": 4154,
"State": "KY",
"Year": 2011,
"variable": "Injuries",
"value":             28 
},
{
 "X": 4155,
"State": "LA",
"Year": 1950,
"variable": "Injuries",
"value":            144 
},
{
 "X": 4156,
"State": "LA",
"Year": 1951,
"variable": "Injuries",
"value":             14 
},
{
 "X": 4157,
"State": "LA",
"Year": 1952,
"variable": "Injuries",
"value":             51 
},
{
 "X": 4158,
"State": "LA",
"Year": 1953,
"variable": "Injuries",
"value":            150 
},
{
 "X": 4159,
"State": "LA",
"Year": 1954,
"variable": "Injuries",
"value":             11 
},
{
 "X": 4160,
"State": "LA",
"Year": 1955,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4161,
"State": "LA",
"Year": 1956,
"variable": "Injuries",
"value":              4 
},
{
 "X": 4162,
"State": "LA",
"Year": 1957,
"variable": "Injuries",
"value":             90 
},
{
 "X": 4163,
"State": "LA",
"Year": 1958,
"variable": "Injuries",
"value":              3 
},
{
 "X": 4164,
"State": "LA",
"Year": 1959,
"variable": "Injuries",
"value":              4 
},
{
 "X": 4165,
"State": "LA",
"Year": 1960,
"variable": "Injuries",
"value":             12 
},
{
 "X": 4166,
"State": "LA",
"Year": 1961,
"variable": "Injuries",
"value":            128 
},
{
 "X": 4167,
"State": "LA",
"Year": 1962,
"variable": "Injuries",
"value":             32 
},
{
 "X": 4168,
"State": "LA",
"Year": 1963,
"variable": "Injuries",
"value":              5 
},
{
 "X": 4169,
"State": "LA",
"Year": 1964,
"variable": "Injuries",
"value":            173 
},
{
 "X": 4170,
"State": "LA",
"Year": 1965,
"variable": "Injuries",
"value":             11 
},
{
 "X": 4171,
"State": "LA",
"Year": 1966,
"variable": "Injuries",
"value":              2 
},
{
 "X": 4172,
"State": "LA",
"Year": 1967,
"variable": "Injuries",
"value":             17 
},
{
 "X": 4173,
"State": "LA",
"Year": 1968,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4174,
"State": "LA",
"Year": 1969,
"variable": "Injuries",
"value":             18 
},
{
 "X": 4175,
"State": "LA",
"Year": 1970,
"variable": "Injuries",
"value":              6 
},
{
 "X": 4176,
"State": "LA",
"Year": 1971,
"variable": "Injuries",
"value":             37 
},
{
 "X": 4177,
"State": "LA",
"Year": 1972,
"variable": "Injuries",
"value":              5 
},
{
 "X": 4178,
"State": "LA",
"Year": 1973,
"variable": "Injuries",
"value":             52 
},
{
 "X": 4179,
"State": "LA",
"Year": 1974,
"variable": "Injuries",
"value":            126 
},
{
 "X": 4180,
"State": "LA",
"Year": 1975,
"variable": "Injuries",
"value":             60 
},
{
 "X": 4181,
"State": "LA",
"Year": 1976,
"variable": "Injuries",
"value":             73 
},
{
 "X": 4182,
"State": "LA",
"Year": 1977,
"variable": "Injuries",
"value":             29 
},
{
 "X": 4183,
"State": "LA",
"Year": 1978,
"variable": "Injuries",
"value":            291 
},
{
 "X": 4184,
"State": "LA",
"Year": 1979,
"variable": "Injuries",
"value":             22 
},
{
 "X": 4185,
"State": "LA",
"Year": 1980,
"variable": "Injuries",
"value":             11 
},
{
 "X": 4186,
"State": "LA",
"Year": 1981,
"variable": "Injuries",
"value":             12 
},
{
 "X": 4187,
"State": "LA",
"Year": 1982,
"variable": "Injuries",
"value":              2 
},
{
 "X": 4188,
"State": "LA",
"Year": 1983,
"variable": "Injuries",
"value":            139 
},
{
 "X": 4189,
"State": "LA",
"Year": 1984,
"variable": "Injuries",
"value":             37 
},
{
 "X": 4190,
"State": "LA",
"Year": 1985,
"variable": "Injuries",
"value":             30 
},
{
 "X": 4191,
"State": "LA",
"Year": 1986,
"variable": "Injuries",
"value":             15 
},
{
 "X": 4192,
"State": "LA",
"Year": 1987,
"variable": "Injuries",
"value":            124 
},
{
 "X": 4193,
"State": "LA",
"Year": 1988,
"variable": "Injuries",
"value":             11 
},
{
 "X": 4194,
"State": "LA",
"Year": 1989,
"variable": "Injuries",
"value":            111 
},
{
 "X": 4195,
"State": "LA",
"Year": 1990,
"variable": "Injuries",
"value":             56 
},
{
 "X": 4196,
"State": "LA",
"Year": 1991,
"variable": "Injuries",
"value":             32 
},
{
 "X": 4197,
"State": "LA",
"Year": 1992,
"variable": "Injuries",
"value":            120 
},
{
 "X": 4198,
"State": "LA",
"Year": 1993,
"variable": "Injuries",
"value":             70 
},
{
 "X": 4199,
"State": "LA",
"Year": 1994,
"variable": "Injuries",
"value":             16 
},
{
 "X": 4200,
"State": "LA",
"Year": 1995,
"variable": "Injuries",
"value":             46 
},
{
 "X": 4201,
"State": "LA",
"Year": 1996,
"variable": "Injuries",
"value":             51 
},
{
 "X": 4202,
"State": "LA",
"Year": 1997,
"variable": "Injuries",
"value":             95 
},
{
 "X": 4203,
"State": "LA",
"Year": 1998,
"variable": "Injuries",
"value":             84 
},
{
 "X": 4204,
"State": "LA",
"Year": 1999,
"variable": "Injuries",
"value":            171 
},
{
 "X": 4205,
"State": "LA",
"Year": 2000,
"variable": "Injuries",
"value":             64 
},
{
 "X": 4206,
"State": "LA",
"Year": 2001,
"variable": "Injuries",
"value":             19 
},
{
 "X": 4207,
"State": "LA",
"Year": 2002,
"variable": "Injuries",
"value":             24 
},
{
 "X": 4208,
"State": "LA",
"Year": 2003,
"variable": "Injuries",
"value":             15 
},
{
 "X": 4209,
"State": "LA",
"Year": 2004,
"variable": "Injuries",
"value":             37 
},
{
 "X": 4210,
"State": "LA",
"Year": 2005,
"variable": "Injuries",
"value":             34 
},
{
 "X": 4211,
"State": "LA",
"Year": 2006,
"variable": "Injuries",
"value":             40 
},
{
 "X": 4212,
"State": "LA",
"Year": 2007,
"variable": "Injuries",
"value":             60 
},
{
 "X": 4213,
"State": "LA",
"Year": 2008,
"variable": "Injuries",
"value":             22 
},
{
 "X": 4214,
"State": "LA",
"Year": 2009,
"variable": "Injuries",
"value":             35 
},
{
 "X": 4215,
"State": "LA",
"Year": 2010,
"variable": "Injuries",
"value":             18 
},
{
 "X": 4216,
"State": "LA",
"Year": 2011,
"variable": "Injuries",
"value":             43 
},
{
 "X": 4217,
"State": "MA",
"Year": 1950,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4218,
"State": "MA",
"Year": 1951,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4219,
"State": "MA",
"Year": 1952,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4220,
"State": "MA",
"Year": 1953,
"variable": "Injuries",
"value":           1245 
},
{
 "X": 4221,
"State": "MA",
"Year": 1954,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4222,
"State": "MA",
"Year": 1955,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4223,
"State": "MA",
"Year": 1956,
"variable": "Injuries",
"value":             14 
},
{
 "X": 4224,
"State": "MA",
"Year": 1957,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4225,
"State": "MA",
"Year": 1958,
"variable": "Injuries",
"value":              2 
},
{
 "X": 4226,
"State": "MA",
"Year": 1959,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4227,
"State": "MA",
"Year": 1960,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4228,
"State": "MA",
"Year": 1961,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4229,
"State": "MA",
"Year": 1962,
"variable": "Injuries",
"value":              3 
},
{
 "X": 4230,
"State": "MA",
"Year": 1963,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4231,
"State": "MA",
"Year": 1964,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4232,
"State": "MA",
"Year": 1965,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4233,
"State": "MA",
"Year": 1966,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4234,
"State": "MA",
"Year": 1967,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4235,
"State": "MA",
"Year": 1968,
"variable": "Injuries",
"value":              5 
},
{
 "X": 4236,
"State": "MA",
"Year": 1969,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4237,
"State": "MA",
"Year": 1970,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4238,
"State": "MA",
"Year": 1971,
"variable": "Injuries",
"value":              3 
},
{
 "X": 4239,
"State": "MA",
"Year": 1972,
"variable": "Injuries",
"value":             11 
},
{
 "X": 4240,
"State": "MA",
"Year": 1973,
"variable": "Injuries",
"value":             36 
},
{
 "X": 4241,
"State": "MA",
"Year": 1974,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4242,
"State": "MA",
"Year": 1975,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4243,
"State": "MA",
"Year": 1976,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4244,
"State": "MA",
"Year": 1977,
"variable": "Injuries",
"value":              2 
},
{
 "X": 4245,
"State": "MA",
"Year": 1978,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4246,
"State": "MA",
"Year": 1979,
"variable": "Injuries",
"value":              3 
},
{
 "X": 4247,
"State": "MA",
"Year": 1980,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4248,
"State": "MA",
"Year": 1981,
"variable": "Injuries",
"value":              3 
},
{
 "X": 4249,
"State": "MA",
"Year": 1982,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4250,
"State": "MA",
"Year": 1983,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4251,
"State": "MA",
"Year": 1984,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4252,
"State": "MA",
"Year": 1985,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4253,
"State": "MA",
"Year": 1986,
"variable": "Injuries",
"value":              5 
},
{
 "X": 4254,
"State": "MA",
"Year": 1987,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4255,
"State": "MA",
"Year": 1988,
"variable": "Injuries",
"value":              5 
},
{
 "X": 4256,
"State": "MA",
"Year": 1989,
"variable": "Injuries",
"value":             12 
},
{
 "X": 4257,
"State": "MA",
"Year": 1990,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4258,
"State": "MA",
"Year": 1991,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4259,
"State": "MA",
"Year": 1992,
"variable": "Injuries",
"value":              4 
},
{
 "X": 4260,
"State": "MA",
"Year": 1993,
"variable": "Injuries",
"value":              2 
},
{
 "X": 4261,
"State": "MA",
"Year": 1994,
"variable": "Injuries",
"value":             41 
},
{
 "X": 4262,
"State": "MA",
"Year": 1995,
"variable": "Injuries",
"value":             36 
},
{
 "X": 4263,
"State": "MA",
"Year": 1996,
"variable": "Injuries",
"value":             77 
},
{
 "X": 4264,
"State": "MA",
"Year": 1997,
"variable": "Injuries",
"value":             34 
},
{
 "X": 4265,
"State": "MA",
"Year": 1998,
"variable": "Injuries",
"value":             19 
},
{
 "X": 4266,
"State": "MA",
"Year": 1999,
"variable": "Injuries",
"value":              4 
},
{
 "X": 4267,
"State": "MA",
"Year": 2000,
"variable": "Injuries",
"value":              8 
},
{
 "X": 4268,
"State": "MA",
"Year": 2001,
"variable": "Injuries",
"value":              3 
},
{
 "X": 4269,
"State": "MA",
"Year": 2002,
"variable": "Injuries",
"value":              2 
},
{
 "X": 4270,
"State": "MA",
"Year": 2003,
"variable": "Injuries",
"value":              7 
},
{
 "X": 4271,
"State": "MA",
"Year": 2004,
"variable": "Injuries",
"value":             14 
},
{
 "X": 4272,
"State": "MA",
"Year": 2005,
"variable": "Injuries",
"value":             28 
},
{
 "X": 4273,
"State": "MA",
"Year": 2006,
"variable": "Injuries",
"value":             15 
},
{
 "X": 4274,
"State": "MA",
"Year": 2007,
"variable": "Injuries",
"value":              5 
},
{
 "X": 4275,
"State": "MA",
"Year": 2008,
"variable": "Injuries",
"value":             30 
},
{
 "X": 4276,
"State": "MA",
"Year": 2009,
"variable": "Injuries",
"value":              9 
},
{
 "X": 4277,
"State": "MA",
"Year": 2010,
"variable": "Injuries",
"value":             26 
},
{
 "X": 4278,
"State": "MA",
"Year": 2011,
"variable": "Injuries",
"value":            406 
},
{
 "X": 4279,
"State": "MD",
"Year": 1950,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4280,
"State": "MD",
"Year": 1951,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4281,
"State": "MD",
"Year": 1952,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4282,
"State": "MD",
"Year": 1953,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4283,
"State": "MD",
"Year": 1954,
"variable": "Injuries",
"value":              8 
},
{
 "X": 4284,
"State": "MD",
"Year": 1955,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4285,
"State": "MD",
"Year": 1956,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4286,
"State": "MD",
"Year": 1957,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4287,
"State": "MD",
"Year": 1958,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4288,
"State": "MD",
"Year": 1959,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4289,
"State": "MD",
"Year": 1960,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4290,
"State": "MD",
"Year": 1961,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4291,
"State": "MD",
"Year": 1962,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4292,
"State": "MD",
"Year": 1963,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4293,
"State": "MD",
"Year": 1964,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4294,
"State": "MD",
"Year": 1965,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4295,
"State": "MD",
"Year": 1966,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4296,
"State": "MD",
"Year": 1967,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4297,
"State": "MD",
"Year": 1968,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4298,
"State": "MD",
"Year": 1969,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4299,
"State": "MD",
"Year": 1970,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4300,
"State": "MD",
"Year": 1971,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4301,
"State": "MD",
"Year": 1972,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4302,
"State": "MD",
"Year": 1973,
"variable": "Injuries",
"value":              4 
},
{
 "X": 4303,
"State": "MD",
"Year": 1974,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4304,
"State": "MD",
"Year": 1975,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4305,
"State": "MD",
"Year": 1976,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4306,
"State": "MD",
"Year": 1977,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4307,
"State": "MD",
"Year": 1978,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4308,
"State": "MD",
"Year": 1979,
"variable": "Injuries",
"value":              2 
},
{
 "X": 4309,
"State": "MD",
"Year": 1980,
"variable": "Injuries",
"value":             14 
},
{
 "X": 4310,
"State": "MD",
"Year": 1981,
"variable": "Injuries",
"value":              2 
},
{
 "X": 4311,
"State": "MD",
"Year": 1982,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4312,
"State": "MD",
"Year": 1983,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4313,
"State": "MD",
"Year": 1984,
"variable": "Injuries",
"value":             38 
},
{
 "X": 4314,
"State": "MD",
"Year": 1985,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4315,
"State": "MD",
"Year": 1986,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4316,
"State": "MD",
"Year": 1987,
"variable": "Injuries",
"value":              4 
},
{
 "X": 4317,
"State": "MD",
"Year": 1988,
"variable": "Injuries",
"value":              9 
},
{
 "X": 4318,
"State": "MD",
"Year": 1989,
"variable": "Injuries",
"value":              4 
},
{
 "X": 4319,
"State": "MD",
"Year": 1990,
"variable": "Injuries",
"value":             75 
},
{
 "X": 4320,
"State": "MD",
"Year": 1991,
"variable": "Injuries",
"value":             13 
},
{
 "X": 4321,
"State": "MD",
"Year": 1992,
"variable": "Injuries",
"value":              3 
},
{
 "X": 4322,
"State": "MD",
"Year": 1993,
"variable": "Injuries",
"value":              4 
},
{
 "X": 4323,
"State": "MD",
"Year": 1994,
"variable": "Injuries",
"value":             13 
},
{
 "X": 4324,
"State": "MD",
"Year": 1995,
"variable": "Injuries",
"value":             48 
},
{
 "X": 4325,
"State": "MD",
"Year": 1996,
"variable": "Injuries",
"value":            169 
},
{
 "X": 4326,
"State": "MD",
"Year": 1997,
"variable": "Injuries",
"value":            189 
},
{
 "X": 4327,
"State": "MD",
"Year": 1998,
"variable": "Injuries",
"value":             26 
},
{
 "X": 4328,
"State": "MD",
"Year": 1999,
"variable": "Injuries",
"value":            304 
},
{
 "X": 4329,
"State": "MD",
"Year": 2000,
"variable": "Injuries",
"value":             21 
},
{
 "X": 4330,
"State": "MD",
"Year": 2001,
"variable": "Injuries",
"value":             66 
},
{
 "X": 4331,
"State": "MD",
"Year": 2002,
"variable": "Injuries",
"value":            138 
},
{
 "X": 4332,
"State": "MD",
"Year": 2003,
"variable": "Injuries",
"value":            220 
},
{
 "X": 4333,
"State": "MD",
"Year": 2004,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4334,
"State": "MD",
"Year": 2005,
"variable": "Injuries",
"value":             41 
},
{
 "X": 4335,
"State": "MD",
"Year": 2006,
"variable": "Injuries",
"value":             65 
},
{
 "X": 4336,
"State": "MD",
"Year": 2007,
"variable": "Injuries",
"value":              5 
},
{
 "X": 4337,
"State": "MD",
"Year": 2008,
"variable": "Injuries",
"value":              3 
},
{
 "X": 4338,
"State": "MD",
"Year": 2009,
"variable": "Injuries",
"value":              8 
},
{
 "X": 4339,
"State": "MD",
"Year": 2010,
"variable": "Injuries",
"value":             34 
},
{
 "X": 4340,
"State": "MD",
"Year": 2011,
"variable": "Injuries",
"value":              4 
},
{
 "X": 4341,
"State": "ME",
"Year": 1950,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4342,
"State": "ME",
"Year": 1951,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4343,
"State": "ME",
"Year": 1952,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4344,
"State": "ME",
"Year": 1953,
"variable": "Injuries",
"value":              2 
},
{
 "X": 4345,
"State": "ME",
"Year": 1954,
"variable": "Injuries",
"value":              2 
},
{
 "X": 4346,
"State": "ME",
"Year": 1955,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4347,
"State": "ME",
"Year": 1956,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4348,
"State": "ME",
"Year": 1957,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4349,
"State": "ME",
"Year": 1958,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4350,
"State": "ME",
"Year": 1959,
"variable": "Injuries",
"value":              2 
},
{
 "X": 4351,
"State": "ME",
"Year": 1960,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4352,
"State": "ME",
"Year": 1961,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4353,
"State": "ME",
"Year": 1962,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4354,
"State": "ME",
"Year": 1963,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4355,
"State": "ME",
"Year": 1964,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4356,
"State": "ME",
"Year": 1965,
"variable": "Injuries",
"value":              3 
},
{
 "X": 4357,
"State": "ME",
"Year": 1966,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4358,
"State": "ME",
"Year": 1967,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4359,
"State": "ME",
"Year": 1968,
"variable": "Injuries",
"value":              2 
},
{
 "X": 4360,
"State": "ME",
"Year": 1969,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4361,
"State": "ME",
"Year": 1970,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4362,
"State": "ME",
"Year": 1971,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4363,
"State": "ME",
"Year": 1972,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4364,
"State": "ME",
"Year": 1973,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4365,
"State": "ME",
"Year": 1974,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4366,
"State": "ME",
"Year": 1975,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4367,
"State": "ME",
"Year": 1976,
"variable": "Injuries",
"value":              2 
},
{
 "X": 4368,
"State": "ME",
"Year": 1977,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4369,
"State": "ME",
"Year": 1978,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4370,
"State": "ME",
"Year": 1979,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4371,
"State": "ME",
"Year": 1980,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4372,
"State": "ME",
"Year": 1981,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4373,
"State": "ME",
"Year": 1982,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4374,
"State": "ME",
"Year": 1983,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4375,
"State": "ME",
"Year": 1984,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4376,
"State": "ME",
"Year": 1985,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4377,
"State": "ME",
"Year": 1986,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4378,
"State": "ME",
"Year": 1987,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4379,
"State": "ME",
"Year": 1988,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4380,
"State": "ME",
"Year": 1989,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4381,
"State": "ME",
"Year": 1990,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4382,
"State": "ME",
"Year": 1991,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4383,
"State": "ME",
"Year": 1992,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4384,
"State": "ME",
"Year": 1993,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4385,
"State": "ME",
"Year": 1994,
"variable": "Injuries",
"value":             12 
},
{
 "X": 4386,
"State": "ME",
"Year": 1995,
"variable": "Injuries",
"value":             16 
},
{
 "X": 4387,
"State": "ME",
"Year": 1996,
"variable": "Injuries",
"value":             11 
},
{
 "X": 4388,
"State": "ME",
"Year": 1997,
"variable": "Injuries",
"value":             15 
},
{
 "X": 4389,
"State": "ME",
"Year": 1998,
"variable": "Injuries",
"value":              3 
},
{
 "X": 4390,
"State": "ME",
"Year": 1999,
"variable": "Injuries",
"value":              8 
},
{
 "X": 4391,
"State": "ME",
"Year": 2000,
"variable": "Injuries",
"value":             13 
},
{
 "X": 4392,
"State": "ME",
"Year": 2001,
"variable": "Injuries",
"value":             34 
},
{
 "X": 4393,
"State": "ME",
"Year": 2002,
"variable": "Injuries",
"value":              3 
},
{
 "X": 4394,
"State": "ME",
"Year": 2003,
"variable": "Injuries",
"value":              6 
},
{
 "X": 4395,
"State": "ME",
"Year": 2004,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4396,
"State": "ME",
"Year": 2005,
"variable": "Injuries",
"value":              2 
},
{
 "X": 4397,
"State": "ME",
"Year": 2006,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4398,
"State": "ME",
"Year": 2007,
"variable": "Injuries",
"value":              4 
},
{
 "X": 4399,
"State": "ME",
"Year": 2008,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4400,
"State": "ME",
"Year": 2009,
"variable": "Injuries",
"value":             16 
},
{
 "X": 4401,
"State": "ME",
"Year": 2010,
"variable": "Injuries",
"value":              9 
},
{
 "X": 4402,
"State": "ME",
"Year": 2011,
"variable": "Injuries",
"value":              4 
},
{
 "X": 4403,
"State": "MI",
"Year": 1950,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4404,
"State": "MI",
"Year": 1951,
"variable": "Injuries",
"value":              4 
},
{
 "X": 4405,
"State": "MI",
"Year": 1952,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4406,
"State": "MI",
"Year": 1953,
"variable": "Injuries",
"value":            982 
},
{
 "X": 4407,
"State": "MI",
"Year": 1954,
"variable": "Injuries",
"value":              2 
},
{
 "X": 4408,
"State": "MI",
"Year": 1955,
"variable": "Injuries",
"value":              2 
},
{
 "X": 4409,
"State": "MI",
"Year": 1956,
"variable": "Injuries",
"value":            534 
},
{
 "X": 4410,
"State": "MI",
"Year": 1957,
"variable": "Injuries",
"value":             18 
},
{
 "X": 4411,
"State": "MI",
"Year": 1958,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4412,
"State": "MI",
"Year": 1959,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4413,
"State": "MI",
"Year": 1960,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4414,
"State": "MI",
"Year": 1961,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4415,
"State": "MI",
"Year": 1962,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4416,
"State": "MI",
"Year": 1963,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4417,
"State": "MI",
"Year": 1964,
"variable": "Injuries",
"value":            233 
},
{
 "X": 4418,
"State": "MI",
"Year": 1965,
"variable": "Injuries",
"value":            800 
},
{
 "X": 4419,
"State": "MI",
"Year": 1966,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4420,
"State": "MI",
"Year": 1967,
"variable": "Injuries",
"value":             56 
},
{
 "X": 4421,
"State": "MI",
"Year": 1968,
"variable": "Injuries",
"value":             14 
},
{
 "X": 4422,
"State": "MI",
"Year": 1969,
"variable": "Injuries",
"value":             65 
},
{
 "X": 4423,
"State": "MI",
"Year": 1970,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4424,
"State": "MI",
"Year": 1971,
"variable": "Injuries",
"value":              5 
},
{
 "X": 4425,
"State": "MI",
"Year": 1972,
"variable": "Injuries",
"value":              9 
},
{
 "X": 4426,
"State": "MI",
"Year": 1973,
"variable": "Injuries",
"value":             10 
},
{
 "X": 4427,
"State": "MI",
"Year": 1974,
"variable": "Injuries",
"value":             51 
},
{
 "X": 4428,
"State": "MI",
"Year": 1975,
"variable": "Injuries",
"value":             18 
},
{
 "X": 4429,
"State": "MI",
"Year": 1976,
"variable": "Injuries",
"value":             93 
},
{
 "X": 4430,
"State": "MI",
"Year": 1977,
"variable": "Injuries",
"value":             69 
},
{
 "X": 4431,
"State": "MI",
"Year": 1978,
"variable": "Injuries",
"value":             12 
},
{
 "X": 4432,
"State": "MI",
"Year": 1979,
"variable": "Injuries",
"value":              7 
},
{
 "X": 4433,
"State": "MI",
"Year": 1980,
"variable": "Injuries",
"value":             97 
},
{
 "X": 4434,
"State": "MI",
"Year": 1981,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4435,
"State": "MI",
"Year": 1982,
"variable": "Injuries",
"value":              7 
},
{
 "X": 4436,
"State": "MI",
"Year": 1983,
"variable": "Injuries",
"value":              4 
},
{
 "X": 4437,
"State": "MI",
"Year": 1984,
"variable": "Injuries",
"value":             15 
},
{
 "X": 4438,
"State": "MI",
"Year": 1985,
"variable": "Injuries",
"value":              6 
},
{
 "X": 4439,
"State": "MI",
"Year": 1986,
"variable": "Injuries",
"value":             36 
},
{
 "X": 4440,
"State": "MI",
"Year": 1987,
"variable": "Injuries",
"value":             26 
},
{
 "X": 4441,
"State": "MI",
"Year": 1988,
"variable": "Injuries",
"value":             23 
},
{
 "X": 4442,
"State": "MI",
"Year": 1989,
"variable": "Injuries",
"value":             11 
},
{
 "X": 4443,
"State": "MI",
"Year": 1990,
"variable": "Injuries",
"value":              7 
},
{
 "X": 4444,
"State": "MI",
"Year": 1991,
"variable": "Injuries",
"value":             45 
},
{
 "X": 4445,
"State": "MI",
"Year": 1992,
"variable": "Injuries",
"value":             45 
},
{
 "X": 4446,
"State": "MI",
"Year": 1993,
"variable": "Injuries",
"value":              7 
},
{
 "X": 4447,
"State": "MI",
"Year": 1994,
"variable": "Injuries",
"value":             53 
},
{
 "X": 4448,
"State": "MI",
"Year": 1995,
"variable": "Injuries",
"value":             23 
},
{
 "X": 4449,
"State": "MI",
"Year": 1996,
"variable": "Injuries",
"value":             13 
},
{
 "X": 4450,
"State": "MI",
"Year": 1997,
"variable": "Injuries",
"value":            130 
},
{
 "X": 4451,
"State": "MI",
"Year": 1998,
"variable": "Injuries",
"value":            187 
},
{
 "X": 4452,
"State": "MI",
"Year": 1999,
"variable": "Injuries",
"value":            102 
},
{
 "X": 4453,
"State": "MI",
"Year": 2000,
"variable": "Injuries",
"value":             27 
},
{
 "X": 4454,
"State": "MI",
"Year": 2001,
"variable": "Injuries",
"value":            223 
},
{
 "X": 4455,
"State": "MI",
"Year": 2002,
"variable": "Injuries",
"value":             47 
},
{
 "X": 4456,
"State": "MI",
"Year": 2003,
"variable": "Injuries",
"value":             18 
},
{
 "X": 4457,
"State": "MI",
"Year": 2004,
"variable": "Injuries",
"value":             13 
},
{
 "X": 4458,
"State": "MI",
"Year": 2005,
"variable": "Injuries",
"value":             14 
},
{
 "X": 4459,
"State": "MI",
"Year": 2006,
"variable": "Injuries",
"value":            331 
},
{
 "X": 4460,
"State": "MI",
"Year": 2007,
"variable": "Injuries",
"value":             24 
},
{
 "X": 4461,
"State": "MI",
"Year": 2008,
"variable": "Injuries",
"value":              4 
},
{
 "X": 4462,
"State": "MI",
"Year": 2009,
"variable": "Injuries",
"value":              4 
},
{
 "X": 4463,
"State": "MI",
"Year": 2010,
"variable": "Injuries",
"value":             27 
},
{
 "X": 4464,
"State": "MI",
"Year": 2011,
"variable": "Injuries",
"value":             31 
},
{
 "X": 4465,
"State": "MN",
"Year": 1950,
"variable": "Injuries",
"value":              4 
},
{
 "X": 4466,
"State": "MN",
"Year": 1951,
"variable": "Injuries",
"value":             60 
},
{
 "X": 4467,
"State": "MN",
"Year": 1952,
"variable": "Injuries",
"value":             29 
},
{
 "X": 4468,
"State": "MN",
"Year": 1953,
"variable": "Injuries",
"value":             24 
},
{
 "X": 4469,
"State": "MN",
"Year": 1954,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4470,
"State": "MN",
"Year": 1955,
"variable": "Injuries",
"value":             24 
},
{
 "X": 4471,
"State": "MN",
"Year": 1956,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4472,
"State": "MN",
"Year": 1957,
"variable": "Injuries",
"value":              4 
},
{
 "X": 4473,
"State": "MN",
"Year": 1958,
"variable": "Injuries",
"value":             16 
},
{
 "X": 4474,
"State": "MN",
"Year": 1959,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4475,
"State": "MN",
"Year": 1960,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4476,
"State": "MN",
"Year": 1961,
"variable": "Injuries",
"value":              4 
},
{
 "X": 4477,
"State": "MN",
"Year": 1962,
"variable": "Injuries",
"value":             37 
},
{
 "X": 4478,
"State": "MN",
"Year": 1963,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4479,
"State": "MN",
"Year": 1964,
"variable": "Injuries",
"value":             29 
},
{
 "X": 4480,
"State": "MN",
"Year": 1965,
"variable": "Injuries",
"value":            689 
},
{
 "X": 4481,
"State": "MN",
"Year": 1966,
"variable": "Injuries",
"value":              5 
},
{
 "X": 4482,
"State": "MN",
"Year": 1967,
"variable": "Injuries",
"value":             94 
},
{
 "X": 4483,
"State": "MN",
"Year": 1968,
"variable": "Injuries",
"value":            155 
},
{
 "X": 4484,
"State": "MN",
"Year": 1969,
"variable": "Injuries",
"value":            117 
},
{
 "X": 4485,
"State": "MN",
"Year": 1970,
"variable": "Injuries",
"value":              9 
},
{
 "X": 4486,
"State": "MN",
"Year": 1971,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4487,
"State": "MN",
"Year": 1972,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4488,
"State": "MN",
"Year": 1973,
"variable": "Injuries",
"value":             22 
},
{
 "X": 4489,
"State": "MN",
"Year": 1974,
"variable": "Injuries",
"value":              9 
},
{
 "X": 4490,
"State": "MN",
"Year": 1975,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4491,
"State": "MN",
"Year": 1976,
"variable": "Injuries",
"value":             17 
},
{
 "X": 4492,
"State": "MN",
"Year": 1977,
"variable": "Injuries",
"value":             33 
},
{
 "X": 4493,
"State": "MN",
"Year": 1978,
"variable": "Injuries",
"value":             48 
},
{
 "X": 4494,
"State": "MN",
"Year": 1979,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4495,
"State": "MN",
"Year": 1980,
"variable": "Injuries",
"value":             16 
},
{
 "X": 4496,
"State": "MN",
"Year": 1981,
"variable": "Injuries",
"value":             94 
},
{
 "X": 4497,
"State": "MN",
"Year": 1982,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4498,
"State": "MN",
"Year": 1983,
"variable": "Injuries",
"value":              4 
},
{
 "X": 4499,
"State": "MN",
"Year": 1984,
"variable": "Injuries",
"value":             79 
},
{
 "X": 4500,
"State": "MN",
"Year": 1985,
"variable": "Injuries",
"value":              6 
},
{
 "X": 4501,
"State": "MN",
"Year": 1986,
"variable": "Injuries",
"value":              3 
},
{
 "X": 4502,
"State": "MN",
"Year": 1987,
"variable": "Injuries",
"value":              9 
},
{
 "X": 4503,
"State": "MN",
"Year": 1988,
"variable": "Injuries",
"value":              2 
},
{
 "X": 4504,
"State": "MN",
"Year": 1989,
"variable": "Injuries",
"value":              3 
},
{
 "X": 4505,
"State": "MN",
"Year": 1990,
"variable": "Injuries",
"value":              4 
},
{
 "X": 4506,
"State": "MN",
"Year": 1991,
"variable": "Injuries",
"value":             16 
},
{
 "X": 4507,
"State": "MN",
"Year": 1992,
"variable": "Injuries",
"value":             53 
},
{
 "X": 4508,
"State": "MN",
"Year": 1993,
"variable": "Injuries",
"value":              6 
},
{
 "X": 4509,
"State": "MN",
"Year": 1994,
"variable": "Injuries",
"value":             14 
},
{
 "X": 4510,
"State": "MN",
"Year": 1995,
"variable": "Injuries",
"value":             27 
},
{
 "X": 4511,
"State": "MN",
"Year": 1996,
"variable": "Injuries",
"value":             29 
},
{
 "X": 4512,
"State": "MN",
"Year": 1997,
"variable": "Injuries",
"value":             29 
},
{
 "X": 4513,
"State": "MN",
"Year": 1998,
"variable": "Injuries",
"value":             85 
},
{
 "X": 4514,
"State": "MN",
"Year": 1999,
"variable": "Injuries",
"value":              9 
},
{
 "X": 4515,
"State": "MN",
"Year": 2000,
"variable": "Injuries",
"value":             20 
},
{
 "X": 4516,
"State": "MN",
"Year": 2001,
"variable": "Injuries",
"value":             41 
},
{
 "X": 4517,
"State": "MN",
"Year": 2002,
"variable": "Injuries",
"value":             11 
},
{
 "X": 4518,
"State": "MN",
"Year": 2003,
"variable": "Injuries",
"value":             13 
},
{
 "X": 4519,
"State": "MN",
"Year": 2004,
"variable": "Injuries",
"value":              5 
},
{
 "X": 4520,
"State": "MN",
"Year": 2005,
"variable": "Injuries",
"value":             20 
},
{
 "X": 4521,
"State": "MN",
"Year": 2006,
"variable": "Injuries",
"value":             44 
},
{
 "X": 4522,
"State": "MN",
"Year": 2007,
"variable": "Injuries",
"value":             58 
},
{
 "X": 4523,
"State": "MN",
"Year": 2008,
"variable": "Injuries",
"value":             38 
},
{
 "X": 4524,
"State": "MN",
"Year": 2009,
"variable": "Injuries",
"value":              3 
},
{
 "X": 4525,
"State": "MN",
"Year": 2010,
"variable": "Injuries",
"value":             49 
},
{
 "X": 4526,
"State": "MN",
"Year": 2011,
"variable": "Injuries",
"value":             59 
},
{
 "X": 4527,
"State": "MO",
"Year": 1950,
"variable": "Injuries",
"value":              8 
},
{
 "X": 4528,
"State": "MO",
"Year": 1951,
"variable": "Injuries",
"value":              2 
},
{
 "X": 4529,
"State": "MO",
"Year": 1952,
"variable": "Injuries",
"value":            117 
},
{
 "X": 4530,
"State": "MO",
"Year": 1953,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4531,
"State": "MO",
"Year": 1954,
"variable": "Injuries",
"value":              5 
},
{
 "X": 4532,
"State": "MO",
"Year": 1955,
"variable": "Injuries",
"value":             25 
},
{
 "X": 4533,
"State": "MO",
"Year": 1956,
"variable": "Injuries",
"value":             23 
},
{
 "X": 4534,
"State": "MO",
"Year": 1957,
"variable": "Injuries",
"value":            310 
},
{
 "X": 4535,
"State": "MO",
"Year": 1958,
"variable": "Injuries",
"value":             10 
},
{
 "X": 4536,
"State": "MO",
"Year": 1959,
"variable": "Injuries",
"value":            351 
},
{
 "X": 4537,
"State": "MO",
"Year": 1960,
"variable": "Injuries",
"value":              9 
},
{
 "X": 4538,
"State": "MO",
"Year": 1961,
"variable": "Injuries",
"value":             33 
},
{
 "X": 4539,
"State": "MO",
"Year": 1962,
"variable": "Injuries",
"value":              3 
},
{
 "X": 4540,
"State": "MO",
"Year": 1963,
"variable": "Injuries",
"value":              5 
},
{
 "X": 4541,
"State": "MO",
"Year": 1964,
"variable": "Injuries",
"value":             42 
},
{
 "X": 4542,
"State": "MO",
"Year": 1965,
"variable": "Injuries",
"value":             24 
},
{
 "X": 4543,
"State": "MO",
"Year": 1966,
"variable": "Injuries",
"value":             36 
},
{
 "X": 4544,
"State": "MO",
"Year": 1967,
"variable": "Injuries",
"value":            323 
},
{
 "X": 4545,
"State": "MO",
"Year": 1968,
"variable": "Injuries",
"value":              8 
},
{
 "X": 4546,
"State": "MO",
"Year": 1969,
"variable": "Injuries",
"value":             48 
},
{
 "X": 4547,
"State": "MO",
"Year": 1970,
"variable": "Injuries",
"value":             20 
},
{
 "X": 4548,
"State": "MO",
"Year": 1971,
"variable": "Injuries",
"value":            144 
},
{
 "X": 4549,
"State": "MO",
"Year": 1972,
"variable": "Injuries",
"value":             15 
},
{
 "X": 4550,
"State": "MO",
"Year": 1973,
"variable": "Injuries",
"value":             91 
},
{
 "X": 4551,
"State": "MO",
"Year": 1974,
"variable": "Injuries",
"value":              8 
},
{
 "X": 4552,
"State": "MO",
"Year": 1975,
"variable": "Injuries",
"value":             45 
},
{
 "X": 4553,
"State": "MO",
"Year": 1976,
"variable": "Injuries",
"value":             28 
},
{
 "X": 4554,
"State": "MO",
"Year": 1977,
"variable": "Injuries",
"value":             56 
},
{
 "X": 4555,
"State": "MO",
"Year": 1978,
"variable": "Injuries",
"value":             10 
},
{
 "X": 4556,
"State": "MO",
"Year": 1979,
"variable": "Injuries",
"value":             33 
},
{
 "X": 4557,
"State": "MO",
"Year": 1980,
"variable": "Injuries",
"value":             48 
},
{
 "X": 4558,
"State": "MO",
"Year": 1981,
"variable": "Injuries",
"value":             40 
},
{
 "X": 4559,
"State": "MO",
"Year": 1982,
"variable": "Injuries",
"value":             74 
},
{
 "X": 4560,
"State": "MO",
"Year": 1983,
"variable": "Injuries",
"value":             32 
},
{
 "X": 4561,
"State": "MO",
"Year": 1984,
"variable": "Injuries",
"value":             36 
},
{
 "X": 4562,
"State": "MO",
"Year": 1985,
"variable": "Injuries",
"value":             19 
},
{
 "X": 4563,
"State": "MO",
"Year": 1986,
"variable": "Injuries",
"value":             36 
},
{
 "X": 4564,
"State": "MO",
"Year": 1987,
"variable": "Injuries",
"value":              5 
},
{
 "X": 4565,
"State": "MO",
"Year": 1988,
"variable": "Injuries",
"value":             29 
},
{
 "X": 4566,
"State": "MO",
"Year": 1989,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4567,
"State": "MO",
"Year": 1990,
"variable": "Injuries",
"value":             45 
},
{
 "X": 4568,
"State": "MO",
"Year": 1991,
"variable": "Injuries",
"value":             70 
},
{
 "X": 4569,
"State": "MO",
"Year": 1992,
"variable": "Injuries",
"value":             19 
},
{
 "X": 4570,
"State": "MO",
"Year": 1993,
"variable": "Injuries",
"value":             18 
},
{
 "X": 4571,
"State": "MO",
"Year": 1994,
"variable": "Injuries",
"value":            103 
},
{
 "X": 4572,
"State": "MO",
"Year": 1995,
"variable": "Injuries",
"value":            631 
},
{
 "X": 4573,
"State": "MO",
"Year": 1996,
"variable": "Injuries",
"value":             90 
},
{
 "X": 4574,
"State": "MO",
"Year": 1997,
"variable": "Injuries",
"value":             56 
},
{
 "X": 4575,
"State": "MO",
"Year": 1998,
"variable": "Injuries",
"value":            333 
},
{
 "X": 4576,
"State": "MO",
"Year": 1999,
"variable": "Injuries",
"value":            424 
},
{
 "X": 4577,
"State": "MO",
"Year": 2000,
"variable": "Injuries",
"value":            281 
},
{
 "X": 4578,
"State": "MO",
"Year": 2001,
"variable": "Injuries",
"value":            269 
},
{
 "X": 4579,
"State": "MO",
"Year": 2002,
"variable": "Injuries",
"value":            405 
},
{
 "X": 4580,
"State": "MO",
"Year": 2003,
"variable": "Injuries",
"value":            328 
},
{
 "X": 4581,
"State": "MO",
"Year": 2004,
"variable": "Injuries",
"value":            152 
},
{
 "X": 4582,
"State": "MO",
"Year": 2005,
"variable": "Injuries",
"value":            177 
},
{
 "X": 4583,
"State": "MO",
"Year": 2006,
"variable": "Injuries",
"value":           1180 
},
{
 "X": 4584,
"State": "MO",
"Year": 2007,
"variable": "Injuries",
"value":            543 
},
{
 "X": 4585,
"State": "MO",
"Year": 2008,
"variable": "Injuries",
"value":            347 
},
{
 "X": 4586,
"State": "MO",
"Year": 2009,
"variable": "Injuries",
"value":             29 
},
{
 "X": 4587,
"State": "MO",
"Year": 2010,
"variable": "Injuries",
"value":             33 
},
{
 "X": 4588,
"State": "MO",
"Year": 2011,
"variable": "Injuries",
"value":           1313 
},
{
 "X": 4589,
"State": "MS",
"Year": 1950,
"variable": "Injuries",
"value":             23 
},
{
 "X": 4590,
"State": "MS",
"Year": 1951,
"variable": "Injuries",
"value":             17 
},
{
 "X": 4591,
"State": "MS",
"Year": 1952,
"variable": "Injuries",
"value":             28 
},
{
 "X": 4592,
"State": "MS",
"Year": 1953,
"variable": "Injuries",
"value":            310 
},
{
 "X": 4593,
"State": "MS",
"Year": 1954,
"variable": "Injuries",
"value":             63 
},
{
 "X": 4594,
"State": "MS",
"Year": 1955,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4595,
"State": "MS",
"Year": 1956,
"variable": "Injuries",
"value":             63 
},
{
 "X": 4596,
"State": "MS",
"Year": 1957,
"variable": "Injuries",
"value":            114 
},
{
 "X": 4597,
"State": "MS",
"Year": 1958,
"variable": "Injuries",
"value":             92 
},
{
 "X": 4598,
"State": "MS",
"Year": 1959,
"variable": "Injuries",
"value":              2 
},
{
 "X": 4599,
"State": "MS",
"Year": 1960,
"variable": "Injuries",
"value":              2 
},
{
 "X": 4600,
"State": "MS",
"Year": 1961,
"variable": "Injuries",
"value":             24 
},
{
 "X": 4601,
"State": "MS",
"Year": 1962,
"variable": "Injuries",
"value":             14 
},
{
 "X": 4602,
"State": "MS",
"Year": 1963,
"variable": "Injuries",
"value":             45 
},
{
 "X": 4603,
"State": "MS",
"Year": 1964,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4604,
"State": "MS",
"Year": 1965,
"variable": "Injuries",
"value":             17 
},
{
 "X": 4605,
"State": "MS",
"Year": 1966,
"variable": "Injuries",
"value":            532 
},
{
 "X": 4606,
"State": "MS",
"Year": 1967,
"variable": "Injuries",
"value":             39 
},
{
 "X": 4607,
"State": "MS",
"Year": 1968,
"variable": "Injuries",
"value":             47 
},
{
 "X": 4608,
"State": "MS",
"Year": 1969,
"variable": "Injuries",
"value":            261 
},
{
 "X": 4609,
"State": "MS",
"Year": 1970,
"variable": "Injuries",
"value":            110 
},
{
 "X": 4610,
"State": "MS",
"Year": 1971,
"variable": "Injuries",
"value":           1490 
},
{
 "X": 4611,
"State": "MS",
"Year": 1972,
"variable": "Injuries",
"value":             96 
},
{
 "X": 4612,
"State": "MS",
"Year": 1973,
"variable": "Injuries",
"value":            185 
},
{
 "X": 4613,
"State": "MS",
"Year": 1974,
"variable": "Injuries",
"value":             27 
},
{
 "X": 4614,
"State": "MS",
"Year": 1975,
"variable": "Injuries",
"value":            230 
},
{
 "X": 4615,
"State": "MS",
"Year": 1976,
"variable": "Injuries",
"value":            294 
},
{
 "X": 4616,
"State": "MS",
"Year": 1977,
"variable": "Injuries",
"value":             21 
},
{
 "X": 4617,
"State": "MS",
"Year": 1978,
"variable": "Injuries",
"value":             58 
},
{
 "X": 4618,
"State": "MS",
"Year": 1979,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4619,
"State": "MS",
"Year": 1980,
"variable": "Injuries",
"value":             54 
},
{
 "X": 4620,
"State": "MS",
"Year": 1981,
"variable": "Injuries",
"value":              5 
},
{
 "X": 4621,
"State": "MS",
"Year": 1982,
"variable": "Injuries",
"value":            106 
},
{
 "X": 4622,
"State": "MS",
"Year": 1983,
"variable": "Injuries",
"value":             32 
},
{
 "X": 4623,
"State": "MS",
"Year": 1984,
"variable": "Injuries",
"value":            108 
},
{
 "X": 4624,
"State": "MS",
"Year": 1985,
"variable": "Injuries",
"value":             11 
},
{
 "X": 4625,
"State": "MS",
"Year": 1986,
"variable": "Injuries",
"value":             18 
},
{
 "X": 4626,
"State": "MS",
"Year": 1987,
"variable": "Injuries",
"value":            369 
},
{
 "X": 4627,
"State": "MS",
"Year": 1988,
"variable": "Injuries",
"value":             32 
},
{
 "X": 4628,
"State": "MS",
"Year": 1989,
"variable": "Injuries",
"value":             13 
},
{
 "X": 4629,
"State": "MS",
"Year": 1990,
"variable": "Injuries",
"value":             71 
},
{
 "X": 4630,
"State": "MS",
"Year": 1991,
"variable": "Injuries",
"value":             30 
},
{
 "X": 4631,
"State": "MS",
"Year": 1992,
"variable": "Injuries",
"value":            357 
},
{
 "X": 4632,
"State": "MS",
"Year": 1993,
"variable": "Injuries",
"value":              3 
},
{
 "X": 4633,
"State": "MS",
"Year": 1994,
"variable": "Injuries",
"value":             31 
},
{
 "X": 4634,
"State": "MS",
"Year": 1995,
"variable": "Injuries",
"value":             13 
},
{
 "X": 4635,
"State": "MS",
"Year": 1996,
"variable": "Injuries",
"value":             45 
},
{
 "X": 4636,
"State": "MS",
"Year": 1997,
"variable": "Injuries",
"value":             37 
},
{
 "X": 4637,
"State": "MS",
"Year": 1998,
"variable": "Injuries",
"value":             54 
},
{
 "X": 4638,
"State": "MS",
"Year": 1999,
"variable": "Injuries",
"value":             49 
},
{
 "X": 4639,
"State": "MS",
"Year": 2000,
"variable": "Injuries",
"value":             34 
},
{
 "X": 4640,
"State": "MS",
"Year": 2001,
"variable": "Injuries",
"value":            228 
},
{
 "X": 4641,
"State": "MS",
"Year": 2002,
"variable": "Injuries",
"value":             56 
},
{
 "X": 4642,
"State": "MS",
"Year": 2003,
"variable": "Injuries",
"value":             25 
},
{
 "X": 4643,
"State": "MS",
"Year": 2004,
"variable": "Injuries",
"value":             18 
},
{
 "X": 4644,
"State": "MS",
"Year": 2005,
"variable": "Injuries",
"value":            135 
},
{
 "X": 4645,
"State": "MS",
"Year": 2006,
"variable": "Injuries",
"value":             23 
},
{
 "X": 4646,
"State": "MS",
"Year": 2007,
"variable": "Injuries",
"value":             21 
},
{
 "X": 4647,
"State": "MS",
"Year": 2008,
"variable": "Injuries",
"value":             58 
},
{
 "X": 4648,
"State": "MS",
"Year": 2009,
"variable": "Injuries",
"value":             42 
},
{
 "X": 4649,
"State": "MS",
"Year": 2010,
"variable": "Injuries",
"value":            173 
},
{
 "X": 4650,
"State": "MS",
"Year": 2011,
"variable": "Injuries",
"value":            219 
},
{
 "X": 4651,
"State": "MT",
"Year": 1950,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4652,
"State": "MT",
"Year": 1951,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4653,
"State": "MT",
"Year": 1952,
"variable": "Injuries",
"value":              2 
},
{
 "X": 4654,
"State": "MT",
"Year": 1953,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4655,
"State": "MT",
"Year": 1954,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4656,
"State": "MT",
"Year": 1955,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4657,
"State": "MT",
"Year": 1956,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4658,
"State": "MT",
"Year": 1957,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4659,
"State": "MT",
"Year": 1958,
"variable": "Injuries",
"value":              3 
},
{
 "X": 4660,
"State": "MT",
"Year": 1959,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4661,
"State": "MT",
"Year": 1960,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4662,
"State": "MT",
"Year": 1961,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4663,
"State": "MT",
"Year": 1962,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4664,
"State": "MT",
"Year": 1963,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4665,
"State": "MT",
"Year": 1964,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4666,
"State": "MT",
"Year": 1965,
"variable": "Injuries",
"value":              6 
},
{
 "X": 4667,
"State": "MT",
"Year": 1966,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4668,
"State": "MT",
"Year": 1967,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4669,
"State": "MT",
"Year": 1968,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4670,
"State": "MT",
"Year": 1969,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4671,
"State": "MT",
"Year": 1970,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4672,
"State": "MT",
"Year": 1971,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4673,
"State": "MT",
"Year": 1972,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4674,
"State": "MT",
"Year": 1973,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4675,
"State": "MT",
"Year": 1974,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4676,
"State": "MT",
"Year": 1975,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4677,
"State": "MT",
"Year": 1976,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4678,
"State": "MT",
"Year": 1977,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4679,
"State": "MT",
"Year": 1978,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4680,
"State": "MT",
"Year": 1979,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4681,
"State": "MT",
"Year": 1980,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4682,
"State": "MT",
"Year": 1981,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4683,
"State": "MT",
"Year": 1982,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4684,
"State": "MT",
"Year": 1983,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4685,
"State": "MT",
"Year": 1984,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4686,
"State": "MT",
"Year": 1985,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4687,
"State": "MT",
"Year": 1986,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4688,
"State": "MT",
"Year": 1987,
"variable": "Injuries",
"value":              2 
},
{
 "X": 4689,
"State": "MT",
"Year": 1988,
"variable": "Injuries",
"value":              2 
},
{
 "X": 4690,
"State": "MT",
"Year": 1989,
"variable": "Injuries",
"value":              5 
},
{
 "X": 4691,
"State": "MT",
"Year": 1990,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4692,
"State": "MT",
"Year": 1991,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4693,
"State": "MT",
"Year": 1992,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4694,
"State": "MT",
"Year": 1993,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4695,
"State": "MT",
"Year": 1994,
"variable": "Injuries",
"value":              2 
},
{
 "X": 4696,
"State": "MT",
"Year": 1995,
"variable": "Injuries",
"value":              4 
},
{
 "X": 4697,
"State": "MT",
"Year": 1996,
"variable": "Injuries",
"value":              3 
},
{
 "X": 4698,
"State": "MT",
"Year": 1997,
"variable": "Injuries",
"value":              2 
},
{
 "X": 4699,
"State": "MT",
"Year": 1998,
"variable": "Injuries",
"value":              8 
},
{
 "X": 4700,
"State": "MT",
"Year": 1999,
"variable": "Injuries",
"value":              5 
},
{
 "X": 4701,
"State": "MT",
"Year": 2000,
"variable": "Injuries",
"value":             44 
},
{
 "X": 4702,
"State": "MT",
"Year": 2001,
"variable": "Injuries",
"value":             13 
},
{
 "X": 4703,
"State": "MT",
"Year": 2002,
"variable": "Injuries",
"value":             11 
},
{
 "X": 4704,
"State": "MT",
"Year": 2003,
"variable": "Injuries",
"value":             15 
},
{
 "X": 4705,
"State": "MT",
"Year": 2004,
"variable": "Injuries",
"value":             14 
},
{
 "X": 4706,
"State": "MT",
"Year": 2005,
"variable": "Injuries",
"value":              7 
},
{
 "X": 4707,
"State": "MT",
"Year": 2006,
"variable": "Injuries",
"value":              9 
},
{
 "X": 4708,
"State": "MT",
"Year": 2007,
"variable": "Injuries",
"value":              7 
},
{
 "X": 4709,
"State": "MT",
"Year": 2008,
"variable": "Injuries",
"value":              3 
},
{
 "X": 4710,
"State": "MT",
"Year": 2009,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4711,
"State": "MT",
"Year": 2010,
"variable": "Injuries",
"value":              3 
},
{
 "X": 4712,
"State": "MT",
"Year": 2011,
"variable": "Injuries",
"value":              5 
},
{
 "X": 4713,
"State": "NC",
"Year": 1950,
"variable": "Injuries",
"value":              8 
},
{
 "X": 4714,
"State": "NC",
"Year": 1951,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4715,
"State": "NC",
"Year": 1952,
"variable": "Injuries",
"value":              9 
},
{
 "X": 4716,
"State": "NC",
"Year": 1953,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4717,
"State": "NC",
"Year": 1954,
"variable": "Injuries",
"value":              5 
},
{
 "X": 4718,
"State": "NC",
"Year": 1955,
"variable": "Injuries",
"value":              2 
},
{
 "X": 4719,
"State": "NC",
"Year": 1956,
"variable": "Injuries",
"value":              2 
},
{
 "X": 4720,
"State": "NC",
"Year": 1957,
"variable": "Injuries",
"value":            110 
},
{
 "X": 4721,
"State": "NC",
"Year": 1958,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4722,
"State": "NC",
"Year": 1959,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4723,
"State": "NC",
"Year": 1960,
"variable": "Injuries",
"value":              9 
},
{
 "X": 4724,
"State": "NC",
"Year": 1961,
"variable": "Injuries",
"value":              3 
},
{
 "X": 4725,
"State": "NC",
"Year": 1962,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4726,
"State": "NC",
"Year": 1963,
"variable": "Injuries",
"value":              4 
},
{
 "X": 4727,
"State": "NC",
"Year": 1964,
"variable": "Injuries",
"value":             19 
},
{
 "X": 4728,
"State": "NC",
"Year": 1965,
"variable": "Injuries",
"value":             90 
},
{
 "X": 4729,
"State": "NC",
"Year": 1966,
"variable": "Injuries",
"value":              9 
},
{
 "X": 4730,
"State": "NC",
"Year": 1967,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4731,
"State": "NC",
"Year": 1968,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4732,
"State": "NC",
"Year": 1969,
"variable": "Injuries",
"value":              2 
},
{
 "X": 4733,
"State": "NC",
"Year": 1970,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4734,
"State": "NC",
"Year": 1971,
"variable": "Injuries",
"value":             60 
},
{
 "X": 4735,
"State": "NC",
"Year": 1972,
"variable": "Injuries",
"value":              4 
},
{
 "X": 4736,
"State": "NC",
"Year": 1973,
"variable": "Injuries",
"value":             20 
},
{
 "X": 4737,
"State": "NC",
"Year": 1974,
"variable": "Injuries",
"value":             52 
},
{
 "X": 4738,
"State": "NC",
"Year": 1975,
"variable": "Injuries",
"value":             32 
},
{
 "X": 4739,
"State": "NC",
"Year": 1976,
"variable": "Injuries",
"value":             17 
},
{
 "X": 4740,
"State": "NC",
"Year": 1977,
"variable": "Injuries",
"value":             12 
},
{
 "X": 4741,
"State": "NC",
"Year": 1978,
"variable": "Injuries",
"value":             11 
},
{
 "X": 4742,
"State": "NC",
"Year": 1979,
"variable": "Injuries",
"value":             15 
},
{
 "X": 4743,
"State": "NC",
"Year": 1980,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4744,
"State": "NC",
"Year": 1981,
"variable": "Injuries",
"value":              4 
},
{
 "X": 4745,
"State": "NC",
"Year": 1982,
"variable": "Injuries",
"value":              4 
},
{
 "X": 4746,
"State": "NC",
"Year": 1983,
"variable": "Injuries",
"value":             18 
},
{
 "X": 4747,
"State": "NC",
"Year": 1984,
"variable": "Injuries",
"value":            816 
},
{
 "X": 4748,
"State": "NC",
"Year": 1985,
"variable": "Injuries",
"value":             12 
},
{
 "X": 4749,
"State": "NC",
"Year": 1986,
"variable": "Injuries",
"value":             27 
},
{
 "X": 4750,
"State": "NC",
"Year": 1987,
"variable": "Injuries",
"value":             16 
},
{
 "X": 4751,
"State": "NC",
"Year": 1988,
"variable": "Injuries",
"value":            176 
},
{
 "X": 4752,
"State": "NC",
"Year": 1989,
"variable": "Injuries",
"value":            137 
},
{
 "X": 4753,
"State": "NC",
"Year": 1990,
"variable": "Injuries",
"value":             12 
},
{
 "X": 4754,
"State": "NC",
"Year": 1991,
"variable": "Injuries",
"value":             44 
},
{
 "X": 4755,
"State": "NC",
"Year": 1992,
"variable": "Injuries",
"value":             92 
},
{
 "X": 4756,
"State": "NC",
"Year": 1993,
"variable": "Injuries",
"value":             24 
},
{
 "X": 4757,
"State": "NC",
"Year": 1994,
"variable": "Injuries",
"value":              8 
},
{
 "X": 4758,
"State": "NC",
"Year": 1995,
"variable": "Injuries",
"value":            148 
},
{
 "X": 4759,
"State": "NC",
"Year": 1996,
"variable": "Injuries",
"value":            263 
},
{
 "X": 4760,
"State": "NC",
"Year": 1997,
"variable": "Injuries",
"value":             45 
},
{
 "X": 4761,
"State": "NC",
"Year": 1998,
"variable": "Injuries",
"value":             93 
},
{
 "X": 4762,
"State": "NC",
"Year": 1999,
"variable": "Injuries",
"value":             90 
},
{
 "X": 4763,
"State": "NC",
"Year": 2000,
"variable": "Injuries",
"value":             44 
},
{
 "X": 4764,
"State": "NC",
"Year": 2001,
"variable": "Injuries",
"value":             21 
},
{
 "X": 4765,
"State": "NC",
"Year": 2002,
"variable": "Injuries",
"value":             29 
},
{
 "X": 4766,
"State": "NC",
"Year": 2003,
"variable": "Injuries",
"value":             39 
},
{
 "X": 4767,
"State": "NC",
"Year": 2004,
"variable": "Injuries",
"value":             59 
},
{
 "X": 4768,
"State": "NC",
"Year": 2005,
"variable": "Injuries",
"value":             30 
},
{
 "X": 4769,
"State": "NC",
"Year": 2006,
"variable": "Injuries",
"value":             48 
},
{
 "X": 4770,
"State": "NC",
"Year": 2007,
"variable": "Injuries",
"value":             14 
},
{
 "X": 4771,
"State": "NC",
"Year": 2008,
"variable": "Injuries",
"value":             47 
},
{
 "X": 4772,
"State": "NC",
"Year": 2009,
"variable": "Injuries",
"value":             28 
},
{
 "X": 4773,
"State": "NC",
"Year": 2010,
"variable": "Injuries",
"value":             34 
},
{
 "X": 4774,
"State": "NC",
"Year": 2011,
"variable": "Injuries",
"value":            494 
},
{
 "X": 4775,
"State": "ND",
"Year": 1950,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4776,
"State": "ND",
"Year": 1951,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4777,
"State": "ND",
"Year": 1952,
"variable": "Injuries",
"value":             27 
},
{
 "X": 4778,
"State": "ND",
"Year": 1953,
"variable": "Injuries",
"value":             20 
},
{
 "X": 4779,
"State": "ND",
"Year": 1954,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4780,
"State": "ND",
"Year": 1955,
"variable": "Injuries",
"value":             19 
},
{
 "X": 4781,
"State": "ND",
"Year": 1956,
"variable": "Injuries",
"value":              9 
},
{
 "X": 4782,
"State": "ND",
"Year": 1957,
"variable": "Injuries",
"value":            103 
},
{
 "X": 4783,
"State": "ND",
"Year": 1958,
"variable": "Injuries",
"value":              4 
},
{
 "X": 4784,
"State": "ND",
"Year": 1959,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4785,
"State": "ND",
"Year": 1960,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4786,
"State": "ND",
"Year": 1961,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4787,
"State": "ND",
"Year": 1962,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4788,
"State": "ND",
"Year": 1963,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4789,
"State": "ND",
"Year": 1964,
"variable": "Injuries",
"value":             11 
},
{
 "X": 4790,
"State": "ND",
"Year": 1965,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4791,
"State": "ND",
"Year": 1966,
"variable": "Injuries",
"value":              2 
},
{
 "X": 4792,
"State": "ND",
"Year": 1967,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4793,
"State": "ND",
"Year": 1968,
"variable": "Injuries",
"value":              3 
},
{
 "X": 4794,
"State": "ND",
"Year": 1969,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4795,
"State": "ND",
"Year": 1970,
"variable": "Injuries",
"value":              9 
},
{
 "X": 4796,
"State": "ND",
"Year": 1971,
"variable": "Injuries",
"value":              2 
},
{
 "X": 4797,
"State": "ND",
"Year": 1972,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4798,
"State": "ND",
"Year": 1973,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4799,
"State": "ND",
"Year": 1974,
"variable": "Injuries",
"value":             11 
},
{
 "X": 4800,
"State": "ND",
"Year": 1975,
"variable": "Injuries",
"value":              9 
},
{
 "X": 4801,
"State": "ND",
"Year": 1976,
"variable": "Injuries",
"value":              5 
},
{
 "X": 4802,
"State": "ND",
"Year": 1977,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4803,
"State": "ND",
"Year": 1978,
"variable": "Injuries",
"value":             35 
},
{
 "X": 4804,
"State": "ND",
"Year": 1979,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4805,
"State": "ND",
"Year": 1980,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4806,
"State": "ND",
"Year": 1981,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4807,
"State": "ND",
"Year": 1982,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4808,
"State": "ND",
"Year": 1983,
"variable": "Injuries",
"value":              2 
},
{
 "X": 4809,
"State": "ND",
"Year": 1984,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4810,
"State": "ND",
"Year": 1985,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4811,
"State": "ND",
"Year": 1986,
"variable": "Injuries",
"value":             14 
},
{
 "X": 4812,
"State": "ND",
"Year": 1987,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4813,
"State": "ND",
"Year": 1988,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4814,
"State": "ND",
"Year": 1989,
"variable": "Injuries",
"value":              3 
},
{
 "X": 4815,
"State": "ND",
"Year": 1990,
"variable": "Injuries",
"value":              5 
},
{
 "X": 4816,
"State": "ND",
"Year": 1991,
"variable": "Injuries",
"value":              2 
},
{
 "X": 4817,
"State": "ND",
"Year": 1992,
"variable": "Injuries",
"value":              6 
},
{
 "X": 4818,
"State": "ND",
"Year": 1993,
"variable": "Injuries",
"value":              3 
},
{
 "X": 4819,
"State": "ND",
"Year": 1994,
"variable": "Injuries",
"value":             10 
},
{
 "X": 4820,
"State": "ND",
"Year": 1995,
"variable": "Injuries",
"value":             21 
},
{
 "X": 4821,
"State": "ND",
"Year": 1996,
"variable": "Injuries",
"value":              6 
},
{
 "X": 4822,
"State": "ND",
"Year": 1997,
"variable": "Injuries",
"value":            122 
},
{
 "X": 4823,
"State": "ND",
"Year": 1998,
"variable": "Injuries",
"value":              6 
},
{
 "X": 4824,
"State": "ND",
"Year": 1999,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4825,
"State": "ND",
"Year": 2000,
"variable": "Injuries",
"value":             34 
},
{
 "X": 4826,
"State": "ND",
"Year": 2001,
"variable": "Injuries",
"value":             18 
},
{
 "X": 4827,
"State": "ND",
"Year": 2002,
"variable": "Injuries",
"value":              7 
},
{
 "X": 4828,
"State": "ND",
"Year": 2003,
"variable": "Injuries",
"value":             13 
},
{
 "X": 4829,
"State": "ND",
"Year": 2004,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4830,
"State": "ND",
"Year": 2005,
"variable": "Injuries",
"value":              7 
},
{
 "X": 4831,
"State": "ND",
"Year": 2006,
"variable": "Injuries",
"value":              6 
},
{
 "X": 4832,
"State": "ND",
"Year": 2007,
"variable": "Injuries",
"value":             23 
},
{
 "X": 4833,
"State": "ND",
"Year": 2008,
"variable": "Injuries",
"value":              5 
},
{
 "X": 4834,
"State": "ND",
"Year": 2009,
"variable": "Injuries",
"value":              2 
},
{
 "X": 4835,
"State": "ND",
"Year": 2010,
"variable": "Injuries",
"value":              6 
},
{
 "X": 4836,
"State": "ND",
"Year": 2011,
"variable": "Injuries",
"value":              8 
},
{
 "X": 4837,
"State": "NE",
"Year": 1950,
"variable": "Injuries",
"value":            135 
},
{
 "X": 4838,
"State": "NE",
"Year": 1951,
"variable": "Injuries",
"value":              8 
},
{
 "X": 4839,
"State": "NE",
"Year": 1952,
"variable": "Injuries",
"value":             21 
},
{
 "X": 4840,
"State": "NE",
"Year": 1953,
"variable": "Injuries",
"value":            103 
},
{
 "X": 4841,
"State": "NE",
"Year": 1954,
"variable": "Injuries",
"value":             32 
},
{
 "X": 4842,
"State": "NE",
"Year": 1955,
"variable": "Injuries",
"value":             42 
},
{
 "X": 4843,
"State": "NE",
"Year": 1956,
"variable": "Injuries",
"value":              8 
},
{
 "X": 4844,
"State": "NE",
"Year": 1957,
"variable": "Injuries",
"value":              9 
},
{
 "X": 4845,
"State": "NE",
"Year": 1958,
"variable": "Injuries",
"value":              4 
},
{
 "X": 4846,
"State": "NE",
"Year": 1959,
"variable": "Injuries",
"value":              5 
},
{
 "X": 4847,
"State": "NE",
"Year": 1960,
"variable": "Injuries",
"value":             11 
},
{
 "X": 4848,
"State": "NE",
"Year": 1961,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4849,
"State": "NE",
"Year": 1962,
"variable": "Injuries",
"value":             27 
},
{
 "X": 4850,
"State": "NE",
"Year": 1963,
"variable": "Injuries",
"value":              8 
},
{
 "X": 4851,
"State": "NE",
"Year": 1964,
"variable": "Injuries",
"value":             68 
},
{
 "X": 4852,
"State": "NE",
"Year": 1965,
"variable": "Injuries",
"value":             54 
},
{
 "X": 4853,
"State": "NE",
"Year": 1966,
"variable": "Injuries",
"value":              2 
},
{
 "X": 4854,
"State": "NE",
"Year": 1967,
"variable": "Injuries",
"value":              4 
},
{
 "X": 4855,
"State": "NE",
"Year": 1968,
"variable": "Injuries",
"value":              3 
},
{
 "X": 4856,
"State": "NE",
"Year": 1969,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4857,
"State": "NE",
"Year": 1970,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4858,
"State": "NE",
"Year": 1971,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4859,
"State": "NE",
"Year": 1972,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4860,
"State": "NE",
"Year": 1973,
"variable": "Injuries",
"value":             13 
},
{
 "X": 4861,
"State": "NE",
"Year": 1974,
"variable": "Injuries",
"value":             20 
},
{
 "X": 4862,
"State": "NE",
"Year": 1975,
"variable": "Injuries",
"value":            141 
},
{
 "X": 4863,
"State": "NE",
"Year": 1976,
"variable": "Injuries",
"value":             23 
},
{
 "X": 4864,
"State": "NE",
"Year": 1977,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4865,
"State": "NE",
"Year": 1978,
"variable": "Injuries",
"value":              9 
},
{
 "X": 4866,
"State": "NE",
"Year": 1979,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4867,
"State": "NE",
"Year": 1980,
"variable": "Injuries",
"value":            204 
},
{
 "X": 4868,
"State": "NE",
"Year": 1981,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4869,
"State": "NE",
"Year": 1982,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4870,
"State": "NE",
"Year": 1983,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4871,
"State": "NE",
"Year": 1984,
"variable": "Injuries",
"value":             34 
},
{
 "X": 4872,
"State": "NE",
"Year": 1985,
"variable": "Injuries",
"value":             12 
},
{
 "X": 4873,
"State": "NE",
"Year": 1986,
"variable": "Injuries",
"value":             32 
},
{
 "X": 4874,
"State": "NE",
"Year": 1987,
"variable": "Injuries",
"value":             17 
},
{
 "X": 4875,
"State": "NE",
"Year": 1988,
"variable": "Injuries",
"value":             12 
},
{
 "X": 4876,
"State": "NE",
"Year": 1989,
"variable": "Injuries",
"value":             14 
},
{
 "X": 4877,
"State": "NE",
"Year": 1990,
"variable": "Injuries",
"value":             10 
},
{
 "X": 4878,
"State": "NE",
"Year": 1991,
"variable": "Injuries",
"value":              7 
},
{
 "X": 4879,
"State": "NE",
"Year": 1992,
"variable": "Injuries",
"value":              7 
},
{
 "X": 4880,
"State": "NE",
"Year": 1993,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4881,
"State": "NE",
"Year": 1994,
"variable": "Injuries",
"value":             14 
},
{
 "X": 4882,
"State": "NE",
"Year": 1995,
"variable": "Injuries",
"value":              4 
},
{
 "X": 4883,
"State": "NE",
"Year": 1996,
"variable": "Injuries",
"value":             28 
},
{
 "X": 4884,
"State": "NE",
"Year": 1997,
"variable": "Injuries",
"value":              9 
},
{
 "X": 4885,
"State": "NE",
"Year": 1998,
"variable": "Injuries",
"value":             42 
},
{
 "X": 4886,
"State": "NE",
"Year": 1999,
"variable": "Injuries",
"value":             52 
},
{
 "X": 4887,
"State": "NE",
"Year": 2000,
"variable": "Injuries",
"value":              4 
},
{
 "X": 4888,
"State": "NE",
"Year": 2001,
"variable": "Injuries",
"value":             28 
},
{
 "X": 4889,
"State": "NE",
"Year": 2002,
"variable": "Injuries",
"value":             37 
},
{
 "X": 4890,
"State": "NE",
"Year": 2003,
"variable": "Injuries",
"value":             12 
},
{
 "X": 4891,
"State": "NE",
"Year": 2004,
"variable": "Injuries",
"value":             68 
},
{
 "X": 4892,
"State": "NE",
"Year": 2005,
"variable": "Injuries",
"value":             10 
},
{
 "X": 4893,
"State": "NE",
"Year": 2006,
"variable": "Injuries",
"value":             15 
},
{
 "X": 4894,
"State": "NE",
"Year": 2007,
"variable": "Injuries",
"value":             15 
},
{
 "X": 4895,
"State": "NE",
"Year": 2008,
"variable": "Injuries",
"value":             10 
},
{
 "X": 4896,
"State": "NE",
"Year": 2009,
"variable": "Injuries",
"value":              9 
},
{
 "X": 4897,
"State": "NE",
"Year": 2010,
"variable": "Injuries",
"value":              4 
},
{
 "X": 4898,
"State": "NE",
"Year": 2011,
"variable": "Injuries",
"value":              7 
},
{
 "X": 4899,
"State": "NH",
"Year": 1950,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4900,
"State": "NH",
"Year": 1951,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4901,
"State": "NH",
"Year": 1952,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4902,
"State": "NH",
"Year": 1953,
"variable": "Injuries",
"value":              5 
},
{
 "X": 4903,
"State": "NH",
"Year": 1954,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4904,
"State": "NH",
"Year": 1955,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4905,
"State": "NH",
"Year": 1956,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4906,
"State": "NH",
"Year": 1957,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4907,
"State": "NH",
"Year": 1958,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4908,
"State": "NH",
"Year": 1959,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4909,
"State": "NH",
"Year": 1960,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4910,
"State": "NH",
"Year": 1961,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4911,
"State": "NH",
"Year": 1962,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4912,
"State": "NH",
"Year": 1963,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4913,
"State": "NH",
"Year": 1964,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4914,
"State": "NH",
"Year": 1965,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4915,
"State": "NH",
"Year": 1966,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4916,
"State": "NH",
"Year": 1967,
"variable": "Injuries",
"value":              5 
},
{
 "X": 4917,
"State": "NH",
"Year": 1968,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4918,
"State": "NH",
"Year": 1969,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4919,
"State": "NH",
"Year": 1970,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4920,
"State": "NH",
"Year": 1971,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4921,
"State": "NH",
"Year": 1972,
"variable": "Injuries",
"value":              7 
},
{
 "X": 4922,
"State": "NH",
"Year": 1973,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4923,
"State": "NH",
"Year": 1974,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4924,
"State": "NH",
"Year": 1975,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4925,
"State": "NH",
"Year": 1976,
"variable": "Injuries",
"value":              5 
},
{
 "X": 4926,
"State": "NH",
"Year": 1977,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4927,
"State": "NH",
"Year": 1978,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4928,
"State": "NH",
"Year": 1979,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4929,
"State": "NH",
"Year": 1980,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4930,
"State": "NH",
"Year": 1981,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4931,
"State": "NH",
"Year": 1982,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4932,
"State": "NH",
"Year": 1983,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4933,
"State": "NH",
"Year": 1984,
"variable": "Injuries",
"value":              2 
},
{
 "X": 4934,
"State": "NH",
"Year": 1985,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4935,
"State": "NH",
"Year": 1986,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4936,
"State": "NH",
"Year": 1987,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4937,
"State": "NH",
"Year": 1988,
"variable": "Injuries",
"value":              2 
},
{
 "X": 4938,
"State": "NH",
"Year": 1989,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4939,
"State": "NH",
"Year": 1990,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4940,
"State": "NH",
"Year": 1991,
"variable": "Injuries",
"value":             12 
},
{
 "X": 4941,
"State": "NH",
"Year": 1992,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4942,
"State": "NH",
"Year": 1993,
"variable": "Injuries",
"value":              4 
},
{
 "X": 4943,
"State": "NH",
"Year": 1994,
"variable": "Injuries",
"value":              6 
},
{
 "X": 4944,
"State": "NH",
"Year": 1995,
"variable": "Injuries",
"value":              4 
},
{
 "X": 4945,
"State": "NH",
"Year": 1996,
"variable": "Injuries",
"value":              7 
},
{
 "X": 4946,
"State": "NH",
"Year": 1997,
"variable": "Injuries",
"value":              4 
},
{
 "X": 4947,
"State": "NH",
"Year": 1998,
"variable": "Injuries",
"value":             23 
},
{
 "X": 4948,
"State": "NH",
"Year": 1999,
"variable": "Injuries",
"value":             17 
},
{
 "X": 4949,
"State": "NH",
"Year": 2000,
"variable": "Injuries",
"value":              6 
},
{
 "X": 4950,
"State": "NH",
"Year": 2001,
"variable": "Injuries",
"value":              2 
},
{
 "X": 4951,
"State": "NH",
"Year": 2002,
"variable": "Injuries",
"value":              7 
},
{
 "X": 4952,
"State": "NH",
"Year": 2003,
"variable": "Injuries",
"value":             29 
},
{
 "X": 4953,
"State": "NH",
"Year": 2004,
"variable": "Injuries",
"value":             11 
},
{
 "X": 4954,
"State": "NH",
"Year": 2005,
"variable": "Injuries",
"value":              9 
},
{
 "X": 4955,
"State": "NH",
"Year": 2006,
"variable": "Injuries",
"value":              9 
},
{
 "X": 4956,
"State": "NH",
"Year": 2007,
"variable": "Injuries",
"value":              3 
},
{
 "X": 4957,
"State": "NH",
"Year": 2008,
"variable": "Injuries",
"value":              5 
},
{
 "X": 4958,
"State": "NH",
"Year": 2009,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4959,
"State": "NH",
"Year": 2010,
"variable": "Injuries",
"value":              6 
},
{
 "X": 4960,
"State": "NH",
"Year": 2011,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4961,
"State": "NJ",
"Year": 1950,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4962,
"State": "NJ",
"Year": 1951,
"variable": "Injuries",
"value":              2 
},
{
 "X": 4963,
"State": "NJ",
"Year": 1952,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4964,
"State": "NJ",
"Year": 1953,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4965,
"State": "NJ",
"Year": 1954,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4966,
"State": "NJ",
"Year": 1955,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4967,
"State": "NJ",
"Year": 1956,
"variable": "Injuries",
"value":              8 
},
{
 "X": 4968,
"State": "NJ",
"Year": 1957,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4969,
"State": "NJ",
"Year": 1958,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4970,
"State": "NJ",
"Year": 1959,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4971,
"State": "NJ",
"Year": 1960,
"variable": "Injuries",
"value":              6 
},
{
 "X": 4972,
"State": "NJ",
"Year": 1961,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4973,
"State": "NJ",
"Year": 1962,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4974,
"State": "NJ",
"Year": 1963,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4975,
"State": "NJ",
"Year": 1964,
"variable": "Injuries",
"value":             10 
},
{
 "X": 4976,
"State": "NJ",
"Year": 1965,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4977,
"State": "NJ",
"Year": 1966,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4978,
"State": "NJ",
"Year": 1967,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4979,
"State": "NJ",
"Year": 1968,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4980,
"State": "NJ",
"Year": 1969,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4981,
"State": "NJ",
"Year": 1970,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4982,
"State": "NJ",
"Year": 1971,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4983,
"State": "NJ",
"Year": 1972,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4984,
"State": "NJ",
"Year": 1973,
"variable": "Injuries",
"value":             12 
},
{
 "X": 4985,
"State": "NJ",
"Year": 1974,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4986,
"State": "NJ",
"Year": 1975,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4987,
"State": "NJ",
"Year": 1976,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4988,
"State": "NJ",
"Year": 1977,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4989,
"State": "NJ",
"Year": 1978,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4990,
"State": "NJ",
"Year": 1979,
"variable": "Injuries",
"value":              1 
},
{
 "X": 4991,
"State": "NJ",
"Year": 1980,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4992,
"State": "NJ",
"Year": 1981,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4993,
"State": "NJ",
"Year": 1982,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4994,
"State": "NJ",
"Year": 1983,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4995,
"State": "NJ",
"Year": 1984,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4996,
"State": "NJ",
"Year": 1985,
"variable": "Injuries",
"value":              8 
},
{
 "X": 4997,
"State": "NJ",
"Year": 1986,
"variable": "Injuries",
"value":              0 
},
{
 "X": 4998,
"State": "NJ",
"Year": 1987,
"variable": "Injuries",
"value":              3 
},
{
 "X": 4999,
"State": "NJ",
"Year": 1988,
"variable": "Injuries",
"value":             15 
},
{
 "X": 5000,
"State": "NJ",
"Year": 1989,
"variable": "Injuries",
"value":             14 
},
{
 "X": 5001,
"State": "NJ",
"Year": 1990,
"variable": "Injuries",
"value":             39 
},
{
 "X": 5002,
"State": "NJ",
"Year": 1991,
"variable": "Injuries",
"value":              2 
},
{
 "X": 5003,
"State": "NJ",
"Year": 1992,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5004,
"State": "NJ",
"Year": 1993,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5005,
"State": "NJ",
"Year": 1994,
"variable": "Injuries",
"value":             62 
},
{
 "X": 5006,
"State": "NJ",
"Year": 1995,
"variable": "Injuries",
"value":             30 
},
{
 "X": 5007,
"State": "NJ",
"Year": 1996,
"variable": "Injuries",
"value":             15 
},
{
 "X": 5008,
"State": "NJ",
"Year": 1997,
"variable": "Injuries",
"value":             68 
},
{
 "X": 5009,
"State": "NJ",
"Year": 1998,
"variable": "Injuries",
"value":            124 
},
{
 "X": 5010,
"State": "NJ",
"Year": 1999,
"variable": "Injuries",
"value":            390 
},
{
 "X": 5011,
"State": "NJ",
"Year": 2000,
"variable": "Injuries",
"value":             36 
},
{
 "X": 5012,
"State": "NJ",
"Year": 2001,
"variable": "Injuries",
"value":             37 
},
{
 "X": 5013,
"State": "NJ",
"Year": 2002,
"variable": "Injuries",
"value":             25 
},
{
 "X": 5014,
"State": "NJ",
"Year": 2003,
"variable": "Injuries",
"value":             36 
},
{
 "X": 5015,
"State": "NJ",
"Year": 2004,
"variable": "Injuries",
"value":             14 
},
{
 "X": 5016,
"State": "NJ",
"Year": 2005,
"variable": "Injuries",
"value":              5 
},
{
 "X": 5017,
"State": "NJ",
"Year": 2006,
"variable": "Injuries",
"value":             58 
},
{
 "X": 5018,
"State": "NJ",
"Year": 2007,
"variable": "Injuries",
"value":             14 
},
{
 "X": 5019,
"State": "NJ",
"Year": 2008,
"variable": "Injuries",
"value":             40 
},
{
 "X": 5020,
"State": "NJ",
"Year": 2009,
"variable": "Injuries",
"value":             35 
},
{
 "X": 5021,
"State": "NJ",
"Year": 2010,
"variable": "Injuries",
"value":             14 
},
{
 "X": 5022,
"State": "NJ",
"Year": 2011,
"variable": "Injuries",
"value":             25 
},
{
 "X": 5023,
"State": "NM",
"Year": 1950,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5024,
"State": "NM",
"Year": 1951,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5025,
"State": "NM",
"Year": 1952,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5026,
"State": "NM",
"Year": 1953,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5027,
"State": "NM",
"Year": 1954,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5028,
"State": "NM",
"Year": 1955,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5029,
"State": "NM",
"Year": 1956,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5030,
"State": "NM",
"Year": 1957,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5031,
"State": "NM",
"Year": 1958,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5032,
"State": "NM",
"Year": 1959,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5033,
"State": "NM",
"Year": 1960,
"variable": "Injuries",
"value":             34 
},
{
 "X": 5034,
"State": "NM",
"Year": 1961,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5035,
"State": "NM",
"Year": 1962,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5036,
"State": "NM",
"Year": 1963,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5037,
"State": "NM",
"Year": 1964,
"variable": "Injuries",
"value":              9 
},
{
 "X": 5038,
"State": "NM",
"Year": 1965,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5039,
"State": "NM",
"Year": 1966,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5040,
"State": "NM",
"Year": 1967,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5041,
"State": "NM",
"Year": 1968,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5042,
"State": "NM",
"Year": 1969,
"variable": "Injuries",
"value":              4 
},
{
 "X": 5043,
"State": "NM",
"Year": 1970,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5044,
"State": "NM",
"Year": 1971,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5045,
"State": "NM",
"Year": 1972,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5046,
"State": "NM",
"Year": 1973,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5047,
"State": "NM",
"Year": 1974,
"variable": "Injuries",
"value":              8 
},
{
 "X": 5048,
"State": "NM",
"Year": 1975,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5049,
"State": "NM",
"Year": 1976,
"variable": "Injuries",
"value":              2 
},
{
 "X": 5050,
"State": "NM",
"Year": 1977,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5051,
"State": "NM",
"Year": 1978,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5052,
"State": "NM",
"Year": 1979,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5053,
"State": "NM",
"Year": 1980,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5054,
"State": "NM",
"Year": 1981,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5055,
"State": "NM",
"Year": 1982,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5056,
"State": "NM",
"Year": 1983,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5057,
"State": "NM",
"Year": 1984,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5058,
"State": "NM",
"Year": 1985,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5059,
"State": "NM",
"Year": 1986,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5060,
"State": "NM",
"Year": 1987,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5061,
"State": "NM",
"Year": 1988,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5062,
"State": "NM",
"Year": 1989,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5063,
"State": "NM",
"Year": 1990,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5064,
"State": "NM",
"Year": 1991,
"variable": "Injuries",
"value":             26 
},
{
 "X": 5065,
"State": "NM",
"Year": 1992,
"variable": "Injuries",
"value":             51 
},
{
 "X": 5066,
"State": "NM",
"Year": 1993,
"variable": "Injuries",
"value":              7 
},
{
 "X": 5067,
"State": "NM",
"Year": 1994,
"variable": "Injuries",
"value":             15 
},
{
 "X": 5068,
"State": "NM",
"Year": 1995,
"variable": "Injuries",
"value":             40 
},
{
 "X": 5069,
"State": "NM",
"Year": 1996,
"variable": "Injuries",
"value":              6 
},
{
 "X": 5070,
"State": "NM",
"Year": 1997,
"variable": "Injuries",
"value":             14 
},
{
 "X": 5071,
"State": "NM",
"Year": 1998,
"variable": "Injuries",
"value":             15 
},
{
 "X": 5072,
"State": "NM",
"Year": 1999,
"variable": "Injuries",
"value":             13 
},
{
 "X": 5073,
"State": "NM",
"Year": 2000,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5074,
"State": "NM",
"Year": 2001,
"variable": "Injuries",
"value":             16 
},
{
 "X": 5075,
"State": "NM",
"Year": 2002,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5076,
"State": "NM",
"Year": 2003,
"variable": "Injuries",
"value":              8 
},
{
 "X": 5077,
"State": "NM",
"Year": 2004,
"variable": "Injuries",
"value":              5 
},
{
 "X": 5078,
"State": "NM",
"Year": 2005,
"variable": "Injuries",
"value":              2 
},
{
 "X": 5079,
"State": "NM",
"Year": 2006,
"variable": "Injuries",
"value":              9 
},
{
 "X": 5080,
"State": "NM",
"Year": 2007,
"variable": "Injuries",
"value":             45 
},
{
 "X": 5081,
"State": "NM",
"Year": 2008,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5082,
"State": "NM",
"Year": 2009,
"variable": "Injuries",
"value":              9 
},
{
 "X": 5083,
"State": "NM",
"Year": 2010,
"variable": "Injuries",
"value":              4 
},
{
 "X": 5084,
"State": "NM",
"Year": 2011,
"variable": "Injuries",
"value":             16 
},
{
 "X": 5085,
"State": "NV",
"Year": 1950,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5086,
"State": "NV",
"Year": 1951,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5087,
"State": "NV",
"Year": 1952,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5088,
"State": "NV",
"Year": 1953,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5089,
"State": "NV",
"Year": 1954,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5090,
"State": "NV",
"Year": 1955,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5091,
"State": "NV",
"Year": 1956,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5092,
"State": "NV",
"Year": 1957,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5093,
"State": "NV",
"Year": 1958,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5094,
"State": "NV",
"Year": 1959,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5095,
"State": "NV",
"Year": 1960,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5096,
"State": "NV",
"Year": 1961,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5097,
"State": "NV",
"Year": 1962,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5098,
"State": "NV",
"Year": 1963,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5099,
"State": "NV",
"Year": 1964,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5100,
"State": "NV",
"Year": 1965,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5101,
"State": "NV",
"Year": 1966,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5102,
"State": "NV",
"Year": 1967,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5103,
"State": "NV",
"Year": 1968,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5104,
"State": "NV",
"Year": 1969,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5105,
"State": "NV",
"Year": 1970,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5106,
"State": "NV",
"Year": 1971,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5107,
"State": "NV",
"Year": 1972,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5108,
"State": "NV",
"Year": 1973,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5109,
"State": "NV",
"Year": 1974,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5110,
"State": "NV",
"Year": 1975,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5111,
"State": "NV",
"Year": 1976,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5112,
"State": "NV",
"Year": 1977,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5113,
"State": "NV",
"Year": 1978,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5114,
"State": "NV",
"Year": 1979,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5115,
"State": "NV",
"Year": 1980,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5116,
"State": "NV",
"Year": 1981,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5117,
"State": "NV",
"Year": 1982,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5118,
"State": "NV",
"Year": 1983,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5119,
"State": "NV",
"Year": 1984,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5120,
"State": "NV",
"Year": 1985,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5121,
"State": "NV",
"Year": 1986,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5122,
"State": "NV",
"Year": 1987,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5123,
"State": "NV",
"Year": 1988,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5124,
"State": "NV",
"Year": 1989,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5125,
"State": "NV",
"Year": 1990,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5126,
"State": "NV",
"Year": 1991,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5127,
"State": "NV",
"Year": 1992,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5128,
"State": "NV",
"Year": 1993,
"variable": "Injuries",
"value":              2 
},
{
 "X": 5129,
"State": "NV",
"Year": 1994,
"variable": "Injuries",
"value":             12 
},
{
 "X": 5130,
"State": "NV",
"Year": 1995,
"variable": "Injuries",
"value":             10 
},
{
 "X": 5131,
"State": "NV",
"Year": 1996,
"variable": "Injuries",
"value":              9 
},
{
 "X": 5132,
"State": "NV",
"Year": 1997,
"variable": "Injuries",
"value":             57 
},
{
 "X": 5133,
"State": "NV",
"Year": 1998,
"variable": "Injuries",
"value":             21 
},
{
 "X": 5134,
"State": "NV",
"Year": 1999,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5135,
"State": "NV",
"Year": 2000,
"variable": "Injuries",
"value":             15 
},
{
 "X": 5136,
"State": "NV",
"Year": 2001,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5137,
"State": "NV",
"Year": 2002,
"variable": "Injuries",
"value":             18 
},
{
 "X": 5138,
"State": "NV",
"Year": 2003,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5139,
"State": "NV",
"Year": 2004,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5140,
"State": "NV",
"Year": 2005,
"variable": "Injuries",
"value":             32 
},
{
 "X": 5141,
"State": "NV",
"Year": 2006,
"variable": "Injuries",
"value":             13 
},
{
 "X": 5142,
"State": "NV",
"Year": 2007,
"variable": "Injuries",
"value":              5 
},
{
 "X": 5143,
"State": "NV",
"Year": 2008,
"variable": "Injuries",
"value":              8 
},
{
 "X": 5144,
"State": "NV",
"Year": 2009,
"variable": "Injuries",
"value":              2 
},
{
 "X": 5145,
"State": "NV",
"Year": 2010,
"variable": "Injuries",
"value":              5 
},
{
 "X": 5146,
"State": "NV",
"Year": 2011,
"variable": "Injuries",
"value":             10 
},
{
 "X": 5147,
"State": "NY",
"Year": 1950,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5148,
"State": "NY",
"Year": 1951,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5149,
"State": "NY",
"Year": 1952,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5150,
"State": "NY",
"Year": 1953,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5151,
"State": "NY",
"Year": 1954,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5152,
"State": "NY",
"Year": 1955,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5153,
"State": "NY",
"Year": 1956,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5154,
"State": "NY",
"Year": 1957,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5155,
"State": "NY",
"Year": 1958,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5156,
"State": "NY",
"Year": 1959,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5157,
"State": "NY",
"Year": 1960,
"variable": "Injuries",
"value":              9 
},
{
 "X": 5158,
"State": "NY",
"Year": 1961,
"variable": "Injuries",
"value":              4 
},
{
 "X": 5159,
"State": "NY",
"Year": 1962,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5160,
"State": "NY",
"Year": 1963,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5161,
"State": "NY",
"Year": 1964,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5162,
"State": "NY",
"Year": 1965,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5163,
"State": "NY",
"Year": 1966,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5164,
"State": "NY",
"Year": 1967,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5165,
"State": "NY",
"Year": 1968,
"variable": "Injuries",
"value":              4 
},
{
 "X": 5166,
"State": "NY",
"Year": 1969,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5167,
"State": "NY",
"Year": 1970,
"variable": "Injuries",
"value":              4 
},
{
 "X": 5168,
"State": "NY",
"Year": 1971,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5169,
"State": "NY",
"Year": 1972,
"variable": "Injuries",
"value":              4 
},
{
 "X": 5170,
"State": "NY",
"Year": 1973,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5171,
"State": "NY",
"Year": 1974,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5172,
"State": "NY",
"Year": 1975,
"variable": "Injuries",
"value":              5 
},
{
 "X": 5173,
"State": "NY",
"Year": 1976,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5174,
"State": "NY",
"Year": 1977,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5175,
"State": "NY",
"Year": 1978,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5176,
"State": "NY",
"Year": 1979,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5177,
"State": "NY",
"Year": 1980,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5178,
"State": "NY",
"Year": 1981,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5179,
"State": "NY",
"Year": 1982,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5180,
"State": "NY",
"Year": 1983,
"variable": "Injuries",
"value":             11 
},
{
 "X": 5181,
"State": "NY",
"Year": 1984,
"variable": "Injuries",
"value":             14 
},
{
 "X": 5182,
"State": "NY",
"Year": 1985,
"variable": "Injuries",
"value":             18 
},
{
 "X": 5183,
"State": "NY",
"Year": 1986,
"variable": "Injuries",
"value":             25 
},
{
 "X": 5184,
"State": "NY",
"Year": 1987,
"variable": "Injuries",
"value":             10 
},
{
 "X": 5185,
"State": "NY",
"Year": 1988,
"variable": "Injuries",
"value":             13 
},
{
 "X": 5186,
"State": "NY",
"Year": 1989,
"variable": "Injuries",
"value":             55 
},
{
 "X": 5187,
"State": "NY",
"Year": 1990,
"variable": "Injuries",
"value":             48 
},
{
 "X": 5188,
"State": "NY",
"Year": 1991,
"variable": "Injuries",
"value":              7 
},
{
 "X": 5189,
"State": "NY",
"Year": 1992,
"variable": "Injuries",
"value":             14 
},
{
 "X": 5190,
"State": "NY",
"Year": 1993,
"variable": "Injuries",
"value":             13 
},
{
 "X": 5191,
"State": "NY",
"Year": 1994,
"variable": "Injuries",
"value":             82 
},
{
 "X": 5192,
"State": "NY",
"Year": 1995,
"variable": "Injuries",
"value":             79 
},
{
 "X": 5193,
"State": "NY",
"Year": 1996,
"variable": "Injuries",
"value":             95 
},
{
 "X": 5194,
"State": "NY",
"Year": 1997,
"variable": "Injuries",
"value":            130 
},
{
 "X": 5195,
"State": "NY",
"Year": 1998,
"variable": "Injuries",
"value":            169 
},
{
 "X": 5196,
"State": "NY",
"Year": 1999,
"variable": "Injuries",
"value":             43 
},
{
 "X": 5197,
"State": "NY",
"Year": 2000,
"variable": "Injuries",
"value":             61 
},
{
 "X": 5198,
"State": "NY",
"Year": 2001,
"variable": "Injuries",
"value":             50 
},
{
 "X": 5199,
"State": "NY",
"Year": 2002,
"variable": "Injuries",
"value":            139 
},
{
 "X": 5200,
"State": "NY",
"Year": 2003,
"variable": "Injuries",
"value":             28 
},
{
 "X": 5201,
"State": "NY",
"Year": 2004,
"variable": "Injuries",
"value":             27 
},
{
 "X": 5202,
"State": "NY",
"Year": 2005,
"variable": "Injuries",
"value":             16 
},
{
 "X": 5203,
"State": "NY",
"Year": 2006,
"variable": "Injuries",
"value":             31 
},
{
 "X": 5204,
"State": "NY",
"Year": 2007,
"variable": "Injuries",
"value":             27 
},
{
 "X": 5205,
"State": "NY",
"Year": 2008,
"variable": "Injuries",
"value":             18 
},
{
 "X": 5206,
"State": "NY",
"Year": 2009,
"variable": "Injuries",
"value":             15 
},
{
 "X": 5207,
"State": "NY",
"Year": 2010,
"variable": "Injuries",
"value":             26 
},
{
 "X": 5208,
"State": "NY",
"Year": 2011,
"variable": "Injuries",
"value":             33 
},
{
 "X": 5209,
"State": "OH",
"Year": 1950,
"variable": "Injuries",
"value":             31 
},
{
 "X": 5210,
"State": "OH",
"Year": 1951,
"variable": "Injuries",
"value":              5 
},
{
 "X": 5211,
"State": "OH",
"Year": 1952,
"variable": "Injuries",
"value":              4 
},
{
 "X": 5212,
"State": "OH",
"Year": 1953,
"variable": "Injuries",
"value":            379 
},
{
 "X": 5213,
"State": "OH",
"Year": 1954,
"variable": "Injuries",
"value":              4 
},
{
 "X": 5214,
"State": "OH",
"Year": 1955,
"variable": "Injuries",
"value":             12 
},
{
 "X": 5215,
"State": "OH",
"Year": 1956,
"variable": "Injuries",
"value":              5 
},
{
 "X": 5216,
"State": "OH",
"Year": 1957,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5217,
"State": "OH",
"Year": 1958,
"variable": "Injuries",
"value":             14 
},
{
 "X": 5218,
"State": "OH",
"Year": 1959,
"variable": "Injuries",
"value":              6 
},
{
 "X": 5219,
"State": "OH",
"Year": 1960,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5220,
"State": "OH",
"Year": 1961,
"variable": "Injuries",
"value":             28 
},
{
 "X": 5221,
"State": "OH",
"Year": 1962,
"variable": "Injuries",
"value":             20 
},
{
 "X": 5222,
"State": "OH",
"Year": 1963,
"variable": "Injuries",
"value":             10 
},
{
 "X": 5223,
"State": "OH",
"Year": 1964,
"variable": "Injuries",
"value":              7 
},
{
 "X": 5224,
"State": "OH",
"Year": 1965,
"variable": "Injuries",
"value":            742 
},
{
 "X": 5225,
"State": "OH",
"Year": 1966,
"variable": "Injuries",
"value":             23 
},
{
 "X": 5226,
"State": "OH",
"Year": 1967,
"variable": "Injuries",
"value":              4 
},
{
 "X": 5227,
"State": "OH",
"Year": 1968,
"variable": "Injuries",
"value":            137 
},
{
 "X": 5228,
"State": "OH",
"Year": 1969,
"variable": "Injuries",
"value":            354 
},
{
 "X": 5229,
"State": "OH",
"Year": 1970,
"variable": "Injuries",
"value":             17 
},
{
 "X": 5230,
"State": "OH",
"Year": 1971,
"variable": "Injuries",
"value":             17 
},
{
 "X": 5231,
"State": "OH",
"Year": 1972,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5232,
"State": "OH",
"Year": 1973,
"variable": "Injuries",
"value":            140 
},
{
 "X": 5233,
"State": "OH",
"Year": 1974,
"variable": "Injuries",
"value":           1398 
},
{
 "X": 5234,
"State": "OH",
"Year": 1975,
"variable": "Injuries",
"value":              5 
},
{
 "X": 5235,
"State": "OH",
"Year": 1976,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5236,
"State": "OH",
"Year": 1977,
"variable": "Injuries",
"value":             47 
},
{
 "X": 5237,
"State": "OH",
"Year": 1978,
"variable": "Injuries",
"value":             14 
},
{
 "X": 5238,
"State": "OH",
"Year": 1979,
"variable": "Injuries",
"value":              4 
},
{
 "X": 5239,
"State": "OH",
"Year": 1980,
"variable": "Injuries",
"value":             57 
},
{
 "X": 5240,
"State": "OH",
"Year": 1981,
"variable": "Injuries",
"value":             81 
},
{
 "X": 5241,
"State": "OH",
"Year": 1982,
"variable": "Injuries",
"value":             20 
},
{
 "X": 5242,
"State": "OH",
"Year": 1983,
"variable": "Injuries",
"value":             52 
},
{
 "X": 5243,
"State": "OH",
"Year": 1984,
"variable": "Injuries",
"value":             13 
},
{
 "X": 5244,
"State": "OH",
"Year": 1985,
"variable": "Injuries",
"value":            345 
},
{
 "X": 5245,
"State": "OH",
"Year": 1986,
"variable": "Injuries",
"value":             47 
},
{
 "X": 5246,
"State": "OH",
"Year": 1987,
"variable": "Injuries",
"value":             10 
},
{
 "X": 5247,
"State": "OH",
"Year": 1988,
"variable": "Injuries",
"value":             13 
},
{
 "X": 5248,
"State": "OH",
"Year": 1989,
"variable": "Injuries",
"value":             20 
},
{
 "X": 5249,
"State": "OH",
"Year": 1990,
"variable": "Injuries",
"value":             39 
},
{
 "X": 5250,
"State": "OH",
"Year": 1991,
"variable": "Injuries",
"value":             54 
},
{
 "X": 5251,
"State": "OH",
"Year": 1992,
"variable": "Injuries",
"value":             92 
},
{
 "X": 5252,
"State": "OH",
"Year": 1993,
"variable": "Injuries",
"value":             19 
},
{
 "X": 5253,
"State": "OH",
"Year": 1994,
"variable": "Injuries",
"value":           1672 
},
{
 "X": 5254,
"State": "OH",
"Year": 1995,
"variable": "Injuries",
"value":            253 
},
{
 "X": 5255,
"State": "OH",
"Year": 1996,
"variable": "Injuries",
"value":             54 
},
{
 "X": 5256,
"State": "OH",
"Year": 1997,
"variable": "Injuries",
"value":             30 
},
{
 "X": 5257,
"State": "OH",
"Year": 1998,
"variable": "Injuries",
"value":            193 
},
{
 "X": 5258,
"State": "OH",
"Year": 1999,
"variable": "Injuries",
"value":            177 
},
{
 "X": 5259,
"State": "OH",
"Year": 2000,
"variable": "Injuries",
"value":            179 
},
{
 "X": 5260,
"State": "OH",
"Year": 2001,
"variable": "Injuries",
"value":             21 
},
{
 "X": 5261,
"State": "OH",
"Year": 2002,
"variable": "Injuries",
"value":             73 
},
{
 "X": 5262,
"State": "OH",
"Year": 2003,
"variable": "Injuries",
"value":             13 
},
{
 "X": 5263,
"State": "OH",
"Year": 2004,
"variable": "Injuries",
"value":             13 
},
{
 "X": 5264,
"State": "OH",
"Year": 2005,
"variable": "Injuries",
"value":             13 
},
{
 "X": 5265,
"State": "OH",
"Year": 2006,
"variable": "Injuries",
"value":             29 
},
{
 "X": 5266,
"State": "OH",
"Year": 2007,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5267,
"State": "OH",
"Year": 2008,
"variable": "Injuries",
"value":             12 
},
{
 "X": 5268,
"State": "OH",
"Year": 2009,
"variable": "Injuries",
"value":             11 
},
{
 "X": 5269,
"State": "OH",
"Year": 2010,
"variable": "Injuries",
"value":             64 
},
{
 "X": 5270,
"State": "OH",
"Year": 2011,
"variable": "Injuries",
"value":             10 
},
{
 "X": 5271,
"State": "OK",
"Year": 1950,
"variable": "Injuries",
"value":             45 
},
{
 "X": 5272,
"State": "OK",
"Year": 1951,
"variable": "Injuries",
"value":             16 
},
{
 "X": 5273,
"State": "OK",
"Year": 1952,
"variable": "Injuries",
"value":              2 
},
{
 "X": 5274,
"State": "OK",
"Year": 1953,
"variable": "Injuries",
"value":             45 
},
{
 "X": 5275,
"State": "OK",
"Year": 1954,
"variable": "Injuries",
"value":            103 
},
{
 "X": 5276,
"State": "OK",
"Year": 1955,
"variable": "Injuries",
"value":            299 
},
{
 "X": 5277,
"State": "OK",
"Year": 1956,
"variable": "Injuries",
"value":            131 
},
{
 "X": 5278,
"State": "OK",
"Year": 1957,
"variable": "Injuries",
"value":             53 
},
{
 "X": 5279,
"State": "OK",
"Year": 1958,
"variable": "Injuries",
"value":             25 
},
{
 "X": 5280,
"State": "OK",
"Year": 1959,
"variable": "Injuries",
"value":             42 
},
{
 "X": 5281,
"State": "OK",
"Year": 1960,
"variable": "Injuries",
"value":            319 
},
{
 "X": 5282,
"State": "OK",
"Year": 1961,
"variable": "Injuries",
"value":            109 
},
{
 "X": 5283,
"State": "OK",
"Year": 1962,
"variable": "Injuries",
"value":             16 
},
{
 "X": 5284,
"State": "OK",
"Year": 1963,
"variable": "Injuries",
"value":             11 
},
{
 "X": 5285,
"State": "OK",
"Year": 1964,
"variable": "Injuries",
"value":              4 
},
{
 "X": 5286,
"State": "OK",
"Year": 1965,
"variable": "Injuries",
"value":             12 
},
{
 "X": 5287,
"State": "OK",
"Year": 1966,
"variable": "Injuries",
"value":             21 
},
{
 "X": 5288,
"State": "OK",
"Year": 1967,
"variable": "Injuries",
"value":             14 
},
{
 "X": 5289,
"State": "OK",
"Year": 1968,
"variable": "Injuries",
"value":             15 
},
{
 "X": 5290,
"State": "OK",
"Year": 1969,
"variable": "Injuries",
"value":              2 
},
{
 "X": 5291,
"State": "OK",
"Year": 1970,
"variable": "Injuries",
"value":            118 
},
{
 "X": 5292,
"State": "OK",
"Year": 1971,
"variable": "Injuries",
"value":             13 
},
{
 "X": 5293,
"State": "OK",
"Year": 1972,
"variable": "Injuries",
"value":              9 
},
{
 "X": 5294,
"State": "OK",
"Year": 1973,
"variable": "Injuries",
"value":            220 
},
{
 "X": 5295,
"State": "OK",
"Year": 1974,
"variable": "Injuries",
"value":            301 
},
{
 "X": 5296,
"State": "OK",
"Year": 1975,
"variable": "Injuries",
"value":             90 
},
{
 "X": 5297,
"State": "OK",
"Year": 1976,
"variable": "Injuries",
"value":             77 
},
{
 "X": 5298,
"State": "OK",
"Year": 1977,
"variable": "Injuries",
"value":             18 
},
{
 "X": 5299,
"State": "OK",
"Year": 1978,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5300,
"State": "OK",
"Year": 1979,
"variable": "Injuries",
"value":            136 
},
{
 "X": 5301,
"State": "OK",
"Year": 1980,
"variable": "Injuries",
"value":             20 
},
{
 "X": 5302,
"State": "OK",
"Year": 1981,
"variable": "Injuries",
"value":            100 
},
{
 "X": 5303,
"State": "OK",
"Year": 1982,
"variable": "Injuries",
"value":            225 
},
{
 "X": 5304,
"State": "OK",
"Year": 1983,
"variable": "Injuries",
"value":             12 
},
{
 "X": 5305,
"State": "OK",
"Year": 1984,
"variable": "Injuries",
"value":            220 
},
{
 "X": 5306,
"State": "OK",
"Year": 1985,
"variable": "Injuries",
"value":             48 
},
{
 "X": 5307,
"State": "OK",
"Year": 1986,
"variable": "Injuries",
"value":             30 
},
{
 "X": 5308,
"State": "OK",
"Year": 1987,
"variable": "Injuries",
"value":             26 
},
{
 "X": 5309,
"State": "OK",
"Year": 1988,
"variable": "Injuries",
"value":             21 
},
{
 "X": 5310,
"State": "OK",
"Year": 1989,
"variable": "Injuries",
"value":             11 
},
{
 "X": 5311,
"State": "OK",
"Year": 1990,
"variable": "Injuries",
"value":             36 
},
{
 "X": 5312,
"State": "OK",
"Year": 1991,
"variable": "Injuries",
"value":             85 
},
{
 "X": 5313,
"State": "OK",
"Year": 1992,
"variable": "Injuries",
"value":             39 
},
{
 "X": 5314,
"State": "OK",
"Year": 1993,
"variable": "Injuries",
"value":            127 
},
{
 "X": 5315,
"State": "OK",
"Year": 1994,
"variable": "Injuries",
"value":             16 
},
{
 "X": 5316,
"State": "OK",
"Year": 1995,
"variable": "Injuries",
"value":             50 
},
{
 "X": 5317,
"State": "OK",
"Year": 1996,
"variable": "Injuries",
"value":             16 
},
{
 "X": 5318,
"State": "OK",
"Year": 1997,
"variable": "Injuries",
"value":             19 
},
{
 "X": 5319,
"State": "OK",
"Year": 1998,
"variable": "Injuries",
"value":             91 
},
{
 "X": 5320,
"State": "OK",
"Year": 1999,
"variable": "Injuries",
"value":            706 
},
{
 "X": 5321,
"State": "OK",
"Year": 2000,
"variable": "Injuries",
"value":             21 
},
{
 "X": 5322,
"State": "OK",
"Year": 2001,
"variable": "Injuries",
"value":             39 
},
{
 "X": 5323,
"State": "OK",
"Year": 2002,
"variable": "Injuries",
"value":             11 
},
{
 "X": 5324,
"State": "OK",
"Year": 2003,
"variable": "Injuries",
"value":            163 
},
{
 "X": 5325,
"State": "OK",
"Year": 2004,
"variable": "Injuries",
"value":             15 
},
{
 "X": 5326,
"State": "OK",
"Year": 2005,
"variable": "Injuries",
"value":             26 
},
{
 "X": 5327,
"State": "OK",
"Year": 2006,
"variable": "Injuries",
"value":            149 
},
{
 "X": 5328,
"State": "OK",
"Year": 2007,
"variable": "Injuries",
"value":             75 
},
{
 "X": 5329,
"State": "OK",
"Year": 2008,
"variable": "Injuries",
"value":            214 
},
{
 "X": 5330,
"State": "OK",
"Year": 2009,
"variable": "Injuries",
"value":             55 
},
{
 "X": 5331,
"State": "OK",
"Year": 2010,
"variable": "Injuries",
"value":            345 
},
{
 "X": 5332,
"State": "OK",
"Year": 2011,
"variable": "Injuries",
"value":            430 
},
{
 "X": 5333,
"State": "OR",
"Year": 1950,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5334,
"State": "OR",
"Year": 1951,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5335,
"State": "OR",
"Year": 1952,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5336,
"State": "OR",
"Year": 1953,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5337,
"State": "OR",
"Year": 1954,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5338,
"State": "OR",
"Year": 1955,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5339,
"State": "OR",
"Year": 1956,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5340,
"State": "OR",
"Year": 1957,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5341,
"State": "OR",
"Year": 1958,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5342,
"State": "OR",
"Year": 1959,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5343,
"State": "OR",
"Year": 1960,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5344,
"State": "OR",
"Year": 1961,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5345,
"State": "OR",
"Year": 1962,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5346,
"State": "OR",
"Year": 1963,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5347,
"State": "OR",
"Year": 1964,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5348,
"State": "OR",
"Year": 1965,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5349,
"State": "OR",
"Year": 1966,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5350,
"State": "OR",
"Year": 1967,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5351,
"State": "OR",
"Year": 1968,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5352,
"State": "OR",
"Year": 1969,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5353,
"State": "OR",
"Year": 1970,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5354,
"State": "OR",
"Year": 1971,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5355,
"State": "OR",
"Year": 1972,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5356,
"State": "OR",
"Year": 1973,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5357,
"State": "OR",
"Year": 1974,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5358,
"State": "OR",
"Year": 1975,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5359,
"State": "OR",
"Year": 1976,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5360,
"State": "OR",
"Year": 1977,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5361,
"State": "OR",
"Year": 1978,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5362,
"State": "OR",
"Year": 1979,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5363,
"State": "OR",
"Year": 1980,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5364,
"State": "OR",
"Year": 1981,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5365,
"State": "OR",
"Year": 1982,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5366,
"State": "OR",
"Year": 1983,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5367,
"State": "OR",
"Year": 1984,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5368,
"State": "OR",
"Year": 1985,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5369,
"State": "OR",
"Year": 1986,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5370,
"State": "OR",
"Year": 1987,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5371,
"State": "OR",
"Year": 1988,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5372,
"State": "OR",
"Year": 1989,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5373,
"State": "OR",
"Year": 1990,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5374,
"State": "OR",
"Year": 1991,
"variable": "Injuries",
"value":              5 
},
{
 "X": 5375,
"State": "OR",
"Year": 1992,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5376,
"State": "OR",
"Year": 1993,
"variable": "Injuries",
"value":              6 
},
{
 "X": 5377,
"State": "OR",
"Year": 1994,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5378,
"State": "OR",
"Year": 1995,
"variable": "Injuries",
"value":              9 
},
{
 "X": 5379,
"State": "OR",
"Year": 1996,
"variable": "Injuries",
"value":             44 
},
{
 "X": 5380,
"State": "OR",
"Year": 1997,
"variable": "Injuries",
"value":             26 
},
{
 "X": 5381,
"State": "OR",
"Year": 1998,
"variable": "Injuries",
"value":             13 
},
{
 "X": 5382,
"State": "OR",
"Year": 1999,
"variable": "Injuries",
"value":             46 
},
{
 "X": 5383,
"State": "OR",
"Year": 2000,
"variable": "Injuries",
"value":             14 
},
{
 "X": 5384,
"State": "OR",
"Year": 2001,
"variable": "Injuries",
"value":              9 
},
{
 "X": 5385,
"State": "OR",
"Year": 2002,
"variable": "Injuries",
"value":             12 
},
{
 "X": 5386,
"State": "OR",
"Year": 2003,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5387,
"State": "OR",
"Year": 2004,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5388,
"State": "OR",
"Year": 2005,
"variable": "Injuries",
"value":              4 
},
{
 "X": 5389,
"State": "OR",
"Year": 2006,
"variable": "Injuries",
"value":              6 
},
{
 "X": 5390,
"State": "OR",
"Year": 2007,
"variable": "Injuries",
"value":              2 
},
{
 "X": 5391,
"State": "OR",
"Year": 2008,
"variable": "Injuries",
"value":              2 
},
{
 "X": 5392,
"State": "OR",
"Year": 2009,
"variable": "Injuries",
"value":             12 
},
{
 "X": 5393,
"State": "OR",
"Year": 2010,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5394,
"State": "OR",
"Year": 2011,
"variable": "Injuries",
"value":              2 
},
{
 "X": 5395,
"State": "PA",
"Year": 1950,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5396,
"State": "PA",
"Year": 1951,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5397,
"State": "PA",
"Year": 1952,
"variable": "Injuries",
"value":             14 
},
{
 "X": 5398,
"State": "PA",
"Year": 1953,
"variable": "Injuries",
"value":              2 
},
{
 "X": 5399,
"State": "PA",
"Year": 1954,
"variable": "Injuries",
"value":             10 
},
{
 "X": 5400,
"State": "PA",
"Year": 1955,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5401,
"State": "PA",
"Year": 1956,
"variable": "Injuries",
"value":              9 
},
{
 "X": 5402,
"State": "PA",
"Year": 1957,
"variable": "Injuries",
"value":              5 
},
{
 "X": 5403,
"State": "PA",
"Year": 1958,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5404,
"State": "PA",
"Year": 1959,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5405,
"State": "PA",
"Year": 1960,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5406,
"State": "PA",
"Year": 1961,
"variable": "Injuries",
"value":              6 
},
{
 "X": 5407,
"State": "PA",
"Year": 1962,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5408,
"State": "PA",
"Year": 1963,
"variable": "Injuries",
"value":             90 
},
{
 "X": 5409,
"State": "PA",
"Year": 1964,
"variable": "Injuries",
"value":             10 
},
{
 "X": 5410,
"State": "PA",
"Year": 1965,
"variable": "Injuries",
"value":              7 
},
{
 "X": 5411,
"State": "PA",
"Year": 1966,
"variable": "Injuries",
"value":              6 
},
{
 "X": 5412,
"State": "PA",
"Year": 1967,
"variable": "Injuries",
"value":             11 
},
{
 "X": 5413,
"State": "PA",
"Year": 1968,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5414,
"State": "PA",
"Year": 1969,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5415,
"State": "PA",
"Year": 1970,
"variable": "Injuries",
"value":             10 
},
{
 "X": 5416,
"State": "PA",
"Year": 1971,
"variable": "Injuries",
"value":              4 
},
{
 "X": 5417,
"State": "PA",
"Year": 1972,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5418,
"State": "PA",
"Year": 1973,
"variable": "Injuries",
"value":              4 
},
{
 "X": 5419,
"State": "PA",
"Year": 1974,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5420,
"State": "PA",
"Year": 1975,
"variable": "Injuries",
"value":              2 
},
{
 "X": 5421,
"State": "PA",
"Year": 1976,
"variable": "Injuries",
"value":             26 
},
{
 "X": 5422,
"State": "PA",
"Year": 1977,
"variable": "Injuries",
"value":             11 
},
{
 "X": 5423,
"State": "PA",
"Year": 1978,
"variable": "Injuries",
"value":             31 
},
{
 "X": 5424,
"State": "PA",
"Year": 1979,
"variable": "Injuries",
"value":              5 
},
{
 "X": 5425,
"State": "PA",
"Year": 1980,
"variable": "Injuries",
"value":            142 
},
{
 "X": 5426,
"State": "PA",
"Year": 1981,
"variable": "Injuries",
"value":              6 
},
{
 "X": 5427,
"State": "PA",
"Year": 1982,
"variable": "Injuries",
"value":              4 
},
{
 "X": 5428,
"State": "PA",
"Year": 1983,
"variable": "Injuries",
"value":             13 
},
{
 "X": 5429,
"State": "PA",
"Year": 1984,
"variable": "Injuries",
"value":             16 
},
{
 "X": 5430,
"State": "PA",
"Year": 1985,
"variable": "Injuries",
"value":            530 
},
{
 "X": 5431,
"State": "PA",
"Year": 1986,
"variable": "Injuries",
"value":             35 
},
{
 "X": 5432,
"State": "PA",
"Year": 1987,
"variable": "Injuries",
"value":              5 
},
{
 "X": 5433,
"State": "PA",
"Year": 1988,
"variable": "Injuries",
"value":              8 
},
{
 "X": 5434,
"State": "PA",
"Year": 1989,
"variable": "Injuries",
"value":             28 
},
{
 "X": 5435,
"State": "PA",
"Year": 1990,
"variable": "Injuries",
"value":             11 
},
{
 "X": 5436,
"State": "PA",
"Year": 1991,
"variable": "Injuries",
"value":             38 
},
{
 "X": 5437,
"State": "PA",
"Year": 1992,
"variable": "Injuries",
"value":             46 
},
{
 "X": 5438,
"State": "PA",
"Year": 1993,
"variable": "Injuries",
"value":             11 
},
{
 "X": 5439,
"State": "PA",
"Year": 1994,
"variable": "Injuries",
"value":            494 
},
{
 "X": 5440,
"State": "PA",
"Year": 1995,
"variable": "Injuries",
"value":            112 
},
{
 "X": 5441,
"State": "PA",
"Year": 1996,
"variable": "Injuries",
"value":             52 
},
{
 "X": 5442,
"State": "PA",
"Year": 1997,
"variable": "Injuries",
"value":             84 
},
{
 "X": 5443,
"State": "PA",
"Year": 1998,
"variable": "Injuries",
"value":            264 
},
{
 "X": 5444,
"State": "PA",
"Year": 1999,
"variable": "Injuries",
"value":            358 
},
{
 "X": 5445,
"State": "PA",
"Year": 2000,
"variable": "Injuries",
"value":             17 
},
{
 "X": 5446,
"State": "PA",
"Year": 2001,
"variable": "Injuries",
"value":             32 
},
{
 "X": 5447,
"State": "PA",
"Year": 2002,
"variable": "Injuries",
"value":            141 
},
{
 "X": 5448,
"State": "PA",
"Year": 2003,
"variable": "Injuries",
"value":             32 
},
{
 "X": 5449,
"State": "PA",
"Year": 2004,
"variable": "Injuries",
"value":            233 
},
{
 "X": 5450,
"State": "PA",
"Year": 2005,
"variable": "Injuries",
"value":             73 
},
{
 "X": 5451,
"State": "PA",
"Year": 2006,
"variable": "Injuries",
"value":             52 
},
{
 "X": 5452,
"State": "PA",
"Year": 2007,
"variable": "Injuries",
"value":             13 
},
{
 "X": 5453,
"State": "PA",
"Year": 2008,
"variable": "Injuries",
"value":             25 
},
{
 "X": 5454,
"State": "PA",
"Year": 2009,
"variable": "Injuries",
"value":             40 
},
{
 "X": 5455,
"State": "PA",
"Year": 2010,
"variable": "Injuries",
"value":              8 
},
{
 "X": 5456,
"State": "PA",
"Year": 2011,
"variable": "Injuries",
"value":             26 
},
{
 "X": 5457,
"State": "RI",
"Year": 1950,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5458,
"State": "RI",
"Year": 1951,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5459,
"State": "RI",
"Year": 1952,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5460,
"State": "RI",
"Year": 1953,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5461,
"State": "RI",
"Year": 1954,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5462,
"State": "RI",
"Year": 1955,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5463,
"State": "RI",
"Year": 1956,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5464,
"State": "RI",
"Year": 1957,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5465,
"State": "RI",
"Year": 1958,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5466,
"State": "RI",
"Year": 1959,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5467,
"State": "RI",
"Year": 1960,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5468,
"State": "RI",
"Year": 1961,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5469,
"State": "RI",
"Year": 1962,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5470,
"State": "RI",
"Year": 1963,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5471,
"State": "RI",
"Year": 1964,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5472,
"State": "RI",
"Year": 1965,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5473,
"State": "RI",
"Year": 1966,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5474,
"State": "RI",
"Year": 1967,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5475,
"State": "RI",
"Year": 1968,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5476,
"State": "RI",
"Year": 1969,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5477,
"State": "RI",
"Year": 1970,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5478,
"State": "RI",
"Year": 1971,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5479,
"State": "RI",
"Year": 1972,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5480,
"State": "RI",
"Year": 1973,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5481,
"State": "RI",
"Year": 1974,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5482,
"State": "RI",
"Year": 1975,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5483,
"State": "RI",
"Year": 1976,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5484,
"State": "RI",
"Year": 1977,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5485,
"State": "RI",
"Year": 1978,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5486,
"State": "RI",
"Year": 1979,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5487,
"State": "RI",
"Year": 1980,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5488,
"State": "RI",
"Year": 1981,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5489,
"State": "RI",
"Year": 1982,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5490,
"State": "RI",
"Year": 1983,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5491,
"State": "RI",
"Year": 1984,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5492,
"State": "RI",
"Year": 1985,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5493,
"State": "RI",
"Year": 1986,
"variable": "Injuries",
"value":             20 
},
{
 "X": 5494,
"State": "RI",
"Year": 1987,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5495,
"State": "RI",
"Year": 1988,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5496,
"State": "RI",
"Year": 1989,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5497,
"State": "RI",
"Year": 1990,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5498,
"State": "RI",
"Year": 1991,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5499,
"State": "RI",
"Year": 1992,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5500,
"State": "RI",
"Year": 1993,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5501,
"State": "RI",
"Year": 1994,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5502,
"State": "RI",
"Year": 1995,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5503,
"State": "RI",
"Year": 1996,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5504,
"State": "RI",
"Year": 1997,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5505,
"State": "RI",
"Year": 1998,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5506,
"State": "RI",
"Year": 1999,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5507,
"State": "RI",
"Year": 2000,
"variable": "Injuries",
"value":              2 
},
{
 "X": 5508,
"State": "RI",
"Year": 2001,
"variable": "Injuries",
"value":              4 
},
{
 "X": 5509,
"State": "RI",
"Year": 2002,
"variable": "Injuries",
"value":              2 
},
{
 "X": 5510,
"State": "RI",
"Year": 2003,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5511,
"State": "RI",
"Year": 2004,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5512,
"State": "RI",
"Year": 2005,
"variable": "Injuries",
"value":              2 
},
{
 "X": 5513,
"State": "RI",
"Year": 2006,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5514,
"State": "RI",
"Year": 2007,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5515,
"State": "RI",
"Year": 2008,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5516,
"State": "RI",
"Year": 2009,
"variable": "Injuries",
"value":              9 
},
{
 "X": 5517,
"State": "RI",
"Year": 2010,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5518,
"State": "RI",
"Year": 2011,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5519,
"State": "SC",
"Year": 1950,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5520,
"State": "SC",
"Year": 1951,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5521,
"State": "SC",
"Year": 1952,
"variable": "Injuries",
"value":              4 
},
{
 "X": 5522,
"State": "SC",
"Year": 1953,
"variable": "Injuries",
"value":              2 
},
{
 "X": 5523,
"State": "SC",
"Year": 1954,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5524,
"State": "SC",
"Year": 1955,
"variable": "Injuries",
"value":             15 
},
{
 "X": 5525,
"State": "SC",
"Year": 1956,
"variable": "Injuries",
"value":              2 
},
{
 "X": 5526,
"State": "SC",
"Year": 1957,
"variable": "Injuries",
"value":             19 
},
{
 "X": 5527,
"State": "SC",
"Year": 1958,
"variable": "Injuries",
"value":              2 
},
{
 "X": 5528,
"State": "SC",
"Year": 1959,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5529,
"State": "SC",
"Year": 1960,
"variable": "Injuries",
"value":             10 
},
{
 "X": 5530,
"State": "SC",
"Year": 1961,
"variable": "Injuries",
"value":              9 
},
{
 "X": 5531,
"State": "SC",
"Year": 1962,
"variable": "Injuries",
"value":              4 
},
{
 "X": 5532,
"State": "SC",
"Year": 1963,
"variable": "Injuries",
"value":             13 
},
{
 "X": 5533,
"State": "SC",
"Year": 1964,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5534,
"State": "SC",
"Year": 1965,
"variable": "Injuries",
"value":             46 
},
{
 "X": 5535,
"State": "SC",
"Year": 1966,
"variable": "Injuries",
"value":              8 
},
{
 "X": 5536,
"State": "SC",
"Year": 1967,
"variable": "Injuries",
"value":              5 
},
{
 "X": 5537,
"State": "SC",
"Year": 1968,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5538,
"State": "SC",
"Year": 1969,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5539,
"State": "SC",
"Year": 1970,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5540,
"State": "SC",
"Year": 1971,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5541,
"State": "SC",
"Year": 1972,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5542,
"State": "SC",
"Year": 1973,
"variable": "Injuries",
"value":            111 
},
{
 "X": 5543,
"State": "SC",
"Year": 1974,
"variable": "Injuries",
"value":              6 
},
{
 "X": 5544,
"State": "SC",
"Year": 1975,
"variable": "Injuries",
"value":             32 
},
{
 "X": 5545,
"State": "SC",
"Year": 1976,
"variable": "Injuries",
"value":             11 
},
{
 "X": 5546,
"State": "SC",
"Year": 1977,
"variable": "Injuries",
"value":             13 
},
{
 "X": 5547,
"State": "SC",
"Year": 1978,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5548,
"State": "SC",
"Year": 1979,
"variable": "Injuries",
"value":              2 
},
{
 "X": 5549,
"State": "SC",
"Year": 1980,
"variable": "Injuries",
"value":             45 
},
{
 "X": 5550,
"State": "SC",
"Year": 1981,
"variable": "Injuries",
"value":              6 
},
{
 "X": 5551,
"State": "SC",
"Year": 1982,
"variable": "Injuries",
"value":             16 
},
{
 "X": 5552,
"State": "SC",
"Year": 1983,
"variable": "Injuries",
"value":              9 
},
{
 "X": 5553,
"State": "SC",
"Year": 1984,
"variable": "Injuries",
"value":            467 
},
{
 "X": 5554,
"State": "SC",
"Year": 1985,
"variable": "Injuries",
"value":             41 
},
{
 "X": 5555,
"State": "SC",
"Year": 1986,
"variable": "Injuries",
"value":              6 
},
{
 "X": 5556,
"State": "SC",
"Year": 1987,
"variable": "Injuries",
"value":             15 
},
{
 "X": 5557,
"State": "SC",
"Year": 1988,
"variable": "Injuries",
"value":             11 
},
{
 "X": 5558,
"State": "SC",
"Year": 1989,
"variable": "Injuries",
"value":             71 
},
{
 "X": 5559,
"State": "SC",
"Year": 1990,
"variable": "Injuries",
"value":             25 
},
{
 "X": 5560,
"State": "SC",
"Year": 1991,
"variable": "Injuries",
"value":              9 
},
{
 "X": 5561,
"State": "SC",
"Year": 1992,
"variable": "Injuries",
"value":             10 
},
{
 "X": 5562,
"State": "SC",
"Year": 1993,
"variable": "Injuries",
"value":              9 
},
{
 "X": 5563,
"State": "SC",
"Year": 1994,
"variable": "Injuries",
"value":             95 
},
{
 "X": 5564,
"State": "SC",
"Year": 1995,
"variable": "Injuries",
"value":             67 
},
{
 "X": 5565,
"State": "SC",
"Year": 1996,
"variable": "Injuries",
"value":             20 
},
{
 "X": 5566,
"State": "SC",
"Year": 1997,
"variable": "Injuries",
"value":             35 
},
{
 "X": 5567,
"State": "SC",
"Year": 1998,
"variable": "Injuries",
"value":             59 
},
{
 "X": 5568,
"State": "SC",
"Year": 1999,
"variable": "Injuries",
"value":             54 
},
{
 "X": 5569,
"State": "SC",
"Year": 2000,
"variable": "Injuries",
"value":             23 
},
{
 "X": 5570,
"State": "SC",
"Year": 2001,
"variable": "Injuries",
"value":             58 
},
{
 "X": 5571,
"State": "SC",
"Year": 2002,
"variable": "Injuries",
"value":             20 
},
{
 "X": 5572,
"State": "SC",
"Year": 2003,
"variable": "Injuries",
"value":             44 
},
{
 "X": 5573,
"State": "SC",
"Year": 2004,
"variable": "Injuries",
"value":             44 
},
{
 "X": 5574,
"State": "SC",
"Year": 2005,
"variable": "Injuries",
"value":              9 
},
{
 "X": 5575,
"State": "SC",
"Year": 2006,
"variable": "Injuries",
"value":             44 
},
{
 "X": 5576,
"State": "SC",
"Year": 2007,
"variable": "Injuries",
"value":             40 
},
{
 "X": 5577,
"State": "SC",
"Year": 2008,
"variable": "Injuries",
"value":             32 
},
{
 "X": 5578,
"State": "SC",
"Year": 2009,
"variable": "Injuries",
"value":             24 
},
{
 "X": 5579,
"State": "SC",
"Year": 2010,
"variable": "Injuries",
"value":             12 
},
{
 "X": 5580,
"State": "SC",
"Year": 2011,
"variable": "Injuries",
"value":             41 
},
{
 "X": 5581,
"State": "SD",
"Year": 1950,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5582,
"State": "SD",
"Year": 1951,
"variable": "Injuries",
"value":              5 
},
{
 "X": 5583,
"State": "SD",
"Year": 1952,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5584,
"State": "SD",
"Year": 1953,
"variable": "Injuries",
"value":              2 
},
{
 "X": 5585,
"State": "SD",
"Year": 1954,
"variable": "Injuries",
"value":              4 
},
{
 "X": 5586,
"State": "SD",
"Year": 1955,
"variable": "Injuries",
"value":              2 
},
{
 "X": 5587,
"State": "SD",
"Year": 1956,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5588,
"State": "SD",
"Year": 1957,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5589,
"State": "SD",
"Year": 1958,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5590,
"State": "SD",
"Year": 1959,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5591,
"State": "SD",
"Year": 1960,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5592,
"State": "SD",
"Year": 1961,
"variable": "Injuries",
"value":              7 
},
{
 "X": 5593,
"State": "SD",
"Year": 1962,
"variable": "Injuries",
"value":             43 
},
{
 "X": 5594,
"State": "SD",
"Year": 1963,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5595,
"State": "SD",
"Year": 1964,
"variable": "Injuries",
"value":             13 
},
{
 "X": 5596,
"State": "SD",
"Year": 1965,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5597,
"State": "SD",
"Year": 1966,
"variable": "Injuries",
"value":             12 
},
{
 "X": 5598,
"State": "SD",
"Year": 1967,
"variable": "Injuries",
"value":             15 
},
{
 "X": 5599,
"State": "SD",
"Year": 1968,
"variable": "Injuries",
"value":              2 
},
{
 "X": 5600,
"State": "SD",
"Year": 1969,
"variable": "Injuries",
"value":             18 
},
{
 "X": 5601,
"State": "SD",
"Year": 1970,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5602,
"State": "SD",
"Year": 1971,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5603,
"State": "SD",
"Year": 1972,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5604,
"State": "SD",
"Year": 1973,
"variable": "Injuries",
"value":             21 
},
{
 "X": 5605,
"State": "SD",
"Year": 1974,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5606,
"State": "SD",
"Year": 1975,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5607,
"State": "SD",
"Year": 1976,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5608,
"State": "SD",
"Year": 1977,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5609,
"State": "SD",
"Year": 1978,
"variable": "Injuries",
"value":             15 
},
{
 "X": 5610,
"State": "SD",
"Year": 1979,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5611,
"State": "SD",
"Year": 1980,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5612,
"State": "SD",
"Year": 1981,
"variable": "Injuries",
"value":              2 
},
{
 "X": 5613,
"State": "SD",
"Year": 1982,
"variable": "Injuries",
"value":              4 
},
{
 "X": 5614,
"State": "SD",
"Year": 1983,
"variable": "Injuries",
"value":              4 
},
{
 "X": 5615,
"State": "SD",
"Year": 1984,
"variable": "Injuries",
"value":              2 
},
{
 "X": 5616,
"State": "SD",
"Year": 1985,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5617,
"State": "SD",
"Year": 1986,
"variable": "Injuries",
"value":             28 
},
{
 "X": 5618,
"State": "SD",
"Year": 1987,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5619,
"State": "SD",
"Year": 1988,
"variable": "Injuries",
"value":              2 
},
{
 "X": 5620,
"State": "SD",
"Year": 1989,
"variable": "Injuries",
"value":              9 
},
{
 "X": 5621,
"State": "SD",
"Year": 1990,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5622,
"State": "SD",
"Year": 1991,
"variable": "Injuries",
"value":             31 
},
{
 "X": 5623,
"State": "SD",
"Year": 1992,
"variable": "Injuries",
"value":             10 
},
{
 "X": 5624,
"State": "SD",
"Year": 1993,
"variable": "Injuries",
"value":             37 
},
{
 "X": 5625,
"State": "SD",
"Year": 1994,
"variable": "Injuries",
"value":             57 
},
{
 "X": 5626,
"State": "SD",
"Year": 1995,
"variable": "Injuries",
"value":             28 
},
{
 "X": 5627,
"State": "SD",
"Year": 1996,
"variable": "Injuries",
"value":            104 
},
{
 "X": 5628,
"State": "SD",
"Year": 1997,
"variable": "Injuries",
"value":             31 
},
{
 "X": 5629,
"State": "SD",
"Year": 1998,
"variable": "Injuries",
"value":            171 
},
{
 "X": 5630,
"State": "SD",
"Year": 1999,
"variable": "Injuries",
"value":             59 
},
{
 "X": 5631,
"State": "SD",
"Year": 2000,
"variable": "Injuries",
"value":             20 
},
{
 "X": 5632,
"State": "SD",
"Year": 2001,
"variable": "Injuries",
"value":             14 
},
{
 "X": 5633,
"State": "SD",
"Year": 2002,
"variable": "Injuries",
"value":              5 
},
{
 "X": 5634,
"State": "SD",
"Year": 2003,
"variable": "Injuries",
"value":             13 
},
{
 "X": 5635,
"State": "SD",
"Year": 2004,
"variable": "Injuries",
"value":              2 
},
{
 "X": 5636,
"State": "SD",
"Year": 2005,
"variable": "Injuries",
"value":              5 
},
{
 "X": 5637,
"State": "SD",
"Year": 2006,
"variable": "Injuries",
"value":              9 
},
{
 "X": 5638,
"State": "SD",
"Year": 2007,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5639,
"State": "SD",
"Year": 2008,
"variable": "Injuries",
"value":             18 
},
{
 "X": 5640,
"State": "SD",
"Year": 2009,
"variable": "Injuries",
"value":              5 
},
{
 "X": 5641,
"State": "SD",
"Year": 2010,
"variable": "Injuries",
"value":             15 
},
{
 "X": 5642,
"State": "SD",
"Year": 2011,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5643,
"State": "TN",
"Year": 1950,
"variable": "Injuries",
"value":              9 
},
{
 "X": 5644,
"State": "TN",
"Year": 1951,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5645,
"State": "TN",
"Year": 1952,
"variable": "Injuries",
"value":            659 
},
{
 "X": 5646,
"State": "TN",
"Year": 1953,
"variable": "Injuries",
"value":             34 
},
{
 "X": 5647,
"State": "TN",
"Year": 1954,
"variable": "Injuries",
"value":              4 
},
{
 "X": 5648,
"State": "TN",
"Year": 1955,
"variable": "Injuries",
"value":             16 
},
{
 "X": 5649,
"State": "TN",
"Year": 1956,
"variable": "Injuries",
"value":             66 
},
{
 "X": 5650,
"State": "TN",
"Year": 1957,
"variable": "Injuries",
"value":             19 
},
{
 "X": 5651,
"State": "TN",
"Year": 1958,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5652,
"State": "TN",
"Year": 1959,
"variable": "Injuries",
"value":             10 
},
{
 "X": 5653,
"State": "TN",
"Year": 1960,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5654,
"State": "TN",
"Year": 1961,
"variable": "Injuries",
"value":              2 
},
{
 "X": 5655,
"State": "TN",
"Year": 1962,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5656,
"State": "TN",
"Year": 1963,
"variable": "Injuries",
"value":             27 
},
{
 "X": 5657,
"State": "TN",
"Year": 1964,
"variable": "Injuries",
"value":             19 
},
{
 "X": 5658,
"State": "TN",
"Year": 1965,
"variable": "Injuries",
"value":             59 
},
{
 "X": 5659,
"State": "TN",
"Year": 1966,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5660,
"State": "TN",
"Year": 1967,
"variable": "Injuries",
"value":             12 
},
{
 "X": 5661,
"State": "TN",
"Year": 1968,
"variable": "Injuries",
"value":             33 
},
{
 "X": 5662,
"State": "TN",
"Year": 1969,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5663,
"State": "TN",
"Year": 1970,
"variable": "Injuries",
"value":            114 
},
{
 "X": 5664,
"State": "TN",
"Year": 1971,
"variable": "Injuries",
"value":            223 
},
{
 "X": 5665,
"State": "TN",
"Year": 1972,
"variable": "Injuries",
"value":             35 
},
{
 "X": 5666,
"State": "TN",
"Year": 1973,
"variable": "Injuries",
"value":              9 
},
{
 "X": 5667,
"State": "TN",
"Year": 1974,
"variable": "Injuries",
"value":            774 
},
{
 "X": 5668,
"State": "TN",
"Year": 1975,
"variable": "Injuries",
"value":             44 
},
{
 "X": 5669,
"State": "TN",
"Year": 1976,
"variable": "Injuries",
"value":             12 
},
{
 "X": 5670,
"State": "TN",
"Year": 1977,
"variable": "Injuries",
"value":             20 
},
{
 "X": 5671,
"State": "TN",
"Year": 1978,
"variable": "Injuries",
"value":             27 
},
{
 "X": 5672,
"State": "TN",
"Year": 1979,
"variable": "Injuries",
"value":              9 
},
{
 "X": 5673,
"State": "TN",
"Year": 1980,
"variable": "Injuries",
"value":             19 
},
{
 "X": 5674,
"State": "TN",
"Year": 1981,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5675,
"State": "TN",
"Year": 1982,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5676,
"State": "TN",
"Year": 1983,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5677,
"State": "TN",
"Year": 1984,
"variable": "Injuries",
"value":             58 
},
{
 "X": 5678,
"State": "TN",
"Year": 1985,
"variable": "Injuries",
"value":              4 
},
{
 "X": 5679,
"State": "TN",
"Year": 1986,
"variable": "Injuries",
"value":             15 
},
{
 "X": 5680,
"State": "TN",
"Year": 1987,
"variable": "Injuries",
"value":             25 
},
{
 "X": 5681,
"State": "TN",
"Year": 1988,
"variable": "Injuries",
"value":             40 
},
{
 "X": 5682,
"State": "TN",
"Year": 1989,
"variable": "Injuries",
"value":              7 
},
{
 "X": 5683,
"State": "TN",
"Year": 1990,
"variable": "Injuries",
"value":             16 
},
{
 "X": 5684,
"State": "TN",
"Year": 1991,
"variable": "Injuries",
"value":             85 
},
{
 "X": 5685,
"State": "TN",
"Year": 1992,
"variable": "Injuries",
"value":              7 
},
{
 "X": 5686,
"State": "TN",
"Year": 1993,
"variable": "Injuries",
"value":             83 
},
{
 "X": 5687,
"State": "TN",
"Year": 1994,
"variable": "Injuries",
"value":            100 
},
{
 "X": 5688,
"State": "TN",
"Year": 1995,
"variable": "Injuries",
"value":            118 
},
{
 "X": 5689,
"State": "TN",
"Year": 1996,
"variable": "Injuries",
"value":             24 
},
{
 "X": 5690,
"State": "TN",
"Year": 1997,
"variable": "Injuries",
"value":            155 
},
{
 "X": 5691,
"State": "TN",
"Year": 1998,
"variable": "Injuries",
"value":            169 
},
{
 "X": 5692,
"State": "TN",
"Year": 1999,
"variable": "Injuries",
"value":            174 
},
{
 "X": 5693,
"State": "TN",
"Year": 2000,
"variable": "Injuries",
"value":             14 
},
{
 "X": 5694,
"State": "TN",
"Year": 2001,
"variable": "Injuries",
"value":             45 
},
{
 "X": 5695,
"State": "TN",
"Year": 2002,
"variable": "Injuries",
"value":            159 
},
{
 "X": 5696,
"State": "TN",
"Year": 2003,
"variable": "Injuries",
"value":            134 
},
{
 "X": 5697,
"State": "TN",
"Year": 2004,
"variable": "Injuries",
"value":             40 
},
{
 "X": 5698,
"State": "TN",
"Year": 2005,
"variable": "Injuries",
"value":             25 
},
{
 "X": 5699,
"State": "TN",
"Year": 2006,
"variable": "Injuries",
"value":            269 
},
{
 "X": 5700,
"State": "TN",
"Year": 2007,
"variable": "Injuries",
"value":             23 
},
{
 "X": 5701,
"State": "TN",
"Year": 2008,
"variable": "Injuries",
"value":            171 
},
{
 "X": 5702,
"State": "TN",
"Year": 2009,
"variable": "Injuries",
"value":             76 
},
{
 "X": 5703,
"State": "TN",
"Year": 2010,
"variable": "Injuries",
"value":             27 
},
{
 "X": 5704,
"State": "TN",
"Year": 2011,
"variable": "Injuries",
"value":            880 
},
{
 "X": 5705,
"State": "TX",
"Year": 1950,
"variable": "Injuries",
"value":            106 
},
{
 "X": 5706,
"State": "TX",
"Year": 1951,
"variable": "Injuries",
"value":            118 
},
{
 "X": 5707,
"State": "TX",
"Year": 1952,
"variable": "Injuries",
"value":             13 
},
{
 "X": 5708,
"State": "TX",
"Year": 1953,
"variable": "Injuries",
"value":            834 
},
{
 "X": 5709,
"State": "TX",
"Year": 1954,
"variable": "Injuries",
"value":            129 
},
{
 "X": 5710,
"State": "TX",
"Year": 1955,
"variable": "Injuries",
"value":             63 
},
{
 "X": 5711,
"State": "TX",
"Year": 1956,
"variable": "Injuries",
"value":             11 
},
{
 "X": 5712,
"State": "TX",
"Year": 1957,
"variable": "Injuries",
"value":            489 
},
{
 "X": 5713,
"State": "TX",
"Year": 1958,
"variable": "Injuries",
"value":             53 
},
{
 "X": 5714,
"State": "TX",
"Year": 1959,
"variable": "Injuries",
"value":             64 
},
{
 "X": 5715,
"State": "TX",
"Year": 1960,
"variable": "Injuries",
"value":             73 
},
{
 "X": 5716,
"State": "TX",
"Year": 1961,
"variable": "Injuries",
"value":            278 
},
{
 "X": 5717,
"State": "TX",
"Year": 1962,
"variable": "Injuries",
"value":             57 
},
{
 "X": 5718,
"State": "TX",
"Year": 1963,
"variable": "Injuries",
"value":              6 
},
{
 "X": 5719,
"State": "TX",
"Year": 1964,
"variable": "Injuries",
"value":            132 
},
{
 "X": 5720,
"State": "TX",
"Year": 1965,
"variable": "Injuries",
"value":             96 
},
{
 "X": 5721,
"State": "TX",
"Year": 1966,
"variable": "Injuries",
"value":             11 
},
{
 "X": 5722,
"State": "TX",
"Year": 1967,
"variable": "Injuries",
"value":             44 
},
{
 "X": 5723,
"State": "TX",
"Year": 1968,
"variable": "Injuries",
"value":             15 
},
{
 "X": 5724,
"State": "TX",
"Year": 1969,
"variable": "Injuries",
"value":             67 
},
{
 "X": 5725,
"State": "TX",
"Year": 1970,
"variable": "Injuries",
"value":            736 
},
{
 "X": 5726,
"State": "TX",
"Year": 1971,
"variable": "Injuries",
"value":            178 
},
{
 "X": 5727,
"State": "TX",
"Year": 1972,
"variable": "Injuries",
"value":             63 
},
{
 "X": 5728,
"State": "TX",
"Year": 1973,
"variable": "Injuries",
"value":            212 
},
{
 "X": 5729,
"State": "TX",
"Year": 1974,
"variable": "Injuries",
"value":             61 
},
{
 "X": 5730,
"State": "TX",
"Year": 1975,
"variable": "Injuries",
"value":             58 
},
{
 "X": 5731,
"State": "TX",
"Year": 1976,
"variable": "Injuries",
"value":             62 
},
{
 "X": 5732,
"State": "TX",
"Year": 1977,
"variable": "Injuries",
"value":             59 
},
{
 "X": 5733,
"State": "TX",
"Year": 1978,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5734,
"State": "TX",
"Year": 1979,
"variable": "Injuries",
"value":           1835 
},
{
 "X": 5735,
"State": "TX",
"Year": 1980,
"variable": "Injuries",
"value":             52 
},
{
 "X": 5736,
"State": "TX",
"Year": 1981,
"variable": "Injuries",
"value":             83 
},
{
 "X": 5737,
"State": "TX",
"Year": 1982,
"variable": "Injuries",
"value":            253 
},
{
 "X": 5738,
"State": "TX",
"Year": 1983,
"variable": "Injuries",
"value":            107 
},
{
 "X": 5739,
"State": "TX",
"Year": 1984,
"variable": "Injuries",
"value":            142 
},
{
 "X": 5740,
"State": "TX",
"Year": 1985,
"variable": "Injuries",
"value":             68 
},
{
 "X": 5741,
"State": "TX",
"Year": 1986,
"variable": "Injuries",
"value":            123 
},
{
 "X": 5742,
"State": "TX",
"Year": 1987,
"variable": "Injuries",
"value":            397 
},
{
 "X": 5743,
"State": "TX",
"Year": 1988,
"variable": "Injuries",
"value":             39 
},
{
 "X": 5744,
"State": "TX",
"Year": 1989,
"variable": "Injuries",
"value":            107 
},
{
 "X": 5745,
"State": "TX",
"Year": 1990,
"variable": "Injuries",
"value":            119 
},
{
 "X": 5746,
"State": "TX",
"Year": 1991,
"variable": "Injuries",
"value":             49 
},
{
 "X": 5747,
"State": "TX",
"Year": 1992,
"variable": "Injuries",
"value":             73 
},
{
 "X": 5748,
"State": "TX",
"Year": 1993,
"variable": "Injuries",
"value":             75 
},
{
 "X": 5749,
"State": "TX",
"Year": 1994,
"variable": "Injuries",
"value":            188 
},
{
 "X": 5750,
"State": "TX",
"Year": 1995,
"variable": "Injuries",
"value":            647 
},
{
 "X": 5751,
"State": "TX",
"Year": 1996,
"variable": "Injuries",
"value":            102 
},
{
 "X": 5752,
"State": "TX",
"Year": 1997,
"variable": "Injuries",
"value":            387 
},
{
 "X": 5753,
"State": "TX",
"Year": 1998,
"variable": "Injuries",
"value":           6442 
},
{
 "X": 5754,
"State": "TX",
"Year": 1999,
"variable": "Injuries",
"value":             99 
},
{
 "X": 5755,
"State": "TX",
"Year": 2000,
"variable": "Injuries",
"value":            146 
},
{
 "X": 5756,
"State": "TX",
"Year": 2001,
"variable": "Injuries",
"value":            314 
},
{
 "X": 5757,
"State": "TX",
"Year": 2002,
"variable": "Injuries",
"value":            180 
},
{
 "X": 5758,
"State": "TX",
"Year": 2003,
"variable": "Injuries",
"value":            139 
},
{
 "X": 5759,
"State": "TX",
"Year": 2004,
"variable": "Injuries",
"value":            104 
},
{
 "X": 5760,
"State": "TX",
"Year": 2005,
"variable": "Injuries",
"value":             74 
},
{
 "X": 5761,
"State": "TX",
"Year": 2006,
"variable": "Injuries",
"value":            131 
},
{
 "X": 5762,
"State": "TX",
"Year": 2007,
"variable": "Injuries",
"value":            248 
},
{
 "X": 5763,
"State": "TX",
"Year": 2008,
"variable": "Injuries",
"value":             79 
},
{
 "X": 5764,
"State": "TX",
"Year": 2009,
"variable": "Injuries",
"value":             88 
},
{
 "X": 5765,
"State": "TX",
"Year": 2010,
"variable": "Injuries",
"value":             32 
},
{
 "X": 5766,
"State": "TX",
"Year": 2011,
"variable": "Injuries",
"value":            657 
},
{
 "X": 5767,
"State": "UT",
"Year": 1950,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5768,
"State": "UT",
"Year": 1951,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5769,
"State": "UT",
"Year": 1952,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5770,
"State": "UT",
"Year": 1953,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5771,
"State": "UT",
"Year": 1954,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5772,
"State": "UT",
"Year": 1955,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5773,
"State": "UT",
"Year": 1956,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5774,
"State": "UT",
"Year": 1957,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5775,
"State": "UT",
"Year": 1958,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5776,
"State": "UT",
"Year": 1959,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5777,
"State": "UT",
"Year": 1960,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5778,
"State": "UT",
"Year": 1961,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5779,
"State": "UT",
"Year": 1962,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5780,
"State": "UT",
"Year": 1963,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5781,
"State": "UT",
"Year": 1964,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5782,
"State": "UT",
"Year": 1965,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5783,
"State": "UT",
"Year": 1966,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5784,
"State": "UT",
"Year": 1967,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5785,
"State": "UT",
"Year": 1968,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5786,
"State": "UT",
"Year": 1969,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5787,
"State": "UT",
"Year": 1970,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5788,
"State": "UT",
"Year": 1971,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5789,
"State": "UT",
"Year": 1972,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5790,
"State": "UT",
"Year": 1973,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5791,
"State": "UT",
"Year": 1974,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5792,
"State": "UT",
"Year": 1975,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5793,
"State": "UT",
"Year": 1976,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5794,
"State": "UT",
"Year": 1977,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5795,
"State": "UT",
"Year": 1978,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5796,
"State": "UT",
"Year": 1979,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5797,
"State": "UT",
"Year": 1980,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5798,
"State": "UT",
"Year": 1981,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5799,
"State": "UT",
"Year": 1982,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5800,
"State": "UT",
"Year": 1983,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5801,
"State": "UT",
"Year": 1984,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5802,
"State": "UT",
"Year": 1985,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5803,
"State": "UT",
"Year": 1986,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5804,
"State": "UT",
"Year": 1987,
"variable": "Injuries",
"value":              8 
},
{
 "X": 5805,
"State": "UT",
"Year": 1988,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5806,
"State": "UT",
"Year": 1989,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5807,
"State": "UT",
"Year": 1990,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5808,
"State": "UT",
"Year": 1991,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5809,
"State": "UT",
"Year": 1992,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5810,
"State": "UT",
"Year": 1993,
"variable": "Injuries",
"value":             46 
},
{
 "X": 5811,
"State": "UT",
"Year": 1994,
"variable": "Injuries",
"value":             18 
},
{
 "X": 5812,
"State": "UT",
"Year": 1995,
"variable": "Injuries",
"value":             15 
},
{
 "X": 5813,
"State": "UT",
"Year": 1996,
"variable": "Injuries",
"value":            126 
},
{
 "X": 5814,
"State": "UT",
"Year": 1997,
"variable": "Injuries",
"value":            280 
},
{
 "X": 5815,
"State": "UT",
"Year": 1998,
"variable": "Injuries",
"value":            160 
},
{
 "X": 5816,
"State": "UT",
"Year": 1999,
"variable": "Injuries",
"value":            143 
},
{
 "X": 5817,
"State": "UT",
"Year": 2000,
"variable": "Injuries",
"value":             31 
},
{
 "X": 5818,
"State": "UT",
"Year": 2001,
"variable": "Injuries",
"value":             27 
},
{
 "X": 5819,
"State": "UT",
"Year": 2002,
"variable": "Injuries",
"value":            104 
},
{
 "X": 5820,
"State": "UT",
"Year": 2003,
"variable": "Injuries",
"value":             27 
},
{
 "X": 5821,
"State": "UT",
"Year": 2004,
"variable": "Injuries",
"value":             14 
},
{
 "X": 5822,
"State": "UT",
"Year": 2005,
"variable": "Injuries",
"value":             35 
},
{
 "X": 5823,
"State": "UT",
"Year": 2006,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5824,
"State": "UT",
"Year": 2007,
"variable": "Injuries",
"value":              7 
},
{
 "X": 5825,
"State": "UT",
"Year": 2008,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5826,
"State": "UT",
"Year": 2009,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5827,
"State": "UT",
"Year": 2010,
"variable": "Injuries",
"value":             12 
},
{
 "X": 5828,
"State": "UT",
"Year": 2011,
"variable": "Injuries",
"value":              6 
},
{
 "X": 5829,
"State": "VA",
"Year": 1950,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5830,
"State": "VA",
"Year": 1951,
"variable": "Injuries",
"value":             12 
},
{
 "X": 5831,
"State": "VA",
"Year": 1952,
"variable": "Injuries",
"value":              2 
},
{
 "X": 5832,
"State": "VA",
"Year": 1953,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5833,
"State": "VA",
"Year": 1954,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5834,
"State": "VA",
"Year": 1955,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5835,
"State": "VA",
"Year": 1956,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5836,
"State": "VA",
"Year": 1957,
"variable": "Injuries",
"value":              5 
},
{
 "X": 5837,
"State": "VA",
"Year": 1958,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5838,
"State": "VA",
"Year": 1959,
"variable": "Injuries",
"value":             13 
},
{
 "X": 5839,
"State": "VA",
"Year": 1960,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5840,
"State": "VA",
"Year": 1961,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5841,
"State": "VA",
"Year": 1962,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5842,
"State": "VA",
"Year": 1963,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5843,
"State": "VA",
"Year": 1964,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5844,
"State": "VA",
"Year": 1965,
"variable": "Injuries",
"value":              5 
},
{
 "X": 5845,
"State": "VA",
"Year": 1966,
"variable": "Injuries",
"value":              2 
},
{
 "X": 5846,
"State": "VA",
"Year": 1967,
"variable": "Injuries",
"value":              6 
},
{
 "X": 5847,
"State": "VA",
"Year": 1968,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5848,
"State": "VA",
"Year": 1969,
"variable": "Injuries",
"value":              5 
},
{
 "X": 5849,
"State": "VA",
"Year": 1970,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5850,
"State": "VA",
"Year": 1971,
"variable": "Injuries",
"value":              4 
},
{
 "X": 5851,
"State": "VA",
"Year": 1972,
"variable": "Injuries",
"value":              2 
},
{
 "X": 5852,
"State": "VA",
"Year": 1973,
"variable": "Injuries",
"value":             37 
},
{
 "X": 5853,
"State": "VA",
"Year": 1974,
"variable": "Injuries",
"value":             11 
},
{
 "X": 5854,
"State": "VA",
"Year": 1975,
"variable": "Injuries",
"value":              6 
},
{
 "X": 5855,
"State": "VA",
"Year": 1976,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5856,
"State": "VA",
"Year": 1977,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5857,
"State": "VA",
"Year": 1978,
"variable": "Injuries",
"value":             13 
},
{
 "X": 5858,
"State": "VA",
"Year": 1979,
"variable": "Injuries",
"value":             19 
},
{
 "X": 5859,
"State": "VA",
"Year": 1980,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5860,
"State": "VA",
"Year": 1981,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5861,
"State": "VA",
"Year": 1982,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5862,
"State": "VA",
"Year": 1983,
"variable": "Injuries",
"value":              6 
},
{
 "X": 5863,
"State": "VA",
"Year": 1984,
"variable": "Injuries",
"value":             21 
},
{
 "X": 5864,
"State": "VA",
"Year": 1985,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5865,
"State": "VA",
"Year": 1986,
"variable": "Injuries",
"value":              2 
},
{
 "X": 5866,
"State": "VA",
"Year": 1987,
"variable": "Injuries",
"value":              4 
},
{
 "X": 5867,
"State": "VA",
"Year": 1988,
"variable": "Injuries",
"value":              2 
},
{
 "X": 5868,
"State": "VA",
"Year": 1989,
"variable": "Injuries",
"value":             42 
},
{
 "X": 5869,
"State": "VA",
"Year": 1990,
"variable": "Injuries",
"value":             28 
},
{
 "X": 5870,
"State": "VA",
"Year": 1991,
"variable": "Injuries",
"value":              4 
},
{
 "X": 5871,
"State": "VA",
"Year": 1992,
"variable": "Injuries",
"value":             11 
},
{
 "X": 5872,
"State": "VA",
"Year": 1993,
"variable": "Injuries",
"value":            289 
},
{
 "X": 5873,
"State": "VA",
"Year": 1994,
"variable": "Injuries",
"value":             16 
},
{
 "X": 5874,
"State": "VA",
"Year": 1995,
"variable": "Injuries",
"value":            220 
},
{
 "X": 5875,
"State": "VA",
"Year": 1996,
"variable": "Injuries",
"value":             25 
},
{
 "X": 5876,
"State": "VA",
"Year": 1997,
"variable": "Injuries",
"value":             67 
},
{
 "X": 5877,
"State": "VA",
"Year": 1998,
"variable": "Injuries",
"value":             17 
},
{
 "X": 5878,
"State": "VA",
"Year": 1999,
"variable": "Injuries",
"value":            121 
},
{
 "X": 5879,
"State": "VA",
"Year": 2000,
"variable": "Injuries",
"value":             51 
},
{
 "X": 5880,
"State": "VA",
"Year": 2001,
"variable": "Injuries",
"value":             15 
},
{
 "X": 5881,
"State": "VA",
"Year": 2002,
"variable": "Injuries",
"value":             31 
},
{
 "X": 5882,
"State": "VA",
"Year": 2003,
"variable": "Injuries",
"value":            116 
},
{
 "X": 5883,
"State": "VA",
"Year": 2004,
"variable": "Injuries",
"value":             23 
},
{
 "X": 5884,
"State": "VA",
"Year": 2005,
"variable": "Injuries",
"value":              7 
},
{
 "X": 5885,
"State": "VA",
"Year": 2006,
"variable": "Injuries",
"value":             11 
},
{
 "X": 5886,
"State": "VA",
"Year": 2007,
"variable": "Injuries",
"value":              4 
},
{
 "X": 5887,
"State": "VA",
"Year": 2008,
"variable": "Injuries",
"value":            230 
},
{
 "X": 5888,
"State": "VA",
"Year": 2009,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5889,
"State": "VA",
"Year": 2010,
"variable": "Injuries",
"value":             16 
},
{
 "X": 5890,
"State": "VA",
"Year": 2011,
"variable": "Injuries",
"value":            165 
},
{
 "X": 5891,
"State": "VT",
"Year": 1950,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5892,
"State": "VT",
"Year": 1951,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5893,
"State": "VT",
"Year": 1952,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5894,
"State": "VT",
"Year": 1953,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5895,
"State": "VT",
"Year": 1954,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5896,
"State": "VT",
"Year": 1955,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5897,
"State": "VT",
"Year": 1956,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5898,
"State": "VT",
"Year": 1957,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5899,
"State": "VT",
"Year": 1958,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5900,
"State": "VT",
"Year": 1959,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5901,
"State": "VT",
"Year": 1960,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5902,
"State": "VT",
"Year": 1961,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5903,
"State": "VT",
"Year": 1962,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5904,
"State": "VT",
"Year": 1963,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5905,
"State": "VT",
"Year": 1964,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5906,
"State": "VT",
"Year": 1965,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5907,
"State": "VT",
"Year": 1966,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5908,
"State": "VT",
"Year": 1967,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5909,
"State": "VT",
"Year": 1968,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5910,
"State": "VT",
"Year": 1969,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5911,
"State": "VT",
"Year": 1970,
"variable": "Injuries",
"value":              7 
},
{
 "X": 5912,
"State": "VT",
"Year": 1971,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5913,
"State": "VT",
"Year": 1972,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5914,
"State": "VT",
"Year": 1973,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5915,
"State": "VT",
"Year": 1974,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5916,
"State": "VT",
"Year": 1975,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5917,
"State": "VT",
"Year": 1976,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5918,
"State": "VT",
"Year": 1977,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5919,
"State": "VT",
"Year": 1978,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5920,
"State": "VT",
"Year": 1979,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5921,
"State": "VT",
"Year": 1980,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5922,
"State": "VT",
"Year": 1981,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5923,
"State": "VT",
"Year": 1982,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5924,
"State": "VT",
"Year": 1983,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5925,
"State": "VT",
"Year": 1984,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5926,
"State": "VT",
"Year": 1985,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5927,
"State": "VT",
"Year": 1986,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5928,
"State": "VT",
"Year": 1987,
"variable": "Injuries",
"value":              7 
},
{
 "X": 5929,
"State": "VT",
"Year": 1988,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5930,
"State": "VT",
"Year": 1989,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5931,
"State": "VT",
"Year": 1990,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5932,
"State": "VT",
"Year": 1991,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5933,
"State": "VT",
"Year": 1992,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5934,
"State": "VT",
"Year": 1993,
"variable": "Injuries",
"value":             11 
},
{
 "X": 5935,
"State": "VT",
"Year": 1994,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5936,
"State": "VT",
"Year": 1995,
"variable": "Injuries",
"value":              2 
},
{
 "X": 5937,
"State": "VT",
"Year": 1996,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5938,
"State": "VT",
"Year": 1997,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5939,
"State": "VT",
"Year": 1998,
"variable": "Injuries",
"value":              5 
},
{
 "X": 5940,
"State": "VT",
"Year": 1999,
"variable": "Injuries",
"value":              6 
},
{
 "X": 5941,
"State": "VT",
"Year": 2000,
"variable": "Injuries",
"value":              4 
},
{
 "X": 5942,
"State": "VT",
"Year": 2001,
"variable": "Injuries",
"value":              2 
},
{
 "X": 5943,
"State": "VT",
"Year": 2002,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5944,
"State": "VT",
"Year": 2003,
"variable": "Injuries",
"value":              2 
},
{
 "X": 5945,
"State": "VT",
"Year": 2004,
"variable": "Injuries",
"value":              2 
},
{
 "X": 5946,
"State": "VT",
"Year": 2005,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5947,
"State": "VT",
"Year": 2006,
"variable": "Injuries",
"value":             13 
},
{
 "X": 5948,
"State": "VT",
"Year": 2007,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5949,
"State": "VT",
"Year": 2008,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5950,
"State": "VT",
"Year": 2009,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5951,
"State": "VT",
"Year": 2010,
"variable": "Injuries",
"value":              3 
},
{
 "X": 5952,
"State": "VT",
"Year": 2011,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5953,
"State": "WA",
"Year": 1950,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5954,
"State": "WA",
"Year": 1951,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5955,
"State": "WA",
"Year": 1952,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5956,
"State": "WA",
"Year": 1953,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5957,
"State": "WA",
"Year": 1954,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5958,
"State": "WA",
"Year": 1955,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5959,
"State": "WA",
"Year": 1956,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5960,
"State": "WA",
"Year": 1957,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5961,
"State": "WA",
"Year": 1958,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5962,
"State": "WA",
"Year": 1959,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5963,
"State": "WA",
"Year": 1960,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5964,
"State": "WA",
"Year": 1961,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5965,
"State": "WA",
"Year": 1962,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5966,
"State": "WA",
"Year": 1963,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5967,
"State": "WA",
"Year": 1964,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5968,
"State": "WA",
"Year": 1965,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5969,
"State": "WA",
"Year": 1966,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5970,
"State": "WA",
"Year": 1967,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5971,
"State": "WA",
"Year": 1968,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5972,
"State": "WA",
"Year": 1969,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5973,
"State": "WA",
"Year": 1970,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5974,
"State": "WA",
"Year": 1971,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5975,
"State": "WA",
"Year": 1972,
"variable": "Injuries",
"value":            301 
},
{
 "X": 5976,
"State": "WA",
"Year": 1973,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5977,
"State": "WA",
"Year": 1974,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5978,
"State": "WA",
"Year": 1975,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5979,
"State": "WA",
"Year": 1976,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5980,
"State": "WA",
"Year": 1977,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5981,
"State": "WA",
"Year": 1978,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5982,
"State": "WA",
"Year": 1979,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5983,
"State": "WA",
"Year": 1980,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5984,
"State": "WA",
"Year": 1981,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5985,
"State": "WA",
"Year": 1982,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5986,
"State": "WA",
"Year": 1983,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5987,
"State": "WA",
"Year": 1984,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5988,
"State": "WA",
"Year": 1985,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5989,
"State": "WA",
"Year": 1986,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5990,
"State": "WA",
"Year": 1987,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5991,
"State": "WA",
"Year": 1988,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5992,
"State": "WA",
"Year": 1989,
"variable": "Injuries",
"value":              1 
},
{
 "X": 5993,
"State": "WA",
"Year": 1990,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5994,
"State": "WA",
"Year": 1991,
"variable": "Injuries",
"value":              0 
},
{
 "X": 5995,
"State": "WA",
"Year": 1992,
"variable": "Injuries",
"value":              2 
},
{
 "X": 5996,
"State": "WA",
"Year": 1993,
"variable": "Injuries",
"value":            137 
},
{
 "X": 5997,
"State": "WA",
"Year": 1994,
"variable": "Injuries",
"value":             51 
},
{
 "X": 5998,
"State": "WA",
"Year": 1995,
"variable": "Injuries",
"value":              2 
},
{
 "X": 5999,
"State": "WA",
"Year": 1996,
"variable": "Injuries",
"value":             34 
},
{
 "X": 6000,
"State": "WA",
"Year": 1997,
"variable": "Injuries",
"value":             21 
},
{
 "X": 6001,
"State": "WA",
"Year": 1998,
"variable": "Injuries",
"value":             15 
},
{
 "X": 6002,
"State": "WA",
"Year": 1999,
"variable": "Injuries",
"value":             15 
},
{
 "X": 6003,
"State": "WA",
"Year": 2000,
"variable": "Injuries",
"value":             21 
},
{
 "X": 6004,
"State": "WA",
"Year": 2001,
"variable": "Injuries",
"value":             19 
},
{
 "X": 6005,
"State": "WA",
"Year": 2002,
"variable": "Injuries",
"value":             12 
},
{
 "X": 6006,
"State": "WA",
"Year": 2003,
"variable": "Injuries",
"value":             37 
},
{
 "X": 6007,
"State": "WA",
"Year": 2004,
"variable": "Injuries",
"value":             10 
},
{
 "X": 6008,
"State": "WA",
"Year": 2005,
"variable": "Injuries",
"value":             23 
},
{
 "X": 6009,
"State": "WA",
"Year": 2006,
"variable": "Injuries",
"value":             14 
},
{
 "X": 6010,
"State": "WA",
"Year": 2007,
"variable": "Injuries",
"value":             18 
},
{
 "X": 6011,
"State": "WA",
"Year": 2008,
"variable": "Injuries",
"value":              4 
},
{
 "X": 6012,
"State": "WA",
"Year": 2009,
"variable": "Injuries",
"value":              4 
},
{
 "X": 6013,
"State": "WA",
"Year": 2010,
"variable": "Injuries",
"value":              7 
},
{
 "X": 6014,
"State": "WA",
"Year": 2011,
"variable": "Injuries",
"value":              4 
},
{
 "X": 6015,
"State": "WI",
"Year": 1950,
"variable": "Injuries",
"value":             12 
},
{
 "X": 6016,
"State": "WI",
"Year": 1951,
"variable": "Injuries",
"value":             13 
},
{
 "X": 6017,
"State": "WI",
"Year": 1952,
"variable": "Injuries",
"value":              6 
},
{
 "X": 6018,
"State": "WI",
"Year": 1953,
"variable": "Injuries",
"value":             32 
},
{
 "X": 6019,
"State": "WI",
"Year": 1954,
"variable": "Injuries",
"value":              4 
},
{
 "X": 6020,
"State": "WI",
"Year": 1955,
"variable": "Injuries",
"value":              7 
},
{
 "X": 6021,
"State": "WI",
"Year": 1956,
"variable": "Injuries",
"value":             52 
},
{
 "X": 6022,
"State": "WI",
"Year": 1957,
"variable": "Injuries",
"value":              7 
},
{
 "X": 6023,
"State": "WI",
"Year": 1958,
"variable": "Injuries",
"value":            140 
},
{
 "X": 6024,
"State": "WI",
"Year": 1959,
"variable": "Injuries",
"value":             15 
},
{
 "X": 6025,
"State": "WI",
"Year": 1960,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6026,
"State": "WI",
"Year": 1961,
"variable": "Injuries",
"value":              1 
},
{
 "X": 6027,
"State": "WI",
"Year": 1962,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6028,
"State": "WI",
"Year": 1963,
"variable": "Injuries",
"value":             40 
},
{
 "X": 6029,
"State": "WI",
"Year": 1964,
"variable": "Injuries",
"value":             67 
},
{
 "X": 6030,
"State": "WI",
"Year": 1965,
"variable": "Injuries",
"value":             78 
},
{
 "X": 6031,
"State": "WI",
"Year": 1966,
"variable": "Injuries",
"value":             18 
},
{
 "X": 6032,
"State": "WI",
"Year": 1967,
"variable": "Injuries",
"value":             17 
},
{
 "X": 6033,
"State": "WI",
"Year": 1968,
"variable": "Injuries",
"value":             14 
},
{
 "X": 6034,
"State": "WI",
"Year": 1969,
"variable": "Injuries",
"value":            163 
},
{
 "X": 6035,
"State": "WI",
"Year": 1970,
"variable": "Injuries",
"value":              8 
},
{
 "X": 6036,
"State": "WI",
"Year": 1971,
"variable": "Injuries",
"value":             24 
},
{
 "X": 6037,
"State": "WI",
"Year": 1972,
"variable": "Injuries",
"value":              3 
},
{
 "X": 6038,
"State": "WI",
"Year": 1973,
"variable": "Injuries",
"value":              2 
},
{
 "X": 6039,
"State": "WI",
"Year": 1974,
"variable": "Injuries",
"value":             54 
},
{
 "X": 6040,
"State": "WI",
"Year": 1975,
"variable": "Injuries",
"value":              6 
},
{
 "X": 6041,
"State": "WI",
"Year": 1976,
"variable": "Injuries",
"value":              2 
},
{
 "X": 6042,
"State": "WI",
"Year": 1977,
"variable": "Injuries",
"value":             49 
},
{
 "X": 6043,
"State": "WI",
"Year": 1978,
"variable": "Injuries",
"value":              2 
},
{
 "X": 6044,
"State": "WI",
"Year": 1979,
"variable": "Injuries",
"value":             13 
},
{
 "X": 6045,
"State": "WI",
"Year": 1980,
"variable": "Injuries",
"value":             53 
},
{
 "X": 6046,
"State": "WI",
"Year": 1981,
"variable": "Injuries",
"value":             62 
},
{
 "X": 6047,
"State": "WI",
"Year": 1982,
"variable": "Injuries",
"value":              5 
},
{
 "X": 6048,
"State": "WI",
"Year": 1983,
"variable": "Injuries",
"value":             10 
},
{
 "X": 6049,
"State": "WI",
"Year": 1984,
"variable": "Injuries",
"value":            250 
},
{
 "X": 6050,
"State": "WI",
"Year": 1985,
"variable": "Injuries",
"value":             81 
},
{
 "X": 6051,
"State": "WI",
"Year": 1986,
"variable": "Injuries",
"value":              2 
},
{
 "X": 6052,
"State": "WI",
"Year": 1987,
"variable": "Injuries",
"value":              5 
},
{
 "X": 6053,
"State": "WI",
"Year": 1988,
"variable": "Injuries",
"value":              8 
},
{
 "X": 6054,
"State": "WI",
"Year": 1989,
"variable": "Injuries",
"value":             15 
},
{
 "X": 6055,
"State": "WI",
"Year": 1990,
"variable": "Injuries",
"value":              7 
},
{
 "X": 6056,
"State": "WI",
"Year": 1991,
"variable": "Injuries",
"value":              9 
},
{
 "X": 6057,
"State": "WI",
"Year": 1992,
"variable": "Injuries",
"value":             62 
},
{
 "X": 6058,
"State": "WI",
"Year": 1993,
"variable": "Injuries",
"value":              3 
},
{
 "X": 6059,
"State": "WI",
"Year": 1994,
"variable": "Injuries",
"value":             16 
},
{
 "X": 6060,
"State": "WI",
"Year": 1995,
"variable": "Injuries",
"value":             66 
},
{
 "X": 6061,
"State": "WI",
"Year": 1996,
"variable": "Injuries",
"value":            140 
},
{
 "X": 6062,
"State": "WI",
"Year": 1997,
"variable": "Injuries",
"value":             41 
},
{
 "X": 6063,
"State": "WI",
"Year": 1998,
"variable": "Injuries",
"value":            179 
},
{
 "X": 6064,
"State": "WI",
"Year": 1999,
"variable": "Injuries",
"value":             60 
},
{
 "X": 6065,
"State": "WI",
"Year": 2000,
"variable": "Injuries",
"value":             69 
},
{
 "X": 6066,
"State": "WI",
"Year": 2001,
"variable": "Injuries",
"value":             32 
},
{
 "X": 6067,
"State": "WI",
"Year": 2002,
"variable": "Injuries",
"value":             37 
},
{
 "X": 6068,
"State": "WI",
"Year": 2003,
"variable": "Injuries",
"value":             14 
},
{
 "X": 6069,
"State": "WI",
"Year": 2004,
"variable": "Injuries",
"value":             28 
},
{
 "X": 6070,
"State": "WI",
"Year": 2005,
"variable": "Injuries",
"value":             41 
},
{
 "X": 6071,
"State": "WI",
"Year": 2006,
"variable": "Injuries",
"value":             56 
},
{
 "X": 6072,
"State": "WI",
"Year": 2007,
"variable": "Injuries",
"value":              6 
},
{
 "X": 6073,
"State": "WI",
"Year": 2008,
"variable": "Injuries",
"value":             33 
},
{
 "X": 6074,
"State": "WI",
"Year": 2009,
"variable": "Injuries",
"value":              6 
},
{
 "X": 6075,
"State": "WI",
"Year": 2010,
"variable": "Injuries",
"value":             46 
},
{
 "X": 6076,
"State": "WI",
"Year": 2011,
"variable": "Injuries",
"value":             18 
},
{
 "X": 6077,
"State": "WV",
"Year": 1950,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6078,
"State": "WV",
"Year": 1951,
"variable": "Injuries",
"value":              1 
},
{
 "X": 6079,
"State": "WV",
"Year": 1952,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6080,
"State": "WV",
"Year": 1953,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6081,
"State": "WV",
"Year": 1954,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6082,
"State": "WV",
"Year": 1955,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6083,
"State": "WV",
"Year": 1956,
"variable": "Injuries",
"value":              1 
},
{
 "X": 6084,
"State": "WV",
"Year": 1957,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6085,
"State": "WV",
"Year": 1958,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6086,
"State": "WV",
"Year": 1959,
"variable": "Injuries",
"value":             12 
},
{
 "X": 6087,
"State": "WV",
"Year": 1960,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6088,
"State": "WV",
"Year": 1961,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6089,
"State": "WV",
"Year": 1962,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6090,
"State": "WV",
"Year": 1963,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6091,
"State": "WV",
"Year": 1964,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6092,
"State": "WV",
"Year": 1965,
"variable": "Injuries",
"value":              3 
},
{
 "X": 6093,
"State": "WV",
"Year": 1966,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6094,
"State": "WV",
"Year": 1967,
"variable": "Injuries",
"value":              7 
},
{
 "X": 6095,
"State": "WV",
"Year": 1968,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6096,
"State": "WV",
"Year": 1969,
"variable": "Injuries",
"value":              1 
},
{
 "X": 6097,
"State": "WV",
"Year": 1970,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6098,
"State": "WV",
"Year": 1971,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6099,
"State": "WV",
"Year": 1972,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6100,
"State": "WV",
"Year": 1973,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6101,
"State": "WV",
"Year": 1974,
"variable": "Injuries",
"value":             32 
},
{
 "X": 6102,
"State": "WV",
"Year": 1975,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6103,
"State": "WV",
"Year": 1976,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6104,
"State": "WV",
"Year": 1977,
"variable": "Injuries",
"value":              9 
},
{
 "X": 6105,
"State": "WV",
"Year": 1978,
"variable": "Injuries",
"value":              1 
},
{
 "X": 6106,
"State": "WV",
"Year": 1979,
"variable": "Injuries",
"value":              1 
},
{
 "X": 6107,
"State": "WV",
"Year": 1980,
"variable": "Injuries",
"value":             15 
},
{
 "X": 6108,
"State": "WV",
"Year": 1981,
"variable": "Injuries",
"value":              3 
},
{
 "X": 6109,
"State": "WV",
"Year": 1982,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6110,
"State": "WV",
"Year": 1983,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6111,
"State": "WV",
"Year": 1984,
"variable": "Injuries",
"value":              7 
},
{
 "X": 6112,
"State": "WV",
"Year": 1985,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6113,
"State": "WV",
"Year": 1986,
"variable": "Injuries",
"value":              2 
},
{
 "X": 6114,
"State": "WV",
"Year": 1987,
"variable": "Injuries",
"value":              3 
},
{
 "X": 6115,
"State": "WV",
"Year": 1988,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6116,
"State": "WV",
"Year": 1989,
"variable": "Injuries",
"value":              3 
},
{
 "X": 6117,
"State": "WV",
"Year": 1990,
"variable": "Injuries",
"value":              1 
},
{
 "X": 6118,
"State": "WV",
"Year": 1991,
"variable": "Injuries",
"value":             87 
},
{
 "X": 6119,
"State": "WV",
"Year": 1992,
"variable": "Injuries",
"value":             19 
},
{
 "X": 6120,
"State": "WV",
"Year": 1993,
"variable": "Injuries",
"value":              5 
},
{
 "X": 6121,
"State": "WV",
"Year": 1994,
"variable": "Injuries",
"value":             12 
},
{
 "X": 6122,
"State": "WV",
"Year": 1995,
"variable": "Injuries",
"value":             14 
},
{
 "X": 6123,
"State": "WV",
"Year": 1996,
"variable": "Injuries",
"value":              2 
},
{
 "X": 6124,
"State": "WV",
"Year": 1997,
"variable": "Injuries",
"value":              5 
},
{
 "X": 6125,
"State": "WV",
"Year": 1998,
"variable": "Injuries",
"value":             16 
},
{
 "X": 6126,
"State": "WV",
"Year": 1999,
"variable": "Injuries",
"value":             12 
},
{
 "X": 6127,
"State": "WV",
"Year": 2000,
"variable": "Injuries",
"value":              3 
},
{
 "X": 6128,
"State": "WV",
"Year": 2001,
"variable": "Injuries",
"value":             11 
},
{
 "X": 6129,
"State": "WV",
"Year": 2002,
"variable": "Injuries",
"value":              5 
},
{
 "X": 6130,
"State": "WV",
"Year": 2003,
"variable": "Injuries",
"value":             24 
},
{
 "X": 6131,
"State": "WV",
"Year": 2004,
"variable": "Injuries",
"value":             10 
},
{
 "X": 6132,
"State": "WV",
"Year": 2005,
"variable": "Injuries",
"value":              4 
},
{
 "X": 6133,
"State": "WV",
"Year": 2006,
"variable": "Injuries",
"value":             10 
},
{
 "X": 6134,
"State": "WV",
"Year": 2007,
"variable": "Injuries",
"value":              1 
},
{
 "X": 6135,
"State": "WV",
"Year": 2008,
"variable": "Injuries",
"value":              2 
},
{
 "X": 6136,
"State": "WV",
"Year": 2009,
"variable": "Injuries",
"value":              4 
},
{
 "X": 6137,
"State": "WV",
"Year": 2010,
"variable": "Injuries",
"value":             12 
},
{
 "X": 6138,
"State": "WV",
"Year": 2011,
"variable": "Injuries",
"value":              3 
},
{
 "X": 6139,
"State": "WY",
"Year": 1950,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6140,
"State": "WY",
"Year": 1951,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6141,
"State": "WY",
"Year": 1952,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6142,
"State": "WY",
"Year": 1953,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6143,
"State": "WY",
"Year": 1954,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6144,
"State": "WY",
"Year": 1955,
"variable": "Injuries",
"value":              3 
},
{
 "X": 6145,
"State": "WY",
"Year": 1956,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6146,
"State": "WY",
"Year": 1957,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6147,
"State": "WY",
"Year": 1958,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6148,
"State": "WY",
"Year": 1959,
"variable": "Injuries",
"value":              1 
},
{
 "X": 6149,
"State": "WY",
"Year": 1960,
"variable": "Injuries",
"value":              3 
},
{
 "X": 6150,
"State": "WY",
"Year": 1961,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6151,
"State": "WY",
"Year": 1962,
"variable": "Injuries",
"value":              4 
},
{
 "X": 6152,
"State": "WY",
"Year": 1963,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6153,
"State": "WY",
"Year": 1964,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6154,
"State": "WY",
"Year": 1965,
"variable": "Injuries",
"value":              1 
},
{
 "X": 6155,
"State": "WY",
"Year": 1966,
"variable": "Injuries",
"value":              6 
},
{
 "X": 6156,
"State": "WY",
"Year": 1967,
"variable": "Injuries",
"value":              3 
},
{
 "X": 6157,
"State": "WY",
"Year": 1968,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6158,
"State": "WY",
"Year": 1969,
"variable": "Injuries",
"value":              1 
},
{
 "X": 6159,
"State": "WY",
"Year": 1970,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6160,
"State": "WY",
"Year": 1971,
"variable": "Injuries",
"value":              3 
},
{
 "X": 6161,
"State": "WY",
"Year": 1972,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6162,
"State": "WY",
"Year": 1973,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6163,
"State": "WY",
"Year": 1974,
"variable": "Injuries",
"value":              2 
},
{
 "X": 6164,
"State": "WY",
"Year": 1975,
"variable": "Injuries",
"value":              1 
},
{
 "X": 6165,
"State": "WY",
"Year": 1976,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6166,
"State": "WY",
"Year": 1977,
"variable": "Injuries",
"value":              1 
},
{
 "X": 6167,
"State": "WY",
"Year": 1978,
"variable": "Injuries",
"value":              2 
},
{
 "X": 6168,
"State": "WY",
"Year": 1979,
"variable": "Injuries",
"value":             40 
},
{
 "X": 6169,
"State": "WY",
"Year": 1980,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6170,
"State": "WY",
"Year": 1981,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6171,
"State": "WY",
"Year": 1982,
"variable": "Injuries",
"value":              7 
},
{
 "X": 6172,
"State": "WY",
"Year": 1983,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6173,
"State": "WY",
"Year": 1984,
"variable": "Injuries",
"value":              1 
},
{
 "X": 6174,
"State": "WY",
"Year": 1985,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6175,
"State": "WY",
"Year": 1986,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6176,
"State": "WY",
"Year": 1987,
"variable": "Injuries",
"value":              4 
},
{
 "X": 6177,
"State": "WY",
"Year": 1988,
"variable": "Injuries",
"value":              2 
},
{
 "X": 6178,
"State": "WY",
"Year": 1989,
"variable": "Injuries",
"value":              2 
},
{
 "X": 6179,
"State": "WY",
"Year": 1990,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6180,
"State": "WY",
"Year": 1991,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6181,
"State": "WY",
"Year": 1992,
"variable": "Injuries",
"value":              0 
},
{
 "X": 6182,
"State": "WY",
"Year": 1993,
"variable": "Injuries",
"value":             28 
},
{
 "X": 6183,
"State": "WY",
"Year": 1994,
"variable": "Injuries",
"value":              4 
},
{
 "X": 6184,
"State": "WY",
"Year": 1995,
"variable": "Injuries",
"value":              4 
},
{
 "X": 6185,
"State": "WY",
"Year": 1996,
"variable": "Injuries",
"value":              5 
},
{
 "X": 6186,
"State": "WY",
"Year": 1997,
"variable": "Injuries",
"value":             69 
},
{
 "X": 6187,
"State": "WY",
"Year": 1998,
"variable": "Injuries",
"value":             29 
},
{
 "X": 6188,
"State": "WY",
"Year": 1999,
"variable": "Injuries",
"value":             17 
},
{
 "X": 6189,
"State": "WY",
"Year": 2000,
"variable": "Injuries",
"value":             48 
},
{
 "X": 6190,
"State": "WY",
"Year": 2001,
"variable": "Injuries",
"value":             19 
},
{
 "X": 6191,
"State": "WY",
"Year": 2002,
"variable": "Injuries",
"value":              7 
},
{
 "X": 6192,
"State": "WY",
"Year": 2003,
"variable": "Injuries",
"value":              7 
},
{
 "X": 6193,
"State": "WY",
"Year": 2004,
"variable": "Injuries",
"value":              9 
},
{
 "X": 6194,
"State": "WY",
"Year": 2005,
"variable": "Injuries",
"value":             25 
},
{
 "X": 6195,
"State": "WY",
"Year": 2006,
"variable": "Injuries",
"value":              6 
},
{
 "X": 6196,
"State": "WY",
"Year": 2007,
"variable": "Injuries",
"value":              9 
},
{
 "X": 6197,
"State": "WY",
"Year": 2008,
"variable": "Injuries",
"value":             14 
},
{
 "X": 6198,
"State": "WY",
"Year": 2009,
"variable": "Injuries",
"value":              5 
},
{
 "X": 6199,
"State": "WY",
"Year": 2010,
"variable": "Injuries",
"value":             32 
},
{
 "X": 6200,
"State": "WY",
"Year": 2011,
"variable": "Injuries",
"value":              8 
} 
]
  
      if(!(opts.type==="pieChart" || opts.type==="sparklinePlus" || opts.type==="bulletChart")) {
        var data = d3.nest()
          .key(function(d){
            //return opts.group === undefined ? 'main' : d[opts.group]
            //instead of main would think a better default is opts.x
            return opts.group === undefined ? opts.y : d[opts.group];
          })
          .entries(data);
      }
      
      if (opts.disabled != undefined){
        data.map(function(d, i){
          d.disabled = opts.disabled[i]
        })
      }
      
      nv.addGraph(function() {
        var chart = nv.models[opts.type]()
          .width(opts.width)
          .height(opts.height)
          
        if (opts.type != "bulletChart"){
          chart
            .x(function(d) { return d[opts.x] })
            .y(function(d) { return d[opts.y] })
        }
          
         
        
          
        

        
        
        
      
       d3.select("#" + opts.id)
        .append('svg')
        .datum(data)
        .transition().duration(500)
        .call(chart);

       nv.utils.windowResize(chart.update);
       return chart;
      });
    };
</script>


---

