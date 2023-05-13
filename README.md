# pymaceuticals_challange

https://www.geeksforgeeks.org/python-pandas-dataframe-duplicated/

learned how to use code above, also referenced classmates code in slack for below code

duplicate_ids = full_mouse_data.loc[full_mouse_data.duplicated(subset=['Mouse ID', 'Timepoint'], keep='first'),'Mouse ID'].unique()


Learned how to use (.isin) here
https://www.geeksforgeeks.org/ways-to-filter-pandas-dataframe-by-column-values/