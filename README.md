# Display Mode: Time
Supported formats:

<table>
<tr>
<td><b>Format</b></td>
<td><b>Description</b></td>
<td><b>Example</b></td>
</tr>
<tr>
<td>d</td>
<td>date</td>
<td>1</td>
</tr>
<tr>
<td>dd</td>
<td>date with leading zero</td>
<td>01</td>
</tr>
<tr>
<td>M</td>
<td>month</td>
<td>3</td>
</tr>
<tr>
<td>MM</td>
<td>month with leading zero</td>
<td>03</td>
</tr>
<tr>
<td>yy</td>
<td>2-digits year</td>
<td>24</td>
</tr>
<tr>
<td>yyyy</td>
<td>full year</td>
<td>2024</td>
</tr>
<tr>
<td>h</td>
<td>12-hour</td>
<td>8</td>
</tr>
<tr>
<td>hh</td>
<td>12-hour with leading zero</td>
<td>08</td>
</tr>
<tr>
<td>H</td>
<td>24-hour</td>
<td>20</td>
</tr>
<tr>
<td>HH</td>
<td>24-hour with leading zero</td>
<td>20</td>
</tr>
<tr>
<td>m</td>
<td>minute</td>
<td>5</td>
</tr>
<tr>
<td>mm</td>
<td>minute with leading zero</td>
<td>05</td>
</tr>
<tr>
<td>s</td>
<td>second</td>
<td>3</td>
</tr>
<tr>
<td>ss</td>
<td>second with leading zero</td>
<td>03</td>
</tr>
<tr>
<td>t</td>
<td>a/p</td>
<td>p</td>
</tr>
<tr>
<td>tt</td>
<td>am/pm</td>
<td>pm</td>
</tr>
</table>

# Display Mode: Pixel Art
Pixel Art is an Array of ones and zeroes in an Array, One represents light on and Zero represents light off. 
Each group of Ones and Zeroes is equals to each row on your Matrix.

For example: Dino on my 16x16 Matrix
```
[
[0,0,0,0,0,0,0,0,0,1,1,1,1,1,1,0],
[0,0,0,0,0,0,0,0,1,1,0,1,1,1,1,1],
[0,0,0,0,0,0,0,0,1,1,1,1,1,1,1,1],
[0,0,0,0,0,0,0,0,1,1,1,1,1,1,1,1],
[0,0,0,0,0,0,0,0,1,1,1,1,1,0,0,0],
[0,0,0,0,0,0,0,0,1,1,1,1,1,0,0,0],
[1,0,0,0,0,0,0,1,1,1,1,1,1,1,1,0],
[1,1,0,0,0,0,1,1,1,1,1,1,0,0,0,0],
[1,1,1,0,0,1,1,1,1,1,1,1,0,0,0,0],
[0,1,1,1,1,1,1,1,1,1,1,1,1,1,0,0],
[0,0,1,1,1,1,1,1,1,1,1,1,0,1,0,0],
[0,0,0,1,1,1,1,1,1,1,1,0,0,0,0,0],
[0,0,0,0,1,1,1,0,1,1,0,0,0,0,0,0],
[0,0,0,0,1,1,0,0,0,1,0,0,0,0,0,0],
[0,0,0,0,1,0,0,0,0,1,1,0,0,0,0,0],
[0,0,0,0,1,1,0,0,0,0,0,0,0,0,0,0]
]
```
