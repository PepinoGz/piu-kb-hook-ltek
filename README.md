# Pump It Up Keyboard and Ltek usb pad Hook

Tool that allows you to use your keyboard on Pump It Up and also Ltek Dance mat PIU EX PRO Metal 2

Tested on NX2, NXA, Fiesta 1, Fiesta 2, Fiesta EX, Prime 1 and Prime2. To modify the keys, edit the `binds` list in `hook.cpp`.

# Usage
Download the pre-compiled binary or compile it, then add it to LD_PRELOAD before executing Prime.

# Default keys
F1 for test, F2 for service, F5 for player 1 coin, F6 for player 2 coin

Pad layout:
```
Q   E   7   9
  S       5
Z   C   1   3
Pad 1   Pad 2
```

# Compiling

Requires an atleast C++11 compliant compiler.

To compile it yourself, run these commands:

```
sudo apt-get install git build-essential libx11-dev
git clone https://github.com/PepinoGz/piu-kb-hook-ltek
cd piu-kb-hook-ltek
make
```

You'll now have a `hook.so` file in the aforementioned directory.
