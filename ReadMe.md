# TOPSIS Package

Submitted by:
- Bhumika Tandon
- 102203280

## What is TOPSIS?
TOPSIS (Technique for Order Preference by Similarity to Ideal Solution) is a multi-criteria decision-making method that helps in ranking and selecting from several alternatives based on their closeness to an ideal solution. It's particularly useful when you have to consider multiple, sometimes conflicting criteria.It is a method of compensatory aggregation that compares a set of alternatives by identifying weights for each criterion, normalising scores for each criterion and calculating the geometric distance between each alternative and the ideal alternative, which is the best score in each criterion.
An assumption of TOPSIS is that the criteria are monotonically increasing or decreasing. In this Python package Vector Normalization has been implemented.

_This package has been created based on Project 1 of course UCS654.
Bhumika Tandon 102203280 3C22_

To install,run in cmd:

```bash
pip install -e .[dev]
```

After installation, in Command Prompt/Terminal in pwd/current dir:

```bash
topsis <InputDataFile> <Weights> <Impacts> <ResultFileName>
```
