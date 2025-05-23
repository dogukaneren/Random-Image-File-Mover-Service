# 📂 Random Image Sender Service

This is a lightweight `systemd` service that periodically moves `.jpg` image files from a source directory to a destination directory.  
It supports both **fixed interval and count** or a fully **randomized mode**.

---

## 📄 Files

- `random-image-sender.sh` — Bash script that performs the file moving
- `random-image-sender.service` — systemd service definition

---

## ⚙️ Installation

1. **Copy the script to a safe location:**

```bash
sudo cp random-image-sender.sh /usr/local/bin/
sudo chmod +x /usr/local/bin/random-image-sender.sh
