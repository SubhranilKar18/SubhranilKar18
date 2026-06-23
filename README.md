# Hi, I'm Subhranil Kar 👋
**3rd Year B.E. student in Electronics and Telecommunication Engineering at Jadavpur University**

I am trying to focus on bridging the gap between theoretical circuit analysis and practical implementation. I have strong fundamentals in analog circuit design and simulations, and technical documentation.

### 🛠️ Technical Toolbox
* **Simulation & Design:** LTspice (Advanced DC/AC/Transient), MATLAB, Simulink.
* **Analysis Techniques:** Frequency Response (Bode Plots), Pole-Zero Analysis, Transfer Function (`.tf`), and Parameterized Measurement (`.meas`).
* **Hardware & HDLs:** 8085 Microprocessor, Verilog HDL, FPGA.
* **Languages:** C, C++, MATLAB & Python.

### 📈 Featured Projects
#### 🟢 [Circuit-Theory-to-Implementation Using LTSpice](https://github.com/SubhranilKar18/Circuit-Theory-to-Implementation-Using-LTSpice)
A structured series of simulations exploring circuit theorems and analog behaviors.

* **Common Drain (Source Follower) Amplifier:** Designed a high-speed voltage buffer stage using a 180nm bulk CMOS process. Simulated impedance transformations to protect high-gain active blocks from heavy loading, and mapped sub-micron non-idealities like the physical **Body Effect** ($g_{mb}$).

* **Common Source Amplifier Stage:** Characterized a 180nm active CMOS gain stage using voltage divider bias. Analyzed high-pass roll-off driven by input/output coupling networks and high-frequency constraints imposed by Miller-multiplied device parasitics.

* **MOSFET Characterization:** Mapped nested `.dc` sweeps of discrete and sub-micron transistors. Extracted threshold voltage ($V_{th}$) and plotted real-time transconductance profiles using `d(Id(M1))`.

* **First-Order Transient Response (RC & RL):** Conducted a comparative study of energy storage dynamics. Verified the duality between capacitor voltage charging and inductor current energizing using PULSE source characterization and automated $\tau$ extraction.

* **Maxwell Inductance-Capacitance Bridge:** Proved the frequency-independent balance condition of AC bridges. Analyzed the transition from **Zero-Order behavior** to high-frequency second-order roll-off caused by **Pole-Zero mismatch** in the SPICE solver.

* **Maximum Power Transfer Analysis:** Demonstrated the **Maximum Power Transfer Theorem** by using `.step` parameter sweeps to identify the exact load resistance ($R_L = R_{th}$) required for peak power delivery.

* **Thevenin & Norton Equivalents:** Simplified complex unbalanced bridge networks into equivalent models. Verified results using the 1A Test Source method and Short-Circuit current probing.

* **Wheatstone Bridge Analysis:** Investigated bridge sensitivity and verified quadratic power relationships using multi-pane DC sweeps.

### 🧪 Engineering Approach
* **System Dynamics:** Understanding the physical order of circuits and how pole-zero cancellations can be used to linearize system responses.
* **Time & Frequency Duality:** Proficient in analyzing circuits across both domains—utilizing `.tran` for switching dynamics and `.ac` for steady-state stability.
* **Computational Insight:** Ability to differentiate between ideal theoretical results and simulation limitations (e.g., numerical noise floor in high-accuracy AC nulls).
* **Rigorous Verification:** Committed to cross-verifying simulation results with manual theoretical derivations (e.g., equate real and imaginary parts of complex impedance) to ensure design reliability.

### 📫 Connect with Me
[LinkedIn](https://www.linkedin.com/in/subhranil-kar-a3a830230/) | [Email](mailto:subhranilkar.ece@gmail.com)
