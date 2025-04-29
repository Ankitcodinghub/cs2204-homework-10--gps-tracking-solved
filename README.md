# cs2204-homework-10--gps-tracking-solved
**TO GET THIS SOLUTION VISIT:** [CS2204 Homework 10- GPS tracking Solved](https://www.ankitcodinghub.com/product/cs2204-homework-gps-tracking-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116680&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS2204 Homework 10- GPS tracking Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Objectives

Gain experience in working with CSV datasets

Understand the need for data type conversions

Implement mathematical formulas in Python

Background

You are given a GPS track of a vehicle in CSV format. The data file contains a series of coordinate points with timestamps. The three columns in the data file are as follows:

1. Time : the timestamp in fractional seconds of the GPS location. Do not assume that all timestamps fall on integer second boundaries. Neither they are at uniform intervals from each other.

2. Latitude : the geographic latitude in signed decimal degrees. The latitude is preceded by a minus sign (-) if it is south of the equator (a positive number implies north)

3. Longitude : the geographic longitude in signed decimal degrees. The longitude is preceded by a minus sign if it is west of the prime meridian (a positive number implies east).

A quick intro/refresher on the geographic coordinate system can be found here: https://journeynorth.org/tm/LongitudeIntro.html

Tasks

Finish the gps_tracking.py script which reads and the processes the GPS track data. Use the csv Python module to work with this file.

Your first task is to implement the distance() function, which calculates the distance in miles between two GPS coordinates. See the docstring and the hints below for details.

Than, your script should compute and print the following metrics:

Overall distance: the entire length of the trip (sum of distances between the measurement points). You should print this information in miles rouded to one decimal place precision.

Average speed: the ratio of overall distance and overall time of the trip in miles per hour (mph) rounded to the closest integer.

Maximum speed: the maximum speed observed between consecutive GPS track points in miles per hour (mph) rounded to the closest integer.

If done correctly, your output should look like this (use the exact same output format):

Distance: 19.1 miles

Average speed: 52 mph

Maximum speed: 84 mph

Hints

The first challenge in this assignment is to compute the distance on the surface of Earth between two geographic coordinate points (p1 and p2). You should use and implement the haversine formula to calculate the distance (d) in miles:

φ1,φ2: latitude of p1 and p2 in radians, respecitvely λ1,λ2: longitude of p1 and p2 in radians, respecitvely R: mean radius of Earth in miles (use: 3,958.8 miles)

dφ = φ2 − φ1 dλ = λ2 − λ1

a

c

√1 − a d = R ⋅ c

Notes:

All the required mathematical functions ( sin , cos , atan2 , sqrt , radians ) are available from the Python math module.

Use the atan2 function to calculate the arctangent in the formula.

The trigonometric functions use radians (not degrees). You can convert from degrees to radians using the math.radians() function.

Grading

Penalties

Points will be deducted if you fail to set __author__ variable (-10 pts) and for each PEP 8 style errors (-1 pt for each) in your program.

Submission

Please, upload the final version of the following file(s) (and only those files) to Brightspace:

gps_tracking.py
