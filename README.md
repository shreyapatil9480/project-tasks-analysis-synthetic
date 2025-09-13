# Synthetic Project Tasks Analysis

This repository contains a **synthetic dataset** simulating project management tasks, along with a Jupyter notebook demonstrating exploratory data analysis (EDA), visualization, and predictive modeling. It is designed to showcase analytical skills relevant to roles such as **Business Analyst**, **Program Manager**, and **Data Analyst**.

## Dataset

The dataset `synthetic_project_tasks.csv` includes 300 synthetic records of project tasks, with the following columns:

| Column | Description |
| --- | --- |
| `ProjectID` | Identifier for each project (e.g., `Project_1`, `Project_2`). |
| `TaskID` | Unique identifier for each task (e.g., `T0001`). |
| `TaskName` | Short task description (e.g., *Strategic Planning*). |
| `AssignedTo` | Team member responsible for the task. |
| `StartDate` | Task start date. |
| `EndDate` | Task end date. |
| `DurationDays` | Duration of the task in days. |
| `Budget` | Allocated budget for the task (USD). |
| `ActualCost` | Actual cost incurred (USD). |
| `TaskStatus` | Current status (`Not Started`, `In Progress`, `Completed`, `Cancelled`, `On Hold`). |
| `Priority` | Priority level (`Low`, `Medium`, `High`, `Critical`). |
| `CompletionPercentage` | Percent completion (0–100). |
| `OverBudget` | Indicator whether actual cost exceeded the budget (`1`=Yes, `0`=No). |

All data is **synthetic** and generated for demonstration purposes only.

## Notebook

The Jupyter notebook `analysis.ipynb` demonstrates:

- Loading and exploring the dataset.
- Computing summary statistics and visualizing distributions (e.g., budgets, costs, task status counts).
- Creating scatter plots to examine relationships between budget and actual cost.
- Preprocessing categorical variables and building a logistic regression model to predict whether a task will go over budget (`OverBudget`).
- Evaluating the model using a confusion matrix and classification report.

## How to Use

1. Clone or download this repository.

```bash
git clone <repository_url>
cd <repository_name>
```

2. (Optional) Create a virtual environment and install dependencies:

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

3. Open the Jupyter notebook:

```bash
jupyter notebook analysis.ipynb
```

4. Run the notebook cells to explore the dataset and reproduce the analysis. Feel free to modify the code to explore further insights or experiment with different models.

## Dependencies

Dependencies are listed in `requirements.txt` and include:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- nbformat

## License

This project is released under the MIT License. The data is synthetic and free to use for educational and demonstration purposes.


## Additional Notes

This project is designed as a portfolio piece showcasing data analysis and predictive modeling skills. You can extend the synthetic dataset, customize the notebook, or adapt the analysis to fit specific domains or business scenarios. Contributions and suggestions are welcome!
