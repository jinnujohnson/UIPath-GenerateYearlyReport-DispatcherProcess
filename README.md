# RPA Project Using UIPath Studio and Orchestrator

This is an Automation Project using UIPath Studio and Orchestrator. Project is built upon REFramework template.


## About Generate Yearly Report

This project is used to generate yearly report for a vendor by collecting monthly reports and uploading the final report and thereby updating the status by unique Id. 
Here Orchestrator Queue is used to process each and every transaction items by using multiple Robots. Two processes are used- Dispatcher and Perfomer. Dispatcher is used to dispatch transaction items to Orchestrator Queue and Performer is used to process the items generated in the previous step.

