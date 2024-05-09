# "Beyond the Atmosphere: Computational Analysis of Rocket Paths”

For my project I will be comparing the velocities and times of two rockets with similar mass and height. The two rockets will be on different planets which means different gravity. 

Note: For the title i used Copilot's AI was used
## Introduction

Does it convince the reader that the project is worth their time? 

Include background information and some references

##**Background/ Motivation**:
I am motivated to solve this problem because as an engineer i love solving these types of problems that involve space.
The average gravitational pull of the Earth is 9.8 meters per second squared (m/s2). The Earth is made of different substances like air, rock, and water. These substances have a different amount of mass in a certain amount of space (density). For example, rock has a higher density than air.

It is weaker than Earth's gravity due to the planet's smaller mass. The average gravitational acceleration on Mars is 3.72076 m/s2 (about 38% of the gravity of Earth) and it varies.

- **Resources**
  - [Space X](https://www.spacex.com/)
  - [Earth](https://www.nsf.gov/news/classroom/images/Gravity.pdf)
  - [Mars](https://en.wikipedia.org/wiki/Gravity_of_Mars#:~:text=It%20is%20weaker%20than%20Earth's,of%20Earth)
  - [Projectile Motion](https://phys.libretexts.org/Bookshelves/University_Physics/Physics_(Boundless)/3%3A_Two-Dimensional_Kinematics/3.3%3A_Projectile_Motion#:~:text=The%20maximum%20height%20of%20an,visin%CE%B8g%20.)
  - [Diagram of Starship's internals](https://en.wikipedia.org/wiki/SpaceX_Starship#/media/File:Starship_internal_structure.jpg)

 ## Computational Model

Describe the model, its parameters and key equations.

How can you verify that your project works? 

---
**Description for Starship Rocket** 
- **Size**
  - Height of the Rocket: 121.3 m (398 ft)
  - Diameter of the Rocket: 9 m (30 ft)
  - Mass of the Rocket: 5,000 t (11,000,000 lb)
  - Engines: 74,400 kN (16,700,000 $lb_f$) of thrust 
  - Gravitational Constant: $6.674x10^-11 $
  - Earth's Gravitational pull: 9.8 $\frac {m}{s^2}$  
  - Mars Gravitational pull: 3.72076 $\frac {m}{s^2}$  
  - Mass of the Earth: $M_{Earth} = 5.9722x10^{24}kg$
  - Mass of Mars: $M_{Mars} = 6.4171x10^{23}kg$
  - Radius of Earth: $6371 x10^3 m$
  - Radius of Mars: $3389 x10^3 m$
 
  ---
$$\vec{F} = -G \frac {m_1*m_{Mars,Earth}}{(R+x)^2}$$
$r = R+h$
$$F_{net}=F_g+F_L = \frac{dp}{dt}$$


- **Description**
  - Gravitational Constant: $6.674x10^-11 $
  - $m_r$ (Mass of Rocket) = 5,000 t
  - $m_p$ = Mass of the Plants
  - Mass of the Earth: $M_{Earth} = 5.9722x10^{24}kg$
  - Mass of Mars: $M_{Mars} = 6.4171x10^{23}kg$

**Rocket equation** $$\Delta{v} = v_e*ln(\frac{m_o}{m_f})$$

- **Description**
  - $V_e$ = effective exhaust velocity = 
  - $m_o$ = initial mass
  - $m_f$ = final mass (after fuel is burnt)

**Escape Velocity** $$V_e = \sqrt{\frac{2GM}{R}}$$


- **Description**
  - G = gravitational Constant: $6.674x10^-11 $
  - M = Mass of the Planet
  - R = Planets Radius

Main Computation goes here (might need to save data)
Make sure the data is reproducible.

## Results and Discussion

List the question that you want to answer and follow up with a visualization of the result

Visualization Code goes here

- **Questions**
  - 1: What is the velocity of the rocket leaving Earth?
  - 2: What is the velocity of the rocket leaving Mars?
  - 3: What is the difference in time as they leave the atmosphere?
  - 4: Does weather play a big factor?
 
  ## Summary

Include a brief summary that includes the motivation and what you found. 

