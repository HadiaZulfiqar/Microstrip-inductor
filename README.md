<h1>Microstrip Inductor Design and HFSS Simulation</h1>

Design, mathematical calculation, verification, and Ansys HFSS electromagnetic simulation of a short-circuit microstrip inductor operating at a 2.4 GHz center frequency with a 100 MHz bandwidth on a Rogers RO4003C substrate.

<h2>Explanation</h2>

<h3>Overview</h3>
<p>
This project focuses on designing a planar microstrip inductor using a short-circuited microstrip transmission line model operating at a microwave center frequency of 2.4 GHz with a characteristic impedance of 50 ohms. The design utilizes a Rogers RO4003C substrate with a dielectric constant of 3.38 and a thickness of 0.5 mm to replace bulky conventional inductors at high frequencies.
</p>

<h3>Design</h3>
<img width="606" height="459" alt="image" src="https://github.com/user-attachments/assets/ee34dd04-8c94-4d16-a266-5db41b6ba725" />
<img width="611" height="402" alt="image" src="https://github.com/user-attachments/assets/ccbbf543-5c24-4676-bd55-3071361f099e" />
<img width="613" height="396" alt="image" src="https://github.com/user-attachments/assets/cb238ea5-f240-4205-bcb7-24f94c396a50" />
<img width="512" height="481" alt="image" src="https://github.com/user-attachments/assets/92e30dd5-89b1-46b7-b6fa-a9ba57402d77" />
<img width="489" height="319" alt="image" src="https://github.com/user-attachments/assets/1a7d2b5c-041e-41fb-9410-e1303e3e0f41" />


<h3>Theoretical Calculations & Parameter Synthesis</h3>
<p>
Analytical formulations were applied to determine the precise physical dimensions required for the 50-ohm characteristic impedance and required inductance:
</p>
<ul>
  <li><b>Microstrip Width ($w$):</b> Calculated using impedance ratio equations for $Z_0 = 50\,\Omega$, yielding a width-to-height ratio of $\frac{w}{h} = 2.33$. With a substrate thickness $h = 0.5\text{ mm}$, the physical width is $w = 1.165\text{ mm}$.</li>
  <li><b>Microstrip Length ($l$):</b> Calculated by evaluating the effective relative permittivity ($\epsilon_{eff} = 2.19$), phase velocity ($v_p = 0.675c$), and phase constant ($\beta = 75.02\text{ rad/m}$). For a short-circuit line configuration, the physical length is solved as $l = 20.5\text{ mm}$.</li>
  <li><b>Loss & Return Loss Analysis:</b> Evaluated conductor, dielectric ($\epsilon_{eff} = 2.66$), radiation, and reflection mechanisms. Ideal short-circuit calculations confirm a reflection coefficient $\vert{}\Gamma\vert{} = 1$ and a theoretical return

<h3>Results</h3>
<img width="1192" height="357" alt="image" src="https://github.com/user-attachments/assets/da3def9b-9666-45da-b596-2a9dfc6e83c9" />
<img width="1198" height="460" alt="image" src="https://github.com/user-attachments/assets/442ce039-f710-4cde-ae70-6b9947bf5478" />
