# First approach

code link : https://code.earthengine.google.com/?scriptPath=users%2Fmadeleinesarahabbes%2FGeoInfProject%3Afirst_approach

parameters the user should modify in the header :

num_points : (integer). This parameter is the number of points to be sampled in per class and per continent. ex : if num_points = 100, the algorithm will sample 100 points in the burn area and 100 points in the unburn area for each continent. This means for each continent in total we sample 2*num_points points (in the example 400 points per continent) /!\ : for Oceania, as the surface is really small compared to other continents, the number of points per class is num_points/2, This is to avoid autocorrelation.

myDriveFolder : string This is the name of the drive folder you want to download the data in

scale : integer (minimum : 500 m) this is the pixel size in meter to which every variable will be resample before extracting the points.

startDate/endDate : ee.Date min : 2013-03-18 ; max : today This is the time period that will be considered for the analysis. All variables will be averaged over this time period. before extracting the points.
