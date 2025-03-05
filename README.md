# Ms and Bs Temperature Calculator

## Overview
This project calculates the martensite start temperature (Ms) and bainite start temperature (Bs) for steel alloys based on various empirical equations. It allows the user to input the chemical composition of the steel and choose between different models to estimate these temperatures.

If the user knows the experimental Ms value, the program computes the percentage difference between the estimated and experimental values and visualizes the results.

## Features
- Computes Ms using multiple empirical equations
- Compares estimated Ms with an experimental value (if available)
- Graphical visualization of the results
- Supports a wide range of alloying elements

## Requirements
Ensure you have Python installed along with the required libraries:

```bash
pip install matplotlib numpy
```

## How to Use
1. Run the script in a Jupyter Notebook or as a Python script.
2. Input the chemical composition of the steel alloy when prompted.

![image-1](https://github.com/user-attachments/assets/fae9deed-ab88-4679-a792-517ad07fbea8)


3. Choose whether you know the experimental Ms value:
   - If yes, enter the value and view the percentage difference.
   - If no, see the estimated values from different equations.
4. The results are displayed as a bar chart.

## Example Output
- A bar chart showing the calculated Ms values from different equations.
- 
![Ms](https://github.com/user-attachments/assets/adefdc10-2504-4a06-899e-5d56b906288b)
![Bs](https://github.com/user-attachments/assets/dbb0c8e2-297b-4c21-b174-dd5a0591cac9)

- If an experimental value is provided, a comparison chart with percentage differences.

![BsDff](https://github.com/user-attachments/assets/b443d5f4-786a-46cf-8b2a-470716ca223b)
![MsDff](https://github.com/user-attachments/assets/3a3795b8-1744-4738-a363-dea3b5884205)


## Equations Used
The script implements the following equations for Ms calculation:
- Saha Equation
- Andrews Corrected Equation
- Nehenberg Equation
- Steven-Haynes Equation
- Payson & Savage Equation
- Rowland Equation
- Grange & Stewart Equation
- Andrews Empirical Equation
- Steven & Haynes 2 Equation

The script implements the following equations for Bs calculation:
- Bohemen
- Steven and Hyanes
- Lee & Matt
- Zhao 1
- Zhao 2
- Bodnaretal
- Kirkaldy & Venugopalan
- Suehiro
- Lee
- Kunitake
- J Trzaska

## References

[1] A. Saha Podder and H. K. D. H. Bhadeshia, "Thermal stability of austenite retained in bainitic steels," Materials Science and Engineering A, vol. 527, pp. 2121-2128, 2010.
[2] Andrews, K. W. "Empirical formulae for the calculation of some transformation temperatures." J. Iron Steel Inst 203.7 (1965): 721-727.
[3] Nehrenberg A. E., Discussion of ref. 18., Trans AIME, 167 (1956) 494-498.
[4] W. Stevens and A. G. Haynes: J. Iron Steel Inst., 183 (1956), 349.
[5] S. M. C. van Bohemen: Mater. Sci. Technol., 28 (2012), 487.
[6] W. Stevens and A. G. Haynes: J. Iron Steel Inst., 183 (1956), 349.
[7] Y. K. Lee: J. Mater. Sci., 21 (2002), 1253.
[8] J. Zhao, C. Liu, Y. Liu and D. O. Northwood: J. Mater. Sci., 36(2001), 5045.
[9] J. Zhao: Mater. Sci. Technol., 8 (1992), 1004.
[10] R. L. Bodnar, T. Ohhashi and R. I. Jaffee: Metall. Trans. A, 20A (1989), 1445
[11] . S. Kirkaldy and D. Venugopalan: Phase Transformations in Ferrous Alloys, ed. by A. R. Marder and J. I. Goldstein, TMS-AIME, Warrendale, PA, (1984), 125.
[12] M. Suehiro, T. Senuma, H. Yada, Y. Matsumura and T. Ariyoshi: Tetsu-to-Hagané, 73 (1987), 1026.
[13] T. Kunitake and Y. Okada: J. Iron Steel Inst., 84 (1998), 137.
[14] J. K. Lee: Prediction of Tensile Deformation Behavior of Formable Hot Rolled Steels. POSCO Technical Research Laboratories Report, POSCO, Pohang, Korea, (1999).
[15] Trzaska, J. "Calculation of Critical Temperatures by Empirical Formulae." Archives of Metallurgy and Materials 61.2 (2016): 981-986.

## Contributions
Contributions are welcome! If you find a bug or want to add new features, feel free to open an issue or submit a pull request.

## Author
Jisel Ibargüen
