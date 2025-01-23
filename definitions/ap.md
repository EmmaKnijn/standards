# AP: The Addressing Protocol

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL
NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED",  "MAY", and
"OPTIONAL" in this document are to be interpreted as described in
RFC 2119.

Any computer compliant with AP MUST be addressed using the following system.

Any data using the AP protocol, MUST be sent over one of the following 

The computer address is dependent on the following variables. If any of these variables is unknown, an address MUST NOT be assigned to the computer.
- Computer ID
- Connection Type
- Computer Location

The connection type MUST always be one of the following
| Type                     | ID  |
| ------------------------ | --- |
| Wired                    | 0   |
| Wireless (regular modem) | 1   |
| Wireless (ender modem)   | 2   |
| Wireless (websocket)     |     |

