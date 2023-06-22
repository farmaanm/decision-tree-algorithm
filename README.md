# decision-tree-algorithm

A decision tree algorithm has been developed for the provided dataset, which consists of over 1500 records, 6 columns and 1 class column.
- ID
- Buying
- Maintain
- Doors
- Persons
- LuggageBoot
- Safety
- Class Value (unacc/acc)

Initially, the dataset has been cleaned by dropping null values, unwanted columns, and outliers, etc. Following the cleaning of data, the `Entropy` value of each column and the `Information Gain` has been calculated, and the maximum information gain has been selcted as the node of the tree.

---

## Libraries used

- pandas
- NumPy
- pprint
