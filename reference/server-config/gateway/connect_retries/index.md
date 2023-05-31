# connect_retries

/ [config](/reference/server-config/index.md) / [gateway](/reference/server-config/config/gateway/index.md) 

After how many failed connect attempts to give up establishing
a connection to a discovered gateway. Default is 0, do not retry.
When enabled, attempts will be made once a second. This, does not
apply to explicitly configured gateways.

*Default value*: `0`