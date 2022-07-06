# Central-Pivot-Range-Model

## The Excel File consists of Application of Central Pivot Range (CPR) Model for Nifty 50 stocks to identify whether any of the stocks is near any Support or Resistance

- The CPR Model consists of a set of mathematical equations involving the Open-High-Low-Close (OHLC) Prices of the previous day of the Stock to identify important Support & Resistance levels of a Stock. In my model I have calculated Four Support & Resistance levels of each stock of Nifty 50 index. Based on those values, the model monitors the Real-Time value of Stock Prices & if any stock's price comes within a range of [-0.2%, 0%] it flashes the message of Below the respective Support or Resistance level & if it comes within a range of [0%, +0.2%] it flashes the message of Above the respective Support or Resistance level. It continues to keep flashing the signal until the stock moves out of the above ranges. These signals can be seen in the OUTPUT sheet of the Excel workbook. To see the formulas applied one can refer the CALCULATIONS sheet of the Excel workbook. Data is refreshed every minute.

- This model will help intraday traders keep a simultaneous watch on all Nifty 50 stocks at once & eliminate the need of looking at each & every stock's charts to check if the stock is at it's important Support & Resistance levels. Also based on the frequency of signals flashed one can also get an overview of the direction of the broader market.

P.S - This model will run only on Excel 365 or higher versions & requires continuous Internet connectivity whenever the workbook is open.
