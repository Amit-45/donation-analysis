# Project and funding analysis

## Table of Contents
- [Project Description](#project-description)
- [Tech Stack Used](#tech-stack-used)
- [Libraries Used](#libraries-used)
- [Loading Data](#loading-data)
- [Head of Each Data](#head-of-each-data)
- [Describe Data](#describe-data)
- [Creating New Data by Merging](#creating-new-data-by-merging)
- [List of Columns](#list-of-columns)
- [Questions Solved](#questions-solved)
- [Screenshots](#screenshots)
- [License](#license)
- [Contributing](#contributing)
- [Pdf file of analysis](#analysis)

## Project Description

This project focuses on analyzing data related to school projects and donations. The goal is to gain insights into various aspects such as the number of schools opening projects, the amount of donations received, the relationship between projects and donations, and the performance  of different states in terms of donations.

<img width="992" alt="Screenshot 2023-06-28 at 12 10 30 AM" src="https://github.com/Amit-45/donation-analysis/assets/77204104/e4afb87e-9e68-48f9-8495-3528ca1ff5f1">


The analysis involves loading the required datasets, merging them into a comprehensive dataset, and performing descriptive analysis to extract meaningful information. Key statistical measures like minimum, maximum, mean, median, and percentiles of donations are analyzed. Additionally, visualizations such as bar plots are created to present the findings effectively.

<img width="755" alt="Screenshot 2023-06-28 at 12 12 34 AM" src="https://github.com/Amit-45/donation-analysis/assets/77204104/aced8319-90bc-4859-87e7-baa6d9b92352">

## Tech Stack Used

- Python

## Libraries Used

- [Pandas](https://pandas.pydata.org/): Used for data manipulation and analysis.
- [NumPy](https://numpy.org/): Used for numerical computations and array operations.
- [Matplotlib](https://matplotlib.org/): Used for data visualization and plotting.
- [Scikit-learn](https://scikit-learn.org/): Used for machine learning and statistical modeling in Python.

## Loading Data

- Load the required datasets into the analysis environment.
- Use Python and appropriate libraries (e.g., Pandas) to read and import the data.

## Head of each data

- Display the first few rows of each dataset to get a quick overview of the data structure and contents.
- Utilize Pandas' `head()` function to retrieve the desired information.

## Describe data

- Perform a descriptive analysis of the datasets to gain insights into their statistical properties.
- Use Pandas' `describe()` function to compute statistical measures such as mean, standard deviation, quartiles, etc.

## Creating new data by merging all datasets into a single data

- Combine the separate datasets into a single comprehensive dataset for further analysis.
- Utilize appropriate merging techniques (e.g., Pandas' `merge()` function) based on common columns or keys.

## List of columns in the created data

- Generate a list of columns present in the merged dataset.
- Use Pandas' `columns` attribute or `head()` function to obtain the desired information.

## Questions Solved

1. Which 10 states have the most number of schools that opened projects to gather donations? Plot the data using a bar plot.
2. What are the top 10 states in which schools gathered the most amount of average donations?
3. Analyze the minimum, maximum, mean, median, 25 and 75 percentiles of donations.
4. In which states are there the most donations done by donors?
5. Is there any relationship between the number of projects offered and the number of donations made by donors?
6. Which states are performing better in terms of the number of donations per project? How many of them respond to project requests below average?
7. We need to find the number of projects per state and the number of donations per state and then merge both. Fit a linear model to indicate the relationship between projects and donations.
8. What are the different types of projects that exist? What is the total amount of donation for each type?

## Screenshots

<img width="644" alt="Screenshot 2023-06-28 at 12 16 27 AM" src="https://github.com/Amit-45/donation-analysis/assets/77204104/300e9160-3a9a-44bc-84ec-03303de50cbe">


## License

This project is licensed under the MIT License. Feel free to use, modify, and distribute the code for personal or commercial purposes.

## Contributing

Contributions are welcome! If you encounter any issues or have suggestions for improvement, please open an issue or submit a pull request. We appreciate your feedback and collaboration.

Please note that the tech stack and libraries mentioned above are just samples



# Analysis 
Check the analysis here !!  👉 [analysis pdf file](https://github.com/Amit-45/donation-analysis/files/11885775/school.donation.analysis.pdf)
