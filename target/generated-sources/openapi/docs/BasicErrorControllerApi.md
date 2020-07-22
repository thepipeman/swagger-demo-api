# BasicErrorControllerApi

All URIs are relative to *http://localhost:9000*

Method | HTTP request | Description
------------- | ------------- | -------------
[**errorUsingDELETE**](BasicErrorControllerApi.md#errorUsingDELETE) | **DELETE** /api/error | error
[**errorUsingGET**](BasicErrorControllerApi.md#errorUsingGET) | **GET** /api/error | error
[**errorUsingHEAD**](BasicErrorControllerApi.md#errorUsingHEAD) | **HEAD** /api/error | error
[**errorUsingOPTIONS**](BasicErrorControllerApi.md#errorUsingOPTIONS) | **OPTIONS** /api/error | error
[**errorUsingPATCH**](BasicErrorControllerApi.md#errorUsingPATCH) | **PATCH** /api/error | error
[**errorUsingPOST**](BasicErrorControllerApi.md#errorUsingPOST) | **POST** /api/error | error
[**errorUsingPUT**](BasicErrorControllerApi.md#errorUsingPUT) | **PUT** /api/error | error



## errorUsingDELETE

> Map&lt;String, Object&gt; errorUsingDELETE()

error

### Example

```java
// Import classes:
import com.pipecrafts.invoker.ApiClient;
import com.pipecrafts.invoker.ApiException;
import com.pipecrafts.invoker.Configuration;
import com.pipecrafts.invoker.models.*;
import com.pipecrafts.api.BasicErrorControllerApi;

public class Example {
    public static void main(String[] args) {
        ApiClient defaultClient = Configuration.getDefaultApiClient();
        defaultClient.setBasePath("http://localhost:9000");

        BasicErrorControllerApi apiInstance = new BasicErrorControllerApi(defaultClient);
        try {
            Map<String, Object> result = apiInstance.errorUsingDELETE();
            System.out.println(result);
        } catch (ApiException e) {
            System.err.println("Exception when calling BasicErrorControllerApi#errorUsingDELETE");
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

**Map&lt;String, Object&gt;**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | OK |  -  |
| **204** | No Content |  -  |
| **401** | Unauthorized |  -  |
| **403** | Forbidden |  -  |


## errorUsingGET

> Map&lt;String, Object&gt; errorUsingGET()

error

### Example

```java
// Import classes:
import com.pipecrafts.invoker.ApiClient;
import com.pipecrafts.invoker.ApiException;
import com.pipecrafts.invoker.Configuration;
import com.pipecrafts.invoker.models.*;
import com.pipecrafts.api.BasicErrorControllerApi;

public class Example {
    public static void main(String[] args) {
        ApiClient defaultClient = Configuration.getDefaultApiClient();
        defaultClient.setBasePath("http://localhost:9000");

        BasicErrorControllerApi apiInstance = new BasicErrorControllerApi(defaultClient);
        try {
            Map<String, Object> result = apiInstance.errorUsingGET();
            System.out.println(result);
        } catch (ApiException e) {
            System.err.println("Exception when calling BasicErrorControllerApi#errorUsingGET");
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

**Map&lt;String, Object&gt;**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | OK |  -  |
| **401** | Unauthorized |  -  |
| **403** | Forbidden |  -  |
| **404** | Not Found |  -  |


## errorUsingHEAD

> Map&lt;String, Object&gt; errorUsingHEAD()

error

### Example

```java
// Import classes:
import com.pipecrafts.invoker.ApiClient;
import com.pipecrafts.invoker.ApiException;
import com.pipecrafts.invoker.Configuration;
import com.pipecrafts.invoker.models.*;
import com.pipecrafts.api.BasicErrorControllerApi;

public class Example {
    public static void main(String[] args) {
        ApiClient defaultClient = Configuration.getDefaultApiClient();
        defaultClient.setBasePath("http://localhost:9000");

        BasicErrorControllerApi apiInstance = new BasicErrorControllerApi(defaultClient);
        try {
            Map<String, Object> result = apiInstance.errorUsingHEAD();
            System.out.println(result);
        } catch (ApiException e) {
            System.err.println("Exception when calling BasicErrorControllerApi#errorUsingHEAD");
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

**Map&lt;String, Object&gt;**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | OK |  -  |
| **204** | No Content |  -  |
| **401** | Unauthorized |  -  |
| **403** | Forbidden |  -  |


## errorUsingOPTIONS

> Map&lt;String, Object&gt; errorUsingOPTIONS()

error

### Example

```java
// Import classes:
import com.pipecrafts.invoker.ApiClient;
import com.pipecrafts.invoker.ApiException;
import com.pipecrafts.invoker.Configuration;
import com.pipecrafts.invoker.models.*;
import com.pipecrafts.api.BasicErrorControllerApi;

public class Example {
    public static void main(String[] args) {
        ApiClient defaultClient = Configuration.getDefaultApiClient();
        defaultClient.setBasePath("http://localhost:9000");

        BasicErrorControllerApi apiInstance = new BasicErrorControllerApi(defaultClient);
        try {
            Map<String, Object> result = apiInstance.errorUsingOPTIONS();
            System.out.println(result);
        } catch (ApiException e) {
            System.err.println("Exception when calling BasicErrorControllerApi#errorUsingOPTIONS");
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

**Map&lt;String, Object&gt;**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | OK |  -  |
| **204** | No Content |  -  |
| **401** | Unauthorized |  -  |
| **403** | Forbidden |  -  |


## errorUsingPATCH

> Map&lt;String, Object&gt; errorUsingPATCH()

error

### Example

```java
// Import classes:
import com.pipecrafts.invoker.ApiClient;
import com.pipecrafts.invoker.ApiException;
import com.pipecrafts.invoker.Configuration;
import com.pipecrafts.invoker.models.*;
import com.pipecrafts.api.BasicErrorControllerApi;

public class Example {
    public static void main(String[] args) {
        ApiClient defaultClient = Configuration.getDefaultApiClient();
        defaultClient.setBasePath("http://localhost:9000");

        BasicErrorControllerApi apiInstance = new BasicErrorControllerApi(defaultClient);
        try {
            Map<String, Object> result = apiInstance.errorUsingPATCH();
            System.out.println(result);
        } catch (ApiException e) {
            System.err.println("Exception when calling BasicErrorControllerApi#errorUsingPATCH");
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

**Map&lt;String, Object&gt;**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | OK |  -  |
| **204** | No Content |  -  |
| **401** | Unauthorized |  -  |
| **403** | Forbidden |  -  |


## errorUsingPOST

> Map&lt;String, Object&gt; errorUsingPOST()

error

### Example

```java
// Import classes:
import com.pipecrafts.invoker.ApiClient;
import com.pipecrafts.invoker.ApiException;
import com.pipecrafts.invoker.Configuration;
import com.pipecrafts.invoker.models.*;
import com.pipecrafts.api.BasicErrorControllerApi;

public class Example {
    public static void main(String[] args) {
        ApiClient defaultClient = Configuration.getDefaultApiClient();
        defaultClient.setBasePath("http://localhost:9000");

        BasicErrorControllerApi apiInstance = new BasicErrorControllerApi(defaultClient);
        try {
            Map<String, Object> result = apiInstance.errorUsingPOST();
            System.out.println(result);
        } catch (ApiException e) {
            System.err.println("Exception when calling BasicErrorControllerApi#errorUsingPOST");
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

**Map&lt;String, Object&gt;**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | OK |  -  |
| **201** | Created |  -  |
| **401** | Unauthorized |  -  |
| **403** | Forbidden |  -  |
| **404** | Not Found |  -  |


## errorUsingPUT

> Map&lt;String, Object&gt; errorUsingPUT()

error

### Example

```java
// Import classes:
import com.pipecrafts.invoker.ApiClient;
import com.pipecrafts.invoker.ApiException;
import com.pipecrafts.invoker.Configuration;
import com.pipecrafts.invoker.models.*;
import com.pipecrafts.api.BasicErrorControllerApi;

public class Example {
    public static void main(String[] args) {
        ApiClient defaultClient = Configuration.getDefaultApiClient();
        defaultClient.setBasePath("http://localhost:9000");

        BasicErrorControllerApi apiInstance = new BasicErrorControllerApi(defaultClient);
        try {
            Map<String, Object> result = apiInstance.errorUsingPUT();
            System.out.println(result);
        } catch (ApiException e) {
            System.err.println("Exception when calling BasicErrorControllerApi#errorUsingPUT");
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

**Map&lt;String, Object&gt;**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | OK |  -  |
| **201** | Created |  -  |
| **401** | Unauthorized |  -  |
| **403** | Forbidden |  -  |
| **404** | Not Found |  -  |

