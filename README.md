# time-complexity
how to show time complexity on run time 

#include<iostream>
#include<time.h>
  {
 //write this code at the end of code
	 time_t t = clock();

    //Code goes here

    t = clock() - t;
    double time_taken = ((double)t)/CLOCKS_PER_SEC;
    cout<<time_taken;
    }
