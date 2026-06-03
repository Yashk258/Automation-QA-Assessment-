# Automation & QA Assessment

## Task 2 - n8n Workflow

### Overview

This workflow fetches popular GitHub repositories, enriches repository data using a second API request, applies conditional routing, and prepares structured output.

### Workflow Steps

1. Schedule Trigger
2. GitHub Search API Request
3. JavaScript Data Transformation
4. GitHub Repository Details API Request
5. IF Condition for routing
6. Edit Fields output formatting

### Error Handling

* Retry on Fail enabled
* Error outputs configured on HTTP Request nodes

### Deliverables

* Workflow JSON export
* Workflow screenshots
* Successful execution screenshots
