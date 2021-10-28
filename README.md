## RNN-Price-Prediction
Stock price prediction based on stacking ensemble method with LSTM, GRU, Bidirectional LSTM 

## Abstraction
Machine learning technology is developing rapidly, and people apply the technology to various industries. The financial
industry is especially one of the most active machine-learning enabled industries because it does not affect the human right
or require explainability. Thus, many investment companies adopted machine learning technology to estimate future prices
and even replaces human traders’ stock trading work. However, these techniques are not opened to the public as they are
directly connected to their profit, so this paper will present the fundamental machine learning algorithms and techniques that
can predict the future price with reasonable accuracy. Especially for the price prediction, the paper will use three types of
Recurrent Neural Network algorithms: LSTM, GRU, Bidirectional LSTM. The paper will also use a stacking ensemble method
that can improve the stock price prediction value based on the inputs of each algorithm’s output data. Through these RNN
algorithms and ensemble methods, the paper presents an average of 0.016 Root Mean Square Error rate regarding US tech
stocks price prediction.

## Input Data 
- Stock Price : Stock Daily High, Low, Open, Close Price, and Stock Volume
- Commodity : Gold, Oil
- Exchange Rate : EUR, JPY

## RNN Algorithms
- LSTM, BI-LSTM, GRU

## Test
- Test 1 : With different datasets
- Test 2 : With different window sizes
- Test 3 : With different unit sizes, stock only data set
- Test 4 : With different unit sizes, stock and commodity data set
- Test 5 : With different unit sizes, all dataset
- Test 6 : With different combination of the Algorithms
- Test 7 : performance of the price estimation of four IT stocks(Microsoft, Amazon, Google and Facebook) with stock only dataset
## Result 
Performance was measuerd with Root Mean Square Error(RMSE)
### Test 1
![image](https://user-images.githubusercontent.com/56165279/139312954-3450b064-f0ee-4b79-8712-e972e6247227.png)
### Test 2
![image](https://user-images.githubusercontent.com/56165279/139313006-ddb6c25b-dde0-4f60-b63c-1014eca47e75.png)
### Test 3
![image](https://user-images.githubusercontent.com/56165279/139314113-8d3e7b51-6594-42bc-8d3a-45bcd734fa43.png)
### Test 4
![image](https://user-images.githubusercontent.com/56165279/139314158-1853f7ba-9986-4e0e-8a64-4b9978a96424.png)
### Test 5
![image](https://user-images.githubusercontent.com/56165279/139314199-ff8c08c1-5c5c-4f90-93f0-2e13cac82004.png)
### Test 6 
![image](https://user-images.githubusercontent.com/56165279/139314244-d0d6cafc-8a9d-4717-a727-42e186895532.png)
### Test 7
![image](https://user-images.githubusercontent.com/56165279/139314310-c8ea0192-c379-4ceb-a985-e7377f56f842.png)



