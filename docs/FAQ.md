
### **What kind of license does PortPy use?**
PortPy code is distributed under the **Apache 2.0 license with the Commons Clause**.  
It is available **free for non-commercial academic purposes**.  
For commercial use, please contact the PortPy PI, Masoud Zarepisheh at [zarepism@mskcc.org](mailto:zarepism@mskcc.org).

---

### **How can I use my own patient data?**
PortPy currently supports importing patient data only from the **Eclipse TPS** using its API  
([see notebook](https://github.com/PortPy-Project/PortPy/blob/master/examples/eclipse_photon_dose_calculation.ipynb)). This includes extracting all necessary data for optimization,  
such as the **dose influence matrix** (i.e., a 2D matrix representing 3D dose distributions  
from thousands of beamlets).

---

### **Can I use other open-source software for dose calculation and PortPy for planning optimization?**
One of PortPy’s goals is to generate **clinically usable, deliverable plans** with dose calculations  
that match commercial TPS accuracy. Therefore, we currently do **not** support integrating  
other open-source dose engines into PortPy.

However, users are welcome to use other software for dose calculation and PortPy solely for  
optimization **if clinical-level dose accuracy is not required** for their use case.

---

### **Can I do proton therapy optimization with PortPy?**
Currently, PortPy only supports **photon therapy optimization**.  
Proton therapy support is expected to be released in 2026.

---

### **I have a medical physics background but not in mathematical optimization. Can I still use PortPy?**
Absolutely. PortPy is designed to be **user-friendly and accessible**.  
You can get started using our ready-made **Jupyter Notebooks and tutorials** without needing  
a deep understanding of optimization theory.

---

### **I have a mathematical optimization background but not in medical physics. Can I still use PortPy?**
Yes. Many PortPy contributors come from optimization and engineering backgrounds.  
The **benchmark datasets** and **baseline algorithms** are designed to help users without  
medical physics expertise explore radiotherapy treatment planning.

---

### **I have an engineering/software development background. Can I contribute to PortPy?**
Yes! PortPy is an open-source project and **welcomes community contributions**.  
Please reach out to Gourav Jhanwar, Lead Developer ([jhanwarg@mskcc.org](mailto:jhanwarg@mskcc.org)).


