# Introduction

OCI Object Storage service exposes an [S3 compatible API](https://docs.oracle.com/en-us/iaas/Content/Object/Tasks/s3compatibleapi.htm) that allows you to continue using your existing S3 Tools and applications with minimal changes.

Currently supported S3 API endpoints are documented [here] (https://docs.oracle.com/en-us/iaas/Content/Object/Tasks/s3compatibleapi.htm#APIsupport)

# Prerequisites

Before attempting to invoke the S3 compatible API go through this [guide](https://docs.oracle.com/en-us/iaas/Content/Object/Tasks/s3compatibleapi.htm#usingAPI) and get your access and secret keys.

# Setup

1. Import the [file](/S3_compatibility_API_collection.json) into Postman.
2. Define the current values of the variables: `objectstoragenamespace`, `region`, `bucket-name`, `access_key` and `secret_key`.
