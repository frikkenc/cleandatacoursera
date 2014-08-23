<h1>Codebook for coursera Cleaning Data Project</h1>

In addition to the descriptions below, the variable data follows a naming convention to ease understanding.  
Variables that begin with a “t” are time domain signals.  Those with an “f” are frequency domain signals.  
Variables that contain “acc” are from the accelometer, those that contain “gyro” are from the gyroscope 3-axial raw data.

Variables that contain “mean” have the mean of the variable in the relevant time period.  Those that contain “std” have the standard deviation.

Finally the last portion may contain an X, Y, or Z which indicates the axis measured.</br>

<h2>Subject</h2>
	This is the subject identifier, a numeric 1-30.
<h2>Activity</h2>
	Activity Type cardinal value with one of these six categories
		Walking
		Walking Upstairs
		Walking Downstairs
		Sitting
		Standing
		Laying

<h2>tBodyAcc_mean_X, tBodyAcc_mean_Y, tBodyAcc_mean_Z</h2>
Means of the body acceleration data from the accelerometer X, Y, and Z axis respectively after passed through filtering. These time domain signals were captured at a constant rate of 50 Hz.  Then they were filtered using a median filter and a 3rd order low pass Butterworth filter with a corner frequency of 20 Hz to remove noise.  The acceleration signal was then separated into body and gravity acceleration signals using another low pass Butterworth filter with a corner frequency of 0.3 Hz.

<h2>tBodyAcc_std_X, tBodyAcc_std_Y, tBodyAcc_std_Z</h2>
Standard Deviation of the body acceleration data from the accelerometer X, Y, and Z axis respectively after passed through filtering. These time domain signals were captured at a constant rate of 50 Hz.  Then they were filtered using a median filter and a 3rd order low pass Butterworth filter with a corner frequency of 20 Hz to remove noise.  The acceleration signal was then separated into body and gravity acceleration signals using another low pass Butterworth filter with a corner frequency of 0.3 Hz.

<h2>tGravityAcc</h2>
This category of variables comes from the accelerometer.  These time domain signals (prefix 't' to denote time) were captured at a constant rate of 50 Hz.  Then they were filtered using a median filter and a 3rd order low pass Butterworth filter with a corner frequency of 20 Hz to remove noise.  
The acceleration signal was then separated into body and gravity acceleration signals (tBodyAcc-XYZ and tGravityAcc-XYZ) using another low pass Butterworth filter with a corner frequency of 0.3 Hz.  These values represent the gravity acceleration signals X, Y, and Z variables from the final Butterworth filter pass.

<h2>tGravityAcc_mean_X, tGravityAcc_mean_Y, tGravityAcc_mean_Z</h2>
Means of the gravity acceleration data from the accelerometer X, Y, and Z axis respectively after passed through filtering. These time domain signals were captured at a constant rate of 50 Hz.  Then they were filtered using a median filter and a 3rd order low pass Butterworth filter with a corner frequency of 20 Hz to remove noise.  The acceleration signal was then separated into body and gravity acceleration signals using another low pass Butterworth filter with a corner frequency of 0.3 Hz.

<h2>tGravityAcc_std_X, tGravityAcc_std_Y, tGravityAcc_std_Z</h2>
Standard deviations of the gravity acceleration data from the accelerometer X, Y, and Z axis respectively after passed through filtering. These time domain signals were captured at a constant rate of 50 Hz.  Then they were filtered using a median filter and a 3rd order low pass Butterworth filter with a corner frequency of 20 Hz to remove noise.  The acceleration signal was then separated into body and gravity acceleration signals using another low pass Butterworth filter with a corner frequency of 0.3 Hz.

<h2>tBodyAccJerk_mean_X, tBodyAccJerk_mean_Y, tBodyAccJerk_mean_Z</h2>
Means of the body acceleration jerk data from the accelerometer X, Y, and Z axis respectively after passed through filtering. The time domain signals were captured at a constant rate of 50 Hz.  Then they were filtered using a median filter and a 3rd order low pass Butterworth filter with a corner frequency of 20 Hz to remove noise.  The acceleration signal was then separated into body and gravity acceleration signals using another low pass Butterworth filter with a corner frequency of 0.3 Hz.  Finally the jerk signals were derived in time from the body linear acceleration and angular velocity.

<h2>tBodyAccJerk_std_X, tBodyAccJerk_std_Y, tBodyAccJerk_std_Z</h2>
Standard deviation of the body acceleration jerk data from the accelerometer X, Y, and Z axis respectively after passed through filtering. The time domain signals were captured at a constant rate of 50 Hz.  Then they were filtered using a median filter and a 3rd order low pass Butterworth filter with a corner frequency of 20 Hz to remove noise.  The acceleration signal was then separated into body and gravity acceleration signals using another low pass Butterworth filter with a corner frequency of 0.3 Hz.  Finally the jerk signals were derived in time from the body linear acceleration and angular velocity.

<h2>tBodyGyro_mean_X, tBodyGyro_mean_Y, tBodyGyro_mean_Z</h2>
Means of the body acceleration data from the gyroscope 3-axial X, Y, and Z axis respectively after passed through filtering. These time domain signals were captured at a constant rate of 50 Hz.  Then they were filtered using a median filter and a 3rd order low pass Butterworth filter with a corner frequency of 20 Hz to remove noise.  The acceleration signal was then separated into body and gravity acceleration signals using another low pass Butterworth filter with a corner frequency of 0.3 Hz.

<h2>tBodyGyro_std_X, tBodyGyro_std_Y, tBodyGyro_std_Z</h2>
Standard deviation of the body acceleration data from the gyroscope 3-axial X, Y, and Z axis respectively after passed through filtering. These time domain signals were captured at a constant rate of 50 Hz.  Then they were filtered using a median filter and a 3rd order low pass Butterworth filter with a corner frequency of 20 Hz to remove noise.  The acceleration signal was then separated into body and gravity acceleration signals using another low pass Butterworth filter with a corner frequency of 0.3 Hz.

<h2>tBodyGyroJerk_mean_X, tBodyGyroJerk_mean_Y, tBodyGyroJerk_mean_Z</h2>
Means of the body acceleration jerk data from the gyroscope 3-axial X, Y, and Z axis respectively after passed through filtering. The time domain signals were captured at a constant rate of 50 Hz.  Then they were filtered using a median filter and a 3rd order low pass Butterworth filter with a corner frequency of 20 Hz to remove noise.  The acceleration signal was then separated into body and gravity acceleration signals using another low pass Butterworth filter with a corner frequency of 0.3 Hz.  Finally the jerk signals were derived in time from the body linear acceleration and angular velocity.

<h2>tBodyGyroJerk_std_X, tBodyGyroJerk_std_Y, tBodyGyroJerk_std_Z</h2>
Stadard deviations of the body acceleration jerk data from the gyroscope 3-axial X, Y, and Z axis respectively after passed through filtering. The time domain signals were captured at a constant rate of 50 Hz.  Then they were filtered using a median filter and a 3rd order low pass Butterworth filter with a corner frequency of 20 Hz to remove noise.  The acceleration signal was then separated into body and gravity acceleration signals using another low pass Butterworth filter with a corner frequency of 0.3 Hz.  Finally the jerk signals were derived in time from the body linear acceleration and angular velocity.

<h2>tBodyAccMag_mean</h2>
Mean of the magnitude of the tBodyAcc signals calculated from the using the Euclidian norm.
tBodyAccMag_std	
Standard deviation of the magnitude of the tBodyAcc signals calculated from the using the Euclidian norm.

<h2>tGravityAccMag_mean</h2>
Mean of the magnitude of the tGravityAcc signals calculated from the using the Euclidian norm.

<h2>tGravityAccMag_std</h2>
Standard deviation of the magnitude of the tGravityAcc signals calculated from the using the Euclidian norm.

<h2>tBodyAccJerkMag_mean</h2>
Mean of the magnitude of the tBodyAccJerk signals calculated from the using the Euclidian norm.

<h2>tBodyAccJerkMag_std</h2>
Standard Deviation of the magnitude of the tBodyAccJerk signals calculated from the using the Euclidian norm.

<h2>tBodyGyroMag_mean</h2>
Mean of the magnitude of the tGravityGyro signals calculated from the using the Euclidian norm.

<h2>tBodyGyroMag_std</h2>
Standard deviation of the magnitude of the tGravityGyro signals calculated from the using the Euclidian norm.

<h2>tBodyGyroJerkMag_mean</h2>
Mean of the magnitude of the tGravityGyroJerk signals calculated from the using the Euclidian norm.

<h2>tBodyGyroJerkMag_std</h2>
Standard Deviation of the magnitude of the tGravityGyroJerk signals calculated from the using the Euclidian norm.

<h2>fBodyAcc_mean_X, fBodyAcc_mean_Y, fBodyAcc_mean_Z</h2>
The mean of a frequency domain which was the result of Fast Fourier Transform (FFT) applied to the body accelerometer signal.  These correspond to the X, Y, and Z axis.

<h2>fBodyAcc_std_X, fBodyAcc_std_Y, fBodyAcc_std_Z</h2>
The standard deviation of a frequency domain which was the result of Fast Fourier Transform (FFT) applied to the body accelerometer signal.  These correspond to the X, Y, and Z axis.

<h2>fBodyAcc_meanFreq_X, fBodyAcc_meanFreq_Y, fBodyAcc_meanFreq_Z</h2>
The mean weighted average of a frequency domain which was the result of Fast Fourier Transform (FFT) applied to the body accelerometer signal.  These correspond to the X, Y, and Z axis.

<h2>fBodyAccJerk_mean_X, fBodyAccJerk_mean_Y, fBodyAccJerk_mean_Z</h2>
The mean of a frequency domain which was the result of Fast Fourier Transform (FFT) applied to the body accelerometer jerk signal.  These correspond to the X, Y, and Z axis.

<h2>fBodyAccJerk_std_X, fBodyAccJerk_std_Y, fBodyAccJerk_std_Z</h2>
The standard deviation of a frequency domain which was the result of Fast Fourier Transform (FFT) applied to the body accelerometer jerk signal.  These correspond to the X, Y, and Z axis.

<h2>fBodyAccJerk_meanFreq_X, fBodyAccJerk_meanFreq_Y, fBodyAccJerk_meanFreq_Z</h2>
The mean weighted average of a frequency domain which was the result of Fast Fourier Transform (FFT) applied to the body accelerometer jerk signal.  These correspond to the X, Y, and Z axis.

<h2>fBodyGyro_mean_X, fBodyGyro_mean_Y, fBodyGyro_mean_Z</h2>
The mean of a frequency domain which was the result of Fast Fourier Transform (FFT) applied to the body gyroscope 3-axial signal.  These correspond to the X, Y, and Z axis.

<h2>fBodyGyro_std_X, fBodyGyro_std_Y, fBodyGyro_std_Z</h2>
The standard deviation of a frequency domain which was the result of Fast Fourier Transform (FFT) applied to the body gyroscope 3-axial signal.  These correspond to the X, Y, and Z axis.

<h2>fBodyGyro_meanFreq_X, fBodyGyro_meanFreq_Y, fBodyGyro_meanFreq_Z</h2>
The mean weighted average of a frequency domain which was the result of Fast Fourier Transform (FFT) applied to the body gyroscope 3-axial signal.  These correspond to the X, Y, and Z axis.

<h2>fBodyAccMag_mean </h2>
The mean of a frequency domain which was the result of Fast Fourier Transform (FFT) applied to the body accelerometer magnitude signal.  
<h2>fBodyAccMag_std</h2>
The standard deviation of a frequency domain which was the result of Fast Fourier Transform (FFT) applied to the body accelerometer magnitude signal.  
<h2>fBodyAccMag_meanFreq </h2>
The mean weighted average of a frequency domain which was the result of Fast Fourier Transform (FFT) applied to the body accelerometer magnitude signal.  

<h2>fBodyBodyAccJerkMag_mean</h2>
The mean of a frequency domain which was the result of Fast Fourier Transform (FFT) applied to the body accelerometer jerk magnitude signal.  
<h2>fBodyBodyAccJerkMag_std </h2>
The standard deviation of a frequency domain which was the result of Fast Fourier Transform (FFT) applied to the body accelerometer jerk magnitude signal.
<h2>fBodyBodyAccJerkMag_meanFreq </h2>
The mean weighted average of a frequency domain which was the result of Fast Fourier Transform (FFT) applied to the body accelerometer jerk magnitude signal.  

<h2>fBodyBodyGyroMag_mean</h2>
The mean of a frequency domain which was the result of Fast Fourier Transform (FFT) applied to the body gyroscope 3-axial magnitude signal.  

<h2>fBodyBodyGyroMag_std</h2>
The standard deviation of a frequency domain which was the result of Fast Fourier Transform (FFT) applied to the body gyroscope 3-axial magnitude signal.  

<h2>fBodyBodyGyroMag_meanFreq</h2>
The mean weighted average of a frequency domain which was the result of Fast Fourier Transform (FFT) applied to the body gyroscope 3-axial magnitude signal.  

<h2>fBodyBodyGyroJerkMag_mean</h2>
The mean of a frequency domain which was the result of Fast Fourier Transform (FFT) applied to the body gyroscope 3-axial jerk magnitude signal.  

<h2>fBodyBodyGyroJerkMag_std</h2>
The standard deviation of a frequency domain which was the result of Fast Fourier Transform (FFT) applied to the body gyroscope 3-axial jerk magnitude signal.  

<h2>fBodyBodyGyroJerkMag_meanFreq</h2>
The mean weighted average of a frequency domain which was the result of Fast Fourier Transform (FFT) applied to the body gyroscope 3-axial jerk magnitude signal.  

<h2>angle_tBodyAccMean_gravity</h2>
The mean of a frequency domain which was the result of Fast Fourier Transform (FFT) applied to the accelerometer gravity magnitude signal.  

<h2>angle_tBodyAccJerkMean_gravityMean</h2>
The mean angle of a time domain of the body acceleration jerk data from the accelerometer after passed through filtering.  

<h2>angle_tBodyGyroMean_gravityMean</h2>
The mean angle of a time domain of the body acceleration data from the gyroscope 3-axis after passed through filtering.  

</h2>angle_tBodyGyroJerkMean_gravityMean</h2>
The mean angle of a time domain of the body acceleration jerk data from the gyroscope 3-axis after passed through filtering.  

<h2>angle_X_gravityMean, angle_Y_gravityMean, angle_Z_gravityMean</h2>
The mean angle of the X, Y, and Z gravity variables.  

