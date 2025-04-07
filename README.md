> [!WARNING]
> You are most likely going to be banned since this is detected by Byfron. Use an alt account while running XenoPlus. Use the repository to understand what's happening and how it works.
> XenoPlus is not liable for any bans

# XenoPlus
The goal for XenoPlus is to create a safe, open-source executor for Roblox.

Feel free to add any pull-requests for XenoPlus

It uses the common method of writing unsigned bytecode into a Roblox core module script to manage execution, also more stable and flexible than most executors that has used this exact method.

## Features
- Fast execution
- Multi-instance compatibility
- Supports executing most scripts including Lua Armor scripts
- Uses extremely fast virtual filesystem that syncs to the external
- No in-game performance change & no high CPU usage
- Custom functions like HttpSpy, getting the real address of a Instance, setting & getting globals across all clients, and spoofing instance

This executor has many **vulnerabilities!**

## Dependencies
This project uses the following libraries:

- [**httplib**](https://github.com/yhirose/cpp-httplib)
- [**xxhash**](https://github.com/Cyan4973/xxHash)
- [**zstd**](https://github.com/facebook/zstd)
- [**openssl**](https://github.com/openssl/openssl)

Dependencies are managed with [**vcpkg**](https://github.com/microsoft/vcpkg). Install them with this command:
```sh
vcpkg install xxhash zstd openssl
```

The proper version of **httplib** is already included inside this project

### Credits

Thank you **Riz-ve** for the source.

Thank you [**Incognito**](https://github.com/Incognito-Roblox/Incognito) for the method.

Thanks to others that has helped me with decompressing, and compressing the bytecode.

Thanks to the [**Init script**](https://github.com/plusgiant5/TaaprWareV2/blob/main/Release/bin/InitScript.lua) of [TaaprWareV2](https://github.com/plusgiant5/TaaprWareV2/) by plusgiant5

Thanks to [**nhisoka**](https://github.com/nhisoka) for helping me out at the start of this project
