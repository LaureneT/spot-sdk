<!--
Copyright (c) 2020 Boston Dynamics, Inc.  All rights reserved.

Downloading, reproducing, distributing or otherwise using the SDK Software
is subject to the terms and conditions of the Boston Dynamics Software
Development Kit License (20191101-BDSDK-SL).
-->

# API Example - Using the Robot State Service

This example program demonstrates how to query the robot state service for the hardware config, the current robot state, or the robot metrics.

## Setup Dependencies
This example requires the bosdyn API and client to be installed, and must be run using python3. Using pip, these dependencies can be installed using:

```
python -m pip install -r requirements.txt
```
As well, the program requires one of `{state, hardware, metrics}` as a command line argument to specify which robot state request to issue when running the example program.

## Running the Example
To run the example:
```
python get_robot_state.py --username USER --password PASSWORD ROBOT_IP {state,hardware,metrics}
```