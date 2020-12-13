# C2-JARM
A list of JARM hashes for different ssl implementations used by some C2 tools. Also adding other useful red team tools that use ssl (ex: EvilGinx2).

For more info on JARM hashing, check out the work by the Salesforce security team on their JARM github link here: https://github.com/salesforce/jarm

This is a neat way to fingerprint ssl servers by the software implementation. This alone would not be sufficient to detect C2 in a high fidelity manner, but JARM hashes coupled with other high value indicators would certainly be of value. This also highlights the need for red teams to ensure their C2 infra is not exposed for public access.

I plan to add more to this list over time. Feel free to contribute!!


| C2 TOOL |      SSL IMPLEMENTATION TESTED      |                           JARM HASH                            |                    LINK TO TOOL                  |
|---------|------------------------------|----------------------------------------------------------------|--------------------------------------------------|
| Mythic  | python 3 w/aiohttp 3 | 2ad2ad0002ad2ad00042d42d000000ad9bf51cc3f5a1e29eecb81d0c7b06eb | https://github.com/its-a-feature/Mythic          |
| Metasploit ssl listener | ruby 2.7.0p0 | 07d14d16d21d21d00042d43d000000aa99ce74e2c6d013c745aa52b5cc042d | https://github.com/rapid7/metasploit-framework |
| Cobalt Strike | Java 11 | 07d14d16d21d21d07c42d41d00041d24a458a375eef0c576d23a7bab9a9fb1 | https://www.cobaltstrike.com/ |
| Merlin | go 1.15.2 linux/amd64 | 29d21b20d29d29d21c41d21b21b41d494e0df9532e75299f15ba73156cee38 | https://github.com/Ne0nd0g/merlin |
| Deimos | go 1.15.2 linux/amd64 with github.com/gorilla/websocket package | 00000000000000000041d00000041d9535d5979f591ae8e547c5e5743e5b64 | https://github.com/DeimosC2/DeimosC2 |
| MacC2 | python 3.8.6 w/aiohttp 3 | 2ad2ad0002ad2ad22c42d42d000000faabb8fd156aa8b4d8a37853e1063261 | https://github.com/cedowens/MacC2 |
| MacC2 | python 3.8.2 w/aiohttp 3 | 2ad2ad0002ad2ad00042d42d000000ad9bf51cc3f5a1e29eecb81d0c7b06eb | https://github.com/cedowens/MacC2 |
| MacShellSwift | python 3.8.6 socket | 2ad000000000000000000000000000eeebf944d0b023a00f510f06a29b4f46 | https://github.com/cedowens/MacShellSwift |
| MacShell | python 3.8.6 socket | 2ad000000000000000000000000000eeebf944d0b023a00f510f06a29b4f46 | https://github.com/cedowens/MacShellSwift |
| Sliver | go 1.15.2 linux/amd64 | 2ad2ad0002ad2ad00041d2ad2ad41da5207249a18099be84ef3c8811adc883 | https://github.com/BishopFox/sliver |
| EvilGinx2 | go 1.10.4 linux/amd64 | 20d14d20d21d20d20c20d14d20d20daddf8a68a1444c74b6dbe09910a511e6 | https://github.com/kgretzky/evilginx2 |
