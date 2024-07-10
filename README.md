# Ins-PedSwap

Ins-PedSwap is a versatile and easy-to-use script for FiveM servers that allows players to switch their character models by simply typing a command. Whether you want to switch to a default GTA character or a custom add-on ped, Ins-PedSwap makes it easy and seamless.

## Features

- **Simple Command**: Change your ped model by typing `/ped PedName` in the chat.
- **Compatibility**: Works with both default GTA and custom add-on peds.
- **Standalone**: Compatible with standalone servers.
- **Easy to Install**: Quick setup with minimal configuration required.

## Installation

1. **Download the Script:**
   - Clone or download this repository to your local machine.

2. **Add to Your Server:**
   - Place the `ins-pedswap` folder into your server's `resources` directory.

3. **Add to `server.cfg`:**
   - Open your `server.cfg` file and add the following line:
     ```plaintext
     start ins-pedswap
     ```

4. **Ensure Add-on Peds Are Loaded:**
   - If you're using custom add-on peds, make sure they are correctly installed in your server's `resources` directory and started in the `server.cfg`.

## Usage

- To change your ped, simply type the following command in the chat:
  ```plaintext
  /ped PedName
