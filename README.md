# ethstorage-ceremony-guide
# EthStorage V1 Trusted Ceremony Setup Guide

## Prerequisites

Before participating in the ceremony, ensure your GitHub account meets these requirements:

- **Account Age**: Minimum 1 month old
- **Repositories**: At least 1 repository
- **Following**: Following 5+ users
- **Followers**: At least 1 follower

## Setup Instructions

### Step 1: Initial Setup

Run the following command to download and execute the setup script:

```bash
wget https://raw.githubusercontent.com/ezlabsnodes/autoinstall/main/setup-eth-storage.sh && chmod +x setup-eth-storage.sh && sudo ./setup-eth-storage.sh
```

After running the script:

1. Navigate to http://github.com/login/device in your browser
2. Authenticate with your GitHub account
3. Copy the authentication code from the terminal when prompted

### Step 2: Create Screen Session

Create a new screen session for the ceremony:

```bash
screen -S ceremony
```

### Step 3: Contribute to Ceremony

Start the contribution process:

```bash
phase2cli contribute
```

Follow these steps in the interactive menu:

1. Use arrow keys to select the **second option**: "EthStorage V1 Trusted Setup Ceremony"
2. Press **ENTER**
3. Select "Randomly" when prompted
4. Press **ENTER**
5. Wait for completion

## Screen Session Management

- **Minimize/Detach session**: `Ctrl + A + D`
- **Reattach to session**: `screen -r ceremony`

## Completion

Once all steps are completed successfully, your participation in the EthStorage V1 Trusted Ceremony will be registered.

---

*Guide based on instructions from FasoNodez*
