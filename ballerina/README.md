## Overview

The MySQL Change Data Capture (CDC) driver enables capturing and tracking data changes in MySQL databases in real-time. It provides a reliable way to stream data modifications (Insert, Update, Delete) to downstream systems for processing or synchronization. The CDC driver is essential for building real-time data integration and synchronization pipelines.

### Key Features

- Real-time capturing of data changes (Insert, Update, Delete)
- Seamless streaming of data modifications to downstream systems
- Reliable tracking of database changes with minimal overhead
- Support for various CDC mechanisms and configurations
- Secure communication and efficient data handling
- GraalVM compatible for native image builds


This library provides the necessary Debezium drivers required for the CDC (Change Data Capture) connector in Ballerina. It enables listening to changes in MySQL databases seamlessly within Ballerina projects.

## Usage

To include the `mysql.cdc.driver` dependency in your project, simply import the module as shown below:

```ballerina
import ballerinax/cdc;
import ballerinax/mysql.cdc.driver as _;
```

The `mysql.cdc.driver` library is bundled with the required drivers, so no additional configuration is needed.
