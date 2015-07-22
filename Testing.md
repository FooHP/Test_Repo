##Getting & Cleaning Data  - Course Project  Code Book   TESTING TESTING 

Foo HP
22 July 2015


**PURPOSE** : To describe the variables, the data and any transformations or work performed to clean up the data

    

**INPUT DATA** : https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip



.		activ
.  V1                 V2
.1  1            WALKING
.2  2   WALKING_UPSTAIRS
.3  3 WALKING_DOWNSTAIRS
.4  4            SITTING
.5  5           STANDING
.6  6             LAYING


. Column 3 to Column 68 : "tBodyAcc-mean()-X" "tBodyAcc-mean()-Y" "tBodyAcc-mean()-Z" .........           
.  			"fBodyBodyGyroMag-mean()"     "fBodyBodyGyroMag-std()"   
.			"fBodyBodyGyroJerkMag-mean()" "fBodyBodyGyroJerkMag-std()"	


.$ Subject                    : int  1 1 1 1 1 1 2 2 2 2 ...
.$ Activity                   : chr  "LAYING" "SITTING" "STANDING" "WALKING" ...
.$ tBodyAcc-mean()-X          : num  0.222 0.261 0.279 0.277 0.289 ...