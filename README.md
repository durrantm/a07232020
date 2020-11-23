I can get useState working with strings and even array, but getting the syntax right for objects has eluded me.
- I do NOT need to save previous values or use the reducer pattern to do so, placing all the values in my object is fine for this exercise.
- I do not want to put all my states inside one object in this exercise (I will do that later).

I just want to do one thing - store the result for API#3 (weather forecast) and then display them.
I was able to store the high_temp for 5 days and save them in an array (forecast5DaysHighs).
I now want to store all the 15 days of weather data and then retrieve it - starting with high_temp.
So far I can't getr anything to display.
Perhaps I am not reaching deep enough into the objects, or perhaps my array for useEffect isn't set right.

Notes:

App.js

Line# Note
 18   State Object
 37   The API call for temps
 83   Storing data in an array - works
 90   Storing daat in an object - not working
 93   Issue
191   Can't map on an object this way.
