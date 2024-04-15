# Alt Model Api Documentation

## https://alt-new-model.fiddllepat.com/predict?user_id={user_id}
- Generic endpoint, returns a json with 3 values
```json
{
  "alt": 100,
  "longterm_alt": 0,
  "main": 0
}
```
- The one with the highest value is the classification
