# \GameApi

All URIs are relative to *http://localhost:3000/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetPlayer**](GameApi.md#GetPlayer) | **Get** /player | Get Player
[**PostMoves**](GameApi.md#PostMoves) | **Post** /moves | Create Move



## GetPlayer

> InlineResponse202 GetPlayer(ctx, )

Get Player

Get player information

### Required Parameters

This endpoint does not need any parameter.

### Return type

[**InlineResponse202**](inline_response_202.md)

### Authorization

[token](../README.md#token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PostMoves

> InlineResponse202 PostMoves(ctx, direction)

Create Move

Create a player move

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**direction** | **string**| The direction to move | 

### Return type

[**InlineResponse202**](inline_response_202.md)

### Authorization

[token](../README.md#token)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

