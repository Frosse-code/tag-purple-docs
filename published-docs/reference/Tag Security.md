## About the tags
TagPurple tags are a type of NFC tag that have a clever security feature.
Each time a tag is tapped, a counter is incremented and a cryptographic signature is generated from a key on the tag, using the tags unique identifier and the current counter as inputs.
In this way, every tap can be verified as a unique real tap on a known TagPurple tag, registered by you to one of your locations.

## Confidence in the data
### Location
Assuming confidence in the tags inability to move location, this security gives reasonable confidence that the TagPurple tag was really tapped at the registered location.
### Tapper
Before any user can tap-in, they must authenticate by following a link sent to them in an SMS message. This authentication process generates a session that will be usable for 30 days, before they must repeat the authorisation. In this way, the phone number as the unique identifier for the tapper, 
<!--stackedit_data:
eyJoaXN0b3J5IjpbMzY2MDQyMDgxLDk3OTk1NjM3OF19
-->