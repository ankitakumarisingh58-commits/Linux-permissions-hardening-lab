# Linux Permissions and Hardening Lab Report

## 1. Aim

To practise Linux users, groups, file permissions, firewall settings, and SSH security in a virtual machine.

## 2. Environment

* Virtual Machine: To be specified
* Linux Distribution: To be specified
* Terminal: Linux shell

## 3. User and Group Management

Commands:

```bash
whoami
id
groups
```

Purpose:

* `whoami` displays the current username.
* `id` displays user and group IDs.
* `groups` displays group membership.

## 4. File Permissions

Commands:

```bash
touch labfile.txt
ls -l labfile.txt
chmod 640 labfile.txt
ls -l labfile.txt
```

Result:
The commands create a file, display its permissions, change its permissions, and display the updated permissions.

## 5. Firewall Review

For Ubuntu systems using UFW:

```bash
sudo ufw status verbose
```

Purpose:
Displays the firewall status and rules.

## 6. SSH Security Review

Check SSH service status:

```bash
systemctl status ssh
```

On some distributions, the service may be named `sshd` instead.

Review SSH configuration:

```bash
sudo sshd -T
```

Purpose:
Checks the effective SSH server configuration, if the SSH server is installed.

## 7. Results

Record the actual output of each command after running it in the Linux virtual machine.

## 8. Conclusion

This lab introduces Linux user and group management, file permissions, firewall review, and SSH configuration review.

**Note:** Commands and results must be verified in the user's own virtual machine before submission.
