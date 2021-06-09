# Master-Thesis-Research
<h3> A Study of Visual and Data Analytics of Multivariate Time Series </h3>

<h3> Overview </h3>

<p> Time series analysis (TSA) is process of collecting the data at regular time intervals within certain time to determine trends, seasonal variances and cycle’s that helps to forecast the future event. Within the Time Series Analysis, Time Series forecasting is the use of a model to predict future values based on previously observed values. Time series are widely used for non-stationary data, like economics, finance, stock trading, weather-energy, web traffic forecasting, retail, and e-commerce sales forecasting. Several methods and algorithms are used to determine univariate time series data like SARIMA and ARIMA whereas, majority of data are nonlinear multi variables and unstructured format so the significant scope of research is to forecast multivariate time series. Multivariate time series data contains multiple variables to reflect the real life and massive amount of data that has been created in the form of multivariate time series. Therefore, the task of analysing and forecasting multivariate time series is both challenging and important across industry and academic sectors such as forecasting stock price on a given day, forecasting economic growth of the company, forecasting power consumption and weather, forecasting demands of the products, and so on. Currently every industry using time series forecasting models to make better decision about their business process to improve services and products. </br>

<h3> Scope of the research </h3>

<p>The project aims to analyse and forecast multivariate time series which can ultimately help make better decision to improve business process. The scope of the research is to evaluate Multivariate Time Series Forecasting (MTSF) and determine different models or algorithms for MTSF. In addition to this, the study compares all the algorithms and proposes an optimized solution model for the analysing multivariate time series and visual analytics of different time series datasets. The study will collect and pre-process two different datasets for multivariate time series forecasting and define a concrete problem for MTSF. It offers visual analytics of different time series datasets and apply python and statistical algorithms, machine learning and deep learning algorithms to get desired analysis and forecasting results. </br>

<h3> Design and Structure of the Research </h3>

<h3> Statistical analysis and modelling </h3>

<p>In part one of the thesis, all the statistical models such as ARIMA, SARIMA, moving average, weighted moving average and VARMA has been applied and these models are good to capture seasonality of the business trend and can capture short term past data to make future prediction. All the statistical models based on simple linear regression algorithms but these models are not able to capture non-linear relationship between variables and not able to capture long term sequence information which is necessary to predict future trends as small mistake can cause million dollars particularly for economics and financial forecasting. To address this problem, we need advanced algorithms such as ensemble models (advanced machine learning) and deep learning (neural network) based algorithms.</br>

<h3> Machine learning & Deep learning algorithms </h3> 

<p>Second part of the thesis, machine learning and deep-learning based algorithms have been applied such as (tree-based model) random forest, XG boost and deep-learning based algorithms such as MLP, CNN, RNN, LSTM ang GRU can work very well with non-linear relationship as these algorithms has multiple functions including linear-algebra based functions, calculus (differentiation), optimisation algorithms, chain rule which can easily capture complex relationship. CNN, LSTM and GRU algorithms works very well to capture sequence information and can predict accurate results as compare to other machine learning and statistical models.</br>

<h3> Model evaluation & Findings </h3>

<p>This is just one part of evaluation results out of all the experiments have been done. These results show different algorithms performance on a stock price dataset. </br>


| Evaluation Metrics | Random Forest | MLP | CNN | LSTM | VAR | GRU |
| :------------ |:---------------:| -----:|-----:|-----:|-----:|-----:|
| R2-Score (%) | 95.94 | 97.85 | 97.13 | 97.72 | -0.28 | 99.60 |
| MAE | 0.009 | 0.009 | 0.005 | 0.004 | 1686 | 0.004 |
| MSE | 0.001 | 0.001 | 0.001 | 0.001 | 3999797 | 0.001 |
| RMSE | 0.033 | 0.023 | 0.027 | 0.024 | 1999 | 0.011 |


<p>Gated recurrent unit model has outperformed other models. The number of samples in train set are more than month and day aggregation groupings, and it was previously discussed that gated recurrent unit was developed as an improvement to LSTM architecture, and here we can see that this objective is fulfilled. The best generalized model for real time hourly stock values prediction is of GRU.</br>

<h3>Outcomes of research</h3>

<p>In this research multiple models were developed by extracting month, day and hour aggregation groupings from the acquired data set of stocks. The acquired data set has records of only five years, therefore, by extracting these aggregate groupings the number of observations were reduced significantly. Although, there is no proper rule for deep learning training data set size, but a general thumb rule says ten thousand, which in our case was not possible. The maximum observations we obtained was for hour aggregate groupings (approximately eight thousand and six hundred). Additionally, the given data set has records of five years which limits the generalization of the developed models. Another limitation in the given data set was that there were a lot of missing records. In stocks data set the first ten months record of 2012 were missing. Similarly, in household data almost 25,000 recorded values were missing, which reduced the training set size. However, the developed models are still able to forecast the output efficiently.</br>

<h3>Conclusion & future Recommendation</h3>
<p>The proposed research claimed that artificial neural-network based models outperform statistical models and the advance ensemble learning models also give significant results. Hence, the disruptive technologies like advance machine learning and neural network will able to predict multivariate time series and visual analytics helps to make effective decision to enhance the business and services for various industries like financial services, retail, e-commerce, smart cities, and health care. Different time aggregations are developed from the acquired data set of stocks and by utilizing these aggregations, models are created. For stock month aggregate CNN was having best results. For stocks day aggregate data set random forest was having best results and for hour aggregate data set gated recurrent unit was having optimum results. For household the results of LSTM were best.</br>

<p>It is recommended for the future to work on hybrid model as in the future data will become more complex therefore combination of any two or three models such as Random Forest and Neural network can give significant result.</br>
