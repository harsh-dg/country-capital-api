# country-capital-api

### Getting Started

 This is an API written in Python and Flask that returns the name of the country if a capital city is provided
 
### Request URL (Endpoint)
 
[https://example.com/country-capital/capital-city-name](https://example.com/country-capital/capital-city-name)
  
### Required Parameter

 <pre>
 capital-city-name                        Delhi
 *STRING*                                 *REQUIRED*  use this parameter when searching for a country
 </pre>
 
#### Response Body
 
 <pre>
{4 items
  "error":false
  "statusCode":200
  "message":"OK"
  "data":{2 items
            "country":"India"
            "capital":"Delhi"
          }
}
 </pre>
 
 ### Installation and Setup
 
 To install all required files
 
 ``` <b>pip install -r requirements.txt</b> ```

To run Flask application

``` <b>python app.py</b> ```

Visit http://localhost:5000
