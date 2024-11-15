## Model Description 
We can determine the LOS, RFC, and entry capacity of an unsignalized junction by using the ARCADY software. Here, we'll utilize LinSIG software to determine the degree of saturation flow and delay for a cycle time on Motorway A6120 (Ring road) and Low Lane Road Junction Roundabout for year 2029 forecast future demand design.
## Model Input Data
AutoCAD with Google Earth Pro used to find the geometric parameters, As seen in Figure 1 below, Arms are categorized according to their direction: Arm A is Low Lane North bound, Arm B is A6120 east bound, Arm C is Low Lane South bound, and Arm D is A6120 west bound. 
Figure 1: Geometric Parameters of junction
![image](https://github.com/user-attachments/assets/4ec30d75-d361-476e-a024-6cf905b76738)
For model, saturation flow of 1900 PCU\hr used instead of lane and radius parameter. Custom connector length is required in order to calculate the mean cruise time of a lane connector with a cruise time of 10 m/sec. Here, the circular lane's length is 110 meters. Since there are now four circulatory lanes, 110/4=27 meters were formed. Demand flows for Turning Proportions are predicted for design year 2029 period of 7.30 to 8.30 AM (Table 1). U turn flows and pedestrian traffic are not taken for considerations. Exit lane of Arm A, C and D has 6m in length, so Two lane of 3m each are added in model (Figure 1). 
Table 1: Predicted design flow demand for 2029
![image](https://github.com/user-attachments/assets/b693bbf1-bf6e-4e5b-bfa9-24ed7652ab95)
## Description of the Modelling work
created phases A, B, C, D as entry arms and E, F, G and H as circulatory arm as shown in Figure 3 and assigned with 4 streams and 2 stages each with alternative with conflicting points. In stages, for each stream assigned with stages 1 and 2 as shown in Figure 4 .  Inter green of 5 sec provided in Inter green views. 
Figure 2: Network layout view
![image](https://github.com/user-attachments/assets/bee5918a-b293-4b0a-a1e5-bdae3d67fdda)
Figure 3: Phase Diagram
![image](https://github.com/user-attachments/assets/0962ab83-a5ee-4bdd-98a6-28aeefd1bf5a)
## Analysis of Modelling Results
Table 2 : PRC and Delay Values of Scenario for 60 and 90 sec cycle time
![image](https://github.com/user-attachments/assets/caede5b3-db43-420e-99e2-f175148b020f)
Table 3: PRC and Delay in each stream for 60 sec (left) and 90 sec (right)
![image](https://github.com/user-attachments/assets/f8d1fc0e-53f4-4099-b081-d93926f313ae)![image](https://github.com/user-attachments/assets/d6fe4766-3bea-41e7-b231-769e19ea6cac)
In Table 2, PRC value for 60 sec Cycle time is 1.9% with delay of 49.92 PCU/hr and 90 sec cycle time shows 2.0 % delay with 60.76 PCU/Hr
From Table 3, stream 1 (arm A) has lowest PRC value and rest stream working with good PRC value. So, improvement should be needed in Arm A lanes
Figure 5: Network layout with Queue and Flow Graph for scenario 1( 60 sec)
![image](https://github.com/user-attachments/assets/5f7ebeea-ebd0-48a0-a909-f024555beada)
In Figure 7, phase A, E, C, G and phases H, B, F, D running parallelly as to avoid the conflicts. For 90 sec phase diagram, stream 1 starts with 0 -5 sec inter green and 5 to 42 sec phase A running and stream 2 starts 42 to 47sec inter green then H phase runs till 90 sec next Phase B running for 13 sec and A start to run parallel  and phase E start to run after inter green and so on. Streams are running parallel as shown in figure.
Figure 7: Signal timing diagram for 90 sec cycle time
![image](https://github.com/user-attachments/assets/7dd1842e-94c0-4698-8db8-57eb2460cf43)
## Conclusions and Recommendations
For 2029 design period, Roundabout running with 1.90% Practical reserve capacity is quite good. Still, it can be improved by making some modifications like adding extra lane, particularly Arm A shows worst PRC which effects the overall PRC adding one more lane with existing lane will improve the PRC of 9.6% for 60 sec Cycle Time and 15.4 % for 90 sec Cycle Time and Degree of Saturation as well. By Changing the Cruise time there will be not much difference in PRC, but It varies little bit in Total delay. Providing extra lane in circulator lane will also increase PRC and minimise delay.
