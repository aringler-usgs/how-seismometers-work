**Retrieving Signals from a Noisy World: How seismometers work**

This workshop will provide an overview of how seismic instrumentation works. It will overview how raw ground motion is sensed by a seismic sensor and then converted from digital counts to more tangible units of velocity or acceleration. We assume no prior knowledge of seismic instrumentation or data collection methods, making it ideal for graduate students or anyone interested in understanding how seismic data is recorded. The goal is to provide participants with basic understanding of how seismic data is recorded, how the instrumentation works, as well as possible pitfalls and complications that can arise in the process. By better understanding the physical and electronic limitations of seismic instruments, we hope that participants will have a better grasp on limitations of processing and interpreting the seismic data. Hands on exercises will help participants gain exposure to working with seismic data from the perspective of the instrument. 

Participants will learn:
- Elements of modern seismic sensors
- Some of the limitations in modern seismometers (e.g. self-noise) as well as how the response of the instrument works
- Basic knowledge of how seismometers with force-feedback electronics work and will understand differences between symmetric triaxial (Galperin) and conventional triaxial sensor element configurations
- Properties of seismic sensors such as dynamic range, gain, and damping
- How sensors are built and created

This git repository will contain the teaching materials for this course and will include a number of Python notebooks. We will add and update the content of this page as we get closer to the meeting.

**Course agenda:**
- Welcome notes, Motivations, and Introductions (5 min)

- Part I: Seismic sensors and their structure (Akram Mostafanejad, PASSCAL)
  - Seismic sensors in time; physics and history review
  - Seismic sensors; the sensing elements
  - Short break
  - Python jupyter notebook exercise
  - Electronic force balance seismic sensors
  - Q&A
- Part II: Seismic Instrument Response and Response Removal (Rob Anthony, USGS)
  - Introduction to Seismic Instrument Responses
  - Where to find Responses and how to read RESP files
  - Useful Links
    QSPA Station Information from IRIS http://ds.iris.edu/mda/IU/QSPA/
    
    QSPA GS-13 Information http://ds.iris.edu/mda/IU/QSPA/85/HHZ/?starttime=2011-01-18T00:00:00&endtime=2599-12-31T23:59:59
    
    QSPA GS-13 Response File http://service.iris.edu/irisws/resp/1/query?net=IU&sta=QSPA&loc=85&cha=HHZ&starttime=2011-01-18T00:00:00&endtime=2599-12-31T23:59:59
    
  - Exercise 1 on Response Removal (Python Jupyter Notebook )
In case you are interested in what generated this seismic
signal:
USGS Event Page for M 6.0 Balleny Islands Event
https://earthquake.usgs.gov/earthquakes/eventpage/us7000clt8/executive

  - Exercise 2 using NRL to make your own response and verify that you got it right! (Python Jupyter Notebook)
  Use Nominal Response Library (Thanks Mary Templeton!!!) for this
exercise: http://ds.iris.edu/NRL/
 Here’s the earthquake you’re looking at to verify your response:
https://earthquake.usgs.gov/earthquakes/eventpage/us7000bq10/executive
- Part III: Instrument Specifications and why we should care (Adam Ringler, USGS)
  - What do we want to record?
  - Basic Specifications
  - How do they relate to modern seismology
  - Beyond specifications
  - Exercise on self-noise (Python Jupyter Notebook)
 - Summary, wrap up, and Q&A (10 min)  Feedback and evaluation (10 min)

