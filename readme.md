#dither.js

A javascript library which transforms an <img> element 
into a dithered image using a fixed palette.

###Usage:
HTML:
```
<img src="..." class="dither" />
```

JS:
```
new Dithering('.dither'[,options]);
```

options are defined as:
```
var options = {
    "step": n // The step for the pixel quantization n = 1,2,3...
    "palette": palette // an array of colors as rgb arrays
    "className": "dither" // can be whatever class used in the constructor
    "algorithm": "ordered" // can be "ordered" or "errorDiffusion"
};
```

author 2014 [Daniele Piccone](http://www.danielepiccone.com)

license [GPL](https://gnu.org/licenses/gpl.html)