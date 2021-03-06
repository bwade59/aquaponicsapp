# swagger_client.DefaultApi

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**conditions_get**](DefaultApi.md#conditions_get) | **GET** /conditions | 


# **conditions_get**
> list[Conditions] conditions_get()



Gets `condition` objects. Optional query param of **size** determines size of returned array 

### Example 
```python
from __future__ import print_function
import time
import swagger_client
from swagger_client.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = swagger_client.DefaultApi()

try: 
    api_response = api_instance.conditions_get()
    pprint(api_response)
except ApiException as e:
    print("Exception when calling DefaultApi->conditions_get: %s\n" % e)
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**list[Conditions]**](Conditions.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

