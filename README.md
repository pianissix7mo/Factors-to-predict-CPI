### Overview
- The project aims to predict the Consumer Price Index (CPI) using various factors and a neural network model.
- Due to the impact of COVID-19, inflation has significantly increased, making the study of CPI prediction particularly relevant.

### Author: Mofei Wang

### Data and Methods
- **CPI Data**: Monthly data from 1913 to 2020.
- **Population and Real GDP Data**: Yearly data from 1929 to 2020.
- **Gold Price Data**: Monthly data from 1913 to 2020.

### Experiments
1. **Predicting CPI with CPI**: 
   - Implemented a simple Recurrent Neural Network (RNN).
   - Noted high loss potentially due to limited data and external factors influencing CPI.

2. **Predicting CPI with Population and Real GDP**: 
   - Used a neural network with 4 hidden layers.
   - Data limitation due to yearly records.
   - Achieved a minimum validation loss of 0.00015191052807494998.

3. **Predicting CPI with Gold Prices**:
   - Gold prices were used because of their availability and historical significance.
   - Achieved a minimum validation loss of 3.2560117688262835e-05.

4. **Predicting CPI with both CPI and Gold Prices**:
   - Combined CPI and Gold prices for prediction.
   - Achieved the lowest validation loss of 9.2999471235089e-06.

### Conclusion
- Using both CPI and Gold prices as factors yielded the best prediction results.
- Despite data limitations, the project demonstrated the potential of using neural networks for CPI prediction.

### Resources and Configuration
- Utilized the online notebook Deepnote for code execution.
- Data sources included various websites providing historical CPI, population, GDP, and gold prices.

### References
- CPI data from datahub.io, usinflationcalculator.com, and the Minneapolis Fed.
- Population data from the US Census and macrotrends.net.
- GDP data from thebalance.com.
- Gold prices data from datahub.io and indexmundi.com.

If you need more specific details or additional information from the report, please let me know!
