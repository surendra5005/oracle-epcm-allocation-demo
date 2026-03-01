# Oracle EPCM Driver-Based Expense Allocation

## Overview
This project demonstrates a driver-based cost allocation model implemented in Oracle Enterprise Profitability and Cost Management (EPCM).

The solution includes:
- Model creation
- Rule set configuration
- Currency translation
- Allocation execution
- Validation of results

## Business Scenario
Corporate departments incur shared expenses such as Rent and Utilities. These costs are allocated to business units using occupancy square footage as the allocation driver.

## Key Features
- Currency conversion to USD reporting currency
- Utilities expense adjustment (15%)
- Driver-based allocation using Sq Ft
- End-to-end execution and validation

## Allocation Logic
Allocation is performed using the following approach:

Allocation % = BU Sq Ft / Total Sq Ft  
Allocated Cost = Source Cost × Allocation %

## Execution Flow
1. Model creation  
2. Rule set configuration  
3. Currency conversion  
4. Utilities adjustment  
5. Cost allocation  
6. Validation  

## Results
- Costs successfully allocated from corporate to business units  
- Driver-based logic applied correctly  
- Total cost consistency maintained  

## Learning Outcome
This project demonstrates practical implementation of allocation logic in EPCM, including rule sequencing, driver usage, and validation techniques.

## Author
Oracle ACE Apprentice Contribution
