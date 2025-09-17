# Starting with Git – Mastering Git collaboration and version control

---

## 1.	Setting up the Environment

I have set up my own Linux environment in my Windows system using WSL and have installed git using the package manager:

```bash
sudo apt install git
git –version
```

---

## 2.	Setting up Git, GitHub and GitLab accounts for collaboration.

I have created created two GutHub accounts (I had a pre-existing one and created a new one) to simulate code reviews and merging changes, and have setup Personal Access
Token (PAT) for secure access.
I have also created a GitLab account, created a new repo, also forked an existing one and set up SSH authentication for GitLab:

```bash
ssh-keygen -t rsa -b 4096 -C "your.email@example.com"
ssh-add ~/.ssh/id_rsa
```

The above command cretes the pair of private and public in the `~/.ssh` directory and we copy the public key into the key generation section in GitLab

But merely typing these commands might not work as the terminal will not enable the ssh connection required for connecting to GitLab

<img width="1258" height="509" alt="Image" src="https://github.com/user-attachments/assets/c348a9e4-4a91-472a-b42a-7fbad18c9325" />
