# API Documentation

## Endpoints
### Request Intake
- **Description**: Collect, validate and normalize sensors from Payment System; attach a runId and timestamp for traceability.
- **Type**: Processing

### API Discovery
- **Description**: Execute api discovery phase for the Tool-Use pattern: persist interim state, enforce guardrails, and emit structured JSON results.
- **Type**: HTTP Request

### Tool Execution
- **Description**: Execute tool execution phase for the Tool-Use pattern: persist interim state, enforce guardrails, and emit structured JSON results.
- **Type**: Processing

### Intake
- **Description**: Intake across joined datasets; branch on thresholds using decision gates; write metrics (success/error counts) for observability.
- **Type**: Processing

### Field Inspection
- **Description**: Field Inspection across joined datasets; branch on thresholds using decision gates; write metrics (success/error counts) for observability.
- **Type**: Processing

### Eligibility Determination
- **Description**: Eligibility Determination across joined datasets; branch on thresholds using decision gates; write metrics (success/error counts) for observability.
- **Type**: Processing

### Scheduling
- **Description**: Scheduling across joined datasets; branch on thresholds using decision gates; write metrics (success/error counts) for observability.
- **Type**: Processing

### Background Check
- **Description**: Background Check across joined datasets; branch on thresholds using decision gates; write metrics (success/error counts) for observability.
- **Type**: Processing

### Decision Support
- **Description**: Decision Support across joined datasets; branch on thresholds using decision gates; write metrics (success/error counts) for observability.
- **Type**: Processing

### Citizen Notification
- **Description**: Assemble final payload with status, artifacts, KPIs and audit trail; store to GIS; return response JSON for the client.
- **Type**: Processing
