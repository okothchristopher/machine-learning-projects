# In this Project we will explore the following tasks
We will practice data cleaning skills on the main data (not the summarized version) by perfoming the following tasks:
1. Explore the missingness in the dataset for categorical and numerical data
2. Develop a strategy to deal with the missing values, i.e deletion, imputation by mean or mode etc, whilst providing rationale for your approach.
3. Drop non-consequntial fields
4. Transform temporal data to their corrrect format (date time)
5. Perfom a full EDA and demonstrate the validity of the following assumptions
> - Moore's Law still holds, especially in GPUs.
> - Dannard Scaling is still valid in general.
> - CPUs have higher frequencies, but GPUs are catching up.
> - GPU performance doubles every 1.5 years.
> - GPU performance improvement is a joint effect of smaller transistors, larger die size, and higher frequency.
> - High-end GPUs tends to first use new semiconductor technologies. Low-end GPUs may use old technologies for a few years.
> - Process Size for Intel, AMD and Nvidia lies in comparatively lower range than for ATI and other vemdors
> - TSMC makes the highest number of chips in the world

6. Calculate and visualized the correlation among the features
7. Perfom the correct encoding for the data, in readiness for modelling.

# bonus task

We will explore a classification model to predict whether a product is a GPU or a CPU based on the other independent variables.
We will Compare the perfomance of a Random Forest Classifier with that of a Logistic Regression Model


# data dictionary

# `semiconductor-chips.csv`

|variable                 |class     |description |
|:------------------------|:---------|:-----------|
|date                     |double    |Date of release    |
|type                     |character |Type of chip    |
|foundry                  |character | Creator    |
|vendor                   |character | Vendor    |
|process_size_nm_mean     |double    | Process size in nanometer    |
|process_size_nm_sd       |double    |    Process size in nanometer |
|tdp_w_mean               |double    | Thermal design profile    |
|tdp_w_sd                 |double    |Thermal design profile    |
|die_size_mm_2_mean       |double    | Die size in millimeters^2    |
|die_size_mm_2_sd         |double    |Die size in millimeters^2    |
|transistors_million_mean |double    | Transitor count in millions    |
|transistors_million_sd   |double    |Transitor count in millions    |
|freq_m_hz_mean           |double    | Frequency (Mhz)    |
|freq_m_hz_sd             |double    |Frequency (Mhz)    |
|n                        |integer   | Total number of observations for date, type, foundry, vendor grouping    |

