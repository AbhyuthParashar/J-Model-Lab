# J-Model-Lab

🛠 Description:

This Python-based tool allows users to model and visualize capillary pressure (Pc) as a function of water saturation (Sw) using the Leverett J-function. It uses curve_fit to estimate model parameters and provides interactive sliders (via ipywidgets) for intuitive sensitivity analysis.

📊 Features:

1. Fits experimental Pc vs Sw data using the Leverett J-function.

2. Estimates key parameters: A, b, Swr (irreducible water saturation), and Sor (residual oil saturation).

3. Interactive sliders to adjust and visualize the impact of each parameter in real time.

4. Uses Matplotlib for clear visualization.

5. Ideal for petroleum engineering lab data analysis.


📦 Libraries Used:

NumPy

Matplotlib

SciPy (curve fitting)

ipywidgets (interactive controls)

🚀 How to Run:

Install ipywidgets if not already.

Run the Python script in Jupyter Notebook or Google Colab for full interactivity.

🧠 Concept Behind:

The Leverett J-function is used to normalize capillary pressure data in porous media by accounting for wettability, saturation, and pore geometry. This tool helps in:

Visualizing core flooding or drainage-imbibition behavior.

Understanding rock-fluid interaction.

History matching and reservoir characterization workflows.

Author:
Abhyuth Parashar.
abhyuthp@gmail.com
