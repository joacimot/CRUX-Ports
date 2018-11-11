# CRUX-Ports

To download individual ports with httpup, visit [my entry][1] in the CRUX
port db. Install [the sync file][2] to /etc/ports if you wish to download
the entire repository.

```
# curl "https://crux.nu/portdb/?a=getup&q=joacim" -o /etc/ports/joacim.httpup
# ports -u joacim
```

[1]: http://crux.nu/portdb/?a=repo&q=joacim "CRUX portdb"
[2]: http://crux.nu/portdb/?a=getup&q=joacim "joacim.httpup"
