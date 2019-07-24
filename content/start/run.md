---
title: "Running the Notebooks"
chapter: false
weight: 24
---
If we reload the Notebook, we'll see a new folder called "1-pure-sagemaker-workshop"

We will run all the notebooks there in order.
The First Notebook it can run without modifications.
In the Second Notebook it's important to:

* Create a bucket for this notebook (ie: "sales-prediction-mrtdom")
* Change the bucket name to some of your own in the step 3: bucket = 'sales-prediction-mrtdom' and from then it can run without modifications.

In the Third Notebook take special care in the last step, if you get an "Best training job not available for tuning job" it's mostly because the training jobs are still running. The process takes roughly 20 minutes so it's a good moment to get a cup of coffee or have a break.

The Fourth Notebook can run without modifications.

The Fifth Notebook needs the data of the best training job from the last step of the Third Notebook (best_training_job). From then it can run without modifications.
