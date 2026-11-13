# WDM-Ex.NO-10-Sentimental-Analysis-on-Any-dataset-Using-Rapidminer
## NAME: Subha shree U
## DATE:10-11-2026
**AIM:**<br>
To create a project for Sentimental Analysis on Any Dataset a Using Rapidminer<br>
**Description:**<br>
**Procedure:**<br>
**1.Import Excel data**<br>
a. Drag the "Read Excel" operator from the IO folder onto the process canvas.

b. Double-click on the operator to open its configuration panel.

c. Specify the path to the Excel file you want to analyze.

d. Configure options such as sheet selection, header inclusion, etc.

e. Click on the "Run" button to execute the operator and import the Excel data.<br>

**2.Perform sentiment analysis with Generate Attributes operator**<br>
a. Drag the "Generate Attributes" operator from the Operators panel onto the canvas.

b. Connect the output of the "Extract Sentiment" operator to the input of the "Generate Attributes" operator.

c. Double-click on the "Generate Attributes" operator to configure it.

d. Specify a name for the new sentiment attribute you want to generate (e.g., "Sentiment").

e. Choose the sentiment analysis algorithm, "VADER."

f. Click on the "Run" button to perform sentiment analysis on the Excel data and generate the sentiment attribute.

**3.Interpret and export the results**<br>
a. Analyze the sentiment analysis results from the generated visualizations.

b. If desired, drag the "Write Excel" operator onto the canvas to export the sentiment analysis results to a new Excel file.

c. Connect the output of the visualization operator(s) to the input of the "Write Excel" operator.

d. Configure the file path and other settings for the Excel export.

e. Click on the "Run" button to export the sentiment analysis results to a new Excel file.

**Design:**<br>
<img width="1047" height="550" alt="image" src="https://github.com/user-attachments/assets/eebf3fb9-d041-4356-ae31-ecbbdd428251" />

**Output:**<br>
<img width="852" height="795" alt="image" src="https://github.com/user-attachments/assets/dd7fa76c-e962-4f23-b2a4-545a35d08cf5" />


**Result:**
Sentimental Analysis on Twitter Dataset Using Rapidminer is implemented.
