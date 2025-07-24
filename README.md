# DATA_ENGINEER_PROJECT

1. Create a pipeline to fetch the 5 countries (india,us,uk,china,russia) data from Rest API (https://restcountries.com/v3.1/name/{name} here replace the {name} with Country name like https://restcountries.com/v3.1/name/us) and save it in separate file as JSON with File name equal to Country name.
 2. Add the trigger to above pipeline in such a way that it will automatically run two times in a day ( 12:00 AM and 12:00 PM IST) 
3. Create a pipeline to copy customer data from db to adls only if record count is more than 500. Once a data get copy it should call a child pipeline (which will copy the product data from table if customer record count is > 600). 
4. Design the pipeline in such a manner that it will pass the Customer pipeline pass the customer count to the child product pipeline via Pipeline parameter.
