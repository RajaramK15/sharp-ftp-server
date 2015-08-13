### 959 ###
```
ACCT <SP> <account-information> <CRLF> - Partial
SMNT <SP> <pathname> <CRLF> - Not Implemented
STRU <SP> <structure-code> <CRLF> - Partial
MODE <SP> <mode-code> <CRLF> - Partial
ALLO <SP> <decimal-integer> - Partial
	[<SP> R <SP> <decimal-integer>] <CRLF>
REST <SP> <marker> <CRLF> - Not Implemented
ABOR <CRLF> - Not Implemented
NLST [<SP> <pathname>] <CRLF> - Not Implemented
SITE <SP> <string> <CRLF> - Not Implemented
STAT [<SP> <pathname>] <CRLF> - Not Implemented
HELP [<SP> <string>] <CRLF> - Not Implemented
```

### 2228 ###
```
AUTH <SP> <mechanism-name> <CRLF> - Implemented for TLS
ADAT <SP> <base64data> <CRLF>
PROT <SP> <prot-code> <CRLF>
PBSZ <SP> <decimal-integer> <CRLF>
MIC <SP> <base64data> <CRLF>
CONF <SP> <base64data> <CRLF>
ENC <SP> <base64data> <CRLF>
```

### 2389 ###
```
FEAT
OPTS
```

### 3659 ###
```
MDTM
SIZE
REST
TVFS
MLST
MLSD
OPTS
```