# CRUX-Ports

To download individual ports with httpup, visit [my entry][1] in the CRUX
port browser. Install [the sync file][2] to /etc/ports/ if you wish to
download the entire repository.

```
# curl "https://crux.nu/portdb/?a=getup&q=joacim" -o /etc/ports/joacim.httpup
# ports -u joacim
```

This repository uses signed ports, so please install [my public key][3] to
/etc/ports/ if you want to verify the integrity of my ports and downloaded
source files.

```
# curl "https://crux.nu/keys/joacim.pub" -o /etc/ports/joacim.pub
```

[1]: http://crux.nu/portdb/?a=repo&q=joacim "CRUX portdb"
[2]: http://crux.nu/portdb/?a=getup&q=joacim "joacim.httpup"
[3]: https://crux.nu/keys/joacim.pub "joacim.pub"
