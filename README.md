# gmlm_ascii85
 Ascii 85 Encoding in Pure Lua

## Example:
```lua
	require("ascii85")
	local str = "PrikolMen:-b"
	local enc = ascii85.encode( str )
	local dec = ascii85.decode( enc )

	print( enc, dec )
 ```
 
 ### Result:
 ```
 <~:i^8cDer-ZDE9@Y~>	PrikolMen:-b
 ```
