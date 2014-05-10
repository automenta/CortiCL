CortiCL
=
CortiCL is a C++/OpenCL implementation of the HTM Cortical Learning Algorithm by Numenta. [Whitepaper](http://numenta.org/resources/HTM_CorticalLearningAlgorithms.pdf)


Dependencies
-
 * G++
 * cmake
 * SDL2
 * OpenCL 1.2


OpenCL 1.2 Packages for Ubuntu Linux 14.04:
-
www.luxrender.net/forum/viewtopic.php?f=16&t=9477
```
I removed these packages:
	nvidia-libopencl1 
	nvidia-opencl-dev 
	opencl-headers 

And installed these:
	ocl-icd-opencl-dev
	nvidia-opencl-icd-331-updates
```


Building
-
The main platform is 64-bit Linux, but it might run elsewhere too. To build:

	mkdir build
	cd build
	cmake ..
	make
	./cldemo


Algorithm
-
Numenta owns the Intellectual Property of the HTM algorithm. Please refer to Numenta website (http://numenta.org/) for more information.

"Also note that I am not affiliated with the company, and that this library is the result of programming in my free time." --Joonas Haapala, originator of CortiCL

