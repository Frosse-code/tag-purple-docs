## About the tags
TagPurple tags are a type of NFC tag that have a clever security feature.
Each time a tag is tapped, a counter is incremented and a cryptographic signature is generated from a key on the tag, using the tags unique identifier and the current counter as inputs.
In this way, every tap can be verified as a unique real tap on a known TagPurple tag, registered by you to one of your locations.

## Confidence in the data
TagPurple provides an audit trail of **who** was **where** **when**.
### Who - The Tapper
Before any user can tap-in, they must authenticate by following a link sent to them in an SMS message. This authentication process generates a session that will be usable for 30 days, before they must repeat the authorisation. In this way, the phone number is used as the unique identifier for the tapper.
Therefore, in-as-much as SMS is secure and access to that phone isn't shared, strong evidence for tapper identity is provided by TagPurple.
### Where - Location
Assuming confidence in the tags inability to move location, the nature of the tag's security features (described above) give confidence that the TagPurple tag was really tapped at the registered location.
### When - Time
Ordinarily, as soon as a tapper taps, the request hits TagPurple servers and confirms the tap-in and the date and time is recorded. Because the counter is incremented predictable, and because it is cryptographically verified, we can have high confidence that an individual tap happened after the previous tap and before the subsequent one.
When a phone taps while offline, it will make its best effort to registered that tap when it comes back online, registering the time that it was originally tapped.
However, the precise timing could be manipulated by deliberately manipulating the time 
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTYxNTIzODE3NCwtMTAxNTMzOTM5Nyw5Nz
k5NTYzNzhdfQ==
-->