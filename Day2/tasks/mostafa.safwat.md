🔑 What is an SSH key (with GitHub)?

An SSH key lets you connect to GitHub securely without typing your username/password every time you push or pull code.

## first generate your key

`ssh-keygen -t ed25519 -C "mostafa.safwat.is.fcai@gmail.com"`

## 2- Copy it;

    `cat ~/.ssh/id_ed25519.pub`
    ->> ssh-ed25519 ############################+#######/####### mostafa.safwat.is.fcai@gmail.com

## 3- Add key to GitHub

1- Settings → SSH and GPG keys

2- New SSH key

3- Paste the key

4- Save

## 4- testing

    `ssh -T git@github.com `
