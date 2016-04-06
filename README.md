# semile
_~profile what you care, monitor how it goes~_ http://r-kan.github.io/semile/

#What is semile?  
A profiling framework that provides the ability to monitor programs, in general of any programming language, by the following two pieces of information:  
1. consumed time per execution  
2. 'footprint' message per execution  

#Difference with other profiling tools?  
* **_Profile 'semantically'_**  Each call to the same function plays its individual role within profiling. Normal 'syntactic' profilers are good in other aspects but fail to achieve this.  
* **_Lightweight_**  The profiled program gives little run-time overhead. The viewer is compact that targets to provide only necessary information without fancy visual effect. It gives profile result in widespread PNG and XML format.  
* **_Message-embedded profile_**  Customized information can be left within profile elements. It then also provides the ability to help reveal internal state/decision inside the program.  

P.S. The user-provided semantic specifications (via the profile library) is necessary for semantic profile  

# System Requirement
python3 (viewer)   
g++ (cpp profile library)  

# Dependent Library
<a href="http://www.graphviz.org" target="_blank">dot (graphviz)</a>   

# Contact  
Please contact *rkan* by its_right@msn.com for any question/request/bug without hesitation. 

***
Find screenshots, tutorials, and more information at http://r-kan.github.io/semile/!