# SpaQui-Web
SpaQui Web App (Work in progress)
by Intrinsic Nebulae

Note that this project is still work in progress.
You can run the prototype version of this web app by running the index.html file on your device.



SpaQui Web
SpaQui Web (Derived from Spatium Quisquiliae which is Latin for space trash) is designed to make space missions easier. In other words, it is a precaution so that space debris do not adversely affect space missions. Apart from making official space missions easier and safer, we also aimed to raise public awareness about space pollution. Because, just as it is important to reduce the garbage on the earth, it is just as important to protect the environment outside the atmosphere, perhaps the area where we will continue our lives in the future. That's why we developed our project in a way that lets anyone reach and observe the space debris in the Earth's atmosphere.


SPACE DEBRIS
Space debris (also known as space junk, space pollution, space waste, space trash, or space garbage) is defunct artificial objects in space—principally in Earth orbit—which no longer serve a useful function. In space, even the smallest objects can get up to incredible speeds. So, every junk left in space may become a threat for future space missions. Next graph shows the increase of space debris over the years.



WHAT ARE TLE SETS?
A two-line element set (TLE) is a data format encoding a list of orbital elements of an Earth-orbiting object for a given point in time, the epoch. Using a suitable prediction formula, the state(position and velocity) at any point in the past or future can be estimated to some accuracy. We are able to calculate vital information(location, velocity, etc.) about individual satellites using these two line sets. In our app, we collected this data from CelesTrak databases.



PROGRAMMING LANGUAGES WE USED
In our project, we mainly used JavaScript and HTML since these languages are at the top when it comes to programming web apps. We used two JavaScript libraries called CesiumJS and SatelliteJS. A 3D map of the Earth was coded using CesiumJS. Then, we used SatelliteJS to calculate debris' longtitude, latitude, altitude, velocity and path.



We will be able to add more debris to our map, using the same method.



GETTING DATA FROM INDIVIDUAL SPACE DEBRIS
Using the same library, we could also collect individual debris' longtitude, latitude and altitude.

