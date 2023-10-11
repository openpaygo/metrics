# OpenPAYGO Metrics

This repository contains all the information you need to integrate OpenPAYGO Metrics into your device or PAYGO software. 

<p align="center">
  <img
    alt="Project Status"
    src="https://img.shields.io/badge/Project%20Status-active-blue"
  >
  <a href="https://github.com/openpaygo/metrics/blob/main/LICENSE" target="_blank">
    <img
      alt="License"
      src="https://img.shields.io/github/license/openpaygo/metrics"
    >
  </a>
</p>


## Credits
This open-source project was fully funded and developped by [Solaris Offgrid](https://www.solarisoffgrid.com/), the developers of PaygOps™ and is free to use by all. 


## Implementations

### Python Implementation
A [Python implementation](https://github.com/EnAccess/OpenPAYGO-python) is available, implementing OpenPAYGO Metrics as well as OpenPAYGO Token for use either on server side or on device side. 

### Arduino Implementation
An Arduino library for the device side is currently being worked on. More information will be posted here once a working version is available. If you would like to contribute or sponsor this project, or if you would like to be added to the registry of current user, open an issue in the issue tracker to let us know. 

## Getting Started

OpenPAYGO Metrics provide a standardized way for PAYGO devices to send usage metrics to a server and get back information about their activation status in a low cost and secure way. The specification is designed so that the payload is very lightweight while additional information about the data format can be provided to allow servers to display and process the data with a lot of details. It is currently in active use by multiple software providers and manufacturers. 

To get started implementing, check out [that document](https://github.com/openpaygo/metrics/blob/main/Specifications.md) that describes the detailed specification of the OpenPAYGO Metrics payload and API. 

## Changelog

## 2023-10-xx - v1.0.0-rc1
- Added "Recursive Data Auth" as a memory efficient authentication option
- Added clarification about data formatting for auth signature generation
- Properly specified code block type for examples
- Add link to OpenPAYGO Python library for handling metrics

### 2023-10-02 - v1.0.0-rc0
- Improved the "Variable Type" object structure documentation
- Added information about the aggregation of temporal data

### 2023-09-22 - v0.15
- Added details about asynchronous flow
- Documentation coherence improvements

### 2023-09-15 - v0.14
- Added definition of the security schemes
- Added clarifications about the request and responses flow
- Migrated the documentation to Markdown

### 2022-10-20 - v0.13
- Added clarifications about the order of tokens in the response

### 2021-05-10 - v0.12
- First version published on Github
- Clarified the headers needed for JSON and CBOR content
