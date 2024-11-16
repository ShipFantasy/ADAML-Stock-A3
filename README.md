# ADAML-Stock-A3

## Week ML2:

We are getting to know the data. Find an informative way to visualize the time series. Start a reporting document where you will add to the model bits by bits. Time-series visualization and partition materials:  

Time-series decomposition [Python] [MATLAB] 
partition of time-series data [MATLAB] for validation purposes [Python, but also descriptive].
autocorrelation analysis [MATLAB], [Python] In your first submission, present:
(0.5p) a visualization for the data, that is appropriate for time-series, and initial exploratory analysis\
(0.5p) a time-series decomposition analysis in long-term trend, seasonality and residuals\
(0.5p) an autocorrelation analysis of the dataset\
(0.5p) a plan for partitioning the time-series data for model formation\

## Week ML3:  Data pretreatment & baseline models

Some materials to help you with this submission:

To reason our usage of recurrent neural networks, we need to have a comparisson with an autoregressive model, a benchmark comparison. Some of the models you will develop will perform better than the autoregressive models, and some not. Here is an example on performing autoregressive model computations on a synthetic sinusoidal data [MATLAB: video, resource] [Python: resource]. This is utilized for baseline predictions and initial comparison. 
In the following submission, think about the following items

(0.3p) Do you have continuous measurements with the same frequency? If not, what procedures can you employ to have the data sampled at the same rate.\
(0.3p) Is your data synchronous across all the variables? If not, what procedures can you utilize to bring the data in the same timesteps? \
(0.3p) Do you have missing values in your data? if yes, are there multiple consecutive missing values? what are some strategies for filling in the missing values?\
(0.1p) Can you use the STL decomposition to spot and eliminate possible outliers?\
(0.5p) Do a mini literature-review. (i) on dividing a long time-series into sub-samplings (multiple sequences). How can the sub-sequencing be done? How does seasonality affect sub-sequencing? Can we consider trends and seasonality in LSTM models? (ii) what are some typical standardization methods for LSTM.\
(0.5p) Run a baseline model, to have some initial model results for to compare against. You can choose it yourself based on what is utilized in literature, or you can use the autoregressive model above.


## Week ML4:

The A level teams will perform both RNN and LSTM model calibration. The B-level teams will choose only one of them (RNN or LSTM).\
Here is an example of training an RNN for time-series forecasting, on an Airline passengers dataset [MATLAB: resource][Python: example resource]. Normalize the data for better performance.\
Here is an example of training LSTM for time-series forecasting, on Macroeconomic US data [MATLAB: resource, video][Python: example resource, good tool if you have a single long time-series and you wish to partition it into sequences [batches]]. To avoid padding, the sequences can be ordered by sequence length, and thus padding variable for each minibatch. Normalize the data for better performance.\


##Week ML5:

To make forecasts with Transformer NN, you have the tools available from Week 5's workshop. \
In addition the following might serve useful:\
MATLAB: This starting point example
Python: (1) torch This starting point example (re-up); (2) Library; (3) Tutorial.
