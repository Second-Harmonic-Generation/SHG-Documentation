## 🧰 How to Use This Template    

Click the green **"Use this template"** button at the top of the page, then choose **"Create a new repository"**.   

This will create your own copy of this project, which you can modify freely — no need to fork!   

---    

<p align="center">
  <img src="./Archive/images/3.%20Readme_images/SHG_Logo.png" alt="Image 1">
</p>


---

***Table of Contents***

<details>
  <summary><a href="#1-about-this-repository"><i><b>1. About this Repository</b></i></a></summary>
  <div>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#11-who-is-this-tutorial-for">1.1. Who Is This Tutorial For?</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#12-what-will-you-learn">1.2. What Will You Learn?</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#13-prerequisites">1.3. Prerequisites</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#14-contents-of-this-repository">1.4. Contents of this Repository</a>
  </div>
</details>

<div>
  &nbsp;&nbsp;&nbsp;&nbsp;<a href="#2-second-harmonic-generation-shg"><i><b>2. Second Harmonic Generation (SHG)</b></i></a>
</div>
&nbsp;

<div>
  &nbsp;&nbsp;&nbsp;&nbsp;<a href="#3-thermal-challenge-in-shg"><i><b>3. Thermal Challenge in SHG</b></i></a>
</div>
&nbsp;

<div>
  &nbsp;&nbsp;&nbsp;&nbsp;<a href="#4-thermal-gradient-in-a-crystal-during-shg"><i><b>4. Thermal Gradient in a Crystal during SHG</b></i></a>
</div>
&nbsp;

<div>
  &nbsp;&nbsp;&nbsp;&nbsp;<a href="#5-reducing-computational-cost"><i><b>5. Reducing Computational Cost</b></i></a>
</div>
&nbsp;

<details>
  <summary><a href="#6-boundry-conditions"><i><b>6. Boundary Conditions</b></i></a></summary>
  <div style="padding-left: 20px; line-height: 1.2;">
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#61-our-contribution-1">6.1. Our Contribution (1)</a>
  </div>
</details>

<details>
  <summary><a href="#7-phase-mismatch"><i><b>7. Phase Mismatch</b></i></a></summary>
  <div style="padding-left: 20px; line-height: 1.2;">
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#71-our-contribution-2">7.1. Our Contribution (2)</a>
  </div>
</details>

<details>
  <summary><a href="#8-electromagnetic-field"><i><b>8. Electromagnetic Field</b></i></a></summary>
  <div style="padding-left: 20px; line-height: 1.2;">
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#81-our-contribution-3">8.1. Our Contribution (3)</a>
  </div>
</details>

<details>
  <summary><a href="#9-interdependency-of-heat-phase-and-electromagnetic-field"><i><b>9. Interdependency of Heat, Phase, and Electromagnetic Field</b></i></a></summary>
  <div style="padding-left: 20px; line-height: 1.2;">
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#91-our-contribution-4">9.1. Our Contribution (4)</a>
  </div>
</details>

<details>
  <summary><a href="#10-methodology"><i><b>10. Methodology</b></i></a></summary>
  <div style="padding-left: 20px; line-height: 1.2;">
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#101-computational-approach-using-finite-difference-method-fdm">10.1. Computational Approach using Finite Difference Method (FDM)</a>
  </div>
</details>

<div>
  &nbsp;&nbsp;&nbsp;&nbsp;<a href="#11-research-opportunities"><i><b>11. Research Opportunities</b></i></a>
</div>
&nbsp;

<div>
  &nbsp;&nbsp;&nbsp;&nbsp;<a href="#12-how-to-cite-us"><i><b>12. How to Cite Us</b></i></a>
</div>
&nbsp;

<div>
  &nbsp;&nbsp;&nbsp;&nbsp;<a href="#13-for-additional-questions"><i><b>13. For Additional Questions</b></i></a>
</div>
&nbsp;                                                 

                            

# 1. About this Repository
This GitHub repository offers comprehensive guidance, from basic to advanced levels, for computationally addressing thermal effects in Second Harmonic Generation (SHG). As an educational resource, this repository starts with covering fundamental aspects of Fortran, including how to install it and master its essential commands. Also, we demonstrate techniques for computationally solving a nonlinear optics phenomenon using the Finite Difference Method (FDM), provide access to the codes utilized in our studies, and explain our research findings clearly. Also, we outline potential research opportunities for future exploration. Our ongoing efforts involve expanding the repository to incorporate further advancements in the field. 

## 1.1. Who Is This Tutorial For?   
This tutorial is designed for anyone interested in computational physics, nonlinear optics, or scientific computing, regardless of their prior experience. Whether you're a student, researcher, or professional, this resource will guide you through the process of solving Thermal Effects in SHG using FDM.

## 1.2. What Will You Learn?    
By the end of this tutorial, you will:           
- Gain proficiency in Fortran, from installation to mastering essential commands.
- Understand the basic to advanced principles of Thermal Effects in SHG.
- Learn FDM and how to apply it for solving nonlinear optics problems computationally.
- Access and utilize real codes used in this cutting-edge research.
- Clearly comprehend the research findings and understand the potential for future exploration in this area.

## 1.3. Prerequisites  
This tutorial is designed for three types of researcher:

1. **For those who are familiar with SHG and Fortran**: You can dive straight into the research phase. The codes and topics provided in this repository, in [**2. SHG Codes**](https://github.com/Mostafa-M-Rezaee/SHG__Second_Harmonic_Generation/tree/main/2.%20SHG%20Codes), are meant to deepen your knowledge and assist in further studies.

2. **For those who know Fortran but are new to SHG**: This tutorial will introduce you to the fundamentals of SHG, guiding you step-by-step through the key concepts. By the end, you'll be ready to tackle complex problems in this field.

3. **For beginners with no prior knowledge of SHG or Fortran**: This repository is built with you in mind. We’ll start with the basics, teaching you Fortran from the ground up in [**1. FORTRAN Tutorial**](https://github.com/Mostafa-M-Rezaee/SHG__Second_Harmonic_Generation/tree/main/1.%20FORTRAN%20Tutorial), followed by an introduction to SHG. Our goal is to help you progress from understanding the basics to solving advanced physics and engineering problems.


## 1.4. Contents of this Repository 

```
Folder PATH listing
. 
|
+---0. Cite Us
|       1_Heat-Equation_Continuous-Wave_Gaussian_Analytical.pdf
|       2_Heat-Equation_Continuous-Wave_Gaussian.pdf
|       3_Heat-Equation_Pulsed-Wave_Gaussian.pdf
|       4_Phase-Mismatch_Pulsed-Wave_Gaussia.pdf
|       5_Ideal_Continuous-Wave_Gaussian.pdf
|       6_Ideal_Pulsed-Wave_Bessel-Gaussian.pdf
|       7_Coupled_Continuous-Wave_Gaussian.pdf
|       README.md
|       
+---1. FORTRAN Tutorial
|       00_ifort_Installation-Guide.md
|       01_FORTRAN_Main-Commands_Tutorial.md
|       02_FORTRAN_Coding-Template_Tutorial.md
|       03_FORTRAN_Run_a_Code_Tutorial.md
|       04_FORTRAN_Coding_Template.F90
|       05_Write-Read-Variables_Types.F90
|       06_Readable_Code_Structure.F90
|       07_do-loop.F90
|       08_If-then-else.F90
|       09_open-file.F90
|       10_Array.F90
|       README.md
|       
+---2. SHG Codes
|   |   2_Heat-Equation_Continuous-Wave_Gaussian.f90
|   |   3_Heat-Equation_Pulsed-Wave_Gaussian.f90
|   |   4_Phase-Mismatch_Pulsed-Wave_Gaussia.f90
|   |   5_Ideal_Continuous-Wave_Gaussian.f90
|   |   6_Ideal_Pulsed-Wave_Bessel-Gaussian.f90
|   |   7_Coupled_Continuous-Wave_Gaussian.f90
|   |   README.md 
|   |  
|   +---2_Results   <-- Contains plots generated by the code of article 2
|   +---3_Results   <-- Contains plots generated by the code of article 3  
|   +---4_Results   <-- Contains plots generated by the code of article 4   
|   +---5_Results   <-- Contains plots generated by the code of article 5   
|   +---6_Results   <-- Contains plots generated by the code of article 6  
|   \---7_Results   <-- Contains plots generated by the code of article 7 

```         


# 2. Second Harmonic Generation (SHG)
SHG employs a nonlinear crystal like Potassium Titanyl Phosphate (KTP) to convert red laser (1064 nm) into green laser (532 nm). This conversion is essential because of green light's necessity and difficulty in direct production. During the SHG process, a powerful laser beam interacts with the crystal, causing it to emit light at exactly half the wavelength of the incoming beam, effectively doubling the light's frequency. 

<p align="center">
  <img src="./Archive/images/3.%20Readme_images/image01.png" alt="Image 1">
</p>

<p align="center"> <strong>Figure 1.</strong> During SHG, a nonlinear crystal like KTP converts a 1064 nm red laser (Fundamental Wave) into 532 nm green laser (Second Harmonic Wave), effectively doubling the frequency of the original beam through a nonlinear optical process.</p>

# 3. Thermal Challenge in SHG
As the SHG process occurs, some of the input energy is not perfectly converted into the desired higher-frequency photons. Instead, a portion of this energy is lost as heat within the nonlinear crystal or medium. The dissipated heat within the nonlinear crystal reduces efficiency by causing thermal dephasing, which disrupts phase matching. This temperature increase can also lead to crystal damage, further lowering the conversion efficiency and output power.

To address this issue, the crystal is equipped with a cooling system depicted in the Figure 2. A coolant circulates around the crystal, absorbing the heat thereby maintaining an optimal temperature for a more efficient SHG. The crystal's lateral surface is maintained at a constant temperature through cooling. Typically, a double layer of copper covers these surfaces, with either water or liquid nitrogen passing through it. This ensures a constant temperature condition at the crystal's side surface. Additionally, the input and output surfaces of the crystal are cooled through both radiation and convection. Heat reaches these surfaces through conduction and is then transferred away by convection and radiation processes.

<p align="center">
  <img src="./Archive/images/3.%20Readme_images/image02.png" alt="Image 2" >
</p>

<p align="center"> <strong>Figure 2.</strong> A cooling system uses a double layer of copper and circulating coolant (water or liquid nitrogen) to manage heat dissipation, keeping the crystal at an optimal temperature for efficient laser performance during SHG.</p>


# 4. Thermal Gradient in a Crystal during SHG
The thermal gradient within a crystal subjected to laser radiation is shown in Figure 3. Since the axis of the crystal is under the laser beam and its lateral surface is in heat exchange with the environment, the peak of the temperature gradient is at the center of the crystal, where the laser beam is focused, and gradually decreases towards the surface. Also, the left side of the crystal, where the laser initially contacts, is the hottest, with temperature decreasing towards the right side. This spatial temperature variation is crucial in understanding the thermal behaviour of crystals under laser irradiation.


<p align="center">
  <img src="./Archive/images/3.%20Readme_images/image03.png" alt="Image 3">
</p>

<p align="center"> <strong>Figure 3.</strong> Visualization of the thermal gradient in a crystal exposed to laser radiation. The hottest point is at the center where the laser is focused, with temperature decreasing outward toward the edges. The left side, where the laser first hits, is the hottest, with the temperature gradually cooling as it moves to the right.</p>

To achieve optimal performance, understanding the heat conduction within a crystal is crucial. Here’s a breakdown of the key factors:

- **Material Properties**:
   - Mass Density $(\rho)$: A measure of how much mass is contained in a unit volume of the material.
   - Heat Capacity $(c)$: Indicates the amount of energy needed to change the material’s temperature, influencing how it absorbs or loses heat.
   - Thermal Conductivity $(K)$: Describes how efficiently heat is conducted through the material, and it varies with temperature, making the heat transfer process dynamic.

- **Temperature Dependency**:
   - The thermal conductivity $(K)$ is temperature-dependent, meaning it changes as the temperature within the crystal changes, affecting how heat moves through the material.

- **Heat Source $(S)$**:
   - An external heat source adds energy to the system, altering the temperature distribution over time and space within the crystal.


# 5. Reducing Computational Cost  
To efficiently analyze Second Harmonic Generation (SHG) in a KTP crystal modeled as a cylinder, we can reduce the workload by taking advantage of the crystal’s symmetry. Instead of examining the entire cylindrical shape, we focus on a simpler two-dimensional half-plane, a rectangular section that represents one side of the cylinder. This works because of the crystal’s symmetry along its lateral axis; studying this smaller section captures the behavior of the full cylinder. By visualizing this half-plane rotating around the horizontal axis, we effectively account for the whole cylindrical structure. This approach significantly reduces the size of the problem, decreasing the number of calculations needed. It allows for high-resolution analysis with greater efficiency, maintaining the accuracy of the SHG study while saving substantial time and resources.

<p align="center">
  <img src="./Archive/images/3.%20Readme_images/image04.png" alt="Image 4" width="45%">
</p>

<p align="center"> <strong>Figure 4.</strong> Efficient SHG Analysis in KTP Crystals Using Symmetry: The image shows how a two-dimensional half-plane leverages the crystal’s symmetry to represent the entire cylinder, reducing computational complexity while maintaining accurate SHG analysis. 
</p>


# 6. Boundry Conditions  
In the KTP crystal, the input and output faces undergo convective and radiative cooling, allowing heat to dissipate efficiently from these surfaces. Since the lateral surfaces are in contact with a cooling system, only conductive heat transfer occurs at these boundaries, maintaining a constant temperature. As a result, there are no mathematical complexities associated with lateral surface boundary conditions. Heat transfer within crystal occurs exclusively through conduction, since it is a solid. Additionally, we need to carefully determine the boundary conditions of the crystal's axis for accurate modeling.

<p align="center">
  <img src="./Archive/images/3.%20Readme_images/image05.png" alt="Image 5" width="85%">
</p>

<p align="center"> <strong>Figure 5.</strong> Heat dissipation in KTP crystal during SHG, with convective and radiative cooling at the faces and constant temperature maintained at the lateral surfaces.
</p>

Just as a ball rolls downhill due to the force of gravity, heat flows from a hotter region to a colder one due to the temperature gradient. The temperature difference drives this heat transfer, similar to how gravity drives the motion of the ball (Figure 6).

<p align="center">
  <img src="./Archive/images/3.%20Readme_images/image06.png" alt="Image 6" width="75%">
</p>

<p align="center"> <strong>Figure 6.</strong> Just like a ball that only rolls downhill and not uphill due to gravity, heat flows from the hottest regions to the cooler ones, illustrating the natural direction of heat transfer within the crystal.
</p>

The crystal axis represents the hottest region, and no heat flows across it, meaning there is no conduction, convection, or radiation in this direction. Due to the temperature gradient, heat is transferred solely outward from the axis toward the cooler lateral surfaces.

<p align="center">
  <img src="./Archive/images/3.%20Readme_images/image07.png" alt="Image 7" width="30%">
</p>

<p align="center"> <strong>Figure 7.</strong> Heat only flows radially outward from the hottest crystal axis to the cooler lateral surfaces, with no heat transfer across the axis.
</p>


In conclusion, the boundary condition for the crystal axis is insulation, as no heat transfer occurs across it. With this, all boundary conditions for the crystal are defined: insulation for the axis, constant temperature at the lateral surfaces, and convection and radiation at the faces. These boundary conditions are essential for accurately modeling the heat distribution and optimizing SHG performance.

<p align="center">
  <img src="./Archive/images/3.%20Readme_images/image08.png" alt="Image 8" width="85%">
</p>

<p align="center"> <strong>Figure 8.</strong> 
Boundary conditions for heat transfer in SHG crystals: The lateral surfaces are cooled to a constant temperature, facilitating heat dissipation, while input and output faces are cooled by radiation and convection. The crystal axis, experiencing peak temperatures, is treated as an insulated boundary, ensuring accurate heat distribution modeling critical for optimizing SHG performance.
</p>

## 6.1. Our Contribution (1)
The thermal behavior in SHG can be accurately described by the heat equation: 

<table style="width: 100%; border-collapse: collapse; border: none;">
  <tr>
    <td style="text-align: left; vertical-align: middle; border: none;">
      $\large +\rho c \frac{\partial \textcolor{orange}{T}}{\partial t}-\vec{\nabla} \cdot (K(\textcolor{orange}{T}) \vec{\nabla} \textcolor{orange}{T}) = S$
    </td>
    <td style="text-align: right; vertical-align: middle; border: none;">
      Heat Equation
    </td>
  </tr>
</table>

In our next three publications, we investigate different configurations of key parameters in the model: 
- The **heat source $(S)$** can be either continuous or pulsed, representing different energy input conditions. 
- The **thermal conductivity $(K)$** may be constant or vary with temperature, reflecting more realistic material behavior. 
- **Boundary conditions** can be either approximations or set with higher accuracy, depending on the system's constraints. 
- Lastly, the **solution method** is either analytical, offering simpler closed-form solutions, or computational, providing more detailed results for complex conditions.

Each study builds on the last, incorporating increasingly realistic factors to improve model accuracy. This progression brings the models closer to real-world, enhancing our ability to predict heat transfer dynamics in nonlinear optics.


- **Heat Equation _ Continuous Wave Gaussian _ Analytical** [(Journal)](https://opg.optica.org/ao/abstract.cfm?uri=ao-47-13-2317), [(Article)](https://drive.google.com/file/d/18ttMkf2prKUyNsPEq9cskoHHzzX8SAL3/view?usp=sharing)  
This work focuses on predicting temperature distributions in laser crystals using a Continuous Wave Gaussian source. The analytical model provided insights into the basic thermal behavior in solid-state lasers, a critical step toward designing more efficient systems by accurately modeling heat within complex crystal structures.

- **Heat Equation _ Continuous Wave Gaussian** [(Journal)](https://link.springer.com/article/10.1007/s13538-014-0291-x), [(Article)](https://drive.google.com/file/d/18F3k_iJ07qBrluaiskguTS4543vvu_ql/view?usp=sharing), [(Code)](https://github.com/Mostafa-M-Rezaee/SHG__Second_Harmonic_Generation/blob/main/2.%20SHG%20Codes/2_Heat-Equation_Continuous-Wave_Gaussian.f90)   
Building upon the analytical work, this computational study incorporated more realistic factors, such as temperature-dependent thermal conductivity and radiation effects. The model demonstrated the significant impact of these often-overlooked factors on heat distribution in KTP crystals, enhancing the thermal modeling of laser systems.

- **Heat Equation _ Pulsed Wave Gaussian** [(Journal)](https://opg.optica.org/ao/abstract.cfm?uri=ao-54-6-1241), [(Article)](https://drive.google.com/file/d/18HvFuUr76KRqqbIswoLgJYoMV1vD1Y0i/view?usp=sharing), [(Code)](https://github.com/Mostafa-M-Rezaee/SHG__Second_Harmonic_Generation/blob/main/2.%20SHG%20Codes/3_Heat-Equation_Pulsed-Wave_Gaussian.f90)       
This study developed a numerical model for heat distribution under Pulsed Gaussian conditions, highlighting the critical role of variable thermal conductivity, especially when radiation effects are minimal. The findings improved the accuracy of predicting heat behavior in pulsed laser systems, contributing to more effective thermal management strategies.


# 7. Phase Mismatch
During SHG, a crystal is subjected to laser radiation, the temperature at various points within the crystal becomes spatially and temporally dependent. This variation in temperature causes corresponding changes in the crystal's refractive index, making the refractive index also a function of position and time. Since the speed of light in a medium is dependent on its refractive index, the speed of light traveling through different regions of the crystal will similarly be a function of position and time. Specifically, the temperature gradient within the crystal causes the speed of light to vary radially. Consequently, different regions of the wavefront experience different speeds, leading to distortions in the wavefront shape. This results in a phase mismatch between the fundamental and second harmonic waves. In different crystals, the wavefronts may be convex or concave. Figure 9. shows a concave wavefront.

<p align="center">
  <img src="./Archive/images/3.%20Readme_images/image09.png" alt="Image 9" width="75%">
</p>

<p align="center"> <strong>Figure 9.</strong> Schematic of the phase mismatch due to temprature gradient within the crystal. In different crystals the wavefronts may be convex or concave. This figure shows a concave wavefront.</p>

Phase is a function of temperature and it is clear that due to the presence of the phase difference in the electromagnetic field equations, this quantity is very effective in determining the efficiency of the SHG. In this way, heat and electromagnetic waves are related indirectly. We can effectively integrate heat considerations into electromagnetic equations, thereby advancing our comprehension of how thermal effects impact the efficiency of nonlinear optical phenomena.

## 7.1. Our Contribution (2)
The heat equation enables us to calculate the Spatial-temporal temperature distribution within the crystal. This temperature profile directly influences the phase mismatch, which can be described by the following equation:

Note: The equations, represented in different colors for $\textcolor{orange}{T}$, and $\textcolor{purple}{\Delta \varphi}$, illustrate they are coupled equations which means changes in one variable influence the entire system simultaneously.

<table style="width: 100%; border-collapse: collapse; border: none;">
  <tr>
    <td style="text-align: left; vertical-align: middle; border: none;">
      $\large +\rho c \frac{\partial \textcolor{orange}{T}}{\partial t}-\vec{\nabla} \cdot (K(\textcolor{orange}{T}) \vec{\nabla} \textcolor{orange}{T}) = S$
    </td>
    <td style="text-align: right; vertical-align: middle; border: none;">
      Heat Equation
    </td>
  </tr>
  <tr>
    <td style="text-align: left; vertical-align: middle; border: none;">
      $\large \textcolor{purple}{\Delta \varphi} = \int_0^z \Delta k(\textcolor{orange}{T}) d z^{\prime}$
    </td>
    <td style="text-align: right; vertical-align: middle; border: none;">
      Phase Mismatch Equation
    </td>
  </tr>
</table>

By solving the heat equation, we obtain the temperature-dependent phase mismatch $(\Delta \varphi)$  across the crystal. This relationship enables us to predict the phase mismatch spatially and temporally, which is crucial for optimizing nonlinear optical processes such as Second Harmonic Generation (SHG). Our contributions in this area are detailed in the following publication:

- **Phase Mismatch _ Pulsed Wave Gaussian** [(Journal)](https://www.researchgate.net/publication/267926440_Thermally_induced_phase_mismatching_in_a_repetitively_Gaussian_pulsed_pumping_KTP_crystal_A_spatiotemporal_treatment), [(Article)](https://drive.google.com/file/d/18VvRk22iipi_4PUVVhzVp16BRNN4TfbN/view?usp=sharing), [(Code)](https://github.com/Mostafa-M-Rezaee/SHG__Second_Harmonic_Generation/blob/main/2.%20SHG%20Codes/4_Phase-Mismatch_Pulsed-Wave_Gaussia.f90)     
This work addresses the issue of Thermally Induced Phase Mismatching (TIPM) in KTP crystals under Pulsed Wave Gaussian conditions. The study developed a spatiotemporal model to examine how temperature rise influences nonlinear conversion efficiency, highlighting the critical need to manage TIPM to optimize SHG performance in pulsed laser applications. The findings emphasize the importance of precise thermal management strategies to reduce phase mismatches and improve overall system efficiency.

# 8. Electromagnetic Field
In ideal conditions where there is no heat dissipation or phase mismatch, all of the fundamental wave is perfectly converted into the Second Harmonic Wave, demonstrating the maximum possible efficiency in nonlinear crystals. 

<p align="center">
  <img src="./Archive/images/3.%20Readme_images/image01.png" alt="Image 1">
</p>

<p align="center"> <strong>Figure 1.</strong> Maximum SHG Efficiency: Achieving full conversion of the Fundamental Wave (FW) to the Second Harmonic Wave (SHW) under ideal thermal and phase conditions.
</p>

## 8.1. Our Contribution (3)
In the following articles, we solve the electromagnetic field equations under idealized conditions, meaning no heat dissipation and no phase mismatch. This allows us to focus solely on the optical electromagnetic field.  The equations are coupled because each electromagnetic field ($\textcolor{red}{\psi_1}$), ($\textcolor{blue}{\psi_2}$), and ($\textcolor{green}{\psi_3}$) interacts through nonlinear terms like $(\textcolor{blue}{\psi_2} \textcolor{green}{\psi_3})$ and $(\textcolor{red}{\psi_1} \textcolor{green}{\psi_3})$, representing energy exchange between the electromagnetic fields. As we see in the formula, to calculate each $(\psi)$, we need to know the values of the other two $(\psi)$ electromagnetic fields. These interactions drive the coupling, which is essential for describing processes like Second Harmonic Generation (SHG). 

Note: The equations, represented in different colors for $\textcolor{purple}{\Delta \varphi}$, $\textcolor{red}{\psi_1}$, $\textcolor{blue}{\psi_2}$, and $\textcolor{green}{\psi_3}$, illustrate they are coupled equations which means changes in one variable influence the entire system simultaneously.

<table style="width: 100%; border-collapse: collapse; border: none;">
    <tr>
    <td style="text-align: left; vertical-align: middle; border: none;">
      $\large \frac{n_1}{c} \frac{d \textcolor{red}{\psi_1}}{d t} + \frac{d \textcolor{red}{\psi_1}}{d z} - \frac{i c}{2 n_1 \omega} \frac{1}{r} \frac{d \textcolor{red}{\psi_1}}{d r} - \frac{i c}{2 n_1 \omega} \frac{d^2 \textcolor{red}{\psi_1}}{d^2 r} + \frac{\gamma_1}{2} \textcolor{red}{\psi_1} = \frac{i}{L_T} \textcolor{blue}{\psi_2} \textcolor{green}{\psi_3} e^{-i \textcolor{purple}{\Delta \varphi}}$
    </td>
    <td style="text-align: right; vertical-align: middle; border: none;">
      First Fundamental Wave Equation
    </td>
  </tr>
  <tr>
    <td style="text-align: left; vertical-align: middle; border: none;">
      $\large \frac{n_2}{c} \frac{d \textcolor{blue}{\psi_2}}{d t} + \frac{d \textcolor{blue}{\psi_2}}{d z} - \frac{i c}{2 n_2 \omega} \frac{1}{r} \frac{d \textcolor{blue}{\psi_2}}{d r} - \frac{i c}{2 n_2 \omega} \frac{d^2 \textcolor{blue}{\psi_2}}{d^2 r} + \frac{\gamma_2}{2} \textcolor{blue}{\psi_2} = \frac{i}{L_T} \textcolor{red}{\psi_1} \textcolor{green}{\psi_3} e^{-i \textcolor{purple}{\Delta \varphi}}$
    </td>
    <td style="text-align: right; vertical-align: middle; border: none;">
      Second Fundamental Wave Equation
    </td>
  </tr>
  <tr>
    <td style="text-align: left; vertical-align: middle; border: none;">
      $\large \frac{n_3}{c} \frac{d \textcolor{green}{\psi_3}}{d t} + \frac{d \textcolor{green}{\psi_3}}{d z} - \frac{i c}{4 n_3 \omega} \frac{1}{r} \frac{d \textcolor{green}{\psi_3}}{d r} - \frac{i c}{4 n_3 \omega} \frac{d^2 \textcolor{green}{\psi_3}}{d^2 r} + \frac{\gamma_3}{2} \textcolor{green}{\psi_3} = \frac{i}{L_T} \textcolor{red}{\psi_1} \textcolor{blue}{\psi_2} e^{i \textcolor{purple}{\Delta \varphi}}$
    </td>
    <td style="text-align: right; vertical-align: middle; border: none;">
      Second Harmonic Wave Equation
    </td>
  </tr>
</table>

We used different wave sources in each article: one uses a Continuous Wave Gaussian source, while the other employs a Pulsed Wave Bessel-Gaussian source. These variations in wave sources provide further insight into how different beam profiles affect the system's behavior.

- **Ideal _ Continuous Wave Gaussian** [(Journal)](https://opg.optica.org/ao/abstract.cfm?uri=ao-54-4-869), [(Article)](https://drive.google.com/file/d/18AKCzgJj9XeXfkdSd-pU1j5JNYf84JRb/view?usp=sharing), [(Code)](https://github.com/Mostafa-M-Rezaee/SHG__Second_Harmonic_Generation/blob/main/2.%20SHG%20Codes/5_Ideal_Continuous-Wave_Gaussian.f90)    
This study explored SHG efficiency under Continuous Wave Gaussian conditions, highlighting how temperature fluctuations can prevent achieving ideal conversion efficiency. The study found that even minor temperature increases could drastically reduce SHG efficiency due to beam depletion and refractive index changes, highlighting the importance of temperature control in optimizing SHG processes.
 
- **Ideal _ Pulsed Wave Bessel Gaussian** [(Journal)](https://opg.optica.org/ao/abstract.cfm?uri=ao-53-32-7691), [(Article)](https://drive.google.com/file/d/18J0wFsrO8zeXkY09Jodgmx6Rkr28w-Ez/view?usp=sharing), [(Code)](https://github.com/Mostafa-M-Rezaee/SHG__Second_Harmonic_Generation/blob/main/2.%20SHG%20Codes/6_Ideal_Pulsed-Wave_Bessel-Gaussian.f90)    
This research introduced a model using Pulsed Bessel-Gauss beams, challenging traditional assumptions like the nondepleted wave approximation. This study provided a more accurate framework for SHG by considering wave depletion effects, demonstrating the impact of beam profile on heat and SHG efficiency under pulsed conditions.


# 9. Interdependency of Heat, Phase, and Electromagnetic Field
To accurately model SHG, it is essential to recognize that heat, phase, and the electromagnetic field are interconnected and must be treated as a coupled system. 

The **heat** governs the temperature distribution within the crystal, which directly influences the refractive index through temperature-dependent material properties. This, in turn, affects the phase mismatch between the interacting waves. The **phase mismatch** modifies the interaction conditions for the fundamental and second harmonic waves, directly impacting their efficiency and the electromagnetic field. The **electromagnetic field** itself defines how the energy is transferred between the waves, how the phase evolves, and how the power distribution affects local heating within the crystal. This heating further alters the temperature profile, creating a feedback loop that perpetuates continuously.

Because of this tightly coupled nature, solving these equations independently would fail to capture the dynamic interactions and feedback mechanisms that occur in real-world conditions. A proper approach is necessary to account for these interdependencies, ensuring a comprehensive and accurate representation of SHG performance under varying thermal and optical conditions.

## 9.1. Our Contribution (4)
In the following article, we solve the coupled equations of heat, phase, and electromagnetic field. This approach provides the most accurate model for Second Harmonic Generation (SHG), as it captures the interdependence between thermal effects, phase mismatch, and electromagnetic field propagation. By treating these elements as a unified system, we achieve a model that is much closer to real-world behavior.

Note: The equations, represented in different colors for $\textcolor{orange}{T}$, $\textcolor{purple}{\Delta \varphi}$, $\textcolor{red}{\psi_1}$, $\textcolor{blue}{\psi_2}$, and $\textcolor{green}{\psi_3}$, illustrate they are coupled equations which means changes in one variable influence the entire system simultaneously.


<table style="width: 100%; border-collapse: collapse; border: none;">
  <tr>
    <td style="text-align: left; vertical-align: middle; border: none;">
      $\large +\rho c \frac{\partial \textcolor{orange}{T}}{\partial t}-\vec{\nabla} \cdot (K(\textcolor{orange}{T}) \vec{\nabla} \textcolor{orange}{T}) = S = \gamma_1 \textcolor{red}{\psi_1} + \gamma_2 \textcolor{blue}{\psi_2} + \gamma_3 \textcolor{green}{\psi_3}$
    </td>
    <td style="text-align: right; vertical-align: middle; border: none;">
      Heat Equation
    </td>
  </tr>
  <tr>
    <td style="text-align: left; vertical-align: middle; border: none;">
      $\large \textcolor{purple}{\Delta \varphi} = \int_0^z \Delta k(\textcolor{orange}{T}) d z^{\prime}$
    </td>
    <td style="text-align: right; vertical-align: middle; border: none;">
      Phase Mismatch Equation
    </td>
  </tr>
  <tr>
    <td style="text-align: left; vertical-align: middle; border: none;">
      $\large \frac{n_1}{c} \frac{d \textcolor{red}{\psi_1}}{d t} + \frac{d \textcolor{red}{\psi_1}}{d z} - \frac{i c}{2 n_1 \omega} \frac{1}{r} \frac{d \textcolor{red}{\psi_1}}{d r} - \frac{i c}{2 n_1 \omega} \frac{d^2 \textcolor{red}{\psi_1}}{d^2 r} + \frac{\gamma_1}{2} \textcolor{red}{\psi_1} = \frac{i}{L_T} \textcolor{blue}{\psi_2} \textcolor{green}{\psi_3} e^{-i \textcolor{purple}{\Delta \varphi}}$
    </td>
    <td style="text-align: right; vertical-align: middle; border: none;">
      First Fundamental Wave Equation
    </td>
  </tr>
  <tr>
    <td style="text-align: left; vertical-align: middle; border: none;">
      $\large \frac{n_2}{c} \frac{d \textcolor{blue}{\psi_2}}{d t} + \frac{d \textcolor{blue}{\psi_2}}{d z} - \frac{i c}{2 n_2 \omega} \frac{1}{r} \frac{d \textcolor{blue}{\psi_2}}{d r} - \frac{i c}{2 n_2 \omega} \frac{d^2 \textcolor{blue}{\psi_2}}{d^2 r} + \frac{\gamma_2}{2} \textcolor{blue}{\psi_2} = \frac{i}{L_T} \textcolor{red}{\psi_1} \textcolor{green}{\psi_3} e^{-i \textcolor{purple}{\Delta \varphi}}$
    </td>
    <td style="text-align: right; vertical-align: middle; border: none;">
      Second Fundamental Wave Equation
    </td>
  </tr>
  <tr>
    <td style="text-align: left; vertical-align: middle; border: none;">
      $\large \frac{n_3}{c} \frac{d \textcolor{green}{\psi_3}}{d t} + \frac{d \textcolor{green}{\psi_3}}{d z} - \frac{i c}{4 n_3 \omega} \frac{1}{r} \frac{d \textcolor{green}{\psi_3}}{d r} - \frac{i c}{4 n_3 \omega} \frac{d^2 \textcolor{green}{\psi_3}}{d^2 r} + \frac{\gamma_3}{2} \textcolor{green}{\psi_3} = \frac{i}{L_T} \textcolor{red}{\psi_1} \textcolor{blue}{\psi_2} e^{i \textcolor{purple}{\Delta \varphi}}$
    </td>
    <td style="text-align: right; vertical-align: middle; border: none;">
      Second Harmonic Wave Equation
    </td>
  </tr>
</table>


- **Coupled _ Continuous Wave Gaussian** [(Journal)](https://opg.optica.org/oe/fulltext.cfm?uri=oe-22-21-25615&id=302163), [(Article)](https://drive.google.com/file/d/18HWrgN8duMyRQpjSpjvIApGhuVh5ti_A/view?usp=sharing), [(Code)](https://github.com/Mostafa-M-Rezaee/SHG__Second_Harmonic_Generation/blob/main/2.%20SHG%20Codes/7_Coupled_Continuous-Wave_Gaussian.f90)     
This study advanced our understanding by incorporating both Thermally Induced Phase Mismatching (TIPM) and thermal lensing into SHG models using a Continuous Wave Gaussian source. By coupling eight different equations, the model captured the dynamic interactions between heat and SHG efficiency over time. This comprehensive approach provided a realistic simulation that closely matched experimental results, significantly enhancing our understanding of thermal effects in Continuous Wave Gaussian SHG systems.


# 10. Methodology
Direct measurement of internal temperature in a nonlinear crystal during Second Harmonic Generation (SHG) is not feasible due to the lack of instrumentation capable of probing the localized, transient thermal effects within the crystal. Conventional techniques are insufficient to resolve the rapid, spatially confined temperature changes, making experimental assessment impractical.

Analytical approaches are similarly challenging due to the complexity of the coupled equations of heat, phase, and electromagnetic field  governing SHG. Analytical solution of these equations requires simplifying assumptions that deviate the model from reality. For example, even the fundamental heat equation which plays a crucial role in this domain, relies on such simplifications. 

However, through computational approaches, we've pushed the boundaries, avoiding any simplifying assumptions to offer a more precise model. For instance, we no longer assume the thermal conductivity coefficient to be constant; instead, it dynamically varies with temperature throughout time. This shift from traditional analytical models, which rely on simplifying assumptions, enables a more accurate study of nonlinear optics phenomena.

## 10.1. Computational Approach using Finite Difference Method (FDM)
Every physical phenomenon is mathematically represented by differential equations, from which we typically derive simplified formulas to make them more practical for use. However, this approach doesn't always lead to a straightforward solution. For instance, in solving SHG computationally, it is often more efficient to work with the differential equations directly by applying their derivatives definition, rather than relying on a derived formula.

We use the FDM as the computational method to model thermal effects in SHG due to its low computational cost and user-friendly nature. FDM offers simplicity in both learning and application. Since heat operates on a macroscopic scale and doesn't vary drastically, FDM provides accurate results without the need for using other complex methods. Its straightforward approach that efficiently captures the thermal dynamics involved in SHG without unnecessary complexity. 

The FDM approximates derivatives in differential equations through discretization of the domain into a grid and replacing derivatives with finite difference expressions. This transforms the equation into a system of algebraic equations solvable with numerical techniques. FDM's accuracy and stability rely on discretization, approximation schemes, and solution methods chosen, offering a versatile and efficient approach for solving complex differential equations when analytical solutions are impractical. By employing FDM, we achieve cost-effective and accurate simulations, making it an ideal choice for modelling thermal effects in SHG processes.

In FDM, we approximate the derivative by choosing a small but finite value of $( \Delta x $). This turns the derivative into a simple difference equation:

$$
f'(x) \approx \frac{f(x + \Delta x) - f(x)}{\Delta x}
$$

This is called the **Forward Difference** approximation.

**A Simple Example**: Approximating the Derivative of $( f(x) = x^2 $)

Let's use FDM to approximate the derivative of the function $( f(x) = x^2 $) at $( x = 2 $).

1. Function Value at $( x = 2 $):
   
$$
f(2) = 2^2 = 4
$$

2. Function Value at $( x + \Delta x $) with $( \Delta x = 0.1 $):
   
$$
f(2 + 0.1) = (2.1)^2 = 4.41
$$

3. Approximate Derivative:
   
$$
f'(2) \approx \frac{f(2 + 0.1) - f(2)}{0.1} = \frac{4.41 - 4}{0.1} = 4.1
$$

4. Exact Derivative for Comparison:
   
   The exact derivative of $( f(x) = x^2 $) is $( f'(x) = 2x $). At $( x = 2 $), this gives:
   
$$
f'(2) = 2 \times 2 = 4
$$

**Note**: The approximation $( 4.1 $) is close to the exact derivative $( 4 $). As $( \Delta x $) becomes smaller, the approximation improves, demonstrating how FDM essentially breaks down the derivative to its fundamental definition by using a discrete, manageable calculation.

This method helps solve differential equations where exact analytical solutions are not feasible, highlighting how FDM is powerful in practical computational scenarios.

# 11. Research Opportunities
While our research has focused on modeling the thermal effects in KTP crystals under specific wave conditions—namely Gaussian Continuous Wave, Gaussian Pulsed Wave, and Bessel-Gauss Pulsed Wave—significant opportunities remain for further exploration in this field. A natural extension of this work involves investigating different types of wave sources and alternative nonlinear crystals. 

The key distinction between different wave types and crystal materials lies in the unique heat transfer behavior each combination exhibits. These variations can fundamentally alter the thermal dynamics within the crystal, leading to different impacts on SHG efficiency and system performance. For instance, the use of other waveforms, such as Hermite-Gaussian or Laguerre-Gaussian beams, or employing different crystal materials like Lithium Niobate or Beta Barium Borate, would result in diverse heat distribution patterns and necessitate distinct thermal management strategies. 

Moreover, while our studies primarily focused on developing detailed models to understand these thermal behaviors, future research can take the next step by conducting comprehensive simulations and experimental validations. These simulations can provide deeper insights into how different thermal properties, such as anisotropic conductivity and varying boundary conditions, influence heat distribution and phase mismatching across various laser and crystal configurations. Such explorations would not only enhance the theoretical understanding but also offer practical guidelines for optimizing SHG systems under varying thermal conditions.

Ultimately, exploring these new avenues will open up entirely new research trajectories, each with its own set of challenges and opportunities. This will enable a more complete understanding of thermal effects in nonlinear optical systems, contributing to the design of more efficient and adaptable laser technologies. To facilitate further research, other researchers can use our GitHub repository as a tutorial, utilizing the provided source code as a foundation for conducting simulations and extending the study in this field. By building on our work, future studies can deepen insights into heat transfer dynamics and refine thermal management strategies across various nonlinear optical configurations.

We are currently working on these topics and are dedicated to pushing this research forward. In the near future, we will share the results of our ongoing studies along with new articles and code updates in this repository. Our goal is to expand thes repository into a more comprehensive resource that will support other researchers in exploring the complexities of thermal effects in nonlinear optics. Stay tuned for these updates, as they will provide even deeper insights and tools to enhance future research in this field.

# 12. How to Cite Us
Please refer to the [**0. Cite Us**](https://github.com/Mostafa-M-Rezaee/SHG__Second_Harmonic_Generation/tree/main/0.%20Cite%20Us) folder for accurate citations. It contains essential guidelines for accurate referencing, ensuring accurate acknowledgement of our work.


# 13. For Additional Questions
If you have questions that are not covered in the resources above, the best way to reach [Mostafa Rezaee](https://www.linkedin.com/in/mostafa-rezaee/).    
- Gmail: mostafa.mohammadrezaee@gmail.com       
- [Linkedin](https://www.linkedin.com/in/mostafa-rezaee/)           




