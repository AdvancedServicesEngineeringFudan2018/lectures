# Advanced Services Engineering, Summer 2018 for Fudan University

The Advanced Services Engineering (ASE) is a course lectured by [Hong-Linh Truong](http://www.infosys.tuwien.ac.at/staff/truong) at [TU Wien](http://www.infosys.tuwien.ac.at/teaching/courses/ase/) since many years. This site includes lecture notes and other information about the ASE course carried out in Summer 2018 for Fudan University in the FIST program through the visiting professor of Hong-Linh Truong.

The ASE Course at Fudan University is jointly run by [Hong-Linh Truong](http://www.infosys.tuwien.ac.at/staff/truong) and [Liang ZHANG (Leon)](http://www.cs.fudan.edu.vn/en/?page_id=2303).

The course is carried out in a combination of conventional lecture, hackathon and summer school work.

**The key activities are: learn lecture materials, discuss topics, design software services, and coding the design everyday during the lecture period, following the DevOps and agile principles, resulting in not only knowledge gained but also a mini open-source prototype.**


The detailed program is [listed here](ase-fist2018-overview.pdf). The material for the course is mainly based on the previous ASE courses at TU Wien, with some customization and specific issues suitable for Fudan students.

# Lectures

## Lecture 1: Emerging distributed systems and challenges for services engineering


### Lecture content

We will discuss about challenges for services engineering given the emerging types of distributed systems and platforms. We especially look at real-world examples to learn the key elements of complex software services.

Download [the slides of the lecture](truong-ase-fudan-2018-lecture1-dss-challenges.pdf).

### Lab on identifying scenarios (requirements, datasets, and business models)

Students have to create their git project with basic readme file. They have to work on the high-level scenario of their mini project. Furthermore, they should be able to gather resources (existing cloud services, data sets, etc.) for they project.

All the information will be available in the git project. Here is [an example of the template for the scenario description](ase-scenario-template.pdf).

**Note: by 11.30, July 12, 2018 (extended to 13.30), we should have the initial scenario for each team in the Git. Each team should have  2-3 members.**

## Lecture 2: The role of IoT, Cloud systems, Blockchain and Machine Learning as a service
### Lecture content

We examine the role of clouds, IoT, machine learning and blockchain in a complex software service system and try to understand how we can leverage them for building complex software services.

Download [the slides of the lecture](truong-ase-fudan-2018-lecture2-IoTCloudMLBlockchainSystems.pdf).

### Lab: Lab on identifying application-specific services and platform services, presentation of scenarios and services

Students should be able to identify key application-specific services and platform services. They should be able to show their initial scenario and services. They should be aware that the scenario and its services will be evolved.

So what do we expect from this lab:

* Outline main building blocks of your scenario
* Outline platform services and application services
* Outline data and possible ways for having data for the scenario

These points can be described into a document about the design of the  scenario.

## Lecture 3: Data as a Service, Data Marketplace and Data Lake – Models, Data Concerns and Engineering

### Lecture content

We examine models of data-as-a-service, data marketplace and data lakes. We study possible data concerns associated with data.

Download [the slides of the lecture](truong-ase-fudan-2018-lecture3-daas_datalake_datamarket_dataconcerns.pdf).

### Lab: Lab on designing data sources for the scenario and data concerns

Data sources for the mini project/scenario will be data-as-a-service, data marketplace or data lakes. Students should be able to make sure that their components will receive data from such sources (e.g., Tracking data, Weather information) with well-defined interfaces and protocols. For this, students may need to build DaaS wrapping existing/simulation data sources.

Second, students must be able to identify some key important data concerns (e.g., data quality) and they must be able to consider data concerns in the scenario, e.g., remove bad data or check bad data and run suitable algorithms for processing bad data.

**Lab report: at 14:00 students will report their initial decision/design on data concerns for their project.**

## Lecture 4: Big data service systems: Models and Platforms

### Lecture content

We examine existing big data service systems. In particular, we focus on state-of-the-art systems and how to design elasticity with these systems.

Download [the slides of the lecture](truong-ase-fudan-2018-lecture4-bigdatasystems.pdf).

### Lab: Lab on design and develop analytics features

In this lab, students will work on data ingestion and analytics features for their scenario. From the data sources in the previous lab, data will be ingested or analyzed by some services developed by students. This lab concentrates on the data processing of data from these sources.

**Lab report: at 16:30 a short (5 minutes each team) report for the possible services/frameworks for data analytics within the project.**

**Lab: we continue to the present the design and discussion in next Monday 16 July**

## Lecture 5: Principles of Elasticity for Service systems

### Lecture content

Students will learn basic ideas of elasticity for service systems.

Download [the slides of the lecture](truong-ase-fudan-2018-lecture5-elasticity.pdf).


## Lecture 6: Quality-aware data analytics services

### Lecture content

We examine existing big data service systems. In particular, we focus on state-of-the-art systems and how to design elasticity with these systems.

Download [the slides of the lecture](truong-ase-fudan-2018-lecture6-qorda.pdf)

### Lab: incorporating quality-aware features and elasticity into services

In this lab, students will examine quality features in their services and define elasticity functions for their services. Such functions will be implemented through service models, such as offering higher quality results given higher price and less response time.

## Lecture 7: Engineering Human-based Services in Hybrid Computing  Systems

### Lecture content
We examine the role of human-in-the-loop in complex services.

Download [the slides of the lecture](truong-ase-fudan-2018-lecture7-humandataanalytics.pdf)

### Lab: incorporating human-in-the-loop

In this lab, students will find suitable tasks that need human capabilities. And then students will implement a feature that invokes human to perform the task.

## Project discussion session
We run a project discussion session where we ask students:

* what has been achieved? can you show some results?
* what are the main obstacles?
* who does what: plan and responsibility

students have presented and clarified their work and we work on helping students to move on with their projects.

## Lecture 8: Ensembles of IoT, Network functions and Clouds

We discuss the new research direction on ensembles for IoT, network functions and clouds.

Download [the slides of the lecture](truong-ase-fudan-2018-lecture8-ensembles.pdf)

# Demo Day

The demo day will be 18 July 2018. Students will present project presentation and demonstrate their work.

# Student Projects

During the course, students will have to propose a mini project and implement the project within the course. The list of the [student project can be found here](https://github.com/AdvancedServicesEngineeringFudan2018). Several examples of previous ASE projects from other students can be found from http://www.infosys.tuwien.ac.at/teaching/courses/ase/.

During the intensive schedule of the course, student projects are running like a hackathon: everyday students will have to code and update their git project incrementally. At the end of the course, we will run a demo session where we will see the project.

# Lessons Learned

We have [some lessons learned that we document here](Lessonslearned.md)
# Other resources

* The [TU Wien Advanced Services Engineering course](http://www.infosys.tuwien.ac.at/teaching/courses/ase/)
* The [TU Wien Distributed Systems Technologies course](http://www.infosys.tuwien.ac.at/staff/truong/dst/) lectures many technologies, design patterns and examples.
* [IoTCloudSamples](https://github.com/rdsea/IoTCloudSamples) as a collection of IoT, Cloud and Network function services and service systems.
* [Examples](https://github.com/linhsolar/distributedsystemsexamples) of distributed systems and applications code
* [TU Wien student project ASE 2018](https://github.com/AdvancedServicesEngineeringTUWien2018)
* [TU Wien student project ASE 2017](https://github.com/AdvancedServicesEngineeringTUWien2017)
* [TU Wien student project ASE 2016](https://github.com/AdvancedServicesEngineeringTUWien2016)
