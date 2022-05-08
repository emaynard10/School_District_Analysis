# School_District_Analysis
PyCitySchools

## Overview of the school district analysis
This analysis was intended to provide a school board with specific statistics for a better understanding of how the schools in the distric compare with eaach other on various metrics. The most important part of this analysis was cleaning the data; once the school board realized that there was an error with some sparsley populated reading and math scores at one of the high schools, it was worth eliminating the data that they thougth to be altered for a better overview of all the schools. The reading and math scores at Thomas High School were replaced with NaN (or Not a Number) for all the ninth grade students. Because the first analysis was conducted with these students included it will be easy to see how the comparison of the 15 schools was impacted.

## Results
Using bulleted lists and images of DataFrames as support, address the following questions.

* How is the district summary affected?
For camparision the district summary with the ninth grade Thomas High scores included is listed first and the cleaned district summary without the ninth grade scores is listed second. The difference between the number of student is 461; the average math scores and the percentages are slightly lower without all the students.

![Screen Shot 2022-05-07 at 6 12 48 PM](https://user-images.githubusercontent.com/99676466/167276268-9ce3ea04-b85d-4854-8931-c4a86e9d285d.png)


![Screen Shot 2022-05-07 at 6 08 59 PM](https://user-images.githubusercontent.com/99676466/167276229-7bc4290b-6797-4a85-95b0-640f2750d361.png)


* How is the school summary affected?
The school summary is affected only slightly with Thomas High School at 93.27% passing math and 97.31% passing reading before the ninth graders were removed and 97.02% passing math and 93.19% passing reading after. When comparing the different grades Thomas High cannot be compared to other ninth graders due to the lack of data now. Thomas High went from listing 1635 students in all to 1174.

* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Thomas High School remains in the top five schools.

![Screen Shot 2022-05-07 at 6 36 43 PM](https://user-images.githubusercontent.com/99676466/167276800-7da229c9-8ae8-40e1-bb73-f81ac73bc58b.png)

#### How does replacing the ninth-grade scores affect the following:
* Math and reading scores by grade were impacted by the lack of a number for the 9th graders at Thomas:
 
![Screen Shot 2022-05-07 at 6 38 09 PM](https://user-images.githubusercontent.com/99676466/167276823-0a8a828c-b1f7-4824-8385-d4a067b51b38.png)
 
 
![Screen Shot 2022-05-07 at 6 38 45 PM](https://user-images.githubusercontent.com/99676466/167276833-ddcfbc96-a3da-4a9a-91b3-f0d88ace31a9.png)

 * Scores by school spending only had an impact on the reading scores
 
 ![Screen Shot 2022-05-07 at 6 51 17 PM](https://user-images.githubusercontent.com/99676466/167277079-8ce241f9-5319-405d-bdab-9766d105ea81.png)

 ![Screen Shot 2022-05-07 at 6 50 34 PM](https://user-images.githubusercontent.com/99676466/167277057-8afb8ffc-5911-4073-8235-fd04f7e9de43.png)

    
* Scores by school size
These scores were unaffected by the removal of ninth grade math and reading scores at Thomas High because the school still fell within the same size bin of size medium or 1000 to 1999 students.

* Scores by school type were only impacted with a change in the reading scores which went down without the inclusion of the ninth graders. This means without the added reaading scores at Thomas the averages went down.
* 
![Screen Shot 2022-05-07 at 6 42 59 PM](https://user-images.githubusercontent.com/99676466/167276913-0bbcdfa7-1dda-4228-9c7b-c9ca08d263a9.png)
![Screen Shot 2022-05-07 at 6 43 17 PM](https://user-images.githubusercontent.com/99676466/167276916-0526ebde-7f99-42c3-9ad7-e040de594338.png)

## Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
Four changes the updated school district analysis had without the coparison of ninth grade scores at Thomas High School were:
1. Thomas High had 461 fewer students to count toward their averages. This brought the total students from 39,170 down to 38,709. 
2. The ninth grade scores are replaces with NaN 

![Screen Shot 2022-05-07 at 7 10 41 PM](https://user-images.githubusercontent.com/99676466/167277578-07d486fc-d222-48e0-9009-80d37ab9bd0e.png)

3. The score percentages are slightly lower without the ninth grade scores.
4. The spending ranges per student changed in the $631 to $645 range
