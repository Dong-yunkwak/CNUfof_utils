# CNUfof_utils 
This is a Friends of Friends algorithm that makes galaxy group finding. It is made by multiprocessing package "RAY"

## Welcome to using Parallelizing Friends Of Friends. 
I'm an undergraduate at the Exo-galaxy cosmology Lab in Chungnam National University. 
If you have any questions or feedback about PFOF code, Please contact me at the email address below! 
[I want your opinions and thoughts about my code.]

***<Email : 98ehddbs@naver.com>***
---------------------------------------------------------------------------------------------------

Version 1.0.6 2024.06.28  
Version of packages used. (Please check these versions) \
numpy   1.21.4 \
astropy 5.1.1 \
pandas  1.3.5 \
pydl    1.0.0 \
ray     2.2.9 -> It does not support to window enviroment (Curently, It is said that a beta version has been created in the Window) 


Based on observing data Parallelizing Friends of Friends algorithm
ra (0 ~ 360[degree]), dec (-90 ~ 90[degree]), redshift (&ge; 10<sup>3</sup>)

Cautions)  Before importing, You should install the following pacakages 
- ray package (Parallelizing pack) 
- pydl package (gcirc function pack) 

Note) 
- Set linking length [Physical Distance [kpc] | velocity [km/s]] , nmin(minimum number of particles(galaxies)) 

- The group name you run as whole at once may be different from the group you run in parallel. But, The particles found for each group will be the same 

- When setting the variables, you should follow the example.

More detail usage methods are explained in "example" and "Explanations file for each code"  file 

