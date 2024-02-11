Dice Randomizer App

## Introduction
The Dice Randomizer app is a simple iOS application developed using Swift and UIKit. It allows users to simulate rolling two dice by randomizing the images of the dice displayed on the screen.

## How It Works
The app consists of a single view controller that contains two UIImageViews for displaying the dice images. When the user taps the "Roll" button, the app randomly selects an image for each dice from a predefined array of dice images and updates the UIImageViews accordingly.

## Code Documentation
### ViewController.swift
- **Outlets**: 
    - `diceImageView1`: UIImageView outlet for displaying the image of the first dice.
    - `diceImageView2`: UIImageView outlet for displaying the image of the second dice.

- **Actions**:
    - `rollButtonTouched`: Method triggered when the roll button is touched. It randomizes the dice images and updates the image views accordingly.

## Usage
To use the app, simply clone the repository and open the Xcode project file. Build and run the project on a simulator or a physical iOS device. Tap the "Roll" button to simulate rolling two dice and observe the randomized dice images.

## Tech Stack
- Swift programming language
- UIKit framework

<img width="515" alt="Dice" src="https://github.com/Aziza0508/DiceGame/assets/112758271/4c21330c-1ea8-4e25-9f77-ef6493e2d36f">
