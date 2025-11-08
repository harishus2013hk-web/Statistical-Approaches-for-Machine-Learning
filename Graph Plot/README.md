Frequency Distribution Bar Chart in Python
This script visualizes the frequency distribution of a dataset using a bar chart with matplotlib.
🔧 Features
- Counts the frequency of each unique value in the dataset.
- Sorts the values for a clean visual layout.
- Displays a bar chart with custom colors and edge styling.
- Annotates each bar with its frequency value.
- Includes axis labels, title, and grid for readability.
📦 Requirements
- Python 3.x
- matplotlib library
📈 How It Works
- Data Preparation:
data = [2,2,3,3,3,4,4,4,5,6,6,6,7,7,7,7,8,2,4,5,6,8,8,9]
- A list of numeric values representing raw observations.
- Frequency Calculation:
freq = {}
for i in data:
    freq[i] = freq.get(i, 0) + 1
- Builds a dictionary where keys are unique values and values are their counts.
- Sorting and Extraction:
classes = sorted(freq)
frequency = list(freq.values())
- Sorts the values and prepares lists for plotting.
- Plotting:
plt.bar(classes, frequency, color="green", edgecolor="red")
- Creates a bar chart with green bars and red edges.
- Annotations and Styling:
- Adds frequency labels above each bar.
- Sets axis labels and chart title.
- Enables grid for better readability.
