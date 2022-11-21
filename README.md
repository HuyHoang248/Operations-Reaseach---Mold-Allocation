## Mold Allocation Project

**1. Objectives of the project**

Our client requires an application to systemize and optimize mold allocation and OEE including the following:
+ Provide optimized mold allocation and injection planning so that the planning and capacity team better utilizes resources
+ Measure the improvement in terms of OEE for each machine and factory level

**2. Scopes of the project**

+ Conduct activities for production planning improvement
+ Apply algorithm for optimization of mold allocation
+ Test and validate model performance
+ Fine tune model and put it into production for automation
+ Train end-users and conduct change management
+ Compare the baseline OEE with OEE after execution of the optimization program
+ Scale up the program to 6 machines with more variables, constraints, and outputs

**3. What in this repository**

+ Outcome 1: One machine mold loading plan.
1. Mold loading plan for the following shift.
2. The mold loading plan should show which mold needs to be loaded on which station, which compound to inject and how many times to inject it.

**4. Production Planning Background**

+ After the Purchase Orders are sent to factory, they will be recorded at client’s ERP collectively. There are internal Purchase Orders which are the sum numbers of IP with the same colors, size, and style. In that internal PO, the production manager will devise into required production quantity and prioritize by the amount and expected time to complete.

+ On daily basis, the production manager will update the actual production quantity and provide the machine supervisor (head) the instruction.

+ Also from his experience, 60 is the possible cycle one shift can complete for each station. The 80 cycles are expected cycles during one shift.

+ There are 2 shift a day: morning shift start at 7:30 and night shift start at 19:30. The shift handover time is about 10 - 15 minutes, time of mold changing and heating process about 35-40 minutes and time of color changing about 20-23 minutes.

+ A production plan is probably made by one or more machines. Finished products are moved to print a sticker may take 3 – 4 weeks before packing process, in case of having hard fashion styles, it may be required for a long time about 1 month.

+ Crocs are made with a proprietary closed-foam resin which is a type of EVA (ethylene Vinyl-Acetate) is injected into a mold to create an upper section of Crocs sandal. Crocs are made in a variety of styles, colors, and sizes. For instance, Size C for toddlers, size J for teens.

+ An injection molding machine, also known as an injection press, is a machine for manufacturing plastic products by the injection molding process. It consists of two main parts, an injection unit and a clamping unit.

+ One station has a pair of mold, right mold, and left mold. There are a total of 8 stations for a machine and the injection machine will go over each of these stations. In case the station is not ready yet, the injection machine would be waiting for a few seconds.

**5. Machine Operation**

+ 1 machine has 8 stations
+ 1 station has L mold and R mold
+ 1 mold has X cavities (X∈ℤ^∗)

+ For example: a mold has 4 cavities, 2 pairs of shoes per mold  1 station can produce 2 x 2 = 4 pairs of shoes  1 machine can run 8 x 2 = 16 molds at once

+ L mold and R mold of a station can be different items; parameters (time, temperature, volume of compound, …) for each mold can be set up independently in the machine monitor

![image](https://user-images.githubusercontent.com/92867270/202961812-68a539ba-e3d8-459b-9216-72084c1448c3.png)

![image](https://user-images.githubusercontent.com/92867270/202961919-7fed3c71-3858-4e7e-97e9-bf123b42bd1b.png)

**6. Parameter and Variables Definifition**

![image](https://user-images.githubusercontent.com/92867270/202961971-438e101d-cc0d-4320-a223-89c5934b6b30.png)

![image](https://user-images.githubusercontent.com/92867270/202962164-da443857-30a0-4a36-adf5-5fcbf1e3c2d5.png)

**7. Output**

As requested by client, the output of the application is 20 day mold loading plan
		
![image](https://user-images.githubusercontent.com/92867270/202962340-3d5f8895-4974-4a8a-824b-9fc5dfaa450c.png)

