# Code Book
========================================================
##Description
This is a code book for the *"Human Activity Recognition Using Smartphones"* data set found [here](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) and described [here](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones).  The code book reflects the set after processing with run_analysis.R

## Activity
Six values exist for the variable Activity:
  1. walking
  2. walkingup - Walking Upstairs
  3. walkingdown - Walking Downstairs
  4. sitting
  5. standing
  6. laying
  
## Time Domain Signals
 
### t.body.acc
Body acceleration signals for 3 axial directions (x, y, z) and includes mean and standard deviation for each.

    t.body.acc.mean.x
    t.body.acc.mean.y
    t.body.acc.mean.z
    t.body.acc.std.x
    t.body.acc.std.y
    t.body.acc.std.z

###t.gravity.acc
Gravity acceleration signals for 3 axial directions (x, y, z) and includes mean and standard deviation for each.


    t.gravity.acc.mean.x
    t.gravity.acc.mean.y
    t.gravity.acc.mean.z
    t.gravity.acc.std.x
    t.gravity.acc.std.y
    t.gravity.acc.std.z
    
###t.body.acc.jerk
Body acceleration jerk signals for 3 axial directions (x, y, z) and includes mean and standard deviation for each.


    t.body.acc.jerk.mean.x
    t.body.acc.jerk.mean.y
    t.body.acc.jerk.mean.z
    t.body.acc.jerk.std.x
    t.body.acc.jerk.std.y
    t.body.acc.jerk.std.z
    
###t.body,gyro
Body gyroscope signals for 3 axial directions (x, y, z) and includes mean and standard deviation for each.

    t.body.gyro.mean.x
    t.body.gyro.mean.y
    t.body.gyro.mean.z
    t.body.gyro.std.x
    t.body.gyro.std.y
    t.body.gyro.std.z
    
###t.body.gyro.jerk
Body gyroscope jerk signals for 3 axial directions (x, y, z) and includes mean and standard deviation for each.

    t.body.gyro.jerk.mean.x
    t.body.gyro.jerk.mean.y
    t.body.gyro.jerk.mean.z
    t.body.gyro.jerk.std.x
    t.body.gyro.jerk.std.y
    t.body.gyro.jerk.std.z
    
###Magintude signals

Magnitude signals Includes mean and standard deviation and follow the same notation as above:

    t.body.acc.mag.mean
    t.body.acc.mag.std
   
    t.gravity.acc.mag.mean
    t.gravity.acc.mag.std

    t.body.acc.jerk.mag.mean
    time.body.acc.jerk.mag.std

    t.body.gyro.mag.mean
    t.body.gyro.mag.std

    t.body.gyro.jerk.mag.mean
    t.body.gyro.jerk.mag.std

##Frequency Domain Signals
Frequency domain signals follow the smae denotation as time domain signals with the exception of the character "f" replacing "t" to denote frequency.

###f.body.acc
Body acceleration signals for 3 axial directions (x, y, z) and includes mean and standard deviation for each.

    f.body.acc.mean.x
    f.body.acc.mean.y
    f.body.acc.mean.z
    f.body.acc.std.x
    f.body.acc.std.y
    f.body.acc.std.z

###f.gravity.acc
Gravity acceleration signals for 3 axial directions (x, y, z) and includes mean and standard deviation for each.


    f.gravity.acc.mean.x
    f.gravity.acc.mean.y
    f.gravity.acc.mean.z
    f.gravity.acc.std.x
    f.gravity.acc.std.y
    f.gravity.acc.std.z
    
###f.body.acc.jerk
Body acceleration jerk signals for 3 axial directions (x, y, z) and includes mean and standard deviation for each.


    f.body.acc.jerk.mean.x
    f.body.acc.jerk.mean.y
    f.body.acc.jerk.mean.z
    f.body.acc.jerk.std.x
    f.body.acc.jerk.std.y
    f.body.acc.jerk.std.z
    
###f.body,gyro
Body gyroscope signals for 3 axial directions (x, y, z) and includes mean and standard deviation for each.

    f.body.gyro.mean.x
    f.body.gyro.mean.y
    f.body.gyro.mean.z
    f.body.gyro.std.x
    f.body.gyro.std.y
    f.body.gyro.std.z
    
###f.body.gyro.jerk
Body gyroscope jerk signals for 3 axial directions (x, y, z) and includes mean and standard deviation for each.

    f.body.gyro.jerk.mean.x
    f.body.gyro.jerk.mean.y
    f.body.gyro.jerk.mean.z
    f.body.gyro.jerk.std.x
    f.body.gyro.jerk.std.y
    f.body.gyro.jerk.std.z
    
###Magintude signals

Magnitude signals Includes mean and standard deviation and follow the same notation as above:

    f.body.acc.mag.mean
    f.body.acc.mag.std
   
    f.gravity.acc.mag.mean
    f.gravity.acc.mag.std

    f.body.acc.jerk.mag.mean
    time.body.acc.jerk.mag.std

    f.body.gyro.mag.mean
    f.body.gyro.mag.std

    f.body.gyro.jerk.mag.mean
    f.body.gyro.jerk.mag.std
    
