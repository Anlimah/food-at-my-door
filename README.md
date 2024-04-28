# OpenAPIClient-php

API for managing restaurants, menus, orders, and deliveries in a food delivery app


## Installation & Usage

### Requirements

PHP 7.4 and later.
Should also work with PHP 8.0.

### Composer

To install the bindings via [Composer](https://getcomposer.org/), add the following to `composer.json`:

```json
{
  "repositories": [
    {
      "type": "vcs",
      "url": "https://github.com/GIT_USER_ID/GIT_REPO_ID.git"
    }
  ],
  "require": {
    "GIT_USER_ID/GIT_REPO_ID": "*@dev"
  }
}
```

Then run `composer install`

### Manual Installation

Download the files and include `autoload.php`:

```php
<?php
require_once('/path/to/OpenAPIClient-php/vendor/autoload.php');
```

## Getting Started

Please follow the [installation procedure](#installation--usage) and then run the following:

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

## API Endpoints

All URIs are relative to *https://api.lafcomputerlabs.com:8443/v1*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*DefaultApi* | [**categoriesCategoryIdDelete**](docs/Api/DefaultApi.md#categoriescategoryiddelete) | **DELETE** /categories/{categoryId} | Delete a category
*DefaultApi* | [**categoriesCategoryIdGet**](docs/Api/DefaultApi.md#categoriescategoryidget) | **GET** /categories/{categoryId} | Get a category by ID
*DefaultApi* | [**categoriesCategoryIdPut**](docs/Api/DefaultApi.md#categoriescategoryidput) | **PUT** /categories/{categoryId} | Update a category
*DefaultApi* | [**categoriesGet**](docs/Api/DefaultApi.md#categoriesget) | **GET** /categories | Get all categories
*DefaultApi* | [**categoriesPost**](docs/Api/DefaultApi.md#categoriespost) | **POST** /categories | Create a new category
*DefaultApi* | [**customersCustomerIdDelete**](docs/Api/DefaultApi.md#customerscustomeriddelete) | **DELETE** /customers/{customerId} | Delete a customer
*DefaultApi* | [**customersCustomerIdGet**](docs/Api/DefaultApi.md#customerscustomeridget) | **GET** /customers/{customerId} | Get a customer by ID
*DefaultApi* | [**customersCustomerIdPut**](docs/Api/DefaultApi.md#customerscustomeridput) | **PUT** /customers/{customerId} | Update a customer
*DefaultApi* | [**customersGet**](docs/Api/DefaultApi.md#customersget) | **GET** /customers | Get all customers
*DefaultApi* | [**customersPost**](docs/Api/DefaultApi.md#customerspost) | **POST** /customers | Create a new customer
*DefaultApi* | [**discountsDiscountIdDelete**](docs/Api/DefaultApi.md#discountsdiscountiddelete) | **DELETE** /discounts/{discountId} | Delete a discount
*DefaultApi* | [**discountsDiscountIdGet**](docs/Api/DefaultApi.md#discountsdiscountidget) | **GET** /discounts/{discountId} | Get a discount by ID
*DefaultApi* | [**discountsDiscountIdPut**](docs/Api/DefaultApi.md#discountsdiscountidput) | **PUT** /discounts/{discountId} | Update a discount
*DefaultApi* | [**discountsGet**](docs/Api/DefaultApi.md#discountsget) | **GET** /discounts | Get all discounts
*DefaultApi* | [**discountsPost**](docs/Api/DefaultApi.md#discountspost) | **POST** /discounts | Create a new discount
*DefaultApi* | [**ingredientsGet**](docs/Api/DefaultApi.md#ingredientsget) | **GET** /ingredients | Get all ingredients
*DefaultApi* | [**ingredientsIngredientIdDelete**](docs/Api/DefaultApi.md#ingredientsingredientiddelete) | **DELETE** /ingredients/{ingredientId} | Delete an ingredient
*DefaultApi* | [**ingredientsIngredientIdGet**](docs/Api/DefaultApi.md#ingredientsingredientidget) | **GET** /ingredients/{ingredientId} | Get an ingredient by ID
*DefaultApi* | [**ingredientsIngredientIdPut**](docs/Api/DefaultApi.md#ingredientsingredientidput) | **PUT** /ingredients/{ingredientId} | Update an ingredient
*DefaultApi* | [**ingredientsPost**](docs/Api/DefaultApi.md#ingredientspost) | **POST** /ingredients | Create a new ingredient
*DefaultApi* | [**menuItemCategoriesCategoryIdDelete**](docs/Api/DefaultApi.md#menuitemcategoriescategoryiddelete) | **DELETE** /menu-item-categories/{categoryId} | Delete a menu item category
*DefaultApi* | [**menuItemCategoriesCategoryIdGet**](docs/Api/DefaultApi.md#menuitemcategoriescategoryidget) | **GET** /menu-item-categories/{categoryId} | Get a menu item category by ID
*DefaultApi* | [**menuItemCategoriesCategoryIdPut**](docs/Api/DefaultApi.md#menuitemcategoriescategoryidput) | **PUT** /menu-item-categories/{categoryId} | Update a menu item category
*DefaultApi* | [**menuItemCategoriesGet**](docs/Api/DefaultApi.md#menuitemcategoriesget) | **GET** /menu-item-categories | Get all menu item categories
*DefaultApi* | [**menuItemCategoriesPost**](docs/Api/DefaultApi.md#menuitemcategoriespost) | **POST** /menu-item-categories | Create a new menu item category
*DefaultApi* | [**menuItemOptionsGet**](docs/Api/DefaultApi.md#menuitemoptionsget) | **GET** /menu-item-options | Get all menu item options
*DefaultApi* | [**menuItemOptionsOptionIdDelete**](docs/Api/DefaultApi.md#menuitemoptionsoptioniddelete) | **DELETE** /menu-item-options/{optionId} | Delete a menu item option
*DefaultApi* | [**menuItemOptionsOptionIdGet**](docs/Api/DefaultApi.md#menuitemoptionsoptionidget) | **GET** /menu-item-options/{optionId} | Get a menu item option by ID
*DefaultApi* | [**menuItemOptionsOptionIdPut**](docs/Api/DefaultApi.md#menuitemoptionsoptionidput) | **PUT** /menu-item-options/{optionId} | Update a menu item option
*DefaultApi* | [**menuItemOptionsPost**](docs/Api/DefaultApi.md#menuitemoptionspost) | **POST** /menu-item-options | Create a new menu item option
*DefaultApi* | [**menuItemsGet**](docs/Api/DefaultApi.md#menuitemsget) | **GET** /menu-items | Get all menu items
*DefaultApi* | [**menuItemsItemIdDelete**](docs/Api/DefaultApi.md#menuitemsitemiddelete) | **DELETE** /menu-items/{itemId} | Delete a menu item
*DefaultApi* | [**menuItemsItemIdGet**](docs/Api/DefaultApi.md#menuitemsitemidget) | **GET** /menu-items/{itemId} | Get a menu item by ID
*DefaultApi* | [**menuItemsItemIdPut**](docs/Api/DefaultApi.md#menuitemsitemidput) | **PUT** /menu-items/{itemId} | Update a menu item
*DefaultApi* | [**menuItemsPost**](docs/Api/DefaultApi.md#menuitemspost) | **POST** /menu-items | Create a new menu item
*DefaultApi* | [**orderItemsGet**](docs/Api/DefaultApi.md#orderitemsget) | **GET** /order-items | Get all order items
*DefaultApi* | [**orderItemsItemIdDelete**](docs/Api/DefaultApi.md#orderitemsitemiddelete) | **DELETE** /order-items/{itemId} | Delete an order item
*DefaultApi* | [**orderItemsItemIdGet**](docs/Api/DefaultApi.md#orderitemsitemidget) | **GET** /order-items/{itemId} | Get an order item by ID
*DefaultApi* | [**orderItemsItemIdPut**](docs/Api/DefaultApi.md#orderitemsitemidput) | **PUT** /order-items/{itemId} | Update an order item
*DefaultApi* | [**orderItemsPost**](docs/Api/DefaultApi.md#orderitemspost) | **POST** /order-items | Create a new order item
*DefaultApi* | [**ordersGet**](docs/Api/DefaultApi.md#ordersget) | **GET** /orders | Get all orders
*DefaultApi* | [**ordersOrderIdDelete**](docs/Api/DefaultApi.md#ordersorderiddelete) | **DELETE** /orders/{orderId} | Delete an order
*DefaultApi* | [**ordersOrderIdGet**](docs/Api/DefaultApi.md#ordersorderidget) | **GET** /orders/{orderId} | Get an order by ID
*DefaultApi* | [**ordersOrderIdPut**](docs/Api/DefaultApi.md#ordersorderidput) | **PUT** /orders/{orderId} | Update an order
*DefaultApi* | [**ordersPost**](docs/Api/DefaultApi.md#orderspost) | **POST** /orders | Create a new order
*DefaultApi* | [**reportsComponentItemGet**](docs/Api/DefaultApi.md#reportscomponentitemget) | **GET** /reports/{component}/{item} | Generate a report for a specific component and item
*DefaultApi* | [**reportsCustomersAverageOrderFrequencyGet**](docs/Api/DefaultApi.md#reportscustomersaverageorderfrequencyget) | **GET** /reports/customers/average-order-frequency | Generate a report of average order frequency per customer
*DefaultApi* | [**reportsCustomersRetentionGet**](docs/Api/DefaultApi.md#reportscustomersretentionget) | **GET** /reports/customers/retention | Generate a report of customer retention rate
*DefaultApi* | [**reportsCustomersTotalGet**](docs/Api/DefaultApi.md#reportscustomerstotalget) | **GET** /reports/customers/total | Generate a report of total number of customers registered on the platform
*DefaultApi* | [**reportsDiscountsEffectivenessGet**](docs/Api/DefaultApi.md#reportsdiscountseffectivenessget) | **GET** /reports/discounts/effectiveness | Generate a report of effectiveness of discounts in increasing order volume or customer retention
*DefaultApi* | [**reportsDiscountsRevenueImpactGet**](docs/Api/DefaultApi.md#reportsdiscountsrevenueimpactget) | **GET** /reports/discounts/revenue-impact | Generate a report of revenue impact of discounts
*DefaultApi* | [**reportsDiscountsUsageGet**](docs/Api/DefaultApi.md#reportsdiscountsusageget) | **GET** /reports/discounts/usage | Generate a report of usage statistics for each discount code
*DefaultApi* | [**reportsGet**](docs/Api/DefaultApi.md#reportsget) | **GET** /reports | Get all reports
*DefaultApi* | [**reportsMenusPopularityGet**](docs/Api/DefaultApi.md#reportsmenuspopularityget) | **GET** /reports/menus/popularity | Generate a report of most popular dishes at each restaurant
*DefaultApi* | [**reportsOrdersAverageValueGet**](docs/Api/DefaultApi.md#reportsordersaveragevalueget) | **GET** /reports/orders/average-value | Generate a report of average order value within a specific time period
*DefaultApi* | [**reportsOrdersFulfillmentTimeGet**](docs/Api/DefaultApi.md#reportsordersfulfillmenttimeget) | **GET** /reports/orders/fulfillment-time | Generate a report of order fulfillment time statistics
*DefaultApi* | [**reportsOrdersTotalGet**](docs/Api/DefaultApi.md#reportsorderstotalget) | **GET** /reports/orders/total | Generate a report of total number of orders placed within a specific time period
*DefaultApi* | [**reportsPost**](docs/Api/DefaultApi.md#reportspost) | **POST** /reports | Create a new report
*DefaultApi* | [**reportsReportIdDelete**](docs/Api/DefaultApi.md#reportsreportiddelete) | **DELETE** /reports/{reportId} | Delete a report
*DefaultApi* | [**reportsReportIdGet**](docs/Api/DefaultApi.md#reportsreportidget) | **GET** /reports/{reportId} | Get a report by ID
*DefaultApi* | [**reportsReportIdPut**](docs/Api/DefaultApi.md#reportsreportidput) | **PUT** /reports/{reportId} | Update a report
*DefaultApi* | [**reportsRestaurantsOrdersGet**](docs/Api/DefaultApi.md#reportsrestaurantsordersget) | **GET** /reports/restaurants/orders | Generate a report of total orders received by each restaurant
*DefaultApi* | [**reportsRestaurantsRatingsGet**](docs/Api/DefaultApi.md#reportsrestaurantsratingsget) | **GET** /reports/restaurants/ratings | Generate a report of average ratings of each restaurant
*DefaultApi* | [**reportsRestaurantsRevenueGet**](docs/Api/DefaultApi.md#reportsrestaurantsrevenueget) | **GET** /reports/restaurants/revenue | Generate a report of revenue generated by each restaurant
*DefaultApi* | [**restaurantsGet**](docs/Api/DefaultApi.md#restaurantsget) | **GET** /restaurants | Get all restaurants
*DefaultApi* | [**restaurantsPost**](docs/Api/DefaultApi.md#restaurantspost) | **POST** /restaurants | Create a new restaurant
*DefaultApi* | [**restaurantsRestaurantIdDelete**](docs/Api/DefaultApi.md#restaurantsrestaurantiddelete) | **DELETE** /restaurants/{restaurantId} | Delete a restaurant
*DefaultApi* | [**restaurantsRestaurantIdGet**](docs/Api/DefaultApi.md#restaurantsrestaurantidget) | **GET** /restaurants/{restaurantId} | Get a restaurant by ID
*DefaultApi* | [**restaurantsRestaurantIdMenusGet**](docs/Api/DefaultApi.md#restaurantsrestaurantidmenusget) | **GET** /restaurants/{restaurantId}/menus | Get all menu items for a restaurant
*DefaultApi* | [**restaurantsRestaurantIdMenusMenuIdDelete**](docs/Api/DefaultApi.md#restaurantsrestaurantidmenusmenuiddelete) | **DELETE** /restaurants/{restaurantId}/menus/{menuId} | Delete a menu item
*DefaultApi* | [**restaurantsRestaurantIdMenusMenuIdGet**](docs/Api/DefaultApi.md#restaurantsrestaurantidmenusmenuidget) | **GET** /restaurants/{restaurantId}/menus/{menuId} | Get a menu item by ID
*DefaultApi* | [**restaurantsRestaurantIdMenusMenuIdPut**](docs/Api/DefaultApi.md#restaurantsrestaurantidmenusmenuidput) | **PUT** /restaurants/{restaurantId}/menus/{menuId} | Update a menu item
*DefaultApi* | [**restaurantsRestaurantIdMenusPost**](docs/Api/DefaultApi.md#restaurantsrestaurantidmenuspost) | **POST** /restaurants/{restaurantId}/menus | Create a new menu item
*DefaultApi* | [**restaurantsRestaurantIdPut**](docs/Api/DefaultApi.md#restaurantsrestaurantidput) | **PUT** /restaurants/{restaurantId} | Update a restaurant

## Models

- [Category](docs/Model/Category.md)
- [Customer](docs/Model/Customer.md)
- [Discount](docs/Model/Discount.md)
- [Ingredient](docs/Model/Ingredient.md)
- [MenuItem](docs/Model/MenuItem.md)
- [MenuItemCategory](docs/Model/MenuItemCategory.md)
- [MenuItemOption](docs/Model/MenuItemOption.md)
- [NewCategory](docs/Model/NewCategory.md)
- [NewCustomer](docs/Model/NewCustomer.md)
- [NewDiscount](docs/Model/NewDiscount.md)
- [NewIngredient](docs/Model/NewIngredient.md)
- [NewMenuItem](docs/Model/NewMenuItem.md)
- [NewMenuItemCategory](docs/Model/NewMenuItemCategory.md)
- [NewMenuItemOption](docs/Model/NewMenuItemOption.md)
- [NewOrder](docs/Model/NewOrder.md)
- [NewOrderItem](docs/Model/NewOrderItem.md)
- [NewOrderItemsInner](docs/Model/NewOrderItemsInner.md)
- [NewReport](docs/Model/NewReport.md)
- [Order](docs/Model/Order.md)
- [OrderItem](docs/Model/OrderItem.md)
- [Report](docs/Model/Report.md)
- [Restaurant](docs/Model/Restaurant.md)
- [RestaurantsPostRequestLocation](docs/Model/RestaurantsPostRequestLocation.md)
- [UpdateCategory](docs/Model/UpdateCategory.md)
- [UpdateCustomer](docs/Model/UpdateCustomer.md)
- [UpdateDiscount](docs/Model/UpdateDiscount.md)
- [UpdateIngredient](docs/Model/UpdateIngredient.md)
- [UpdateMenuItem](docs/Model/UpdateMenuItem.md)
- [UpdateMenuItemCategory](docs/Model/UpdateMenuItemCategory.md)
- [UpdateMenuItemOption](docs/Model/UpdateMenuItemOption.md)
- [UpdateOrder](docs/Model/UpdateOrder.md)
- [UpdateOrderItem](docs/Model/UpdateOrderItem.md)
- [UpdateReport](docs/Model/UpdateReport.md)

## Authorization
Endpoints do not require authorization.

## Tests

To run the tests, use:

```bash
composer install
vendor/bin/phpunit
```

## Author



## About this package

This PHP package is automatically generated by the [OpenAPI Generator](https://openapi-generator.tech) project:

- API version: `1.0.0`
    - Generator version: `7.5.0`
- Build package: `org.openapitools.codegen.languages.PhpClientCodegen`
