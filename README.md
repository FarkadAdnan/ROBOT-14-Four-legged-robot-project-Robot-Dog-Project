# ROBOT-14-Four-legged-robot-project-Robot-Dog-Project
Chapter 2 code_Project_14 The Third Part 3 of "The Arduino World Book" code_Project_14 ROBOT-14-Four legged robot project - Robot Dog Project
- code_Project_14

-  By:Farkad Adnan فرقد عدنان -
- https://linktr.ee/farkadadnan

 - E-mail: farkad.hpfa95@gmail.com 
- inst : farkadadnan 
- #farkadadnan , #farkad_adnan , فرقد عدنان# 
- FaceBook: كتاب عالم الاردوينو 
- inst : arduinobook
1. #كتاب_عالم_الاردوينو
2. #كتاب_عالم_الآردوينو 

* facebook : https://www.facebook.com/profile.php?id=100002145048612
* instagram:  https://www.instagram.com/farkadadnan/
* linkedin : https://www.linkedin.com/in/farkad-adnan-499972121/

 <p>
 <a href='https://mobile.twitter.com/farkadadnan'>
        <img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/farkadadnan?label=%40farkadadnan&style=social" alt='Twitter' align="center"/>
    </a>
</p>


# Project Structure
-بناء وتصميم روبوت رباعي الارجل قادر على الحركة من خلال لوحة التحكم واداء حركات مختلفة في بيئات مختلفة وكما موضح في الشكل التالي :

- Building and designing a four-legged robot capable of moving through the control panel and performing different movements in different environments, as shown in the following figure:



![FYV2NDKKAL2UERYب](https://user-images.githubusercontent.com/35774039/218168231-b4fc9042-b464-4aac-9398-2c84f6bd58f0.PNG)



# Robot Dog Designed

* https://social.thangs.com/m/709268




![3](https://user-images.githubusercontent.com/35774039/218171803-f8d3672a-c593-47e7-9225-c4a74621c4c8.PNG)
 
 # The mathematical part
 
 ![FO08O1TKAL2UES0](https://user-images.githubusercontent.com/35774039/218172325-e3ca2a0e-e28d-4f34-8786-eeb33cf4ffd0.png)
![FNJ2ZL5L42QVBO8](https://user-images.githubusercontent.com/35774039/218172344-13637a3e-8e74-4580-b093-349afb1fe3a9.png)
![IKBezier](https://user-images.githubusercontent.com/35774039/218172356-0f980730-31c0-4ed8-8a7b-ad562c086671.png)

 
 # Results
 ![spot_yaw](https://user-images.githubusercontent.com/35774039/218203628-22312a1f-05d3-4baf-ba42-851e7b039ee1.gif)
![spot_bezier](https://user-images.githubusercontent.com/35774039/218203643-d49791cb-7bf1-4050-a783-437efe7fb02b.gif)

 # Training Models in Simulation
To train a policy using randomized robotic morphologies, run the following command:
```

python3 motion_imitation/run.py --mode train --randomized_robot --phase_only --int_save_freq 10000000 --timesteps_per_actorbatch 8192 --optim_batchsize 512 --visualize
```
- --int_save_freq specifies the frequency for saving intermediate policies every n policy steps.

- --visualize enables visualization, and rendering can be disabled by removing the flag.

- the trained model and logs will be written to output/.



![inversed](https://user-images.githubusercontent.com/35774039/218204482-0c15cd94-8aaf-4bf9-acea-dd40189aeefc.gif)



 # Here’s a system diagram and algorithm for the D2 -GMBC process:
 
 
![GMBC_ALGO](https://user-images.githubusercontent.com/35774039/218204924-691664bf-f2a6-41ec-9bb0-7f40b9dda5e5.png)
![GMBC_SM](https://user-images.githubusercontent.com/35774039/218204927-4be08cab-094f-47f7-b87a-46f169c4e3a0.png)


# Conclusion
In this project, Farkad Adnan presented the design and simulation, in a 3D environment, of a simple four-legged robot modeled on CAD and Matlab. The quad has passive knees and a spine made by passive joints, which are provided by rotational springs. Each leg has one active DOF which is driven by a commercial servo motor, SG90. Adjusting the spring stiffness in the legs and spine allows the behavior of the system to be modified. With proper calibration, it is possible to obtain a reduction in the energy required for robot movement, which leads to an increase in system performance. In conclusion, we found that with the right combination of stiffness springs in the knees and spine, it is possible to obtain better performance. However, the effect of spine stiffness in relation to leg stiffness is higher if the ultimate goal is to increase robot performance in terms of reducing energy consumption and allowing optimal redistribution of energy in the entire robotic system.



 # References
- Alexander, R. (1990). Three uses for springs in legged locomotion. Int. J. Robot. Res. 9, 53–61. doi: 10.1177/027836499000900205
- Alexander, R. M. (1984). Elastic energy stores in running vertebrates. Am. Zool. 24, 85–94. doi: 10.1093/icb/24.1.85
- Blickhan, R. (1989). The spring-mass model for running and hopping. J. Biomech. 22, 1217–1227. doi: 10.1016/0021-9290(89)90224-8


- Boston Dynamics (2017). Introducing Handle. Available online at: https://www.youtube.com/watch?v=-7xvqQeoA8cs (accessed January 21, 2020).


- Buchli, J., Iida, F., and Ijspeert, A. J. (2006). “Finding resonance: adaptive frequency oscillators for dynamic legged locomotion,” in 2006 IEEE/RSJ International Conference on Intelligent Robots and Systems (Beijing: IEEE), 3903–3909. doi: 10.1109/IROS.2006.281802


- Chatzakos, P., and Papadopoulos, E. (2007). “Parametric analysis and design guidelines for a quadruped bounding robot,” in 2007 Mediterranean Conference on Control & Automation (Athens: IEEE), 1–6. doi: 10.1109/MED.2007.4433668


- Culha, U., and Saranli, U. (2011). “Quadrupedal bounding with an actuated spinal joint,” in 2011 IEEE International Conference on Robotics and Automation (Shanghai: IEEE), 1392–1397. doi: 10.1109/ICRA.2011.5980176


- Deng, Q., Wang, S., Xu, W., Mo, J., and Liang, Q. (2012). Quasi passive bounding of a quadruped model with articulated spine. Mech. Mach. Theory 52, 232–242. doi: 10.1016/j.mechmachtheory.2012.02.003


-  Eckert, P., Spröwitz, A., Witte, H., and Ijspeert, A. J. (2015). “Comparing the effect of different spine and leg designs for a small bounding quadruped robot,” in 2015 IEEE International Conference on Robotics and Automation (ICRA) (Seattle, WA: IEEE), 3128–3133. doi: 10.1109/ICRA.2015.7139629


- Gehring, C., Coros, S., Hutter, M., Bloesch, M., Hoepflinger, M. A., and Siegwart, R. (2013). “Control of dynamic gaits for a quadrupedal robot,” in 2013 IEEE International Conference on Robotics and Automation (Karlsruhe: IEEE), 3287–3292. doi: 10.1109/ICRA.2013.6631035


- Khoramshahi, M., Spröwitz, A., Tuleu, A., Ahmadabadi, M. N., and Ijspeert, A. J. (2013). “Benefits of an active spine supported bounding locomotion with a small compliant quadruped robot,” in 2013 IEEE International Conference on Robotics and Automation (Karlsruhe: IEEE), 3329–3334. doi: 10.1109/ICRA.2013.6631041


- Muscolo, G. G., Caldwell, D., and Cannella, F. (2017). “Biomechanics of human locomotion with constraints to design flexible-wheeled biped robots,” in 2017 IEEE International Conference on Advanced Intelligent Mechatronics (AIM) (Munich: IEEE), 1273–1278. doi: 10.1109/AIM.2017.8014193


 
