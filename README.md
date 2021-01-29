# Internet-Income-Inequality-Regression-Model
Regression Model to predict Estonia's Income Inequality using it's Internet Access Data
# README

The following is a Jupyter Notebook containing the code for a Regression Model that uses Estonia's Internet Access Data to predict their Income Inequality. 

1. The first Jupyter Notebook is titled Model 1 and contains the code for training the model using all available Estonian Internet Access and Income Inequality data from the following resources which are in CSV format.
    - Estonian Internet Access Data: [https://data.worldbank.org/indicator/IT.NET.USER.ZS?end=2019&locations=EE&start=1995](https://data.worldbank.org/indicator/IT.NET.USER.ZS?end=2019&locations=EE&start=1995)
    - Estonian Income Inequality Data: [https://wid.world/data/#countrytimeseries/gptinc_p0p100_z/EE/1980/2019/eu/k/p/yearly/g](https://wid.world/data/#countrytimeseries/gptinc_p0p100_z/EE/1980/2019/eu/k/p/yearly/g)
2. The second Jupyter notebook titled Model 2 contains almost the same code except it filters out all the years Estonia had an income access of under 40% and trains a model on that data. The same data sets were used as above and were filtered in the code. 

### Making The Code Work For Both Models

1. **If you want to download the dataset from the source:** For this to work with the code, the Estonian Internet Access and Income Inequality data must be in a single column in order by year. The CSV files when downloaded from the resources will have extra columns such as years and other countries so ensure to filter them out.
2. **The quick way**: The formatted data sets for Estonian income inequality and Internet Access will be provided in the repository if you do not want to download them from the source.
3. Ensure that the now formatted CSV files are in the same folder/directory as the downloaded Jupyter Notebook or use the OS library in python and change the working directory to the location where the CSV files are. 
4. Then in the line of code documented as "Reading CSV" make sure you change the name of the CSV file that is in between parentheses and quotes to the name you saved the CSV file as to make this code work. This step does not apply if you are using the same CSV file name as I did.
5. Now you can run all the code and can see the results.

### Results

Spoiler Model 1 is a weak non-predictive model while Model 2 is a strong predictive one. This means that Estonia Internet Access can predict income inequality only above 40% Internet Access.

For further reading on this and why it matters you can go to the link to my full paper on this in my Github bio.
