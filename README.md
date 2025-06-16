markdown
# Financial Statements MCP Server

## Overview

The **Financial Statements MCP Server** is a robust solution for accessing standardized financial data for global companies. This server provides comprehensive access to companies' balance sheets, income statements, and cash flow statements, with historical data available for the past five years. The data is sourced from original filings, ensuring accuracy and reliability, and is accessible through intuitive endpoints.

## Features

- **Balance Sheet Statement**: Retrieve detailed balance sheet statements for companies, with all figures presented in thousands. This tool allows you to analyze the financial position of a company by examining assets, liabilities, and shareholders' equity.

- **Income Statement**: Access income statements to evaluate a company's profitability over a specified period. This includes revenue, expenses, and net income, presented in thousands and available on an annual basis.

- **Cash Flow Statement**: Obtain cash flow statements to understand the cash inflows and outflows from operating, investing, and financing activities. The data is presented annually, with numbers in thousands.

## Tool Descriptions

### Balance Sheet Statement
- **Function Name**: `balance_sheet_statement`
- **Description**: Get company balance sheet statement by year. All numbers are in thousands.
- **Parameters**:
  - `ticker`: A string representing the stock symbol of the company. This parameter is required.

### Cash Flow Statement
- **Function Name**: `cash_flow_statement`
- **Description**: Get company cash flow statement by year. Includes trailing twelve months (ttm) data. All numbers are in thousands.
- **Parameters**:
  - `ticker`: A string representing the stock symbol of the company. This parameter is required.

### Income Statement
- **Function Name**: `income_statement`
- **Description**: Get company income statement by year. Includes trailing twelve months (ttm) data. All numbers are in thousands.
- **Parameters**:
  - `ticker`: A string representing the stock symbol of the company. This parameter is optional.

## Subscription Plans

The Financial Statements MCP Server offers various subscription plans tailored to meet different needs:

- **BASIC**: Free access with limited features.
- **PRO**: Comprehensive access for more in-depth analysis at $10.00 per month.
- **ULTRA**: Additional features and higher usage limits at $25.00 per month.
- **MEGA**: Full access with premium support and capabilities at $250.00 per month.

## Performance

The server boasts an impressive 9.5 popularity rating and operates with a 71% service level. Users can expect an average latency of 1716ms, making it a reliable choice for financial data retrieval.

## Usage

To utilize the Financial Statements MCP Server, users can invoke the provided tools by specifying the appropriate parameters. This allows for seamless integration into various financial analysis workflows, enabling users to make informed decisions based on accurate financial data.

---
This README provides a concise overview of the capabilities and features of the Financial Statements MCP Server, offering users the tools necessary for detailed financial analysis.