# SoML-50

Handwritten mathematical expression dataset for value evaluation and notation type classification.

The dataset consists of 50,000 images of dimensions 384 x 128 (w x h), with each image having a expression in either the prefix (eg: +12), postfix (eg: 12+) or infix (eg: 1+2) notations. The characters in the image are evenly spaced, such that every one-third of the image has a single character in it. 

Some sample images from the dataset can be seen below: 

<div align="center">
	<img src="examples/100.jpg" width="45%"/>
	<img src="examples/311.jpg" width="45%"/>
	<hr>
	<img src="examples/9991.jpg" width="45%"/>
	<img src="examples/34788.jpg" width="45%"/>
	<hr>
	<img src="examples/34651.jpg" width="45%"/>
	<img src="examples/34611.jpg" width="45%"/>
</div>

---

The annotations of the dataset contain the label (prefic, postfix or infix) and the value obtained after evaluation of the expression

<table align="center">
	<tr>
		<th>Image</th>
		<th>Label</th>
		<th>Value</th>
	</tr>
	<tr>
		<td>100.jpg</td>
		<td>prefix</td>
		<td>0</td>
	</tr>
	<tr>
		<td>311.jpg</td>
		<td>postfix</td>
		<td>3</td>
	</tr>
	<tr>
		<td>9991.jpg</td>
		<td>prefix</td>
		<td>0</td>
	</tr>
	<tr>
		<td>34788.jpg</td>
		<td>infix</td>
		<td>7</td>
	</tr>
	<tr>
		<td>34651.jpg</td>
		<td>prefix</td>
		<td>16</td>
	</tr>
	<tr>
		<td>34611.jpg</td>
		<td>infix</td>
		<td>28</td>
	</tr>

</table>

---

## Download

The dataset can be downloaded from [google drive](https://drive.google.com/file/d/1rAYZBd3z5FA9IjxiCPa-PbAGuyWChwdX/view?usp=sharing). On extracting, it has a directory 'data' with all images and a 'annotations.csv' file with the labels and values of each image. 