# CreCrossX-Reversed
Its late i could make this better but i got work in the morning so i'll write up better and clean up the post about this ai slop fest later at some point




# Telemetry
VRC id, name, id, fps, ping, thumbnailUrl | Proc ID  | module version | loader version | Keybinds 

These are pushed to crecross.com in 5s intvls



#Security

- Resource Examples
_cvm.strings | For strings
_cvm.data | For methods
CrelenVM.ExternalKey.v1 | Keyshizle

loads blabla into le AppDomain, but you can still use old keys locally just fine which kinda defeats the purpose :D
``` provider = AppDomain.CurrentDomain.GetData("CrelenVM.KeyProvider.v1") ```
Keys last once given like 15m but again old ones are accept no matter what locally so heyyyy flaw in vibecoded obfuscator


Just memein
```
if Environment.GetEnvironmentVariable("CRELEN_PROTECTED_RUNTIME") == "crelen-guard-v1"
```

Callin this in the big 26 as a csharpian
```
Debugger.IsAttached
IsDebuggerPresent()
CheckRemoteDebuggerPresent(GetCurrentProcess(), out b)
NtQueryInformationProcess(ProcessDebugPort = 7)
NtQueryInformationProcess(ProcessDebugObjectHandle = 30)
NtQueryInformationProcess(ProcessDebugFlags = 31) == 0
```

Blocking this when "injected" doesnt really work when your dll isnt doing anything chat what are we doing
```
frida-agent.dll, frida-gadget.dll, frida-agent-64.dll, scyllahidehookx64.dll, scyllahidehookx86.dll, titanhide.dll, vehdebug-x86_64.dll, vehdebug-i386.dll, dbk64.dll, dbk32.dll
```


I wish his super hero hardcore Protected runtime would have gave me this error
```
log "[CreClient] Protected runtime integrity check failed. CreClient remains unloaded."
```



300s heartbeattttt gets vrc id, name | source,version, and last seen

```
POST https://crecross.com/api/creclient/users/heartbeat
User-Agent: CreClientX
Content-Type: application/json
```


# Slop time

Might get put offline but here are some of those naughty users in there
- usr_09497af5-2a0c-444f-8fae-8753cdad8681
- usr_23de258c-5177-42d7-9c7b-e2498512d5ac
- usr_25447763-8b3c-4b96-9fb7-c390a96479bf
- usr_31ec508c-f518-43ca-bccd-07c04f1e133c
- usr_5d9e248f-4054-4fc5-9c07-e8d714e90ad2
- usr_7ce3c4a9-aaca-4a25-8ee3-6b65bb38d7ac
- usr_8493740a-68bd-4f27-85a5-0a3c018b090d
```
https://crecross.com/api/creclient/users
```


avatar search
```
https://api.crecross.com/avatars/v2/search?q=
```


files !!
```
https://www.crecross.com/creclient/assets/button-icons-v2.zip
https://www.crecross.com/creclient/assets/cre-nav-button.png
https://www.crecross.com/creclient/assets/cre-grey-square.png
https://git.sexparty.cc/Crecross/creclientv2/-/raw/master/CreClientX/CreRPC.zip
https://astroswrld.club/ValorClient/Images/World.png
```


This url with more users + crediddys accounts
```
https://raw.githubusercontent.com/Issetsum/CCBL/refs/heads/main/CCPRV

usr_c2380690-1d25-40a2-aebd-a773fe230e7b
usr_9a51f728-d365-409d-8a8b-f0efcedca052
usr_fb3812b9-47fb-4ef0-9910-48165903f672
usr_112d1608-5b45-47e6-99fe-f576226e7efd
usr_92c162f3-067e-4ef7-bc51-0cf270b56aeb
usr_5a7bd931-4c11-4f6f-a9ef-1476fdd706d6
usr_34584e51-fb77-49f9-a0e5-b62160556a1f
usr_d1d790a9-a0d8-4fa5-99e2-ecca5bb60f32
usr_8b4441a8-ecf8-4793-8abf-63597604ebea
usr_923643e1-24d7-4916-91cb-a9a98f0e7939
usr_b673fa1b-508b-48aa-b647-8feaec06900b
usr_c9f34402-0a28-4c09-b5bd-f17a63baa5a9
usr_d7c5b4a5-93ba-4013-8071-c575c46b6463
usr_7a50ce66-e086-48b6-b258-0bf6f8415347
usr_2dcb8ac2-15eb-4b2b-aa49-18bfbf80b77d
usr_6e01dc64-73bb-4936-8145-b3b761192d1f
usr_9f59266f-e7ce-48ff-841f-52ff62bb7b78
```





