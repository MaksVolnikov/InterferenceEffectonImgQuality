# InterferenceEffectonImgQuality
This module calculates the effect of the MSE PSNR and SSIM coefficients on the final image quality and records the results in an Excel table in xlsx format
According to the MSE indicator in the final table, it can be said that noise has the greatest effect on the difference in images, since the value becomes very large, and with an increase in the number of details in the photo, the MSE value also increases with distortion.
According to the PSNR indicator in the final table, we can say that with increasing detail in the photos, this parameter decreases, and noise also strongly affects this parameter, which leads to a sharp decline in values.
According to the SSIM indicator in the final table, it can be said that blurring and saving with loss of quality has the least effect on the difference with the original image, since the value is close to 1, but with increasing detail, this difference becomes more and more. Noise has the maximum effect on the difference in images.
The calculation of all three indicators for the presented images  is given in the table below:

**************************************
| Group | Basefile | Diffile | MSE | PSNR | SSIM |
|---:|:---:|:---:|:---:|:---:|:---|
|0|    |Small|   |_1.jpg|           |_1_blur.jpg|    |221.086|  |24.685|  |0.913|
|1|    |Small|   |_1.jpg|  |_1_impulse_noise.jpg|  |10862.836|   |7.771|  |0.045|
|2|    |Small|   |_1.jpg|  |_1_low_quality_1.jpg|    |254.594|  |24.072|  |0.759|
|3|    |Small|   |_2.jpg|           |_2_blur.jpg|     |66.296|  |29.916|  |0.897|
|4|    |Small|   |_2.jpg|  |_2_impulse_noise.jpg|   |6886.964|   |9.751|  |0.026|
|5|    |Small|   |_2.jpg|  |_2_low_quality_1.jpg|    |347.115|  |22.726|  |0.749|
|6|    |Small|   |_3.jpg|           |_3_blur.jpg|     |11.024|  |37.707|  |0.973|
|7|    |Small|   |_3.jpg|  |_3_impulse_noise.jpg|   |6957.270|   |9.706|  |0.013|
|8|    |Small|   |_3.jpg|  |_3_low_quality_1.jpg|    |314.338|  |23.157|  |0.865|
|9|   |Middle|   |_1.jpg|           |_1_blur.jpg|    |362.640|  |22.536|  |0.589|
|10|  |Middle|   |_1.jpg|  |_1_impulse_noise.jpg|   |7657.863|   |9.290|  |0.083|
|11|  |Middle|   |_1.jpg|  |_1_low_quality_1.jpg|    |604.980|  |20.313|  |0.551|
|12|  |Middle|   |_2.jpg|           |_2_blur.jpg|    |103.334|  |27.988|  |0.723|
|13|  |Middle|   |_2.jpg|  |_2_impulse_noise.jpg|   |7007.161|   |9.675|  |0.033|
|14|  |Middle|   |_2.jpg|  |_2_low_quality_1.jpg|    |376.054|  |22.378|  |0.564|
|15|  |Middle|   |_3.jpg|           |_3_blur.jpg|    |139.103|  |26.697|  |0.729|
|16|  |Middle|   |_3.jpg|  |_3_impulse_noise.jpg|   |7022.315|   |9.666|  |0.038|
|17|  |Middle|   |_3.jpg|  |_3_low_quality_1.jpg|    |382.360|  |22.306|  0.622|
|18|   |Large|   |_1.jpg|           |_1_blur.jpg|   |3642.909|  |12.516|  |0.373|
|19|   |Large|   |_1.jpg|  |_1_impulse_noise.jpg|  |10883.674|   |7.763|  |0.301|
|20|   |Large|   |_1.jpg|  |_1_low_quality_1.jpg|   |1313.713|  |16.946|  |0.815|
|21|   |Large|   |_2.jpg|           |_2_blur.jpg|    |244.539|  |24.247|  0.668|
|22|   |Large|   |_2.jpg|  |_2_impulse_noise.jpg|  |10641.929|   |7.861|  |0.040|
|23|   |Large|   |_2.jpg|  |_2_low_quality_1.jpg|    |473.021|  |21.382|  |0.547|
|24|   |Large|   |_3.jpg|           |_3_blur.jpg|    |429.904|  |21.797|  |0.588|
|25|   |Large|   |_3.jpg|  |_3_impulse_noise.jpg|   |8035.840|   |9.080|  |0.092|
|26|   |Large|   |_3.jpg|  |_3_low_quality_1.jpg|    |523.850|  |20.939|  |0.591|
