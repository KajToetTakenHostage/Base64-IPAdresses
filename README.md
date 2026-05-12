# Base64-IPAdresses
IP Addresses (4 or 6) converted to Base64 that are opened with a bookmarklet.

This is to avoid use of evil DNS.

A bookmarklet can be used to translate the host IP address to Base64. A forwarder page can be used to redirect to the extracted IP address.

Instead of a hosted forwarder page, a bookmarklet can be used with a prompt for the Base64 string.

An IPv4 address take 5 characters in Base64. An IPv6 address takes 20 characters in Base64.

JS' "location.host" could be used to get the IP address, along with a third party that retreives the IP address from the host. The third party should buffer the domain lookup (?)
