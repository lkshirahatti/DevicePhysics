# DevicePhysics

A curated collection of Jupyter Notebooks explaining fundamental concepts of semiconductor device physics.

## 📚 Topics Covered

- Drift and Diffusion Current
- Fermi Level Calculations
- Intrinsic Carrier Concentration
- Hall Effect
- GaAs and Negative Differential Mobility
- Einstein Relation
- Resistor Design

## 🧪 Examples

Each notebook includes:
- Scientific equations using LaTeX ($...$)
- Graphs and visualizations using `matplotlib`
- SI units and constants clearly explained

## References

Some concepts, equations, and data in this repository are adapted from the following references

1. Donald A. Neamen, *Semiconductor Physics and Devices: Basic Principles*, 4th Edition, McGraw-Hill Education, 2011. ISBN: 978-0073380643.
2. S. M. Sze and Kwok K. Ng, *Physics of Semiconductor Devices*, 3rd Edition, Wiley-Interscience, 2006. ISBN: 978-0471143239.
3. Richard C. Jaeger and Travis N. Blalock, *Microelectronic Circuit Design*, 5th Edition, McGraw-Hill Education, 2015. ISBN: 978-0073380452.
4. Stephen A. Campbell, *The Science and Engineering of Microelectronic Fabrication*, 2nd Edition, Oxford University Press, 2001. ISBN: 978-0195136050.


VLSI 
1. **Neil H. E. Weste & David Money Harris**,  
   *CMOS VLSI Design: A Circuits and Systems Perspective*, 4th Edition, Pearson, 2010.  
   [Companion site with lecture slides, labs, and projects](https://pages.hmc.edu/harris/cmosvlsi/4e/index.html)  
   [Direct link to lecture videos](https://pages.hmc.edu/harris/cmosvlsi/4e/lect/index.html)

2. **NPTEL – VLSI Design Lectures**,  
   by Prof. Janakiraman and others at IITs.  
   Covers topics from RTL coding to physical design and verification.  
   [Available via NPTEL Portal](https://nptel.ac.in/courses/117101058) or [YouTube Channel](https://www.youtube.com/c/nptelhrd/playlists)

3. **David Money Harris (Harvey Mudd College)**  
   - [RTL to GDS Flow Labs](https://pages.hmc.edu/harris/class/e155/index.html)  
   Includes hands-on labs with Verilog, synthesis, place & route using tools like Cadence or OpenROAD.

4. **The OpenROAD Project**  
   Open-source RTL-to-GDSII flow developed by DARPA and university collaborators.  
   [GitHub Repo](https://github.com/The-OpenROAD-Project/OpenROAD)  
   [Official Documentation](https://openroad.readthedocs.io/)

5. **Skywater Open PDK & Google’s Open MPW Initiative**  
   Real-world tapeout project using Sky130nm node with OpenLane flow.  
   - [Skywater PDK GitHub](https://github.com/google/skywater-pdk)  
   - [OpenLane GitHub](https://github.com/The-OpenROAD-Project/OpenLane)  
   - [MPW Shuttle Info](https://efabless.com/open_shuttle_program)

6. **“Digital Integrated Circuits” by Jan M. Rabaey et al.**,  
   2nd Edition, Prentice Hall, 2002.  
   Offers deeper transistor-level and timing analysis that complements RTL-GDS2 flow.  
   ISBN: 978-0130909961

7. **ASIC World – Verilog & VLSI Flow Tutorials**  
   Free educational platform for RTL, synthesis, and testbench writing.  
   [https://asic-world.com/](https://asic-world.com/)

8. **Digital VLSI Design on GitHub**  
   Example flows integrating Verilog → Yosys → OpenROAD → Magic + KLayout.  
   [Awesome Open Source VLSI Projects](https://github.com/drom/awesome-open-source-vlsi)



## References on Reliability 

1. Richard C. Jaeger, *Introduction to Microelectronic Fabrication*, 2nd Edition, Pearson Education, 2001. ISBN: 978-0201444940.
2. Renesas Electronics Corporation, *Semiconductor Reliability Handbook*, 2023 Edition. 
3. United States Department of Defense, *MIL-HDBK-217F: Military Handbook – Reliability Prediction of Electronic Equipment*, Notice 2, February 1995. 
4. S. M. Sze and Kwok K. Ng, *Physics of Semiconductor Devices*, 3rd Edition, Wiley-Interscience, 2006. ISBN: 978-0471143239.
5. Donald A. Neamen, *Semiconductor Physics and Devices: Basic Principles*, 4th Edition, McGraw-Hill Education, 2011. ISBN: 978-0073380643.
6. Stephen A. Campbell, *The Science and Engineering of Microelectronic Fabrication*, 2nd Edition, Oxford University Press, 2001. ISBN: 978-0195136050.
7. Richard C. Jaeger and Travis N. Blalock, *Microelectronic Circuit Design*, 5th Edition, McGraw-Hill Education, 2015. ISBN: 978-0073380452.
8. JEDEC Solid State Technology Association, *JESD47 and JESD22 Series: Stress-Test-Driven Qualification of Integrated Circuits*, [Available at JEDEC.org](https://www.jedec.org).
9. IEEE Standards Association, *IEEE Std 1413-2010: Standard Framework for Reliability Prediction*, IEEE, 2010. DOI: 10.1109/IEEESTD.2010.5540906.
10. Telcordia Technologies, *SR-332: Reliability Prediction Procedure for Electronic Equipment*, Issue 4, 2016.




Following Links Provide References / Sources for Novice Semiconductor Device Physics Engineers   
Band Gap of different Materials 
1. [Wiki](https://en.wikipedia.org/wiki/List_of_semiconductor_materials) 
2. [Energy Band Gap](https://psec.uchicago.edu/library/photocathodes/Compilation_of_Energy_Band_Gaps_in_Elemental_and_Binary_Compound.pdf) 

Oxygen / Moisture Impact References 
1. https://theses.hal.science/tel-03205937v1/file/VIDAL-DHO_2020_archivage.pdf 
2. Oxidation of the TA Diffusion Barrier and Its Effect on the Reliability of CU Interconnects (https://www.researchgate.net/publication/224672883_Oxidation_of_the_TA_Diffusion_Barrier_and_Its_Effect_on_the_Reliability_of_CU_Interconnects)
3. D. Shamiryan et al. “Low-k dielectric materials”. In: Materials Today 7.1 (2004), pp. 34–39. issn: 13697021. https://www.sciencedirect.com/science/article/pii/S1369702104000537 
4. Challenges in the implementation of low-k dielectrics in the back-end of line https://www.sciencedirect.com/science/article/abs/pii/S0167931705002273 
