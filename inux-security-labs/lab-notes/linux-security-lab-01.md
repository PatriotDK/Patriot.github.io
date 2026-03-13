# Linux Security Lab 01 – System Enumeration

## Objective

Understand the basic information available about a Linux system and how it can be enumerated.

---

## System Identification

Check kernel version:

```bash
uname -a
```

Example output:

```
Linux kali 6.x.x-amd64 #1 SMP Debian
```

Purpose:

- Identify kernel version
- Identify architecture
- Identify potential outdated kernels

---

## Distribution Information

```bash
lsb_release -a
```

or

```bash
cat /etc/os-release
```

Purpose:

- Identify operating system
- Determine patch and update status

---

## User Identification

```bash
whoami
id
```

Example:

```
uid=1000(alexander) gid=1000(alexander)
```

Purpose:

- Identify privilege level
- Check group membership

---

## Hostname

```bash
hostname
```

Useful for identifying:

- system role
- network naming conventions

---

## Installed Software

```bash
dpkg -l
```

or

```bash
apt list --installed
```

Purpose:

- detect unnecessary services
- identify vulnerable packages

---

## Key Learning Points

System enumeration reveals:

- system identity
- user privileges
- installed software
- potential attack surface
