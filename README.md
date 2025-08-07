<h1 align="center">
  🐍 GoPhish Installation Guide on Kali Linux
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Tested%20On-Kali%20Linux%202025.x-purple?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Purpose-Education%20Only-blue?style=for-the-badge" />
</p>

---

## 📌 What is GoPhish?

[**GoPhish**](https://github.com/gophish/gophish) is an open-source phishing simulation framework that helps security teams train and test their organization's resilience against phishing attacks.

This guide helps you install and run GoPhish **from scratch** on **Kali Linux**, the preferred OS for penetration testers and cybersecurity learners.

> ⚠️ **Legal Warning**: This tool must only be used in authorized environments for educational or ethical purposes. Unauthorized use is illegal.

---

## 🧠 Requirements

- ✅ Kali Linux (VM or Host)
- ✅ Internet connection
- ✅ Basic Linux terminal knowledge
- ✅ `wget` and `unzip` packages (usually pre-installed)

---

## ⚙️ Step-by-Step Installation (A to Z)

## ✅ Note

You can always check for the **latest version of GoPhish** here:  
🔗 [https://github.com/gophish/gophish/releases](https://github.com/gophish/gophish/releases)

---

## 📦 Step-by-Step Installation

```bash
# Step 1: Download GoPhish
cd ~
wget https://github.com/gophish/gophish/releases/download/v0.12.1/gophish-v0.12.1-linux-64bit.zip

# Step 2: Unzip the Archive
unzip gophish-v0.12.1-linux-64bit.zip
cd gophish-v0.12.1-linux-64bit

# Step 3: Make the binary executable
chmod +x gophish

# Step 4: Start GoPhish
./gophish
```

📍 **By default**, GoPhish runs on:

- 🌐 Web UI: [https://localhost:3333](https://localhost:3333)
- 🎯 Phishing Server: [http://localhost:80](http://localhost:80)

✅ **Admin Login (default):**

- **Username**: `admin`  
- **Password**: *(shown in terminal on first run)*

---

## 🌐 Access Web Interface

1. Open your browser and go to 👉 **https://localhost:3333**
2. ⚠️ You’ll see a browser warning (self-signed SSL certificate). Click **"Advanced" → "Proceed"**
3. Login using the default credentials above

---

## 🔧 Configure GoPhish

Once you're logged in, you can:

- 📤 Create Email Templates  
- 🎯 Add Targets & Groups  
- 📅 Schedule Campaigns  
- 🧪 Run Simulations  
- 📊 View Real-Time Results  

---

## 🛠 Optional: Change Admin Credentials

After your first login, go to:  
`Settings → Change Password`  
to secure your GoPhish admin panel.

---

## 🧼 Optional: Remove GoPhish

If you want to clean up GoPhish from your system:

```bash
cd ~
rm -rf gophish-v0.12.1-linux-64bit gophish-v0.12.1-linux-64bit.zip
```

---

## 🧠 Tips & Notes

- 🔐 Use in a **test lab only**, never on real users or public networks.
- 🛡️ Always get permission before testing.
- 📥 Backup your GoPhish data if running long-term.
- 🔄 Edit `config.json` to change ports, SSL, etc.

---

## 📚 Learn More

- 📖 [GoPhish Documentation](https://docs.getgophish.com/)
- 🧪 [Kali Linux Tools](https://tools.kali.org/)
- 🎥 [Coding Chat Room YouTube](https://www.youtube.com/@CodingChatRoom)

---

## ⚠️ Legal & Ethical Notice

This project is **only for educational and ethical penetration testing**.

❌ Do **NOT** use it on real people, websites, or companies without **explicit permission**.  
✅ Do **USE** it in:

- Labs  
- Testing Environments  
- Cybersecurity Training  
