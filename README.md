# Hyde-Protector
A .NET obfuscator, and code protector using Mono.Cecil

# Features
- Uses GetCallType as an indirect method to call the loading of the assembly
- Bruteforces its own decryption key upon runtime, to prevent hardcoding of it.
- Runs anti-VM checks on runtime
- Memory zeroing techniques
- Compresses, and encrypts bytes of payload

## Changelog
# Version 1.5
- Added more polymorphism
- Added anti-VM function
- Added 'memory zeroing' routine
- Converted stub to Window's Service (-3kb size)
- Consolidated functions (function merging)

# Version 1.4
- Added polymorphic string encryption to be injected into stub, for indirect calls.
- Added parameter & field name obfuscation.

# Version 1.3
- Added method name obfuscation.
- Changed payload transfer from hexadecimal to default encoding scheme.

# Version 1.2
- Added byte compression & option of compression level.
- Changed payload transfer to hexadecimal from base64.

# Version 1.1
- Removed encryption from base64 encoding to reduce payload size.
- UI Updated to light blue theme

# Version 1.0
- Released
- Basic Functionality
