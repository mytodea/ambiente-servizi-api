# Swagger\Client\DefaultApi

All URIs are relative to *https://virtserver.swaggerhub.com/Antonis-Polychroniou/Alea/1.0.0*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ecodizionarioLangLangGet**](DefaultApi.md#ecodizionarioLangLangGet) | **GET** /ecodizionario/lang/{lang} | 


# **ecodizionarioLangLangGet**
> \Swagger\Client\Model\InlineResponse200 ecodizionarioLangLangGet($lang)



Returns all municipalities and the associated zones by passing the language parameter

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Swagger\Client\Api\DefaultApi();
$lang = "lang_example"; // string | The language

try {
    $result = $api_instance->ecodizionarioLangLangGet($lang);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->ecodizionarioLangLangGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **lang** | **string**| The language |

### Return type

[**\Swagger\Client\Model\InlineResponse200**](../Model/InlineResponse200.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

