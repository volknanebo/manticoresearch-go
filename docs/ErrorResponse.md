# ErrorResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | **map[string]map[string]interface{}** |  | 
**Status** | **int32** |  | 

## Methods

### NewErrorResponse

`func NewErrorResponse(error_ map[string]map[string]interface{}, status int32, ) *ErrorResponse`

NewErrorResponse instantiates a new ErrorResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewErrorResponseWithDefaults

`func NewErrorResponseWithDefaults() *ErrorResponse`

NewErrorResponseWithDefaults instantiates a new ErrorResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *ErrorResponse) GetError() map[string]map[string]interface{}`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ErrorResponse) GetErrorOk() (*map[string]map[string]interface{}, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ErrorResponse) SetError(v map[string]map[string]interface{})`

SetError sets Error field to given value.


### GetStatus

`func (o *ErrorResponse) GetStatus() int32`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ErrorResponse) GetStatusOk() (*int32, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ErrorResponse) SetStatus(v int32)`

SetStatus sets Status field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


