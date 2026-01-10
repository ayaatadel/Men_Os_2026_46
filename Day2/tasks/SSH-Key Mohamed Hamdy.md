# SSH-Key: is a method to link my machine to the github in secure than https. 

## SSH-Key consists of 'private key' stored on the machine & 'public key' stored on the github.

### How to generate SHH-Key -> ssh-keygen -t ed25519 -C "mohamed135hamdy@gmail.com"
### To show the generated publi key -> cat ~/.ssh/id_ed25519.pub
### the generated Public key is: `ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAID5+DVM+7cKPiHp6RdpjNR1QZdHtItojIf+ymUv9+tlA mohamed135hamdy@example.com`
### To test the the connection -> ssh -T git@github.com