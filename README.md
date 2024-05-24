# adaptive-transaction-confirmation

The Adaptive Confirmation Channel (ACC) System dynamically selects the best communication channel based on user preferences and current network conditions. This ensures that the confirmation is sent via the most efficient and reliable channel at the time of the transaction.

## Features
- Stores and retrieves user preferences for confirmation channels.
- Collects context data to evaluate network conditions and device status.
- Selects the optimal confirmation channel based on real-time data.
- Sends confirmation messages through App, Email, or SMS.

## Prerequisites
- `psutil` library for network status monitoring.
- Replace placeholder methods for sending notifications and retrieving user preferences with actual implementations.

## Usage

### User Preference Storage
Replace with your preferred storage method.
```python
from user_preferences import get_user_preference, set_user_preference
