# IDEAuthDataset
Dataset for IDeAuth : A novel behavioral biometric-based implicit deauthentication scheme for smartphones

https://www.sciencedirect.com/science/article/abs/pii/S0167865522000770

# Dataset Description
IDeAuth Dataset contains boardcast data from 52 users. However, we discarded eleven testers due to insufficient data and used data of 41 users in our experiment. Among these 41 testers, 26 were males, 15 were females with 36 right-handed and 5 left-handed. Majority of testers were situated in Asia (19) and Europe (16) while per- forming the experiment, with 27 were between 20 to 30, 12 were between 30 to 40, and 2 were above 40.

# Features Details
6 motion sensors are used for features acquisition:<br />
1. Physical sensors - the accelerometer (Accel), the gravity sensor (Gravity), the gyroscope (Gyro), and the magnetometer (Magnet).<br />
2. Virtual/derieved sensors - the high-pass sensor (HPS) and the low-pass sensor (LPS).<br />

A. From each sensor, 3 raw streams are acquired (X, Y and Z) and a magnitude is computed mathematically from it. <br />
B. From each stream, 4 statstical features are determined that are Mean (μ), Standard Deviation (σ), Skewness (s), and Kurtosis (k) with 16
statistical features per sensor.<br />
C. From 6 sensors, 16 x 9 = 96 sensors are obtained.<br />
D. Overall, there are 96 statistical features per sample.

**This can be used as header for csv file.**

Accel_KurtX	Accel_KurtY	Accel_KurtZ	Accel_KurtMag	Accel_MeanMag	Accel_MeanX	Accel_MeanY	Accel_MeanZ	Accel_SkewMag	Accel_SkewX	Accel_SkewY	Accel_SkewZ	Accel_STDMag	Accel_STDX	Accel_STDY	Accel_STDZ	LPF_KurtX	LPF_KurtY	LPF_KurtZ	LPF_KurtMag	LPF_MeanMag	LPF_MeanX	LPF_MeanY	LPF_MeanZ	LPF_SkewMag	LPF_SkewX	LPF_SkewY	LPF_SkewZ	LPF_STDMag	LPF_STDX	LPF_STDY	LPF_STDZ	HPF_KurtX	HPF_KurtY	HPF_KurtZ	HPF_KurtMag	HPF_MeanMag	HPF_MeanX	HPF_MeanY	HPF_MeanZ	HPF_SkewMag	HPF_SkewX	HPF_SkewY	HPF_SkewZ	HPF_STDMag	HPF_STDX	HPF_STDY	HPF_STDZ	Magnet_KurtX	Magnet_KurtY	Magnet_KurtZ	Magnet_KurtMag	Magnet_MeanMag	Magnet_MeanX	Magnet_MeanY	Magnet_MeanZ	Magnet_SkewMag	Magnet_SkewX	Magnet_SkewY	Magnet_SkewZ	Magnet_STDMag	Magnet_STDX	Magnet_STDY	Magnet_STDZ	Gyro_KurtX	Gyro_KurtY	Gyro_KurtZ	Gyro_KurtMag	Gyro_MeanMag	Gyro_MeanX	Gyro_MeanY	Gyro_MeanZ	Gyro_SkewMag	Gyro_SkewX	Gyro_SkewY	Gyro_SkewZ	Gyro_STDMag	Gyro_STDX	Gyro_STDY	Gyro_STDZ	Gravity_KurtX	Gravity_KurtY	Gravity_KurtZ	Gravity_KurtMag	Gravity_MeanMag	Gravity_MeanX	Gravity_MeanY	Gravity_MeanZ	Gravity_SkewMag	Gravity_SkewX	Gravity_SkewY	Gravity_SkewZ	Gravity_STDMag	Gravity_STDX	Gravity_STDY	Gravity_STDZ

# Citations
Please cite our following papers to use the dataset.

@article{gupta2022ideauth,<br />
  title={IDeAuth: A novel behavioral biometric-based implicit deauthentication scheme for smartphones},<br />
  author={Gupta, Sandeep and Kumar, Rajesh and Kacimi, Mouna and Crispo, Bruno},<br />
  journal={Pattern Recognition Letters},<br />
  volume={157},<br />
  pages={8--15},<br />
  year={2022},<br />
  publisher={Elsevier}<br />
}

@phdthesis{gupta2020next,<br />
  title={Next-generation user authentication schemes for iot applications},<br />
  author={Gupta, Sandeep},<br />
  year={2020},<br />
  school={PhD thesis, Ph. D. dissertation, University of Trento, Italy}<br />
}

