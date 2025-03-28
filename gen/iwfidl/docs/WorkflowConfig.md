# WorkflowConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DisableSystemSearchAttribute** | Pointer to **bool** |  | [optional] 
**ExecutingStateIdMode** | Pointer to [**ExecutingStateIdMode**](ExecutingStateIdMode.md) |  | [optional] 
**ContinueAsNewThreshold** | Pointer to **int32** |  | [optional] 
**ContinueAsNewPageSizeInBytes** | Pointer to **int32** |  | [optional] 
**OptimizeActivity** | Pointer to **bool** |  | [optional] 
**OptimizeTimer** | Pointer to **bool** |  | [optional] 

## Methods

### NewWorkflowConfig

`func NewWorkflowConfig() *WorkflowConfig`

NewWorkflowConfig instantiates a new WorkflowConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkflowConfigWithDefaults

`func NewWorkflowConfigWithDefaults() *WorkflowConfig`

NewWorkflowConfigWithDefaults instantiates a new WorkflowConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDisableSystemSearchAttribute

`func (o *WorkflowConfig) GetDisableSystemSearchAttribute() bool`

GetDisableSystemSearchAttribute returns the DisableSystemSearchAttribute field if non-nil, zero value otherwise.

### GetDisableSystemSearchAttributeOk

`func (o *WorkflowConfig) GetDisableSystemSearchAttributeOk() (*bool, bool)`

GetDisableSystemSearchAttributeOk returns a tuple with the DisableSystemSearchAttribute field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisableSystemSearchAttribute

`func (o *WorkflowConfig) SetDisableSystemSearchAttribute(v bool)`

SetDisableSystemSearchAttribute sets DisableSystemSearchAttribute field to given value.

### HasDisableSystemSearchAttribute

`func (o *WorkflowConfig) HasDisableSystemSearchAttribute() bool`

HasDisableSystemSearchAttribute returns a boolean if a field has been set.

### GetExecutingStateIdMode

`func (o *WorkflowConfig) GetExecutingStateIdMode() ExecutingStateIdMode`

GetExecutingStateIdMode returns the ExecutingStateIdMode field if non-nil, zero value otherwise.

### GetExecutingStateIdModeOk

`func (o *WorkflowConfig) GetExecutingStateIdModeOk() (*ExecutingStateIdMode, bool)`

GetExecutingStateIdModeOk returns a tuple with the ExecutingStateIdMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExecutingStateIdMode

`func (o *WorkflowConfig) SetExecutingStateIdMode(v ExecutingStateIdMode)`

SetExecutingStateIdMode sets ExecutingStateIdMode field to given value.

### HasExecutingStateIdMode

`func (o *WorkflowConfig) HasExecutingStateIdMode() bool`

HasExecutingStateIdMode returns a boolean if a field has been set.

### GetContinueAsNewThreshold

`func (o *WorkflowConfig) GetContinueAsNewThreshold() int32`

GetContinueAsNewThreshold returns the ContinueAsNewThreshold field if non-nil, zero value otherwise.

### GetContinueAsNewThresholdOk

`func (o *WorkflowConfig) GetContinueAsNewThresholdOk() (*int32, bool)`

GetContinueAsNewThresholdOk returns a tuple with the ContinueAsNewThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContinueAsNewThreshold

`func (o *WorkflowConfig) SetContinueAsNewThreshold(v int32)`

SetContinueAsNewThreshold sets ContinueAsNewThreshold field to given value.

### HasContinueAsNewThreshold

`func (o *WorkflowConfig) HasContinueAsNewThreshold() bool`

HasContinueAsNewThreshold returns a boolean if a field has been set.

### GetContinueAsNewPageSizeInBytes

`func (o *WorkflowConfig) GetContinueAsNewPageSizeInBytes() int32`

GetContinueAsNewPageSizeInBytes returns the ContinueAsNewPageSizeInBytes field if non-nil, zero value otherwise.

### GetContinueAsNewPageSizeInBytesOk

`func (o *WorkflowConfig) GetContinueAsNewPageSizeInBytesOk() (*int32, bool)`

GetContinueAsNewPageSizeInBytesOk returns a tuple with the ContinueAsNewPageSizeInBytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContinueAsNewPageSizeInBytes

`func (o *WorkflowConfig) SetContinueAsNewPageSizeInBytes(v int32)`

SetContinueAsNewPageSizeInBytes sets ContinueAsNewPageSizeInBytes field to given value.

### HasContinueAsNewPageSizeInBytes

`func (o *WorkflowConfig) HasContinueAsNewPageSizeInBytes() bool`

HasContinueAsNewPageSizeInBytes returns a boolean if a field has been set.

### GetOptimizeActivity

`func (o *WorkflowConfig) GetOptimizeActivity() bool`

GetOptimizeActivity returns the OptimizeActivity field if non-nil, zero value otherwise.

### GetOptimizeActivityOk

`func (o *WorkflowConfig) GetOptimizeActivityOk() (*bool, bool)`

GetOptimizeActivityOk returns a tuple with the OptimizeActivity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOptimizeActivity

`func (o *WorkflowConfig) SetOptimizeActivity(v bool)`

SetOptimizeActivity sets OptimizeActivity field to given value.

### HasOptimizeActivity

`func (o *WorkflowConfig) HasOptimizeActivity() bool`

HasOptimizeActivity returns a boolean if a field has been set.

### GetOptimizeTimer

`func (o *WorkflowConfig) GetOptimizeTimer() bool`

GetOptimizeTimer returns the OptimizeTimer field if non-nil, zero value otherwise.

### GetOptimizeTimerOk

`func (o *WorkflowConfig) GetOptimizeTimerOk() (*bool, bool)`

GetOptimizeTimerOk returns a tuple with the OptimizeTimer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOptimizeTimer

`func (o *WorkflowConfig) SetOptimizeTimer(v bool)`

SetOptimizeTimer sets OptimizeTimer field to given value.

### HasOptimizeTimer

`func (o *WorkflowConfig) HasOptimizeTimer() bool`

HasOptimizeTimer returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


