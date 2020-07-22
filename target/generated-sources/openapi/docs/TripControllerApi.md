# TripControllerApi

All URIs are relative to *http://localhost:9000*

Method | HTTP request | Description
------------- | ------------- | -------------
[**getTripsUsingGET**](TripControllerApi.md#getTripsUsingGET) | **GET** /api/trips | getTrips



## getTripsUsingGET

> List&lt;Trip&gt; getTripsUsingGET()

getTrips

### Example

```java
// Import classes:
import com.pipecrafts.invoker.ApiClient;
import com.pipecrafts.invoker.ApiException;
import com.pipecrafts.invoker.Configuration;
import com.pipecrafts.invoker.models.*;
import com.pipecrafts.api.TripControllerApi;

public class Example {
    public static void main(String[] args) {
        ApiClient defaultClient = Configuration.getDefaultApiClient();
        defaultClient.setBasePath("http://localhost:9000");

        TripControllerApi apiInstance = new TripControllerApi(defaultClient);
        try {
            List<Trip> result = apiInstance.getTripsUsingGET();
            System.out.println(result);
        } catch (ApiException e) {
            System.err.println("Exception when calling TripControllerApi#getTripsUsingGET");
            System.err.println("Status code: " + e.getCode());
            System.err.println("Reason: " + e.getResponseBody());
            System.err.println("Response headers: " + e.getResponseHeaders());
            e.printStackTrace();
        }
    }
}
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**List&lt;Trip&gt;**](Trip.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | OK |  -  |
| **401** | Unauthorized |  -  |
| **403** | Forbidden |  -  |
| **404** | Not Found |  -  |

