# Linux User Management: Essential Commands

## 1. Root User: The Ultimate Power

### What is the Root User?
The root user is the superuser with the highest permissions in the system, capable of installing or removing software, managing users, and changing system settings.

- **Important:** Avoid using root for everyday tasks due to security risks.

---

## 2. The `su` Command: Switching Users

### Switching to Root
```bash
su
```
- Enter the root password to switch to root.

### Switching to Another User
```bash
su <username>
```
- Example:
  ```bash
  su alice
  ```

### Exit `su`
```bash
exit
```
- Switch back to the original user.

---

## 3. The `sudo su` Command: Gaining Root Privileges

### Switch to Root Using Sudo
```bash
sudo su
```
- No need for the root password, just the user’s sudo password.

### Switch to Another User with Sudo
```bash
sudo su <username>
```
- Example:
  ```bash
  sudo su alice
  ```

---

## 4. Adding a New User with `useradd`

### Create a New User with Home Directory
```bash
sudo useradd -m <username>
```
- Example:
  ```bash
  sudo useradd -m john
  ```

---

## 5. Managing Passwords with `passwd`

### Set Password for New User
```bash
sudo passwd <username>
```
- Example:
  ```bash
  sudo passwd john
  ```

### Change Your Own Password
```bash
passwd
```

---

## 6. Viewing the `/etc/passwd` File

### Format of `/etc/passwd`
```plaintext
username:x:UID:GID:comment:home_directory:shell
```

### View `/etc/passwd` Contents
```bash
cat /etc/passwd
```

---

## 7. Managing Groups with `groupadd` and `gpasswd`

### Create a New Group
```bash
sudo groupadd <groupname>
```
- Example:
  ```bash
  sudo groupadd developers
  ```

### Add a User to a Group
```bash
sudo gpasswd -a <username> <groupname>
```
- Example:
  ```bash
  sudo gpasswd -a john developers
  ```

---

## 8. Viewing the `/etc/group` File

### Format of `/etc/group`
```plaintext
group_name:x:GID:user_list
```

### View `/etc/group` Contents
```bash
cat /etc/group
```

---

By mastering these commands, you’ll have a solid foundation for user and group management in Linux.
