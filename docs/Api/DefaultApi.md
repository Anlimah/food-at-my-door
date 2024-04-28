# OpenAPI\Client\DefaultApi

All URIs are relative to https://api.lafcomputerlabs.com:8443/v1, except if the operation defines another base path.

| Method | HTTP request | Description |
| ------------- | ------------- | ------------- |
| [**categoriesCategoryIdDelete()**](DefaultApi.md#categoriesCategoryIdDelete) | **DELETE** /categories/{categoryId} | Delete a category |
| [**categoriesCategoryIdGet()**](DefaultApi.md#categoriesCategoryIdGet) | **GET** /categories/{categoryId} | Get a category by ID |
| [**categoriesCategoryIdPut()**](DefaultApi.md#categoriesCategoryIdPut) | **PUT** /categories/{categoryId} | Update a category |
| [**categoriesGet()**](DefaultApi.md#categoriesGet) | **GET** /categories | Get all categories |
| [**categoriesPost()**](DefaultApi.md#categoriesPost) | **POST** /categories | Create a new category |
| [**customersCustomerIdDelete()**](DefaultApi.md#customersCustomerIdDelete) | **DELETE** /customers/{customerId} | Delete a customer |
| [**customersCustomerIdGet()**](DefaultApi.md#customersCustomerIdGet) | **GET** /customers/{customerId} | Get a customer by ID |
| [**customersCustomerIdPut()**](DefaultApi.md#customersCustomerIdPut) | **PUT** /customers/{customerId} | Update a customer |
| [**customersGet()**](DefaultApi.md#customersGet) | **GET** /customers | Get all customers |
| [**customersPost()**](DefaultApi.md#customersPost) | **POST** /customers | Create a new customer |
| [**discountsDiscountIdDelete()**](DefaultApi.md#discountsDiscountIdDelete) | **DELETE** /discounts/{discountId} | Delete a discount |
| [**discountsDiscountIdGet()**](DefaultApi.md#discountsDiscountIdGet) | **GET** /discounts/{discountId} | Get a discount by ID |
| [**discountsDiscountIdPut()**](DefaultApi.md#discountsDiscountIdPut) | **PUT** /discounts/{discountId} | Update a discount |
| [**discountsGet()**](DefaultApi.md#discountsGet) | **GET** /discounts | Get all discounts |
| [**discountsPost()**](DefaultApi.md#discountsPost) | **POST** /discounts | Create a new discount |
| [**ingredientsGet()**](DefaultApi.md#ingredientsGet) | **GET** /ingredients | Get all ingredients |
| [**ingredientsIngredientIdDelete()**](DefaultApi.md#ingredientsIngredientIdDelete) | **DELETE** /ingredients/{ingredientId} | Delete an ingredient |
| [**ingredientsIngredientIdGet()**](DefaultApi.md#ingredientsIngredientIdGet) | **GET** /ingredients/{ingredientId} | Get an ingredient by ID |
| [**ingredientsIngredientIdPut()**](DefaultApi.md#ingredientsIngredientIdPut) | **PUT** /ingredients/{ingredientId} | Update an ingredient |
| [**ingredientsPost()**](DefaultApi.md#ingredientsPost) | **POST** /ingredients | Create a new ingredient |
| [**menuItemCategoriesCategoryIdDelete()**](DefaultApi.md#menuItemCategoriesCategoryIdDelete) | **DELETE** /menu-item-categories/{categoryId} | Delete a menu item category |
| [**menuItemCategoriesCategoryIdGet()**](DefaultApi.md#menuItemCategoriesCategoryIdGet) | **GET** /menu-item-categories/{categoryId} | Get a menu item category by ID |
| [**menuItemCategoriesCategoryIdPut()**](DefaultApi.md#menuItemCategoriesCategoryIdPut) | **PUT** /menu-item-categories/{categoryId} | Update a menu item category |
| [**menuItemCategoriesGet()**](DefaultApi.md#menuItemCategoriesGet) | **GET** /menu-item-categories | Get all menu item categories |
| [**menuItemCategoriesPost()**](DefaultApi.md#menuItemCategoriesPost) | **POST** /menu-item-categories | Create a new menu item category |
| [**menuItemOptionsGet()**](DefaultApi.md#menuItemOptionsGet) | **GET** /menu-item-options | Get all menu item options |
| [**menuItemOptionsOptionIdDelete()**](DefaultApi.md#menuItemOptionsOptionIdDelete) | **DELETE** /menu-item-options/{optionId} | Delete a menu item option |
| [**menuItemOptionsOptionIdGet()**](DefaultApi.md#menuItemOptionsOptionIdGet) | **GET** /menu-item-options/{optionId} | Get a menu item option by ID |
| [**menuItemOptionsOptionIdPut()**](DefaultApi.md#menuItemOptionsOptionIdPut) | **PUT** /menu-item-options/{optionId} | Update a menu item option |
| [**menuItemOptionsPost()**](DefaultApi.md#menuItemOptionsPost) | **POST** /menu-item-options | Create a new menu item option |
| [**menuItemsGet()**](DefaultApi.md#menuItemsGet) | **GET** /menu-items | Get all menu items |
| [**menuItemsItemIdDelete()**](DefaultApi.md#menuItemsItemIdDelete) | **DELETE** /menu-items/{itemId} | Delete a menu item |
| [**menuItemsItemIdGet()**](DefaultApi.md#menuItemsItemIdGet) | **GET** /menu-items/{itemId} | Get a menu item by ID |
| [**menuItemsItemIdPut()**](DefaultApi.md#menuItemsItemIdPut) | **PUT** /menu-items/{itemId} | Update a menu item |
| [**menuItemsPost()**](DefaultApi.md#menuItemsPost) | **POST** /menu-items | Create a new menu item |
| [**orderItemsGet()**](DefaultApi.md#orderItemsGet) | **GET** /order-items | Get all order items |
| [**orderItemsItemIdDelete()**](DefaultApi.md#orderItemsItemIdDelete) | **DELETE** /order-items/{itemId} | Delete an order item |
| [**orderItemsItemIdGet()**](DefaultApi.md#orderItemsItemIdGet) | **GET** /order-items/{itemId} | Get an order item by ID |
| [**orderItemsItemIdPut()**](DefaultApi.md#orderItemsItemIdPut) | **PUT** /order-items/{itemId} | Update an order item |
| [**orderItemsPost()**](DefaultApi.md#orderItemsPost) | **POST** /order-items | Create a new order item |
| [**ordersGet()**](DefaultApi.md#ordersGet) | **GET** /orders | Get all orders |
| [**ordersOrderIdDelete()**](DefaultApi.md#ordersOrderIdDelete) | **DELETE** /orders/{orderId} | Delete an order |
| [**ordersOrderIdGet()**](DefaultApi.md#ordersOrderIdGet) | **GET** /orders/{orderId} | Get an order by ID |
| [**ordersOrderIdPut()**](DefaultApi.md#ordersOrderIdPut) | **PUT** /orders/{orderId} | Update an order |
| [**ordersPost()**](DefaultApi.md#ordersPost) | **POST** /orders | Create a new order |
| [**reportsComponentItemGet()**](DefaultApi.md#reportsComponentItemGet) | **GET** /reports/{component}/{item} | Generate a report for a specific component and item |
| [**reportsCustomersAverageOrderFrequencyGet()**](DefaultApi.md#reportsCustomersAverageOrderFrequencyGet) | **GET** /reports/customers/average-order-frequency | Generate a report of average order frequency per customer |
| [**reportsCustomersRetentionGet()**](DefaultApi.md#reportsCustomersRetentionGet) | **GET** /reports/customers/retention | Generate a report of customer retention rate |
| [**reportsCustomersTotalGet()**](DefaultApi.md#reportsCustomersTotalGet) | **GET** /reports/customers/total | Generate a report of total number of customers registered on the platform |
| [**reportsDiscountsEffectivenessGet()**](DefaultApi.md#reportsDiscountsEffectivenessGet) | **GET** /reports/discounts/effectiveness | Generate a report of effectiveness of discounts in increasing order volume or customer retention |
| [**reportsDiscountsRevenueImpactGet()**](DefaultApi.md#reportsDiscountsRevenueImpactGet) | **GET** /reports/discounts/revenue-impact | Generate a report of revenue impact of discounts |
| [**reportsDiscountsUsageGet()**](DefaultApi.md#reportsDiscountsUsageGet) | **GET** /reports/discounts/usage | Generate a report of usage statistics for each discount code |
| [**reportsGet()**](DefaultApi.md#reportsGet) | **GET** /reports | Get all reports |
| [**reportsMenusPopularityGet()**](DefaultApi.md#reportsMenusPopularityGet) | **GET** /reports/menus/popularity | Generate a report of most popular dishes at each restaurant |
| [**reportsOrdersAverageValueGet()**](DefaultApi.md#reportsOrdersAverageValueGet) | **GET** /reports/orders/average-value | Generate a report of average order value within a specific time period |
| [**reportsOrdersFulfillmentTimeGet()**](DefaultApi.md#reportsOrdersFulfillmentTimeGet) | **GET** /reports/orders/fulfillment-time | Generate a report of order fulfillment time statistics |
| [**reportsOrdersTotalGet()**](DefaultApi.md#reportsOrdersTotalGet) | **GET** /reports/orders/total | Generate a report of total number of orders placed within a specific time period |
| [**reportsPost()**](DefaultApi.md#reportsPost) | **POST** /reports | Create a new report |
| [**reportsReportIdDelete()**](DefaultApi.md#reportsReportIdDelete) | **DELETE** /reports/{reportId} | Delete a report |
| [**reportsReportIdGet()**](DefaultApi.md#reportsReportIdGet) | **GET** /reports/{reportId} | Get a report by ID |
| [**reportsReportIdPut()**](DefaultApi.md#reportsReportIdPut) | **PUT** /reports/{reportId} | Update a report |
| [**reportsRestaurantsOrdersGet()**](DefaultApi.md#reportsRestaurantsOrdersGet) | **GET** /reports/restaurants/orders | Generate a report of total orders received by each restaurant |
| [**reportsRestaurantsRatingsGet()**](DefaultApi.md#reportsRestaurantsRatingsGet) | **GET** /reports/restaurants/ratings | Generate a report of average ratings of each restaurant |
| [**reportsRestaurantsRevenueGet()**](DefaultApi.md#reportsRestaurantsRevenueGet) | **GET** /reports/restaurants/revenue | Generate a report of revenue generated by each restaurant |
| [**restaurantsGet()**](DefaultApi.md#restaurantsGet) | **GET** /restaurants | Get all restaurants |
| [**restaurantsPost()**](DefaultApi.md#restaurantsPost) | **POST** /restaurants | Create a new restaurant |
| [**restaurantsRestaurantIdDelete()**](DefaultApi.md#restaurantsRestaurantIdDelete) | **DELETE** /restaurants/{restaurantId} | Delete a restaurant |
| [**restaurantsRestaurantIdGet()**](DefaultApi.md#restaurantsRestaurantIdGet) | **GET** /restaurants/{restaurantId} | Get a restaurant by ID |
| [**restaurantsRestaurantIdMenusGet()**](DefaultApi.md#restaurantsRestaurantIdMenusGet) | **GET** /restaurants/{restaurantId}/menus | Get all menu items for a restaurant |
| [**restaurantsRestaurantIdMenusMenuIdDelete()**](DefaultApi.md#restaurantsRestaurantIdMenusMenuIdDelete) | **DELETE** /restaurants/{restaurantId}/menus/{menuId} | Delete a menu item |
| [**restaurantsRestaurantIdMenusMenuIdGet()**](DefaultApi.md#restaurantsRestaurantIdMenusMenuIdGet) | **GET** /restaurants/{restaurantId}/menus/{menuId} | Get a menu item by ID |
| [**restaurantsRestaurantIdMenusMenuIdPut()**](DefaultApi.md#restaurantsRestaurantIdMenusMenuIdPut) | **PUT** /restaurants/{restaurantId}/menus/{menuId} | Update a menu item |
| [**restaurantsRestaurantIdMenusPost()**](DefaultApi.md#restaurantsRestaurantIdMenusPost) | **POST** /restaurants/{restaurantId}/menus | Create a new menu item |
| [**restaurantsRestaurantIdPut()**](DefaultApi.md#restaurantsRestaurantIdPut) | **PUT** /restaurants/{restaurantId} | Update a restaurant |


## `categoriesCategoryIdDelete()`

```php
categoriesCategoryIdDelete($category_id)
```

Delete a category

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$category_id = 'category_id_example'; // string

try {
    $apiInstance->categoriesCategoryIdDelete($category_id);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->categoriesCategoryIdDelete: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **category_id** | **string**|  | |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `categoriesCategoryIdGet()`

```php
categoriesCategoryIdGet($category_id): \OpenAPI\Client\Model\Category
```

Get a category by ID

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$category_id = 'category_id_example'; // string

try {
    $result = $apiInstance->categoriesCategoryIdGet($category_id);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->categoriesCategoryIdGet: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **category_id** | **string**|  | |

### Return type

[**\OpenAPI\Client\Model\Category**](../Model/Category.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `categoriesCategoryIdPut()`

```php
categoriesCategoryIdPut($category_id, $update_category)
```

Update a category

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$category_id = 'category_id_example'; // string
$update_category = new \OpenAPI\Client\Model\UpdateCategory(); // \OpenAPI\Client\Model\UpdateCategory

try {
    $apiInstance->categoriesCategoryIdPut($category_id, $update_category);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->categoriesCategoryIdPut: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **category_id** | **string**|  | |
| **update_category** | [**\OpenAPI\Client\Model\UpdateCategory**](../Model/UpdateCategory.md)|  | |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `categoriesGet()`

```php
categoriesGet(): \OpenAPI\Client\Model\Category[]
```

Get all categories

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $result = $apiInstance->categoriesGet();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->categoriesGet: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**\OpenAPI\Client\Model\Category[]**](../Model/Category.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `categoriesPost()`

```php
categoriesPost($new_category)
```

Create a new category

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$new_category = new \OpenAPI\Client\Model\NewCategory(); // \OpenAPI\Client\Model\NewCategory

try {
    $apiInstance->categoriesPost($new_category);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->categoriesPost: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **new_category** | [**\OpenAPI\Client\Model\NewCategory**](../Model/NewCategory.md)|  | |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `customersCustomerIdDelete()`

```php
customersCustomerIdDelete($customer_id)
```

Delete a customer

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$customer_id = 'customer_id_example'; // string

try {
    $apiInstance->customersCustomerIdDelete($customer_id);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->customersCustomerIdDelete: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **customer_id** | **string**|  | |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `customersCustomerIdGet()`

```php
customersCustomerIdGet($customer_id): \OpenAPI\Client\Model\Customer
```

Get a customer by ID

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$customer_id = 'customer_id_example'; // string

try {
    $result = $apiInstance->customersCustomerIdGet($customer_id);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->customersCustomerIdGet: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **customer_id** | **string**|  | |

### Return type

[**\OpenAPI\Client\Model\Customer**](../Model/Customer.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `customersCustomerIdPut()`

```php
customersCustomerIdPut($customer_id, $update_customer)
```

Update a customer

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$customer_id = 'customer_id_example'; // string
$update_customer = new \OpenAPI\Client\Model\UpdateCustomer(); // \OpenAPI\Client\Model\UpdateCustomer

try {
    $apiInstance->customersCustomerIdPut($customer_id, $update_customer);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->customersCustomerIdPut: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **customer_id** | **string**|  | |
| **update_customer** | [**\OpenAPI\Client\Model\UpdateCustomer**](../Model/UpdateCustomer.md)|  | |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `customersGet()`

```php
customersGet(): \OpenAPI\Client\Model\Customer[]
```

Get all customers

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $result = $apiInstance->customersGet();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->customersGet: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**\OpenAPI\Client\Model\Customer[]**](../Model/Customer.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `customersPost()`

```php
customersPost($new_customer)
```

Create a new customer

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$new_customer = new \OpenAPI\Client\Model\NewCustomer(); // \OpenAPI\Client\Model\NewCustomer

try {
    $apiInstance->customersPost($new_customer);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->customersPost: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **new_customer** | [**\OpenAPI\Client\Model\NewCustomer**](../Model/NewCustomer.md)|  | |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `discountsDiscountIdDelete()`

```php
discountsDiscountIdDelete($discount_id)
```

Delete a discount

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$discount_id = 'discount_id_example'; // string

try {
    $apiInstance->discountsDiscountIdDelete($discount_id);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->discountsDiscountIdDelete: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **discount_id** | **string**|  | |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `discountsDiscountIdGet()`

```php
discountsDiscountIdGet($discount_id): \OpenAPI\Client\Model\Discount
```

Get a discount by ID

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$discount_id = 'discount_id_example'; // string

try {
    $result = $apiInstance->discountsDiscountIdGet($discount_id);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->discountsDiscountIdGet: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **discount_id** | **string**|  | |

### Return type

[**\OpenAPI\Client\Model\Discount**](../Model/Discount.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `discountsDiscountIdPut()`

```php
discountsDiscountIdPut($discount_id, $update_discount)
```

Update a discount

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$discount_id = 'discount_id_example'; // string
$update_discount = new \OpenAPI\Client\Model\UpdateDiscount(); // \OpenAPI\Client\Model\UpdateDiscount

try {
    $apiInstance->discountsDiscountIdPut($discount_id, $update_discount);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->discountsDiscountIdPut: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **discount_id** | **string**|  | |
| **update_discount** | [**\OpenAPI\Client\Model\UpdateDiscount**](../Model/UpdateDiscount.md)|  | |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `discountsGet()`

```php
discountsGet(): \OpenAPI\Client\Model\Discount[]
```

Get all discounts

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $result = $apiInstance->discountsGet();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->discountsGet: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**\OpenAPI\Client\Model\Discount[]**](../Model/Discount.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `discountsPost()`

```php
discountsPost($new_discount)
```

Create a new discount

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$new_discount = new \OpenAPI\Client\Model\NewDiscount(); // \OpenAPI\Client\Model\NewDiscount

try {
    $apiInstance->discountsPost($new_discount);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->discountsPost: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **new_discount** | [**\OpenAPI\Client\Model\NewDiscount**](../Model/NewDiscount.md)|  | |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `ingredientsGet()`

```php
ingredientsGet(): \OpenAPI\Client\Model\Ingredient[]
```

Get all ingredients

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $result = $apiInstance->ingredientsGet();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->ingredientsGet: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**\OpenAPI\Client\Model\Ingredient[]**](../Model/Ingredient.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `ingredientsIngredientIdDelete()`

```php
ingredientsIngredientIdDelete($ingredient_id)
```

Delete an ingredient

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$ingredient_id = 'ingredient_id_example'; // string

try {
    $apiInstance->ingredientsIngredientIdDelete($ingredient_id);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->ingredientsIngredientIdDelete: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **ingredient_id** | **string**|  | |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `ingredientsIngredientIdGet()`

```php
ingredientsIngredientIdGet($ingredient_id): \OpenAPI\Client\Model\Ingredient
```

Get an ingredient by ID

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$ingredient_id = 'ingredient_id_example'; // string

try {
    $result = $apiInstance->ingredientsIngredientIdGet($ingredient_id);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->ingredientsIngredientIdGet: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **ingredient_id** | **string**|  | |

### Return type

[**\OpenAPI\Client\Model\Ingredient**](../Model/Ingredient.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `ingredientsIngredientIdPut()`

```php
ingredientsIngredientIdPut($ingredient_id, $update_ingredient)
```

Update an ingredient

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$ingredient_id = 'ingredient_id_example'; // string
$update_ingredient = new \OpenAPI\Client\Model\UpdateIngredient(); // \OpenAPI\Client\Model\UpdateIngredient

try {
    $apiInstance->ingredientsIngredientIdPut($ingredient_id, $update_ingredient);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->ingredientsIngredientIdPut: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **ingredient_id** | **string**|  | |
| **update_ingredient** | [**\OpenAPI\Client\Model\UpdateIngredient**](../Model/UpdateIngredient.md)|  | |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `ingredientsPost()`

```php
ingredientsPost($new_ingredient)
```

Create a new ingredient

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$new_ingredient = new \OpenAPI\Client\Model\NewIngredient(); // \OpenAPI\Client\Model\NewIngredient

try {
    $apiInstance->ingredientsPost($new_ingredient);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->ingredientsPost: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **new_ingredient** | [**\OpenAPI\Client\Model\NewIngredient**](../Model/NewIngredient.md)|  | |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `menuItemCategoriesCategoryIdDelete()`

```php
menuItemCategoriesCategoryIdDelete($category_id)
```

Delete a menu item category

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$category_id = 'category_id_example'; // string

try {
    $apiInstance->menuItemCategoriesCategoryIdDelete($category_id);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->menuItemCategoriesCategoryIdDelete: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **category_id** | **string**|  | |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `menuItemCategoriesCategoryIdGet()`

```php
menuItemCategoriesCategoryIdGet($category_id): \OpenAPI\Client\Model\MenuItemCategory
```

Get a menu item category by ID

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$category_id = 'category_id_example'; // string

try {
    $result = $apiInstance->menuItemCategoriesCategoryIdGet($category_id);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->menuItemCategoriesCategoryIdGet: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **category_id** | **string**|  | |

### Return type

[**\OpenAPI\Client\Model\MenuItemCategory**](../Model/MenuItemCategory.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `menuItemCategoriesCategoryIdPut()`

```php
menuItemCategoriesCategoryIdPut($category_id, $update_menu_item_category)
```

Update a menu item category

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$category_id = 'category_id_example'; // string
$update_menu_item_category = new \OpenAPI\Client\Model\UpdateMenuItemCategory(); // \OpenAPI\Client\Model\UpdateMenuItemCategory

try {
    $apiInstance->menuItemCategoriesCategoryIdPut($category_id, $update_menu_item_category);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->menuItemCategoriesCategoryIdPut: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **category_id** | **string**|  | |
| **update_menu_item_category** | [**\OpenAPI\Client\Model\UpdateMenuItemCategory**](../Model/UpdateMenuItemCategory.md)|  | |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `menuItemCategoriesGet()`

```php
menuItemCategoriesGet(): \OpenAPI\Client\Model\MenuItemCategory[]
```

Get all menu item categories

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $result = $apiInstance->menuItemCategoriesGet();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->menuItemCategoriesGet: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**\OpenAPI\Client\Model\MenuItemCategory[]**](../Model/MenuItemCategory.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `menuItemCategoriesPost()`

```php
menuItemCategoriesPost($new_menu_item_category)
```

Create a new menu item category

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$new_menu_item_category = new \OpenAPI\Client\Model\NewMenuItemCategory(); // \OpenAPI\Client\Model\NewMenuItemCategory

try {
    $apiInstance->menuItemCategoriesPost($new_menu_item_category);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->menuItemCategoriesPost: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **new_menu_item_category** | [**\OpenAPI\Client\Model\NewMenuItemCategory**](../Model/NewMenuItemCategory.md)|  | |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `menuItemOptionsGet()`

```php
menuItemOptionsGet(): \OpenAPI\Client\Model\MenuItemOption[]
```

Get all menu item options

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $result = $apiInstance->menuItemOptionsGet();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->menuItemOptionsGet: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**\OpenAPI\Client\Model\MenuItemOption[]**](../Model/MenuItemOption.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `menuItemOptionsOptionIdDelete()`

```php
menuItemOptionsOptionIdDelete($option_id)
```

Delete a menu item option

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$option_id = 'option_id_example'; // string

try {
    $apiInstance->menuItemOptionsOptionIdDelete($option_id);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->menuItemOptionsOptionIdDelete: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **option_id** | **string**|  | |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `menuItemOptionsOptionIdGet()`

```php
menuItemOptionsOptionIdGet($option_id): \OpenAPI\Client\Model\MenuItemOption
```

Get a menu item option by ID

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$option_id = 'option_id_example'; // string

try {
    $result = $apiInstance->menuItemOptionsOptionIdGet($option_id);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->menuItemOptionsOptionIdGet: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **option_id** | **string**|  | |

### Return type

[**\OpenAPI\Client\Model\MenuItemOption**](../Model/MenuItemOption.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `menuItemOptionsOptionIdPut()`

```php
menuItemOptionsOptionIdPut($option_id, $update_menu_item_option)
```

Update a menu item option

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$option_id = 'option_id_example'; // string
$update_menu_item_option = new \OpenAPI\Client\Model\UpdateMenuItemOption(); // \OpenAPI\Client\Model\UpdateMenuItemOption

try {
    $apiInstance->menuItemOptionsOptionIdPut($option_id, $update_menu_item_option);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->menuItemOptionsOptionIdPut: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **option_id** | **string**|  | |
| **update_menu_item_option** | [**\OpenAPI\Client\Model\UpdateMenuItemOption**](../Model/UpdateMenuItemOption.md)|  | |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `menuItemOptionsPost()`

```php
menuItemOptionsPost($new_menu_item_option)
```

Create a new menu item option

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$new_menu_item_option = new \OpenAPI\Client\Model\NewMenuItemOption(); // \OpenAPI\Client\Model\NewMenuItemOption

try {
    $apiInstance->menuItemOptionsPost($new_menu_item_option);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->menuItemOptionsPost: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **new_menu_item_option** | [**\OpenAPI\Client\Model\NewMenuItemOption**](../Model/NewMenuItemOption.md)|  | |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `menuItemsGet()`

```php
menuItemsGet(): \OpenAPI\Client\Model\MenuItem[]
```

Get all menu items

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $result = $apiInstance->menuItemsGet();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->menuItemsGet: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**\OpenAPI\Client\Model\MenuItem[]**](../Model/MenuItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `menuItemsItemIdDelete()`

```php
menuItemsItemIdDelete($item_id)
```

Delete a menu item

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$item_id = 'item_id_example'; // string

try {
    $apiInstance->menuItemsItemIdDelete($item_id);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->menuItemsItemIdDelete: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **item_id** | **string**|  | |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `menuItemsItemIdGet()`

```php
menuItemsItemIdGet($item_id): \OpenAPI\Client\Model\MenuItem
```

Get a menu item by ID

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$item_id = 'item_id_example'; // string

try {
    $result = $apiInstance->menuItemsItemIdGet($item_id);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->menuItemsItemIdGet: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **item_id** | **string**|  | |

### Return type

[**\OpenAPI\Client\Model\MenuItem**](../Model/MenuItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `menuItemsItemIdPut()`

```php
menuItemsItemIdPut($item_id, $update_menu_item)
```

Update a menu item

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$item_id = 'item_id_example'; // string
$update_menu_item = new \OpenAPI\Client\Model\UpdateMenuItem(); // \OpenAPI\Client\Model\UpdateMenuItem

try {
    $apiInstance->menuItemsItemIdPut($item_id, $update_menu_item);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->menuItemsItemIdPut: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **item_id** | **string**|  | |
| **update_menu_item** | [**\OpenAPI\Client\Model\UpdateMenuItem**](../Model/UpdateMenuItem.md)|  | |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `menuItemsPost()`

```php
menuItemsPost($new_menu_item)
```

Create a new menu item

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$new_menu_item = new \OpenAPI\Client\Model\NewMenuItem(); // \OpenAPI\Client\Model\NewMenuItem

try {
    $apiInstance->menuItemsPost($new_menu_item);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->menuItemsPost: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **new_menu_item** | [**\OpenAPI\Client\Model\NewMenuItem**](../Model/NewMenuItem.md)|  | |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `orderItemsGet()`

```php
orderItemsGet(): \OpenAPI\Client\Model\OrderItem[]
```

Get all order items

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $result = $apiInstance->orderItemsGet();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->orderItemsGet: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**\OpenAPI\Client\Model\OrderItem[]**](../Model/OrderItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `orderItemsItemIdDelete()`

```php
orderItemsItemIdDelete($item_id)
```

Delete an order item

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$item_id = 'item_id_example'; // string

try {
    $apiInstance->orderItemsItemIdDelete($item_id);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->orderItemsItemIdDelete: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **item_id** | **string**|  | |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `orderItemsItemIdGet()`

```php
orderItemsItemIdGet($item_id): \OpenAPI\Client\Model\OrderItem
```

Get an order item by ID

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$item_id = 'item_id_example'; // string

try {
    $result = $apiInstance->orderItemsItemIdGet($item_id);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->orderItemsItemIdGet: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **item_id** | **string**|  | |

### Return type

[**\OpenAPI\Client\Model\OrderItem**](../Model/OrderItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `orderItemsItemIdPut()`

```php
orderItemsItemIdPut($item_id, $update_order_item)
```

Update an order item

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$item_id = 'item_id_example'; // string
$update_order_item = new \OpenAPI\Client\Model\UpdateOrderItem(); // \OpenAPI\Client\Model\UpdateOrderItem

try {
    $apiInstance->orderItemsItemIdPut($item_id, $update_order_item);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->orderItemsItemIdPut: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **item_id** | **string**|  | |
| **update_order_item** | [**\OpenAPI\Client\Model\UpdateOrderItem**](../Model/UpdateOrderItem.md)|  | |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `orderItemsPost()`

```php
orderItemsPost($new_order_item)
```

Create a new order item

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$new_order_item = new \OpenAPI\Client\Model\NewOrderItem(); // \OpenAPI\Client\Model\NewOrderItem

try {
    $apiInstance->orderItemsPost($new_order_item);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->orderItemsPost: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **new_order_item** | [**\OpenAPI\Client\Model\NewOrderItem**](../Model/NewOrderItem.md)|  | |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `ordersGet()`

```php
ordersGet(): \OpenAPI\Client\Model\Order[]
```

Get all orders

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $result = $apiInstance->ordersGet();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->ordersGet: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**\OpenAPI\Client\Model\Order[]**](../Model/Order.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `ordersOrderIdDelete()`

```php
ordersOrderIdDelete($order_id)
```

Delete an order

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$order_id = 'order_id_example'; // string

try {
    $apiInstance->ordersOrderIdDelete($order_id);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->ordersOrderIdDelete: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **order_id** | **string**|  | |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `ordersOrderIdGet()`

```php
ordersOrderIdGet($order_id): \OpenAPI\Client\Model\Order
```

Get an order by ID

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$order_id = 'order_id_example'; // string

try {
    $result = $apiInstance->ordersOrderIdGet($order_id);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->ordersOrderIdGet: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **order_id** | **string**|  | |

### Return type

[**\OpenAPI\Client\Model\Order**](../Model/Order.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `ordersOrderIdPut()`

```php
ordersOrderIdPut($order_id, $update_order)
```

Update an order

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$order_id = 'order_id_example'; // string
$update_order = new \OpenAPI\Client\Model\UpdateOrder(); // \OpenAPI\Client\Model\UpdateOrder

try {
    $apiInstance->ordersOrderIdPut($order_id, $update_order);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->ordersOrderIdPut: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **order_id** | **string**|  | |
| **update_order** | [**\OpenAPI\Client\Model\UpdateOrder**](../Model/UpdateOrder.md)|  | |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `ordersPost()`

```php
ordersPost($new_order)
```

Create a new order

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$new_order = new \OpenAPI\Client\Model\NewOrder(); // \OpenAPI\Client\Model\NewOrder

try {
    $apiInstance->ordersPost($new_order);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->ordersPost: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **new_order** | [**\OpenAPI\Client\Model\NewOrder**](../Model/NewOrder.md)|  | |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `reportsComponentItemGet()`

```php
reportsComponentItemGet($component, $item, $start_date, $end_date, $limit)
```

Generate a report for a specific component and item

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$component = 'component_example'; // string | The component for which the report is being generated (e.g., 'restaurants', 'menus', 'orders')
$item = 'item_example'; // string | The specific item within the component for which the report is being generated (e.g., 'revenue', 'ratings', 'total')
$start_date = new \DateTime("2013-10-20T19:20:30+01:00"); // \DateTime | Start date for the report (format: 'YYYY-MM-DD')
$end_date = new \DateTime("2013-10-20T19:20:30+01:00"); // \DateTime | End date for the report (format: 'YYYY-MM-DD')
$limit = 100; // int | Limit the number of results (default: 100)

try {
    $apiInstance->reportsComponentItemGet($component, $item, $start_date, $end_date, $limit);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->reportsComponentItemGet: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **component** | **string**| The component for which the report is being generated (e.g., &#39;restaurants&#39;, &#39;menus&#39;, &#39;orders&#39;) | |
| **item** | **string**| The specific item within the component for which the report is being generated (e.g., &#39;revenue&#39;, &#39;ratings&#39;, &#39;total&#39;) | |
| **start_date** | **\DateTime**| Start date for the report (format: &#39;YYYY-MM-DD&#39;) | [optional] |
| **end_date** | **\DateTime**| End date for the report (format: &#39;YYYY-MM-DD&#39;) | [optional] |
| **limit** | **int**| Limit the number of results (default: 100) | [optional] [default to 100] |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `reportsCustomersAverageOrderFrequencyGet()`

```php
reportsCustomersAverageOrderFrequencyGet()
```

Generate a report of average order frequency per customer

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->reportsCustomersAverageOrderFrequencyGet();
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->reportsCustomersAverageOrderFrequencyGet: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

This endpoint does not need any parameter.

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `reportsCustomersRetentionGet()`

```php
reportsCustomersRetentionGet()
```

Generate a report of customer retention rate

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->reportsCustomersRetentionGet();
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->reportsCustomersRetentionGet: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

This endpoint does not need any parameter.

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `reportsCustomersTotalGet()`

```php
reportsCustomersTotalGet()
```

Generate a report of total number of customers registered on the platform

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->reportsCustomersTotalGet();
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->reportsCustomersTotalGet: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

This endpoint does not need any parameter.

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `reportsDiscountsEffectivenessGet()`

```php
reportsDiscountsEffectivenessGet()
```

Generate a report of effectiveness of discounts in increasing order volume or customer retention

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->reportsDiscountsEffectivenessGet();
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->reportsDiscountsEffectivenessGet: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

This endpoint does not need any parameter.

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `reportsDiscountsRevenueImpactGet()`

```php
reportsDiscountsRevenueImpactGet()
```

Generate a report of revenue impact of discounts

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->reportsDiscountsRevenueImpactGet();
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->reportsDiscountsRevenueImpactGet: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

This endpoint does not need any parameter.

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `reportsDiscountsUsageGet()`

```php
reportsDiscountsUsageGet()
```

Generate a report of usage statistics for each discount code

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->reportsDiscountsUsageGet();
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->reportsDiscountsUsageGet: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

This endpoint does not need any parameter.

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `reportsGet()`

```php
reportsGet(): \OpenAPI\Client\Model\Report[]
```

Get all reports

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $result = $apiInstance->reportsGet();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->reportsGet: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**\OpenAPI\Client\Model\Report[]**](../Model/Report.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `reportsMenusPopularityGet()`

```php
reportsMenusPopularityGet()
```

Generate a report of most popular dishes at each restaurant

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->reportsMenusPopularityGet();
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->reportsMenusPopularityGet: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

This endpoint does not need any parameter.

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `reportsOrdersAverageValueGet()`

```php
reportsOrdersAverageValueGet()
```

Generate a report of average order value within a specific time period

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->reportsOrdersAverageValueGet();
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->reportsOrdersAverageValueGet: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

This endpoint does not need any parameter.

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `reportsOrdersFulfillmentTimeGet()`

```php
reportsOrdersFulfillmentTimeGet()
```

Generate a report of order fulfillment time statistics

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->reportsOrdersFulfillmentTimeGet();
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->reportsOrdersFulfillmentTimeGet: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

This endpoint does not need any parameter.

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `reportsOrdersTotalGet()`

```php
reportsOrdersTotalGet()
```

Generate a report of total number of orders placed within a specific time period

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->reportsOrdersTotalGet();
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->reportsOrdersTotalGet: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

This endpoint does not need any parameter.

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `reportsPost()`

```php
reportsPost($new_report)
```

Create a new report

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$new_report = new \OpenAPI\Client\Model\NewReport(); // \OpenAPI\Client\Model\NewReport

try {
    $apiInstance->reportsPost($new_report);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->reportsPost: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **new_report** | [**\OpenAPI\Client\Model\NewReport**](../Model/NewReport.md)|  | |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `reportsReportIdDelete()`

```php
reportsReportIdDelete($report_id)
```

Delete a report

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$report_id = 'report_id_example'; // string

try {
    $apiInstance->reportsReportIdDelete($report_id);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->reportsReportIdDelete: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **report_id** | **string**|  | |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `reportsReportIdGet()`

```php
reportsReportIdGet($report_id): \OpenAPI\Client\Model\Report
```

Get a report by ID

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$report_id = 'report_id_example'; // string

try {
    $result = $apiInstance->reportsReportIdGet($report_id);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->reportsReportIdGet: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **report_id** | **string**|  | |

### Return type

[**\OpenAPI\Client\Model\Report**](../Model/Report.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `reportsReportIdPut()`

```php
reportsReportIdPut($report_id, $update_report)
```

Update a report

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$report_id = 'report_id_example'; // string
$update_report = new \OpenAPI\Client\Model\UpdateReport(); // \OpenAPI\Client\Model\UpdateReport

try {
    $apiInstance->reportsReportIdPut($report_id, $update_report);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->reportsReportIdPut: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **report_id** | **string**|  | |
| **update_report** | [**\OpenAPI\Client\Model\UpdateReport**](../Model/UpdateReport.md)|  | |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `reportsRestaurantsOrdersGet()`

```php
reportsRestaurantsOrdersGet()
```

Generate a report of total orders received by each restaurant

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->reportsRestaurantsOrdersGet();
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->reportsRestaurantsOrdersGet: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

This endpoint does not need any parameter.

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `reportsRestaurantsRatingsGet()`

```php
reportsRestaurantsRatingsGet()
```

Generate a report of average ratings of each restaurant

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->reportsRestaurantsRatingsGet();
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->reportsRestaurantsRatingsGet: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

This endpoint does not need any parameter.

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `reportsRestaurantsRevenueGet()`

```php
reportsRestaurantsRevenueGet()
```

Generate a report of revenue generated by each restaurant

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->reportsRestaurantsRevenueGet();
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->reportsRestaurantsRevenueGet: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

This endpoint does not need any parameter.

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `restaurantsGet()`

```php
restaurantsGet(): \OpenAPI\Client\Model\Restaurant[]
```

Get all restaurants

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $result = $apiInstance->restaurantsGet();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->restaurantsGet: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**\OpenAPI\Client\Model\Restaurant[]**](../Model/Restaurant.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `restaurantsPost()`

```php
restaurantsPost($name, $description, $location, $opening_hours, $delivery_areas, $image)
```

Create a new restaurant

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$name = 'name_example'; // string
$description = 'description_example'; // string
$location = new \OpenAPI\Client\Model\RestaurantsPostRequestLocation(); // \OpenAPI\Client\Model\RestaurantsPostRequestLocation
$opening_hours = 'opening_hours_example'; // string
$delivery_areas = array('delivery_areas_example'); // string[]
$image = "/path/to/file.txt"; // \SplFileObject

try {
    $apiInstance->restaurantsPost($name, $description, $location, $opening_hours, $delivery_areas, $image);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->restaurantsPost: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **name** | **string**|  | [optional] |
| **description** | **string**|  | [optional] |
| **location** | [**\OpenAPI\Client\Model\RestaurantsPostRequestLocation**](../Model/RestaurantsPostRequestLocation.md)|  | [optional] |
| **opening_hours** | **string**|  | [optional] |
| **delivery_areas** | [**string[]**](../Model/string.md)|  | [optional] |
| **image** | **\SplFileObject****\SplFileObject**|  | [optional] |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `multipart/form-data`
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `restaurantsRestaurantIdDelete()`

```php
restaurantsRestaurantIdDelete($restaurant_id)
```

Delete a restaurant

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$restaurant_id = 'restaurant_id_example'; // string

try {
    $apiInstance->restaurantsRestaurantIdDelete($restaurant_id);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->restaurantsRestaurantIdDelete: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **restaurant_id** | **string**|  | |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `restaurantsRestaurantIdGet()`

```php
restaurantsRestaurantIdGet($restaurant_id): \OpenAPI\Client\Model\Restaurant
```

Get a restaurant by ID

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$restaurant_id = 'restaurant_id_example'; // string

try {
    $result = $apiInstance->restaurantsRestaurantIdGet($restaurant_id);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->restaurantsRestaurantIdGet: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **restaurant_id** | **string**|  | |

### Return type

[**\OpenAPI\Client\Model\Restaurant**](../Model/Restaurant.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `restaurantsRestaurantIdMenusGet()`

```php
restaurantsRestaurantIdMenusGet($restaurant_id): \OpenAPI\Client\Model\MenuItem[]
```

Get all menu items for a restaurant

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$restaurant_id = 'restaurant_id_example'; // string

try {
    $result = $apiInstance->restaurantsRestaurantIdMenusGet($restaurant_id);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->restaurantsRestaurantIdMenusGet: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **restaurant_id** | **string**|  | |

### Return type

[**\OpenAPI\Client\Model\MenuItem[]**](../Model/MenuItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `restaurantsRestaurantIdMenusMenuIdDelete()`

```php
restaurantsRestaurantIdMenusMenuIdDelete($restaurant_id, $menu_id)
```

Delete a menu item

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$restaurant_id = 'restaurant_id_example'; // string
$menu_id = 'menu_id_example'; // string

try {
    $apiInstance->restaurantsRestaurantIdMenusMenuIdDelete($restaurant_id, $menu_id);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->restaurantsRestaurantIdMenusMenuIdDelete: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **restaurant_id** | **string**|  | |
| **menu_id** | **string**|  | |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `restaurantsRestaurantIdMenusMenuIdGet()`

```php
restaurantsRestaurantIdMenusMenuIdGet($restaurant_id, $menu_id): \OpenAPI\Client\Model\MenuItem
```

Get a menu item by ID

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$restaurant_id = 'restaurant_id_example'; // string
$menu_id = 'menu_id_example'; // string

try {
    $result = $apiInstance->restaurantsRestaurantIdMenusMenuIdGet($restaurant_id, $menu_id);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->restaurantsRestaurantIdMenusMenuIdGet: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **restaurant_id** | **string**|  | |
| **menu_id** | **string**|  | |

### Return type

[**\OpenAPI\Client\Model\MenuItem**](../Model/MenuItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `restaurantsRestaurantIdMenusMenuIdPut()`

```php
restaurantsRestaurantIdMenusMenuIdPut($restaurant_id, $menu_id, $name, $description, $price, $image)
```

Update a menu item

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$restaurant_id = 'restaurant_id_example'; // string
$menu_id = 'menu_id_example'; // string
$name = 'name_example'; // string
$description = 'description_example'; // string
$price = 3.4; // float
$image = "/path/to/file.txt"; // \SplFileObject

try {
    $apiInstance->restaurantsRestaurantIdMenusMenuIdPut($restaurant_id, $menu_id, $name, $description, $price, $image);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->restaurantsRestaurantIdMenusMenuIdPut: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **restaurant_id** | **string**|  | |
| **menu_id** | **string**|  | |
| **name** | **string**|  | [optional] |
| **description** | **string**|  | [optional] |
| **price** | **float**|  | [optional] |
| **image** | **\SplFileObject****\SplFileObject**|  | [optional] |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `multipart/form-data`
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `restaurantsRestaurantIdMenusPost()`

```php
restaurantsRestaurantIdMenusPost($restaurant_id, $name, $description, $price, $image)
```

Create a new menu item

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$restaurant_id = 'restaurant_id_example'; // string
$name = 'name_example'; // string
$description = 'description_example'; // string
$price = 3.4; // float
$image = "/path/to/file.txt"; // \SplFileObject

try {
    $apiInstance->restaurantsRestaurantIdMenusPost($restaurant_id, $name, $description, $price, $image);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->restaurantsRestaurantIdMenusPost: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **restaurant_id** | **string**|  | |
| **name** | **string**|  | [optional] |
| **description** | **string**|  | [optional] |
| **price** | **float**|  | [optional] |
| **image** | **\SplFileObject****\SplFileObject**|  | [optional] |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `multipart/form-data`
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `restaurantsRestaurantIdPut()`

```php
restaurantsRestaurantIdPut($restaurant_id, $name, $description, $location, $opening_hours, $delivery_areas, $image)
```

Update a restaurant

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$restaurant_id = 'restaurant_id_example'; // string
$name = 'name_example'; // string
$description = 'description_example'; // string
$location = new \OpenAPI\Client\Model\RestaurantsPostRequestLocation(); // \OpenAPI\Client\Model\RestaurantsPostRequestLocation
$opening_hours = 'opening_hours_example'; // string
$delivery_areas = array('delivery_areas_example'); // string[]
$image = "/path/to/file.txt"; // \SplFileObject

try {
    $apiInstance->restaurantsRestaurantIdPut($restaurant_id, $name, $description, $location, $opening_hours, $delivery_areas, $image);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->restaurantsRestaurantIdPut: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **restaurant_id** | **string**|  | |
| **name** | **string**|  | [optional] |
| **description** | **string**|  | [optional] |
| **location** | [**\OpenAPI\Client\Model\RestaurantsPostRequestLocation**](../Model/RestaurantsPostRequestLocation.md)|  | [optional] |
| **opening_hours** | **string**|  | [optional] |
| **delivery_areas** | [**string[]**](../Model/string.md)|  | [optional] |
| **image** | **\SplFileObject****\SplFileObject**|  | [optional] |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `multipart/form-data`
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)
