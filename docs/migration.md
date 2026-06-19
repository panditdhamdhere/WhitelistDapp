# Migration Guide
## Breaking Changes
The `removeAddress` function has been added to the Whitelist contract but does not currently remove the address as expected. When using this function, be aware that it will return the input address without modifying the whitelist.
## Steps to Migrate
1. Review the current implementation of the `removeAddress` function.
2. Be aware of the potential for unexpected behavior due to its incomplete implementation.