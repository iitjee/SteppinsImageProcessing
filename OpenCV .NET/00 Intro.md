Hi, and welcome to Pluralsight. My name is Kobi Hikri, and you are watching Getting Started with OpenCV in.NET. In a few days, prior to the release of this course, a new version of OpenCV, OpenCV 3 was released. 
However, we will be using a prior version for stability concerns. throughout the course we are using Emgu CV, a popular .NET wrapperto OpenCV,
As OpenCV is an unmanaged library, written entirely and optimized in C and C++, we will use a well known and popular .NET library called Emgu CV. Hand in hand we will strive together towards a better understanding of the capabilities of the OpenCV library. 
There are many researcher's techniques in both software and hardware approaches to problem solving. We will focus on problem solving using software.
OpenCV has been around with us for quite some time now and has gained popularity among researchers, academies, companies, and developers. OpenCV is basically a framework targeted at solving problems from the domain of computer-vision. As such, it contains implementations for the most popular and efficient algorithms for solving such problems. How efficient you ask? Well, it's even possible to compile and run OpenCV on a Raspberry Pi on an Android phone; however, this is not the scope of this course. In this course, we will focus on consuming OpenCV formal .NET applications. 
Yet another important aspect is that hardware acceleration via the popular NVIDIA CUDA and OpenCL are natively supported by the framework. 
OpenCV is cross-platform and will run on Linux, Android, Windows, and iOS. In order to supply these amazing features in an efficient and cross-platform manner, OpenCV is an optimized C and C++ framework. 

<br/>
For us as .NET developers, the meaning is that we need to wrap the library in order to consume it in our applications. In the following module I will demonstrate how you can do it manually using your own C++ to CLI wrapper library. However, I do not recommend going this path unless you require a very small portion of OpenCV's capabilities. What I do recommend is using an already written and tested .NET wrapper called Emgu CV. Emgu CV is a popular .NET wrapper for OpenCV, which is released under the GPL, open-source license. I will go into details shortly.


Traffic:
 Monitoring the amount of vehicles entering and leaving a city at a given time, this allows for an automatic adjustment of traffic lights in the city. 
 Medical: 
 In the medical arena it is possible to accurately analyze fractures and decide on the best way of treatment prior to surgery. t
