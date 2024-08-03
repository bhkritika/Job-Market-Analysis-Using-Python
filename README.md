# Job Market Analysis Using Python

## Project Overview

This project provides a comprehensive analysis of job market data. The dataset includes various attributes related to job postings, such as experience required, salary details, job locations, and ratings. The analysis covers multiple aspects to gain insights into job trends, salary distributions, and job ratings across different titles and locations.

## Dataset

The dataset includes the following columns:
- `Sr_no`: Serial number
- `job_title`: Title of the job
- `company`: Company offering the job
- `experience`: Experience required for the job
- `min_exp`: Minimum experience required
- `max_exp`: Maximum experience required
- `base_salary`: Base salary offered
- `max_salary`: Maximum salary offered
- `location`: Job location
- `jobListed(days_ago)`: Number of days ago the job was listed
- `postedIn`: Date when the job was posted
- `rating`: Rating of the job
- `reviews_count`: Number of reviews for the job
- `details`: Additional details about the job

## Analysis and Visualizations

1. **Experience Range Distribution**: Distribution of job postings across different experience levels.
2. **Base Salary Distribution**: Distribution of base salaries across job postings.
3. **Max Salary Distribution**: Distribution of maximum salaries offered in job postings.
4. **Average Rating per Job Title**: Average ratings for different job titles.
5. **Reviews Count per Job Title**: Total number of reviews for each job title.
6. **Job Listings by Location**: Distribution of job listings across various locations.
7. **Job Listings by PostedIn**: Job listings based on the date they were posted.
8. **Experience vs Max Salary**: Relationship between experience levels and maximum salary offered.
9. **Group by Job Title and Aggregate**: Aggregated metrics based on job titles.
10. **Use a Facet Grid for Better Clarity**: Facet grid for clearer visualization of multiple aspects.
11. **Base Salary by Location**: Comparison of base salaries across different locations.
12. **Correlation Heatmap**: Correlations between various numeric features.
13. **Salary Range by Job Title**: Salary ranges associated with different job titles.
14. **Ratings Distribution by Job Title**: Distribution of ratings across job titles.
15. **Correlation Between Rating and Reviews Count**: Relationship between ratings and reviews count.
16. **Base Salary and Max Salary vs Job Listed Days Ago**: Relationship between salary and job listing age.
17. **Interactive Scatter Plot**: Interactive plot for exploring relationships between numeric features.
18. **Interactive Heatmap**: Interactive heatmap of job listings by location and experience level.
19. **Location vs Experience Level**: Distribution of experience levels across different locations.

## Installation and Setup

To run this project locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git


2. **Navigate to the Project Directory**:
   ```bash
   cd your-repo-name

3. **Install Dependencies**:
   ```bash
    pip install -r requirements.txt

4. **Run the Analysis**:
Execute the Jupyter notebooks or Python scripts to perform the analysis.

## Files Included

- `data/`: Directory containing the dataset.
- `notebooks/`: Jupyter notebooks with the analysis and visualizations.

## Acknowledgments
- Seaborn
- Plotly
- Pandas
- NumPy