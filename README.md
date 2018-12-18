# http-communication-examples
Examples of how to pass data using http requests

# Useful Links:

# Json TypeNameHandling
https://stackoverflow.com/questions/12638741/deserialising-json-to-derived-types-in-asp-net-web-api/12641541
https://stackoverflow.com/questions/20408771/json-net-abstract-derived-class-deserialization-with-webapi-2
https://stackoverflow.com/questions/14124189/can-i-pass-an-interface-based-object-to-an-mvc-4-webapi-post
https://stackoverflow.com/questions/38463547/how-to-pass-abstract-class-to-asp-net-webapi-using-json-formatter
https://stackoverflow.com/questions/20060495/readasasync-error-type-is-an-interface-or-abstract-class-and-cannot-be-inst
https://stackoverflow.com/questions/31454712/ef-tph-inheritance-lost-in-web-api-json
https://stackoverflow.com/questions/37282014/webapi-custom-model-binding-of-complex-abstract-object

https://stackoverflow.com/questions/42996144/typenamehandling-with-attribute-on-a-class
For this link this is the useful part `[JsonProperty(ItemTypeNameHandling = TypeNameHandling.Auto)]`

## Json Security
https://stackoverflow.com/questions/49038055/external-json-vulnerable-because-of-json-net-typenamehandling-auto

Using any NameTypeHandling other than None can increase the attack surface area on the api as it exposes the internal structure of the assembly.
