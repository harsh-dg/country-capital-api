# country-capital-api

### Getting Started

 This is an API written in Python and Flask that returns the name of the country if a capital city is provided
 
### Request URL (Endpoint)
 
[https://example.com/country-capital/capital-city-name](https://example.com/country-capital/capital-city-name)
  
### Required Parameter

 <pre>
 capital-city-name                        Delhi
 <i>STRING</i>                                   <i>REQUIRED</i>  use this parameter when searching for a country
 </pre>
 
#### Response Body
 
 ```
{4 items
  "error":false
  "statusCode":200
  "message":"OK"
  "data":{2 items
            "country":"India"
            "capital":"Delhi"
          }
}
 ```
 
 ### Installation and Setup
 
 **To install all required files**
 
 ``` pip install -r requirements.txt ```

**To run Flask application**

``` python app.py ```

Visit http://localhost:5000
