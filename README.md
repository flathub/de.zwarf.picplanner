# PicPlanner

## The Idea
People who love to photograph know, the biggest problem is being at the right spot at the right time.
Therefore, landscape pictures should be planned before visiting the place of choice. To plan the location it is important to know the positon of the sun, moon and sometimes also the milky way.
Where to find the sun at which time is most of the time easy to guess but when is the sunset? And for the milky way normally nobody knows where to find it in the night sky at which time at a specific location.
This small program should answer all these questions.

## Plan
```diff
+1.  Create a basic GNOME like GUI -- Starting from zero again... Update: I think we can call it basic now :D
+2.  Calculate the center of the milky way at a specific time -- Implemented and equations seem to be very precise (± 1°) 
+3.  Calculate the position of the sun -- Implemented and equations seem to be very precise (< ± 1°) 
+4.  Find the position of the moon at a spesific time -- Implemented and equations seem to be sufficiently precise (~ ± 2°) 
+5.  Present all calculated data in the GUI -- Most of the data is showen
+6.  Create the location search -- A simple offline search is implemented now more will follow
+7.  Implement "smarphone functionality" e.g. find location via GPS
+8.  Insert a map view with OSM
+9.  Visualise important data direktly on the map
```

## Formulas used

Most of the formulas used are explained in detail directly inside the code. Reference is given or will be added soon.
Some of these formulas are from the excellent book by Jean Meeus "Astronomical Algorithms". Others are from scientific papers or combined by me.


## Libraries

- GTK 4 is used to create the GUI.
- Libadwaita is used to make the GUI adaptive.
- Shumate is used to show a map.
- Libgweather is used for the offline search functionality.
- GeoClue is used to get the users location.
