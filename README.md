# Go Python
This repo is a work in progress and may be abandoned, who knows!

![Golang Gopher vs Python Python](https://github.com/actes2/go_python/blob/main/go_python_logo.png?raw=true)
## Why make my own solution

Because I feel like a lot of various solutions and setups to this exact connundrum are overcomplicated, and realistically we can get this cranked out with much less effort.

Pip is weird and I haven't seen anyone do it right

Possibly venv or poetry support? We'll see.

## Gameplan

* We're going to get python embedded into Go.

* We're going to crank out some OS recognition and make this able to float through:
  * x64 windows
  * x64 linux
  * x32 linux
  * arm64 linux
  * arm32 linux
  > Bonus DLC maybe we'll throw on some Darwin love.

At this point, we'll see what's going on - probably some github actions to keep my automation pumping out active embeddable things from python.org
