# apache\_config\_notes.md

## Apache Configuration Notes for Static Site Hosting

---

### 📁 Default Web Root Directory

Apache serves files from:

```
/var/www/html/
```

Any static files placed here will be publicly accessible.

---

### 🔀 Overwriting Default Page

To replace the default Apache landing page:

```bash
sudo rm /var/www/html/index.html
sudo cp /path/to/exported_site/* /var/www/html/
```

Make sure your custom `index.html` is copied.

---

