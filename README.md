## Extended-Kalman-Filter-for-SDR-Based-Digital-Communication-Systems

In the realm of signal processing for software-defined radio (SDR) systems, the Kalman filter emerges as a pivotal tool, particularly renowned for its efficacy in mitigating outlier effects that frequently occur at the transmitting and receiving ends of SDR-based communications. While the standard Kalman filter excels in handling linear system models with Gaussian noise, its implementation within the LabVIEW and LabVIEW NXG environments is traditionally limited to its simplest form, which primarily addresses scenarios with linear dynamics and measurement models.

Acknowledging these limitations, our code introduces an advanced variant: the Extended Kalman Filter (EKF). The EKF is adept at dealing with non-linear system dynamics and measurement models – a common characteristic in practical SDR scenarios. This advanced algorithm approximates non-linear functions through a linearization process, thereby extending the utility of the classic Kalman filter to a broader range of SDR applications.

This implementation of the Extended Kalman Filter is designed to be versatile, and capable of receiving and processing input arguments in both 1D and 2D spaces. Such flexibility enables the EKF to adapt to various SDR scenarios, whether it involves straightforward signal tracking or more complex spatial estimations.

Our EKF code has been optimized for SDR devices, ensuring seamless integration and enhanced performance of SDR-based digital communication systems. 
