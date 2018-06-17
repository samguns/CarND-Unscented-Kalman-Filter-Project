# Unscented Kalman Filter Project
Self-Driving Car Engineer Nanodegree Program

[image1]: ./images/radar_nis.png
[image2]: ./images/ladar_nis.png
[image3]: ./images/rmse.png

I used the `./no_sim > ../analyze_nis/nis.csv` to generate NIS datas for determining longitudinal acceleration and yaw acceleration process noises. The final std_a_ for my project is 2m/s^2, std_yawdd_ is 0.3rad/s^2.
![image1]

![image2]


And the `RMSE` I can get is `[0.0793, 0.0845, 0.1978, 0.1933]`.
![image3]