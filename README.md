# Welcome to your organization's demo respository
This code repository (or "repo") is designed to demonstrate the best GitHub has to offer with the least amount of noise.

The repo includes an `index.html` file (so it can render a web page), two GitHub Actions workflows, and a CSS stylesheet dependency.

## SSH Keys

### Generating an SSH Key

To generate an SSH key, open a terminal and run the following command:

```
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
```

This will create a new SSH key, using the provided email as a label. You will be prompted to enter a file in which to save the key, and then to enter a passphrase.

### Adding the SSH Key to GitHub

To add the SSH key to your GitHub account, follow these steps:

1. Copy the SSH key to your clipboard by running the following command:

```
pbcopy < ~/.ssh/id_rsa.pub
```

2. Go to GitHub and navigate to **Settings** > **SSH and GPG keys** > **New SSH key**.
3. Paste your key into the "Key" field and add a descriptive title.
4. Click **Add SSH key**.
