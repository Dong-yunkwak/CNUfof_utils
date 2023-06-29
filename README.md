# CNUfof_utils 
This is a Friends of Friends algorithm that make galaxy group finding. It is made by multiprocessing package "RAY"

## Welcome to using Parallelizing Friends Of Friends. 
I'm an undergraduate at the Exo-galaxy Lab in Chungnam National University. 
If you have any questions or feedback about PFOF code, Place contact us at the email address below.
I want your opinions and thoughts about the code. Please feel free to contact me! 
<Email : 98ehddbs@naver.com>
---------------------------------------------------------------------------------------------------

Version 0.1.0 2023.06.22 
Version of packages used. (Please check these versions)
numpy   1.21.4
astropy 5.1.1
pandas  1.3.5
pydl    1.0.0
ray     2.2.9

*** Based on observing data Parallelizing Friends of Friends algorithm *** 
ra (0~360[degree]), dec (-90~90[degree]), redshift (>=10^(-3))

Cautions)  Before importing, You should install some of packages 
- ray package (Parallelizing pack) 
- pydl package (gcirc function pack) 

Note) 
- Set linking length [Physical Distance [kpc] | velocity [km/s]] , nmin(minimum number of particles(galaxies)) 

- The group name you run as whole at once may be different from the group you run in parallel. But, The particles found for each group will be the same 

- When setting the variables, you should follow the example.

More detail usage methods are explained in "example" and "Explanations file for each code"  file 

