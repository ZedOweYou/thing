# Coding Assignment

Python code written in notebook format for demo purposes.

Run all cells to execute code and recieve processed file.

Code includes the following methods:
1. read_csv_files - given a list of file names, reads and stiches multiple csv files into one dataframe (assuming same format)
2. validate - given dataframe of assumed format runs a series of checks, flags all rows with errors
3. aggregate - given validated dataframe, aggregates the data by date and lkid as required
4. patch_sector_tag - given a dictionary {old_name:new_name} patches all sectors tags with updated names
5. calcualte_daily_returns - calcualtes start of day capital for each day and then daily return for each security
6. process - runs all the previous methods together to process file from start to finish, also has alternative mode to process file to show errors
