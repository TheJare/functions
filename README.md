# Useful basis functions
This is an in-progress list of interesting basis functions, functions that map from the interval [0,1] to an interval in the general vicinity of [0,1], and which can be useful for many effects and transitions.

Thanks to Tom Forsyth and Jim Scott for ideas. Please feel free to tweet more suggestions to [@TheJare](https://twitter.com/TheJare).

## Humps
These start and end at zero, and generally reach around 1 at some point in the interval.

[y = x * (1-x) * 4](https://www.google.com/search?q=y%3Dx*(1-x)*4+from+-0.2+to+1.3)
![](hump.png)
[y = sin(x*pi)](https://www.google.com/search?q=y%3Dsin(x*pi)+from+-0.2+to+1.3)
![](humpsin.png)
<a href="https://www.google.com/search?q=y%3Dx*x*(1-x)*(1-x)*16+from+-0.2+to+1.3"><p>y = x*x*(1-x)*(1-x)*16</p>
![](smoothhump.png)
<a href="https://www.google.com/search?q=y%3D-7*x*(1-x)*(x-1)+from+-0.2+to+1.3"><p>y = -7 * x*(1-x)*(x-1)</p>
![](cubichump.png)
</div></div>

<p><span class="btn" onclick="toggleVisible('transitions')"><span class="cat">Transitions</span> <span id="transitionsbtn" class="btnbox">[-]</span></span></p>
<p>These start at zero and end at one, but with a more interesting trajectory than just linear.</p>
<div id="transitions"><div class="eqs">
<p>Raising the right side to a power &gt; 1 will push the curve towards the right, &lt; 1 towards the left.</p>
<a href="https://www.google.com/search?q=y%3Dx*x+from+-0.2+to+1.3"><p>y = x * x</p>
<img src="x2.png"></a>
<a href="https://www.google.com/search?q=y%3Dsqrt(x)+from+-0.2+to+1.3"><p>y = sqrt(x)</p>
<img src="sqrtx.png"></a>
<a href="https://www.google.com/search?q=y%3D-2*x*x*x+%2B+3*x*x+from+-0.2+to+1.3"><p>y = -2*x*x*x + 3*x*x</p>
<img src="cubicstep.png"></a>
<a href="https://www.google.com/search?q=y%3D-5*x*(1-x)*(x-1)%2Bx+from+-0.2+to+1.3"><p>y = -5 * x*(1-x)*(x-1) + x</p>
<img src="outbackin.png"></a>
</div></div>
