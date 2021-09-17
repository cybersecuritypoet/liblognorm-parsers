# OpenSSH Current
## General Info
|Software|Version|Is Current|
|--------|-------|----------|
|OpenSSH|7|
|OpenSSH|8|true|

## Parameters
|Param| |
|-|-|
|ID|1051|
|author|cybersecuritypoet|
|includes|authentication, network, encryption, general|

## Known problems
1. Usernames containing spaces are not parsed correctly, leading to the whole messages being unparsed. Currenly, no liblognorm parsing is possible.

## TODO
1. SFTP logs
2. Successful authentication logs
    * public key - publickey
    * password - password
    * host - hostbased
    * keyboard interactive - keyboard-interactive
    * GSSAPI - gssapi-with-mic
    * none - none (do we *REALLY* need that?)


## Help Needed
What we need:
1. GSSAPI authentication logs
2. SFTP logs
