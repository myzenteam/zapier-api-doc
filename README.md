# zapier-api-doc
API Documentation for Zapier

MyZenTeam has the following [Triggers](https://platform.zapier.com/docs/triggers) on the Zapier. The sample data format that will be received on the Zap is also given along with the event name.

## Events
### Application created
Sample data: 
```json
{
  "name": "Test User",
  "email": "test_user@gmail.com",
  "stage": "new",
  "job": "Developer at MZT"
}
```

### Application stage updated
Sample data:
```json
{
  "name": "Test User",
  "email": "test_user@gmail.com",
  "stage": "hired",
  "job": "Developer at MZT"
}
```
