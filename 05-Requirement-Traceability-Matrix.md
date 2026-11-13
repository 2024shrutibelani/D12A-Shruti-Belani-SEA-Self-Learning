
# Requirement Traceability Matrix (RTM)

## 1. Introduction

Requirement Traceability Matrix (RTM) is a document used in Software Engineering to track and manage software requirements throughout the software development life cycle.

It helps ensure that every requirement is properly implemented and tested.

RTM connects requirements with their corresponding design, development and testing activities.

## 2. What is Requirement Traceability Matrix?

A Requirement Traceability Matrix is a table that maps each software requirement to its related test cases.

It helps the development team verify whether all requirements are covered during testing.

### Objectives of RTM

- Ensure that all requirements are implemented.
- Track requirements throughout the project.
- Identify missing requirements.
- Verify test coverage.
- Reduce the chances of missing important features.
- Maintain proper documentation.

## 3. Types of Requirement Traceability

### 1. Forward Traceability

Forward Traceability tracks requirements from their initial documentation to design, development and test cases.

It ensures that every requirement is implemented and tested.

### 2. Backward Traceability

Backward Traceability tracks test cases and implementation activities back to their original requirements.

It ensures that unnecessary features are not developed.

### 3. Bidirectional Traceability

Bidirectional Traceability combines forward and backward traceability.

It ensures that every requirement is covered by test cases and every test case is linked to a valid requirement.

## 4. Structure of a Requirement Traceability Matrix

An RTM generally contains the following columns:

| Column Name | Description |
|:---|:---|
| Requirement ID | Unique identification number of a requirement. |
| Requirement Description | Details of the software requirement. |
| Module | Software module related to the requirement. |
| Design Reference | Related design or specification reference. |
| Test Case ID | Unique identification number of the test case. |
| Test Status | Indicates whether the test passed or failed. |

## 5. Practical Example of RTM

### Project: Online Shopping Application

Suppose we are developing an Online Shopping Application.

The application contains features such as user registration, login, product search, shopping cart and order placement.

The following RTM connects these requirements with their test cases.

| Requirement ID | Requirement Description | Module | Design Reference | Test Case ID | Test Status |
|:---|:---|:---|:---|:---|:---|
| REQ-01 | User should be able to register. | Registration | DES-01 | TC-01 | Pass |
| REQ-02 | User should be able to log in. | Login | DES-02 | TC-02 | Pass |
| REQ-03 | User should be able to search products. | Product Search | DES-03 | TC-03 | Pass |
| REQ-04 | User should be able to add products to cart. | Shopping Cart | DES-04 | TC-04 | Pass |
| REQ-05 | User should be able to place an order. | Order | DES-05 | TC-05 | Pending |

Note: The above is an illustrative RTM for an example project.

## 6. Steps to Prepare an RTM

1. Collect all project requirements.
2. Assign a unique ID to each requirement.
3. Write a clear description of every requirement.
4. Identify the related software modules.
5. Connect requirements with design references.
6. Create test cases for each requirement.
7. Record the testing status.
8. Update the matrix whenever requirements change.

## 7. Advantages of RTM

- Improves requirement management.
- Ensures complete test coverage.
- Helps identify missing requirements.
- Makes project tracking easier.
- Improves communication between developers and testers.
- Helps manage changes in requirements.
- Supports software quality assurance.

## 8. Limitations of RTM

- Requires regular maintenance.
- Can become complex for large projects.
- Takes time to prepare and update.
- Incorrect mapping can lead to tracking errors.

## 9. Tools Used for Requirement Traceability

Some commonly used tools are:

1. IBM Engineering Requirements Management DOORS.
2. JIRA.
3. Azure DevOps.
4. Jama Connect.
5. Helix ALM.

These tools help teams document requirements, manage changes and maintain traceability.

## 10. Conclusion

Requirement Traceability Matrix is an important tool in Software Engineering.

It connects software requirements with design and testing activities and ensures that all requirements are properly covered.

RTM helps improve project tracking, testing coverage and software quality.

## 11. References

1. IBM - Engineering Requirements Management DOORS.
   https://www.ibm.com/products/engineering-requirements-management-doors

2. Atlassian - Jira.
   https://www.atlassian.com/software/jira

3. Software Engineering - Requirements Traceability Concepts.
