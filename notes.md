## Bloch Theorem

The theorem states that all one-electron wave functions, for problems involving periodically varying potential energy functions, must be of the form:  

`ψ(x) = u(x) · exp(j · k · x)`

## k-Space Diagram
![Band Gap Animation](https://upload.wikimedia.org/wikipedia/commons/d/d2/Bulkbandstructure.gif)

**Image Attribution:**  
"Bulkbandstructure.gif" by Solid State is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).  
Source: [Wikipedia](https://en.wikipedia.org/wiki/File:Bulkbandstructure.gif)

Note: Click the link above to view the animation.

### Impurity Ionization Energies in Silicon and Germanium

| **Impurity**   | **Ionization Energy (eV)** |            |  
|----------------|----------------------------|------------|  
|                | **Si**                     | **Ge**     |  
| *Donors*       |                            |            |  
| Phosphorus     | 0.045                      | 0.012      |  
| Arsenic        | 0.050                      | 0.0127     |  
| *Acceptors*    |                            |            |  
| Boron          | 0.045                      | 0.0104     |  
| Aluminum       | 0.060                      | 0.0102     |


## Two basic transport mechanisms in a semiconductor crystal:
1. Drift—the movement of charge due to electric fields  
2. Diffusion—the flow of charge due to density gradients

The carrier transport phenomena are the foundation for finally determining the current–voltage characteristics of semiconductor devices.

Typical mobility and diffusion coefficient values at $T = 300 \, \text{K}$  

| **Material**         | $\mu_n$ (cm²/V·s) | $D_n$ (cm²/s) | $\mu_p$ (cm²/V·s) | $D_p$ (cm²/s) |
|----------------------|-------------------|---------------|-------------------|---------------|
| **Silicon**          | 1350              | 35            | 480               | 12.4          |
| **Gallium Arsenide** | 8500              | 220           | 400               | 10.4          |
| Germanium            | 3900              | 101           | 1900              | 49.2          |



Excess electrons and excess holes do not move independently of each other.
These excess carriers diffuse, drift, and recombine with the same effective diffusion coefficient, drift mobility, and lifetime. 
This phenomenon is called **ambipolar transport**.

Excess carriers dominate the electrical properties of a semiconductor material, and the behavior of excess carriers is fundamental to the
operation of semiconductor devices. 



| **Symbol**            | **Definition**                                                                                  |
|-----------------------|-------------------------------------------------------------------------------------------------|
| *n₀, p₀*              | Thermal-equilibrium electron and hole concentrations (independent of time and usually position) |
| *n, p*                | Total electron and hole concentrations (may be functions of time and/or position)               |
| *δn = n − n₀*         | Excess electron concentration (may be a function of time and/or position)                       |
| *δp = p − p₀*         | Excess hole concentration (may be a function of time and/or position)                           |
| *g′ₙ, g′ₚ*            | Excess electron and hole generation rates                                                       |
| *R′ₙ, R′ₚ*            | Excess electron and hole recombination rates                                                    |
| *τₙ₀, τₚ₀*            | Excess minority carrier electron and hole lifetimes                                             |


For an extrinsic semiconductor under low injection, the effective diffusion coefficient and mobility parameters are those of the **minority carrier**.


## Ambipolar Transport under Low Injection

**For p-type semiconductor**:

$$
D_n \frac{\partial^2 (\delta n)}{\partial x^2} + \mu_n \mathbf{E} \frac{\partial (\delta n)}{\partial x} + g' - \frac{\delta n}{\tau_{n0}} = \frac{\partial (\delta n)}{\partial t} \tag{1}
$$

**For n-type semiconductor**:

$$
D_p \frac{\partial^2 (\delta p)}{\partial x^2} - \mu_p \mathbf{E} \frac{\partial (\delta p)}{\partial x} + g' - \frac{\delta p}{\tau_{p0}} = \frac{\partial (\delta p)}{\partial t} \tag{2}
$$

It is crucial to understand that the transport and recombination parameters in Equations (1) and (2) correspond to those of the minority carriers. These equations govern how excess minority carriers move and recombine over time and space due to drift and diffusion. Under the assumption of charge neutrality, the excess majority carrier concentration equals that of the minority carriers. As a result, the excess majority carriers move together with the minority carriers, and their behavior is dictated by the minority carrier properties. This ambipolar transport effect is fundamental in semiconductor physics and forms the foundation for analyzing and modeling the behavior of semiconductor devices.
