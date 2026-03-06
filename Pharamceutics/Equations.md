
### 1. Single Oral Dose (First-Order Absorption)

Calculating plasma concentration ($C_p$) at any time ($t$) after an oral dose is more complex than IV because it accounts for both the absorption rate ($k_a$) and elimination rate ($k$).

$$C_p = \frac{F \cdot D \cdot k_a}{V_d(k_a - k)} (e^{-kt} - e^{-k_at})$$

- **$F$**: Bioavailability (fraction of dose reaching systemic circulation).
- **$D$**: Dose administered.
- **$k_a$**: Absorption rate constant.
- **$k$**: Elimination rate constant.
- **$V_d$**: Volume of distribution.

---

### 2. Volume of Distribution ($V_d$) and Clearance ($Cl$)

These are the two most fundamental parameters in PK.

- **Volume of Distribution:** Relates the amount of drug in the body ($A_b$) to the measured plasma concentration ($C$).
    
    $$V_d = \frac{Dose}{C_0}$$
    
    _(Use $C_0$ for IV bolus; for oral, use $F \cdot Dose$)_.
    
- **Clearance:** The volume of plasma cleared of drug per unit of time.
    
    $$Cl = k \cdot V_d$$
    
    _Alternatively, using Area Under the Curve (AUC):_
    
    $$Cl = \frac{F \cdot Dose}{AUC}$$
    

---

### 3. Elimination Half-Life ($t_{1/2}$)

For first-order kinetics, the half-life is constant regardless of the dose.

$$t_{1/2} = \frac{0.693}{k} = \frac{0.693 \cdot V_d}{Cl}$$

---

### 4. Multiple Dosing & Steady State ($C_{ss}$)

When a drug is given repeatedly at a dosing interval ($\tau$), it eventually reaches a plateau where rate in = rate out.

- **Average Steady State Concentration:**
    
    $$C_{ss,avg} = \frac{F \cdot Dose}{Cl \cdot \tau}$$
    
- **Dosing Interval ($\tau$):** If you have a target $C_{ss}$ and know the clearance, you can rearrange to find how often to dose:
    
    $$\tau = \frac{F \cdot Dose}{Cl \cdot C_{ss,target}}$$
    

---

### 5. Loading Dose ($LD$) vs. Maintenance Dose ($MD$)

- **Loading Dose:** Used to reach steady state immediately.
    
    $$LD = \frac{C_{target} \cdot V_d}{F}$$
    
- **Maintenance Dose:** Used to maintain steady state by replacing what is cleared.
    
    $$MD = \frac{C_{target} \cdot Cl \cdot \tau}{F}$$
    


---

### 6. Noyes-Whitney Equation (Dissolution)

This is the most important equation for understanding how fast a tablet or powder dissolves in the GI tract.

$$\frac{dC}{dt} = \frac{DA(C_s - C)}{h}$$

- **$dC/dt$**: Rate of dissolution.
- **$D$**: Diffusion coefficient.
- **$A$**: Surface area of the drug (Why we **granulate** or micronize!).
- **$C_s$**: Solubility of the drug in the solvent.
- **$C$**: Concentration of drug in the bulk solvent at time $t$.
- **$h$**: Thickness of the stagnant diffusion layer.
    

---

### 7. Stokes' Law (Sedimentation)

Used to predict the stability of **suspensions**. It tells you how fast particles will settle to the bottom of the bottle.

$$v = \frac{d^2(\rho_s - \rho_l)g}{18\eta}$$

- **$v$**: Sedimentation velocity.
- **$d$**: Diameter of the particle.
- **$\rho_s - \rho_l$**: Density difference between the particle and the liquid.
- **$g$**: Acceleration due to gravity.
- **$\eta$**: Viscosity of the medium (Why we add **thickening agents** to reduce settling).

---

### 8. Stokes-Einstein Equation (Diffusion)

Relates the diffusion of particles to the temperature and viscosity of the system.

$$D = \frac{kT}{6\pi\eta r}$$

- **$D$**: Diffusion coefficient.
- **$k$**: Boltzmann constant.
- **$T$**: Absolute temperature.
- **$\eta$**: Viscosity.
- **$r$**: Radius of the particle.

---

### 9. Henderson-Hasselbalch Equation (pH & Ionization)

Critical for predicting drug absorption. Remember: **Unionized drugs cross membranes; ionized drugs don't.**

- **For Weak Acids:** $pH = pK_a + \log\frac{[Salt]}{[Acid]}$
- **For Weak Bases:** $pH = pK_a + \log\frac{[Base]}{[Salt]}$
    

---

### 10. Required HLB (RHLB)

Used to calculate how much surfactant (emulsifier) you need to create a stable **emulsion**.

$$HLB_{mix} = f_A \times HLB_A + f_B \times HLB_B$$

- **$f$**: Fraction of the specific surfactant in the blend.
- **Rule of Thumb:**
    - **HLB 3–6:** W/O (Water-in-Oil) emulsifier.
    - **HLB 8–18:** O/W (Oil-in-Water) emulsifier.

---
