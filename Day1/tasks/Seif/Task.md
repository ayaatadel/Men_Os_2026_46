# SSH vs HTTPS (GitHub)

**SSH**
- Authentication: uses SSH keys, no password needed
- Security: encrypted and secure
- Convenience: no repeated login once set up
- Setup: generate and add SSH key to GitHub
- Use case: ideal for frequent contributors
- Clone example: git@github.com:user/repo.git

**HTTPS**
- Authentication: uses username + token/password
- Security: encrypted
- Convenience: must enter token/password often
- Setup: works out-of-the-box
- Use case: good for occasional access
- Clone example: https://github.com/user/repo.git

**Summary:**  
SSH = fast, secure, no password prompts  
HTTPS = simple setup, may require token/password every push

