# 🤔 What this is
This github repo is a collection and backup of all our code for the NERC robotics competition. It also contains a catalog for all tested and future ideas.

# 💡 How it works
- All ideas (wheather they have been implemente in code or not) for  ways to complete the entire race track are named as I1, I2, I3, I4, etc
- Implemented ideas have their code uploaded above and each new version is saved such that older versions can be viewed at any time.

# 🗨️ Abbreviations and terminology used
- All segments of the entire track have been labelled from A to F as shown in the diagram with the red text
- All corners are named by the two segments they goin as shown in the diagram with the green text
- 
![diagram](https://github.com/ahmadsb86/NERC/assets/33711947/6ca88d35-068f-4aca-b06e-4da3d7d582bd  | width=100)


# I1 (Implemented)
**Description**: Fully hardcoded route

**Best time**: 

**Known Issues**
- Terribily inconsistent with turns
  

# I2 (Implemented)
**Description**: Full Gyro route w/ front sonar for timing AB, BC and CD turns

**Best time**: approx. 12 seconds

**Known Issues**
- Occasionally early turning @ B and C segment (possibily due to using sonar instead of ir)
- Highly inconsistent horizontal positioning @ C segment

**Sub Versions**
- **I1.1**: Using IR instead of sonar
- **I1.2**: Using color sensor for AB turn


# I3 
**Description**: Full line following route with 4 color sensors

**Best time**:

**Known Issues**

# I4
**Description**: Line follow until T2 after which gyro for straight movement & front sonar for turns

**Best time**:

**Known Issues**

**Sub Versions**
- **I4.1**: Using hardcode after T2 instead of front sonar readings.

# I5
**Description**: Line follow untill AB turn. Then line follow BC Curve for a fixed time. Lane change to left slightly to get in line with T2. Then use gyro to move straight and complete route (and turn w/ front sonar readings)

**Best time**:

**Known Issues**

**Sub Versions**
- **I5.1**: Using hardcode after T2 instead of front sonar readings.



# I6
**Description**: Color sensor & gyro for a slight turn at AB and then aligning position at flat line @ C w/ color sensor. After aligning, use gyro to face forward and complete route.

**Best time**:

**Known Issues**


