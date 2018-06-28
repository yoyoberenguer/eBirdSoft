# eBirdSoft
Testing software for eBird® lateral, vertical and roll control of seismic cables

What is eBirdSoft?

eBirdsoft is a project coded in Python (version 2.7, with Tkinter) providing a real-time GUI interface in order to test seismic equipment such as eBird body and wings technology.

It is designed to work onto various platforms such as Linux RedHat for backward compatibility with the BOCS system but will work on most platforms including Mac OS and windows (tested proficiently on Linux and windows).

eBirdSoft is using multithreaded/multiprocessing applications to utilise the full potential of Konsberg Seatex ECLT commands. It will perform background tasks and regroup results in a concise manner.
The results are displayed into tables to simplify the way the equipment functions are represented

This application comes with powerful graphic tools to analyse equipment behaviours but also to store data in a local SQLITE database. Plots and graph can be generated to more easily understand the overall mechanisms such as current charging, voltage variations, eBird body current leakage etc. 

What can eBirdSoft provide in addition to BOCS ?:

It provides a testing platform with a very concise and intuitive way to monitor and
test eBird equipment via graphical tools
It is ideal for intermittent issues as eBirdSoft is capable of continuously monitoring eBird body functions.

eBird Technology
https://www.km.kongsberg.com/ks/web/nokbg0240.nsf/AllWeb/EB747DB0D24FFF94C125765600465A3B?OpenDocument
