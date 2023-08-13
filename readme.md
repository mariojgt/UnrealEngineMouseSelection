# Unreal Engine Mouse Selection Project

Welcome to the **Unreal Engine Mouse Selection Project** repository! This project allows you to use the mouse to select actors within the game environment. This can be particularly useful for creating interactive and dynamic experiences within Unreal Engine.

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Demo
![Mouse Selection Demo](https://raw.githubusercontent.com/mariojgt/UnrealEngineMouseSelection/main/imgs/feature.png)
Check the implementation in the third person character it contains the mouse selection component and the mouse selection widget.

## Simple Event
![Mouse Selection Demo](https://raw.githubusercontent.com/mariojgt/UnrealEngineMouseSelection/main/imgs/img1.png)

## Selection Example
![Mouse Selection Demo](https://raw.githubusercontent.com/mariojgt/UnrealEngineMouseSelection/main/imgs/img2.png)
## Features

- Mouse-driven actor selection within the Unreal Engine environment.
- Responsive and intuitive user interface for selecting and interacting with actors.
- Customizable settings to adjust the behavior of the selection system.
- Optimized for performance and scalability.

## Installation

1. First in you scene add a post process volume and search for post process material and add the material click to add one and select M_Hightlight, this process will have so we can highlight the selected actor.

2: in the post process volume search infinite extend (unbound) that will make so the post process material will be visible in the entire scene.

3: in you player character add the BPC_DragSelection component.

More information please check the BP_ThirdPersonCharacter actor as it has all the logic implemented.
