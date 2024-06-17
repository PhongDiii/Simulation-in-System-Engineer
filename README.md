# Simulation-in-System-Engineer

# The production line simulation : Inspection and Package
Company X is a bicycle manufacturer that runs **8 working-hours** per day, from **8:00AM to 4:00PM**. The process of inspection and packaging of bicycles comprises three main zones.
Every day, there are **2 kinds of pallets** delivered to **zone 1** of the company. Each different kind of pallet contains a type of bicycle. There are **4 bicycles** in one pallet. Upon arrival, a forklift moves pallets from Zone 1 to Zone 2. A forklift can move one pallet at a time.

At Zone 2, the pallet is unboxed by a **group of 2 unbox_workers**. The empty pallet is removed for reuse. Then, all bicycles are loaded on a main conveyor by a **loader_worker** to go to Zone 3.At Zone 3, each bi cycle is inspected and classified by an inspector. After that, bicycles of **type 1 **access space on the **conveyor 1.** Before bicycles are taken out of the conveyor, there is a process for labeling by a worker **(worker 1)**. After the exit of the conveyor, each bicycle is packaged by another worker (worker 3).Bicycles of type 2 follow a similar process with conveyor 2, worker 2 and worker 4.
