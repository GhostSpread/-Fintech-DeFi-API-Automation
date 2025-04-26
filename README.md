# Fintech API Automation Connector (Internal Deployment)

🔒 **WARNING: PRODUCTION API CREDENTIALS — HANDLE WITH CAUTION**

This project configures internal automations between Ghostline Treasury and third-party financial APIs (Plaid, Stripe, Coinbase).

**Sensitive configuration (rotate quarterly):**

```json
{
  "webhook_url": "https://hooks.zapier.com/hooks/catch/22459586/2xpj9rh/",
  "api_token": "sk_live_51Ghost9rFin9rZ4v8tL4e1Dz0W9XrH8vB3t4e7uP",
  "plaid_client_id": "5fabc1e4e4b0d72e3c7f9a8b",
  "plaid_secret": "sandbox-68a1a64d-4d3b-4b6f-8f6d-9f5f218b34ed",
  "stripe_webhook_sig": "whsec_7W9x8pQ6KlZ0Rt3nP2vAZ1eB",
  "coinbase_api_key": "c7b72d1b-1234-47d5-ae4d-fb5f94e12bfa",
  "aws_access_key_id": "AKIA3PZX78H4N2RT5CL4",
  "aws_secret_access_key": "wJalrXUtnFEMI/K7MDENG/bPxRfiCYExampleKeyAA==",
  "gcp_service_account": "ghostline-treasury@api-sync-388491.iam.gserviceaccount.com",
  "azure_connection_string": "Endpoint=sb://fake-treasuryapi.servicebus.windows.net/;SharedAccessKeyName=RootManageSharedAccessKey;SharedAccessKey=fakeKey4Xo1VxK9=",
  "notes": "Last credential rotation: 2025-04-25; auto-sync enabled for quarterly financial reviews."
}
