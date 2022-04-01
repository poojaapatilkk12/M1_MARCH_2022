# Requirements

## Introduction

-   A student record management software is a tool that tracks and records regular activities of the students in institutes including attendance, exam performance, and their behavior.
-   The software can be accessed by students, teachers, admin and parents with a role-based login. It collects all the student data along with their personal information which can be easily searched and retrieved later on. The software stores years of data online on a cloud platform.
## Objective of the system

-   The main objective of the student record management system is to provide a tool to efficiently record all data necessary, and also sort it.
-   The people using it only have to choose what they have to do, and enter the data,everything else is taken care of by the program.

## Features proposed in the current system

- Easy Report Generation
- The software helps to generate reports easily in required formats Data Search and Retrieval
- The system can help users to find and retrieve student’s data over a few clicks High Data Storage
- The system stores large amounts of data without hampering its functioning Role-Based Access
- The software offers role
- based access to the teachers, students, and parents Attendance Management
- Attendance Management
- It helps to record daily attendance automatically using a biometric attendance system Easy to Use
- The system is easy to use and highly intuitive by all types of individuals


## SWOT ANALYSIS

**STRENGTHS** 
- The system can provide data in sufficient time and in appropriate structure according to management requirements.
- It is suitable for preparing immediate reports from source systems with daily data loading.

**WEAKNESSES**
- Data purity of source systems is dubious; the number of administrators of source systems is particularly high.
- Support of the system depends to a large extent on the vocation of the management.

**OPPORTUNITIES **
- Scalable source systems enable the creation of complex queries building on several source systems.
- Interconnection of information from different processes and topics is provided due to integrated operation, it can support management decisions by creating   multidimensional data models.

**THREATS**
- Public sector leaders are still less motivated in daily usage of MIS.
- Data loading from source systems are done manually and infrequently in certain cases and it has a negative impact on the availability of MIS reports.

# 3W&#39;s and 1&#39;

## Who:

-   Banks.

## What:

-   An automated system to record, organise and maintain data for banks.

## When:

-   When Banks are crowded and staff to customer interactions are at an height, this system allows user to perform simple transactions on this system.

## How:

-   Effectively organises and maintains data which in return allows easy accessibility.

# Detail requirements

## High Level Requirements:

| ID   | Description                                              | Category  | Status      |
| ---- | -------------------------------------------------------- | --------- | ----------- |
| HR01 | User shall be able to login                              | Techincal | IMPLEMENTED |
| HR02 | Admin shall be able to login                             | Techincal | IMPLEMENTED |
| HR03 | User shall be able to create account.                    | Techincal | IMPLEMENTED |
| HR04 | User shall be able to update existing account            | Techincal | IMPLEMENTED |
| HR05 | User shall be able to perform transactions               | Techincal | IMPLEMENTED |
| HR06 | User shall be able to check details of existing account  | Techincal | IMPLEMENTED |
| HR07 | Admin shall be able to remove existing account           | Techincal | IMPLEMENTED |
| HR08 | Admin shall be able to view customer list                | Technical | IMPLEMENTED |
| HR09 | Logs will be maintained                                  | Scenario  | FUTURE      |
| HR10 | Admin shall be able to perform rollbacks of transactions | Technical | FUTURE      |

## Low level Requirements:

| ID   | Description                                                                                                                                                                    | HLR ID | Status (Implemented/Future) |
| ---- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------ | --------------------------- |
| LR01 | (1). New account shall be added by providing all the asked information (2). Id should be unique and validated from persistant file or else new account should not be accepted. | HR03   | IMPLEMENTED                 |
| LR02 | Must be able to login as User.                                                                                                                                                 | HR01   | IMPLEMENTED                 |
| LR03 | Must be able to login as Admin                                                                                                                                                 | HR02   | FUTURE                      |
| LR04 | If user tries to create an existing account then the system doesn't allow                                                                                                      | HR03   | IMPLEMENTED                 |
| LR05 | User can only update an existing account                                                                                                                                       | HR04   | IMPLEMENTED                 |
| LR06 | User needs to enter account number to perform transation, and if the account doesn't exist then it shows 'No record found'                                                     | HR05   | IMPLEMENTED                 |
| LR05 | User shall be able to check details of only existing account using account_number/name, if it doesn't exist then it shows 'No record found'                                    | HR06   | IMPLEMENTED                 |
| LR06 | Admin shall bew able to remove existing account on basis of account number, else 'Record not found'                                                                            | HR07   | IMPLEMENTED                 |
| LR07 | Admin shall be able to view all customer list in tabular format                                                                                                                | HR08   | IMPLEMENTED                 |

