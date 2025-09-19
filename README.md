# Bio_Medical_Data_Analysis
<br>
<p>
  Biomedical datasets such as HR, RESP, SpO₂, PPG, and ECG are rich in information but challenging to analyze due to their size, noise, and multi-signal complexity. Current analysis methods demand programming expertise, repeated scripting, and significant time investment, creating barriers for students, researchers, and healthcare innovators. This project aims to bridge that gap by providing a user-friendly, GUI-based tool that simplifies biomedical signal analysis, visualization, and feature extraction without requiring coding knowledge.
</p><br>
<p>
  This program is a **PPG signal analysis tool with a GUI** built using Tkinter. It allows the user to select one or more `_Signals.csv` files containing physiological data and then performs multiple analyses on the PPG (photoplethysmography) and respiration signals. The code first cleans the PPG signal with a moving average filter, detects peaks, and computes **HRV measures** (Mean RR, SDNN, RMSSD, pNN50, and heart rate). It then applies an **FFT** to extract frequency domain features (LF, HF, LF/HF ratio) and estimates the **respiration rate** using the baseline-corrected PPG signal. All results are saved into a CSV file for record-keeping and displayed in the GUI text box, while plots show raw and filtered signals, peaks, frequency spectrum, and respiration signals.

The code solves the issue by **automating biomedical signal analysis** in a user-friendly way. Instead of manually filtering signals, detecting peaks, or calculating HRV and respiration metrics, the program integrates everything into one GUI-based workflow. The user only needs to select the correct `_Signals.csv` file, set the maximum number of readings, and run the analysis. The uniqueness lies in combining **time-domain, frequency-domain, and respiration analysis** within a single lightweight Python tool that requires no specialized software, making it accessible for students, researchers, or healthcare innovators.

</p>
