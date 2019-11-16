# assessment_2_meostat_weather

The endpoint is /weather
and the link is localhost:8081

query parameters are there 
Three query parameters:

1. start : (This is the start date) 2017-01-10,
2. end : (This is the end date) 2017-01-17,
3. info : (this is the operation i.e."MAX" or "MIN" or "AVG") IT IS compulsory and case-sensitive.
Even if you don't pass the query parameter "info" it shows appropriate exception.

even in precipitation field there are NULL values but those are filtered out, and the exception are handled well.
