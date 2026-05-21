#Ingestion notes


## Standardization rules 
ASD is to be treated as the metadata template to follow going forward

rows 1-28: Standardized metadata as specified on ASD
rows 28+: Instrument specific metadata

Spectral data to start after all metadata sections. Starting row may vary because of this (parsing logic should handle this)
If data doesn't exist for an instrument, leave the row values blank. 


## Common metadata fields should match across all sheets 

1. Instrument name
2. Blank or  Labspec 4 hi-res
3. Directory(yy/mm/dd)
4. Basename
5. Sample #
6. Sample Description
7. Sample Descrip.(con'd)
8. Sample Descrip.(con'd)
9. Sample Descrip.(con'd)
10. Grain Size (microns):
11. Viewing geometry(i/e/ϕ):
12. Wavelength Range (nm):
13. Resolution
14. Sampling Interval(nm)
15. Integration Time:
16. # of Spectrum Avg.
17. Boxcar/Zero Fill
18. blanks
19. Atmosphere:
20. Sample temperature:
21. Sample cup:
22. Light source:
23. Depolarizer:
24. Sample spun:
25. Pickup fiber:
26. Approximate measured area:
27. Sample prep.:
28. Spectralon correction file 

## Instrument Specific metadata

Raman
30. Resolution(∆ cm-1):
31. Sampling interval (∆ cm-1)
32. Raman-shift Range (∆ cm-1):
33. Laser wavelength(nm):
34. Laser power (mW):
35. Linearity corrected:
36. Dark compensate:
37. Dark subtracted:
38. CCD temperature(°C):
39. Fiber optic cable:
40. Notch filter:
41. Laser spot diameter:
42. Viewed spot diameter:
43. Microscope Used: 

Bruker Vertex
30. Reflectance standard
31. Scanning Velocity (kHz)
32. Other info:

Maya
30-33 = Notes: