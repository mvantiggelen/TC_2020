___________________________________________________________________
IS2photons_areaA.txt

Height of selected georeferenced photons from ICESat-2 (track 1169, cycle 04, segment 05, version 003, revision 01, beam gt1r) in area A on 12-09-2019

Variables: 
- Along-track_distance(m) : Horizontal distance (with x=0 at point most North) 
- Height(m): Height of selected photons above WGS 86 Ellipsoid
- Height_ph_sub(m): Resdidual of selected photons after kriging and filtering
___________________________________________________________________
elevprofiles1m_areaA.txt

Elevation profiles of UAV DEM and gridded ICESat-2 at 1m resolution in area A
Variables: 
- long-track_distance(m) : Horizontal distance (with x=0 at point most North) 
- IS2_profile_filt(m): Filtered ICEsat-2 profile 
- UAV_profile_filt (m): Filtered UAV DEM profile 
- IS2_profile(m): ICEsat-2 profile 
- UAV_profile (m): UAV DEM profile 
___________________________________________________________________
PDF_areaA.txt

Averaged Probability Density Function (PDF) of filtered elevations in area A
Variables: 
- filtered_height(m) : Filtered elevation PDF bin 
- PDF_ph: PDF of residual ICESat-2 photon elevations
- PDF_UAV: PDF of filtered UAV elevation profile 
- PDF_IS2: PDF of filtered ICEsat2 elevation profile 
___________________________________________________________________
