# Troubleshooting Notes

## Issue 1: Apache Default Page Showing

### Problem
Apache default page was appearing instead of WordPress.

### Root Cause
index.html existed in /var/www/html.

### Solution

```bash
sudo rm /var/www/html/index.html
```

---

## Issue 2: Database Connection Error

### Problem
WordPress could not connect to MariaDB.

### Root Cause
Duplicate DB configuration entries in wp-config.php.

### Solution
Removed placeholder DB configuration values.
