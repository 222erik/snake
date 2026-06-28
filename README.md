# Snake Game 🐍
Simple game that works the same as Google Snake. Written in C++, pixelart included.

## Features
- 🌈 Pixelart
- 👋 Animations
- 👽 Teleport between walls
- 🖥️ Cross-platform (except Mac)
- 〽️ Low cpu and mem usage
- 🐍 Works like Google Snake

## How to play 👾
Like google snake. You move the snake with the arrow or WASD keys. The goal is to eat as many apples as possible. If you eat the apple, the snake grows. The only way to lose is by hitting yourself, because the walls just teleport you to the other side. If you want to exit the game, press Escape. There's no pause button yet.

## Download and install
To play the game, download it for your platform by clicking the **tags** button and then the latest release. Download the right .zip file and extract it. Run the executable. Your computer might give out a warning, it is safe to ignore.

### How to download it
- Click the **tags** button
- Click on the latest release
- Download the .zip for your platform
- Extract the .zip
- Run the executable

## Pixelart 🌈
This game uses basic pixelart. If you want to improve it or make your own, you are free to do so.

![snake_tail](resources/PNG/tail600.png)![snake_body](resources/PNG/body600.png)![snake_head](resources/PNG/head600.png)
![apple](resources/PNG/apple600.png)

## Compile
You don't need to compile this, there are precompiled binaries available. If you really want to compile it, run the following commands:
```bash
mkdir build
cd build
cmake ..
cmake --build .
```
Then execute it:
```bash
./build/snake
```

## Licence
![MIT](LICENSE)
