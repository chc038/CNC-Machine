# CNC-Machine
 Repository containing CAD files of my DIY CNC mill

 <img width="461" alt="Screenshot 2023-11-04 at 8 48 28 PM" src="https://github.com/chc038/CNC-Machine/assets/146500723/8a934bf1-6e94-4352-90c4-86928c927776">


# Project Description
 In spring 2021, I designed and built this CNC machine mainly for fun, but also to learn about CNC and machining. After setting it up to do only very basic milling operations, I have only used it for one class project where I machined some styrofome on it. In Summer 2023, I slightly upgraded this CNC machine (adding end stops, buttons, new spindle, new spindle mount) so that it can actually machine metal. Since then, I have used it to machine mostly alunimum parts for some of my projects. 

# Features
- 220x270x150 mm (x,y,z) working volume
- Capable of machining aluninum alloys. Machining steel is also possible, although very slow
- Can achieve tolerance of 0.1mm (if toolpath and feedrates are not too aggressive)
- Automatically measures tool length offset
- Semi-automatic probing

# Design and Fabrication
- Frame is made of 4040 aluminum extrusions, mostly of standard length so minimal cutting is needed (manually cutting aluninum with a handsaw was quite tiring). Aluminum extrusions are joined together using some 3D printed parts and t-nuts.
- Moving parts were mounted on 12mm linear rails to achieve good tolorence.
- Used NEMA 23 stepper motors and 8mm lead screws for mation.
- Used grbl firmware on an arduino as the main controller.
- Costs approximately $1000 in total including the recent upgrades. I could have simply built some open-source CNC machine designs instead for less money, although coming up with this design myself is more fun and educational.

 <img width="701" alt="Screenshot 2023-11-04 at 8 11 18 PM" src="https://github.com/chc038/CNC-Machine/assets/146500723/348ccc64-a2d3-4d41-a6bb-453839194098">

# Pictures of some machined parts

<img width="600" alt="Screenshot 2023-11-04 at 9 15 51 PM" src="https://github.com/chc038/CNC-Machine/assets/146500723/6a3b9deb-69ad-4803-96c3-35861255a21b">
<img width="600" alt="Screenshot 2023-11-04 at 9 16 05 PM" src="https://github.com/chc038/CNC-Machine/assets/146500723/332aaa33-3cfa-4ebe-b3be-c6a429911084">
<img width="600" alt="Screenshot 2023-11-04 at 9 16 20 PM" src="https://github.com/chc038/CNC-Machine/assets/146500723/fb57503e-02c0-404b-be1d-a50be749b99b">
<img width="600" alt="Screenshot 2023-11-04 at 9 19 46 PM" src="https://github.com/chc038/CNC-Machine/assets/146500723/7aef0555-b2c2-4b0e-99a7-9b3209a74bfa">


**Note:**
 Some older pictures of the CNC machine in the media folder may look different because of recent upgrades.





 
