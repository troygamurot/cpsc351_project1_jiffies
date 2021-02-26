# cpsc351_project1_jiffies
 
 Troy Gamurot
 
 Professor McCarthy
 
 CPSC 351

 Project 1 - Jiffies
 
 ### Simple.c

As directed in the project directions, simple.c properly displays the GOLDEN_PRIME_RATIO, jiffies value, and HZ value on module load. The gcd of 3300 and 24 and the value of jiffies is displayed on module exit.

![simple_output_img](https://github.com/troygamurot/cpsc351_project1_jiffies/blob/main/pictures/simple%20output.png)

###### Note

As stated per the project's rubric, I modified the provided hello.c project so it would display the GOLDEN_PRIME_RATIO on module load and the gcd of 3300 and 24 on module removal. This function is incorporated into the code of both jiffies.c and seconds.c

### Jiffies.c
###### Loading and Removal of Module
![jiffies_load_rmv_img](https://github.com/troygamurot/cpsc351_project1_jiffies/blob/main/pictures/jiffies%20creation%20and%20deletion%20messages.png)

###### Output of /proc/jiffies

![jiffies_proc_img](https://github.com/troygamurot/cpsc351_project1_jiffies/blob/main/pictures/proc%20jiffies%20output.png)

### Seconds.c
###### Loading and Removal of Module
![seconds_load_rmv_img](https://github.com/troygamurot/cpsc351_project1_jiffies/blob/main/pictures/seconds%20creation%20and%20deletion%20messages.png)

###### Output of /proc/seconds
![seconds_proc_img](https://github.com/troygamurot/cpsc351_project1_jiffies/blob/main/pictures/simple%20output.png)
