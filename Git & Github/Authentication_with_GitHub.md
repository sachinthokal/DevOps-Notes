# Generate SSH Key (Optional, for Authentication with GitHub)

Generate an SSH key:

```bash

ssh-keygen -t rsa -b 4096 -C "your.email@example.com"

```

When prompted, press Enter to use the default file location.


```bash

cat ~/.ssh/id_rsa.pub

```

Copy the SSH key to your clipboard and add to GitHub


# Add the SSH key to your GitHub account under Settings > SSH and GPG Keys.
