# face-makeup.PyTorch
Lip, eyebrow and hair color editor using face parsing maps.

<table>

<tr>
<th>Original</th>
<th>Make up</th>
</tr>

<!-- Line 1: Original Input -->
<tr>
<td><img src="makeup/116_ori.png" height="256" width="256" alt="Original Input"></td>
<td><img src="makeup/116_change.jpg" height="256" width="256" alt="Output"></td>
</tr>

</table>

### Using PyTorch 1.0 and python 3.x

## Demo
Change hair, eyebrow and lip color:
```Shell
python makeup.py --img-path imgs/116.jpg
```
### Try to use other colors:
Change the color list in **makeup.py**(line 83)
```
colors = [[230, 50, 20], [20, 70, 180], [20, 70, 180]]
```
### Train face parsing model (optional)
Follow this repo [zllrunning/face-parsing.PyTorch](https://github.com/zllrunning/face-parsing.PyTorch)
