```python
import datetime
from enum import Enum
from dataclasses import dataclass


class Progress(str, Enum):
    ONGOING = "Ongoing"
    HALTED = "Halted"
    FINISHING = "Finishing"
    FINISHED = "Finished"
    ABANDONED = "Abandoned"

@dataclass
class About_me:
    name: str = "Miel Villyn"

    interests: list[str] = [
        "Space",
        "Learning",
        "Coding",
    ]

    degrees: list[str] = [
        "Bachelor Energymanagement",
    ]

    degrees_in_progress: list[str] = [
        "Bachelor Electronics-ICT",
    ]

    member_since: datetime.datetime = datetime.datetime(2023, 3, 16)

    known: list[str] = [
        "Python",
    ]

    learning: list[tuple[str, Progress]] = [
        ("C", Progress.ONGOING),
        ("C#", Progress.HALTED),
        ("Rust", Progress.HALTED),
    ]

    future_plans: list[str] = [
        "C++",
        "JavaScript",
        "Java",
    ]

# Projects
class IMU_FBT:
  def __init__(self, *args, **kwargs):
    """
    A fully custom implimentation of Full Body Tracking for VRChat using IMU's (Inerial Mesurement Unit)
    to send data over OSC (Open Sound Controll) to the game.
    """
    pass

  def status(self):
    return Progress.HALTED

class Minecraft_server_autostarter:
  def __init__(self, *args, **kwargs):
    """
    A minecraft server Autostart and autointegrate application that allows the user to drag in a server.jar file and
    for it to automaticaly start up or create the server on network command.

    MOTD spoofing is used to allow the client to see if a server is starting or if it is offline.
    """
    pass

  def status(self):
    return Progress.HALTED

class OSC_Library:
  def __init__(self, *args, **kwargs):
    """
    Making an easier to use client and server for OSC (Open Sound Controll).
    """
    pass

  def status(self):
    return Progress.FINISHING

class IMBT_manager_app:
  def __init__(self, *args, **kwargs):
    """
    Making a wireless connection Management platform to change settings over the air on the IMU-FBT tracker.
    """
    pass

  def status(self):
    return Progress.HALTED

class Home_energy_mannager:
  def __init__(self, *args, **kwargs):
    """
    Building a tool to automatical manage energy consumption,
    use **BES** technology to attempt to catch as much Solar energy and **prevent** injection to the grid.
    using a schedule run through the available energy consumers and controll them in case of overproduction of energy.
    """
    pass

  def status(self):
    return Progress.HALTED
```

<!---
- 👋 Hi, I’m Miel Villyn
- 👀 I’m interested in the cold emptyness of the void called space
- 👀 I realy love learning about anything, in my own way.
- 📖 I have a bachelors degree in Energymanagement
- 🌱 I’m currently a student at Vives (Electronics-ICT Bachelor)
- Member since March 16 2023
- 🧑‍💻 I mainly know python
- 🧑‍💻 learing C
- 🧑‍💻 learning C# ⏸️
- 🧑‍💻 learing Rust ⏸️
- 🧑‍💻 planing to learn C++, Javascript and JAVA

# projects in the working
## 1.Project IMU-FBT ⏸️

A fully custom implimentation of Full Body Tracking for VRChat using IMU's (Inerial Mesurement Unit) to send data over OSC (Open Sound Controll) to the game.

## 2.Project Autostart

A minecraft server Autostart and autointegrate application that allows the user to drag in a server.jar file and for it to automaticaly start up or create the server on network command.

MOTD spoofing is used to allow the client to see if a server is starting or if it is offline.

## 3.Project OSC ⏸️

Making an easier to use client and server for OSC (Open Sound Controll).

## 4.Project Mannager ⏸️

Making a wireless connection Management platform to change settings on the IMU-FBT tracker.

## 5.Home Energy Mannager

Building a tool to automatical manage energy consumption, use **BES** technology to attempt to catch as much Solar energy and **prevent** injection to the grid. using a schedule run through the available energy consumers and controll them in case of overproduction of energy.

--->

<!---
Danktempest69/Danktempest69 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
