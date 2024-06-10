# Unity 3D Camera and Movement Scripts

This repository contains Unity scripts for handling player movement and camera control in a 3D environment. The setup includes a player GameObject and a CameraHolder GameObject.

## Contents

- **Player Movement Script**: Handles player movement.
- **Camera Control Script**: Manages the camera's position and rotation relative to the player.

## Setup

### Player GameObject

1. **Attach Player Movement Script**: Ensure that the player GameObject has the Player Movement script attached.
2. **Components**:
   - `CharacterController`: Required for player movement.

### CameraHolder GameObject

1. **Attach Camera Control Script**: Ensure that the CameraHolder GameObject has the Camera Control script attached.
2. **Hierarchy**: The CameraHolder should be a child of the player GameObject to follow the player’s movement.

### Inspector Configuration

Configure the following in the Inspector for both the Player and CameraHolder GameObjects:
![Immagine 2024-06-10 135218](https://github.com/DeletedAccount2131/Unity-3D-Cam-and-Movement-Scripts/assets/170118559/280b0e08-b01a-4090-9a90-6d0925499adb)

#### Player GameObject

1. **CharacterController**: Add a CharacterController component if not already present.
2. **Player Movement Script**: Attach and configure the script settings as needed (e.g., speed, gravity).

#### CameraHolder GameObject

1. **Camera Control Script**: Attach and configure the script settings (e.g., sensitivity, offset).

  


![Immagine 2024-06-10 135302](https://github.com/DeletedAccount2131/Unity-3D-Cam-and-Movement-Scripts/assets/170118559/c459db92-6148-4df6-8d20-e86ae94eac71)
![Immagine 2024-06-10 135246](https://github.com/DeletedAccount2131/Unity-3D-Cam-and-Movement-Scripts/assets/170118559/f727c671-b047-4f37-b173-dfe667a90c41)





![Immagine 2024-06-10 135432](https://github.com/DeletedAccount2131/Unity-3D-Cam-and-Movement-Scripts/assets/170118559/a1dee670-4f67-4bc9-95ae-47fc8e185175)
![Immagine 2024-06-10 135409](https://github.com/DeletedAccount2131/Unity-3D-Cam-and-Movement-Scripts/assets/170118559/0330db89-a09f-4b42-b5d6-d43b610d19d1)
![Immagine 2024-06-10 135350](https://github.com/DeletedAccount2131/Unity-3D-Cam-and-Movement-Scripts/assets/170118559/d2b21771-3183-4e65-9ca8-59d1f18a6d4c)



