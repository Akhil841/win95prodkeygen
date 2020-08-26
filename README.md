# win95prodkeygen
Generate your own OEM and CD keys for Windows 95!

The key generation algorithm for Windows 95 is rather simple, so I've documented it here.

It currently works as an API.

Dependencies:
- Python 3
  - random

To use it in your own scripts, simply download keygen.py and put it in the directory of your script, and then import it:
`from keygen import KeyGenerator`

To generate a CD key, use
`KeyGenerator.cd_key_gen()`

To generate an OEM key, use
`KeyGenerator.oem_key.gen()`

These keys should also work for Office 95.
**I, Akhil841, do not condone piracy. Use at your own risk. This is for educational and informative purposes only.**
