# PoC: BadappleVita, but it's system application

aka version of BadappleVita that can be started simultaneously with the game application in the background.

Use [NoSharedFb plugin](https://github.com/GrapheneCt/NoSharedFb) to bypass framebuffer problems when resuming from LiveArea.

TODO: reduce number of threads, switch to system core -> allow to run in background.

Another thing using monorale engine that originally made for Badapple3ds.

I am not sure this is the thing.

Greetz to @Princess-of-Sleeping @TakuyaKousaka.

# How to Build

Use vitasdk to build application. After building, boot params of the application have to be set manually in executable.
