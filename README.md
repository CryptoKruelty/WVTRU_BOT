# VTRU Bot v3.5

**VTRU Bot** is a powerful and user-friendly application designed to interact with the Vitruveo blockchain. It allows users to manage multiple wallets, monitor blockchain blocks, and execute transactions automatically based on predefined conditions.

---

## Table of Contents

- [Usage](#usage)
- [Managing Private Keys](#managing-private-keys)
- [Logging and Error Handling](#logging-and-error-handling)
- [Disclaimer](#disclaimer)
- [Happy Wrapping!](#happy-wrapping)

---

## Usage

### Main Interface

Upon launching the application, you'll be presented with the main interface, which includes the following components:

- **Current Block:** Displays the latest block number on the Vitruveo blockchain.
- **Epoch Block:** Shows the target block number for executing transactions.
- **Remaining Blocks:** Indicates how many blocks are left until the epoch block.
- **Time Remaining:** Estimates the time left until the epoch block is reached.
- **Loaded Wallets:** Shows the number of wallets currently loaded.

### Controls

- **Start Monitoring:** Begins monitoring the blockchain for new blocks. Click this button to initiate the monitoring process based on your configured parameters.

- **Stop Monitoring:** Stops the ongoing monitoring process. This button becomes active once monitoring has started.

- **Load Keys:** Opens the dialog to manage your private keys. Use this to add, edit, or delete your Vitruveo wallet keys.

### Configurable Parameters

Adjust the following parameters to suit your transaction needs:

- **Gas Price (Gwei):** Set the gas price for transactions. Enter your desired value in Gwei (e.g., `4`).

- **Gas Limit:** Define the gas limit for transactions. Enter the appropriate value (e.g., `151000`).

- **Value (VTRU):** Specify the amount of VTRU tokens to wrap. Enter the desired amount (e.g., `99`).

### Console Output

Real-time logs and transaction details are displayed in the console section of the GUI. This helps in monitoring the application's operations and debugging if necessary.

---

## Managing Private Keys

### Adding a Private Key

1. Click on the **"Load Keys"** button.
2. In the **Manage Private Keys** dialog, click **"Add Key"**.
3. Enter your private key in the prompt and confirm.

### Editing a Private Key

1. Select the key from the list.
2. Click **"Edit Key"**.
3. Modify the key in the prompt and confirm.

### Deleting a Private Key

1. Select the key from the list.
2. Click **"Delete Key"** to remove it.

> **⚠️ Security Warning:** Always ensure your private keys are handled securely. Do not share your private keys with anyone and consider using hardware wallets or secure storage solutions.

---

## Logging and Error Handling

- **Console Output:** The application displays real-time logs in the console section of the GUI for monitoring and debugging purposes.
- **Error Logs:** Errors are appended to an `errors.txt` file with timestamps. This helps in tracking issues and facilitating easier debugging.

---

## Disclaimer

**Use at Your Own Risk:** This application interacts with the Vitruveo blockchain and manages private keys. Ensure you understand the risks involved, including potential loss of funds. The developer is not responsible for any damages or losses resulting from the use of this software.

---

## Happy Wrapping!

Thank you for using **VTRU Bot**! May your transactions be swift and your blocks be few. 🎉

---
