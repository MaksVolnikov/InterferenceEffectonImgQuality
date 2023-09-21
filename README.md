# InterferenceEffectonImgQuality
This module calculates the effect of the MSE PSNR and SSIM coefficients on the final image quality and records the results in an Excel table in xlsx format
According to the MSE indicator in the final table, it can be said that noise has the greatest effect on the difference in images, since the value becomes very large, and with an increase in the number of details in the photo, the MSE value also increases with distortion.
According to the PSNR indicator in the final table, we can say that with increasing detail in the photos, this parameter decreases, and noise also strongly affects this parameter, which leads to a sharp decline in values.
According to the SSIM indicator in the final table, it can be said that blurring and saving with loss of quality has the least effect on the difference with the original image, since the value is close to 1, but with increasing detail, this difference becomes more and more. Noise has the maximum effect on the difference in images.
The calculation of all three indicators for the presented images  is given in the table below:

	Group	BaseFile	DifFile	MSE	PSNR	SSIM
0	Small	_1.jpg	_1_blur.jpg	221.09	24.69	0.91
1	Small	_1.jpg	_1_impulse_noise.jpg	10,862.84	7.77	0.05
2	Small	_1.jpg	_1_low_quality_1.jpg	254.59	24.07	0.76
3	Small	_2.jpg	_2_blur.jpg	66.30	29.92	0.90
4	Small	_2.jpg	_2_impulse_noise.jpg	6,886.96	9.75	0.03
5	Small	_2.jpg	_2_low_quality_1.jpg	347.12	22.73	0.75
6	Small	_3.jpg	_3_blur.jpg	11.02	37.71	0.97
7	Small	_3.jpg	_3_impulse_noise.jpg	6,957.27	9.71	0.01
8	Small	_3.jpg	_3_low_quality_1.jpg	314.34	23.16	0.87
9	Middle	_1.jpg	_1_blur.jpg	362.64	22.54	0.59
10	Middle	_1.jpg	_1_impulse_noise.jpg	7,657.86	9.29	0.08
11	Middle	_1.jpg	_1_low_quality_1.jpg	604.98	20.31	0.55
12	Middle	_2.jpg	_2_blur.jpg	103.33	27.99	0.72
13	Middle	_2.jpg	_2_impulse_noise.jpg	7,007.16	9.68	0.03
14	Middle	_2.jpg	_2_low_quality_1.jpg	376.05	22.38	0.56
15	Middle	_3.jpg	_3_blur.jpg	139.10	26.70	0.73
16	Middle	_3.jpg	_3_impulse_noise.jpg	7,022.32	9.67	0.04
17	Middle	_3.jpg	_3_low_quality_1.jpg	382.36	22.31	0.62
18	Large	_1.jpg	_1_blur.jpg	3,642.91	12.52	0.37
19	Large	_1.jpg	_1_impulse_noise.jpg	10,883.67	7.76	0.30
20	Large	_1.jpg	_1_low_quality_1.jpg	1,313.71	16.95	0.82
21	Large	_2.jpg	_2_blur.jpg	244.54	24.25	0.67
22	Large	_2.jpg	_2_impulse_noise.jpg	10,641.93	7.86	0.04
23	Large	_2.jpg	_2_low_quality_1.jpg	473.02	21.38	0.55
24	Large	_3.jpg	_3_blur.jpg	429.90	21.80	0.59
25	Large	_3.jpg	_3_impulse_noise.jpg	8,035.84	9.08	0.09
26	Large	_3.jpg	_3_low_quality_1.jpg	523.85	20.94	0.59
