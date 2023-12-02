# MVMTN

MVMTN: A multi-task learning framework for multi-view predictive business process monitoring

## Requirements

python==3.9.12 <br />
Levenshtein==0.21.0 <br />
matplotlib==3.5.1 <br />
numpy==1.22.3 <br />
pandas==1.5.2 <br />
pandoc==2.3 <br />
pm4py==2.7.4 <br />
sklearn==1.1.3 <br />
torch==1.12.0 <br />
torch-geometric==2.1.0 <br />
tqdm==4.64.1

## Prepare

raw datasets are placed in path 'raw_datasets'

use 'mkdir datasets_results' and 'mkdir processed_datasets' to store the datasets.

run 0.raw_dataset_process.ipynb to process xes format datasets into csv format.

## Pattern mining

run 1.multi_view_pattern_mining.ipynb to mine frequent pattern from different view

## Trace matching

run 2.prefix_generating_and_trace_matching.ipynb to perform prefix generating and trace matching

## Multi-task learning

use 'mkdir results' to store the results of MTL model

run 3.multi_task_learning.ipynb to train the MTL model

run 3.multi_task_learning_no_frequent.ipynb to train the model without frequent learning module

run 3multi_task_learning_no_task.ipynb to train the model without task aggregation module

