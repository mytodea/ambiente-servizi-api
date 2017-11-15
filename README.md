# SwaggerClient-php
Ambiente servizi API

This PHP package is automatically generated by the [Swagger Codegen](https://github.com/swagger-api/swagger-codegen) project:

- API version: 1.0.0
- Build package: class io.swagger.codegen.languages.PhpClientCodegen

## Requirements

PHP 5.4.0 and later

## Installation & Usage
### Composer

To install the bindings via [Composer](http://getcomposer.org/), add the following to `composer.json`:

```
{
  "repositories": [
    {
      "type": "git",
      "url": "https://github.com//.git"
    }
  ],
  "require": {
    "/": "*@dev"
  }
}
```

Then run `composer install`

### Manual Installation

Download the files and include `autoload.php`:

```php
    require_once('/path/to/SwaggerClient-php/autoload.php');
```

## Tests

To run the unit tests:

```
composer install
./vendor/bin/phpunit
```

## Getting Started

Please follow the [installation procedure](#installation--usage) and then run the following:

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

## Documentation for API Endpoints

All URIs are relative to *https://virtserver.swaggerhub.com/Antonis-Polychroniou/Alea/1.0.0*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*DefaultApi* | [**ecodizionarioLangLangGet**](docs/Api/DefaultApi.md#ecodizionariolanglangget) | **GET** /ecodizionario/lang/{lang} | 


## Documentation For Models

 - [InlineResponse200](docs/Model/InlineResponse200.md)
 - [InlineResponse200Areas](docs/Model/InlineResponse200Areas.md)
 - [InlineResponse200Municipalities](docs/Model/InlineResponse200Municipalities.md)


## Documentation For Authorization

 All endpoints do not require authorization.


## Author

mythodea@gmail.com

