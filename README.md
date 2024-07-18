This Java program calculates electricity bills based on customer details such as consumption units, category, phase, and type. It uses predefined rates and government duties to compute the total bill amount. The calculated details are then stored in a text file.

Features
Input Handling: Takes input from the user including customer name, ID, present and previous readings, category, phase, and type.
Bill Calculation: Calculates the bill amount based on consumption units, category, and phase using predefined rates.
Additional Charges: Includes fixed monthly charges and Fuel and Power Purchase Price Adjustment (FPPPA) in the bill calculation.
Government Duty: Applies government duty based on the type of customer (residential, commercial, industrial, etc.).
Output: Displays a detailed breakdown of the bill including rates, charges, FPPPA, government duty, and the final net bill amount.
File Output: Stores the calculated details in a text file named electricitybill.txt.
Usage
Customer Input:
Enter customer details such as name, ID, present and previous readings, category, phase, and type.
Bill Calculation:
Based on the input details, the program calculates the bill amount considering the specific rates for different categories and phases.
Output Display:
Displays a detailed breakdown of the bill including all charges and taxes.
File Storage:
Saves the generated bill details in a text file (electricitybill.txt) for future reference.
Categories and Phases
Categories:
RGP (Residential General Purpose)
GLP (General Lighting Purpose)
BPL (Below Poverty Line)
Phases:
Single Phase
Three Phase
Customer Types
Types:
Residential
Commercial
Industrial
Religious
Hostel
Each type attracts a different rate of government duty, which is applied to the total energy cost excluding government duty.
