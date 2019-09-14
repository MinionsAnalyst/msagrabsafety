# msagrabsafety
Detect Safe Driving through the use of Data Analytics

Given the telematics data for each trip and the label if the trip is tagged as dangerous driving, derive a model that can detect dangerous driving trips.

The given dataset contains telematics data during trips (bookingID). Each trip will be assigned with label 1 or 0 in a separate label file to indicate dangerous driving. Pls take note that dangerous drivings are labelled per trip, while each trip could contain thousands of telematics data points. participants are supposed to create the features based on the telematics data before training models.

Field            Description

bookingID        trip id

Accuracy         accuracy inferred by GPS in meters

Bearing          GPS bearing in degree

acceleration_x   accelerometer reading at x axis (m/s2)

acceleration_y   accelerometer reading at y axis (m/s2)

acceleration_z   accelerometer reading at z axis (m/s2)

gyro_x          gyroscope reading in x axis (rad/s)

gyro_y          gyroscope reading in y axis (rad/s)

gyro_z          gyroscope reading in z axis (rad/s)

second          time of the record by number of seconds

Speed           speed measured by GPS in m/s

More infomation @ https://www.aiforsea.com/safety

Have Fun!
