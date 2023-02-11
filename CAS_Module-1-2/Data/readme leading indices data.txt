General File Information

- Download from: https://finance.yahoo.com/ using the following codes in the search bar
	- S&P 500: ^SPX
	- SSE Composite: 000001.SS
	- Nikkei 225: ^N225
	- DAX: ^GDAXI
	- BSE Sensex: ^BSESN
	- FTSE 100: ^FTSE?P=FTSE
	- CAC 40: ^FCHI
	- FTSE MIB: FTSEMIB.MI?P=FTSEMIB.MI
	- IBOVESPA: ^BVSP
	- S&P/TSX Composite: ^GSPTSE
- Date of download and file creation: 2020-10-01
- File format: .CSV
- Rows: Date, Open, High, Low, Close, Adj Close, Volume


Methodological Information

- Each dataset was read into a separate data frame
- data frames were reindexed with a date-time index for the period of 2019-10-01 to 2020-09-30
- NaN were interpolated using the interpolate method of pandas
	- Exception: SSE Composite needs manual setting of "Adj Close" at date "2019-10-01" to 2927.92	 in order for interpolate to work properly (no trading on that day)
- More detailled information regarding methodology can be found in the Jupyter notebooks in the corresponding github repository.
 	



