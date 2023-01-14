# Codespaces Zig template

GitHub Codespaces template

<br><br><br><br>

Zig Language Server (zls)   
Formatter  
Debug

<br><br><br><br>




Set a version you prefer.  

Dockerfile
```Dockerfile
ARG ZIGVER="0.10.0"
ARG ZIGTARGET="linux-x86_64"
```

<br><br><br><br><br>


## Hello world

<br>

```shell
zig init-exe
```

<br>

src/main.zig
```
const std = @import("std");

pub fn main() !void {
    std.debug.print("Hello, {s}!\n", .{"World"});
}
```

<br>

```shell
zig build
zig-out/bin/workspace
```



<br><br><br>

### F5

debug

<br><br><br>
<br><br><br>
<br><br><br>







https://user-images.githubusercontent.com/10168979/212047336-1bac88ca-9097-4e72-a963-c9882ac4a958.mp4








<br><br><br><br><br><br>


### Right-click on the port and check in the browser

https://user-images.githubusercontent.com/10168979/209822293-ae2145f7-bcc5-4066-bfdf-ecd140e26d4d.mp4

**Port number is 8085, not 5900.**

<br><br><br><br><br><br>

## Check Codespaces usage

https://github.com/codespaces  

If you want to get it for free, make sure it's shut down after you use it.  
Delete useless containers!

To stop, click on codespeces and stop from the menu

![c](https://user-images.githubusercontent.com/10168979/209823266-8ae47f4e-f86e-44a7-a013-dd480fa6c3ad.png)

<br><br><br><br><br><br>
<br><br><br><br><br><br>





