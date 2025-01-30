# devex-docker
Docker Compose configuration

**Raw notes**

`New-NetFirewallRule -DisplayName "Allow DNS Requests" -Direction Inbound -Protocol UDP -LocalPort 53 -Action Allow`

`New-NetFirewallRule -DisplayName "Allow DNS Requests" -Direction Inbound -Protocol TCP -LocalPort 53 -Action Allow`

`Get-NetAdapter | Where-Object { $_.Status -eq "Up" }`

`Set-DnsClientServerAddress -InterfaceAlias "Wi-Fi" -ServerAddresses ("127.0.0.1", "8.8.8.8")`


`Set-DnsClientServerAddress -InterfaceAlias "Wi-Fi" -ServerAddresses "::1","2001:4860:4860::8888"`


`Get-DnsClientServerAddress -AddressFamily IPv4`
`Get-DnsClientServerAddress -AddressFamily IPv6`

`nslookup sqlserver.local`
`nslookup redis.local`


Reset the System?
