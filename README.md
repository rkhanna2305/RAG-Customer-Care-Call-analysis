# RAG-Customer-Care-Call-analysis
Review Calls data from Customer and explains the customer behavior on basis of prompts
# Customer Care Call Data for Credit Lending Applications

This repository contains a synthetic dataset simulating customer care call logs for a credit lending application. The data is generated programmatically and is designed for machine learning and data analysis purposes, such as:

- Sentiment Analysis
- Call Classification
- Resolution Prediction
- Customer Behavior Analysis

## Dataset Overview

The dataset contains detailed records of customer care calls, including customer information, call details, issue types, resolution statuses, and notes taken by customer care agents. The data is saved in CSV format for easy integration with various tools and programming languages.

### Fields in the Dataset

| Field Name               | Description                                                                                 |
|--------------------------|---------------------------------------------------------------------------------------------|
| `CallID`                 | Unique identifier for each call.                                                           |
| `CustomerID`             | Unique identifier for each customer.                                                       |
| `CustomerName`           | Randomly generated customer names.                                                         |
| `CallTimestamp`          | Timestamp indicating when the call occurred.                                               |
| `IssueType`              | Type of issue reported by the customer (e.g., Loan Application Issue, EMI Calculation Assistance). |
| `IssueDescription`       | Detailed description of the issue.                                                         |
| `ResolutionStatus`       | Status of the resolution (e.g., Resolved, Pending, Escalated).                             |
| `ResolutionTimeMinutes`  | Time (in minutes) taken to resolve the issue (nullable for unresolved cases).               |
| `AgentID`                | Unique identifier for the customer care agent.                                             |
| `AgentPerformanceRating` | Performance rating of the agent handling the call (scale: 1.0 to 5.0).                      |
| `Notes`                  | Notes taken by the customer care agent during or after the call, providing additional context. |

### Example Record

```csv
CallID,CustomerID,CustomerName,CallTimestamp,IssueType,IssueDescription,ResolutionStatus,ResolutionTimeMinutes,AgentID,AgentPerformanceRating,Notes
A1B2C3D4E5,F1G2H3I4,"John Doe","2023-11-16 14:23:00","Loan Application Issue","Customer reported: Loan Application Issue.","Resolved",45,"X6Y7Z8",4.5,"Customer mentioned they were confused about Loan Application Issue. Agent explained the process in detail."
