Wiebe Jelsma, 12468223
Process Book of Programmeerproject
January 2019

Day #1 (Wednesday, 09-01-2019)
Today I spend some time on my datasets. Now, I have two.
It was a bit difficult, because I had to reform them a bit.
Also, some of the names of the columns contained two words.
Because of this, I couldn't get the information I needed out of these datasets.
I spent quite some time figuring out how to make these columns useful.
In the end, I changed the column names when I converted them from CSV and Excel into JSON.
This way, I the column name was one word and I could use it.
The rest of the day, I spent on getting the worldmap on my website, getting the names at the right countries and putting the Life Ladder values next to the countries. Now, the values are those of 2008 (I think), so I have to update it so you can change the years. 
Maybe I can do something like:
if year != 2008:
    i += year - 2008
This way, it is calculated how much difference there is between the current chosen year and 2008, and this amount is added to i so it takes the next year.