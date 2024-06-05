# Visualizing Analysis Results for Software Product Line Models - A User Study
 
This repository includes the supporting material for the paper "Visualizing Analysis Results for Software Product Line Models - A User Study."

## File description

- **graphProductLine**: The code implementing the graph product line and the Neo4j queries used to create the model extracted from the code. 
- **rawData**: The data recorded during the study and used in statistical tests. Files follow the name convention *scenario_variable.csv*, in which *scenario* describes the task category (identify, compare2, or compare3), the study stage (stage1 or stage 2), or the treatment type (visualizationOption) being tested, and *variable* describes the dependent variable (correctness, efficiency, or mental effort) being recorded.
- **statisticalTestResults**: The results of the statistical tests using the files from folder *rawData*. Files in this folder follow a similar name convention with the addition of the suffix *_tTest* and *_OneWay Anova* to describe the performed tests.
- **demographics**: The participants' demographic information.