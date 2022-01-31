# School District Analysis
Pandas practice


## Overview of the school district analysis: Explain the purpose of this analysis.

We'll be helping Maria analyzing data about performance trends and patterns of districts' schools, this will help on decision making specifically on student funding as well as student's evaluations.

After running some analysis, the board has announced that the data might be corrupted so we need to reconsider this situation in the final insights.

The purpose of this analysis is to quantifie the impact of this situation on the districts' metrics as well as to give an advice on how to analyse this data.

## Results: Using bulleted lists and images of DataFrames as support, address the following questions.


### * How is the district summary affected?
Total number of "Thomas High School" Students did not impacted too much on the district summary after changing 9th graders to NaN.


<img width="481" alt="Comparison" src="https://user-images.githubusercontent.com/31755703/151741443-ef3aaa98-c2ff-4fb5-8e6a-53c15cafe027.png">


### * How is the school summary affected?
The new data shows that the performance of Thomas High School wasn't has high as before the change.

<img width="241" alt="Comparison2" src="https://user-images.githubusercontent.com/31755703/151744960-c3988c8b-bf24-4206-b6fd-5896f47d8bd9.png">


### * How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Basically it didn't affected the ranking. Although there was a change, it did't represent too much comparing to the rest of the schools.

### * How does replacing the ninth-grade scores affect the following:
### * Math and reading scores by grade

<img width="222" alt="graders" src="https://user-images.githubusercontent.com/31755703/151747542-d5ff61f6-f0ec-426c-9803-88427a00a0e0.png">
Everything stays the same, except that the 9th graders doesn't have a score.

### * Scores by school spending
<img width="390" alt="Comparison spending ranges" src="https://user-images.githubusercontent.com/31755703/151745223-f40809d7-e261-4d2b-bc07-ea8817b54926.png">
It only affects the bracket to which Thomas High School belongs to

### * Scores by school size
<img width="356" alt="Comparison school size" src="https://user-images.githubusercontent.com/31755703/151745251-96ce734f-27fd-41f5-a385-b7efcc2dd0e2.png">
It only affects the bracket to which Thomas High School belongs to


### * Scores by school type

<img width="333" alt="Comparison school type" src="https://user-images.githubusercontent.com/31755703/151745255-8d7e4ce8-d5c2-495f-b66e-beae61786421.png">
It only affects the bracket to which Thomas High School belongs to



## Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

It is really important to quantify the impact of a change like the one we did so we can take decisions based on reliable information as well as taking into consideration if a change is meaningful or not. In this case it only changes by less than 1%. Some of the changes in the dataframes analyzed are the following.

| Main changes  |
| ------------- |
| School summary|
| Scores by school spending |
| Scores by school size |
| Scores by school type |

It is also important to note that dishonesty at any level can affect decision making, even if the origin of data may be reliable there's always room for human manipulation.
As Data analysts we must be aware of this situations and be critical on how to face them.
