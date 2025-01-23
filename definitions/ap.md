# AP: The Addressing Protocol

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL
NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED",  "MAY", and
"OPTIONAL" in this document are to be interpreted as described in
RFC 2119.

Any computer compliant with AP MUST be addressed using the following system.

Any data using the AP protocol, MUST be sent over ComputerCraft modems.

## Addressing

A computer address MUST consist of the following sections:
- The computer's ID, as a positive integer
- The interface ID, as a positive integer

### Computer ID

The computer ID MUST be a positive integer and MUST be equal to the computer ID

As a computer can have multiple interfaces (wireless, wired), an interface ID is given for every interface

### Interface ID

The interface ID MUST be a string, and MUST consist of a type and num part.

The type MUST be any of the following:
- wired
- wireless
- ender
- nat

The num part MUST be an integer

`type:id`

## Packet structure

An AP packet MUST be a table and MUST have the following fields:
- Destination address
- Destination interface
- Source address
- Source interface