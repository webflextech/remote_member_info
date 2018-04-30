# RemoteMemberInfo::MemberApi

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**member_get**](MemberApi.md#member_get) | **GET** /members/{id} | Gets a member by id


# **member_get**
> User member_get(id)

Gets a member by id

### Example
```ruby
# load the gem
require 'remote_member_info'

api_instance = RemoteMemberInfo::MemberApi.new

id = "id_example" # String | 


begin
  #Gets a member by id
  result = api_instance.member_get(id)
  p result
rescue RemoteMemberInfo::ApiError => e
  puts "Exception when calling MemberApi->member_get: #{e}"
end
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**|  | 

### Return type

[**User**](User.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json



