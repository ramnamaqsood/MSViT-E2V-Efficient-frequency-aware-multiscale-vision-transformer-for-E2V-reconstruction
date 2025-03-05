# MSViT-E2V: Efficient frequency-aware multiscale vision transformer for E2V reconstruction
Visual Results on paper "MSViT-E2V: Efficient frequency-aware multiscale vision transformer for E2V reconstruction" to evaluate the temporal stability of proposed method.

## To-Do List

- [x] Upload Results  
- [ ] Code (Will be uploaded upon acceptance of the paper)
- [ ] Training Dataset (Will be uploaded upon acceptance of the paper)


## Model Comparison
### Sequence of images from class bike_bay of HQF dataset
The consecutive images shows that MSViT-E2V (Ours) can reconstruct textual details more efficiently than SOTA methods. 

![](videos/result_bike_bay.png)
### Sequence of images from class desk of HQF dataset
The consecutive images shows the performance of  MSViT-E2V (Ours) against two benchmark methods. It can be seen that the reconstruted images with our method has less goosting artifacts and more details.

![](videos/desk_output.png)
### Sequence of images from class poster_6dof of ECD dataset
Overall our model has better reconstruction quality.

![result_3](videos/poster_6dof.png)
### Sequence of images from class dynamic_6dof of ECD_fast dataset
In fast camera motion our model still reconstruct better images than ET-Net and E2VID methds.

![fig_2](videos/dynamic.png)


### Video sequence from class office_zigzag of ECD dataset.

| ET-Net | E2VID | OURS |
|--------|-------|------|
| ![](videos/ET-Net.gif) | ![](videos/E2VID.gif) | ![](videos/OURS.gif) |

