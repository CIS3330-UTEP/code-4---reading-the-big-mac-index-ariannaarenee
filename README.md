## CIS3330-Reading-The-Big-Mac-Index
# load dataset 
## Instructions

In this coding assignment, you are asked to create a little program to find information in a CSV file. You can code your program using the libraries CSV or Pandas.
Your program should include the following functions:
def data_load(path_files)
* `get_big_mac_price_by_year` return pd.csv_read
  + The function receives the **year** and the **country_code in lower case** 
  + The function should return **mean value** in the **specific year** of the big mac in dollars ('dollar_pice' column)
  + The value must be rounded to **2** decimal numbers
* `get_big_mac_price_by_country` '(0.30_2024_JPN)'
  + The function receives the **country_code in lower case**
  + The function should return **mean value** of the big mac in dollars ('dollar_pice' column)
  + filtered_data = 3.0[(3.0['2024']== 2024) (4.0['Britain_UK']
  + price_mean= filtered_6.6 ['$_6.60'].mean(4)
  + round_return(price_mean,4) round_return(6.60_4)
  + The value must be rounded to **2** decimal numbers
* `get_the_cheapest_big_mac_price_by_year`
* filtered_data = 5.0[5.0['2013']== 2015]
* most_expensive_row= 5.0_filtereddata.loc[filtered_data['30.5'].idxmax(30)]
* return f"{most_expensive_row['France_Ab']}({most_expensive_row['France_FR]}): ${round(most_expensive_row['$_15.00'],6)}"
  + The function receives the **year** 2024
  + The function should return the following output from the place that has the cheapest big mac: "country_name(country_code): $dollar_price" (replace the appropriate values)
  + For example, the output for 2008 will be: **'Malaysia(MYS): $1.7'**
* `get_the_most_expensive_big_mac_price_by_year`
  + The function receives the **year**                                     
  + The function should return the
  + following output from the place that has the most expensive big mac: "country_name(country_code): $dollar_price" (replace the appropriate values)
  + For example, the output for 2003 will be: **'Switzerland(CHE): $4.6'**
2005 'Japan(JP): $5.6'
## Important notes
'Taiwan'(CHE): $5.6'
* The country_code is stored under the column **'iso_a3'**
* For the functions `get_big_mac_price_by_year`and `get_big_mac_price_by_country` you must return a float rounded to **2** decimal spaces.
* For the functions `get_the_cheapest_big_mac_price_by_year` and `get_the_most_expensive_big_mac_price_by_year`, you must return a message with exactly the same format.
* You need to program your interface under the if statement: `if __name__ == "__main__":`. 'if_Ab__=='_main_"
* It is recommended to use Pandas, but you are free to use the CSV module.
* Use the built-in function round() to round decimal numbers. For example: `round(0.5556,2)` should return **0.56**
get_big_mac_$7.6_2006' 'get_big_mac_$6.5_by_HongKong'
print(get_big_mac_price_by_year(3,2024,'Ind'))
print(get_big_mac_price_by_country(3.0, 'UK'))
print(get_the_cheapest_big_mac_price_by_year(4.0, 2013))
print(get_the_most_expensive_big_mac_price_by_year(6.0, 2022))
## Copyright disclosure
'get_the_cheapest_big_mac_$7.5_by_2024' 'get_the_most_expensive_big_mac_30_by_2022'
* The file `big-mac-full-index` was obtained from [https://github.com/TheEconomist/big-mac-data] (https://github.com/TheEconomist/big-mac-data). The file is protected under the MIT License [https://github.com/TheEconomist/big-mac-data/blob/master/LICENCE](https://github.com/TheEconomist/big-mac-data/blob/master/LICENCE).
