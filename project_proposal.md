# ORIE 4741 Project Proposal: Analyzing 911 Calls in New York City

## Richard Zheng (rz98), Iris Li (icl5), Peter Gribizis (pjg222)

**Background:** 

911 is an integral part to the welfare of the population of the United States. Through the use of a centralized system, emergencies can be responded to and dealt with in a timely manner. However, knowing the nature of an emergency before arriving on scene can have a significant impact on how it is dealt with, including response time and first responder safety.

**The Question:** 

What determines the severity of a call and what can be done to prepare?

**The Problem:**

The current Covid pandemic has brought to light the need for efficacy in America’s medical infrastructure. Emergency Medical Services (EMS) are in demand now more than ever -- pre-pandemic, NYC received around four thousand 911 calls a day, but during the pandemic, [daily calls have spiked 40%](https://www.bloomberg.com/news/articles/2020-03-25/-most-since-9-11-nyc-responders-deluged-with-emergency-calls). We hope to investigate potential methods to improve the way EMS calls are handled.

**The Significance:**

If we are able to model and predict the 911 call volumes for EMS in NYC, we will have a better sense of what types of issues arise at what times, at what locations, and with what level of urgency.  Having a better ability to predict incident rates ahead of time can allow for faster response times, more appropriate resource allocation, improved incidence handling, and avoidance of understaffing.  Ultimately, we wish to lessen the load caused by the increased demand for 911 services by better modeling 911 call severity and call volume.

**The Data:**

We have identified two datasets that will be of use to us in modeling EMS calls. The first provides a breakdown of 911 calls in NYC, which will be useful in the exploratory analysis stages of the project. The second provides dispatch data for individual EMS calls, giving us insight into building a model that can identify the implications of characteristics a sample call may exhibit.

[911 Call Data](https://data.cityofnewyork.us/Public-Safety/911-End-to-End-Data/t7p9-n9dy)
This dataset breaks down calls by agency responding. The dataset includes 6348 rows of data which shows 30 different features including the different agencies such as EMS and FDNY. While it doesn’t have individual call data, like times, it’ll give us a broad idea of the number of critical and non critical calls we should be seeing. 

[EMS Dispatch Data](https://data.cityofnewyork.us/Public-Safety/EMS-Incident-Dispatch-Data/76xm-jjuj)
This dataset has 17.3m EMS call entries as recorded by the EMS Computer Aided Dispatch System from 2008 to present. The 31 features include initial and final call types with time stamps, initial and final severity, dispatch response times, general location, and dispatch location. This information will provide us more specific data points to analyze trends in time, severity, location, dispatcher response time, etc.
