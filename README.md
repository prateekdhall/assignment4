# assignment4
Mulesoft Training-Assignment4

1)	Create a restful web service in mule and consume the same using another mule API.
2)	Create a API in mule which will consume a soap webservice(You can use any publicly available soap web service for this tutorial)
a.	For eg http://webservices.oorsprong.org/websamples.countryinfo/CountryInfoService.wso?WSDL Or you can build your own soap service.
3)	Create a API  in mule , and add exception handling to handle different kinds of exceptions , like HTTP 400 , 401 , 402 , 500 etc , return appropriate http  status code as response with proper exception details.
, also assume your payload contains sensitive information , design a logger which will skip logging the sensitive information.

                For eg.. your Json input payload is 

                                                {
                                                                “Name”  : “Srinivas”,
                                                                “accno”  : “1234567”,
“age”  : “30”,
“ssn”  : “1234567”
                                                                

                                                }

When I log this payload I should not print accno and ssn , or if I print it should be in masked format.
