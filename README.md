# Improving Campus Safety in the Purdue Bike Lanes

## Overview
This project aims to enhance transportation safety across Purdue University's campus, specifically focusing on reducing collisions between pedestrians and cyclists in bike lanes. Our solution, the Pedestrian Alert System, uses ultrasonic sensors and a TI microcontroller to alert pedestrians when a cyclist is approaching.

## Table of Contents
- [Project Overview](#project-overview)
- [Team Members](#team-members)
- [Problem Scoping](#problem-scoping)
- [Design Criteria and Constraints](#design-criteria-and-constraints)
- [Idea Generation](#idea-generation)
- [Prototyping and Testing](#prototyping-and-testing)
- [Final Design](#final-design)
- [Cost Estimate](#cost-estimate)
- [Lessons Learned](#lessons-learned)
- [References](#references)
- [Appendices](#appendices)

## Project Overview
Purdue University has contracted our team to improve transportation safety on campus. Our primary focus is on reducing bike-pedestrian collisions, which have been identified as a significant safety risk. Our solution, the Pedestrian Alert System, is designed to be cost-effective, durable, and scalable.

## Team Members
- Ashton Merriam
- Remley Hooker
- Avery Capps
- Nathaniel Laury

## Problem Scoping
### Problem Statement
Purdue University's campus experiences frequent collisions between pedestrians and cyclists, posing a significant safety risk. Our project aims to mitigate this issue by developing an effective and affordable solution.

### Design Criteria and Constraints
- **Inexpensive**: Cost per person affected should be minimized.
- **Effective**: Must significantly reduce the number of collisions.
- **Purdue Supported**: Must align with Purdue's infrastructure and aesthetic.
- **Microcontroller Functionality**: Must incorporate a TI microcontroller.
- **Longevity**: Solution should be durable and scalable for future use.

## Idea Generation
### Functional Decomposition
- **Main Function**: Alert pedestrians of approaching cyclists.
- **Sub-functions**: Sensing cyclist presence, triggering alerts, and providing visual and auditory signals.

### Exploring Prior Art
We reviewed existing solutions such as educational billboards, raised bike lanes, and bicycle-specific signals. Our solution integrates elements from these while addressing their limitations.

### Sketching and Low Fidelity Prototyping
We created sketches and prototypes to visualize and test our ideas, focusing on the Pedestrian Alert System, Veo Sensor, and Wearable Alert System.

## Prototyping and Testing
### Prototypes
- **Veo Sensor**: A sensor attached to bikes to detect pedestrians.
- **Pedestrian Alert System**: A sign with sensors and alerts placed at intersections.
- **Wearable Alert System**: A wristband that alerts pedestrians via GPS signals from bikes.

### Testing
We conducted surveys and tested prototypes to gather feedback. The Pedestrian Alert System received the highest stakeholder support and was selected for further development.

### Weighted Decision Matrix (WDM)
Our WDM evaluated the prototypes based on criteria like effectiveness, cost, and scalability. The Pedestrian Alert System scored the highest, confirming its suitability.

## Final Design
### Detailed Design
The final design includes:
- **Ultrasonic Sensors**: Detect approaching cyclists.
- **TI Microcontroller**: Processes sensor data and controls alerts.
- **LED Lights and Buzzer**: Provide visual and auditory warnings.
- **Durable Materials**: Ensure longevity and withstand weather conditions.

### Cost Estimate
- **Components**: $363.29
- **Installation**: $1000
- **Total**: $1363.29 per sign

### Design Optimization
- **Double-sided Design**: Detects cyclists from both directions.
- **Material Choices**: Minimizes weight and cost while ensuring durability.

### Trade-offs and Limitations
- **Noise Pollution**: Buzzer may contribute to noise pollution.
- **Environmental Impact**: Electronic components are not easily recyclable.
- **System Complexity**: Handling traffic from both directions may require an upgraded TI Kit.

## Lessons Learned
- **Strengths**: Effective idea generation and prototyping.
- **Improvements**: More thorough research and validation of ideas.
- **Teamwork**: Improved communication and division of tasks ensured timely completion.

## References
- [LED Traffic Signals](https://www.yakimawa.gov/services/streets/led-traffic-signals/)
- [Urban Transportation Safety Enhancement Strategies](https://www.microsoft.com/en-us/research/publication/urban-transportation-safety-enhancement-strategies/)
- [How Much Does a Street Light Cost?](https://www.ecosmartinc.com/how-much-does-a-street-light-cost/)
- [Crashes on and near college campuses](https://doi.org/10.1080/01944363.2014.978354)
- [Carbon Steel](https://agmetalminer.com/metal-prices/carbon-steel/)
- [Billboards on the sides of buses](https://highways.dot.gov/public-roads/julyaugust-2017/focused-approach-pedestrian-and-bicycle-safety)
- [Raised Bike Lane](https://www.transportation.gov/pedestrian-bicycle-safety)
- [Speed Bump Effectiveness](https://www.trafficsafetywarehouse.com/Resources/speed-bumps-how-effective-are-they.asp)

## Appendices
- [Purdue's Transportation Problems (Responses)](Purdue_Transportation_Problems_Responses.xlsx)
- [Stakeholder Prototype Responses](Stakeholder_Prototype_Responses.xlsx)
- [Weighted Decision Matrix](ENGR_131_A16_DesignProject_WDM_19.xlsx)
