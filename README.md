# 1. Qualitative Toy Experiments
## Optimal Transport Guided Pair
Figure 1.1 Left: A continuous Gaussian source distribution (colored level sets) and a multi-modal target samples from 8Gaussian distribution (yellow). Right: Samples from source distribution (yellow), paired samples (green) and unpired samples (blue) from target distribution.
<table>
<tr>
<td><center><img src="asset/t81.png" width="200"/></center></td>
<td><center><img src="asset/t813.png" width="200"/></center></td>
</tr>
</table>
## Compatibility Function Guided Diffusion
Figure 1.2 Illustration of the 8gaussians and swissroll dataset (left) and the generation result of diffusion model (right).
<table>
<tr>
<td><center><img src="asset/t8d.png" width="200"/></center></td>
<td><center><img src="asset/t8s.png" width="175"/></center></td>
</tr>
<td><center><img src="asset/tsd.png" width="200"/></center></td>
<td><center><img src="asset/tss.png" width="175"/></center></td>
</tr>
</table>

# 2. Pixel-based Romomimic Tasks
Figure 2 Learning curves of online fine-tuning with various methods on pixel-based romomimic tasks.
<table>
<tr>
<td><center><img src="asset/Exp1_square_pixel.jpg" width="200"/></center></td>
<td><center><img src="asset/Exp1_can_pixel.jpg" width="200"/></center></td>
<td><center><img src="asset/Exp1_can_pixel.jpg" width="200"/></center></td>
</tr>
</table>

# 3. Reporting of Wall-Clock Times
|     | OTPR | DPPO     | IDQL| DQL |
| :---        |    :----:   |          :---: |   :---: | ---: |
| Robomimic-Can     | 26.5min      | 24.6min   | 23.3min| 21.2min |
| Robomimic-Square   | 54.4min        | 50.8min      | 49.2min| 50.3min |
<!-- | Franka-Kitchen-complete   | 75.4min      | 67.8min  | 67.1min | 64.1min | -->