___________________________________________________________________
AreaA.txt
AreaB.txt

Modelled roughness parameters in 200m windows (separated by 50m) in areas A and B from both UAV survey and ICEsat-2
UAV survey was perfomed on 01/09/2019 in area A and on 03/09/2019 in area B
ICESat-2 profiles are measured on 12/09/2019 in area A and on 23/12/2019 in area B

Variables:

Along-track_distance(m): Horizontal distance of window center (x=0 for point most North)
H_IS2_L6: Height of roughness obstacles from scatter of ICESat-2 ATL03 photons detrended for ATL06 signal
HD(m): Height of roughness obstacles from UAV survey
H_IS2(m): Height of roughness obstacles from filtered ICESat-2 profile 
H_IS2corr(m): Height of roughness obstacles from filtered ICESat-2 profile, accounting for residual scatter in photon elevations after filtering
Lambda_D(-): frontal area index from UAV survey
LAMBDA_IS2(-): frontal area index from filtered ICESat-2 profile
LAMBDA_IS2corr(-): frontal area index from filtered ICESat-2 profile, accounting for residual scatter in photon elevations after filtering
z0R_D(m): aerodynamic roughness length modelled using Raupach(1992) model and forced by UAV data
z0R_IS2(m): aerodynamic roughness length modelled using Raupach(1992) model and forced by ICESat-2 data
z0R_IS2corr(m): aerodynamic roughness length modelled using Raupach(1992) model and forced by ICESat-2 data, accounting for residual scatter in photon elevations after filtering
___________________________________________________________________

