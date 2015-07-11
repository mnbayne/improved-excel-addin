For who's interested: we created an improved version of the force.com Excel Addin with the following improvements:


  1. Enhanced login-screen: easier switching between environments (less typing)
  1. Validation rules are applied by default (by using newer api version)
  1. Fixed error on duplicate columns (required custom fields were downloaded twice)
  1. Removed default query on 'systemModeDate > last 7 days' if no filter criteria were filled in
  1. Increased standard batch size from 50 to 200, improving upload performance
  1. Removed checks on maximum amount of lines
  1. Improved dates handling (sometimes downloaded dates would not upload back into salesforce again)
  1. (new) enabled uploading empty or "" values to numeric fields (currency, number) instead of 0 only
  1. corrected the bug to cope with error when uploading numbers with many decimals. These were put into scientific notation in Excel but not loaded properly to SF
  1. now enables querying for more than 32766 rows (no limit)


Our users are very happy with it. Feel free to try it out or further build on it and let me know what you think.


Disclaimer: Though we made and tested all enhancements with great care, we take no responsibility for the consequences of the use of this tool.