# sysctl

> Access kernel state information

- Show all available variables and their values

`sysctl -a`

- Show Apple model identifier

`sysctl -n hw.model`

- Show CPU model

`sysctl -n machdep.cpu.brand_string`

- Show available CPU features (MMX, SSE, SSE2, SSE3, AES, etc)

`sysctl -n machdep.cpu.feature`

- Set a changeable kernel state variable 

`sysctl -w name=value`
`sysctl -w kern.maxfiles=15000`
