# centurySign
Depending on the month and day you were born, you were born under one of 4 Century High School signs. Your job is to write a function that will determine what sign you were born under based on your birthday.


**requirements:**
----------
* Anyone born between August 15 and November 14 is born under the Jag Crew Sign
* Anyone born between November 15 and February 14 is born under the Canned Food Drive Sign
* Anyone born between Febuary 15 and May 14 is born under the Forecasting Sign
* Anyone born between May 15 and August 14 is born under the Jagfest Sign

**Inputs:**
----------
* **caughtSpeeding()** receives three values (integer, integer & boolean): *speed*, *speed_limit*, and *isBirthday*
  * **speed** = mph your car is travelling when the cop tracked your speed
  * **speed_limit** = the posted speed limit where you were driving
  * **isBirthday** is a Boolean
    * True = if it's your birthday
    * False = if it's not your birthday

**Output:**
------------
Output will be a fine in the form of an integer (0, 500, 1000, 1500, 2000)

**Examples:**
inputs => output/s
--------------------------------
* 45 45 False => 0
* 51 45 False => 500
* 55 45 False => 500
* 61 40 False => 1000
* 100 55 False => 1500
* 81 55 False => 1500
* 105 55 False => 2000
* 65 55 True => 0
* 60 40 True => 500
* 65 40 True => 1000
* 103 55 True => 1500
