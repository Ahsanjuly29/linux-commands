Here’s a revised version of your README with more engaging and seductive icons for a better visual appeal:

---

# 🌟 Change Hostname on Ubuntu (No Reboot Required)

## 🖥️ Change the Hostname

To change your system's hostname, use:

```bash
$ hostnamectl set-hostname new-hostname
$ hostnamectl
```

---

## ✨ Change the Pretty Hostname

Set a user-friendly display name:

```bash
$ hostnamectl set-hostname "new-hostname" --pretty
```

---

## 🔧 Open XAMPP in Linux

Launch the XAMPP manager:

```bash
$ sudo /opt/lampp/./manager-linux-x64.run
```

---

## 🔍 Check MySQL Port

To see which port MySQL is running on:

```bash
$ netstat -tlnp
```

---

## 🔑 Reset Root Password Using Bash

1. **Open Bash as Root:**
   ```bash
   $ sudo bash
   ```

2. **Change Root Password:**
   ```bash
   $ passwd root
   ```

---

## 🔄 Reset MySQL Password on Linux

Reset the MySQL root password:

```bash
$ sudo mysql -u root
USE mysql;
SELECT user, plugin FROM user;
UPDATE user SET plugin = "mysql_native_password" WHERE user = "root";
EXIT;
```

Then restart MySQL:

```bash
$ service mysql restart
```

---

## 📥 Access MySQL in Terminal

1. **With Password:**
   ```bash
   $ mysql -u root -p
   ```

2. **Without Password:**
   ```bash
   $ mysql -u root
   ```

---

This version uses engaging icons to make each section visually appealing. Let me know if you have specific icons in mind or any other adjustments you'd like!
