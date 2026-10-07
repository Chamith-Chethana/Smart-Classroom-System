# Smart Energy Efficiency and Automated Control System for University Lecture Rooms

## Problem Statement

University lecture rooms can consume significant amounts of electrical energy through
lighting, fans, air conditioning, and other electrical equipment. These systems may
remain switched on when a room is empty or only partially occupied, and may operate
at full capacity regardless of the number of students present or the environmental
conditions.

This unnecessary energy consumption increases operating costs and contributes to
inefficient use of electricity. Because different groups of students and lecturers use
lecture rooms throughout the day, manually monitoring and controlling the equipment
is difficult. An automated system is therefore needed to monitor room occupancy and
environmental conditions, reduce unnecessary energy use, and maintain a suitable
environment for students and lecturers.

## Proposed Solution

This project proposes a Raspberry Pi-based smart energy-efficiency system for
university lecture rooms. The Raspberry Pi acts as the main processing and control
platform, while sensors monitor room occupancy and environmental conditions such as
temperature, humidity, and light intensity.

The system uses sensor readings to determine how selected electrical equipment
should operate. For example, when no occupants are detected for a specified period,
it can switch off unnecessary lights and other controllable equipment. It can also
adjust lighting based on the ambient light level instead of keeping lights on
continuously at full capacity.

Sensor measurements and energy-related data can be recorded over time. This data
can help identify periods of high energy consumption and evaluate the effectiveness
of the automated controls.

## Main Hardware Components

- **Raspberry Pi** — Main processing and control unit
- **PIR/occupancy sensor** — Detects whether people are present in the room
- **Temperature and humidity sensor** — Monitors room environmental conditions
- **LDR/light sensor** — Measures ambient light intensity
- **Relay modules** — Switches lights or other suitable electrical loads
- **Current/energy sensor** — Measures the electrical consumption of controlled loads
- **LED lamps, fans, or other low-voltage loads** — Prototype equipment representing
  actual room equipment
- **Power supply and supporting electronic components**

## Objectives

The main objective is to develop a Raspberry Pi-based automated system capable of
reducing unnecessary energy consumption in university lecture rooms.

The specific objectives are to:

1. Monitor lecture-room occupancy using suitable sensors and determine whether the
   room is in use.
2. Monitor environmental conditions, including temperature, humidity, and ambient
   light intensity.
3. Automatically control selected electrical loads, such as lighting and fans,
   according to occupancy and environmental conditions.
4. Measure and record energy consumption of controlled loads using an appropriate
   current or energy sensor.
5. Develop a monitoring interface or data-logging system to observe room conditions
   and energy usage over time.
6. Evaluate the energy-saving potential by comparing energy consumption before and
   after automated control is implemented.
7. Develop a low-cost prototype demonstrating how intelligent automation can improve
   energy efficiency in university facilities.

## Expected Outcome

The intended outcome is a working prototype that demonstrates more efficient
operation of lecture-room electrical equipment through occupancy detection,
environmental monitoring, automated control, and energy-consumption analysis.