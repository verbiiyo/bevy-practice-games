# bevy-practice-games
I'm learning how to use bevy- since I'm new to rust and haven't developed games in a long time, I figured I would create a catch-all repo for some random creations.

Apparently if you're on windows you have to do `$env:WGPU_BACKEND="vk"; cargo run`?
This wasn't necessary when running the code from within bevy's repo... externally it's necessary???

# bevy_window spam
For some reason on my ally x, I saw some spamming messages about the window opening and closing, the way I fixed it was to select vulkan as the backend?
`$env:WGPU_BACKEND="vk"; cargo run --bin cursor`