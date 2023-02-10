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


 
 
 
