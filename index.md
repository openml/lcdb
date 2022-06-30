## LCDB 1.0

The use of learning curves for decision making in supervised machine learning is standard practice, yet understanding of their behavior is rather limited. 
To facilitate a deepening of our knowledge, we introduce the Learning Curve Database (LCDB), which contains empirical learning curves of 20 classification algorithms on 246 datasets.
One of the LCDB's unique strength is that it contains all (probabilistic) predictions, which allows for building learning curves of arbitrary metrics.
Moreover, it unifies the properties of similar high quality databases in that it (i) defines clean splits between training, validation, and test data, (ii) provides training times, and (iii) provides an API for convenient access (pip install lcdb). We demonstrate the utility of LCDB by analyzing some learning curve phenomena, such as convexity, monotonicity, peaking, and curve shapes.
Improving our understanding of these matters is essential for efficient use of learning curves for model selection, speeding up model training, and to determine the value of more training data.

# Paper

The LCDB paper has been accepted for publication at ECML/PKDD 2022. We will link to an open accessible version soon. 

# Installation

LCDB can be installed in Python using the following commandline command. 
```
pip install LCDB
```

# Download

The raw learning curve data (>200GB) can be downloaded using [this link](https://u.pcloud.link/publink/show?code=kZS8m5VZQaOWdf2Q7FmMcKUKCc6cMpggDJRV).
