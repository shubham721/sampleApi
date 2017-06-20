# swagger_client.DefaultApi

All URIs are relative to *https://virtserver.swaggerhub.com/shubham721/sampleworkapi/1.0.0*

Method | HTTP request | Description
------------- | ------------- | -------------
[**controllers_default_controller_write_object_post**](DefaultApi.md#controllers_default_controller_write_object_post) | **POST** /write_object | write object from base path


# **controllers_default_controller_write_object_post**
> controllers_default_controller_write_object_post(instance_object=instance_object)

write object from base path

writes an object from local file to the path  in bucket specified 

### Example 
```python
from __future__ import print_statement
import time
import swagger_client
from swagger_client.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = swagger_client.DefaultApi()
instance_object = swagger_client.InstanceObject() # InstanceObject | launching instance (optional)

try: 
    # write object from base path
    api_instance.controllers_default_controller_write_object_post(instance_object=instance_object)
except ApiException as e:
    print("Exception when calling DefaultApi->controllers_default_controller_write_object_post: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **instance_object** | [**InstanceObject**](InstanceObject.md)| launching instance | [optional] 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

