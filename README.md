# Semisolve: Python-based III-V Nitride Semiconductor Device Simulation Framework

**Semisolve** is a flexible, Python-based simulation framework designed for analyzing the physical behavior of III-V Nitride-based semiconductor heterostructures. 

Moving beyond traditional "black-box" TCAD tools, Semisolve provides a **"Scriptable TCAD"** environment. It empowers researchers and engineers to define complex device structures, select physical models, and execute high-precision calculations entirely through Python scripts.

---

## Key Features

* **Open & Extensible:** A free, open-source (FOSS) alternative to commercial TCAD, designed for academic transparency and seamless integration into modern data science workflows.
* **Scriptable TCAD:** A "Python-first" approach allowing full control over device definition, material parameters, and simulation loops using NumPy, SciPy, and Pydantic.
* **Data Science Ready:** Seamlessly integrates with the standard Python data stack (NumPy, SciPy, Pandas, Matplotlib). Results are ready for immediate analysis, visualization, and machine learning workflows.
* **Numerical Stability:** Specialized algorithms to overcome extreme concentration gradients and carrier concentration underflow in wide-bandgap semiconductors, ensuring robust convergence via Hybrid Gummel-Newton and precision-aware damping.
* **Nitride Semiconductor-Centric Physics:** Native support for spontaneous and piezoelectric polarization, strain-induced band offsets, and wide-bandgap material properties (GaN/AlGaN/InN).

---

## Current Status

* **Project Founder & Lead Developer:** **Takeru Kumabe** ([@tkrkmb](https://github.com/tkrkmb))
* **Current Phase:** **Private Development.** I am currently specializing in 1D band diagram calculations and self-consistent IV characteristic simulations for III-V Nitride heterostructures.
* **Public Release Target:** **Mid-2026**

## License

This project is licensed under the [Apache License 2.0](LICENSE).

**Disclaimer regarding Intellectual Property:**
This software is developed based on public facts described in academic papers and textbooks. If it infringes upon anyone's intellectual property, please contact the developer, and the relevant parts will be privatized or corrected.

---

## Contact

For inquiries regarding the project's progress or potential collaborations, please reach out via the developer's GitHub profile.
