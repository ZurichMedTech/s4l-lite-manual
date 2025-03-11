
# What's new in Sim4Life.lite

Sim4Life.lite V8.4 is the latest version of the student edition of our online simulation platform for computational life science research, device design and optimization, as well as safety and electromagnetic compliance evaluations. This new release introduces significant improvements to enhance your simulation experience and makes Sim4Life more user-friendly and efficient.

The highlights of Sim4Life.lite V8.4:
- Refreshed Interface: The streamlined menu and drag-and-drop actions make starting and organizing projects easier.
- Simplified Neuro-Stimulation Settings: A single checkbox in the settings provides access to different tissue/electrode contact impedance models.


# Release History

## _**Sim4Life.lite**_ V8.4 
### Release Date: 11.03.2025

### **Selected new features**
- Intuitive Project Organization
    - New drag-and-drop functionality for managing simulations online, allowing users to effortlessly organize their workspaces and maintain an overview of multiple projects.
    - Recovery of deleted items thanks to a new trash bin for projects, folders, and workspaces.
- Streamlined Platform Experience and Enhanced Ecosystem: “New” menu simplifies the creation of not only Sim4Life projects, but also of complementary iSeg and JupyterLab projects.
- Simplified Neuro-Stimulation Settings
    - A single checkbox in the settings provides access to different tissue/electrode contact impedance models, making it easier to account for the effects of non-ideal interfaces on pulse shapes.
    - Support for importing compressed .hoc data files, essential for users who want to modify neuron models from online sources such as ModelDB, the Human Brain Project (HBP), or the Allen Brain Institute for use in Sim4Life neuron simulations.
- Simplified full-screen mode improves usability.
- Front-end UI configurations are now stored in the backend.

### **No longer broken**
- Fixed issue where service startup time was unnecessarily long.
- Fixed issue where project/study remained locked until the page was refreshed.
- Fixed issue where heavy dynamic services would fail to start.


## _**Sim4Life.lite**_ V8.2 
### Release Date: 14.11.2024

Final release of Sim4Life.lite V8.2

### Additional new features & enhancements compared to V8.2 beta
- Improved Navigation: An intuitive new search toolbar simplifies the process of locating tools and resources, accessing them, or learning more through tutorial videos.
- Python upgrade to version to 3.11.9.
- A new suite of Python notebooks tailored to specific applications, showing step-by-step how to fully exploit the capabilities of Sim4Life.
- Fixed inconsistency in results when searching with different cases (lowercase or uppercase).
- Fixed issue with compiling Neuron mechanism files.



## _**Sim4Life.lite**_ V8.2 beta
### Release Date: 10.10.2024

Pre-release ahead of the main Sim4Life V8.2 Desktop and Web release

### **Selected new features**
- Introduced a new resource monitoring widget for CPU and RAM usage.
- Launched a new Help Center for advanced search.
- Added guided tours for first-time users.
- IPython-based Python console for simple scripting tasks.
- Persistent preferences across projects.

### **Performance and usability enhancements**
- Speed improvements in tree navigation for projects with many entities.
- Faster application startup using compressed project files.
- Completely revamped the video streaming backend for increased stability.

### **New tools**
- Material calculator.
- Screen capture with download functionality.
- Cursor and ruler added in the modeler.
- Symmetry Tool.
- Extrude Patch.
- Reconstruct Hull.
- Join Wires.
- Annotate Tool.

### **Selected improvements**
- Improved support for multiport simulations in the task manager and simulation setup.
- Added linkable properties.
- Improved move tool.
- Auto-detected accurate transparency.
- Fixed wireframe rendering in the surface viewer.

## _**Sim4Life.lite**_ V7.2
### Release Date: 15.02.2023

The first public release of the powerful web-based simulation platform that allows you to model and analyze real-world phenomena and design complex technical devices in a validated environment.Sim4Life Lite is a student edition, a specially tailored solution for students to gain insight into the world of computational modeling and simulation.

### **Features**

- Novel cloud-native simulation platform, accessible fully online.
- Same performance as desktop version.
- Accessible fully online
- Based on o<sup>2</sup>S<sup>2</sup>PARC technology
- User-friendly GUI
- 3D modeling environment and CAD translators
- Postprocessing and visualization of the simulation results 
- No restrictions on the number of modeling objects
- Solvers & Tissue Models
    * P-EM-FDTD: Electromagnetics Full Wave Solvers
    * P-EM-LF: Finite element method (FEM) low-frequency solver suite
    * P-Thermal: Thermodynamic Solver based on Pennes Bioheat equations
    * P-Acoustics: Acoustics Solver
    * T-Neuro: Neuronal Tissue Models, allowing neurostimulation investigations
- Computational anatomical model Yoon-sun, the first Korean human model of the IT'IS Virtual Population
- Material database
- Python and Jupyter Notebook scripting


---

### **Limitations**
- Grid size of each simulation is limited to a maximum of 20 million grid cells
- High-Performance Computing is not supported:
    * GPU acceleration is not available
    * MPI multicore acceleration is not available
- 3rd-party tools are not available (e.g., MUSAIK, SYSSIM, IMAnalytics, etc…)
- Additional ViP models cannot be added

---


