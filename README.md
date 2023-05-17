# Nashville Accidents Project

## Here is a project we did in class to analyze Nashville traffic accidents for Nashville Software School. 
 
 Stakeholders questions consisted of these...
 ![Screenshot (1)](https://github.com/SpotMcCormick/SpotMcComick.NashvilleAccidents/assets/132832823/05d6a5a8-a4d7-44cf-a031-125c8414b013)
 The first 5 questions were answered by using functions like COUNT, MIN, MAX,COUNTIF, and IF

![Screenshot (4)](https://github.com/SpotMcCormick/SpotMcComick.NashvilleAccidents/assets/132832823/0e4f7489-e7f7-41c6-83c1-94a48d4a6d71)
Next to get the accident count I had to use the TEXT function on the date column to extract the hour, year, and weekday of the date. Then I used COUNTIF with absolute cell refrencing to get a total count of each refrence.
![Screenshot (5)](https://github.com/SpotMcCormick/SpotMcComick.NashvilleAccidents/assets/132832823/3abf61c6-745f-4250-8b1c-498d0eea497c)
Next I had to use CONCAT with wildcards and COUNTIF to find the count of each interstate to look for a certain text string. Function looked like this =COUNTIF(Accidents!Q:Q,CONCAT("*",Analysis!A41,"*")). I did that for every way an interstate could have been written. 
The next question I used another COUNTIF for each precinct and inserted a pie chart for stake holders to get a bigger picture of the total accidents and what percentage of each precinct was assigned to each accident. 




