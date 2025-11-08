Grouped Data Statistics Calculator
This Python script calculates mean, median, mode, variance, and standard deviation for grouped frequency data. It’s ideal for statistical analysis of age distributions, survey results, or any dataset organized into intervals.
Features
- ✅ Calculates mean using midpoints and frequencies
- ✅ Computes median using cumulative frequency and interpolation
- ✅ Determines mode using the modal class formula
- ✅ Computes variance and standard deviation using squared deviations
- ✅ Displays a detailed breakdown table with intermediate values
Input Structure
age_groups = [(15, 25), (25, 35), (35, 45), (45, 55), (55, 65)]
frequencies = [350, 375, 120, 80, 90]


- age_groups: List of tuples representing class intervals
- frequencies: List of frequencies corresponding to each interval

📌 Output
The script prints:
- A formatted table showing:
- Class intervals
- Frequencies
- Midpoints
- f\times x
- Cumulative frequency
- Squared deviations
- f\times \mathrm{squared\  deviation}
- Summary statistics:
- Mean
- Median
- Mode
- Variance
- Standard Deviation

🛠 Requirements
- Python 3.x
- No external libraries required

📌 How to Run
python grouped_statistics.py



📬 Author
Developed by Harish — passionate about statistical analysis, Python logic, and data visualization.
