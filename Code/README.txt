INSTRUCTIONS TO RUN CODE
-----------------------
1. Open OSRT.ipynb in Jupyter Notebook, or in Hex (https://app.hex.tech).
2. Upload provided datasets to accompany the Jupyter file
3. Run the "Package Installation" block of code to install the GOSDT and the OSRT modules into the kernel session.

Running GOSDT or OSRT
--------------------
1. In the OSRT Model Training block, you can run either the GOSDT or the OSRT.
2. To run the OSRT, change line 19 to read in the name of the uploaded regression dataset (Medicaid_Conditions_Binarized.csv).
3. Run this block of code.

4. To run the GOSDT, change line 19 to read in the name of one of the uploaded binary datasets (heart_binarized.csv or anxiety_binarized.csv).
5. Uncomment line 64, and comment out line 65.
6. Uncomment lines 89-91, and 94-96.
7. Run this block of code.

Run other models
-----------------
1. To run other models, go to the Standard Model Testing block.
2. To run classification models, change line 9 to read in the name of one of the uploaded binary datasets (heart_binarized.csv or anxiety_binarized.csv).
3. Comment out the following lines: 20, 56, 95-96, 98-101, 150.
4. Uncomment the following lines: 19, 31-33, 42-44, 55, 70-72, 83-85, 102-103, 105-108, 127-129, 138-140, 151, 163-165, 173-175, 190, 194, 201-203, 210-212, 226, 230, 237-239, 246-248
5. Run this block of code.

6. To run regression models, change line 9 to read in the name of the uploaded regression dataset(Medicaid_Conditions_Binarized.csv).
7. Uncomment the lines that were commented out in step 3.
8. Comment out the lines that were uncommented in step 4.
9. Run this block of code.