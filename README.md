# Image_Compression
Compressing an image using the k-means algorithm on the image’s pixels. 
Each pixel is replaced by its centroid.
The image is normalized, reshaped and then the algorithm is trained on it.
The code runs for 10 iterations for each value of k where k = 2, 4, 8, 16.

***Example:*** 

<table>
<thead>
<tr>
<th>Original</th>
<th>Compressed with 2 colors (K=2)</th>
<th>Compressed with 4 colors (K=4)</th>
</tr>
</thead>
<tbody>
<tr>
<td><img src="https://github.com/DoreenVas/Image_Compression/blob/master/pictures/original.png"/></td>
<td><img src="https://github.com/DoreenVas/Image_Compression/blob/master/pictures/k2.png"/></td>
<td><img src="https://github.com/DoreenVas/Image_Compression/blob/master/pictures/k4.png"/></td>
</tr>
<tr>
<th>Compressed with 8 colors (K=8)</th>
<th>Compressed with 16 colors (K=16)</th>
</tr>
<tr>
<td><img src="https://github.com/DoreenVas/Image_Compression/blob/master/pictures/k8.png"/></td>
<td><img src="https://github.com/DoreenVas/Image_Compression/blob/master/pictures/k16.png"/></td>
</tr>
</tbody>
</table>
