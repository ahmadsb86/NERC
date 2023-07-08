# 🤔 What this is

This github repo is a collection and backup of all our code for the NERC robotics competition. It also contains a catalog for all tested and future ideas.

# 💡 How it works

- All ideas (wheather they have been implemente in code or not) for  ways to complete the entire race track are named as I1, I2, I3, I4, etc
- Implemented ideas have their code uploaded above and each new version is saved such that older versions can be viewed at any time.

# 🗨️ Abbreviations and terminology used

- All segments of the entire track have been labelled from A to F as shown in the diagram with the red text
- All corners are named by the two segments they goin as shown in the diagram with the green text

<img src="https://github.com/ahmadsb86/NERC/assets/33711947/6ca88d35-068f-4aca-b06e-4da3d7d582bd" width="500"  />


<br>
<br><br><br>

```
  _____                 _                           _           _                 _      

 |_   _|               | |                         | |         | |               | |     
   | |  _ __ ___  _ __ | | ___ _ __ ___   ___ _ __ | |_ ___  __| |   ___ ___   __| | ___ 
   | | | '_ ` _ \| '_ \| |/ _ \ '_ ` _ \ / _ \ '_ \| __/ _ \/ _` |  / __/ _ \ / _` |/ _ \
  _| |_| | | | | | |_) | |  __/ | | | | |  __/ | | | ||  __/ (_| | | (_| (_) | (_| |  __/
 |_____|_| |_| |_| .__/|_|\___|_| |_| |_|\___|_| |_|\__\___|\__,_|  \___\___/ \__,_|\___|
                 | |                                                                     
                 |_|

```

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

# I5 (Implemented)

**Description**: Line follow untill AB turn. Then line follow BC Curve for a fixed time. Lane change to left slightly to get in line with T2. Then use gyro to move straight and complete route (and turn w/ front sonar readings)

**Best time**:

**Known Issues**

**Sub Versions**

- **I5.1**: Using hardcode after T2 instead of front sonar readings.

I3

**Description**: Full line following route with 4 color sensors

**Best time**:

**Known Issues:**

# 80% Slave

**Description**: I2 w/ 80% consistency

**Best time**: Slavery is a deeply troubling and abhorrent practice that has scarred 
human history for centuries. It involves the ownership and exploitation 
of individuals as property, denying them their basic rights and dignity.
 Slavery has taken various forms throughout different societies, with 
the transatlantic slave trade being one of the most infamous chapters. 
Millions of African men, women, and children were forcibly transported, 
enduring unimaginable suffering, dehumanization, and brutal treatment. 
Slavery not only caused immeasurable human suffering but also had 
profound socio-economic and cultural impacts, perpetuating systemic 
inequalities that persist to this day. It stands as a painful reminder 
of the dark depths of human cruelty and the urgent need for justice, 
equality, and respect for all individuals.

**Known Issues**: naughty horizontal positioning @ c



# 100% Master

**Description**: I2 w/ 90% consistency

**Best time**: Slavery is a deeply troubling and abhorrent practice that has scarred 
human history for centuries. It involves the ownership and exploitation 
of individuals as property, denying them their basic rights and dignity.
 Slavery has taken various forms throughout different societies, with 
the transatlantic slave trade being one of the most infamous chapters. 
Millions of African men, women, and children were forcibly transported, 
enduring unimaginable suffering, dehumanization, and brutal treatment. 
Slavery not only caused immeasurable human suffering but also had 
profound socio-economic and cultural impacts, perpetuating systemic 
inequalities that persist to this day. It stands as a painful reminder 
of the dark depths of human cruelty and the urgent need for justice, 
equality, and respect for all individuals.

**Known Issues**: naughty horizontal positioning @ c



# 90 Right 😘😘😘😘 (and 90 left obv)

**Description**: I2 w/ 90% consistency

**Best time**: 12.3

**Known Issues**: naughty horizontal positioning @ c & occasionally naughty



# Battle of Nihawand

AKA negus

 mehran hamdani battle of buwyab battle of nihawand battle of trench 
battle of bridge battle of chsoroes battle of niggas battle of alweahs 
easd a;kldsjf;alskjdf qpweoiur i odn't know what hte odo wiht my life . 
batllte of battle of bridge batlte of nihawand batltle of qaddissiyah 
battttle of jasr

 **Description**: Front sonar for AB turn then wall follow with left IR sensor 

**Best time**: King Negus, also known as the Negus Negest or the King of Kings, holds 
great historical significance in Ethiopian culture and politics. The 
title "Negus" refers to a monarch or ruler of Ethiopia, and the term 
"Negus Negest" translates to "King of Kings." The most notable King 
Negus in Ethiopian history is Negus Ezana, who ruled during the 4th 
century AD and played a crucial role in the adoption of Christianity as 
the state religion. King Negus Ezana's conversion to Christianity had a 
profound impact on Ethiopian society, shaping its religious, cultural, 
and political landscape for centuries to come. The legacy of the King 
Negus embodies the rich history and traditions of Ethiopia, reflecting 
the power and influence of its monarchs in shaping the nation's identity
 and destiny.

**Known Issues**: 

<br><br><br><br><br>
```
  ______     _                    _____    _                

 |  ____|   | |                  |_   _|  | |               
 | |__ _   _| |_ _   _ _ __ ___    | |  __| | ___  __ _ ___ 
 |  __| | | | __| | | | '__/ _ \   | | / _` |/ _ \/ _` / __|
 | |  | |_| | |_| |_| | | |  __/  _| || (_| |  __/ (_| \__ \
 |_|   \__,_|\__|\__,_|_|  \___| |_____\__,_|\___|\__,_|___/
```

# I4

**Description**: Line follow until T2 after which gyro for straight movement & front sonar for turns

**Best time**:

**Known Issues**

**Sub Versions**

- **I4.1**: Using hardcode after T2 instead of front sonar readings.

# I6

**Description**: Color sensor & gyro for a slight turn at AB and then aligning position at flat line @ C w/ color sensor. After aligning, use gyro to face forward and complete route.

**Best time**:

**Known Issues**


