# Greg_HW2_3

## data of Greg_HW2_3 for Q3_abcd   
asu_Pleiades.fit   -------raw data from Vizier:Infrared observations of the Pleiades (Stauffer+, 2007)  
Pleiades_Gaia.csv  -------data by CDS X-match service bettwen asu_Pleiades.fit and Gaia DR2  
                          (may return all the sources with match raidus and result in a larger number catelogue)  
Pleiades_Gaia.fits -------asu_Pleiades.fit crossmtach Pleiades_Gaia.csv by Topcat  
                          (Topcat returns the best match source)  
asu_Hyades.fit     -------raw data from Vizier:Pan-STARRS1 (PS1) observations of the Hyades (Goldman+, 2013)  
asu_NGC752.fit    ------- Photometry and radial velocities in NGC752 (Daniel+, 1994)  

## query for Q3_e
50_505_18_185.fits ------field data from Vizier query  
website:http://tapvizier.u-strasbg.fr/adql/  
SELECT "ra", "dec","parallax","phot_g_mean_mag", "bp_rp"  
FROM "I/345/gaia2"  
where "ra" between 50 and 50.5  
and  "dec" between 18 and 18.5  
