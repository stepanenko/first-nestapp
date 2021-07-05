### Serialization

Serialization is a process that happens before objects are returned in a network response.
This is an appropriate place to provide rules for transforming and sanitizing the data to be returned to the client.
For example, sensitive data like passwords should always be excluded from the response.
Or, certain properties might require additional transformation, such as sending only a subset of properties of an entity.
Performing these transformations manually can be tedious and error prone, and can leave you uncertain that all cases have been covered.

https://docs.nestjs.com/techniques/serialization
