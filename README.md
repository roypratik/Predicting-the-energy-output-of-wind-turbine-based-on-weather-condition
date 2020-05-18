Wind energy plays an increasing role in the supply of energy world-wide. The energy output of a wind farm is highly dependent on the wind conditions present at its site. If the output can be predicted more accurately, energy suppliers can coordinate the collaborative production of different energy sources more efficiently to avoid costly overproduction.

Develop a time series model to Predict the power output of wind farm based on the weather condition in the site (1Hr prediction to 72Hrs. prediction) Build an application to recommend the Power Grid to suggest the best time to utilize the energy from wind farm


We visualized the provided dataset and we found a strong correlation between the wind speed and the output power. There is a significant amount of deviations from the theoretical output of power and actual output. We plan to reduce this deviation and create a deep learning model that can give better predictions of output power way ahead of time.

Actual Output and Windspeed


Theoretical output vs Windspeed



We plan to use the time series analysis to come up with a solution that can forecast the output power in the near future. We plan to implement this by bidirectional-LSTM. We will train our model for a specific window and will check the accuracy by testing using unseen data. This will help us to forecast the output power of a given time frame.


Upon implementation of this solution, the wastage of energy can be minimized drastically. The energy will be dynamically distributed when there is an excessive output of power. The present scenario doesn't predict the power output so sudden increment in output causes heavy loss to renewable energy. We plan to effectively utilise the excess production of power by predicting the output power way ahead of time.

Our solution is unique as it improves the current situation by effectively minimising the wastage of generated power. We are using a deep learning model, deployed on IBM cloud to give a solution to the problem statement.


Our solution increases the profitability of the wind energy company and also creates a social impact by delivering power to those in need. In India, we have a huge potential market as India uses only 16.1% of renewable energy and wind energy is only 9.2%. India is focussing more into the production of energy from renewable sources and this creates huge opportunities for the companies to make these kinds of projects highly efficient.

IBM Watson Studio
IBM Cloud
Node-RED
Python3

Our solution can be used for predicting wind energy production on a smaller scale—for individual wind turbines on private farms or urban buildings, or for small wind farms. For future work, we are planning further study of the possibilities for longer-term wind energy forecasting.
