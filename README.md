# Optimization_Final_Project
This is a repository for the final project code section in optimization
<br><br>
To run the notebooks in this repository a file named "AXISBANK_with_indicators_.csv" is required.
Please download the file from https://www.kaggle.com/datasets/debashis74017/stock-market-data-nifty-50-stocks-1-min-data or alternitavely, contact me at omri9195@gmail.com and I will gladly provide the exact file used in the notebooks.
<br><br>
All notebooks use the above dataset, as well as **Adam optimizer**. They differ in model architectures, model parameters, epochs, and insight.
The notebooks contained are:<br><br>
Optimization-LSTM-2048-epochs-in-total.ipynb - this notebook contains the LSTM, trained for a total of 2048 epochs (by running the train cell 1024 epochs twice, if running locally, please run twice as well as in a row the kernel may die).
The LSTM is trained on a subset of the data accounting for ~6.5 months. The sequence length used in 32 time units for inference and for train. Includes trading demos, visualizations, and inference on train for optimizer sanity.<br><br>
Optimization_Transformer_Continuous_early_stop_after_n_epochs_only.ipynb - this notebook contains the Transformer model trained with continuous value targets, trained for a total of 183 epochs. This notebook contains visualizations, trading demos,
re-training for 26 weeks, as well as inference on train. This model is trained on data of ~7 years.<br><br>
Optimization_Transformers_combined_binary_continuous_early_stop.ipynb - this notebook contains two transformer models, one trained with continuous value targets, the second on binary value targets w.r.t derivative direction.
This notebook is trained on the same data as above, and it contains similar details.<br><br>
Optimization_Plots.ipynb - this notebook contains plots used in the presentation.
<br><br>
Each notebook only depends on the data file, they have no dependencies with each other (they do not share any function.py files or etc.)
<br><br>
Do note that the notebooks take a long time to run, ranging from several hours, to ~40 hours (computing power dependant)
<br><br>
Thanks :)
Omri
