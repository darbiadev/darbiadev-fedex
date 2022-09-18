# darbiadev-fedex

This package provides a wrapper for FedEx's API.

### Example usage

```python
from darbiadev_fedex import FedExServices

client = FedExServices(
    web_service_url="https://wsbeta.fedex.com/web-services",
    key="key",
    password="password",
    account_number="account_number",
    meter_number="meter_number",
)

print(client.track("500947581425"))
```
