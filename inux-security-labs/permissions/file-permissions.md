# Linux File Permissions

## Overview

Linux uses a permission model based on:

- owner
- group
- others

Permissions determine who can:

- read
- write
- execute

---

## Viewing Permissions

```bash
ls -l
```

Example:

```
-rwxr-xr-- 1 user user 4096 file.sh
```

Meaning:

```
owner: read write execute
group: read execute
others: read
```

---

## Changing Permissions

Add execute permission:

```bash
chmod +x script.sh
```

Set specific permissions:

```bash
chmod 755 script.sh
```

Meaning:

```
7 = read write execute
5 = read execute
5 = read execute
```

---

## Security Considerations

Avoid:

```
chmod 777
```

because it allows **everyone full access**.

Proper permissions reduce the risk of:

- unauthorized modification
- privilege escalation
- accidental deletion
