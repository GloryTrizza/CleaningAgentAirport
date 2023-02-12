# CleaningAgentAirport

## Introduction
This project is aimed at designing a prototype of an automated vacuum cleaner that will be used to clean boarding gate areas in an airport. The airport normally outsources cleaning services, but in a bid to cut costs, they would like to make use of this automated cleaner. The cleaner should make the same number of visits as human cleaners and be able to monitor its performance throughout the day to optimize power consumption.

## Design Requirements
The prototype should make the same number of visits as human cleaners, i.e. checking the boarding gate areas after every two hours (throughout the day).

The vacuum cleaner should monitor its performance halfway through the day and make adjustments to its cleaning schedule based on the status of the rooms.

If the rooms were dirty in over 50% of the past six visits, the cleaning visits should be increased to every one hour. If the rooms were clean in over 50% of the past six visits, the cleaning visits should be reduced to every three hours.

