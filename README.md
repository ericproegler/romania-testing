# romania-testing
Presentation links and code for Romania Testing Conference Workshop - 16 June, 2022

Includes Links to resources, and JMeter code for running tests. If you attended the Workshop, remember your Lifetime Guarantee!

## JMeter Downloads and Dependencioes

This is what you need to participate in this part of the workshop. If you are blocked by your employer's security requirements or Java depenency issues, please work with a neighbor - we can't spend much time troubleshooting Java.

### Java 8

If you already have Oracle Java, you can check your current Java version in the Java control panel for: 
Windows: https://www.java.com/en/download/help/win_controlpanel.html 
Mac: https://www.java.com/en/download/help/mac_controlpanel.html
Linux: You like being on your own and figuring things out

If you do not already have Java installed, you will need Java 8. Java.com link: https://www.java.com/en/download/.

If you object to Oracle's licenese, OpenJDK is your best option: https://openjdk.java.net/. 

### JMeter 5.4.3

Download the JMeter Binary here: https://jmeter.apache.org/download_jmeter.cgi. 5.4.3 is the version tested for the workshop. Extract this directory.

## The JMeter Script

For the workshop, we are using a script from the tutorial BlazeMeter provides here: https://www.blazemeter.com/blog/getting-started-jmeter-basic-tutorial

The script files we need are BlazeDemo.jmx and cities.csv, found in this repo. Please download them and place it in the /apache-jmeter-5.4.3/bin/examples/ folder. 

BlazeMeter is a public test cloud for running JMeter scripts at scale, across geographies. I have used it to successfully load test with hundreds of thousands of concurrent users. Learn more at https://www.blazemeter.com/. 

There are other load tools and test cloud providers, and many of them are excellent.  

## Thanks

If you did not attend my workshop, I am still willing to help. Find me here https://www.linkedin.com/in/eproegler/ or here https://twitter.com/3r1c_p 
