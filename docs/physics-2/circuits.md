# Circuits

## Resistors

Resistance is measured in ohms ($\Omega$).

### Resistivity

$$
    R = \frac{\rho l}{A}
$$

### Equivalent Resistance

$$
    R_s = \sum_{i} {R_i}\\
    \frac{1}{R_p} = \sum_{i} {\frac{1}{R_i}}
$$

## Capacitors

Capacitance is measured in farads (F).

### Capacitance

$$
    C = \kappa\epsilon_0\frac{A}{d} = \frac{Q}{V}\\
    U_C = \frac{1}{2} Q\Delta{V} = \frac{1}{2} C(\Delta{V})^2\\
    \epsilon_0 = 8.85\times10^{-12} \enspace C^2 / N \cdot m^2
$$

Vacuum permittivity ($\epsilon_0$) is always constant. Dielectric constant
$\kappa$ depends on the material between the plates and doesn't have any units.

### Equivalent Capacitance

$$
    \frac{1}{C_s} = \sum_{i} {\frac{1}{C_i}}\\
    C_p = \sum_{i} {C_i}
$$

Equivalent capacitance is the opposite of equivalent resistance.

### Charge, Discharge

$$
    \tau = R * C\\
    \color{grey}
    V_c = V_s (1 - e^{-\frac{t}{RC}})
$$

Capacitor charge and discharge are exponential, so at one time constant $\tau$,
the capacitor has charged or discharged by 63%. After $5\tau$ seconds, charging
is virtually complete.

## Electricity

$$
    V = IR\\
    P = IV\\
    I = \frac{\Delta{Q}}{\Delta{t}}\\
    I = \frac{\Delta{V}}{R}
$$
