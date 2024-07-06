# Simulation-in-System-Engineer
In this courses, I have learned about some points below : 
* Ability to identify, formulate, and solve complex engineering problems by applying principles of engineering, science, and mathematics
* An ability to apply engineering design to produce solutions that meet specified needs with consideration of public health, safety, and welfare, as well as global, cultural, social, environmental, and economic factors
* An ability to communicate effectively with a range of audiences
* An ability to recognize ethical and professional responsibilities in engineering situations and make informed judgments, which must consider the impact of engineering solutions in global, economic, environmental, and societal contexts
* An ability to function effectively on a team whose members together provide leadership, create a collaborative and inclusive environment, establish goals, plan tasks, and meet objectives
* An ability to develop and conduct appropriate experimentation, analyze and interpret data, and use engineering judgment to draw conclusions
* An ability to acquire and apply new knowledge as needed, using appropriate learning strategies.

# Reference Books
* [1] Banks, J., Carson, J. S., Nelson, B. L., and Nicol, D. M., “Discrete-Event System Simulation”, 4th edition, Prentice-Hall, 2005.
* [2] Kelton, W. D., Sadowski, R. P., and Sturrock, D. T., “Simulation with Arena”, McGraw-Hill, New York (fourth edition), 2006.
* [3] Tayfur Altiok, Benjamin Melamed, “Simulation modeling and analysis with Arena”, Academic Press (Elsevier) 2007


# Main problems : The production line simulation : Inspection and Package
Company X is a bicycle manufacturer that runs **8 working-hours** per day, from **8:00AM to 4:00PM**. The process of inspection and packaging of bicycles comprises three main zones.
Every day, there are **2 kinds of pallets** delivered to **zone 1** of the company. Each different kind of pallet contains a type of bicycle. There are **4 bicycles** in one pallet. Upon arrival, a forklift moves pallets from Zone 1 to Zone 2. A forklift can move one pallet at a time.

At Zone 2, the pallet is unboxed by a **group of 2 unbox_workers**. The empty pallet is removed for reuse. Then, all bicycles are loaded on a main conveyor by a **loader_worker** to go to Zone 3.At Zone 3, each bi cycle is inspected and classified by an inspector. After that, bicycles of **type 1 **access space on the **conveyor 1.** Before bicycles are taken out of the conveyor, there is a process for labeling by a worker **(worker 1)**. After the exit of the conveyor, each bicycle is packaged by another worker (worker 3).Bicycles of type 2 follow a similar process with conveyor 2, worker 2 and worker 4.

![image](https://github.com/PhongDiii/Simulation-in-System-Engineer/assets/105002084/8826e65d-9f75-422a-9bfa-6d0a24fd48f0)
![image](https://github.com/PhongDiii/Simulation-in-System-Engineer/assets/105002084/90d83f46-af88-4531-9da5-989942e30b4d)
![image](https://github.com/PhongDiii/Simulation-in-System-Engineer/assets/105002084/3c60c720-22fe-4afa-9663-d1ff4fc97e7e)

