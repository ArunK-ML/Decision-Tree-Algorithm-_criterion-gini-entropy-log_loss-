# Decision-Tree-Algorithm-_criterion-gini-entropy-log_loss-
In scikit-learn’s DecisionTreeClassifier, the criterion parameter defines the function used to measure the quality of a split.

| Criterion    | Description                                                                             | Used For                       |
| ------------ | --------------------------------------------------------------------------------------- | ------------------------------ |
| `"gini"`     | Measures impurity using **Gini Index** (default)                                        | Classification                 |
| `"entropy"`  | Uses **Information Gain** (based on Shannon entropy)                                    | Classification                 |
| `"log_loss"` | Minimizes **log loss** (also called cross-entropy loss); supports probabilistic outputs | Classification (probabilistic) |

