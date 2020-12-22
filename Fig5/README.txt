___________________________________________________________________
IS2_ATL03D_Ktransect_cyclexx.csv

Estimated surface roughness parameters in 200m segments from processed ICESat-2 ATL03 data along the K-transect (west Greenland ice sheet) for cycle xx. 
Note that each cycle is a period of 3 months

Variables:

lat: latitude (dd)
lon: longitude (dd)
z: average height above WGS 86 ellipsoid (m)
d: along-track distance (m)
d_height: displacement height (m)
Lambda: frontal area index (-)
Lambda_corr: frontal area index accounting for residual photon scatter (-)
stdz: standard deviation of highpass filtered elevation (cutoff wavelength 35m)  (m)
sigmas: standard deviation of residual photon elevations (m)
q: average photon quality flag (between 1 and 4)
n: average number of photons used in kriging
H: height of roughness obstacles, defined as 2xstdz (m)
H_corr: height of roughness obstacles, accounting for residual photons scatter (m)
flags: quality flag (flags == 1 when sigmas > stdz)
z0_R: modelled aerodynamic roughness length using Raupach(1992) model (m)
z0_R_corr: modelled aerodynamic roughness length using Raupach(1992) model, accounting for residual photons scatter (m)
z0_LM: modelled aerodynamic roughness length using Lettau(1969) model (m)
Cd: drag coefficient for form drag (-)
Cs: drag coefficient for skin friction (-)
ftauS: fraction of skin friction over total drag (-)
distance_to_nearest_edge: Horizontal distance to nearest ice sheet margin (m)
in_polygon: =1 if segment is in input polygon (in this case, the Greenland ice sheet)
yyyymmddhhmmss: year month day hour minute second of ICESat2 measurement
ttttccss: track cycle segment of ICESat2 measurement
vvv: version of ICESat2 ATL03 product
rr: release of ICESat2 ATL03 product
track: ICESat-2 laser beam identifier 
___________________________________________________________________

Links to additionnal data:
ArcticDEM: https://www.pgc.umn.edu/data/arcticdem/
Sentinel-2: https://apps.sentinel-hub.com/sentinel-playground/
