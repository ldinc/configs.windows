# Issues

## Electron apps change window size after sleep

[Original thread](https://answers.microsoft.com/en-us/windows/forum/all/solved-windows-10-resizing-open-app-windows-after/7c4ab0f1-e550-47d9-9531-649eed3d3e1e)

`
In previous post I mentioned, that I DELETED all configurations under HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\GraphicsDrivers\Configuration . I was close to solution, would not need to delete these keys, but rather only edit "the right one" and change X and Y values to resolution of my monitor under one of the NOEDID_\00.... subkeys:


PrimSurfSize.cx = 2560 (decimal)

PrimSurfSize.cy = 1440  (decimal)


I am not sure how to indetify the right key in case you have the same problem, some report its name begins with "SIMULATED_" and in my case name bagins vith "NOEDID_", tehn navigate to 00 subkey and find your values to edit.
`