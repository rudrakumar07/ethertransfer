# EtherTransfer - Direct Ethernet File Transfer

**Developer: Rudra Kumar**  
**Copyright © 2025 Rudra Kumar. All rights reserved.**

Fast and simple file transfer between two laptops connected directly via Ethernet cable. No internet, no router, no complicated setup required.

---

## ✨ Features

- **Zero Configuration**: Automatically sets up network connection
- **Fast Transfer**: Direct cable connection for maximum speed
- **File Compression**: Optional compression to save time on large files
- **File Verification**: SHA256 hash checking ensures files arrive intact
- **Modern GUI**: Clean, intuitive interface with dark/light themes
- **Peer Discovery**: Automatically finds the other computer
- **Progress Tracking**: Real-time transfer speed and progress
- **Multiple Files**: Send multiple files in one go

---

## 📋 Requirements

- **Windows 10/11** (64-bit)
- **Ethernet cable** connecting two laptops
- **Administrator privileges** (for network setup)

---

## 🚀 Quick Start

### Step 1: Connect the Computers
1. Connect both laptops directly with an Ethernet cable
2. No router or switch needed - direct cable connection

### Step 2: Run the Application
1. Download `EtherTransfer.exe`
2. Right-click and select **"Run as Administrator"**
3. If Windows SmartScreen appears, click "More info" → "Run anyway"

### Step 3: Set Up Network
1. Click **"Setup Network"** button
2. Wait for automatic configuration (takes 10-15 seconds)
3. Status will show "Connected" when ready

### Step 4: Transfer Files

**On the Sending Computer:**
1. Go to the **"Send"** tab
2. Click **"Select Files"** and choose files to send
3. Click **"Send to Peer"**
4. Wait for transfer to complete

**On the Receiving Computer:**
1. Go to the **"Receive"** tab
2. Files will be received automatically
3. Find received files in the `received` folder

---

## 💡 Tips & Troubleshooting

### Transfer Not Working?
- **Check the cable**: Make sure it's fully plugged in at both ends
- **Run as Administrator**: Both computers must run the app as admin
- **Check firewall**: Windows may ask to allow the app - click "Allow"
- **Wait for setup**: Give the network setup 10-15 seconds to complete

### Slow Transfer Speed?
- **Disable compression** for small files or already-compressed files (videos, zips)
- **Enable compression** for large text files, documents, or code
- **Check cable quality**: Use a good quality Ethernet cable (Cat5e or better)

### Connection Lost?
- Click **"Teardown Network"** on both computers
- Click **"Setup Network"** again
- Wait for connection to re-establish

### Files Not Appearing?
- Check the `received` folder in the same location as the EtherTransfer.exe
- Make sure both computers completed the network setup
- Verify the sender clicked "Send to Peer" and transfer completed

---

## ⚙️ Settings

### Theme
- **Dark Mode**: Easy on the eyes
- **Light Mode**: For bright environments

### Compression
- **Enable**: Best for documents, text files, code
- **Disable**: Best for videos, images, already-compressed files

### Transfer History
- View past transfers in the History tab
- See file names, sizes, and transfer times

---

## 🔒 Security & Privacy

- **No Internet Required**: Files never leave your local network
- **No Cloud Upload**: Everything stays between the two computers
- **No Data Collection**: The app doesn't collect or send any data
- **Offline Operation**: Works completely offline

---

## 📊 Technical Details

- **Transfer Protocol**: HTTP with multipart form-data
- **Compression**: gzip compression (optional)
- **Verification**: SHA256 hash checking
- **IP Assignment**: Automatic static IP (192.168.10.1 and 192.168.10.2)
- **Discovery**: UDP broadcast on port 37020
- **Transfer Port**: HTTP server on port 8080

---

## ❓ FAQ

**Q: Do I need internet?**  
A: No, works completely offline with just an Ethernet cable.

**Q: Can I transfer folders?**  
A: Yes, select multiple files or all files in a folder.

**Q: What's the maximum file size?**  
A: No hard limit, but very large files (50GB+) may take time.

**Q: Can I use a crossover cable?**  
A: Modern network cards auto-detect, so any Ethernet cable works.

**Q: Does it work on Mac or Linux?**  
A: Currently Windows only (Windows 10/11).

**Q: Is it safe to use?**  
A: Yes, all transfers are local between the two computers only.

---

## 📞 Support

If you encounter any issues:
1. Check the troubleshooting section above
2. Make sure both computers are running as administrator
3. Verify the Ethernet cable is properly connected
4. Try restarting the application on both computers

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Copyright © 2025 Rudra Kumar.

---

**Made with ❤️ by Rudra Kumar**
