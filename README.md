# STOCK-ANALYSIS


## INTRODUCTION 

Stock analysis is the evaluation of a particular trading instrument, an investment sector, or the market as a whole. Stock analysts attempt to determine the future activity of an instrument, sector, or market.

---

## FUNDAMENTAL ANALYSIS
Fundamental analysis concentrates on data from sources, including financial records, economic reports, company assets, and market share. To conduct fundamental analysis on a public company or sector, investors and analysts typically analyze the metrics on a company’s financial statements – balance sheet, income statement, cash flow statement, and footnotes.
These statements are released to the public in the form of a 10-Q or 10-K report through the database system, EDGAR, which is administered by the U.S. Securities and Exchange Commission (SEC). Also, the earnings report released by a company during its quarterly earnings press release is analyzed by investors who look to ascertain how much in revenue, expenses, and profits a company made.

---

## About the Model

LSTM stands for Long Short-Term Memory, which is a type of recurrent neural network (RNN) architecture that is designed to handle the vanishing gradient problem in traditional RNNs. The vanishing gradient problem occurs when the gradients of the loss function with respect to the parameters of the model become too small during backpropagation, which can cause the model to converge slowly or not at all.

LSTM networks are composed of memory cells that allow the network to remember information for a long time and gates that control the flow of information into and out of the cells. The three main gates in an LSTM cell are:
1. Forget gate: This gate determines how much of the previous cell state to forget based on the current input and the previous hidden state.

2. Input gate: This gate determines how much of the current input to incorporate into the current cell state.

3. Output gate: This gate determines how much of the current cell state to output as the current hidden state.

---

 LSTM is a type of RNN architecture that uses memory cells and gates to handle the vanishing gradient problem and enable the network to remember information for a long time. It is widely used in applications such as natural language processing, speech recognition, and time series forecasting.

---

## About The Optimizer Used

Adam optimizer is the extended version of stochastic gradient descent which could be implemented in various deep learning applications such as computer vision and natural language processing in the future years.It is an optimization algorithm that can be an alternative for the stochastic gradient descent process. The name is derived from adaptive moment estimation. The optimizer is called Adam because uses estimations of the first and second moments of the gradient to adapt the learning rate for each weight of the neural network. Adam is proposed as the most efficient stochastic optimization which only requires first-order gradients where memory requirement is too little. Before Adam, many adaptive optimization techniques were introduced such as AdaGrad, RMSP which have good performance over SGD but in some cases have some disadvantages such as generalizing performance which is worse than that of the SGD in some cases.

---

## How to setup locally

1. Clone the Repository
```
git clone https://github.com/vanshgupta434/STOCK-ANALYSIS.git
```

2. Install all the necessary libraries that are used in the project.

3. Run Anaconda or Jupyter Notebook or any other tool to run an ipython notebook.

---

LINK TO THE REPORT FILE

https://docs.google.com/document/d/1EdB0uQPLLB1Q5J8TccJXDYjiD5afEaQf/edit?usp=sharing&ouid=110577588602103047514&rtpof=true&sd=true
