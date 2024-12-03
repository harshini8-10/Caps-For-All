# Title of the Project: Caps For All  

## Datathon Achievement  
**Winner of Datathon 1.0**  
For more details, visit the [Datathon 1.0 Project Gallery](https://csueastbay-datathon-2024.devpost.com/project-gallery), which highlights the winning projects.  

## Description  
"Caps For All" is a data-driven initiative that addresses educational disparities in the United States. The project aligns with **Sustainability in Education** and supports the **United Nations Sustainable Development Goals (SDGs)**:  

### SDG 4: Quality Education  
- Focus on increasing enrollment rates for underserved age groups.  
- Address barriers to education for marginalized communities.  
- Enhance educational attainment by improving the quality of education delivered.  

### SDG 5: Gender Equality  
- Analyze gender disparities in educational attainment across states.  
- Highlight areas where gender equity in education needs improvement.  
- Recommend policies to empower women and girls through equal education opportunities.  

### SDG 10: Reduced Inequalities  
- Study disparities in educational attainment by race, gender, and disability status.  
- Identify high-performing states to replicate best practices in underperforming regions.  
- Develop recommendations to close the gap in education access and attainment.  

The project uses interactive visualizations with dropdown menus for insights and comparisons across educational factors such as age, race, gender, and disability.

## Goals  
1. **Analyze Enrollment Trends**: Understand the enrollment proportions across various age groups and identify areas requiring improvement.  
2. **Assess Disparities**: Investigate disparities in educational attainment across race, gender, and disability status.  
3. **Compare States**: Compare state-wise education enrollment and attainment to identify high and low-performing regions.  
4. **Provide Recommendations**: Develop actionable insights and strategies to address educational inequities and improve access and quality.  
5. **Support SDGs**: Contribute to achieving SDG 4, SDG 5, and SDG 10 through data-driven solutions and analysis.  

## Key Files  
- `QualityEducation.csv`: Core dataset used for analysis.  
- `Primary_Secondary_Education.png`: Visualization support file.  
- `Dataset_Description.pdf`: Metadata for understanding dataset columns and variables.  
- `Caps For All.ipynb`: Jupyter Notebook with code and analysis.  
- Generated interactive HTML files: Explore trends and disparities through visualizations.

## Technologies Used  
- **Programming Language**: Python  
- **Environment**: Jupyter Notebook  
- **Visualization Tools**: Plotly for creating interactive HTML visualizations.  

## Dataset  
**Name**: `QualityEducation.csv`  
**Description**: Educational Accessibility, Quality, and Outcomes in the U.S. (2015-2019)  
**Size**: 260 rows × 77 columns  
**Features**:  
- **GeoName**: List of U.S. states  
- **Age Group Levels**: Proportion of enrollment by age  
- **Race-Based Educational Attainment**: Levels of education achieved across racial groups  
- **Gender Disparities**: Proportion of attainment for males and females  
- **Disability Status**: Education outcomes for individuals with and without disabilities  

## Pre-requisites  
**Library Installation**:  
Install the following libraries before running the script:  

!pip install pandas numpy scikit-learn plotly matplotlib seaborn category-encoders dmba

!pip install pandas numpy plotly ipython

## Script File  
`Caps For All.ipynb`  
- The Jupyter Notebook script contains all the steps for data preparation, analysis, and visualization.  

## How to Use  

### 1. **Prepare the Environment**:  
   - Ensure the dataset (`QualityEducation.csv`), image (`Primary_Secondary_Education.png`), and metadata file (`Dataset_Description.pdf`) are in the same directory as the script.  
   - Install the required libraries using the commands provided above.  

### 2. **Run the Script**:  
   - Open the `Caps For All.ipynb` file in Jupyter Notebook.  
   - Execute all cells sequentially to preprocess the data, analyze trends, and generate visualizations.  

### 3. **Explore Outputs**:  
   - The project generates interactive HTML visualizations with dropdown menus for comparing trends across educational dimensions like age, race, gender, and disability.  
   - Use these outputs to gain insights into state-wise and demographic-specific disparities in education.  

## Methodology  

### Data Preparation:  
1. Load the dataset and check for duplicates.  
2. Handle missing data using imputation techniques.  
3. Clean and preprocess the data for analysis.  

### Exploratory Data Analysis (EDA):  
1. Analyze trends in enrollment across age groups over the years.  
2. Assess disparities in educational attainment based on race, gender, and disability.  
3. Compare state-wise performance for primary and secondary education.  

### Interactive Visualizations:  
1. Create dropdown-enabled HTML visualizations for easy navigation and comparison of insights.  
2. Include charts and maps to illustrate key findings.  

### Insights & Recommendations:  
1. Identify areas of concern and provide actionable strategies to improve education access and quality.  
2. Develop state-specific recommendations to replicate successful practices in underperforming areas.  

## How to Use:  

**Clone the Repository**:  
   Clone this GitHub repository to your local machine.  
   ```bash
   git clone https://github.com/yourusername/CapsForAll.git
